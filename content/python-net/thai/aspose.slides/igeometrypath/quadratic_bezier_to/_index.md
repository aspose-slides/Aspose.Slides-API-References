---
title: quadratic_bezier_to method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/igeometrypath/quadratic_bezier_to/
weight: 60
---
## quadratic_bezier_to(self, point1, point2) {#asposepydrawingpointf-asposepydrawingpointf}
เพิ่มโค้ง Bezier ควอดราติกที่ส่วนท้ายของเส้นทาง


```python
def quadratic_bezier_to(self, point1, point2):
    ...
```


| พารามิเตอร์ | ชนิด | คำอธิบาย |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | จุดทิศทาง |
| point2 | **aspose.slides.PointF** | จุดสิ้นสุด |


## quadratic_bezier_to(self, point1, point2, index) {#asposepydrawingpointf-asposepydrawingpointf-int}
เพิ่มโค้ง Bezier ควอดราติกไปยังตำแหน่งที่ระบุของเส้นทาง


```python
def quadratic_bezier_to(self, point1, point2, index):
    ...
```


| พารามิเตอร์ | ชนิด | คำอธิบาย |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | จุดทิศทาง |
| point2 | **aspose.slides.PointF** | จุดสิ้นสุด |
| index | **int** | ดัชนีของส่วนใน PathData |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | ดัชนีส่วนอยู่เกินช่วงของ PathData |


## quadratic_bezier_to(self, x1, y1, x2, y2) {#float-float-float-float}
เพิ่มโค้ง Bezier ควอดราติกที่ส่วนท้ายของเส้นทาง


```python
def quadratic_bezier_to(self, x1, y1, x2, y2):
    ...
```


| พารามิเตอร์ | ชนิด | คำอธิบาย |
| :- | :- | :- |
| x1 | **float** | พิกัด X ของจุดทิศทาง |
| y1 | **float** | พิกัด Y ของจุดทิศทาง |
| x2 | **float** | พิกัด X ของจุดสิ้นสุด |
| y2 | **float** | พิกัด Y ของจุดสิ้นสุด |


## quadratic_bezier_to(self, x1, y1, x2, y2, index) {#float-float-float-float-int}
เพิ่มโค้ง Bezier ควอดราติกไปยังตำแหน่งที่ระบุของเส้นทาง


```python
def quadratic_bezier_to(self, x1, y1, x2, y2, index):
    ...
```


| พารามิเตอร์ | ชนิด | คำอธิบาย |
| :- | :- | :- |
| x1 | **float** | พิกัด X ของจุดทิศทาง |
| y1 | **float** | พิกัด Y ของจุดทิศทาง |
| x2 | **float** | พิกัด X ของจุดสิ้นสุด |
| y2 | **float** | พิกัด Y ของจุดสิ้นสุด |
| index | **int** | ดัชนีของส่วนใน PathData |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | ดัชนีส่วนอยู่เกินช่วงของ PathData |



### ดูเพิ่มเติม
* คลาส [`IGeometryPath`](/slides/python-net/th/aspose.slides/igeometrypath)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)