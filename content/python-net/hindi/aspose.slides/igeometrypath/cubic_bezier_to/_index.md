---
title: cubic_bezier_to method
second_title: Aspose.Slides Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/igeometrypath/cubic_bezier_to/
weight: 30
---
## cubic_bezier_to(self, point1, point2, point3) {#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf}
पाथ के अंत में क्यूबिक बीज़िएर वक्र जोड़ता है


```python
def cubic_bezier_to(self, point1, point2, point3):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | पहला दिशा बिंदु |
| point2 | **aspose.slides.PointF** | दूसरा दिशा बिंदु |
| point3 | **aspose.slides.PointF** | अंत बिंदु |


## cubic_bezier_to(self, point1, point2, point3, index) {#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf-int}
पाथ के निर्दिष्ट स्थान पर क्यूबिक बीज़िएर वक्र जोड़ता है


```python
def cubic_bezier_to(self, point1, point2, point3, index):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | पहला दिशा बिंदु |
| point2 | **aspose.slides.PointF** | दूसरा दिशा बिंदु |
| point3 | **aspose.slides.PointF** | अंत बिंदु |
| index | **int** | PathData में खंड का अनुक्रमांक |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | सेगमेंट अनुक्रमांक PathData की सीमा से बाहर है |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3) {#float-float-float-float-float-float}
पाथ के अंत में क्यूबिक बीज़िएर वक्र जोड़ता है


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| x1 | **float** | पहला दिशा बिंदु का X निर्देशांक |
| y1 | **float** | पहला दिशा बिंदु का Y निर्देशांक |
| x2 | **float** | दूसरा दिशा बिंदु का X निर्देशांक |
| y2 | **float** | दूसरा दिशा बिंदु का Y निर्देशांक |
| x3 | **float** | अंत बिंदु का X निर्देशांक |
| y3 | **float** | अंत बिंदु का Y निर्देशांक |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index) {#float-float-float-float-float-float-int}
पाथ के निर्दिष्ट स्थान पर क्यूबिक बीज़िएर वक्र जोड़ता है


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| x1 | **float** | पहला दिशा बिंदु का X निर्देशांक |
| y1 | **float** | पहला दिशा बिंदु का Y निर्देशांक |
| x2 | **float** | दूसरा दिशा बिंदु का X निर्देशांक |
| y2 | **float** | दूसरा दिशा बिंदु का Y निर्देशांक |
| x3 | **float** | अंत बिंदु का X निर्देशांक |
| y3 | **float** | अंत बिंदु का Y निर्देशांक |
| index | **int** | PathData में खंड का अनुक्रमांक |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | सेगमेंट अनुक्रमांक PathData की सीमा से बाहर है |



### संबंधित देखें
* क्लास [`IGeometryPath`](/slides/python-net/hi/aspose.slides/igeometrypath)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)