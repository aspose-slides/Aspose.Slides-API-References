---
title: contains method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/rectanglef/contains/
weight: 20
---
## contains(self, point) {#pointf}
निर्धारित करता है कि निर्दिष्ट point इस आयत के भीतर सम्मिलित है।

### वापसी

`True` यदि point इस आयत के भीतर सम्मिलित है; अन्यथा, `False`.



```python
def contains(self, point):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/hi/aspose.slides/pointf) | जाँचने के लिए point। `x` और `y` एट्रिब्यूट वाले किसी भी ऑब्जेक्ट को स्वीकार किया जाता है। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **TypeError** | तर्कों की संख्या गलत है। |


## contains(self, rect) {#rectanglef}
निर्धारित करता है कि `rect` द्वारा प्रस्तुत आयताकार क्षेत्र पूरी तरह से इस आयत के भीतर सम्मिलित है।

### वापसी

`True` यदि `rect` द्वारा प्रस्तुत आयताकार क्षेत्र पूरी तरह से इस आयत के भीतर सम्मिलित है; अन्यथा, `False`.



```python
def contains(self, rect):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| rect | [`RectangleF`](/slides/python-net/hi/aspose.slides/rectanglef) | जाँचने के लिए rect। `x`, `y`, `width` और `height` एट्रिब्यूट वाले किसी भी ऑब्जेक्ट को स्वीकार किया जाता है। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **TypeError** | तर्कों की संख्या गलत है। |


## contains(self, x, y) {#float-float}
निर्धारित करता है कि निर्दिष्ट बिंदु इस आयत के भीतर सम्मिलित है।

### वापसी

`True` यदि `x` और `y` द्वारा परिभाषित बिंदु इस आयत के भीतर सम्मिलित है; अन्यथा, `False`.



```python
def contains(self, x, y):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| x | **float** | जाँचने के लिए बिंदु के x-निर्देशांक। |
| y | **float** | जाँचने के लिए बिंदु के y-निर्देशांक। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **TypeError** | तर्कों की संख्या गलत है। |



### देखें
* क्लास [`PointF`](/slides/python-net/hi/aspose.slides/pointf)
* क्लास [`RectangleF`](/slides/python-net/hi/aspose.slides/rectanglef)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)