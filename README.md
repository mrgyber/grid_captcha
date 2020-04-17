# Python Grid Captcha Generator

### Installation

    pip install grid_captcha

Or download the tarball / `git clone` and...

    python setup.py install

### Usage
```python
from grid_captcha import CaptchaBuilder

builder = CaptchaBuilder()  # Create builder
builder.build()  # Generate new image

word = builder.word

builder.show()

builder.save('1.jpeg')

image_jpeg = builder.base64()
image_png = builder.base64(image_format='PNG')
```

### Examples

![Example 3](examples/0.jpeg)

![Example 1](examples/1.jpeg)

![Example 2](examples/2.jpeg)

![Example 3](examples/3.jpeg)

![Example 3](examples/4.jpeg)

![Example 3](examples/5.jpeg)

![Example 3](examples/6.jpeg)

![Example 3](examples/7.jpeg)

![Example 3](examples/8.jpeg)

![Example 3](examples/9.jpeg)
