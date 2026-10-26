---
title: ColorTransformOperation
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/colortransformoperation/
---
## ColorTransformOperation 类

 定义颜色变换操作。

## 常量

| 名称 | 值 | 描述 |
| --- | --- | --- |
[Tint](#Tint) | 0 | 对颜色进行色调混合。参数的范围在 0（原始颜色）到 1（白色）之间。 |
[Shade](#Shade) | 1 | 对颜色进行阴影处理。参数的范围在 0（原始颜色）到 1（黑色）之间。 |
[Complement](#Complement) | 2 | 将颜色更改为 RGB 互补色。m = Max(r, g, b); r = m - r; g = m - g; b = m - b; |
[Inverse](#Inverse) | 3 | 将颜色更改为反转颜色。r = 1 - r; g = 1 - g; b = 1 - b; |
[Grayscale](#Grayscale) | 4 | 将颜色更改为具有相同亮度的灰色。参数被忽略。 |
[SetAlpha](#SetAlpha) | 5 | 定义颜色的 alpha 组件。参数的范围在 0（透明）到 1（不透明）之间。 |
[AddAlpha](#AddAlpha) | 6 | 将参数值添加到颜色的 alpha 组件。参数的范围在 -1 到 1 之间。 |
[MultiplyAlpha](#MultiplyAlpha) | 7 | 将 alpha 组件乘以参数值。 |
[SetHue](#SetHue) | 8 | 将颜色的色相组件更改为参数值。参数的范围在 0 到 360 之间。 |
[AddHue](#AddHue) | 9 | 将参数值添加到颜色的色相组件。参数的范围在 -360 到 360 之间。 |
[MultiplyHue](#MultiplyHue) | 10 | 将色相组件乘以参数值。 |
[SetSaturation](#SetSaturation) | 11 | 将颜色的饱和度组件更改为参数值。参数的范围在 0 到 1 之间。 |
[AddSaturation](#AddSaturation) | 12 | 将参数值添加到颜色的饱和度组件。参数的范围在 -1 到 1 之间。 |
[MultiplySaturation](#MultiplySaturation) | 13 | 将饱和度组件乘以参数值。 |
[SetLuminance](#SetLuminance) | 14 | 将颜色的亮度组件更改为参数值。参数的范围在 0 到 1 之间。 |
[AddLuminance](#AddLuminance) | 15 | 将参数值添加到颜色的亮度组件。参数的范围在 -1 到 1 之间。 |
[MultiplyLuminance](#MultiplyLuminance) | 16 | 将亮度组件乘以参数值。 |
[SetRed](#SetRed) | 17 | 将颜色的红色组件更改为参数值。参数的范围在 0 到 1 之间。 |
[AddRed](#AddRed) | 18 | 将参数值添加到颜色的红色组件。参数的范围在 -1 到 1 之间。 |
[MultiplyRed](#MultiplyRed) | 19 | 将红色组件乘以参数。 |
[SetGreen](#SetGreen) | 20 | 将颜色的绿色组件更改为参数值。参数的范围在 0 到 1 之间。 |
[AddGreen](#AddGreen) | 21 | 将参数添加到颜色的绿色组件。参数的范围在 -1 到 1 之间。 |
[MultiplyGreen](#MultiplyGreen) | 22 | 将绿色组件乘以参数值。 |
[SetBlue](#SetBlue) | 23 | 将颜色的蓝色组件更改为参数值。参数的范围在 0 到 360 之间。 |
[AddBlue](#AddBlue) | 24 | 将参数值添加到颜色的蓝色组件。参数的范围在 -1 到 1 之间。 |
[MultiplyBlue](#MultiplyBlue) | 25 | 将蓝色组件乘以参数值。 |
[Gamma](#Gamma) | 26 | 伽马校正。参数被忽略。 |
[InverseGamma](#InverseGamma) | 27 | 逆伽马校正。参数被忽略。 |

---


### Tint {#Tint}
对颜色进行色调混合。参数的范围在 0（原始颜色）到 1（白色）之间。

---

### Shade {#Shade}
对颜色进行阴影处理。参数的范围在 0（原始颜色）到 1（黑色）之间。

---

### Complement {#Complement}
将颜色更改为 RGB 互补色。m = Max(r, g, b); r = m - r; g = m - g; b = m - b;

---

### Inverse {#Inverse}
将颜色更改为反转颜色。r = 1 - r; g = 1 - g; b = 1 - b;

---

### Grayscale {#Grayscale}
将颜色更改为具有相同亮度的灰色。参数被忽略。

---

### SetAlpha {#SetAlpha}
定义颜色的 alpha 组件。参数的范围在 0（透明）到 1（不透明）之间。

---

### AddAlpha {#AddAlpha}
将参数值添加到颜色的 alpha 组件。参数的范围在 -1 到 1 之间。

---

### MultiplyAlpha {#MultiplyAlpha}
将 alpha 组件乘以参数值。

---

### SetHue {#SetHue}
将颜色的色相组件更改为参数值。参数的范围在 0 到 360 之间。

---

### AddHue {#AddHue}
将参数值添加到颜色的色相组件。参数的范围在 -360 到 360 之间。

---

### MultiplyHue {#MultiplyHue}
将色相组件乘以参数值。

---

### SetSaturation {#SetSaturation}
将颜色的饱和度组件更改为参数值。参数的范围在 0 到 1 之间。

---

### AddSaturation {#AddSaturation}
将参数值添加到颜色的饱和度组件。参数的范围在 -1 到 1 之间。

---

### MultiplySaturation {#MultiplySaturation}
将饱和度组件乘以参数值。

---

### SetLuminance {#SetLuminance}
将颜色的亮度组件更改为参数值。参数的范围在 0 到 1 之间。

---

### AddLuminance {#AddLuminance}
将参数值添加到颜色的亮度组件。参数的范围在 -1 到 1 之间。

---

### MultiplyLuminance {#MultiplyLuminance}
将亮度组件乘以参数值。

---

### SetRed {#SetRed}
将颜色的红色组件更改为参数值。参数的范围在 0 到 1 之间。

---

### AddRed {#AddRed}
将参数值添加到颜色的红色组件。参数的范围在 -1 到 1 之间。

---

### MultiplyRed {#MultiplyRed}
将红色组件乘以参数。

---

### SetGreen {#SetGreen}
将颜色的绿色组件更改为参数值。参数的范围在 0 到 1 之间。

---

### AddGreen {#AddGreen}
将参数添加到颜色的绿色组件。参数的范围在 -1 到 1 之间。

---

### MultiplyGreen {#MultiplyGreen}
将绿色组件乘以参数值。

---

### SetBlue {#SetBlue}
将颜色的蓝色组件更改为参数值。参数的范围在 0 到 360 之间。

---

### AddBlue {#AddBlue}
将参数值添加到颜色的蓝色组件。参数的范围在 -1 到 1 之间。

---

### MultiplyBlue {#MultiplyBlue}
将蓝色组件乘以参数值。

---

### Gamma {#Gamma}
伽马校正。参数被忽略。

---

### InverseGamma {#InverseGamma}
逆伽马校正。参数被忽略。

---