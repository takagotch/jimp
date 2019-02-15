### jimp
---
https://github.com/oliver-moran/jimp

```js
var Jimp = require('jimp');

Jimp.read('lenna.png', (err, lenna) => {
  if (err) throw err;
  lenna
    .resize(256, 256)
    .quality(60)
    .greyscale()
    .write('lena-small-bw.jpg')
});

Jimp.read('lenna.png')
  .then(lenna => {
    return lenna
      .resize(256, 256)
      .quality(60)
      .greyscale()
      .write('lena-small-bw.jpg');
  })
  .catch(err => {
    console.error(err);
  })

import Jimp = require('jimp');
import Jimp from 'jimp';
import * as Jimp from 'jimp';
import Jimp from 'jimp/es';

Jimp.read()
  .then()
  .catch()
Jimp.read()
  .then()
  .catch()
Jimp.read()
  .then()
  .catch()
Jimp.read()
  .then()
  .catch()
  
Jimp.read()
  .then()
  .catch()

Jimp.appendConstructorOption(
  'Name of Option',
  args => arg.hasSomeCustomThing,
  function(resolve, reject, args){
    this.bitmpa = customParser(args);
    resolve();
  }
);

Jimp.appendConstructorOption('', options => options.url, function(
  resolve,
  reject,
  options
) {
  phin(options, (err, res) => {
    if(err) {
      return reject(err);
    }
    
    this.parseBitmap(res.body, options.url, err => {
      if (err) {
        return reject(err);
      }
      
      resolve();
    });
  });
});


image.clone();

image.resize(250, 250);
image.resize(Jimp.AUTO, 250);
image.resize(250, Jimp.AUTO);

Jimp.read('lenna.png').then(image => {
  image
    .greyscale()
    .scale(0.5)
    .write('lenna-half-bw.png');
});

Jimp.read('lenna.png').then(image => {
  image.greyscale((err, image) => {
    image.scale(0.5, (err, image) => {
      image.write('lena-half-bw.png');
    });
  });
});

Jimp.distance(image1, image2);

var diff = Jimp.diff(image1, image2, threshold);
diff.image;
diff.percent;

var distance = Jimp.distance(png, jpeg);
var diff = Jimp.diff(png, jpeg);

if(distance < 0.15 || diff.percent < 0.15) {
} else {
}

const hash1 = iamge1.pHash();
const hash2 = image2.pHash();
image2.distanceFromHash(hash1);
Jimp.compareHashes(hash1, hash2);

new Jimp(256, 256, 0xff0000ff, (err, image) => {
});
new Jimp(256, 256, '#FF00FF', (err, image) => {
});
new Jimp({ data: buffer, width: 1280, height: 768 }, (err, image) => {
});

image.hash();
image.hash(2);

image.getPixelIndex(x, y);
Jimp.EDGE_EXTEND = 1;
Jimp.EDGE_WRAP = 2;
Jimp.EDGE_CROP = 3;

image.getPixelColor(x, y);
image.setPixelColor(hex, x, y);

Jimp.rgbaToInt(r, g, b, a);
Jimp.intToRGBA(hex);

Jimp.cssColorToHex(cssColor);
image.scan(x, y, w, h, f);

image.scan(0, 0, image.bitmap.width, image.bitmap.height, funciton (x, y, idx) {
  var red = this.bitmap.data[idx + 0];
  var green = this.bitmap.data[idx + 1];
  var blue = this.bitmap.data[idx + 2];
  var alpha = this.bitmap.data[idx + 3];
});

image.scan(0, 0, image.bitmap.width, image.bitmap.height, funciton(x, y, idx) {
  if (x == image.bitmap.width - 1 && y == image.bitmap.height - 1) {
  }
});

image.convolute([[-2, -1, 0], [-1, 1, 1], [0, 1, 2]]);

image.bitmap.data;
image.bitmap.width;
image.bitmpa.height;

image.color([
  { apply: 'hue', params: [-90] },
  { apply: 'lighten', params: [50] },
  { apply: 'xor', params: ['#06D'] }
]);

image.quality(n);

image.rgba(bool);
image.filterType(number);
image.deflateLevel(number);
Jimp.deflateStrategy(number);

Jimp.PNG_FILTER_AUTO;
Jimp.PNG_FILTER_NONE;
Jimp.PNG_FILTER_SUB;
Jimp.PNG_FILTER_UP;
Jimp.PNG_FILTER_AVERAGE;
Jimp.PNG_FILTER_PATH;

var file = 'new_name' + image.getExtension();
var file = 'new_name';
image.write(file);

image.getBuffer(mime, cb);
image.getBufferAsync(mime);

Jimp.MIME_PNG;
Jimp.MIME_JPEG;
Jimp.MIEM_BMP;
image.getBase64(mime, cb);
image.getBase64Async(mime);

Jimp.loadFont(Jimp.FONT_SANS_32_BLACK).then(font => {
  image.print(
    font,
    10,
    10,
    'Hello world that wraps!',
    50,
    (err, image, { x, y }) => {
      image.print(font, x, y + 20, 'More text on another line', 50);
    }
  );
});

image.write(path, cb);
image.writeAsync(path);

Jimp.loadFont
```

```
{
  plugins: [
    new webpack.DefinePlugin({
      'process.browser': 'true'
    }),
  ],
}
```

```
```


