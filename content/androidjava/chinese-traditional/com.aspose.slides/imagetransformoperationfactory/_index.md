---
title: ImageTransformOperationFactory
second_title: Aspose.Slides for Android 的 Java API 參考
description: 允許建立影像變換操作
type: docs
url: /zh-hant/com.aspose.slides/imagetransformoperationfactory/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IImageTransformOperationFactory](../../com.aspose.slides/iimagetransformoperationfactory)
```
public class ImageTransformOperationFactory implements IImageTransformOperationFactory
```

允許建立影像變換操作

--------------------

供 COM 相容性使用。

## 建構式

| 建構式 | 說明 |
| --- | --- |
| [ImageTransformOperationFactory()](#ImageTransformOperationFactory--) |  |
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
### ImageTransformOperationFactory() {#ImageTransformOperationFactory--}
```
public ImageTransformOperationFactory()
```


### createAlphaBiLevel(float threshold) {#createAlphaBiLevel-float-}
```
public final IAlphaBiLevel createAlphaBiLevel(float threshold)
```


建立 Alpha BiLevel 效果。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| threshold | float | 閾值。 |

**Returns:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Alpha BiLevel 效果。
### createAlphCeiling() {#createAlphCeiling--}
```
public final IAlphaCeiling createAlphCeiling()
```


建立 Alpha Ceiling 效果。

**Returns:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Alpha Ceiling 效果。
### createAlphaFloor() {#createAlphaFloor--}
```
public final IAlphaFloor createAlphaFloor()
```


建立 Alpha floor 效果。

**Returns:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Alpha floor 效果。
### createAlphaInverse() {#createAlphaInverse--}
```
public final IAlphaInverse createAlphaInverse()
```


建立 Alpha inverse 效果。

**Returns:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Alpha inverst 效果。
### createAlphaModulate() {#createAlphaModulate--}
```
public final IAlphaModulate createAlphaModulate()
```


建立 Alpha modulate 效果。

**Returns:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Alpha modulate 效果。
### createAlphaModulateFixed(float amount) {#createAlphaModulateFixed-float-}
```
public final IAlphaModulateFixed createAlphaModulateFixed(float amount)
```


建立 Alpha modulate fixed 效果。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| amount | float | 數量。 |

**Returns:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Alpha modulate fixed 效果。
### createAlphaReplace(float alpha) {#createAlphaReplace-float-}
```
public final IAlphaReplace createAlphaReplace(float alpha)
```


建立 Alpha replace 效果。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| alpha | float | Alpha |

**Returns:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Alpha replace 效果。
### createBiLevel(float threshold) {#createBiLevel-float-}
```
public final IBiLevel createBiLevel(float threshold)
```


建立 BiLevel 效果。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| threshold | float | 閾值。 |

**Returns:**
[IBiLevel](../../com.aspose.slides/ibilevel) - BiLevel 效果。
### createBlur(double radius, boolean grow) {#createBlur-double-boolean-}
```
public final IBlur createBlur(double radius, boolean grow)
```


建立 Blur 效果。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| radius | double | 半徑。 |
| grow | boolean | 增長。 |

**Returns:**
[IBlur](../../com.aspose.slides/iblur) - Blur 效果。
### createColorChange() {#createColorChange--}
```
public final IColorChange createColorChange()
```


建立 Color change 效果。

**Returns:**
[IColorChange](../../com.aspose.slides/icolorchange) - Color change 效果。
### createColorReplace() {#createColorReplace--}
```
public final IColorReplace createColorReplace()
```


建立 Color replace 效果。

**Returns:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Color replace 效果。
### createDuotone() {#createDuotone--}
```
public final IDuotone createDuotone()
```


建立 Duotone 效果。

**Returns:**
[IDuotone](../../com.aspose.slides/iduotone) - Duotone 效果。
### createFillOverlay() {#createFillOverlay--}
```
public final IFillOverlay createFillOverlay()
```


建立 Fill overlay 效果。

**Returns:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Fill overlay 效果。
### createGrayScale() {#createGrayScale--}
```
public final IGrayScale createGrayScale()
```


建立 Gray scale 效果。

**Returns:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Returns gray scale 效果。
### createHSL(float hue, float saturation, float luminance) {#createHSL-float-float-float-}
```
public final IHSL createHSL(float hue, float saturation, float luminance)
```


建立 Hue Saturation Luminance 效果。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| hue | float | 色相。 |
| saturation | float | 飽和度。 |
| luminance | float | 亮度。 |

**Returns:**
[IHSL](../../com.aspose.slides/ihsl) - HSL 效果。
### createLuminance(float brightness, float contrast) {#createLuminance-float-float-}
```
public final ILuminance createLuminance(float brightness, float contrast)
```


建立 Luminance 效果。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brightness | float | 亮度。 |
| contrast | float | 對比度。 |

**Returns:**
[ILuminance](../../com.aspose.slides/iluminance) - Luminance 效果。
### createTint(float hue, float amount) {#createTint-float-float-}
```
public final ITint createTint(float hue, float amount)
```


建立 Tint 效果。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| hue | float | 色相。 |
| amount | float | 數量。 |

**Returns:**
[ITint](../../com.aspose.slides/itint) - Tint 效果。