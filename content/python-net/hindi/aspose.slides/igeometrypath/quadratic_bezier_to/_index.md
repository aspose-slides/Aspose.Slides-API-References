---
title: quadratic_bezier_to method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/igeometrypath/quadratic_bezier_to/
weight: 60
---
## quadratic_bezier_to(self, point1, point2) {#asposepydrawingpointf-asposepydrawingpointf}
पथ के अंत में द्विघात बीज़ियर वक्र जोड़ता है


```python
def quadratic_bezier_to(self, point1, point2):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | Direction point |
| point2 | **aspose.slides.PointF** | End point |


## quadratic_bezier_to(self, point1, point2, index) {#asposepydrawingpointf-asposepydrawingpointf-int}
पथ के निर्दिष्ट स्थान पर द्विघात बीज़ियर वक्र जोड़ता है


```python
def quadratic_bezier_to(self, point1, point2, index):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | Direction point |
| point2 | **aspose.slides.PointF** | End point |
| index | **int** | Index of segment in PathData |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | सेगमेंट इंडेक्स PathData की सीमा से बाहर है |


## quadratic_bezier_to(self, x1, y1, x2, y2) {#float-float-float-float}
पथ के अंत में द्विघात बीज़ियर वक्र जोड़ता है


```python
def quadratic_bezier_to(self, x1, y1, x2, y2):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| x1 | **float** | X coordinate of direction point |
| y1 | **float** | Y coordinate of direction point |
| x2 | **float** | X coordinate of end point |
| y2 | **float** | Y coordinate of end point |


## quadratic_bezier_to(self, x1, y1, x2, y2, index) {#float-float-float-float-int}
पथ के निर्दिष्ट स्थान पर द्विघात बीज़ियर वक्र जोड़ता है


```python
def quadratic_bezier_to(self, x1, y1, x2, y2, index):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| x1 | **float** | X coordinate of direction point |
| y1 | **float** | Y coordinate of direction point |
| x2 | **float** | X coordinate of end point |
| y2 | **float** | Y coordinate of end point |
| index | **int** | Index of segment in PathData |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | सेगमेंट इंडेक्स PathData की सीमा से बाहर है |



### संबंधित देखें
* क्लास [`IGeometryPath`](/slides/python-net/hi/aspose.slides/igeometrypath)
* मॉड्युल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)