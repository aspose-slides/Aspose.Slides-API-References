---
title: cubic_bezier_to method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET อ้างอิง API
description: 
type: docs
url: /th/aspose.slides/geometrypath/cubic_bezier_to/
weight: 40
---
## cubic_bezier_to(self, point1, point2, point3) {#asposeslidespointf-asposeslidespointf-asposeslidespointf}
เพิ่มเส้นโค้ง Bezier แบบ cubic ที่ส่วนท้ายของเส้นทาง


```python
def cubic_bezier_to(self, point1, point2, point3):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/th/aspose.slides/pointf) | จุดทิศทางแรก |
| point2 | [`PointF`](/slides/python-net/th/aspose.slides/pointf) | จุดทิศทางที่สอง |
| point3 | [`PointF`](/slides/python-net/th/aspose.slides/pointf) | จุดสุดท้าย |


## cubic_bezier_to(self, point1, point2, point3, index) {#asposeslidespointf-asposeslidespointf-asposeslidespointf-int}
เพิ่มเส้นโค้ง Bezier แบบ cubic ไปยังตำแหน่งที่ระบุของเส้นทาง


```python
def cubic_bezier_to(self, point1, point2, point3, index):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/th/aspose.slides/pointf) | จุดทิศทางแรก |
| point2 | [`PointF`](/slides/python-net/th/aspose.slides/pointf) | จุดทิศทางที่สอง |
| point3 | [`PointF`](/slides/python-net/th/aspose.slides/pointf) | จุดสุดท้าย |
| index | **int** | ดัชนีของส่วนใน PathData |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | ดัชนีส่วนอยู่นอกช่วงของ PathData |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3) {#float-float-float-float-float-float}
เพิ่มเส้นโค้ง Bezier แบบ cubic ที่ส่วนท้ายของเส้นทาง


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| x1 | **float** | ค่าพิกัด X ของจุดทิศทางแรก |
| y1 | **float** | ค่าพิกัด Y ของจุดทิศทางแรก |
| x2 | **float** | ค่าพิกัด X ของจุดทิศทางที่สอง |
| y2 | **float** | ค่าพิกัด Y ของจุดทิศทางที่สอง |
| x3 | **float** | ค่าพิกัด X ของจุดสุดท้าย |
| y3 | **float** | ค่าพิกัด Y ของจุดสุดท้าย |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index) {#float-float-float-float-float-float-int}
เพิ่มเส้นโค้ง Bezier แบบ cubic ไปยังตำแหน่งที่ระบุของเส้นทาง


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| x1 | **float** | ค่าพิกัด X ของจุดทิศทางแรก |
| y1 | **float** | ค่าพิกัด Y ของจุดทิศทางแรก |
| x2 | **float** | ค่าพิกัด X ของจุดทิศทางที่สอง |
| y2 | **float** | ค่าพิกัด Y ของจุดทิศทางที่สอง |
| x3 | **float** | ค่าพิกัด X ของจุดสุดท้าย |
| y3 | **float** | ค่าพิกัด Y ของจุดสุดท้าย |
| index | **int** | ดัชนีของส่วนใน PathData |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | ดัชนีส่วนอยู่นอกช่วงของ PathData |



### ดูเพิ่มเติม
* คลาส [`GeometryPath`](/slides/python-net/th/aspose.slides/geometrypath)
* คลาส [`PointF`](/slides/python-net/th/aspose.slides/pointf)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)