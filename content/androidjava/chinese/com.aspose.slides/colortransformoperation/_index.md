---
title: ColorTransformOperation
second_title: Aspose.Slides for Android via Java API 参考文档
description: 定义颜色转换操作。
type: docs
url: /zh/com.aspose.slides/colortransformoperation/
---
**继承:** 
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ColorTransformOperation extends System.Enum
```

定义颜色转换操作。

## 字段

| 字段 | 描述 |
| --- | --- |
| [Tint](#Tint) | 为颜色添加色调。 |
| [Shade](#Shade) | 为颜色添加阴影。 |
| [Complement](#Complement) | 将颜色更改为 RGB 互补色。 |
| [Inverse](#Inverse) | 将颜色更改为反相颜色。 |
| [Grayscale](#Grayscale) | 将颜色更改为具有相同亮度的灰色。 |
| [SetAlpha](#SetAlpha) | 定义颜色的 alpha 分量。 |
| [AddAlpha](#AddAlpha) | 将参数值添加到颜色的 alpha 分量。 |
| [MultiplyAlpha](#MultiplyAlpha) | 将 alpha 分量乘以参数值。 |
| [SetHue](#SetHue) | 将颜色的色相分量更改为参数值。 |
| [AddHue](#AddHue) | 将参数值添加到颜色的色相分量。 |
| [MultiplyHue](#MultiplyHue) | 将色相分量乘以参数值。 |
| [SetSaturation](#SetSaturation) | 将颜色的饱和度分量更改为参数值。 |
| [AddSaturation](#AddSaturation) | 将参数值添加到颜色的饱和度分量。 |
| [MultiplySaturation](#MultiplySaturation) | 将饱和度分量乘以参数值。 |
| [SetLuminance](#SetLuminance) | 将颜色的亮度分量更改为参数值。 |
| [AddLuminance](#AddLuminance) | 将参数值添加到颜色的亮度分量。 |
| [MultiplyLuminance](#MultiplyLuminance) | 将亮度分量乘以参数值。 |
| [SetRed](#SetRed) | 将颜色的红色分量更改为参数值。 |
| [AddRed](#AddRed) | 将参数值添加到颜色的红色分量。 |
| [MultiplyRed](#MultiplyRed) | 将红色分量乘以参数。 |
| [SetGreen](#SetGreen) | 将颜色的绿色分量更改为参数值。 |
| [AddGreen](#AddGreen) | 将参数添加到颜色的绿色分量。 |
| [MultiplyGreen](#MultiplyGreen) | 将绿色分量乘以参数值。 |
| [SetBlue](#SetBlue) | 将颜色的蓝色分量更改为参数值。 |
| [AddBlue](#AddBlue) | 将参数值添加到颜色的蓝色分量。 |
| [MultiplyBlue](#MultiplyBlue) | 将蓝色分量乘以参数值。 |
| [Gamma](#Gamma) | 伽马校正。 |
| [InverseGamma](#InverseGamma) | 逆伽马校正。 |

### Tint {#Tint}
```
public static final int Tint
```

为颜色添加色调。参数范围为 0（原始颜色）至 1（白色）。

### Shade {#Shade}
```
public static final int Shade
```

为颜色添加阴影。参数范围为 0（原始颜色）至 1（黑色）。

### Complement {#Complement}
```
public static final int Complement
```

将颜色更改为 RGB 互补色。m = Max(r, g, b); r = m - r; g = m - g; b = m - b;

### Inverse {#Inverse}
```
public static final int Inverse
```

将颜色更改为反相颜色。r = 1 - r; g = 1 - g; b = 1 - b;

### Grayscale {#Grayscale}
```
public static final int Grayscale
```

将颜色更改为具有相同亮度的灰色。参数被忽略。

### SetAlpha {#SetAlpha}
```
public static final int SetAlpha
```

定义颜色的 alpha 分量。参数范围为 0（透明）至 1（不透明）。

### AddAlpha {#AddAlpha}
```
public static final int AddAlpha
```

将参数值添加到颜色的 alpha 分量。参数范围为 -1 到 1。

### MultiplyAlpha {#MultiplyAlpha}
```
public static final int MultiplyAlpha
```

将 alpha 分量乘以参数值。

### SetHue {#SetHue}
```
public static final int SetHue
```

将颜色的色相分量更改为参数值。参数范围为 0 到 360。

### AddHue {#AddHue}
```
public static final int AddHue
```

将参数值添加到颜色的色相分量。参数范围为 -360 到 360。

### MultiplyHue {#MultiplyHue}
```
public static final int MultiplyHue
```

将色相分量乘以参数值。

### SetSaturation {#SetSaturation}
```
public static final int SetSaturation
```

将颜色的饱和度分量更改为参数值。参数范围为 0 到 1。

### AddSaturation {#AddSaturation}
```
public static final int AddSaturation
```

将参数值添加到颜色的饱和度分量。参数范围为 -1 到 1。

### MultiplySaturation {#MultiplySaturation}
```
public static final int MultiplySaturation
```

将饱和度分量乘以参数值。

### SetLuminance {#SetLuminance}
```
public static final int SetLuminance
```

将颜色的亮度分量更改为参数值。参数范围为 0 到 1。

### AddLuminance {#AddLuminance}
```
public static final int AddLuminance
```

将参数值添加到颜色的亮度分量。参数范围为 -1 到 1。

### MultiplyLuminance {#MultiplyLuminance}
```
public static final int MultiplyLuminance
```

将亮度分量乘以参数值。

### SetRed {#SetRed}
```
public static final int SetRed
```

将颜色的红色分量更改为参数值。参数范围为 0 到 1。

### AddRed {#AddRed}
```
public static final int AddRed
```

将参数值添加到颜色的红色分量。参数范围为 -1 到 1。

### MultiplyRed {#MultiplyRed}
```
public static final int MultiplyRed
```

将红色分量乘以参数。

### SetGreen {#SetGreen}
```
public static final int SetGreen
```

将颜色的绿色分量更改为参数值。参数范围为 0 到 1。

### AddGreen {#AddGreen}
```
public static final int AddGreen
```

将参数添加到颜色的绿色分量。参数范围为 -1 到 1。

### MultiplyGreen {#MultiplyGreen}
```
public static final int MultiplyGreen
```

将绿色分量乘以参数值。

### SetBlue {#SetBlue}
```
public static final int SetBlue
```

将颜色的蓝色分量更改为参数值。参数范围为 0 到 360。

### AddBlue {#AddBlue}
```
public static final int AddBlue
```

将参数值添加到颜色的蓝色分量。参数范围为 -1 到 1。

### MultiplyBlue {#MultiplyBlue}
```
public static final int MultiplyBlue
```

将蓝色分量乘以参数值。

### Gamma {#Gamma}
```
public static final int Gamma
```

伽马校正。参数被忽略。

### InverseGamma {#InverseGamma}
```
public static final int InverseGamma
```

逆伽马校正。参数被忽略。