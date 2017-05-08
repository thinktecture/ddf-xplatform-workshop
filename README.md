# Echtes Cross-Platform mit HTML5 und JavaScript

[.NET Day Franken](http://www.dotnet-day-franken.de/workshops/item/1-echtes-cross-platform-mit-html5-und-javascript-in-action), 12. Mai 2017, 09:00–17:00 Uhr, Le Méridien Grand Hotel Nürnberg.

Your trainers: [Christian Liebel](https://twitter.com/chris_liebel), [Manuel Rauber](https://twitter.com/ManuelRauber), Thinktecture AG, Karlsruhe.

## Setup

### Prerequisites

- [Node.js 6.10.3 LTS or higher](https://nodejs.org/en/)
- [Git](https://git-scm.com/) (recommended)
- Editor of your choice ([WebStorm](https://www.jetbrains.com/webstorm/), [Visual Studio Code](https://code.visualstudio.com/), …)
- Latest version of [Google Chrome](https://www.google.de/chrome/browser/desktop/)
- Laptop

### Mobile Devices
If you want to run the demo application on your mobile device as well, you need the native platform SDKs and/or IDEs for the target platform.

#### Windows

- Windows PC
- Microsoft Visual Studio
- Windows 10 SDK
- Windows Phone 8.1 SDK

#### iOS

- Mac
- Xcode

#### Android

- Android Studio

### Please try this at home

**NOTE:** Web technologies move fast and quickly. As there might be new releases in the meantime, we strictly recommend you to perform the following installation steps not earlier than one week before our workshop, as we might update the versions in this repository until then.

As Hotel WiFis tend to be unreliable, we kindly ask you to install the required third-party packages at home or any place with a stable internet connection. On your command line, please run:

```
npm uninstall -g angular-cli @angular/cli
npm cache clear
npm install -g @angular/cli@1.0.2
```

Next, navigate to a folder of your choice and execute:

```
git clone https://github.com/thinktecture/ddf-xplatform-workshop.git
cd ddf-xplatform-workshop
npm install   # or yarn (if installed)
```

Or, if you prefer SSH, use this checkout URL: `git@github.com:thinktecture/ddf-xplatform-workshop.git`
