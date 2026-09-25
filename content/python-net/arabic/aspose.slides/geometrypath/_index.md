---
title: GeometryPath class
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/geometrypath/
---
## GeometryPath فئة

يمثل مسار هندسي ل GeometryShape

يعرض نوع GeometryPath الأعضاء التالية:

## المنشئون

| المنشئ | الوصف |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ar/aspose.slides/geometrypath/__init__/#) | إنشاء مثيل من GeometryPath |

## الخصائص

| خاصية | الوصف |
| :- | :- |
| [`path_data`](/slides/python-net/ar/aspose.slides/geometrypath/path_data/) | إرجاع مسار هندسي ل GeometryShape كمصفوفة من مقاطع المسار. |
| [`fill_mode`](/slides/python-net/ar/aspose.slides/geometrypath/fill_mode/) | تعيين وضع التعبئة |
| [`stroke`](/slides/python-net/ar/aspose.slides/geometrypath/stroke/) | تعيين مظهر الحد |

## الطرق

| طريقة | الوصف |
| :- | :- |
| [`line_to(self, point)`](/slides/python-net/ar/aspose.slides/geometrypath/line_to/#asposeslidespointf) | إضافة خط إلى نهاية المسار |
| [`line_to(self, x, y)`](/slides/python-net/ar/aspose.slides/geometrypath/line_to/#float-float) | إضافة خط إلى نهاية المسار |
| [`line_to(self, point, index)`](/slides/python-net/ar/aspose.slides/geometrypath/line_to/#asposeslidespointf-int) | إضافة خط إلى الموضع المحدد في المسار |
| [`line_to(self, x, y, index)`](/slides/python-net/ar/aspose.slides/geometrypath/line_to/#float-float-int) | إضافة خط إلى الموضع المحدد في المسار |
| [`cubic_bezier_to(self, point1, point2, point3)`](/slides/python-net/ar/aspose.slides/geometrypath/cubic_bezier_to/#asposeslidespointf-asposeslidespointf-asposeslidespointf) | إضافة منحنى بيزيه مكعب إلى نهاية المسار |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3)`](/slides/python-net/ar/aspose.slides/geometrypath/cubic_bezier_to/#float-float-float-float-float-float) | إضافة منحنى بيزيه مكعب إلى نهاية المسار |
| [`cubic_bezier_to(self, point1, point2, point3, index)`](/slides/python-net/ar/aspose.slides/geometrypath/cubic_bezier_to/#asposeslidespointf-asposeslidespointf-asposeslidespointf-int) | إضافة منحنى بيزيه مكعب إلى الموضع المحدد في المسار |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index)`](/slides/python-net/ar/aspose.slides/geometrypath/cubic_bezier_to/#float-float-float-float-float-float-int) | إضافة منحنى بيزيه مكعب إلى الموضع المحدد في المسار |
| [`quadratic_bezier_to(self, point1, point2)`](/slides/python-net/ar/aspose.slides/geometrypath/quadratic_bezier_to/#asposeslidespointf-asposeslidespointf) | إضافة منحنى بيزيه تربيعي إلى نهاية المسار |
| [`quadratic_bezier_to(self, x1, y1, x2, y2)`](/slides/python-net/ar/aspose.slides/geometrypath/quadratic_bezier_to/#float-float-float-float) | إضافة منحنى بيزيه تربيعي إلى نهاية المسار |
| [`quadratic_bezier_to(self, point1, point2, index)`](/slides/python-net/ar/aspose.slides/geometrypath/quadratic_bezier_to/#asposeslidespointf-asposeslidespointf-int) | إضافة منحنى بيزيه تربيعي إلى الموضع المحدد في المسار |
| [`quadratic_bezier_to(self, x1, y1, x2, y2, index)`](/slides/python-net/ar/aspose.slides/geometrypath/quadratic_bezier_to/#float-float-float-float-int) | إضافة منحنى بيزيه تربيعي إلى الموضع المحدد في المسار |
| [`move_to(self, point)`](/slides/python-net/ar/aspose.slides/geometrypath/move_to/#asposeslidespointf) | تعيين موضع النقطة التالية. |
| [`move_to(self, x, y)`](/slides/python-net/ar/aspose.slides/geometrypath/move_to/#float-float) | تعيين موضع النقطة التالية. |
| [`remove_at(self, index)`](/slides/python-net/ar/aspose.slides/geometrypath/remove_at/#int) | إزالة مقطع عند الفهرس المحدد من المسار الهندسي. |
| [`close_figure(self)`](/slides/python-net/ar/aspose.slides/geometrypath/close_figure/#) | إغلاق الشكل الحالي لهذا المسار |
| [`arc_to(self, width, heigth, start_angle, sweep_angle)`](/slides/python-net/ar/aspose.slides/geometrypath/arc_to/#float-float-float-float) | إلحاق القوس المحدد بالمسار. |

### انظر أيضًا
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)