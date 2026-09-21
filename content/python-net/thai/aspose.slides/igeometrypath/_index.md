---
title: IGeometryPath class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/igeometrypath/
---
## IGeometryPath คลาส

แทนที่ geometry path ของ GeometryShape

ประเภท IGeometryPath เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`path_data`](/slides/python-net/th/aspose.slides/igeometrypath/path_data/) | ส่งคืน geometry path ของ GeometryShape เป็นอาเรย์ของ path segments. |
| [`fill_mode`](/slides/python-net/th/aspose.slides/igeometrypath/fill_mode/) | ตั้งค่า fill mode |
| [`stroke`](/slides/python-net/th/aspose.slides/igeometrypath/stroke/) | ตั้งค่า stroke appearance |

## เมธอด

| เมธอด | คำอธิบาย |
| :- | :- |
| [`line_to(self, point)`](/slides/python-net/th/aspose.slides/igeometrypath/line_to/#asposepydrawingpointf) | เพิ่ม line ไปยังท้ายของ path |
| [`line_to(self, x, y)`](/slides/python-net/th/aspose.slides/igeometrypath/line_to/#float-float) | เพิ่ม line ไปยังท้ายของ path |
| [`line_to(self, point, index)`](/slides/python-net/th/aspose.slides/igeometrypath/line_to/#asposepydrawingpointf-int) | เพิ่ม line ไปยังตำแหน่งที่ระบุของ path |
| [`line_to(self, x, y, index)`](/slides/python-net/th/aspose.slides/igeometrypath/line_to/#float-float-int) | เพิ่ม line ไปยังตำแหน่งที่ระบุของ path |
| [`cubic_bezier_to(self, point1, point2, point3)`](/slides/python-net/th/aspose.slides/igeometrypath/cubic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf) | เพิ่ม cubic Bezier curve ที่ท้ายของ path |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3)`](/slides/python-net/th/aspose.slides/igeometrypath/cubic_bezier_to/#float-float-float-float-float-float) | เพิ่ม cubic Bezier curve ที่ท้ายของ path |
| [`cubic_bezier_to(self, point1, point2, point3, index)`](/slides/python-net/th/aspose.slides/igeometrypath/cubic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf-int) | เพิ่ม cubic Bezier curve ไปยังตำแหน่งที่ระบุของ path |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index)`](/slides/python-net/th/aspose.slides/igeometrypath/cubic_bezier_to/#float-float-float-float-float-float-int) | เพิ่ม cubic Bezier curve ไปยังตำแหน่งที่ระบุของ path |
| [`quadratic_bezier_to(self, point1, point2)`](/slides/python-net/th/aspose.slides/igeometrypath/quadratic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf) | เพิ่ม quadratic Bezier curve ที่ท้ายของ path |
| [`quadratic_bezier_to(self, x1, y1, x2, y2)`](/slides/python-net/th/aspose.slides/igeometrypath/quadratic_bezier_to/#float-float-float-float) | เพิ่ม quadratic Bezier curve ที่ท้ายของ path |
| [`quadratic_bezier_to(self, point1, point2, index)`](/slides/python-net/th/aspose.slides/igeometrypath/quadratic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-int) | เพิ่ม quadratic Bezier curve ไปยังตำแหน่งที่ระบุของ path |
| [`quadratic_bezier_to(self, x1, y1, x2, y2, index)`](/slides/python-net/th/aspose.slides/igeometrypath/quadratic_bezier_to/#float-float-float-float-int) | เพิ่ม quadratic Bezier curve ไปยังตำแหน่งที่ระบุของ path |
| [`move_to(self, point)`](/slides/python-net/th/aspose.slides/igeometrypath/move_to/#asposepydrawingpointf) | ตั้งค่า next point position. |
| [`move_to(self, x, y)`](/slides/python-net/th/aspose.slides/igeometrypath/move_to/#float-float) | ตั้งค่า next point position. |
| [`remove_at(self, index)`](/slides/python-net/th/aspose.slides/igeometrypath/remove_at/#int) | ลบ segment ที่ตำแหน่ง index ที่ระบุของ geometry path. |
| [`close_figure(self)`](/slides/python-net/th/aspose.slides/igeometrypath/close_figure/#) | ปิด figure ปัจจุบันของ path นี้ |
| [`arc_to(self, width, heigth, start_angle, sweep_angle)`](/slides/python-net/th/aspose.slides/igeometrypath/arc_to/#float-float-float-float) | ต่อท้าย arc ที่ระบุไปยัง path. |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)