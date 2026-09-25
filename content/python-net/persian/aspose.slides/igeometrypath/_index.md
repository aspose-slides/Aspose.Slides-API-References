---
title: IGeometryPath class
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/igeometrypath/
---
## IGeometryPath کلاس

نمایانگر مسیر هندسی GeometryShape

نوع IGeometryPath اعضای زیر را نمایان می‌کند:

## خواص

| Property | Description |
| :- | :- |
| [`path_data`](/slides/python-net/fa/aspose.slides/igeometrypath/path_data/) | مسیر هندسی GeometryShape را به‌عنوان یک آرایه‌ای از بخش‌های مسیر برمی‌گرداند. |
| [`fill_mode`](/slides/python-net/fa/aspose.slides/igeometrypath/fill_mode/) | حالت پر کردن را تنظیم می‌کند |
| [`stroke`](/slides/python-net/fa/aspose.slides/igeometrypath/stroke/) | ظاهر خط را تنظیم می‌کند |

## متدها

| Method | Description |
| :- | :- |
| [`line_to(self, point)`](/slides/python-net/fa/aspose.slides/igeometrypath/line_to/#asposeslidespointf) | خطی به انتهای مسیر اضافه می‌کند |
| [`line_to(self, x, y)`](/slides/python-net/fa/aspose.slides/igeometrypath/line_to/#float-float) | خطی به انتهای مسیر اضافه می‌کند |
| [`line_to(self, point, index)`](/slides/python-net/fa/aspose.slides/igeometrypath/line_to/#asposeslidespointf-int) | خطی به مکان مشخص شده مسیر اضافه می‌کند |
| [`line_to(self, x, y, index)`](/slides/python-net/fa/aspose.slides/igeometrypath/line_to/#float-float-int) | خطی به مکان مشخص شده مسیر اضافه می‌کند |
| [`cubic_bezier_to(self, point1, point2, point3)`](/slides/python-net/fa/aspose.slides/igeometrypath/cubic_bezier_to/#asposeslidespointf-asposeslidespointf-asposeslidespointf) | منحنی بزیهٔ مکعبی را به انتهای مسیر اضافه می‌کند |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3)`](/slides/python-net/fa/aspose.slides/igeometrypath/cubic_bezier_to/#float-float-float-float-float-float) | منحنی بزیهٔ مکعبی را به انتهای مسیر اضافه می‌کند |
| [`cubic_bezier_to(self, point1, point2, point3, index)`](/slides/python-net/fa/aspose.slides/igeometrypath/cubic_bezier_to/#asposeslidespointf-asposeslidespointf-asposeslidespointf-int) | منحنی بزیهٔ مکعبی را به مکان مشخص شده مسیر اضافه می‌کند |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index)`](/slides/python-net/fa/aspose.slides/igeometrypath/cubic_bezier_to/#float-float-float-float-float-float-int) | منحنی بزیهٔ مکعبی را به مکان مشخص شده مسیر اضافه می‌کند |
| [`quadratic_bezier_to(self, point1, point2)`](/slides/python-net/fa/aspose.slides/igeometrypath/quadratic_bezier_to/#asposeslidespointf-asposeslidespointf) | منحنی بزیهٔ درجه دو را به انتهای مسیر اضافه می‌کند |
| [`quadratic_bezier_to(self, x1, y1, x2, y2)`](/slides/python-net/fa/aspose.slides/igeometrypath/quadratic_bezier_to/#float-float-float-float) | منحنی بزیهٔ درجه دو را به انتهای مسیر اضافه می‌کند |
| [`quadratic_bezier_to(self, point1, point2, index)`](/slides/python-net/fa/aspose.slides/igeometrypath/quadratic_bezier_to/#asposeslidespointf-asposeslidespointf-int) | منحنی بزیهٔ درجه دو را به مکان مشخص شده مسیر اضافه می‌کند |
| [`quadratic_bezier_to(self, x1, y1, x2, y2, index)`](/slides/python-net/fa/aspose.slides/igeometrypath/quadratic_bezier_to/#float-float-float-float-int) | منحنی بزیهٔ درجه دو را به مکان مشخص شده مسیر اضافه می‌کند |
| [`move_to(self, point)`](/slides/python-net/fa/aspose.slides/igeometrypath/move_to/#asposeslidespointf) | موقعیت نقطهٔ بعدی را تنظیم می‌کند. |
| [`move_to(self, x, y)`](/slides/python-net/fa/aspose.slides/igeometrypath/move_to/#float-float) | موقعیت نقطهٔ بعدی را تنظیم می‌کند. |
| [`remove_at(self, index)`](/slides/python-net/fa/aspose.slides/igeometrypath/remove_at/#int) | بخش در شاخص مشخص شده مسیر هندسی را حذف می‌کند. |
| [`close_figure(self)`](/slides/python-net/fa/aspose.slides/igeometrypath/close_figure/#) | شکل جاری این مسیر را می‌بندد |
| [`arc_to(self, width, heigth, start_angle, sweep_angle)`](/slides/python-net/fa/aspose.slides/igeometrypath/arc_to/#float-float-float-float) | قوس مشخص‌شده را به مسیر اضافه می‌کند. |

### موارد مرتبط
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)