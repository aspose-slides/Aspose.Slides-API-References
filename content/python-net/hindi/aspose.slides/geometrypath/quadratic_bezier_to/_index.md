---
title: quadratic_bezier_to method
second_title: Aspose.Slides for Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/geometrypath/quadratic_bezier_to/
weight: 70
---
## quadratic_bezier_to(self, point1, point2) {#asposeslidespointf-asposeslidespointf}
पथ के अंत में क्वाड्रेटिक बेज़ियर कर्व जोड़ता है


```python
def quadratic_bezier_to(self, point1, point2):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/hi/aspose.slides/pointf) | दिशा बिंदु |
| point2 | [`PointF`](/slides/python-net/hi/aspose.slides/pointf) | अंत बिंदु |


## quadratic_bezier_to(self, point1, point2, index) {#asposeslidespointf-asposeslidespointf-int}
पथ के निर्दिष्ट स्थान पर क्वाड्रेटिक बेज़ियर कर्व जोड़ता है


```python
def quadratic_bezier_to(self, point1, point2, index):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/hi/aspose.slides/pointf) | दिशा बिंदु |
| point2 | [`PointF`](/slides/python-net/hi/aspose.slides/pointf) | अंत बिंदु |
| index | **int** | PathData में खंड का अनुक्रमांक |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | सेगमेंट अनुक्रमांक PathData सीमा से बाहर है |


## quadratic_bezier_to(self, x1, y1, x2, y2) {#float-float-float-float}
पथ के अंत में क्वाड्रेटिक बेज़ियर कर्व जोड़ता है


```python
def quadratic_bezier_to(self, x1, y1, x2, y2):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| x1 | **float** | दिशा बिंदु का X निर्देशांक |
| y1 | **float** | दिशा बिंदु का Y निर्देशांक |
| x2 | **float** | अंत बिंदु का X निर्देशांक |
| y2 | **float** | अंत बिंदु का Y निर्देशांक |


## quadratic_bezier_to(self, x1, y1, x2, y2, index) {#float-float-float-float-int}
पथ के निर्दिष्ट स्थान पर क्वाड्रेटिक बेज़ियर कर्व जोड़ता है


```python
def quadratic_bezier_to(self, x1, y1, x2, y2, index):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| x1 | **float** | दिशा बिंदु का X निर्देशांक |
| y1 | **float** | दिशा बिंदु का Y निर्देशांक |
| x2 | **float** | अंत बिंदु का X निर्देशांक |
| y2 | **float** | अंत बिंदु का Y निर्देशांक |
| index | **int** | PathData में खंड का अनुक्रमांक |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | सेगमेंट अनुक्रमांक PathData सीमा से बाहर है |



### संबंधित देखें
* वर्ग [`GeometryPath`](/slides/python-net/hi/aspose.slides/geometrypath)
* वर्ग [`PointF`](/slides/python-net/hi/aspose.slides/pointf)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)