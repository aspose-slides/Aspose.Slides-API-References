---
title: quadratic_bezier_to method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/geometrypath/quadratic_bezier_to/
weight: 70
---
## quadratic_bezier_to(self, point1, point2) {#asposepydrawingpointf-asposepydrawingpointf}
पथ के अंत में quadratic Bezier वक्र जोड़ता है


```python
def quadratic_bezier_to(self, point1, point2):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | दिशा बिंदु |
| point2 | **aspose.slides.PointF** | अंत बिंदु |


## quadratic_bezier_to(self, point1, point2, index) {#asposepydrawingpointf-asposepydrawingpointf-int}
पथ में निर्दिष्ट स्थान पर quadratic Bezier वक्र जोड़ता है


```python
def quadratic_bezier_to(self, point1, point2, index):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | दिशा बिंदु |
| point2 | **aspose.slides.PointF** | अंत बिंदु |
| index | **int** | PathData में सेगमेंट का इंडेक्स |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | सेगमेंट इंडेक्स PathData रेंज से बाहर है |


## quadratic_bezier_to(self, x1, y1, x2, y2) {#float-float-float-float}
पथ के अंत में quadratic Bezier वक्र जोड़ता है


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
पथ में निर्दिष्ट स्थान पर quadratic Bezier वक्र जोड़ता है


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
| index | **int** | PathData में सेगमेंट का इंडेक्स |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | सेगमेंट इंडेक्स PathData रेंज से बाहर है |



### देखें
* क्लास [`GeometryPath`](/slides/python-net/hi/aspose.slides/geometrypath)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)