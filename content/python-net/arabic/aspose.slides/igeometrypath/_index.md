---
title: IGeometryPath class
second_title: Aspose.Slides لبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/igeometrypath/
---
## IGeometryPath الفئة

يمثل مسار الهندسة لشكل GeometryShape

يعرض نوع IGeometryPath الأعضاء التالية:

## الخصائص

| Property | Description |
| :- | :- |
| [`path_data`](/slides/python-net/ar/aspose.slides/igeometrypath/path_data/) | يعيد مسار الهندسة لـ GeometryShape كمصفوفة من مقاطع المسار. |
| [`fill_mode`](/slides/python-net/ar/aspose.slides/igeometrypath/fill_mode/) | يضبط وضع التعبئة |
| [`stroke`](/slides/python-net/ar/aspose.slides/igeometrypath/stroke/) | يضبط مظهر الحد |

## الطرق

| Method | Description |
| :- | :- |
| [`line_to(self, point)`](/slides/python-net/ar/aspose.slides/igeometrypath/line_to/#asposepydrawingpointf) | يضيف خطًا إلى نهاية المسار |
| [`line_to(self, x, y)`](/slides/python-net/ar/aspose.slides/igeometrypath/line_to/#float-float) | يضيف خطًا إلى نهاية المسار |
| [`line_to(self, point, index)`](/slides/python-net/ar/aspose.slides/igeometrypath/line_to/#asposepydrawingpointf-int) | يضيف خطًا إلى المكان المحدد في المسار |
| [`line_to(self, x, y, index)`](/slides/python-net/ar/aspose.slides/igeometrypath/line_to/#float-float-int) | يضيف خطًا إلى المكان المحدد في المسار |
| [`cubic_bezier_to(self, point1, point2, point3)`](/slides/python-net/ar/aspose.slides/igeometrypath/cubic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf) | يضيف منحنى بيزييه مكعّب في نهاية المسار |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3)`](/slides/python-net/ar/aspose.slides/igeometrypath/cubic_bezier_to/#float-float-float-float-float-float) | يضيف منحنى بيزييه مكعّب في نهاية المسار |
| [`cubic_bezier_to(self, point1, point2, point3, index)`](/slides/python-net/ar/aspose.slides/igeometrypath/cubic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf-int) | يضيف منحنى بيزييه مكعّب إلى المكان المحدد في المسار |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index)`](/slides/python-net/ar/aspose.slides/igeometrypath/cubic_bezier_to/#float-float-float-float-float-float-int) | يضيف منحنى بيزييه مكعّب إلى المكان المحدد في المسار |
| [`quadratic_bezier_to(self, point1, point2)`](/slides/python-net/ar/aspose.slides/igeometrypath/quadratic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf) | يضيف منحنى بيزييه تربيعي في نهاية المسار |
| [`quadratic_bezier_to(self, x1, y1, x2, y2)`](/slides/python-net/ar/aspose.slides/igeometrypath/quadratic_bezier_to/#float-float-float-float) | يضيف منحنى بيزييه تربيعي في نهاية المسار |
| [`quadratic_bezier_to(self, point1, point2, index)`](/slides/python-net/ar/aspose.slides/igeometrypath/quadratic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-int) | يضيف منحنى بيزييه تربيعي إلى المكان المحدد في المسار |
| [`quadratic_bezier_to(self, x1, y1, x2, y2, index)`](/slides/python-net/ar/aspose.slides/igeometrypath/quadratic_bezier_to/#float-float-float-float-int) | يضيف منحنى بيزييه تربيعي إلى المكان المحدد في المسار |
| [`move_to(self, point)`](/slides/python-net/ar/aspose.slides/igeometrypath/move_to/#asposepydrawingpointf) | يضبط موضع النقطة التالية. |
| [`move_to(self, x, y)`](/slides/python-net/ar/aspose.slides/igeometrypath/move_to/#float-float) | يضبط موضع النقطة التالية. |
| [`remove_at(self, index)`](/slides/python-net/ar/aspose.slides/igeometrypath/remove_at/#int) | يزال المقطع عند الفهرس المحدد لمسار الهندسة. |
| [`close_figure(self)`](/slides/python-net/ar/aspose.slides/igeometrypath/close_figure/#) | يغلق الشكل الحالي لهذا المسار |
| [`arc_to(self, width, heigth, start_angle, sweep_angle)`](/slides/python-net/ar/aspose.slides/igeometrypath/arc_to/#float-float-float-float) | يضيف القوس المحدد إلى المسار. |

### انظر أيضا
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)