---
title: GeometryPath class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/geometrypath/
---
## GeometryPath คลาส

แทนเส้นทางเรขาคณิตของ GeometryShape

ประเภท GeometryPath เปิดเผยสมาชิกต่อไปนี้:

## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| :- | :- |
| [`__init__(self)`](/slides/python-net/th/aspose.slides/geometrypath/__init__/#) | สร้างอินสแตนซ์ของ GeometryPath |

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`path_data`](/slides/python-net/th/aspose.slides/geometrypath/path_data/) | คืนค่าเส้นทางเรขาคณิตของ GeometryShape ในรูปแบบอาเรย์ของส่วนเส้นทาง |
| [`fill_mode`](/slides/python-net/th/aspose.slides/geometrypath/fill_mode/) | ตั้งค่าโหมดการเติม |
| [`stroke`](/slides/python-net/th/aspose.slides/geometrypath/stroke/) | ตั้งค่าลักษณะการวาดเส้น |

## เมธอด

| เมธอด | คำอธิบาย |
| :- | :- |
| [`line_to(self, point)`](/slides/python-net/th/aspose.slides/geometrypath/line_to/#asposepydrawingpointf) | เพิ่มเส้นตรงไปยังส่วนท้ายของเส้นทาง |
| [`line_to(self, x, y)`](/slides/python-net/th/aspose.slides/geometrypath/line_to/#float-float) | เพิ่มเส้นตรงไปยังส่วนท้ายของเส้นทาง |
| [`line_to(self, point, index)`](/slides/python-net/th/aspose.slides/geometrypath/line_to/#asposepydrawingpointf-int) | เพิ่มเส้นตรงไปยังตำแหน่งที่กำหนดของเส้นทาง |
| [`line_to(self, x, y, index)`](/slides/python-net/th/aspose.slides/geometrypath/line_to/#float-float-int) | เพิ่มเส้นตรงไปยังตำแหน่งที่กำหนดของเส้นทาง |
| [`cubic_bezier_to(self, point1, point2, point3)`](/slides/python-net/th/aspose.slides/geometrypath/cubic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf) | เพิ่มโค้ง Bezier แบบคิวบิกที่ส่วนท้ายของเส้นทาง |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3)`](/slides/python-net/th/aspose.slides/geometrypath/cubic_bezier_to/#float-float-float-float-float-float) | เพิ่มโค้ง Bezier แบบคิวบิกที่ส่วนท้ายของเส้นทาง |
| [`cubic_bezier_to(self, point1, point2, point3, index)`](/slides/python-net/th/aspose.slides/geometrypath/cubic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf-int) | เพิ่มโค้ง Bezier แบบคิวบิกไปยังตำแหน่งที่กำหนดของเส้นทาง |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index)`](/slides/python-net/th/aspose.slides/geometrypath/cubic_bezier_to/#float-float-float-float-float-float-int) | เพิ่มโค้ง Bezier แบบคิวบิกไปยังตำแหน่งที่กำหนดของเส้นทาง |
| [`quadratic_bezier_to(self, point1, point2)`](/slides/python-net/th/aspose.slides/geometrypath/quadratic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf) | เพิ่มโค้ง Bezier แบบควอดราติกที่ส่วนท้ายของเส้นทาง |
| [`quadratic_bezier_to(self, x1, y1, x2, y2)`](/slides/python-net/th/aspose.slides/geometrypath/quadratic_bezier_to/#float-float-float-float) | เพิ่มโค้ง Bezier แบบควอดราติกที่ส่วนท้ายของเส้นทาง |
| [`quadratic_bezier_to(self, point1, point2, index)`](/slides/python-net/th/aspose.slides/geometrypath/quadratic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-int) | เพิ่มโค้ง Bezier แบบควอดราติกไปยังตำแหน่งที่กำหนดของเส้นทาง |
| [`quadratic_bezier_to(self, x1, y1, x2, y2, index)`](/slides/python-net/th/aspose.slides/geometrypath/quadratic_bezier_to/#float-float-float-float-int) | เพิ่มโค้ง Bezier แบบควอดราติกไปยังตำแหน่งที่กำหนดของเส้นทาง |
| [`move_to(self, point)`](/slides/python-net/th/aspose.slides/geometrypath/move_to/#asposepydrawingpointf) | กำหนดตำแหน่งของจุดถัดไป |
| [`move_to(self, x, y)`](/slides/python-net/th/aspose.slides/geometrypath/move_to/#float-float) | กำหนดตำแหน่งของจุดถัดไป |
| [`remove_at(self, index)`](/slides/python-net/th/aspose.slides/geometrypath/remove_at/#int) | ลบส่วนของเส้นทางเรขาคณิตที่ตำแหน่งดัชนีที่ระบุ |
| [`close_figure(self)`](/slides/python-net/th/aspose.slides/geometrypath/close_figure/#) | ปิดรูปแบบปัจจุบันของเส้นทางนี้ |
| [`arc_to(self, width, heigth, start_angle, sweep_angle)`](/slides/python-net/th/aspose.slides/geometrypath/arc_to/#float-float-float-float) | เพิ่มส่วนโค้งที่ระบุลงในเส้นทาง |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)