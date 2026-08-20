---
title: IImageTransformOperationFactory
second_title: Aspose.Slides สำหรับ Java API Reference
description: อนุญาตให้สร้างอินสแตนซ์ของเอฟเฟกต์ภาพ
type: docs
url: /th/com.aspose.slides/iimagetransformoperationfactory/
---```
public interface IImageTransformOperationFactory
```

อนุญาตให้สร้างอินสแตนซ์ของเอฟเฟกต์ภาพ

--------------------

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
| [createBiLevel(float threshold)](#createBiLevel-float-) | สร้างเอฟเฟกต์ BiLevel |
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
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| threshold | float | ค่าธรณี |

**ผลลัพธ์:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - เอฟเฟกต์ Alpha BiLevel

### createAlphCeiling() {#createAlphCeiling--}
```
public abstract IAlphaCeiling createAlphCeiling()
```

สร้างเอฟเฟกต์ Alpha Ceiling

**ผลลัพธ์:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - เอฟเฟกต์ Alpha Ceiling

### createAlphaFloor() {#createAlphaFloor--}
```
public abstract IAlphaFloor createAlphaFloor()
```

สร้างเอฟเฟกต์ Alpha floor

**ผลลัพธ์:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - เอฟเฟกต์ Alpha floor

### createAlphaInverse() {#createAlphaInverse--}
```
public abstract IAlphaInverse createAlphaInverse()
```

สร้างเอฟเฟกต์ Alpha inverse

**ผลลัพธ์:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - เอฟเฟกต์ Alpha inverst

### createAlphaModulate() {#createAlphaModulate--}
```
public abstract IAlphaModulate createAlphaModulate()
```

สร้างเอฟเฟกต์ Alpha modulate

**ผลลัพธ์:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - เอฟเฟกต์ Alpha modulate

### createAlphaModulateFixed(float amount) {#createAlphaModulateFixed-float-}
```
public abstract IAlphaModulateFixed createAlphaModulateFixed(float amount)
```

สร้างเอฟเฟกต์ Alpha modulate fixed

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| amount | float | จำนวน |

**ผลลัพธ์:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - เอฟเฟกต์ Alpha modulate fixed

### createAlphaReplace(float alpha) {#createAlphaReplace-float-}
```
public abstract IAlphaReplace createAlphaReplace(float alpha)
```

สร้างเอฟเฟกต์ Alpha replace

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| alpha | float | Alpha |

**ผลลัพธ์:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - เอฟเฟกต์ Alpha replace

### createBiLevel(float threshold) {#createBiLevel-float-}
```
public abstract IBiLevel createBiLevel(float threshold)
```

สร้างเอฟเฟกต์ BiLevel

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| threshold | float | ค่าธรณี |

**ผลลัพธ์:**
[IBiLevel](../../com.aspose.slides/ibilevel) - เอฟเฟกต์ BiLevel

### createBlur(double radius, boolean grow) {#createBlur-double-boolean-}
```
public abstract IBlur createBlur(double radius, boolean grow)
```

สร้างเอฟเฟกต์ Blur

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| radius | double | Radius |
| grow | boolean | Grow |

**ผลลัพธ์:**
[IBlur](../../com.aspose.slides/iblur) - เอฟเฟกต์ Blur

### createColorChange() {#createColorChange--}
```
public abstract IColorChange createColorChange()
```

สร้างเอฟเฟกต์ Color change

**ผลลัพธ์:**
[IColorChange](../../com.aspose.slides/icolorchange) - เอฟเฟกต์ Color change

### createColorReplace() {#createColorReplace--}
```
public abstract IColorReplace createColorReplace()
```

สร้างเอฟเฟกต์ Color replace

**ผลลัพธ์:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - เอฟเฟกต์ Color replace

### createDuotone() {#createDuotone--}
```
public abstract IDuotone createDuotone()
```

สร้างเอฟเฟกต์ Duotone

**ผลลัพธ์:**
[IDuotone](../../com.aspose.slides/iduotone) - เอฟเฟกต์ Duotone

### createFillOverlay() {#createFillOverlay--}
```
public abstract IFillOverlay createFillOverlay()
```

สร้างเอฟเฟกต์ Fill overlay

**ผลลัพธ์:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - เอฟเฟกต์ Fill overlay

### createGrayScale() {#createGrayScale--}
```
public abstract IGrayScale createGrayScale()
```

สร้างเอฟเฟกต์ Gray scale

**ผลลัพธ์:**
[IGrayScale](../../com.aspose.slides/igrayscale) - สร้างเอฟเฟกต์ Gray scale

### createHSL(float hue, float saturation, float luminance) {#createHSL-float-float-float-}
```
public abstract IHSL createHSL(float hue, float saturation, float luminance)
```

สร้างเอฟเฟกต์ Hue Saturation Luminance

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| hue | float | Hue |
| saturation | float | Saturation |
| luminance | float | Luminance |

**ผลลัพธ์:**
[IHSL](../../com.aspose.slides/ihsl) - เอฟเฟกต์ HSL

### createLuminance(float brightness, float contrast) {#createLuminance-float-float-}
```
public abstract ILuminance createLuminance(float brightness, float contrast)
```

สร้างเอฟเฟกต์ Luminance

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| brightness | float | Brightness |
| contrast | float | Contrast |

**ผลลัพธ์:**
[ILuminance](../../com.aspose.slides/iluminance) - เอฟเฟกต์ Luminance

### createTint(float hue, float amount) {#createTint-float-float-}
```
public abstract ITint createTint(float hue, float amount)
```

สร้างเอฟเฟกต์ Tint

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| hue | float | Hue |
| amount | float | จำนวน |

**ผลลัพธ์:**
[ITint](../../com.aspose.slides/itint) - เอฟเฟกต์ Tint