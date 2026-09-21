---
title: line_to method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/geometrypath/line_to/
weight: 50
---
## line_to(self, point) {#asposepydrawingpointf}
रेखा को पथ के अंत में जोड़ता है


```python
def line_to(self, point):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| point | **aspose.slides.PointF** | रेखा का अंतिम बिंदु |


## line_to(self, x, y) {#float-float}
रेखा को पथ के अंत में जोड़ता है


```python
def line_to(self, x, y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | रेखा के अंतिम बिंदु का X निर्देशांक |
| y | **float** | रेखा के अंतिम बिंदु का Y निर्देशांक |


## line_to(self, point, index) {#asposepydrawingpointf-int}
रेखा को पथ में निर्दिष्ट स्थान पर जोड़ता है


```python
def line_to(self, point, index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| point | **aspose.slides.PointF** | अंतिम बिंदु |
| index | **int** | PathData में खंड का अनुक्रमांक |

### अपवाद

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | सेगमेंट अनुक्रमांक PathData की सीमा से बाहर है |


## line_to(self, x, y, index) {#float-float-int}
रेखा को पथ में निर्दिष्ट स्थान पर जोड़ता है


```python
def line_to(self, x, y, index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | बिंदु का X निर्देशांक |
| y | **float** | बिंदु का Y निर्देशांक |
| index | **int** | PathData में खंड का अनुक्रमांक |

### अपवाद

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | सेगमेंट अनुक्रमांक PathData की सीमा से बाहर है |



### देखें
* क्लास [`GeometryPath`](/slides/python-net/hi/aspose.slides/geometrypath)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)