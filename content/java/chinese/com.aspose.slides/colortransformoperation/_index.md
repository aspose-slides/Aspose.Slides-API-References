---
title: ColorTransformOperation
second_title: Aspose.Slides for Java API 参考
description: 定义颜色变换操作。
type: docs
url: /zh/com.aspose.slides/colortransformoperation/
---
**继承：**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ColorTransformOperation extends System.Enum
```

定义颜色变换操作。
## 字段

| 字段 | 描述 |
| --- | --- |
| [Tint](#Tint) | 为颜色添加色调。 |
| [Shade](#Shade) | 为颜色添加阴影。 |
| [Complement](#Complement) | 将颜色更改为 RGB 互补色。 |
| [Inverse](#Inverse) | 将颜色更改为反相颜色。 |
| [Grayscale](#Grayscale) | 将颜色更改为相同亮度的灰色。 |
| [SetAlpha](#SetAlpha) | 定义颜色的 alpha 组件。 |
| [AddAlpha](#AddAlpha) | 将参数值添加到颜色的 alpha 组件。 |
| [MultiplyAlpha](#MultiplyAlpha) | 将 alpha 组件乘以参数值。 |
| [SetHue](#SetHue) | 将颜色的 hue 组件更改为参数值。 |
| [AddHue](#AddHue) | 将参数值添加到颜色的 hue 组件。 |
| [MultiplyHue](#MultiplyHue) | 将 hue 组件乘以参数值。 |
| [SetSaturation](#SetSaturation) | 将颜色的 saturation 组件更改为参数值。 |
| [AddSaturation](#AddSaturation) | 将参数值添加到颜色的 saturation 组件。 |
| [MultiplySaturation](#MultiplySaturation) | 将 saturation 组件乘以参数值。 |
| [SetLuminance](#SetLuminance) | 将颜色的 luminance 组件更改为参数值。 |
| [AddLuminance](#AddLuminance) | 将参数值添加到颜色的 luminance 组件。 |
| [MultiplyLuminance](#MultiplyLuminance) | 将 luminance 组件乘以参数值。 |
| [SetRed](#SetRed) | 将颜色的 red 组件更改为参数值。 |
| [AddRed](#AddRed) | 将参数值添加到 red 组件。 |
| [MultiplyRed](#MultiplyRed) | 将 red 组件乘以参数。 |
| [SetGreen](#SetGreen) | 将颜色的 green 组件更改为参数值。 |
| [AddGreen](#AddGreen) | 将参数添加到 green 组件。 |
| [MultiplyGreen](#MultiplyGreen) | 将 green 组件乘以参数值。 |
| [SetBlue](#SetBlue) | 将颜色的 blue 组件更改为参数值。 |
| [AddBlue](#AddBlue) | 将参数值添加到 blue 组件。 |
| [MultiplyBlue](#MultiplyBlue) | 将 blue 组件乘以参数值。 |
| [Gamma](#Gamma) | Gamma 校正。 |
| [InverseGamma](#InverseGamma) | 逆 Gamma 校正。 |
### 色调 {#Tint}
```
public static final int Tint
```

为颜色添加色调。参数范围为 0（原始颜色）到 1（白色）。

### 阴影 {#Shade}
```
public static final int Shade
```

为颜色添加阴影。参数范围为 0（原始颜色）到 1（黑色）。

### 互补色 {#Complement}
```
public static final int Complement
```

将颜色更改为 RGB 互补色。m = Max(r, g, b); r = m - r; g = m - g; b = m - b;

### 反相 {#Inverse}
```
public static final int Inverse
```

将颜色更改为反相颜色。r = 1 - r; g = 1 - g; b = 1 - b;

### 灰度 {#Grayscale}
```
public static final int Grayscale
```

将颜色更改为相同亮度的灰色。参数被忽略。

### 设置 Alpha {#SetAlpha}
```
public static final int SetAlpha
```

定义颜色的 alpha 组件。参数范围为 0（透明）到 1（不透明）。

### 添加 Alpha {#AddAlpha}
```
public static final int AddAlpha
```

将参数值添加到颜色的 alpha 组件。参数范围为 -1 到 1。

### 乘以 Alpha {#MultiplyAlpha}
```
public static final int MultiplyAlpha
```

将 alpha 组件乘以参数值。

### 设置 Hue {#SetHue}
```
public static final int SetHue
```

将颜色的 hue 组件更改为参数值。参数范围为 0 到 360。

### 添加 Hue {#AddHue}
```
public static final int AddHue
```

将参数值添加到颜色的 hue 组件。参数范围为 -360 到 360。

### 乘以 Hue {#MultiplyHue}
```
public static final int MultiplyHue
```

将 hue 组件乘以参数值。

### 设置 Saturation {#SetSaturation}
```
public static final int SetSaturation
```

将颜色的 saturation 组件更改为参数值。参数范围为 0 到 1。

### 添加 Saturation {#AddSaturation}
```
public static final int AddSaturation
```

将参数值添加到颜色的 saturation 组件。参数范围为 -1 到 1。

### 乘以 Saturation {#MultiplySaturation}
```
public static final int MultiplySaturation
```

将 saturation 组件乘以参数值。

### 设置 Luminance {#SetLuminance}
```
public static final int SetLuminance
```

将颜色的 luminance 组件更改为参数值。参数范围为 0 到 1。

### 添加 Luminance {#AddLuminance}
```
public static final int AddLuminance
```

将参数值添加到颜色的 luminance 组件。参数范围为 -1 到 1。

### 乘以 Luminance {#MultiplyLuminance}
```
public static final int MultiplyLuminance
```

将 luminance 组件乘以参数值。

### 设置 Red {#SetRed}
```
public static final int SetRed
```

将颜色的 red 组件更改为参数值。参数范围为 0 到 1。

### 添加 Red {#AddRed}
```
public static final int AddRed
```

将参数值添加到颜色的 red 组件。参数范围为 -1 到 1。

### 乘以 Red {#MultiplyRed}
```
public static final int MultiplyRed
```

将 red 组件乘以参数。

### 设置 Green {#SetGreen}
```
public static final int SetGreen
```

将颜色的 green 组件更改为参数值。参数范围为 0 到 1。

### 添加 Green {#AddGreen}
```
public static final int AddGreen
```

将参数添加到颜色的 green 组件。参数范围为 -1 到 1。

### 乘以 Green {#MultiplyGreen}
```
public static final int MultiplyGreen
```

将 green 组件乘以参数值。

### 设置 Blue {#SetBlue}
```
public static final int SetBlue
```

将颜色的 blue 组件更改为参数值。参数范围为 0 到 360。

### 添加 Blue {#AddBlue}
```
public static final int AddBlue
```

将参数值添加到颜色的 blue 组件。参数范围为 -1 到 1。

### 乘以 Blue {#MultiplyBlue}
```
public static final int MultiplyBlue
```

将 blue 组件乘以参数值。

### Gamma {#Gamma}
```
public static final int Gamma
```

Gamma 校正。参数被忽略。

### InverseGamma {#InverseGamma}
```
public static final int InverseGamma
```

逆 Gamma 校正。参数被忽略。