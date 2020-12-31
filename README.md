# bevy_megaui_web_showcase

An example project running on [bevy_megaui](https://github.com/mvlabat/bevy_megaui).

Live at: https://mvlabat.github.io/bevy_megaui_web_showcase/index.html

## Running

Prerequisites:
- [wasm-pack](https://github.com/rustwasm/wasm-pack)
- [basic-http-server](https://github.com/brson/basic-http-server) (or any other http server to serve index.html)

```sh
wasm-pack build --target web --release
basic-http-server
```
