---
title: GeometryPath class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET อ้างอิง API
description: 
type: docs
url: /th/aspose.slides/geometrypath/
---
## GeometryPath คลาส

แสดงเส้นทางเรขาคณิตของ GeometryShape

ประเภท GeometryPath มีสมาชิกต่อไปนี้:

## ตัวสร้าง

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/th/aspose.slides/geometrypath/__init__/#) | สร้างอินสแตนซ์ของ GeometryPath |

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`path_data`](/slides/python-net/th/aspose.slides/geometrypath/path_data/) | ส่งคืนเส้นทางเรขาคณิตของ GeometryShape เป็นอาร์เรย์ของส่วนของเส้นทาง |
| [`fill_mode`](/slides/python-net/th/aspose.slides/geometrypath/fill_mode/) | ตั้งค่าโหมดเติม |
| [`stroke`](/slides/python-net/th/aspose.slides/geometrypath/stroke/) | ตั้งลักษณะการวาดเส้น |

## วิธีการ

| Method | Description |
| :- | :- |
| [`line_to(self, point)`](/slides/python-net/th/aspose.slides/geometrypath/line_to/#asposeslidespointf) | เพิ่มเส้นตรงที่ส่วนท้ายของเส้นทาง |
| [`line_to(self, x, y)`](/slides/python-net/th/aspose.slides/geometrypath/line_to/#float-float) | เพิ่มเส้นตรงที่ส่วนท้ายของเส้นทาง |
| [`line_to(self, point, index)`](/slides/python-net/th/aspose.slides/geometrypath/line_to/#asposeslidespointf-int) | เพิ่มเส้นตรงในตำแหน่งที่ระบุของเส้นทาง |
| [`line_to(self, x, y, index)`](/slides/python-net/th/aspose.slides/geometrypath/line_to/#float-float-int) | เพิ่มเส้นตรงในตำแหน่งที่ระบุของเส้นทาง |
| [`cubic_bezier_to(self, point1, point2, point3)`](/slides/python-net/th/aspose.slides/geometrypath/cubic_bezier_to/#asposeslidespointf-asposeslidespointf-asposeslidespointf) | เพิ่มเส้นโค้งเบซิเยอร์แบบคิวบิกที่ส่วนท้ายของเส้นทาง |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3)`](/slides/python-net/th/aspose.slides/geometrypath/cubic_bezier_to/#float-float-float-float-float-float) | เพิ่มเส้นโค้งเบซิเยอร์แบบคิวบิกที่ส่วนท้ายของเส้นทาง |
| [`cubic_bezier_to(self, point1, point2, point3, index)`](/slides/python-net/th/aspose.slides/geometrypath/cubic_bezier_to/#asposeslidespointf-asposeslidespointf-asposeslidespointf-int) | เพิ่มเส้นโค้งเบซิเยอร์แบบคิวบิกในตำแหน่งที่ระบุของเส้นทาง |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index)`](/slides/python-net/th/aspose.slides/geometrypath/cubic_bezier_to/#float-float-float-float-float-float-int) | เพิ่มเส้นโค้งเบซิเยอร์แบบคิวบิกในตำแหน่งที่ระบุของเส้นทาง |
| [`quadratic_bezier_to(self, point1, point2)`](/slides/python-net/th/aspose.slides/geometrypath/quadratic_bezier_to/#asposeslidespointf-asposeslidespointf) | เพิ่มเส้นโค้งเบซิเยอร์แบบกำลังสองที่ส่วนท้ายของเส้นทาง |
| [`quadratic_bezier_to(self, x1, y1, x2, y2)`](/slides/python-net/th/aspose.slides/geometrypath/quadratic_bezier_to/#float-float-float-float) | เพิ่มเส้นโค้งเบซิเยอร์แบบกำลังสองที่ส่วนท้ายของเส้นทาง |
| [`quadratic_bezier_to(self, point1, point2, index)`](/slides/python-net/th/aspose.slides/geometrypath/quadratic_bezier_to/#asposeslidespointf-asposeslidespointf-int) | เพิ่มเส้นโค้งเบซิเยอร์แบบกำลังสองในตำแหน่งที่ระบุของเส้นทาง |
| [`quadratic_bezier_to(self, x1, y1, x2, y2, index)`](/slides/python-net/th/aspose.slides/geometrypath/quadratic_bezier_to/#float-float-float-float-int) | เพิ่มเส้นโค้งเบซิเยอร์แบบกำลังสองในตำแหน่งที่ระบุของเส้นทาง |
| [`move_to(self, point)`](/slides/python-net/th/aspose.slides/geometrypath/move_to/#asposeslidespointf) | ตั้งตำแหน่งจุดถัดไป |
| [`move_to(self, x, y)`](/slides/python-net/th/aspose.slides/geometrypath/move_to/#float-float) | ตั้งตำแหน่งจุดถัดไป |
| [`remove_at(self, index)`](/slides/python-net/th/aspose.slides/geometrypath/remove_at/#int) | ลบส่วนที่ตำแหน่งที่ระบุของเส้นทางเรขาคณิต |
| [`close_figure(self)`](/slides/python-net/th/aspose.slides/geometrypath/close_figure/#) | ปิดรูปแบบปัจจุบันของเส้นทางนี้ |
| [`arc_to(self, width, heigth, start_angle, sweep_angle)`](/slides/python-net/th/aspose.slides/geometrypath/arc_to/#float-float-float-float) | ต่อเติมส่วนโค้งที่ระบุเข้ากับเส้นทาง |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)