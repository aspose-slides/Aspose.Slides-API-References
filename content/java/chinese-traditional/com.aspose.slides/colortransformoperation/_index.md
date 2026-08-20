---
title: ColorTransformOperation
second_title: Aspose.Slides for Java API 參考
description: 定義顏色轉換操作。
type: docs
url: /zh-hant/com.aspose.slides/colortransformoperation/
---
**繼承:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ColorTransformOperation extends System.Enum
```

定義顏色轉換操作。
## 欄位

| Field | Description |
| --- | --- |
| [Tint](#Tint) | 為顏色調整色調。 |
| [Shade](#Shade) | 將顏色變暗。 |
| [Complement](#Complement) | 將顏色變為 RGB 互補色。 |
| [Inverse](#Inverse) | 將顏色變為反相顏色。 |
| [Grayscale](#Grayscale) | 將顏色變為相同亮度的灰色。 |
| [SetAlpha](#SetAlpha) | 定義顏色的 Alpha 成分。 |
| [AddAlpha](#AddAlpha) | 將參數值添加到顏色的 Alpha 成分。 |
| [MultiplyAlpha](#MultiplyAlpha) | 將 Alpha 成分乘以參數值。 |
| [SetHue](#SetHue) | 將色相成分更改為參數值。 |
| [AddHue](#AddHue) | 將參數值添加到色相成分。 |
| [MultiplyHue](#MultiplyHue) | 將色相成分乘以參數值。 |
| [SetSaturation](#SetSaturation) | 將飽和度成分更改為參數值。 |
| [AddSaturation](#AddSaturation) | 將參數值添加到飽和度成分。 |
| [MultiplySaturation](#MultiplySaturation) | 將飽和度成分乘以參數值。 |
| [SetLuminance](#SetLuminance) | 將亮度成分更改為參數值。 |
| [AddLuminance](#AddLuminance) | 將參數值添加到亮度成分。 |
| [MultiplyLuminance](#MultiplyLuminance) | 將亮度成分乘以參數值。 |
| [SetRed](#SetRed) | 將紅色成分更改為參數值。 |
| [AddRed](#AddRed) | 將參數值添加到紅色成分。 |
| [MultiplyRed](#MultiplyRed) | 將紅色成分乘以參數。 |
| [SetGreen](#SetGreen) | 將綠色成分更改為參數值。 |
| [AddGreen](#AddGreen) | 將參數添加到綠色成分。 |
| [MultiplyGreen](#MultiplyGreen) | 將綠色成分乘以參數值。 |
| [SetBlue](#SetBlue) | 將藍色成分更改為參數值。 |
| [AddBlue](#AddBlue) | 將參數值添加到藍色成分。 |
| [MultiplyBlue](#MultiplyBlue) | 將藍色成分乘以參數值。 |
| [Gamma](#Gamma) | Gamma 校正。 |
| [InverseGamma](#InverseGamma) | 反向 Gamma 校正。 |
### Tint {#Tint}
```
public static final int Tint
```

調整顏色的色調。參數範圍在 0（原始顏色）至 1（白色）之間。

### Shade {#Shade}
```
public static final int Shade
```

將顏色變暗。參數範圍在 0（原始顏色）至 1（黑色）之間。

### Complement {#Complement}
```
public static final int Complement
```

將顏色變為 RGB 互補色。m = Max(r, g, b); r = m - r; g = m - g; b = m - b;

### Inverse {#Inverse}
```
public static final int Inverse
```

將顏色變為反相顏色。r = 1 - r; g = 1 - g; b = 1 - b;

### Grayscale {#Grayscale}
```
public static final int Grayscale
```

將顏色變為相同亮度的灰色。參數將被忽略。

### SetAlpha {#SetAlpha}
```
public static final int SetAlpha
```

定義顏色的 Alpha 成分。參數範圍在 0（透明）至 1（不透明）之間。

### AddAlpha {#AddAlpha}
```
public static final int AddAlpha
```

將參數值添加到顏色的 Alpha 成分。參數範圍在 -1 至 1 之間。

### MultiplyAlpha {#MultiplyAlpha}
```
public static final int MultiplyAlpha
```

將 Alpha 成分乘以參數值。

### SetHue {#SetHue}
```
public static final int SetHue
```

將色相成分更改為參數值。參數範圍在 0 至 360 之間。

### AddHue {#AddHue}
```
public static final int AddHue
```

將參數值添加到色相成分。參數範圍在 -360 至 360 之間。

### MultiplyHue {#MultiplyHue}
```
public static final int MultiplyHue
```

將色相成分乘以參數值。

### SetSaturation {#SetSaturation}
```
public static final int SetSaturation
```

將飽和度成分更改為參數值。參數範圍在 0 至 1 之間。

### AddSaturation {#AddSaturation}
```
public static final int AddSaturation
```

將參數值添加到飽和度成分。參數範圍在 -1 至 1 之間。

### MultiplySaturation {#MultiplySaturation}
```
public static final int MultiplySaturation
```

將飽和度成分乘以參數值。

### SetLuminance {#SetLuminance}
```
public static final int SetLuminance
```

將亮度成分更改為參數值。參數範圍在 0 至 1 之間。

### AddLuminance {#AddLuminance}
```
public static final int AddLuminance
```

將參數值添加到亮度成分。參數範圍在 -1 至 1 之間。

### MultiplyLuminance {#MultiplyLuminance}
```
public static final int MultiplyLuminance
```

將亮度成分乘以參數值。

### SetRed {#SetRed}
```
public static final int SetRed
```

將紅色成分更改為參數值。參數範圍在 0 至 1 之間。

### AddRed {#AddRed}
```
public static final int AddRed
```

將參數值添加到紅色成分。參數範圍在 -1 至 1 之間。

### MultiplyRed {#MultiplyRed}
```
public static final int MultiplyRed
```

將紅色成分乘以參數。

### SetGreen {#SetGreen}
```
public static final int SetGreen
```

將綠色成分更改為參數值。參數範圍在 0 至 1 之間。

### AddGreen {#AddGreen}
```
public static final int AddGreen
```

將參數添加到綠色成分。參數範圍在 -1 至 1 之間。

### MultiplyGreen {#MultiplyGreen}
```
public static final int MultiplyGreen
```

將綠色成分乘以參數值。

### SetBlue {#SetBlue}
```
public static final int SetBlue
```

將藍色成分更改為參數值。參數範圍在 0 至 360 之間。

### AddBlue {#AddBlue}
```
public static final int AddBlue
```

將參數值添加到藍色成分。參數範圍在 -1 至 1 之間。

### MultiplyBlue {#MultiplyBlue}
```
public static final int MultiplyBlue
```

將藍色成分乘以參數值。

### Gamma {#Gamma}
```
public static final int Gamma
```

Gamma 校正。參數將被忽略。

### InverseGamma {#InverseGamma}
```
public static final int InverseGamma
```

反向 Gamma 校正。參數將被忽略。