---
title: add_image method
second_title: Aspose.Slides for Python के लिए .NET API रेफ़रेंस
description: 
type: docs
url: /hi/aspose.slides/imagecollection/add_image/
weight: 10
---
## add_image(self, image_source) {#ippimage}
एक अन्य प्रस्तुति से छवि की प्रति जोड़ता है।

### Returns
जोड़ी गई छवि।

```python
def add_image(self, image_source):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| image_source | [`IPPImage`](/slides/python-net/hi/aspose.slides/ippimage) | स्रोत छवि। |

## add_image(self, image) {#iimage}
एक प्रस्तुति में छवि जोड़ता है।

### Returns
जोड़ी गई छवि।

```python
def add_image(self, image):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| image | [`IImage`](/slides/python-net/hi/aspose.slides/iimage) | जोड़ने के लिए छवि। |

### Remarks
यह विधि WMF/EMF मेटा फ़ाइलों को प्रस्तुतिकरण में सम्मिलित करने से पहले रास्टर PNG छवि में बदल देती है।

## add_image(self, stream) {#iorawiobase}
स्ट्रीम से प्रस्तुति में छवि जोड़ता है।

### Returns
जोड़ी गई छवि।

```python
def add_image(self, stream):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | छवि जोड़ने के लिए स्ट्रीम। |

### Remarks
यह विधि WMF/EMF मेटा फ़ाइलों को रास्टर PNG छवि में परिवर्तित किए बिना प्रस्तुति में जोड़ सकती है।

## add_image(self, buffer) {#bytes}
निर्दिष्ट बफ़र से प्रस्तुति में छवि जोड़ता है।

### Returns
जोड़ी गई छवि।

```python
def add_image(self, buffer):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| buffer | **bytes** | बफ़र। |

## add_image(self, svg_image) {#isvgimage}
Svg ऑब्जेक्ट से प्रस्तुति में छवि जोड़ता है।

### Returns
जोड़ी गई छवि।

```python
def add_image(self, svg_image):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/hi/aspose.slides/isvgimage) | Svg छवि ऑब्जेक्ट [`ISvgImage`](/slides/python-net/hi/aspose.slides/isvgimage) |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | जब svgImage पैरामीटर None हो। |

## add_image(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
स्ट्रीम से प्रस्तुति में छवि बनाता और जोड़ता है।

### Returns
जोड़ी गई [`IPPImage`](/slides/python-net/hi/aspose.slides/ippimage)।

```python
def add_image(self, stream, loading_stream_behavior):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | छवि फ़ाइल जोड़ने के लिए स्ट्रीम। |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/hi/aspose.slides/loadingstreambehavior) | वह व्यवहार जो स्ट्रीम पर लागू होगा। |

### See Also
* क्लास [`IImage`](/slides/python-net/hi/aspose.slides/iimage)
* क्लास [`ImageCollection`](/slides/python-net/hi/aspose.slides/imagecollection)
* क्लास [`IPPImage`](/slides/python-net/hi/aspose.slides/ippimage)
* क्लास [`ISvgImage`](/slides/python-net/hi/aspose.slides/isvgimage)
* एन्यूमरेशन [`LoadingStreamBehavior`](/slides/python-net/hi/aspose.slides/loadingstreambehavior)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)