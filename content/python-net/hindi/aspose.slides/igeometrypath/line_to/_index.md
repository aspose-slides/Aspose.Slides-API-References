---
title: line_to method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/igeometrypath/line_to/
weight: 40
---
## line_to(self, point) {#asposeslidespointf}
पथ के अंत में एक रेखा जोड़ता है


```python
def line_to(self, point):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/hi/aspose.slides/pointf) | रेखा का अंत बिंदु |


## line_to(self, x, y) {#float-float}
पथ के अंत में एक रेखा जोड़ता है


```python
def line_to(self, x, y):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| x | **float** | रेखा के अंत बिंदु का X निर्देशांक |
| y | **float** | रेखा के अंत बिंदु का Y निर्देशांक |


## line_to(self, point, index) {#asposeslidespointf-int}
पथ के निर्दिष्ट स्थान पर एक रेखा जोड़ता है


```python
def line_to(self, point, index):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/hi/aspose.slides/pointf) | अंत बिंदु |
| index | **int** | PathData में खंड का सूचकांक |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | सेगमेंट सूचकांक PathData की सीमा से बाहर है |


## line_to(self, x, y, index) {#float-float-int}
पथ के निर्दिष्ट स्थान पर एक रेखा जोड़ता है


```python
def line_to(self, x, y, index):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| x | **float** | बिंदु का X निर्देशांक |
| y | **float** | बिंदु का Y निर्देशांक |
| index | **int** | PathData में खंड का सूचकांक |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | सेगमेंट सूचकांक PathData की सीमा से बाहर है |



### संबंधित देखें
* क्लास [`IGeometryPath`](/slides/python-net/hi/aspose.slides/igeometrypath)
* क्लास [`PointF`](/slides/python-net/hi/aspose.slides/pointf)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)