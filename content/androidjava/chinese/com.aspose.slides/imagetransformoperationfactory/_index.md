---
title: ImageTransformOperationFactory
second_title: Aspose.Slides for Android 通过 Java API 参考
description: 允许创建图像变换操作
type: docs
url: /zh/com.aspose.slides/imagetransformoperationfactory/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IImageTransformOperationFactory](../../com.aspose.slides/iimagetransformoperationfactory)  
```
public class ImageTransformOperationFactory implements IImageTransformOperationFactory
```

允许创建图像变换操作

--------------------

用于 COM 兼容性。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ImageTransformOperationFactory()](#ImageTransformOperationFactory--) |  |

## 方法

| 方法 | 描述 |
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

### ImageTransformOperationFactory() {#ImageTransformOperationFactory--}
```
public ImageTransformOperationFactory()
```

### createAlphaBiLevel(float threshold) {#createAlphaBiLevel-float-}
```
public final IAlphaBiLevel createAlphaBiLevel(float threshold)
```

创建 Alpha BiLevel 效果。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| threshold | float | 阈值。 |

**返回：**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Alpha BiLevel 效果。

### createAlphCeiling() {#createAlphCeiling--}
```
public final IAlphaCeiling createAlphCeiling()
```

创建 Alpha Ceiling 效果。

**返回：**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Alpha Ceiling 效果。

### createAlphaFloor() {#createAlphaFloor--}
```
public final IAlphaFloor createAlphaFloor()
```

创建 Alpha floor 效果。

**返回：**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Alpha floor 效果。

### createAlphaInverse() {#createAlphaInverse--}
```
public final IAlphaInverse createAlphaInverse()
```

创建 Alpha inverse 效果。

**返回：**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Alpha inverst 效果。

### createAlphaModulate() {#createAlphaModulate--}
```
public final IAlphaModulate createAlphaModulate()
```

创建 Alpha modulate 效果。

**返回：**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Alpha modulate 效果。

### createAlphaModulateFixed(float amount) {#createAlphaModulateFixed-float-}
```
public final IAlphaModulateFixed createAlphaModulateFixed(float amount)
```

创建 Alpha modulate fixed 效果。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| amount | float | 数量。 |

**返回：**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Alpha modulate fixed 效果。

### createAlphaReplace(float alpha) {#createAlphaReplace-float-}
```
public final IAlphaReplace createAlphaReplace(float alpha)
```

创建 Alpha replace 效果。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| alpha | float | Alpha 值。 |

**返回：**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Alpha replace 效果。

### createBiLevel(float threshold) {#createBiLevel-float-}
```
public final IBiLevel createBiLevel(float threshold)
```

创建 BiLevel 效果。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| threshold | float | 阈值。 |

**返回：**
[IBiLevel](../../com.aspose.slides/ibilevel) - BiLevel 效果。

### createBlur(double radius, boolean grow) {#createBlur-double-boolean-}
```
public final IBlur createBlur(double radius, boolean grow)
```

创建 Blur 效果。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| radius | double | 半径。 |
| grow | boolean | 是否增长。 |

**返回：**
[IBlur](../../com.aspose.slides/iblur) - Blur 效果。

### createColorChange() {#createColorChange--}
```
public final IColorChange createColorChange()
```

创建 Color change 效果。

**返回：**
[IColorChange](../../com.aspose.slides/icolorchange) - Color change 效果。

### createColorReplace() {#createColorReplace--}
```
public final IColorReplace createColorReplace()
```

创建 Color replace 效果。

**返回：**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Color replace 效果。

### createDuotone() {#createDuotone--}
```
public final IDuotone createDuotone()
```

创建 Duotone 效果。

**返回：**
[IDuotone](../../com.aspose.slides/iduotone) - Duotone 效果。

### createFillOverlay() {#createFillOverlay--}
```
public final IFillOverlay createFillOverlay()
```

创建 Fill overlay 效果。

**返回：**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Fill overlay 效果。

### createGrayScale() {#createGrayScale--}
```
public final IGrayScale createGrayScale()
```

创建 Gray scale 效果。

**返回：**
[IGrayScale](../../com.aspose.slides/igrayscale) - 返回 Gray scale 效果。

### createHSL(float hue, float saturation, float luminance) {#createHSL-float-float-float-}
```
public final IHSL createHSL(float hue, float saturation, float luminance)
```

创建 Hue Saturation Luminance 效果。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| hue | float | 色相。 |
| saturation | float | 饱和度。 |
| luminance | float | 亮度。 |

**返回：**
[IHSL](../../com.aspose.slides/ihsl) - HSL 效果。

### createLuminance(float brightness, float contrast) {#createLuminance-float-float-}
```
public final ILuminance createLuminance(float brightness, float contrast)
```

创建 Luminance 效果。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brightness | float | 亮度。 |
| contrast | float | 对比度。 |

**返回：**
[ILuminance](../../com.aspose.slides/iluminance) - Luminance 效果。

### createTint(float hue, float amount) {#createTint-float-float-}
```
public final ITint createTint(float hue, float amount)
```

创建 Tint 效果。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| hue | float | 色相。 |
| amount | float | 数量。 |

**返回：**
[ITint](../../com.aspose.slides/itint) - Tint 效果。