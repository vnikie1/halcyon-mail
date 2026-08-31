# halcyon-mail

The small public site behind [Halcyon Mail](https://github.com/vnikie1/MailBox) — the privacy
policy and the security contact, at stable URLs.

It exists because the Microsoft Store requires a **live, publicly reachable privacy policy URL**
before a submission is accepted, and a dead link is an instant rejection. The application's source
lives in the other repository; this is only the pages that have to be on the open web.

| Page | URL |
|---|---|
| Home | https://vnikie1.github.io/halcyon-mail/ |
| Privacy policy | https://vnikie1.github.io/halcyon-mail/privacy.html |
| Security disclosure | https://vnikie1.github.io/halcyon-mail/security.html |

Plain HTML and one stylesheet. No framework, no build step, no fonts or scripts fetched from
anywhere — a required page that depends on three third-party things is a required page that
eventually breaks during certification. `.nojekyll` turns off GitHub's Jekyll pass, so what is
committed is exactly what is served.

The canonical text is `PRIVACY.md` and `SECURITY.md` in the application repository. When those
change, these change with them.
