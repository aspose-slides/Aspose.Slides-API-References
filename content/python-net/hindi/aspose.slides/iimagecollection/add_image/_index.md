---
title: add_image method
second_title: Aspose.Slides Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/iimagecollection/add_image/
weight: 10
---
## add_image(self, image) {#iimage}
एक प्रस्तुति में एक छवि जोड़ें।

### वापसी

छवि जोड़ी गई।

```python
def add_image(self, image):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| image | [`IImage`](/slides/python-net/hi/aspose.slides/iimage) | जोड़ने के लिए छवि। |

### टिप्पणियाँ

यह मेथड WMF/EMF मेटाफाइलों को बिना रास्टर PNG छवि में परिवर्तित किए एक प्रस्तुति में जोड़ सकता है।

## add_image(self, stream) {#iorawiobase}
स्ट्रीम से एक प्रस्तुति में छवि जोड़ें।

### वापसी

छवी जोड़ी गई।

```python
def add_image(self, stream):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| stream | **io.RawIOBase** | छवि जोड़ने के लिए स्ट्रीम। |

### टिप्पणियाँ

यह मेथड WMF/EMF मेटाफाइलों को बिना रास्टर PNG छवि में परिवर्तित किए एक प्रस्तुति में जोड़ सकता है।

## add_image(self, buffer) {#bytes}
निर्दिष्ट बफ़र से एक प्रस्तुति में छवि जोड़ता है।

### वापसी

छवि जोड़ी गई।

```python
def add_image(self, buffer):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| buffer | **bytes** | बफ़र। |

## add_image(self, image_source) {#ippimage}
एक अन्य प्रस्तुति से छवि की एक प्रतिलिपि जोड़ता है।

### वापसी

छवि जोड़ी गई।

```python
def add_image(self, image_source):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| image_source | [`IPPImage`](/slides/python-net/hi/aspose.slides/ippimage) | स्रोत छवि। |

## add_image(self, svg_image) {#isvgimage}
SVG ऑब्जेक्ट से एक प्रस्तुति में छवि जोड़ें।

### वापसी

छवि जोड़ी गई।

```python
def add_image(self, svg_image):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/hi/aspose.slides/isvgimage) | SVG छवि ऑब्जेक्ट [`ISvgImage`](/slides/python-net/hi/aspose.slides/isvgimage) |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | जब svgImage पैरामीटर None हो तब थ्रो किया जाता है। |

## add_image(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
स्ट्रीम से एक प्रस्तुति में छवि बनाता और जोड़ता है।

### वापसी

जोड़ी गई [`IPPImage`](/slides/python-net/hi/aspose.slides/ippimage)।

```python
def add_image(self, stream, loading_stream_behavior):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| stream | **io.RawIOBase** | छवि फ़ाइल जोड़ने के लिए स्ट्रीम। |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/hi/aspose.slides/loadingstreambehavior) | वह व्यवहार जो स्ट्रीम पर लागू किया जाएगा। |

### संबंधित देखें
* क्लास [`IImage`](/slides/python-net/hi/aspose.slides/iimage)
* क्लास [`IImageCollection`](/slides/python-net/hi/aspose.slides/iimagecollection)
* क्लास [`IPPImage`](/slides/python-net/hi/aspose.slides/ippimage)
* क्लास [`ISvgImage`](/slides/python-net/hi/aspose.slides/isvgimage)
* एनेमरेशन [`LoadingStreamBehavior`](/slides/python-net/hi/aspose.slides/loadingstreambehavior)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)