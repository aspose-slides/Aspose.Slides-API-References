---
title: line_to method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET อ้างอิง API
description: 
type: docs
url: /th/aspose.slides/geometrypath/line_to/
weight: 50
---
## line_to(self, point) {#asposepydrawingpointf}
เพิ่มเส้นไปยังปลายของเส้นทาง


```python
def line_to(self, point):
    ...
```


| พารามิเตอร์ | ชนิด | คำอธิบาย |
| :- | :- | :- |
| point | **aspose.slides.PointF** | จุดปลายของเส้น |


## line_to(self, x, y) {#float-float}
เพิ่มเส้นไปยังปลายของเส้นทาง


```python
def line_to(self, x, y):
    ...
```


| พารามิเตอร์ | ชนิด | คำอธิบาย |
| :- | :- | :- |
| x | **float** | พิกัด X ของจุดปลายของเส้น |
| y | **float** | พิกัด Y ของจุดปลายของเส้น |


## line_to(self, point, index) {#asposepydrawingpointf-int}
เพิ่มเส้นไปยังตำแหน่งที่กำหนดของเส้นทาง


```python
def line_to(self, point, index):
    ...
```


| พารามิเตอร์ | ชนิด | คำอธิบาย |
| :- | :- | :- |
| point | **aspose.slides.PointF** | จุดปลาย |
| index | **int** | ดัชนีของส่วนใน PathData |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | ดัชนีส่วนอยู่นอกช่วงของ PathData |


## line_to(self, x, y, index) {#float-float-int}
เพิ่มเส้นไปยังตำแหน่งที่กำหนดของเส้นทาง


```python
def line_to(self, x, y, index):
    ...
```


| พารามิเตอร์ | ชนิด | คำอธิบาย |
| :- | :- | :- |
| x | **float** | พิกัด X ของจุด |
| y | **float** | พิกัด Y ของจุด |
| index | **int** | ดัชนีของส่วนใน PathData |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | ดัชนีส่วนอยู่นอกช่วงของ PathData |



### ดูเพิ่มเติม
* คลาส [`GeometryPath`](/slides/python-net/th/aspose.slides/geometrypath)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)