---
title: line_to method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/igeometrypath/line_to/
weight: 40
---
## line_to(self, point) {#asposepydrawingpointf}
पथ के अंत में रेखा जोड़ता है


```python
def line_to(self, point):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| point | **aspose.slides.PointF** | रेखा का अंतिम बिंदु |


## line_to(self, x, y) {#float-float}
पथ के अंत में रेखा जोड़ता है


```python
def line_to(self, x, y):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| x | **float** | रेखा के अंतिम बिंदु का X निर्देशांक |
| y | **float** | रेखा के अंतिम बिंदु का Y निर्देशांक |


## line_to(self, point, index) {#asposepydrawingpointf-int}
पथ में निर्दिष्ट स्थान पर रेखा जोड़ता है


```python
def line_to(self, point, index):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| point | **aspose.slides.PointF** | अंतिम बिंदु |
| index | **int** | PathData में खण्ड का अनुक्रमणिका |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | खण्ड अनुक्रमणिका PathData सीमा से बाहर है |


## line_to(self, x, y, index) {#float-float-int}
पथ में निर्दिष्ट स्थान पर रेखा जोड़ता है


```python
def line_to(self, x, y, index):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| x | **float** | बिंदु का X निर्देशांक |
| y | **float** | बिंदु का Y निर्देशांक |
| index | **int** | PathData में खण्ड का अनुक्रमणिका |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | खण्ड अनुक्रमणिका PathData सीमा से बाहर है |



### संबंधित देखें
* क्लास [`IGeometryPath`](/slides/python-net/hi/aspose.slides/igeometrypath)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)