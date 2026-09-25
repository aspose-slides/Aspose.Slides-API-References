---
title: cubic_bezier_to method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/igeometrypath/cubic_bezier_to/
weight: 30
---
## cubic_bezier_to(self, point1, point2, point3) {#asposeslidespointf-asposeslidespointf-asposeslidespointf}
เพิ่มเส้นโค้ง Bezier แบบคิวบิกที่ส่วนท้ายของเส้นทาง


```python
def cubic_bezier_to(self, point1, point2, point3):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/th/aspose.slides/pointf) | จุดทิศทางแรก |
| point2 | [`PointF`](/slides/python-net/th/aspose.slides/pointf) | จุดทิศทางที่สอง |
| point3 | [`PointF`](/slides/python-net/th/aspose.slides/pointf) | จุดสิ้นสุด |


## cubic_bezier_to(self, point1, point2, point3, index) {#asposeslidespointf-asposeslidespointf-asposeslidespointf-int}
เพิ่มเส้นโค้ง Bezier แบบคิวบิกไปยังตำแหน่งที่ระบุของเส้นทาง


```python
def cubic_bezier_to(self, point1, point2, point3, index):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/th/aspose.slides/pointf) | จุดทิศทางแรก |
| point2 | [`PointF`](/slides/python-net/th/aspose.slides/pointf) | จุดทิศทางที่สอง |
| point3 | [`PointF`](/slides/python-net/th/aspose.slides/pointf) | จุดสิ้นสุด |
| index | **int** | ดัชนีของส่วนใน PathData |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | ดัชนีส่วนอยู่นอกช่วงของ PathData |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3) {#float-float-float-float-float-float}
เพิ่มเส้นโค้ง Bezier แบบคิวบิกที่ส่วนท้ายของเส้นทาง


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| x1 | **float** | พิกัด X ของจุดทิศทางแรก |
| y1 | **float** | พิกัด Y ของจุดทิศทางแรก |
| x2 | **float** | พิกัด X ของจุดทิศทางที่สอง |
| y2 | **float** | พิกัด Y ของจุดทิศทางที่สอง |
| x3 | **float** | พิกัด X ของจุดสิ้นสุด |
| y3 | **float** | พิกัด Y ของจุดสิ้นสุด |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index) {#float-float-float-float-float-float-int}
เพิ่มเส้นโค้ง Bezier แบบคิวบิกไปยังตำแหน่งที่ระบุของเส้นทาง


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| x1 | **float** | พิกัด X ของจุดทิศทางแรก |
| y1 | **float** | พิกัด Y ของจุดทิศทางแรก |
| x2 | **float** | พิกัด X ของจุดทิศทางที่สอง |
| y2 | **float** | พิกัด Y ของจุดทิศทางที่สอง |
| x3 | **float** | พิกัด X ของจุดสิ้นสุด |
| y3 | **float** | พิกัด Y ของจุดสิ้นสุด |
| index | **int** | ดัชนีของส่วนใน PathData |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | ดัชนีส่วนอยู่นอกช่วงของ PathData |



### ดูเพิ่มเติม
* คลาส [`IGeometryPath`](/slides/python-net/th/aspose.slides/igeometrypath)
* คลาส [`PointF`](/slides/python-net/th/aspose.slides/pointf)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)