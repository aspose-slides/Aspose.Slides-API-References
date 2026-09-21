---
title: get_image method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/slide/get_image/
weight: 40
---
## get_image(self) {#}
एक Thumbnail Image ऑब्जेक्ट लौटाता है (वास्तविक आकार का 20%).

```python
def get_image(self):
    ...
```

## get_image(self, image_size) {#asposepydrawingsize}
निर्दिष्ट आकार के साथ एक Thumbnail Image ऑब्जेक्ट लौटाता है।

### रिटर्न्स
Image ऑब्जेक्ट।

```python
def get_image(self, image_size):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| image_size | **aspose.slides.Size** | बनाने के लिए इमेज का आकार। |

## get_image(self, options) {#asposeslidesexportitiffoptions}
निर्दिष्ट पैरामीटर के साथ एक Thumbnail tiff image ऑब्जेक्ट लौटाता है।

### रिटर्न्स
Image ऑब्जेक्ट।

```python
def get_image(self, options):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| options | [`ITiffOptions`](/slides/python-net/hi/aspose.slides.export/itiffoptions) | Tiff विकल्प। |

### एक्सेप्शन
| एक्सेप्शन | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | जब options.SlideLayoutOption NotesCommentsLayoutingOptions है और इसकी प्रॉपर्टी NotesPosition मान NotesPositions.BottomFull लेती है, तब थ्रो किया जाता है। |

## get_image(self, options) {#asposeslidesexportirenderingoptions}
एक Thumbnail Image ऑब्जेक्ट लौटाता है।

### रिटर्न्स
Image ऑब्जेक्ट।

```python
def get_image(self, options):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/hi/aspose.slides.export/irenderingoptions) | रेन्डरिंग विकल्प। |

### एक्सेप्शन
| एक्सेप्शन | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | जब notesCommentsLayouting.NotesPosition मान NotesPositions.BottomFull लेता है, तब थ्रो किया जाता है। |

## get_image(self, scale_x, scale_y) {#float-float}
कस्टम स्केलिंग के साथ एक Thumbnail Image ऑब्जेक्ट लौटाता है।

### रिटर्न्स
IImage ऑब्जेक्ट।

```python
def get_image(self, scale_x, scale_y):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| scale_x | **float** | इस Thumbnail को x-अक्ष दिशा में स्केल करने का मान। |
| scale_y | **float** | इस Thumbnail को y-अक्ष दिशा में स्केल करने का मान। |

## get_image(self, options, image_size) {#asposeslidesexportirenderingoptions-asposepydrawingsize}
निर्दिष्ट आकार के साथ एक Thumbnail Image ऑब्जेक्ट लौटाता है।

### रिटर्न्स
Image ऑब्जेक्ट।

```python
def get_image(self, options, image_size):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/hi/aspose.slides.export/irenderingoptions) | रेन्डरिंग विकल्प। |
| image_size | **aspose.slides.Size** | बनाने के लिए इमेज का आकार। |

### एक्सेप्शन
| एक्सेप्शन | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | जब options.SlideLayoutOption NotesCommentsLayoutingOptions है और इसकी प्रॉपर्टी NotesPosition मान NotesPositions.BottomFull लेती है, तब थ्रो किया जाता है। |

## get_image(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
कस्टम स्केलिंग के साथ एक Thumbnail Image ऑब्जेक्ट लौटाता है।

### रिटर्न्स
Bitmap ऑब्जेक्ट्स।

```python
def get_image(self, options, scale_x, scale_y):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/hi/aspose.slides.export/irenderingoptions) | रेन्डरिंग विकल्प। |
| scale_x | **float** | इस Thumbnail को x-अक्ष दिशा में स्केल करने का मान। |
| scale_y | **float** | इस Thumbnail को y-अक्ष दिशा में स्केल करने का मान। |

### एक्सेप्शन
| एक्सेप्शन | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | जब notesCommentsLayouting.NotesPosition मान NotesPositions.BottomFull लेता है, तब थ्रो किया जाता है। |

### देखें
* क्लास [`IImage`](/slides/python-net/hi/aspose.slides/iimage)
* क्लास [`IRenderingOptions`](/slides/python-net/hi/aspose.slides.export/irenderingoptions)
* क्लास [`ITiffOptions`](/slides/python-net/hi/aspose.slides.export/itiffoptions)
* क्लास [`Slide`](/slides/python-net/hi/aspose.slides/slide)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)