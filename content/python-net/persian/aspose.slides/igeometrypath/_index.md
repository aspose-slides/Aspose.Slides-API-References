---
title: IGeometryPath class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/igeometrypath/
---
## IGeometryPath کلاس

نمایانگر مسیر هندسی GeometryShape

نوع IGeometryPath اعضای زیر را در اختیار می‌گذارد:

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`path_data`](/slides/python-net/fa/aspose.slides/igeometrypath/path_data/) | مسیر هندسی GeometryShape را به‌صورت آرایه‌ای از بخش‌های مسیر برمی‌گرداند. |
| [`fill_mode`](/slides/python-net/fa/aspose.slides/igeometrypath/fill_mode/) | حالت پرکردن را تنظیم می‌کند |
| [`stroke`](/slides/python-net/fa/aspose.slides/igeometrypath/stroke/) | ظاهر خط را تنظیم می‌کند |

## متدها

| متد | توضیح |
| :- | :- |
| [`line_to(self, point)`](/slides/python-net/fa/aspose.slides/igeometrypath/line_to/#asposepydrawingpointf) | خطی به انتهای مسیر اضافه می‌کند |
| [`line_to(self, x, y)`](/slides/python-net/fa/aspose.slides/igeometrypath/line_to/#float-float) | خطی به انتهای مسیر اضافه می‌کند |
| [`line_to(self, point, index)`](/slides/python-net/fa/aspose.slides/igeometrypath/line_to/#asposepydrawingpointf-int) | خطی به مکان مشخص شده مسیر اضافه می‌کند |
| [`line_to(self, x, y, index)`](/slides/python-net/fa/aspose.slides/igeometrypath/line_to/#float-float-int) | خطی به مکان مشخص شده مسیر اضافه می‌کند |
| [`cubic_bezier_to(self, point1, point2, point3)`](/slides/python-net/fa/aspose.slides/igeometrypath/cubic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf) | منحنی بزیه مکعبی را به انتهای مسیر اضافه می‌کند |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3)`](/slides/python-net/fa/aspose.slides/igeometrypath/cubic_bezier_to/#float-float-float-float-float-float) | منحنی بزیه مکعبی را به انتهای مسیر اضافه می‌کند |
| [`cubic_bezier_to(self, point1, point2, point3, index)`](/slides/python-net/fa/aspose.slides/igeometrypath/cubic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf-int) | منحنی بزیه مکعبی را به مکان مشخص شده مسیر اضافه می‌کند |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index)`](/slides/python-net/fa/aspose.slides/igeometrypath/cubic_bezier_to/#float-float-float-float-float-float-int) | منحنی بزیه مکعبی را به مکان مشخص شده مسیر اضافه می‌کند |
| [`quadratic_bezier_to(self, point1, point2)`](/slides/python-net/fa/aspose.slides/igeometrypath/quadratic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf) | منحنی بزیه درجه‌دوتایی را به انتهای مسیر اضافه می‌کند |
| [`quadratic_bezier_to(self, x1, y1, x2, y2)`](/slides/python-net/fa/aspose.slides/igeometrypath/quadratic_bezier_to/#float-float-float-float) | منحنی بزیه درجه‌دوتایی را به انتهای مسیر اضافه می‌کند |
| [`quadratic_bezier_to(self, point1, point2, index)`](/slides/python-net/fa/aspose.slides/igeometrypath/quadratic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-int) | منحنی بزیه درجه‌دوتایی را به مکان مشخص شده مسیر اضافه می‌کند |
| [`quadratic_bezier_to(self, x1, y1, x2, y2, index)`](/slides/python-net/fa/aspose.slides/igeometrypath/quadratic_bezier_to/#float-float-float-float-int) | منحنی بزیه درجه‌دوتایی را به مکان مشخص شده مسیر اضافه می‌کند |
| [`move_to(self, point)`](/slides/python-net/fa/aspose.slides/igeometrypath/move_to/#asposepydrawingpointf) | موقعیت نقطه بعدی را تنظیم می‌کند. |
| [`move_to(self, x, y)`](/slides/python-net/fa/aspose.slides/igeometrypath/move_to/#float-float) | موقعیت نقطه بعدی را تنظیم می‌کند. |
| [`remove_at(self, index)`](/slides/python-net/fa/aspose.slides/igeometrypath/remove_at/#int) | بخش را در ایندکس مشخص شده مسیر هندسی حذف می‌کند. |
| [`close_figure(self)`](/slides/python-net/fa/aspose.slides/igeometrypath/close_figure/#) | شکل جاری این مسیر را بسته می‌کند |
| [`arc_to(self, width, heigth, start_angle, sweep_angle)`](/slides/python-net/fa/aspose.slides/igeometrypath/arc_to/#float-float-float-float) | قوس مشخص شده را به مسیر اضافه می‌کند. |

### مراجع
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)