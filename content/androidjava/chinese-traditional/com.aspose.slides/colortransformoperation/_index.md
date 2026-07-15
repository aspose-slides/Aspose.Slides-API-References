---
title: ColorTransformOperation
second_title: Aspose.Slides for Android via Java API 參考
description: 定義顏色變換操作。
type: docs
url: /zh-hant/com.aspose.slides/colortransformoperation/
---
**繼承:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ColorTransformOperation extends System.Enum
```

定義顏色變換操作。
## 欄位

| Field | 說明 |
| --- | --- |
| [Tint](#Tint) | 為顏色添加淡化效果。 |
| [Shade](#Shade) | 為顏色添加暗化效果。 |
| [Complement](#Complement) | 將顏色更改為 RGB 補色。 |
| [Inverse](#Inverse) | 將顏色更改為反相顏色。 |
| [Grayscale](#Grayscale) | 將顏色更改為相同亮度的灰階。 |
| [SetAlpha](#SetAlpha) | 定義顏色的 Alpha 成分。 |
| [AddAlpha](#AddAlpha) | 將參數值添加到顏色的 Alpha 成分。 |
| [MultiplyAlpha](#MultiplyAlpha) | 將 Alpha 成分乘以參數值。 |
| [SetHue](#SetHue) | 將顏色的 Hue 成分更改為參數值。 |
| [AddHue](#AddHue) | 將參數值添加到顏色的 Hue 成分。 |
| [MultiplyHue](#MultiplyHue) | 將 Hue 成分乘以參數值。 |
| [SetSaturation](#SetSaturation) | 將顏色的 Saturation 成分更改為參數值。 |
| [AddSaturation](#AddSaturation) | 將參數值添加到 Saturation 成分。 |
| [MultiplySaturation](#MultiplySaturation) | 將 Saturation 成分乘以參數值。 |
| [SetLuminance](#SetLuminance) | 將顏色的 Luminance 成分更改為參數值。 |
| [AddLuminance](#AddLuminance) | 將參數值添加到 Luminance 成分。 |
| [MultiplyLuminance](#MultiplyLuminance) | 將 Luminance 成分乘以參數值。 |
| [SetRed](#SetRed) | 將顏色的 Red 成分更改為參數值。 |
| [AddRed](#AddRed) | 將參數值添加到 Red 成分。 |
| [MultiplyRed](#MultiplyRed) | 將 Red 成分乘以參數。 |
| [SetGreen](#SetGreen) | 將顏色的 Green 成分更改為參數值。 |
| [AddGreen](#AddGreen) | 將參數添加到 Green 成分。 |
| [MultiplyGreen](#MultiplyGreen) | 將 Green 成分乘以參數值。 |
| [SetBlue](#SetBlue) | 將顏色的 Blue 成分更改為參數值。 |
| [AddBlue](#AddBlue) | 將參數值添加到 Blue 成分。 |
| [MultiplyBlue](#MultiplyBlue) | 將 Blue 成分乘以參數值。 |
| [Gamma](#Gamma) | Gamma 校正。 |
| [InverseGamma](#InverseGamma) | 反向 Gamma 校正。 |
### Tint {#Tint}
```
public static final int Tint
```


為顏色添加淡化效果。參數的取值範圍為 0（原始顏色）至 1（白色）。

### Shade {#Shade}
```
public static final int Shade
```


為顏色添加暗化效果。參數的取值範圍為 0（原始顏色）至 1（黑色）。

### Complement {#Complement}
```
public static final int Complement
```


將顏色更改為 RGB 補色。m = Max(r, g, b); r = m - r; g = m - g; b = m - b;

### Inverse {#Inverse}
```
public static final int Inverse
```


將顏色更改為反相顏色。r = 1 - r; g = 1 - g; b = 1 - b;

### Grayscale {#Grayscale}
```
public static final int Grayscale
```


將顏色更改為相同亮度的灰階。參數被忽略。

### SetAlpha {#SetAlpha}
```
public static final int SetAlpha
```


定義顏色的 Alpha 成分。參數的取值範圍為 0（透明）至 1（不透明）。

### AddAlpha {#AddAlpha}
```
public static final int AddAlpha
```


將參數值添加到顏色的 Alpha 成分。參數的取值範圍為 -1 至 1。

### MultiplyAlpha {#MultiplyAlpha}
```
public static final int MultiplyAlpha
```


將 Alpha 成分乘以參數值。

### SetHue {#SetHue}
```
public static final int SetHue
```


將顏色的 Hue 成分更改為參數值。參數的取值範圍為 0 至 360。

### AddHue {#AddHue}
```
public static final int AddHue
```


將參數值添加到 Hue 成分。參數的取值範圍為 -360 至 360。

### MultiplyHue {#MultiplyHue}
```
public static final int MultiplyHue
```


將 Hue 成分乘以參數值。

### SetSaturation {#SetSaturation}
```
public static final int SetSaturation
```


將顏色的 Saturation 成分更改為參數值。參數的取值範圍為 0 至 1。

### AddSaturation {#AddSaturation}
```
public static final int AddSaturation
```


將參數值添加到 Saturation 成分。參數的取值範圍為 -1 至 1。

### MultiplySaturation {#MultiplySaturation}
```
public static final int MultiplySaturation
```


將 Saturation 成分乘以參數值。

### SetLuminance {#SetLuminance}
```
public static final int SetLuminance
```


將顏色的 Luminance 成分更改為參數值。參數的取值範圍為 0 至 1。

### AddLuminance {#AddLuminance}
```
public static final int AddLuminance
```


將參數值添加到 Luminance 成分。參數的取值範圍為 -1 至 1。

### MultiplyLuminance {#MultiplyLuminance}
```
public static final int MultiplyLuminance
```


將 Luminance 成分乘以參數值。

### SetRed {#SetRed}
```
public static final int SetRed
```


將顏色的 Red 成分更改為參數值。參數的取值範圍為 0 至 1。

### AddRed {#AddRed}
```
public static final int AddRed
```


將參數值添加到 Red 成分。參數的取值範圍為 -1 至 1。

### MultiplyRed {#MultiplyRed}
```
public static final int MultiplyRed
```


將 Red 成分乘以參數。

### SetGreen {#SetGreen}
```
public static final int SetGreen
```


將顏色的 Green 成分更改為參數值。參數的取值範圍為 0 至 1。

### AddGreen {#AddGreen}
```
public static final int AddGreen
```


將參數添加到 Green 成分。參數的取值範圍為 -1 至 1。

### MultiplyGreen {#MultiplyGreen}
```
public static final int MultiplyGreen
```


將 Green 成分乘以參數值。

### SetBlue {#SetBlue}
```
public static final int SetBlue
```


將顏色的 Blue 成分更改為參數值。參數的取值範圍為 0 至 360。

### AddBlue {#AddBlue}
```
public static final int AddBlue
```


將參數值添加到 Blue 成分。參數的取值範圍為 -1 至 1。

### MultiplyBlue {#MultiplyBlue}
```
public static final int MultiplyBlue
```


將 Blue 成分乘以參數值。

### Gamma {#Gamma}
```
public static final int Gamma
```


Gamma 校正。參數被忽略。

### InverseGamma {#InverseGamma}
```
public static final int InverseGamma
```


反向 Gamma 校正。參數被忽略。