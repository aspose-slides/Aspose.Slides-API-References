---
title: ImageTransformOperationFactory
second_title: Aspose.Slides สำหรับ Java API Reference
description: อนุญาตให้สร้างการแปลงภาพ
type: docs
url: /th/com.aspose.slides/imagetransformoperationfactory/
---
**Inheritance:**  
การสืบทอด:

java.lang.Object

**All Implemented Interfaces:**  
อินเทอร์เฟซที่นำไปใช้ทั้งหมด:

[com.aspose.slides.IImageTransformOperationFactory](../../com.aspose.slides/iimagetransformoperationfactory)
```
public class ImageTransformOperationFactory implements IImageTransformOperationFactory
```

Allows to create image transform operations  
อนุญาตให้สร้างการแปลงภาพ

--------------------

For COM compatibility.  
เพื่อความเข้ากันได้กับ COM.

## Constructors

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [ImageTransformOperationFactory()](#ImageTransformOperationFactory--) |  |

## Methods

| เมธอด | คำอธิบาย |
| --- | --- |
| [createAlphaBiLevel(float threshold)](#createAlphaBiLevel-float-) | Creates Alpha BiLevel effect. |
| [createAlphCeiling()](#createAlphCeiling--) | Creates Alpha Ceiling effect. |
| [createAlphaFloor()](#createAlphaFloor--) | Creates Alpha floor effect. |
| [createAlphaInverse()](#createAlphaInverse--) | Creates Alpha inverse effect. |
| [createAlphaModulate()](#createAlphaModulate--) | Creates Alpha modulate effect. |
| [createAlphaModulateFixed(float amount)](#createAlphaModulateFixed-float-) | Creates Alpha modulate fixed effect. |
| [createAlphaReplace(float alpha)](#createAlphaReplace-float-) | Creates Alpha replace effect. |
| [createBiLevel(float threshold)](#createBiLevel-float-) | Creates BiLevel effect. |
| [createBlur(double radius, boolean grow)](#createBlur-double-boolean-) | Creates Blur effect. |
| [createColorChange()](#createColorChange--) | Creates Color change effect. |
| [createColorReplace()](#createColorReplace--) | Creates Color replace effect. |
| [createDuotone()](#createDuotone--) | Creates Duotone effect. |
| [createFillOverlay()](#createFillOverlay--) | Creates Fill overlay effect. |
| [createGrayScale()](#createGrayScale--) | Creates Gray scale effect. |
| [createHSL(float hue, float saturation, float luminance)](#createHSL-float-float-float-) | Creates Hue Saturation Luminance effect. |
| [createLuminance(float brightness, float contrast)](#createLuminance-float-float-) | Createtes Luminance effect. |
| [createTint(float hue, float amount)](#createTint-float-float-) | Creates Tint effect. |

### ImageTransformOperationFactory() {#ImageTransformOperationFactory--}
```
public ImageTransformOperationFactory()
```

### createAlphaBiLevel(float threshold) {#createAlphaBiLevel-float-}
```
public final IAlphaBiLevel createAlphaBiLevel(float threshold)
```

Creates Alpha BiLevel effect.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| threshold | float | Threshold. |

**ผลลัพธ์:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Alpha BiLevel effect.

### createAlphCeiling() {#createAlphCeiling--}
```
public final IAlphaCeiling createAlphCeiling()
```

Creates Alpha Ceiling effect.

**ผลลัพธ์:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Alpha Ceiling effect.

### createAlphaFloor() {#createAlphaFloor--}
```
public final IAlphaFloor createAlphaFloor()
```

Creates Alpha floor effect.

**ผลลัพธ์:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Alpha floor effect.

### createAlphaInverse() {#createAlphaInverse--}
```
public final IAlphaInverse createAlphaInverse()
```

Creates Alpha inverse effect.

**ผลลัพธ์:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Alpha inverst effect.

### createAlphaModulate() {#createAlphaModulate--}
```
public final IAlphaModulate createAlphaModulate()
```

Creates Alpha modulate effect.

**ผลลัพธ์:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Alpha modulate effect.

### createAlphaModulateFixed(float amount) {#createAlphaModulateFixed-float-}
```
public final IAlphaModulateFixed createAlphaModulateFixed(float amount)
```

Creates Alpha modulate fixed effect.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| amount | float | Amount. |

**ผลลัพธ์:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Alpha modulate fixed effect.

### createAlphaReplace(float alpha) {#createAlphaReplace-float-}
```
public final IAlphaReplace createAlphaReplace(float alpha)
```

Creates Alpha replace effect.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| alpha | float | Alpha |

**ผลลัพธ์:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Alpha replace effect.

### createBiLevel(float threshold) {#createBiLevel-float-}
```
public final IBiLevel createBiLevel(float threshold)
```

Creates BiLevel effect.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| threshold | float | Threshold. |

**ผลลัพธ์:**
[IBiLevel](../../com.aspose.slides/ibilevel) - BiLevel effect.

### createBlur(double radius, boolean grow) {#createBlur-double-boolean-}
```
public final IBlur createBlur(double radius, boolean grow)
```

Creates Blur effect.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| radius | double | Radius. |
| grow | boolean | Grow. |

**ผลลัพธ์:**
[IBlur](../../com.aspose.slides/iblur) - Blur effect.

### createColorChange() {#createColorChange--}
```
public final IColorChange createColorChange()
```

Creates Color change effect.

**ผลลัพธ์:**
[IColorChange](../../com.aspose.slides/icolorchange) - Color change effect.

### createColorReplace() {#createColorReplace--}
```
public final IColorReplace createColorReplace()
```

Creates Color replace effect.

**ผลลัพธ์:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Color replace effect.

### createDuotone() {#createDuotone--}
```
public final IDuotone createDuotone()
```

Creates Duotone effect.

**ผลลัพธ์:**
[IDuotone](../../com.aspose.slides/iduotone) - Duotone effect.

### createFillOverlay() {#createFillOverlay--}
```
public final IFillOverlay createFillOverlay()
```

Creates Fill overlay effect.

**ผลลัพธ์:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Fill overlay effect.

### createGrayScale() {#createGrayScale--}
```
public final IGrayScale createGrayScale()
```

Creates Gray scale effect.

**ผลลัพธ์:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Returns gray scale effect.

### createHSL(float hue, float saturation, float luminance) {#createHSL-float-float-float-}
```
public final IHSL createHSL(float hue, float saturation, float luminance)
```

Creates Hue Saturation Luminance effect.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| hue | float | Hue. |
| saturation | float | Saturation. |
| luminance | float | Luminance. |

**ผลลัพธ์:**
[IHSL](../../com.aspose.slides/ihsl) - HSL effect.

### createLuminance(float brightness, float contrast) {#createLuminance-float-float-}
```
public final ILuminance createLuminance(float brightness, float contrast)
```

Createtes Luminance effect.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| brightness | float | Brightness. |
| contrast | float | Contrast. |

**ผลลัพธ์:**
[ILuminance](../../com.aspose.slides/iluminance) - Luminance effect.

### createTint(float hue, float amount) {#createTint-float-float-}
```
public final ITint createTint(float hue, float amount)
```

Creates Tint effect.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| hue | float | Hue. |
| amount | float | Amount. |

**ผลลัพธ์:**
[ITint](../../com.aspose.slides/itint) - Tint effect.