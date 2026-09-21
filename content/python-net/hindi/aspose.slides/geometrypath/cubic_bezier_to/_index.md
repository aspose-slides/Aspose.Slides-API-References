---
title: cubic_bezier_to method
second_title: Aspose.Slides Python के लिये .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/geometrypath/cubic_bezier_to/
weight: 40
---
## cubic_bezier_to(self, point1, point2, point3) {#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf}
पथ के अंत में क्यूबिक बीज़ियर कर्व जोड़ता है


```python
def cubic_bezier_to(self, point1, point2, point3):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | पहला दिशा बिंदु |
| point2 | **aspose.slides.PointF** | दूसरा दिशा बिंदु |
| point3 | **aspose.slides.PointF** | समाप्ति बिंदु |


## cubic_bezier_to(self, point1, point2, point3, index) {#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf-int}
निर्दिष्ट स्थान पर पथ में क्यूबिक बीज़ियर कर्व जोड़ता है


```python
def cubic_bezier_to(self, point1, point2, point3, index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | पहला दिशा बिंदु |
| point2 | **aspose.slides.PointF** | दूसरा दिशा बिंदु |
| point3 | **aspose.slides.PointF** | समाप्ति बिंदु |
| index | **int** | PathData में खंड का सूचकांक |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | सेगमेंट सूचकांक PathData सीमा से बाहर है |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3) {#float-float-float-float-float-float}
पथ के अंत में क्यूबिक बीज़ियर कर्व जोड़ता है


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x1 | **float** | पहले दिशा बिंदु का X निर्देशांक |
| y1 | **float** | पहले दिशा बिंदु का Y निर्देशांक |
| x2 | **float** | दूसरे दिशा बिंदु का X निर्देशांक |
| y2 | **float** | दूसरे दिशा बिंदु का Y निर्देशांक |
| x3 | **float** | समाप्ति बिंदु का X निर्देशांक |
| y3 | **float** | समाप्ति बिंदु का Y निर्देशांक |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index) {#float-float-float-float-float-float-int}
निर्दिष्ट स्थान पर पथ में क्यूबिक बीज़ियर कर्व जोड़ता है


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x1 | **float** | पहले दिशा बिंदु का X निर्देशांक |
| y1 | **float** | पहले दिशा बिंदु का Y निर्देशांक |
| x2 | **float** | दूसरे दिशा बिंदु का X निर्देशांक |
| y2 | **float** | दूसरे दिशा बिंदु का Y निर्देशांक |
| x3 | **float** | समाप्ति बिंदु का X निर्देशांक |
| y3 | **float** | समाप्ति बिंदु का Y निर्देशांक |
| index | **int** | PathData में खंड का सूचकांक |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | सेगमेंट सूचकांक PathData सीमा से बाहर है |



### See Also
* वर्ग [`GeometryPath`](/slides/python-net/hi/aspose.slides/geometrypath)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)