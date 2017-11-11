# Snapshot report for `template/test/web/contact.js`

The actual snapshot is saved in `contact.js.snap`.

Generated by [AVA](https://ava.li).

## fails creating inquiry if last inquiry was within last 24 hours (HTML)

> Snapshot 1

    `<!DOCTYPE html>␊
    <html lang="en">␊
      <head>␊
        <meta charset="utf-8">␊
        <meta http-equiv="x-ua-compatible" content="ie=edge">␊
        <title>Bad Request</title>␊
        <meta name="description" content="You have reached the limit for sending contact requests.  Please try again.">␊
        <meta name="viewport" content="width=device-width, initial-scale=1">␊
        <link rel="alternate" href="http://localhost:3000" hreflang="x-default">␊
        <link rel="alternate" href="http://localhost:3000/zh" hreflang="zh">␊
        <link rel="alternate" href="http://localhost:3000/en" hreflang="en">␊
        <link rel="alternate" href="http://localhost:3000/es" hreflang="es">␊
        <link rel="apple-touch-icon" sizes="152x152" href="/img/apple-touch-icon.png">␊
        <link rel="icon" type="image/png" href="/img/favicon-32x32.png" sizes="32x32">␊
        <link rel="icon" type="image/png" href="/img/favicon-16x16.png" sizes="16x16">␊
        <link rel="manifest" href="/manifest.json">␊
        <meta name="apple-mobile-web-app-title" content="Lad">␊
        <meta name="application-name" content="Lad">␊
        <meta name="theme-color">␊
        <meta name="csrf-token">␊
        <script>window._csrf = "";</script>␊
        <!--.␊
        <link rel="image_src" type="image/png" href="https://stripe.com/img/v3/home/social.png">␊
        <meta property="og:title" content="Checkout Reference">␊
        <meta property="og:url" content="https://stripe.com/docs/checkout">␊
        <meta property="og:description" content="Stripe is a suite of APIs that powers commerce for businesses of all sizes.">␊
        <meta property="og:image" content="https://stripe.com/img/v3/home/social.png">␊
        <meta name="twitter:card" content="summary_large_image">␊
        <meta name="twitter:site" content="@stripe">␊
        <meta name="twitter:title" content="Checkout Reference">␊
        <meta name="twitter:description" content="Stripe is a suite of APIs that powers commerce for businesses of all sizes.">␊
        <meta name="twitter:image:src" content="https://stripe.com/img/v3/home/social.png">␊
        -->␊
        <link rel="stylesheet" href="/css/app.css">␊
      </head>␊
      <body role="document">␊
        <div class="fixed-top fade" id="spinner">␊
          <div class="sk-fading-circle">␊
            <div class="sk-circle1 sk-circle"></div>␊
            <div class="sk-circle2 sk-circle"></div>␊
            <div class="sk-circle3 sk-circle"></div>␊
            <div class="sk-circle4 sk-circle"></div>␊
            <div class="sk-circle5 sk-circle"></div>␊
            <div class="sk-circle6 sk-circle"></div>␊
            <div class="sk-circle7 sk-circle"></div>␊
            <div class="sk-circle8 sk-circle"></div>␊
            <div class="sk-circle9 sk-circle"></div>␊
            <div class="sk-circle10 sk-circle"></div>␊
            <div class="sk-circle11 sk-circle"></div>␊
            <div class="sk-circle12 sk-circle"></div>␊
          </div>␊
        </div><!--[if lt IE 9]>␊
    <p class="browserupgrade">You are using an <strong>outdated</strong> browser. Please <a href="http://browsehappy.com/">upgrade your browser</a> to improve your experience.</p>␊
    <![endif]-->␊
        <nav class="navbar navbar-expand-md fixed-top navbar-dark bg-dark">␊
          <button class="navbar-toggler navbar-toggler-right bg-dark hidden-lg-up" type="button" data-toggle="collapse" data-target="#navbar-header" aria-controls="navbar-header" aria-expanded="false" aria-label="Toggle navigation"><span class="navbar-toggler-icon"></span></button><a class="navbar-brand" href="/en">Lad</a>␊
          <div class="collapse navbar-collapse" id="navbar-header">␊
            <ul class="navbar-nav ml-auto">␊
              <li class="nav-item"><a class="nav-link" href="/en/about">About</a></li>␊
              <li class="nav-item dropdown"><a class="nav-link dropdown-toggle" id="navbar-dropdown-more-links" href="#" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false"><i class="fa fa-fw fa-life-ring"></i> Help</a>␊
                <ul class="dropdown-menu" aria-labelledby="navbar-dropdown-more-links">␊
                  <li><a class="dropdown-item" target="_blank" href="http://slack.crocodilejs.com"><i class="fa fa-fw fa-slack"></i> Chat</a></li>␊
                  <li><a class="dropdown-item" target="_blank" href="https://ladjs.github.io/lad"><i class="fa fa-fw fa-book"></i> Docs</a></li>␊
                  <li><a class="dropdown-item" target="_blank" href="https://github.com/ladjs/lad"><i class="fa fa-fw fa-github"></i> GitHub</a></li>␊
                  <li><a class="dropdown-item" target="_blank" href="https://twitter.com/niftylettuce"><i class="fa fa-fw fa-twitter"></i> Twitter</a></li>␊
                  <li><a class="dropdown-item" href="/en/contact"><i class="fa fa-fw fa-envelope"></i> Contact</a></li>␊
                </ul>␊
              </li>␊
              <li class="nav-item dropdown"><a class="nav-link dropdown-toggle" id="navbar-dropdown-language" href="#" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false"><i class="fa fa-fw fa-language"></i> English</a>␊
                <ul class="dropdown-menu" aria-labelledby="navbar-dropdown-language">␊
                  <li><a class="dropdown-item" href="/zh/contact">Chinese</a></li>␊
                  <li><a class="dropdown-item" href="/es/contact">Spanish</a></li>␊
                </ul>␊
              </li>␊
              <li class="nav-item"><a class="nav-link" href="/en/login"><i class="fa fa-fw fa-sign-in"></i> Log in</a></li>␊
              <li class="nav-item"><a class="nav-link" href="/en/signup"><i class="fa fa-fw fa-user-plus"></i> Sign up</a></li>␊
            </ul>␊
          </div>␊
        </nav>␊
        <div class="jumbotron pb-3">␊
          <div class="container">␊
            <h1 class="display-3">Server Error</h1>␊
            <p class="lead text-muted">A server error has unfortunately occurred.  If this error persists, please contact us.</p>␊
          </div>␊
        </div>␊
        <footer class="footer">␊
          <div class="container text-center"><small class="text-muted">␊
              <ul class="m-0 p-0">␊
                <li class="d-inline">&copy; 2017 Lad␊
                </li>␊
                <li class="d-inline">All Rights Reserved.</li>␊
                <li class="d-inline"><a href="/terms">Terms</a></li>␊
              </ul></small></div>␊
        </footer>␊
        <script>␊
          window._types = {␊
            success: "Success",␊
            error: "Error",␊
            info: "Info",␊
            warning: "Warning",␊
            question: "Question"␊
          };␊
          window._messages = {"success":[],"error":["You have reached the limit for sending contact requests.  Please try again."],"info":[],"warning":[],"question":[]};␊
          window._swalDefaults = {␊
            confirmButtonText: "OK",␊
            cancelButtonText: "Cancel",␊
            closeButtonAriaLabel: "Close this dialog"␊
          };␊
        </script>␊
        <script src="/js/core.js"></script>␊
        <script src="/js/flash.js"></script>␊
      </body>␊
    </html>`