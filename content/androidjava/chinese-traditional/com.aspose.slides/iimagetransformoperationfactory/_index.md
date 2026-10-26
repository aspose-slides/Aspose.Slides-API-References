---
title: IImageTransformOperationFactory
second_title: Aspose.Slides for Android via Java API Reference
description: 允許建立影像效果實例
type: docs
url: /zh-hant/com.aspose.slides/iimagetransformoperationfactory/
---```
public interface IImageTransformOperationFactory
```

允許建立影像效果實例

--------------------

用於 COM 介面。
## 方法

| 方法 | 說明 |
| --- | --- |
| [createAlphaBiLevel(float threshold)](#createAlphaBiLevel-float-) | 建立 Alpha BiLevel 效果。 |
| [createAlphCeiling()](#createAlphCeiling--) | 建立 Alpha Ceiling 效果。 |
| [createAlphaFloor()](#createAlphaFloor--) | 建立 Alpha floor 效果。 |
| [createAlphaInverse()](#createAlphaInverse--) | 建立 Alpha inverse 效果。 |
| [createAlphaModulate()](#createAlphaModulate--) | 建立 Alpha modulate 效果。 |
| [createAlphaModulateFixed(float amount)](#createAlphaModulateFixed-float-) | 建立 Alpha modulate fixed 效果。 |
| [createAlphaReplace(float alpha)](#createAlphaReplace-float-) | 建立 Alpha replace 效果。 |
| [createBiLevel(float threshold)](#createBiLevel-float-) | 建立 BiLevel 效果。 |
| [createBlur(double radius, boolean grow)](#createBlur-double-boolean-) | 建立 Blur 效果。 |
| [createColorChange()](#createColorChange--) | 建立 Color change 效果。 |
| [createColorReplace()](#createColorReplace--) | 建立 Color replace 效果。 |
| [createDuotone()](#createDuotone--) | 建立 Duotone 效果。 |
| [createFillOverlay()](#createFillOverlay--) | 建立 Fill overlay 效果。 |
| [createGrayScale()](#createGrayScale--) | 建立 Gray scale 效果。 |
| [createHSL(float hue, float saturation, float luminance)](#createHSL-float-float-float-) | 建立 Hue Saturation Luminance 效果。 |
| [createLuminance(float brightness, float contrast)](#createLuminance-float-float-) | 建立 Luminance 效果。 |
| [createTint(float hue, float amount)](#createTint-float-float-) | 建立 Tint 效果。 |
### createAlphaBiLevel(float threshold) {#createAlphaBiLevel-float-}
```
public abstract IAlphaBiLevel createAlphaBiLevel(float threshold)
```

建立 Alpha BiLevel 效果。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| threshold | float | 閾值。 |

**返回：**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Alpha BiLevel 效果。
### createAlphCeiling() {#createAlphCeiling--}
```
public abstract IAlphaCeiling createAlphCeiling()
```

建立 Alpha Ceiling 效果。

**返回：**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Alpha Ceiling 效果。
### createAlphaFloor() {#createAlphaFloor--}
```
public abstract IAlphaFloor createAlphaFloor()
```

建立 Alpha floor 效果。

**返回：**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Alpha floor 效果。
### createAlphaInverse() {#createAlphaInverse--}
```
public abstract IAlphaInverse createAlphaInverse()
```

建立 Alpha inverse 效果。

**返回：**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Alpha inverst effect。
### createAlphaModulate() {#createAlphaModulate--}
```
public abstract IAlphaModulate createAlphaModulate()
```

建立 Alpha modulate 效果。

**返回：**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Alpha modulate 效果。
### createAlphaModulateFixed(float amount) {#createAlphaModulateFixed-float-}
```
public abstract IAlphaModulateFixed createAlphaModulateFixed(float amount)
```

建立 Alpha modulate fixed 效果。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| amount | float | 數量。 |

**返回：**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Alpha modulate fixed 效果。
### createAlphaReplace(float alpha) {#createAlphaReplace-float-}
```
public abstract IAlphaReplace createAlphaReplace(float alpha)
```

建立 Alpha replace 效果。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| alpha | float | Alpha |

**返回：**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Alpha replace 效果。
### createBiLevel(float threshold) {#createBiLevel-float-}
```
public abstract IBiLevel createBiLevel(float threshold)
```

建立 BiLevel 效果。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| threshold | float | 閾值。 |

**返回：**
[IBiLevel](../../com.aspose.slides/ibilevel) - BiLevel 效果。
### createBlur(double radius, boolean grow) {#createBlur-double-boolean-}
```
public abstract IBlur createBlur(double radius, boolean grow)
```

建立 Blur 效果。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| radius | double | 半徑。 |
| grow | boolean | 增長。 |

**返回：**
[IBlur](../../com.aspose.slides/iblur) - Blur 效果。
### createColorChange() {#createColorChange--}
```
public abstract IColorChange createColorChange()
```

建立 Color change 效果。

**返回：**
[IColorChange](../../com.aspose.slides/icolorchange) - Color change 效果。
### createColorReplace() {#createColorReplace--}
```
public abstract IColorReplace createColorReplace()
```

建立 Color replace 效果。

**返回：**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Color replace 效果。
### createDuotone() {#createDuotone--}
```
public abstract IDuotone createDuotone()
```

建立 Duotone 效果。

**返回：**
[IDuotone](../../com.aspose.slides/iduotone) - Duotone 效果。
### createFillOverlay() {#createFillOverlay--}
```
public abstract IFillOverlay createFillOverlay()
```

建立 Fill overlay 效果。

**返回：**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Fill overlay 效果。
### createGrayScale() {#createGrayScale--}
```
public abstract IGrayScale createGrayScale()
```

建立 Gray scale 效果。

**返回：**
[IGrayScale](../../com.aspose.slides/igrayscale) - Returns gray scale effect。
### createHSL(float hue, float saturation, float luminance) {#createHSL-float-float-float-}
```
public abstract IHSL createHSL(float hue, float saturation, float luminance)
```

建立 Hue Saturation Luminance 效果。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| hue | float | Hue。 |
| saturation | float | Saturation。 |
| luminance | float | Luminance。 |

**返回：**
[IHSL](../../com.aspose.slides/ihsl) - HSL 效果。
### createLuminance(float brightness, float contrast) {#createLuminance-float-float-}
```
public abstract ILuminance createLuminance(float brightness, float contrast)
```

建立 Luminance 效果。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| brightness | float | 亮度。 |
| contrast | float | 對比度。 |

**返回：**
[ILuminance](../../com.aspose.slides/iluminance) - Luminance 效果。
### createTint(float hue, float amount) {#createTint-float-float-}
```
public abstract ITint createTint(float hue, float amount)
```

建立 Tint 效果。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| hue | float | Hue。 |
| amount | float | 數量。 |

**返回：**
[ITint](../../com.aspose.slides/itint) - Tint 效果。