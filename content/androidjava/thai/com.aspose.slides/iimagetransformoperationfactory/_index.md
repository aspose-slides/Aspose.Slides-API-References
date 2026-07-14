---
title: IImageTransformOperationFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create image effects instances
type: docs
url: /th/com.aspose.slides/iimagetransformoperationfactory/
---```
public interface IImageTransformOperationFactory
```

อนุญาตให้สร้างอินสแตนซ์ของเอฟเฟกต์ภาพ

สำหรับอินเทอร์เฟซ COM.

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [createAlphaBiLevel(float threshold)](#createAlphaBiLevel-float-) | สร้างเอฟเฟกต์ Alpha BiLevel |
| [createAlphCeiling()](#createAlphCeiling--) | สร้างเอฟเฟกต์ Alpha Ceiling |
| [createAlphaFloor()](#createAlphaFloor--) | สร้างเอฟเฟกต์ Alpha floor |
| [createAlphaInverse()](#createAlphaInverse--) | สร้างเอฟเฟกต์ Alpha inverse |
| [createAlphaModulate()](#createAlphaModulate--) | สร้างเอฟเฟกต์ Alpha modulate |
| [createAlphaModulateFixed(float amount)](#createAlphaModulateFixed-float-) | สร้างเอฟเฟกต์ Alpha modulate fixed |
| [createAlphaReplace(float alpha)](#createAlphaReplace-float-) | สร้างเอฟเฟกต์ Alpha replace |
| [createBiLevel(float threshold)](#createBiLevel-float-) | สร้างเอฟเฟ็กต์ BiLevel |
| [createBlur(double radius, boolean grow)](#createBlur-double-boolean-) | สร้างเอฟเฟกต์ Blur |
| [createColorChange()](#createColorChange--) | สร้างเอฟเฟกต์ Color change |
| [createColorReplace()](#createColorReplace--) | สร้างเอฟเฟกต์ Color replace |
| [createDuotone()](#createDuotone--) | สร้างเอฟเฟกต์ Duotone |
| [createFillOverlay()](#createFillOverlay--) | สร้างเอฟเฟกต์ Fill overlay |
| [createGrayScale()](#createGrayScale--) | สร้างเอฟเฟกต์ Gray scale |
| [createHSL(float hue, float saturation, float luminance)](#createHSL-float-float-float-) | สร้างเอฟเฟกต์ Hue Saturation Luminance |
| [createLuminance(float brightness, float contrast)](#createLuminance-float-float-) | สร้างเอฟเฟกต์ Luminance |
| [createTint(float hue, float amount)](#createTint-float-float-) | สร้างเอฟเฟกต์ Tint |
### createAlphaBiLevel(float threshold) {#createAlphaBiLevel-float-}
```
public abstract IAlphaBiLevel createAlphaBiLevel(float threshold)
```

สร้างเอฟเฟกต์ Alpha BiLevel

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| threshold | float | ค่าขีดจำกัด |

**ค่าที่ส่งคืน:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Alpha BiLevel effect.
### createAlphCeiling() {#createAlphCeiling--}
```
public abstract IAlphaCeiling createAlphCeiling()
```

สร้างเอฟเฟกต์ Alpha Ceiling

**ค่าที่ส่งคืน:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Alpha Ceiling effect.
### createAlphaFloor() {#createAlphaFloor--}
```
public abstract IAlphaFloor createAlphaFloor()
```

สร้างเอฟเฟกต์ Alpha floor

**ค่าที่ส่งคืน:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Alpha floor effect.
### createAlphaInverse() {#createAlphaInverse--}
```
public abstract IAlphaInverse createAlphaInverse()
```

สร้างเอฟเฟกต์ Alpha inverse

**ค่าที่ส่งคืน:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Alpha inverst effect.
### createAlphaModulate() {#createAlphaModulate--}
```
public abstract IAlphaModulate createAlphaModulate()
```

สร้างเอฟเฟกต์ Alpha modulate

**ค่าที่ส่งคืน:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Alpha modulate effect.
### createAlphaModulateFixed(float amount) {#createAlphaModulateFixed-float-}
```
public abstract IAlphaModulateFixed createAlphaModulateFixed(float amount)
```

สร้างเอฟเฟกต์ Alpha modulate fixed

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| amount | float | จำนวน |

**ค่าที่ส่งคืน:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Alpha modulate fixed effect.
### createAlphaReplace(float alpha) {#createAlphaReplace-float-}
```
public abstract IAlphaReplace createAlphaReplace(float alpha)
```

สร้างเอฟเฟกต์ Alpha replace

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| alpha | float | Alpha |

**ค่าที่ส่งคืน:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Alpha replace effect.
### createBiLevel(float threshold) {#createBiLevel-float-}
```
public abstract IBiLevel createBiLevel(float threshold)
```

สร้างเอฟเฟ็กต์ BiLevel

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| threshold | float | ค่าขีดจำกัด |

**ค่าที่ส่งคืน:**
[IBiLevel](../../com.aspose.slides/ibilevel) - BiLevel effect.
### createBlur(double radius, boolean grow) {#createBlur-double-boolean-}
```
public abstract IBlur createBlur(double radius, boolean grow)
```

สร้างเอฟเฟกต์ Blur

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| radius | double | รัศมี |
| grow | boolean | Grow |

**ค่าที่ส่งคืน:**
[IBlur](../../com.aspose.slides/iblur) - Blur effect.
### createColorChange() {#createColorChange--}
```
public abstract IColorChange createColorChange()
```

สร้างเอฟเฟกต์ Color change

**ค่าที่ส่งคืน:**
[IColorChange](../../com.aspose.slides/icolorchange) - Color change effect.
### createColorReplace() {#createColorReplace--}
```
public abstract IColorReplace createColorReplace()
```

สร้างเอฟเฟกต์ Color replace

**ค่าที่ส่งคืน:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Color replace effect.
### createDuotone() {#createDuotone--}
```
public abstract IDuotone createDuotone()
```

สร้างเอฟเฟกต์ Duotone

**ค่าที่ส่งคืน:**
[IDuotone](../../com.aspose.slides/iduotone) - Duotone effect.
### createFillOverlay() {#createFillOverlay--}
```
public abstract IFillOverlay createFillOverlay()
```

สร้างเอฟเฟกต์ Fill overlay

**ค่าที่ส่งคืน:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Fill overlay effect.
### createGrayScale() {#createGrayScale--}
```
public abstract IGrayScale createGrayScale()
```

สร้างเอฟเฟกต์ Gray scale

**ค่าที่ส่งคืน:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Returns gray scale effect.
### createHSL(float hue, float saturation, float luminance) {#createHSL-float-float-float-}
```
public abstract IHSL createHSL(float hue, float saturation, float luminance)
```

สร้างเอฟเฟกต์ Hue Saturation Luminance

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| hue | float | Hue |
| saturation | float | Saturation |
| luminance | float | Luminance |

**ค่าที่ส่งคืน:**
[IHSL](../../com.aspose.slides/ihsl) - HSL effect.
### createLuminance(float brightness, float contrast) {#createLuminance-float-float-}
```
public abstract ILuminance createLuminance(float brightness, float contrast)
```

สร้างเอฟเฟกต์ Luminance

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| brightness | float | Brightness |
| contrast | float | Contrast |

**ค่าที่ส่งคืน:**
[ILuminance](../../com.aspose.slides/iluminance) - Luminance effect.
### createTint(float hue, float amount) {#createTint-float-float-}
```
public abstract ITint createTint(float hue, float amount)
```

สร้างเอฟเฟกต์ Tint

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| hue | float | Hue |
| amount | float | Amount |

**ค่าที่ส่งคืน:**
[ITint](../../com.aspose.slides/itint) - Tint effect.