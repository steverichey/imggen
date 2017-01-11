# imggen

A shell script to create simple placeholder images.

# Usage

Create an image with 1024x512 resolution and save it as `some_image.png`.
```
imggen -s 1024x512 -o some_image
```

Shorthand to create a square image and save it as `out.png`.
```
imggen 256
```

Additional settings:
```
Usage: imggen [-s 256x512] [-o 10] [-p 16] [-sw 4] [-fs 24]
              [-fg white] [-bg orange] [-f Arial] [-t Placeholder]
              [-out out]
       imggen 256

Options:
  -h   --help          Print this help info and exit
  -s   --size          Set to width x height of desired output
  -o   --offset        Distance from inner box to edge of image
  -p   --plus          Width and height of center indicator
  -sw  --stroke-width  Width of stroke of all lines
  -fs  --font-size     Size of font
  -fg  --foreground    Color of text, square, center indicator
  -bg  --background    Color of background
  -f   --font          Name of font to use for text
  -t   --text          String to display over size information
  -out --out-file      Name of output file (no extension)
```

# License

&copy; 2017 [Steve Richey](https://github.com/steverichey). Shared under an [MIT license](https://en.wikipedia.org/wiki/MIT_License). See [license.md](./license.md) for details.
