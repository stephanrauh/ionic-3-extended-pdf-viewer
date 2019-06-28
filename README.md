# ionic-3-extended-pdf-viewer

How to use ngx-extended-pdf-viewer with Ionic 3, which uses good old Angular 5?

Truth to tell, the compiler of both Angular and Ionic has changed too much to hope for compatiblity. Maybe it's possible to maintain compatibility widh Angular 5, but the price seems to be high. Among other things, there's a breaking change concerning the `ngOnChange()` method.

Of course, it should be possible to copy the few files of ngx-extended-pdf-viewer to your project. This project follows this approach.

However, there's a runtime error I wasn't able to fix yet. It seems a new polyfill is required - but Ionic 3 doesn't seem to make the polyfills configurable.

So this is unfinished work. I believe it's possible to compile ngx-extended-pdf-viewer with Ionic 3. However, in 2019 Ionic 3 is considered an old version - the current version being Ionic 5 - so I prefer not to dig into the topic deeper.

If you manage to complete my work, please tell me, so the greater audience of https://www.beyondjava.net and https://pdfviewer.net benefits from your success!
