---
title: line_to method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/geometrypath/line_to/
weight: 50
---
## line_to(self, point) {#asposeslidespointf}
เพิ่มเส้นไปยังจุดสิ้นสุดของเส้นทาง


```python
def line_to(self, point):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/th/aspose.slides/pointf) | End point of the line |


## line_to(self, x, y) {#float-float}
เพิ่มเส้นไปยังจุดสิ้นสุดของเส้นทาง


```python
def line_to(self, x, y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | X coordinate of the end point of the line |
| y | **float** | Y coordinate of the end point of the line |


## line_to(self, point, index) {#asposeslidespointf-int}
เพิ่มเส้นไปยังตำแหน่งที่ระบุของเส้นทาง


```python
def line_to(self, point, index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/th/aspose.slides/pointf) | End point |
| index | **int** | Index of segment in PathData |

### ข้อยกเว้น

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Segment index is out of PathData range |


## line_to(self, x, y, index) {#float-float-int}
เพิ่มเส้นไปยังตำแหน่งที่ระบุของเส้นทาง


```python
def line_to(self, x, y, index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | X coordinate of the point |
| y | **float** | Y coordinate of the point |
| index | **int** | Index of segment in PathData |

### ข้อยกเว้น

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Segment index is out of PathData range |



### ดูเพิ่มเติม
* คลาส [`GeometryPath`](/slides/python-net/th/aspose.slides/geometrypath)
* คลาส [`PointF`](/slides/python-net/th/aspose.slides/pointf)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)