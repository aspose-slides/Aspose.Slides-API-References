---
title: IImageTransformOperationFactory
second_title: Aspose.Slides for Java API Reference
description: 允许创建图像效果实例
type: docs
url: /zh/com.aspose.slides/iimagetransformoperationfactory/
---```
public interface IImageTransformOperationFactory
```

允许创建图像效果实例

--------------------

针对 COM 接口。

## 方法

| Method | Description |
| --- | --- |
| [createAlphaBiLevel(float threshold)](#createAlphaBiLevel-float-) | 创建 Alpha BiLevel 效果。 |
| [createAlphCeiling()](#createAlphCeiling--) | 创建 Alpha Ceiling 效果。 |
| [createAlphaFloor()](#createAlphaFloor--) | 创建 Alpha floor 效果。 |
| [createAlphaInverse()](#createAlphaInverse--) | 创建 Alpha inverse 效果。 |
| [createAlphaModulate()](#createAlphaModulate--) | 创建 Alpha modulate 效果。 |
| [createAlphaModulateFixed(float amount)](#createAlphaModulateFixed-float-) | 创建 Alpha modulate fixed 效果。 |
| [createAlphaReplace(float alpha)](#createAlphaReplace-float-) | 创建 Alpha replace 效果。 |
| [createBiLevel(float threshold)](#createBiLevel-float-) | 创建 BiLevel 效果。 |
| [createBlur(double radius, boolean grow)](#createBlur-double-boolean-) | 创建 Blur 效果。 |
| [createColorChange()](#createColorChange--) | 创建 Color change 效果。 |
| [createColorReplace()](#createColorReplace--) | 创建 Color replace 效果。 |
| [createDuotone()](#createDuotone--) | 创建 Duotone 效果。 |
| [createFillOverlay()](#createFillOverlay--) | 创建 Fill overlay 效果。 |
| [createGrayScale()](#createGrayScale--) | 创建 Gray scale 效果。 |
| [createHSL(float hue, float saturation, float luminance)](#createHSL-float-float-float-) | 创建 Hue Saturation Luminance 效果。 |
| [createLuminance(float brightness, float contrast)](#createLuminance-float-float-) | 创建 Luminance 效果。 |
| [createTint(float hue, float amount)](#createTint-float-float-) | 创建 Tint 效果。 |
### createAlphaBiLevel(float threshold) {#createAlphaBiLevel-float-}
```
public abstract IAlphaBiLevel createAlphaBiLevel(float threshold)
```

创建 Alpha BiLevel 效果。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| threshold | float | 阈值。 |

**返回值：**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Alpha BiLevel 效果。

### createAlphCeiling() {#createAlphCeiling--}
```
public abstract IAlphaCeiling createAlphCeiling()
```

创建 Alpha Ceiling 效果。

**返回值：**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Alpha Ceiling 效果。

### createAlphaFloor() {#createAlphaFloor--}
```
public abstract IAlphaFloor createAlphaFloor()
```

创建 Alpha floor 效果。

**返回值：**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Alpha floor 效果。

### createAlphaInverse() {#createAlphaInverse--}
```
public abstract IAlphaInverse createAlphaInverse()
```

创建 Alpha inverse 效果。

**返回值：**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Alpha inverst 效果。

### createAlphaModulate() {#createAlphaModulate--}
```
public abstract IAlphaModulate createAlphaModulate()
```

创建 Alpha modulate 效果。

**返回值：**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Alpha modulate 效果。

### createAlphaModulateFixed(float amount) {#createAlphaModulateFixed-float-}
```
public abstract IAlphaModulateFixed createAlphaModulateFixed(float amount)
```

创建 Alpha modulate fixed 效果。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| amount | float | Amount。 |

**返回值：**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Alpha modulate fixed 效果。

### createAlphaReplace(float alpha) {#createAlphaReplace-float-}
```
public abstract IAlphaReplace createAlphaReplace(float alpha)
```

创建 Alpha replace 效果。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| alpha | float | Alpha |

**返回值：**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Alpha replace 效果。

### createBiLevel(float threshold) {#createBiLevel-float-}
```
public abstract IBiLevel createBiLevel(float threshold)
```

创建 BiLevel 效果。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| threshold | float | 阈值。 |

**返回值：**
[IBiLevel](../../com.aspose.slides/ibilevel) - BiLevel 效果。

### createBlur(double radius, boolean grow) {#createBlur-double-boolean-}
```
public abstract IBlur createBlur(double radius, boolean grow)
```

创建 Blur 效果。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| radius | double | Radius。 |
| grow | boolean | Grow。 |

**返回值：**
[IBlur](../../com.aspose.slides/iblur) - Blur 效果。

### createColorChange() {#createColorChange--}
```
public abstract IColorChange createColorChange()
```

创建 Color change 效果。

**返回值：**
[IColorChange](../../com.aspose.slides/icolorchange) - Color change 效果。

### createColorReplace() {#createColorReplace--}
```
public abstract IColorReplace createColorReplace()
```

创建 Color replace 效果。

**返回值：**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Color replace 效果。

### createDuotone() {#createDuotone--}
```
public abstract IDuotone createDuotone()
```

创建 Duotone 效果。

**返回值：**
[IDuotone](../../com.aspose.slides/iduotone) - Duotone 效果。

### createFillOverlay() {#createFillOverlay--}
```
public abstract IFillOverlay createFillOverlay()
```

创建 Fill overlay 效果。

**返回值：**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Fill overlay 效果。

### createGrayScale() {#createGrayScale--}
```
public abstract IGrayScale createGrayScale()
```

创建 Gray scale 效果。

**返回值：**
[IGrayScale](../../com.aspose.slides/igrayscale) - 返回 Gray scale 效果。

### createHSL(float hue, float saturation, float luminance) {#createHSL-float-float-float-}
```
public abstract IHSL createHSL(float hue, float saturation, float luminance)
```

创建 Hue Saturation Luminance 效果。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| hue | float | Hue。 |
| saturation | float | Saturation。 |
| luminance | float | Luminance。 |

**返回值：**
[IHSL](../../com.aspose.slides/ihsl) - HSL 效果。

### createLuminance(float brightness, float contrast) {#createLuminance-float-float-}
```
public abstract ILuminance createLuminance(float brightness, float contrast)
```

创建 Luminance 效果。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| brightness | float | Brightness。 |
| contrast | float | Contrast。 |

**返回值：**
[ILuminance](../../com.aspose.slides/iluminance) - Luminance 效果。

### createTint(float hue, float amount) {#createTint-float-float-}
```
public abstract ITint createTint(float hue, float amount)
```

创建 Tint 效果。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| hue | float | Hue。 |
| amount | float | Amount。 |

**返回值：**
[ITint](../../com.aspose.slides/itint) - Tint 效果。