---
title: line_to method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/geometrypath/line_to/
weight: 50
---
## line_to(self, point) {#asposeslidespointf}
पथ के अंत में रेखा जोड़ता है


```python
def line_to(self, point):
    ...
```


| पैरामीटर | प्रकार | वर्णन |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/hi/aspose.slides/pointf) | लाइन का अंत बिंदु |


## line_to(self, x, y) {#float-float}
पथ के अंत में रेखा जोड़ता है


```python
def line_to(self, x, y):
    ...
```


| पैरामीटर | प्रकार | वर्णन |
| :- | :- | :- |
| x | **float** | लाइन के अंत बिंदु का X निर्देशांक |
| y | **float** | लाइन के अंत बिंदु का Y निर्देशांक |


## line_to(self, point, index) {#asposeslidespointf-int}
निर्दिष्ट स्थान पर रेखा जोड़ता है


```python
def line_to(self, point, index):
    ...
```


| पैरामीटर | प्रकार | वर्णन |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/hi/aspose.slides/pointf) | अंत बिंदु |
| index | **int** | PathData में खंड का इंडेक्स |

### अपवाद

| अपवाद | वर्णन |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | सेगमेंट इंडेक्स PathData की सीमा से बाहर है |


## line_to(self, x, y, index) {#float-float-int}
निर्दिष्ट स्थान पर रेखा जोड़ता है


```python
def line_to(self, x, y, index):
    ...
```


| पैरामीटर | प्रकार | वर्णन |
| :- | :- | :- |
| x | **float** | बिंदु का X निर्देशांक |
| y | **float** | बिंदु का Y निर्देशांक |
| index | **int** | PathData में खंड का इंडेक्स |

### अपवाद

| अपवाद | वर्णन |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | सेगमेंट इंडेक्स PathData की सीमा से बाहर है |



### देखें
* क्लास [`GeometryPath`](/slides/python-net/hi/aspose.slides/geometrypath)
* क्लास [`PointF`](/slides/python-net/hi/aspose.slides/pointf)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)