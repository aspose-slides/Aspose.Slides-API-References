---
title: IGeometryPath class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET อ้างอิง API
description: 
type: docs
url: /th/aspose.slides/igeometrypath/
---
## IGeometryPath คลาส

แสดงเส้นทางเรขาคณิตของ GeometryShape

ชนิด IGeometryPath เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`path_data`](/slides/python-net/th/aspose.slides/igeometrypath/path_data/) | คืนค่าเส้นทางเรขาคณิตของ GeometryShape เป็นอาร์เรย์ของส่วนของเส้นทาง |
| [`fill_mode`](/slides/python-net/th/aspose.slides/igeometrypath/fill_mode/) | ตั้งค่าโหมดการเติม |
| [`stroke`](/slides/python-net/th/aspose.slides/igeometrypath/stroke/) | ตั้งค่าลักษณะการขีด |

## วิธีการ

| Method | Description |
| :- | :- |
| [`line_to(self, point)`](/slides/python-net/th/aspose.slides/igeometrypath/line_to/#asposeslidespointf) | เพิ่มเส้นตรงที่ส่วนท้ายของเส้นทาง |
| [`line_to(self, x, y)`](/slides/python-net/th/aspose.slides/igeometrypath/line_to/#float-float) | เพิ่มเส้นตรงที่ส่วนท้ายของเส้นทาง |
| [`line_to(self, point, index)`](/slides/python-net/th/aspose.slides/igeometrypath/line_to/#asposeslidespointf-int) | เพิ่มเส้นตรงที่ตำแหน่งที่ระบุของเส้นทาง |
| [`line_to(self, x, y, index)`](/slides/python-net/th/aspose.slides/igeometrypath/line_to/#float-float-int) | เพิ่มเส้นตรงที่ตำแหน่งที่ระบุของเส้นทาง |
| [`cubic_bezier_to(self, point1, point2, point3)`](/slides/python-net/th/aspose.slides/igeometrypath/cubic_bezier_to/#asposeslidespointf-asposeslidespointf-asposeslidespointf) | เพิ่มเส้นโค้ง Bezier Cubic ที่ส่วนท้ายของเส้นทาง |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3)`](/slides/python-net/th/aspose.slides/igeometrypath/cubic_bezier_to/#float-float-float-float-float-float) | เพิ่มเส้นโค้ง Bezier Cubic ที่ส่วนท้ายของเส้นทาง |
| [`cubic_bezier_to(self, point1, point2, point3, index)`](/slides/python-net/th/aspose.slides/igeometrypath/cubic_bezier_to/#asposeslidespointf-asposeslidespointf-asposeslidespointf-int) | เพิ่มเส้นโค้ง Bezier Cubic ที่ตำแหน่งที่ระบุของเส้นทาง |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index)`](/slides/python-net/th/aspose.slides/igeometrypath/cubic_bezier_to/#float-float-float-float-float-float-int) | เพิ่มเส้นโค้ง Bezier Cubic ที่ตำแหน่งที่ระบุของเส้นทาง |
| [`quadratic_bezier_to(self, point1, point2)`](/slides/python-net/th/aspose.slides/igeometrypath/quadratic_bezier_to/#asposeslidespointf-asposeslidespointf) | เพิ่มเส้นโค้ง Bezier Quadratic ที่ส่วนท้ายของเส้นทาง |
| [`quadratic_bezier_to(self, x1, y1, x2, y2)`](/slides/python-net/th/aspose.slides/igeometrypath/quadratic_bezier_to/#float-float-float-float) | เพิ่มเส้นโค้ง Bezier Quadratic ที่ส่วนท้ายของเส้นทาง |
| [`quadratic_bezier_to(self, point1, point2, index)`](/slides/python-net/th/aspose.slides/igeometrypath/quadratic_bezier_to/#asposeslidespointf-asposeslidespointf-int) | เพิ่มเส้นโค้ง Bezier Quadratic ที่ตำแหน่งที่ระบุของเส้นทาง |
| [`quadratic_bezier_to(self, x1, y1, x2, y2, index)`](/slides/python-net/th/aspose.slides/igeometrypath/quadratic_bezier_to/#float-float-float-float-int) | เพิ่มเส้นโค้ง Bezier Quadratic ที่ตำแหน่งที่ระบุของเส้นทาง |
| [`move_to(self, point)`](/slides/python-net/th/aspose.slides/igeometrypath/move_to/#asposeslidespointf) | ตั้งค่าตำแหน่งจุดถัดไป |
| [`move_to(self, x, y)`](/slides/python-net/th/aspose.slides/igeometrypath/move_to/#float-float) | ตั้งค่าตำแหน่งจุดถัดไป |
| [`remove_at(self, index)`](/slides/python-net/th/aspose.slides/igeometrypath/remove_at/#int) | ลบส่วนที่ตำแหน่งดัชนีที่ระบุของเส้นทางเรขาคณิต |
| [`close_figure(self)`](/slides/python-net/th/aspose.slides/igeometrypath/close_figure/#) | ปิดรูปภาพปัจจุบันของเส้นทางนี้ |
| [`arc_to(self, width, heigth, start_angle, sweep_angle)`](/slides/python-net/th/aspose.slides/igeometrypath/arc_to/#float-float-float-float) | ต่อท้ายส่วนโค้งที่ระบุลงในเส้นทาง |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)