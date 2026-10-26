---
title: ColorTransformOperation enumeration
second_title: Aspose.Slides 用于 Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/colortransformoperation/
---
## ColorTransformOperation 枚举

定义颜色变换操作。

ColorTransformOperation 类型公开以下成员：

## 字段

| 字段 | 描述 |
| :- | :- |
| TINT | 为颜色添加色调。参数范围在 0（原始颜色）到 1（白色）之间。 |
| SHADE | 为颜色添加阴影。参数范围在 0（原始颜色）到 1（黑色）之间。 |
| COMPLEMENT | 将颜色更改为 RGB 补色。<br/>            m = Max(r, g, b);<br/>            r = m - r;<br/>            g = m - g;<br/>            b = m - b; |
| INVERSE | 将颜色更改为反转颜色。<br/>            r = 1 - r;<br/>            g = 1 - g;<br/>            b = 1 - b; |
| GRAYSCALE | 将颜色更改为具有相同亮度的灰色。参数被忽略。 |
| SET_ALPHA | 定义颜色的 alpha 分量。参数范围在 0（透明）到 1（不透明）之间。 |
| ADD_ALPHA | 将参数值加到颜色的 alpha 分量。参数范围在 -1 到 1 之间。 |
| MULTIPLY_ALPHA | 将 alpha 分量乘以参数值。 |
| SET_HUE | 将颜色的色相分量更改为参数值。参数范围在 0 到 360 之间。 |
| ADD_HUE | 将参数值加到颜色的色相分量。参数范围在 -360 到 360 之间。 |
| MULTIPLY_HUE | 将色相分量乘以参数值。 |
| SET_SATURATION | 将颜色的饱和度分量更改为参数值。参数范围在 0 到 1 之间。 |
| ADD_SATURATION | 将参数值加到颜色的饱和度分量。参数范围在 -1 到 1 之间。 |
| MULTIPLY_SATURATION | 将饱和度分量乘以参数值。 |
| SET_LUMINANCE | 将颜色的亮度分量更改为参数值。参数范围在 0 到 1 之间。 |
| ADD_LUMINANCE | 将参数值加到颜色的亮度分量。参数范围在 -1 到 1 之间。 |
| MULTIPLY_LUMINANCE | 将亮度分量乘以参数值。 |
| SET_RED | 将颜色的红色分量更改为参数值。参数范围在 0 到 1 之间。 |
| ADD_RED | 将参数值加到颜色的红色分量。参数范围在 -1 到 1 之间。 |
| MULTIPLY_RED | 将红色分量乘以参数。 |
| SET_GREEN | 将颜色的绿色分量更改为参数值。参数范围在 0 到 1 之间。 |
| ADD_GREEN | 将参数加到颜色的绿色分量。参数范围在 -1 到 1 之间。 |
| MULTIPLY_GREEN | 将绿色分量乘以参数值。 |
| SET_BLUE | 将颜色的蓝色分量更改为参数值。参数范围在 0 到 360 之间。 |
| ADD_BLUE | 将参数值加到颜色的蓝色分量。参数范围在 -1 到 1 之间。 |
| MULTIPLY_BLUE | 将蓝色分量乘以参数值。 |
| GAMMA | 伽马校正。参数被忽略。 |
| INVERSE_GAMMA | 反向伽马校正。参数被忽略。 |

### 另见
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)