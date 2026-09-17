---
title: GeometryPath class
second_title: Aspose.Slides لبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/geometrypath/
---
## GeometryPath فئة

يمثل مسار الشكل الهندسي GeometryShape

نوع GeometryPath يعرّف الأعضاء التالية:

## المُنشئات

| المُنشئ | الوصف |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ar/aspose.slides/geometrypath/__init__/#) | ينشئ مثلاً من GeometryPath |

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`path_data`](/slides/python-net/ar/aspose.slides/geometrypath/path_data/) | يرجع مسار الشكل الهندسي GeometryShape كمصفوفة من أقسام المسار. |
| [`fill_mode`](/slides/python-net/ar/aspose.slides/geometrypath/fill_mode/) |يضبط وضع الملء |
| [`stroke`](/slides/python-net/ar/aspose.slides/geometrypath/stroke/) |يضبط مظهر الحد |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`line_to(self, point)`](/slides/python-net/ar/aspose.slides/geometrypath/line_to/#asposepydrawingpointf) | يضيف خطًا إلى نهاية المسار |
| [`line_to(self, x, y)`](/slides/python-net/ar/aspose.slides/geometrypath/line_to/#float-float) | يضيف خطًا إلى نهاية المسار |
| [`line_to(self, point, index)`](/slides/python-net/ar/aspose.slides/geometrypath/line_to/#asposepydrawingpointf-int) | يضيف خطًا إلى الموضع المحدد في المسار |
| [`line_to(self, x, y, index)`](/slides/python-net/ar/aspose.slides/geometrypath/line_to/#float-float-int) | يضيف خطًا إلى الموضع المحدد في المسار |
| [`cubic_bezier_to(self, point1, point2, point3)`](/slides/python-net/ar/aspose.slides/geometrypath/cubic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf) | يضيف منحنى بيزىيري مكعّب إلى نهاية المسار |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3)`](/slides/python-net/ar/aspose.slides/geometrypath/cubic_bezier_to/#float-float-float-float-float-float) | يضيف منحنى بيزىيري مكعّب إلى نهاية المسار |
| [`cubic_bezier_to(self, point1, point2, point3, index)`](/slides/python-net/ar/aspose.slides/geometrypath/cubic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf-int) | يضيف منحنى بيزىيري مكعّب إلى الموضع المحدد في المسار |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index)`](/slides/python-net/ar/aspose.slides/geometrypath/cubic_bezier_to/#float-float-float-float-float-float-int) | يضيف منحنى بيزىيري مكعّب إلى الموضع المحدد في المسار |
| [`quadratic_bezier_to(self, point1, point2)`](/slides/python-net/ar/aspose.slides/geometrypath/quadratic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf) | يضيف منحنى بيزىيري تربيعي إلى نهاية المسار |
| [`quadratic_bezier_to(self, x1, y1, x2, y2)`](/slides/python-net/ar/aspose.slides/geometrypath/quadratic_bezier_to/#float-float-float-float) | يضيف منحنى بيزىيري تربيعي إلى نهاية المسار |
| [`quadratic_bezier_to(self, point1, point2, index)`](/slides/python-net/ar/aspose.slides/geometrypath/quadratic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-int) | يضيف منحنى بيزىيري تربيعي إلى الموضع المحدد في المسار |
| [`quadratic_bezier_to(self, x1, y1, x2, y2, index)`](/slides/python-net/ar/aspose.slides/geometrypath/quadratic_bezier_to/#float-float-float-float-int) | يضيف منحنى بيزىيري تربيعي إلى الموضع المحدد في المسار |
| [`move_to(self, point)`](/slides/python-net/ar/aspose.slides/geometrypath/move_to/#asposepydrawingpointf) | يحدد موضع النقطة التالية. |
| [`move_to(self, x, y)`](/slides/python-net/ar/aspose.slides/geometrypath/move_to/#float-float) | يحدد موضع النقطة التالية. |
| [`remove_at(self, index)`](/slides/python-net/ar/aspose.slides/geometrypath/remove_at/#int) | يزيل الجزء عند الفهرس المحدد في مسار الشكل الهندسي. |
| [`close_figure(self)`](/slides/python-net/ar/aspose.slides/geometrypath/close_figure/#) | يغلق الشكل الحالي لهذا المسار |
| [`arc_to(self, width, heigth, start_angle, sweep_angle)`](/slides/python-net/ar/aspose.slides/geometrypath/arc_to/#float-float-float-float) | يضيف القوس المحدد إلى المسار. |

### انظر أيضًا
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)