---
title: ColorTransformOperation
second_title: Aspose.Slides C++ API 参考
description: 定义颜色变换操作。
type: docs
weight: 5747
url: /zh/aspose.slides/colortransformoperation/
---
## ColorTransformOperation 枚举

Defines color transform operation.

```cpp
enum class ColorTransformOperation
```

### 值

| 名称 | 数值 | 描述 |
| --- | --- | --- |
| Tint | 0 | 为颜色添加色调。参数的取值范围为 0（原始颜色）到 1（白色）。 |
| Shade | 1 | 为颜色添加阴影。参数的取值范围为 0（原始颜色）到 1（黑色）。 |
| Complement | 2 | 将颜色更改为 RGB 互补色。m = Max(r, g, b); r = m - r; g = m - g; b = m - b; |
| Inverse | 3 | 将颜色更改为反向颜色。r = 1 - r; g = 1 - g; b = 1 - b; |
| Grayscale | 4 | 将颜色更改为具有相同亮度的灰色。参数被忽略。 |
| SetAlpha | 5 | 定义颜色的 alpha 分量。参数的取值范围为 0（透明）到 1（不透明）。 |
| AddAlpha | 6 | 将参数的值添加到颜色的 alpha 分量。参数的取值范围为 -1 到 1。 |
| MultiplyAlpha | 7 | 将 alpha 分量乘以参数的值。 |
| SetHue | 8 | 将颜色的色相分量更改为参数的值。参数的取值范围为 0 到 360。 |
| AddHue | 9 | 将参数的值添加到颜色的色相分量。参数的取值范围为 -360 到 360。 |
| MultiplyHue | 10 | 将色相分量乘以参数的值。 |
| SetSaturation | 11 | 将颜色的饱和度分量更改为参数的值。参数的取值范围为 0 到 1。 |
| AddSaturation | 12 | 将参数的值添加到颜色的饱和度分量。参数的取值范围为 -1 到 1。 |
| MultiplySaturation | 13 | 将饱和度分量乘以参数的值。 |
| SetLuminance | 14 | 将颜色的亮度分量更改为参数的值。参数的取值范围为 0 到 1。 |
| AddLuminance | 15 | 将参数的值添加到颜色的亮度分量。参数的取值范围为 -1 到 1。 |
| MultiplyLuminance | 16 | 将亮度分量乘以参数的值。 |
| SetRed | 17 | 将颜色的红色分量更改为参数的值。参数的取值范围为 0 到 1。 |
| AddRed | 18 | 将参数的值添加到颜色的红色分量。参数的取值范围为 -1 到 1。 |
| MultiplyRed | 19 | 将红色分量乘以参数。 |
| SetGreen | 20 | 将颜色的绿色分量更改为参数的值。参数的取值范围为 0 到 1。 |
| AddGreen | 21 | 将参数添加到颜色的绿色分量。参数的取值范围为 -1 到 1。 |
| MultiplyGreen | 22 | 将绿色分量乘以参数的值。 |
| SetBlue | 23 | 将颜色的蓝色分量更改为参数的值。参数的取值范围为 0 到 360。 |
| AddBlue | 24 | 将参数的值添加到颜色的蓝色分量。参数的取值范围为 -1 到 1。 |
| MultiplyBlue | 25 | 将蓝色分量乘以参数的值。 |
| Gamma | 26 | 伽马校正。参数被忽略。 |
| InverseGamma | 27 | 逆伽马校正。参数被忽略。 |

## 另见

* 命名空间 [Aspose::Slides](../)
* 库 [Aspose.Slides](../../)