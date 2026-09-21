---
title: quadratic_bezier_to method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/geometrypath/quadratic_bezier_to/
weight: 70
---
## quadratic_bezier_to(self, point1, point2) {#asposepydrawingpointf-asposepydrawingpointf}
เพิ่มเส้นโค้ง Bezier ระดับสองที่ส่วนท้ายของพาธ


```python
def quadratic_bezier_to(self, point1, point2):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | จุดทิศทาง |
| point2 | **aspose.slides.PointF** | จุดสิ้นสุด |


## quadratic_bezier_to(self, point1, point2, index) {#asposepydrawingpointf-asposepydrawingpointf-int}
เพิ่มเส้นโค้ง Bezier ระดับสองไปยังตำแหน่งที่ระบุของพาธ


```python
def quadratic_bezier_to(self, point1, point2, index):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | จุดทิศทาง |
| point2 | **aspose.slides.PointF** | จุดสิ้นสุด |
| index | **int** | ดัชนีของส่วนใน PathData |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | ดัชนีส่วนอยู่นอกช่วงของ PathData |


## quadratic_bezier_to(self, x1, y1, x2, y2) {#float-float-float-float}
เพิ่มเส้นโค้ง Bezier ระดับสองที่ส่วนท้ายของพาธ


```python
def quadratic_bezier_to(self, x1, y1, x2, y2):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| x1 | **float** | พิกัด X ของจุดทิศทาง |
| y1 | **float** | พิกัด Y ของจุดทิศทาง |
| x2 | **float** | พิกัด X ของจุดสิ้นสุด |
| y2 | **float** | พิกัด Y ของจุดสิ้นสุด |


## quadratic_bezier_to(self, x1, y1, x2, y2, index) {#float-float-float-float-int}
เพิ่มเส้นโค้ง Bezier ระดับสองไปยังตำแหน่งที่ระบุของพาธ


```python
def quadratic_bezier_to(self, x1, y1, x2, y2, index):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| x1 | **float** | พิกัด X ของจุดทิศทาง |
| y1 | **float** | พิกัด Y ของจุดทิศทาง |
| x2 | **float** | พิกัด X ของจุดสิ้นสุด |
| y2 | **float** | พิกัด Y ของจุดสิ้นสุด |
| index | **int** | ดัชนีของส่วนใน PathData |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | ดัชนีส่วนอยู่นอกช่วงของ PathData |



### ดูเพิ่มเติม
* class [`GeometryPath`](/slides/python-net/th/aspose.slides/geometrypath)
* module [`aspose.slides`](/slides/python-net/th/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)