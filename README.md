#js version png compression tool
---
   - 2021.10.14 Add jpg image compression
   - 2021.10.19 Add GIF image compression
   - 2022.01.06 Add demo address
---
## use

Just deploy the web folder to the server for access (needs to be accessed from a browser that supports webassembly, such as Chrome, edge)

You can visit [demo](https://h5.skyfish.me/pngtiny/)

## illustrate

- This project uses https://github.com/ImageOptim/libimagequant, https://github.com/glennrp/libpng, https://github.com/kohler/gifsicle and https://www.ijg.org /library
- libimagequant is a library that compresses png24 into png8, and the compression effect is very good. libpng is a library for reading and generating pngs. libjpeg is a library for reading and compressing jpg. gifsicle is a library for reading and compressing gifs.
- If you need to compile your own compression code, first install the new version of emsdk environment on your computer environment, and then run the build.bat file.
- Then overwrite the files in the web folder with the compiled pngtiny.js and pngtiny.wasm files.
