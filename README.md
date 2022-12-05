# Test project to run egui in Tauri

This is the result of combining
- https://github.com/emilk/eframe_template and
- https://github.com/tauri-apps/create-tauri-app/tree/dev/packages/cli/fragments/fragment-yew

Prerequisites:
```
cargo install tauri-cli
cargo install trunk
rustup target add wasm32-unknown-unknown
``` 

Try it out with
```
cargo tauri dev
``` 