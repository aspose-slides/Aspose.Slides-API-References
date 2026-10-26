---
title: Rotation3D class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/rotation3d/
---
## Rotation3D 类

表示图表的 3D 旋转。

Rotation3D 类型公开以下成员：

## 属性

| Property | Description |
| :- | :- |
| [`rotation_x`](/slides/python-net/zh/aspose.slides.charts/rotation3d/rotation_x/) | 返回或设置围绕 X 轴的旋转角度，即 3D 图表的 Y 方向（范围为 -90 到 90 度）。<br/>该属性对应 ECMA-376 中的 21.2.2.157 rotX (X Rotation) 项以及 PowerPoint 2007+ 中的 "Y Rotation" 选项。<br/>读/写 **int**. |
| [`rotation_y`](/slides/python-net/zh/aspose.slides.charts/rotation3d/rotation_y/) | 返回或设置围绕 Y 轴的旋转角度，即 3D 图表的 X 方向（范围为 0 到 360 度）。<br/>该属性对应 ECMA-376 中的 21.2.2.158 rotY (Y Rotation) 项以及 PowerPoint 2007+ 中的 "X Rotation" 选项。<br/>读/写 **int**. |
| [`perspective`](/slides/python-net/zh/aspose.slides.charts/rotation3d/perspective/) | 返回或设置 3D 图表的透视值（视场角）（范围为 0 到 240）。<br/>如果 RightAngleAxes 属性值为 true，则忽略此设置。<br/>读/写 **int**. |
| [`right_angle_axes`](/slides/python-net/zh/aspose.slides.charts/rotation3d/right_angle_axes/) | 确定图表坐标轴是否为直角，而不是以透视方式绘制。<br/>换句话说，它决定坐标轴的图表角度是否独立于图表 <br/>旋转或倾斜。<br/>读/写 **bool**. |
| [`depth_percents`](/slides/python-net/zh/aspose.slides.charts/rotation3d/depth_percents/) | 返回或设置 3D 图表的深度，以图表宽度的百分比表示（范围为 20% 到 2000%）。<br/>读/写 **int**. |
| [`height_percents`](/slides/python-net/zh/aspose.slides.charts/rotation3d/height_percents/) | 指定 3-D 图表的高度，以图表宽度的百分比表示（范围为 5% 到 500%）。<br/>读/写 **int**. |

### 另请参见
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)