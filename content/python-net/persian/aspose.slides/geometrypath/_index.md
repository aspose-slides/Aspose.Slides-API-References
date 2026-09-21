---
title: GeometryPath class
second_title: Aspose.Slides برای Python از طریق .NET API مرجع
description: 
type: docs
url: /fa/aspose.slides/geometrypath/
---
## GeometryPath کلاس

نمایانگر مسیر هندسی GeometryShape

نوع GeometryPath اعضای زیر را ارائه می‌دهد:

## سازنده‌ها

| سازنده | توضیح |
| :- | :- |
| [`__init__(self)`](/slides/python-net/fa/aspose.slides/geometrypath/__init__/#) | Creates instance of GeometryPath |

## خصوصیات

| خصوصیت | توضیح |
| :- | :- |
| [`path_data`](/slides/python-net/fa/aspose.slides/geometrypath/path_data/) | مسیر هندسی GeometryShape را به‌صورت آرایه‌ای از بخش‌های مسیر برمی‌گرداند. |
| [`fill_mode`](/slides/python-net/fa/aspose.slides/geometrypath/fill_mode/) | حالت پر کردن را تنظیم می‌کند |
| [`stroke`](/slides/python-net/fa/aspose.slides/geometrypath/stroke/) | ظاهر خط را تنظیم می‌کند |

## متدها

| متد | توضیح |
| :- | :- |
| [`line_to(self, point)`](/slides/python-net/fa/aspose.slides/geometrypath/line_to/#asposepydrawingpointf) | خطی را به انتهای مسیر اضافه می‌کند |
| [`line_to(self, x, y)`](/slides/python-net/fa/aspose.slides/geometrypath/line_to/#float-float) | خطی را به انتهای مسیر اضافه می‌کند |
| [`line_to(self, point, index)`](/slides/python-net/fa/aspose.slides/geometrypath/line_to/#asposepydrawingpointf-int) | خطی را به مکان مشخصی از مسیر اضافه می‌کند |
| [`line_to(self, x, y, index)`](/slides/python-net/fa/aspose.slides/geometrypath/line_to/#float-float-int) | خطی را به مکان مشخصی از مسیر اضافه می‌کند |
| [`cubic_bezier_to(self, point1, point2, point3)`](/slides/python-net/fa/aspose.slides/geometrypath/cubic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf) | منحنی بزیه مکعبی را در انتهای مسیر اضافه می‌کند |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3)`](/slides/python-net/fa/aspose.slides/geometrypath/cubic_bezier_to/#float-float-float-float-float-float) | منحنی بزیه مکعبی را در انتهای مسیر اضافه می‌کند |
| [`cubic_bezier_to(self, point1, point2, point3, index)`](/slides/python-net/fa/aspose.slides/geometrypath/cubic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf-int) | منحنی بزیه مکعبی را به مکان مشخصی از مسیر اضافه می‌کند |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index)`](/slides/python-net/fa/aspose.slides/geometrypath/cubic_bezier_to/#float-float-float-float-float-float-int) | منحنی بزیه مکعبی را به مکان مشخصی از مسیر اضافه می‌کند |
| [`quadratic_bezier_to(self, point1, point2)`](/slides/python-net/fa/aspose.slides/geometrypath/quadratic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf) | منحنی بزیه درجه‌دوگانه را در انتهای مسیر اضافه می‌کند |
| [`quadratic_bezier_to(self, x1, y1, x2, y2)`](/slides/python-net/fa/aspose.slides/geometrypath/quadratic_bezier_to/#float-float-float-float) | منحنی بزیه درجه‌دوگانه را در انتهای مسیر اضافه می‌کند |
| [`quadratic_bezier_to(self, point1, point2, index)`](/slides/python-net/fa/aspose.slides/geometrypath/quadratic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-int) | منحنی بزیه درجه‌دوگانه را به مکان مشخصی از مسیر اضافه می‌کند |
| [`quadratic_bezier_to(self, x1, y1, x2, y2, index)`](/slides/python-net/fa/aspose.slides/geometrypath/quadratic_bezier_to/#float-float-float-float-int) | منحنی بزیه درجه‌دوگانه را به مکان مشخصی از مسیر اضافه می‌کند |
| [`move_to(self, point)`](/slides/python-net/fa/aspose.slides/geometrypath/move_to/#asposepydrawingpointf) | موقعیت نقطه بعدی را تنظیم می‌کند. |
| [`move_to(self, x, y)`](/slides/python-net/fa/aspose.slides/geometrypath/move_to/#float-float) | موقعیت نقطه بعدی را تنظیم می‌کند. |
| [`remove_at(self, index)`](/slides/python-net/fa/aspose.slides/geometrypath/remove_at/#int) | بخش را در اندیس مشخص از مسیر هندسی حذف می‌کند. |
| [`close_figure(self)`](/slides/python-net/fa/aspose.slides/geometrypath/close_figure/#) | شکل فعلی این مسیر را می‌بندد |
| [`arc_to(self, width, heigth, start_angle, sweep_angle)`](/slides/python-net/fa/aspose.slides/geometrypath/arc_to/#float-float-float-float) | قوس مشخص‌شده را به مسیر اضافه می‌کند. |

### موارد مرتبط
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)