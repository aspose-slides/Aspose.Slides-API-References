---
title: get_image method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/slide/get_image/
weight: 40
---
## get_image(self) {#}
वास्तविक आकार के 20 % के साथ एक थंबनेल Image ऑब्जेक्ट लौटाता है।

```python
def get_image(self):
    ...
```

## get_image(self, image_size) {#asposeslidessize}
निर्दिष्ट आकार के साथ एक थंबनेल Image ऑब्जेक्ट लौटाता है।

### रिटर्न

Image ऑब्जेक्ट।

```python
def get_image(self, image_size):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| image_size | [`Size`](/slides/python-net/hi/aspose.slides/size) | बनाना हेतु छवि का आकार। |

## get_image(self, options) {#asposeslidesexportitiffoptions}
निर्दिष्ट पैरामीटर के साथ एक थंबनेल tiff Image ऑब्जेक्ट लौटाता है।

### रिटर्न

Image ऑब्जेक्ट।

```python
def get_image(self, options):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| options | [`ITiffOptions`](/slides/python-net/hi/aspose.slides.export/itiffoptions) | Tiff विकल्प। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | जब options.SlideLayoutOption is NotesCommentsLayoutingOptions और उसका प्रॉपर्टी NotesPosition का मान NotesPositions.BottomFull हो तो उत्पन्न होता है। |

## get_image(self, options) {#asposeslidesexportirenderingoptions}
एक थंबनेल Image ऑब्जेक्ट लौटाता है।

### रिटर्न

Image ऑब्जेक्ट।

```python
def get_image(self, options):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/hi/aspose.slides.export/irenderingoptions) | रेंडरिंग विकल्प। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | जब notesCommentsLayouting.NotesPosition का मान NotesPositions.BottomFull हो तो उत्पन्न होता है। |

## get_image(self, scale_x, scale_y) {#float-float}
कस्टम स्केलिंग के साथ एक थंबनेल Image ऑब्जेक्ट लौटाता है।

### रिटर्न

IImage ऑब्जेक्ट।

```python
def get_image(self, scale_x, scale_y):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| scale_x | **float** | x-अक्ष दिशा में इस थंबनेल को स्केल करने का मान। |
| scale_y | **float** | y-अक्ष दिशा में इस थंबनेल को स्केल करने का मान। |

## get_image(self, options, image_size) {#asposeslidesexportirenderingoptions-asposeslidessize}
निर्दिष्ट आकार के साथ एक थंबनेल Image ऑब्जेक्ट लौटाता है।

### रिटर्न

Image ऑब्जेक्ट।

```python
def get_image(self, options, image_size):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/hi/aspose.slides.export/irenderingoptions) | रेंडरिंग विकल्प। |
| image_size | [`Size`](/slides/python-net/hi/aspose.slides/size) | बनाना हेतु छवि का आकार। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | जब options.SlideLayoutOption is NotesCommentsLayoutingOptions और उसका प्रॉपर्टी NotesPosition का मान NotesPositions.BottomFull हो तो उत्पन्न होता है। |

## get_image(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
कस्टम स्केलिंग के साथ एक थंबनेल Image ऑब्जेक्ट लौटाता है।

### रिटर्न

Bitmap ऑब्जेक्ट्स।

```python
def get_image(self, options, scale_x, scale_y):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/hi/aspose.slides.export/irenderingoptions) | रेंडरिंग विकल्प। |
| scale_x | **float** | x-अक्ष दिशा में इस थंबनेल को स्केल करने का मान। |
| scale_y | **float** | y-अक्ष दिशा में इस थंबनेल को स्केल करने का मान। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | जब notesCommentsLayouting.NotesPosition का मान NotesPositions.BottomFull हो तो उत्पन्न होता है। |

### संबंधित देखें
* class [`IImage`](/slides/python-net/hi/aspose.slides/iimage)
* class [`IRenderingOptions`](/slides/python-net/hi/aspose.slides.export/irenderingoptions)
* class [`ITiffOptions`](/slides/python-net/hi/aspose.slides.export/itiffoptions)
* class [`Slide`](/slides/python-net/hi/aspose.slides/slide)
* class [`Size`](/slides/python-net/hi/aspose.slides/size)
* module [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)