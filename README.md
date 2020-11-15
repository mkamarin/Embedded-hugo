# Embedded hugo theme
Hugo theme for embedded micro-controllers

This [Hugo](https://gohugo.io/) theme is based on the [npq theme](https://themes.gohugo.io/npq-hugo/) with modifications to be hosted by embedded systems executing on micro-controllers like the ESP32, ESP8266, Arduino, etc.
Embedded systems are resource constrain, and so most of the modifications were to remove functionality and to minimize storage requirements.


## Features
- dark
- responsive
- avatar support
- table of content


## Installation & Update
After you have installed hugo (see [quick start](https://gohugo.io/getting-started/quick-start/)) run the following in your site's root directory to install the theme:

```sh
git clone https://github.com/mkamarin/Embedded-hugo.git
```
For more information, see [Hugo docs](https://gohugo.io/themes/installing/).
For upgrades, just do:

```sh
git submodule update --remote --merge
```
## Usage
1. Follow [Hugo's Quick Start](https://gohugo.io/getting-started/quick-start/) for the basic functionality. 
2. The only exception is that in [step 4](https://gohugo.io/getting-started/quick-start/#step-4-add-some-content) when creating content, you should use `hugo new pages/name.md` instead of `hugo new posts/my-first-post.md`.
3. For detailed instructions on how to deploy the resulting Hugo generated site to a micro-controller, see my post on simplifying web development for embedded systems.

### config.tom example 

```toml
TODO
```

In order to see your site updating while changing it, run Hugo's built-in local server.

```sh
hugo server 
```
or if your pages still draft use this instead:
```sh
hugo server -D
```

## License
GPLv3
