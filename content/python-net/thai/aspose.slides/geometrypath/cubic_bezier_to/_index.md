---
title: cubic_bezier_to method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/geometrypath/cubic_bezier_to/
weight: 40
---
## cubic_bezier_to(self, point1, point2, point3) {#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf}
เพิ่มเส้นโค้ง Bezier คิวบิกที่ส่วนท้ายของพาธ


```python
def cubic_bezier_to(self, point1, point2, point3):
    ...
```


| พารามิเตอร์ | ชนิด | คำอธิบาย |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | จุดทิศทางแรก |
| point2 | **aspose.slides.PointF** | จุดทิศทางที่สอง |
| point3 | **aspose.slides.PointF** | จุดสุดท้าย |


## cubic_bezier_to(self, point1, point2, point3, index) {#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf-int}
เพิ่มเส้นโค้ง Bezier คิวบิกไปยังตำแหน่งที่ระบุของพาธ


```python
def cubic_bezier_to(self, point1, point2, point3, index):
    ...
```


| พารามิเตอร์ | ชนิด | คำอธิบาย |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | จุดทิศทางแรก |
| point2 | **aspose.slides.PointF** | จุดทิศทางที่สอง |
| point3 | **aspose.slides.PointF** | จุดสุดท้าย |
| index | **int** | ดัชนีของส่วนใน PathData |

### ข้อยกเว้น

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | ดัชนีส่วนอยู่นอกช่วง PathData |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3) {#float-float-float-float-float-float}
เพิ่มเส้นโค้ง Bezier คิวบิกที่ส่วนท้ายของพาธ


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3):
    ...
```


| พารามิเตอร์ | ชนิด | คำอธิบาย |
| :- | :- | :- |
| x1 | **float** | พิกัด X ของจุดทิศทางแรก |
| y1 | **float** | พิกัด Y ของจุดทิศทางแรก |
| x2 | **float** | พิกัด X ของจุดทิศทางที่สอง |
| y2 | **float** | พิกัด Y ของจุดทิศทางที่สอง |
| x3 | **float** | พิกัด X ของจุดสุดท้าย |
| y3 | **float** | พิกัด Y ของจุดสุดท้าย |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index) {#float-float-float-float-float-float-int}
เพิ่มเส้นโค้ง Bezier คิวบิกไปยังตำแหน่งที่ระบุของพาธ


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index):
    ...
```


| พารามิเตอร์ | ชนิด | คำอธิบาย |
| :- | :- | :- |
| x1 | **float** | พิกัด X ของจุดทิศทางแรก |
| y1 | **float** | พิกัด Y ของจุดทิศทางแรก |
| x2 | **float** | พิกัด X ของจุดทิศทางที่สอง |
| y2 | **float** | พิกัด Y ของจุดทิศทางที่สอง |
| x3 | **float** | พิกัด X ของจุดสุดท้าย |
| y3 | **float** | พิกัด Y ของจุดสุดท้าย |
| index | **int** | ดัชนีของส่วนใน PathData |

### ข้อยกเว้น

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | ดัชนีส่วนอยู่นอกช่วง PathData |



### ดูเพิ่มเติม
* คลาส [`GeometryPath`](/slides/python-net/th/aspose.slides/geometrypath)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)