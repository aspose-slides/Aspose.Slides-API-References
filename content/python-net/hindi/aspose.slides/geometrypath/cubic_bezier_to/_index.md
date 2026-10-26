---
title: cubic_bezier_to method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/geometrypath/cubic_bezier_to/
weight: 40
---
## cubic_bezier_to(self, point1, point2, point3) {#asposeslidespointf-asposeslidespointf-asposeslidespointf}
पथ के अंत में क्यूबिक बीज़ियर कर्व जोड़ता है


```python
def cubic_bezier_to(self, point1, point2, point3):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/hi/aspose.slides/pointf) | पहला दिशा बिंदु |
| point2 | [`PointF`](/slides/python-net/hi/aspose.slides/pointf) | दूसरा दिशा बिंदु |
| point3 | [`PointF`](/slides/python-net/hi/aspose.slides/pointf) | अंत बिंदु |


## cubic_bezier_to(self, point1, point2, point3, index) {#asposeslidespointf-asposeslidespointf-asposeslidespointf-int}
पथ के निर्दिष्ट स्थान पर क्यूबिक बीज़ियर कर्व जोड़ता है


```python
def cubic_bezier_to(self, point1, point2, point3, index):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/hi/aspose.slides/pointf) | पहला दिशा बिंदु |
| point2 | [`PointF`](/slides/python-net/hi/aspose.slides/pointf) | दूसरा दिशा बिंदु |
| point3 | [`PointF`](/slides/python-net/hi/aspose.slides/pointf) | अंत बिंदु |
| index | **int** | PathData में खंड का अनुक्रमणिका |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | सेगमेंट अनुक्रमणिका PathData सीमा से बाहर है |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3) {#float-float-float-float-float-float}
पथ के अंत में क्यूबिक बीज़ियर कर्व जोड़ता है


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
पथ के निर्दिष्ट स्थान पर क्यूबिक बीज़ियर कर्व जोड़ता है


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
| index | **int** | PathData में खंड का अनुक्रमणिका |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | सेगमेंट अनुक्रमणिका PathData सीमा से बाहर है |



### संबंधित देखें
* क्लास [`GeometryPath`](/slides/python-net/hi/aspose.slides/geometrypath)
* क्लास [`PointF`](/slides/python-net/hi/aspose.slides/pointf)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)