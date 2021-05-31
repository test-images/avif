# Output Results for Squoosh, AVIF, Lossy, Effort7, Chroma HALF

Squoosh uses [AOMediaCodec/libavif](https://github.com/GoogleChromeLabs/squoosh/tree/dev/codecs/avif/enc) in a WASM online app.

## Settings

Advanced Settings > log2 were both left at default `0`, **Subsample chroma: left HALF**.  Lossless left **off**, Quality left at `30`. Extra chroma compression left off (only saved a few bites).

[Source PNGs](https://test-images.github.io/png/202105/202105.html#pg)


## Output

#### [cs-gray-7f7f7f.avif](cs-gray-7f7f7f.avif)
![cs-gray-7f7f7f.avif](cs-gray-7f7f7f.avif "cs-gray-7f7f7f.avif test image")

#### [ia-forrest.avif](ia-forrest.avif)
![ia-forrest.avif](ia-forrest.avif "ia-forrest.avif test image")

#### [pg-coral.avif](pg-coral.avif)
![pg-coral.avif](pg-coral.avif "pg-coral.avif test image")

#### [web-jakearchibald.avif](web-jakearchibald.avif)
![web-jakearchibald.avif](web-jakearchibald.avif "web-jakearchibald.avif test image")


## Version

* Win10 i5-8300H
* Chrome 93.0.4528.0 (Official Build) canary (64-bit)
* [Squoosh.app](https://squoosh.app/) updated 2021-05-31
