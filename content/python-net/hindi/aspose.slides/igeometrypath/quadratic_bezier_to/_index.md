---
title: quadratic_bezier_to method
second_title: Aspose.Slides Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/igeometrypath/quadratic_bezier_to/
weight: 60
---
## quadratic_bezier_to(self, point1, point2) {#asposeslidespointf-asposeslidespointf}
पाथ के अंत में quadratic Bezier curve जोड़ता है


```python
def quadratic_bezier_to(self, point1, point2):
    ...
```


| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/hi/aspose.slides/pointf) | दिशा बिंदु |
| point2 | [`PointF`](/slides/python-net/hi/aspose.slides/pointf) | अन्त बिंदु |


## quadratic_bezier_to(self, point1, point2, index) {#asposeslidespointf-asposeslidespointf-int}
पाथ के निर्दिष्ट स्थान पर quadratic Bezier curve जोड़ता है


```python
def quadratic_bezier_to(self, point1, point2, index):
    ...
```


| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/hi/aspose.slides/pointf) | दिशा बिंदु |
| point2 | [`PointF`](/slides/python-net/hi/aspose.slides/pointf) | अन्त बिंदु |
| index | **int** | PathData में सेगमेंट का इंडेक्स |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | सेगमेंट इंडेक्स PathData रेंज से बाहर है |


## quadratic_bezier_to(self, x1, y1, x2, y2) {#float-float-float-float}
पाथ के अंत में quadratic Bezier curve जोड़ता है


```python
def quadratic_bezier_to(self, x1, y1, x2, y2):
    ...
```


| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| x1 | **float** | दिशा बिंदु का X निर्देशांक |
| y1 | **float** | दिशा बिंदु का Y निर्देशांक |
| x2 | **float** | अन्त बिंदु का X निर्देशांक |
| y2 | **float** | अन्त बिंदु का Y निर्देशांक |


## quadratic_bezier_to(self, x1, y1, x2, y2, index) {#float-float-float-float-int}
पाथ के निर्दिष्ट स्थान पर quadratic Bezier curve जोड़ता है


```python
def quadratic_bezier_to(self, x1, y1, x2, y2, index):
    ...
```


| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| x1 | **float** | दिशा बिंदु का X निर्देशांक |
| y1 | **float** | दिशा बिंदु का Y निर्देशांक |
| x2 | **float** | अन्त बिंदु का X निर्देशांक |
| y2 | **float** | अन्त बिंदु का Y निर्देशांक |
| index | **int** | PathData में सेगमेंट का इंडेक्स |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | सेगमेंट इंडेक्स PathData रेंज से बाहर है |



### देखिए
* क्लास [`IGeometryPath`](/slides/python-net/hi/aspose.slides/igeometrypath)
* क्लास [`PointF`](/slides/python-net/hi/aspose.slides/pointf)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)