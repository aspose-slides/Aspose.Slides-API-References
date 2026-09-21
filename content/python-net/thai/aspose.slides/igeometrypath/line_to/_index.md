---
title: line_to method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET อ้างอิง API
description: 
type: docs
url: /th/aspose.slides/igeometrypath/line_to/
weight: 40
---
## line_to(self, point) {#asposepydrawingpointf}
เพิ่มเส้นไปยังจุดสุดท้ายของเส้นทาง


```python
def line_to(self, point):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| point | **aspose.slides.PointF** | จุดสิ้นสุดของเส้น |


## line_to(self, x, y) {#float-float}
เพิ่มเส้นไปยังจุดสุดท้ายของเส้นทาง


```python
def line_to(self, x, y):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| x | **float** | พิกัด X ของจุดสุดท้ายของเส้น |
| y | **float** | พิกัด Y ของจุดสุดท้ายของเส้น |


## line_to(self, point, index) {#asposepydrawingpointf-int}
เพิ่มเส้นไปยังตำแหน่งที่กำหนดของเส้นทาง


```python
def line_to(self, point, index):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| point | **aspose.slides.PointF** | จุดสิ้นสุด |
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


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| x | **float** | พิกัด X ของจุด |
| y | **float** | พิกัด Y ของจุด |
| index | **int** | ดัชนีของส่วนใน PathData |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | ดัชนีส่วนอยู่นอกช่วงของ PathData |



### ดูเพิ่มเติม
* คลาส [`IGeometryPath`](/slides/python-net/th/aspose.slides/igeometrypath)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)