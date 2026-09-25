---
title: GeometryPath class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/geometrypath/
---
## GeometryPath 类

表示 GeometryShape 的几何路径

GeometryPath 类型公开以下成员：

## 构造函数

| 构造函数 | 描述 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/zh/aspose.slides/geometrypath/__init__/#) | 创建 GeometryPath 的实例 |

## 属性

| 属性 | 描述 |
| :- | :- |
| [`path_data`](/slides/python-net/zh/aspose.slides/geometrypath/path_data/) | 返回 GeometryShape 的几何路径，作为路径段数组。 |
| [`fill_mode`](/slides/python-net/zh/aspose.slides/geometrypath/fill_mode/) | 设置填充模式 |
| [`stroke`](/slides/python-net/zh/aspose.slides/geometrypath/stroke/) | 设置描边外观 |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`line_to(self, point)`](/slides/python-net/zh/aspose.slides/geometrypath/line_to/#asposeslidespointf) | 在路径末尾添加直线 |
| [`line_to(self, x, y)`](/slides/python-net/zh/aspose.slides/geometrypath/line_to/#float-float) | 在路径末尾添加直线 |
| [`line_to(self, point, index)`](/slides/python-net/zh/aspose.slides/geometrypath/line_to/#asposeslidespointf-int) | 在路径的指定位置添加直线 |
| [`line_to(self, x, y, index)`](/slides/python-net/zh/aspose.slides/geometrypath/line_to/#float-float-int) | 在路径的指定位置添加直线 |
| [`cubic_bezier_to(self, point1, point2, point3)`](/slides/python-net/zh/aspose.slides/geometrypath/cubic_bezier_to/#asposeslidespointf-asposeslidespointf-asposeslidespointf) | 在路径末尾添加立方贝塞尔曲线 |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3)`](/slides/python-net/zh/aspose.slides/geometrypath/cubic_bezier_to/#float-float-float-float-float-float) | 在路径末尾添加立方贝塞尔曲线 |
| [`cubic_bezier_to(self, point1, point2, point3, index)`](/slides/python-net/zh/aspose.slides/geometrypath/cubic_bezier_to/#asposeslidespointf-asposeslidespointf-asposeslidespointf-int) | 在路径的指定位置添加立方贝塞尔曲线 |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index)`](/slides/python-net/zh/aspose.slides/geometrypath/cubic_bezier_to/#float-float-float-float-float-float-int) | 在路径的指定位置添加立方贝塞尔曲线 |
| [`quadratic_bezier_to(self, point1, point2)`](/slides/python-net/zh/aspose.slides/geometrypath/quadratic_bezier_to/#asposeslidespointf-asposeslidespointf) | 在路径末尾添加二次贝塞尔曲线 |
| [`quadratic_bezier_to(self, x1, y1, x2, y2)`](/slides/python-net/zh/aspose.slides/geometrypath/quadratic_bezier_to/#float-float-float-float) | 在路径末尾添加二次贝塞尔曲线 |
| [`quadratic_bezier_to(self, point1, point2, index)`](/slides/python-net/zh/aspose.slides/geometrypath/quadratic_bezier_to/#asposeslidespointf-asposeslidespointf-int) | 在路径的指定位置添加二次贝塞尔曲线 |
| [`quadratic_bezier_to(self, x1, y1, x2, y2, index)`](/slides/python-net/zh/aspose.slides/geometrypath/quadratic_bezier_to/#float-float-float-float-int) | 在路径的指定位置添加二次贝塞尔曲线 |
| [`move_to(self, point)`](/slides/python-net/zh/aspose.slides/geometrypath/move_to/#asposeslidespointf) | 设置下一个点的位置。 |
| [`move_to(self, x, y)`](/slides/python-net/zh/aspose.slides/geometrypath/move_to/#float-float) | 设置下一个点的位置。 |
| [`remove_at(self, index)`](/slides/python-net/zh/aspose.slides/geometrypath/remove_at/#int) | 删除几何路径中指定索引的段。 |
| [`close_figure(self)`](/slides/python-net/zh/aspose.slides/geometrypath/close_figure/#) | 关闭此路径的当前图形 |
| [`arc_to(self, width, heigth, start_angle, sweep_angle)`](/slides/python-net/zh/aspose.slides/geometrypath/arc_to/#float-float-float-float) | 将指定的弧线追加到路径。 |

### 另请参见
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)