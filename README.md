# Email - Scratch-off Effect

Starter file for responsive email with scratch-off / click-to-reveal effects. Built to showcase the advanced capabilities of email for clients that are able to render the features, with fallback content for clients that do not. I followed the Email on Acid Guide [How to Create a “Scratch Off” Effect in Email HTML](https://www.emailonacid.com/blog/article/email-development/scratch-off-email/).

Intended result is to mimic the effect of a scratch off ticket on click. Fall back support is to show full revealed image on click. Support is for email clients that support the :checked selector as per Campaign Monitor support is as follows: https://www.campaignmonitor.com/css/selectors/checked/

The email showcased here was coded from scratch utilizing my email boilerplate framework (developed from Email on Acid and Litmus.com samples as a starting point). Email on Acid Tests passing in 44 popular mobile, web, and desktop email clients/devices as of August, 2021. All copyrights and trademarks remain property of their respective owners.

## Expected Results

Users should be able to:

_On Email Clients that Support :checked selector (iOS, Apple Mail, Thunderbird, Yahoo)_

- View a static **HERO IMAGE** that transitions to animated **HERO IMAGE** on click mimicking "scratch-off" effect

_On Email Clients that **DO NOT** Support :checked selector, but **DO** support animated GIF (Majority of email clients)_

- View animated **HERO IMAGE**

_On Email Clients that **DO NOT** Support :checked selector nor animated GIFs (Outlook 2007-2017)_

- View a static **HERO IMAGE**

_ALL CLIENTS_

- View a responsive layout depending on their device screen size & email client

## Email On Acid Test List

### Mobile

- Gmail App Pixel 2 (Android 9)
- Gmail App Pixel 3 (Android 10)
- Gmail App Pixel 4 (Android 11)

- iPhone11 (iOS 13)
- iPhone12 (iOS 13)
- iPhone13 (iOS 14)

### Desktop

- Apple Mail
- Outlook

### Web Clients

- Gmail (Chrome, Edge, FireFox)
- Office365 (Chrome, Edge, FireFox)
- Outlook.com (Chrome, Edge, FireFox)
- Yahoo (Chrome, Edge, FireFox)

## Screenshot

![screenshot](screenshot.png?raw=true)

## Links

- View Live Code: [https://ninjulia.github.io/email_scratchoff/](https://ninjulia.github.io/email_scratchoff/)

## Attributions

Coded with help from [Email on Acid Tutorial: Scratch Off](https://www.emailonacid.com/blog/article/email-development/scratch-off-email/). Email boilerplate coded by Julia Czarnecki with a lot of help from Litmus and Email on Acid. Any and all copyrighted material is property of the copyright owners. Placeholder logo image provided by [placeholder.com](https://placeholder.com/logos/), used under [Creative Commons License](https://creativecommons.org/).
