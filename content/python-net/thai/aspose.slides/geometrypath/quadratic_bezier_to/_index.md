---
title: quadratic_bezier_to method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/geometrypath/quadratic_bezier_to/
weight: 70
---
## quadratic_bezier_to(self, point1, point2) {#asposeslidespointf-asposeslidespointf}
เพิ่มเส้นโค้งควอดรูติกเบเซียร์ที่ส่วนท้ายของเส้นทาง


```python
def quadratic_bezier_to(self, point1, point2):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/th/aspose.slides/pointf) | จุดทิศทาง |
| point2 | [`PointF`](/slides/python-net/th/aspose.slides/pointf) | จุดสิ้นสุด |


## quadratic_bezier_to(self, point1, point2, index) {#asposeslidespointf-asposeslidespointf-int}
เพิ่มเส้นโค้งควอดรูติกเบเซียร์ไปยังตำแหน่งที่ระบุของเส้นทาง


```python
def quadratic_bezier_to(self, point1, point2, index):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/th/aspose.slides/pointf) | จุดทิศทาง |
| point2 | [`PointF`](/slides/python-net/th/aspose.slides/pointf) | จุดสิ้นสุด |
| index | **int** | ดัชนีของส่วนใน PathData |

### Exceptions

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | ดัชนีส่วนอยู่นอกช่วงของ PathData |


## quadratic_bezier_to(self, x1, y1, x2, y2) {#float-float-float-float}
เพิ่มเส้นโค้งควอดรูติกเบเซียร์ที่ส่วนท้ายของเส้นทาง


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
เพิ่มเส้นโค้งควอดรูติกเบเซียร์ไปยังตำแหน่งที่ระบุของเส้นทาง


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

### Exceptions

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | ดัชนีส่วนอยู่นอกช่วงของ PathData |



### See Also
* คลาส [`GeometryPath`](/slides/python-net/th/aspose.slides/geometrypath)
* คลาส [`PointF`](/slides/python-net/th/aspose.slides/pointf)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)