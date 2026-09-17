---
title: IGeometryPath class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/igeometrypath/
---
## IGeometryPath 类

表示 GeometryShape 的几何路径

IGeometryPath 类型公开以下成员：

## 属性

| Property | Description |
| :- | :- |
| [`path_data`](/slides/python-net/zh/aspose.slides/igeometrypath/path_data/) | 返回 GeometryShape 的几何路径，作为路径段数组。 |
| [`fill_mode`](/slides/python-net/zh/aspose.slides/igeometrypath/fill_mode/) | 设置填充模式 |
| [`stroke`](/slides/python-net/zh/aspose.slides/igeometrypath/stroke/) | 设置描边外观 |

## 方法

| Method | Description |
| :- | :- |
| [`line_to(self, point)`](/slides/python-net/zh/aspose.slides/igeometrypath/line_to/#asposepydrawingpointf) | 在路径末尾添加直线 |
| [`line_to(self, x, y)`](/slides/python-net/zh/aspose.slides/igeometrypath/line_to/#float-float) | 在路径末尾添加直线 |
| [`line_to(self, point, index)`](/slides/python-net/zh/aspose.slides/igeometrypath/line_to/#asposepydrawingpointf-int) | 在路径的指定位置添加直线 |
| [`line_to(self, x, y, index)`](/slides/python-net/zh/aspose.slides/igeometrypath/line_to/#float-float-int) | 在路径的指定位置添加直线 |
| [`cubic_bezier_to(self, point1, point2, point3)`](/slides/python-net/zh/aspose.slides/igeometrypath/cubic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf) | 在路径末尾添加三次贝塞尔曲线 |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3)`](/slides/python-net/zh/aspose.slides/igeometrypath/cubic_bezier_to/#float-float-float-float-float-float) | 在路径末尾添加三次贝塞尔曲线 |
| [`cubic_bezier_to(self, point1, point2, point3, index)`](/slides/python-net/zh/aspose.slides/igeometrypath/cubic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf-int) | 在路径的指定位置添加三次贝塞尔曲线 |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index)`](/slides/python-net/zh/aspose.slides/igeometrypath/cubic_bezier_to/#float-float-float-float-float-float-int) | 在路径的指定位置添加三次贝塞尔曲线 |
| [`quadratic_bezier_to(self, point1, point2)`](/slides/python-net/zh/aspose.slides/igeometrypath/quadratic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf) | 在路径末尾添加二次贝塞尔曲线 |
| [`quadratic_bezier_to(self, x1, y1, x2, y2)`](/slides/python-net/zh/aspose.slides/igeometrypath/quadratic_bezier_to/#float-float-float-float) | 在路径末尾添加二次贝塞尔曲线 |
| [`quadratic_bezier_to(self, point1, point2, index)`](/slides/python-net/zh/aspose.slides/igeometrypath/quadratic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-int) | 在路径的指定位置添加二次贝塞尔曲线 |
| [`quadratic_bezier_to(self, x1, y1, x2, y2, index)`](/slides/python-net/zh/aspose.slides/igeometrypath/quadratic_bezier_to/#float-float-float-float-int) | 在路径的指定位置添加二次贝塞尔曲线 |
| [`move_to(self, point)`](/slides/python-net/zh/aspose.slides/igeometrypath/move_to/#asposepydrawingpointf) | 设置下一个点的位置。 |
| [`move_to(self, x, y)`](/slides/python-net/zh/aspose.slides/igeometrypath/move_to/#float-float) | 设置下一个点的位置。 |
| [`remove_at(self, index)`](/slides/python-net/zh/aspose.slides/igeometrypath/remove_at/#int) | 删除几何路径中指定索引处的段。 |
| [`close_figure(self)`](/slides/python-net/zh/aspose.slides/igeometrypath/close_figure/#) | 闭合此路径的当前图形 |
| [`arc_to(self, width, heigth, start_angle, sweep_angle)`](/slides/python-net/zh/aspose.slides/igeometrypath/arc_to/#float-float-float-float) | 将指定弧线追加到路径。 |

### 另请参见
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)