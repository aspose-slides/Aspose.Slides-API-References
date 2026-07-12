---
title: ImageTransformOperationFactory
second_title: Aspose.Slides for Android üzerinden Java API Referansı
description: Görüntü dönüşüm işlemleri oluşturmayı sağlar
type: docs
url: /tr/com.aspose.slides/imagetransformoperationfactory/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IImageTransformOperationFactory](../../com.aspose.slides/iimagetransformoperationfactory)
```
public class ImageTransformOperationFactory implements IImageTransformOperationFactory
```

Görüntü dönüşüm işlemleri oluşturmaya izin verir

--------------------

COM uyumluluğu için.
## Constructors

| Constructor | Description |
| --- | --- |
| [ImageTransformOperationFactory()](#ImageTransformOperationFactory--) |  |
## Methods

| Method | Description |
| --- | --- |
| [createAlphaBiLevel(float threshold)](#createAlphaBiLevel-float-) | Alpha BiLevel etkisini oluşturur. |
| [createAlphCeiling()](#createAlphCeiling--) | Alpha Ceiling etkisini oluşturur. |
| [createAlphaFloor()](#createAlphaFloor--) | Alpha floor etkisini oluşturur. |
| [createAlphaInverse()](#createAlphaInverse--) | Alpha inverse etkisini oluşturur. |
| [createAlphaModulate()](#createAlphaModulate--) | Alpha modulate etkisini oluşturur. |
| [createAlphaModulateFixed(float amount)](#createAlphaModulateFixed-float-) | Alpha modulate fixed etkisini oluşturur. |
| [createAlphaReplace(float alpha)](#createAlphaReplace-float-) | Alpha replace etkisini oluşturur. |
| [createBiLevel(float threshold)](#createBiLevel-float-) | BiLevel etkisini oluşturur. |
| [createBlur(double radius, boolean grow)](#createBlur-double-boolean-) | Blur etkisini oluşturur. |
| [createColorChange()](#createColorChange--) | Color change etkisini oluşturur. |
| [createColorReplace()](#createColorReplace--) | Color replace etkisini oluşturur. |
| [createDuotone()](#createDuotone--) | Duotone etkisini oluşturur. |
| [createFillOverlay()](#createFillOverlay--) | Fill overlay etkisini oluşturur. |
| [createGrayScale()](#createGrayScale--) | Gray scale etkisini oluşturur. |
| [createHSL(float hue, float saturation, float luminance)](#createHSL-float-float-float-) | Hue Saturation Luminance etkisini oluşturur. |
| [createLuminance(float brightness, float contrast)](#createLuminance-float-float-) | Luminance etkisini oluşturur. |
| [createTint(float hue, float amount)](#createTint-float-float-) | Tint etkisini oluşturur. |
### ImageTransformOperationFactory() {#ImageTransformOperationFactory--}
```
public ImageTransformOperationFactory()
```

### createAlphaBiLevel(float threshold) {#createAlphaBiLevel-float-}
```
public final IAlphaBiLevel createAlphaBiLevel(float threshold)
```

Alpha BiLevel etkisini oluşturur.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| threshold | float | Threshold. |

**Returns:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Alpha BiLevel etkisi.
### createAlphCeiling() {#createAlphCeiling--}
```
public final IAlphaCeiling createAlphCeiling()
```

Alpha Ceiling etkisini oluşturur.

**Returns:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Alpha Ceiling etkisi.
### createAlphaFloor() {#createAlphaFloor--}
```
public final IAlphaFloor createAlphaFloor()
```

Alpha floor etkisini oluşturur.

**Returns:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Alpha floor etkisi.
### createAlphaInverse() {#createAlphaInverse--}
```
public final IAlphaInverse createAlphaInverse()
```

Alpha inverse etkisini oluşturur.

**Returns:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Alpha inverst etkisi.
### createAlphaModulate() {#createAlphaModulate--}
```
public final IAlphaModulate createAlphaModulate()
```

Alpha modulate etkisini oluşturur.

**Returns:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Alpha modulate etkisi.
### createAlphaModulateFixed(float amount) {#createAlphaModulateFixed-float-}
```
public final IAlphaModulateFixed createAlphaModulateFixed(float amount)
```

Alpha modulate fixed etkisini oluşturur.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| amount | float | Amount. |

**Returns:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Alpha modulate fixed etkisi.
### createAlphaReplace(float alpha) {#createAlphaReplace-float-}
```
public final IAlphaReplace createAlphaReplace(float alpha)
```

Alpha replace etkisini oluşturur.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| alpha | float | Alpha |

**Returns:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Alpha replace etkisi.
### createBiLevel(float threshold) {#createBiLevel-float-}
```
public final IBiLevel createBiLevel(float threshold)
```

BiLevel etkisini oluşturur.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| threshold | float | Threshold. |

**Returns:**
[IBiLevel](../../com.aspose.slides/ibilevel) - BiLevel etkisi.
### createBlur(double radius, boolean grow) {#createBlur-double-boolean-}
```
public final IBlur createBlur(double radius, boolean grow)
```

Blur etkisini oluşturur.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| radius | double | Radius. |
| grow | boolean | Grow. |

**Returns:**
[IBlur](../../com.aspose.slides/iblur) - Blur etkisi.
### createColorChange() {#createColorChange--}
```
public final IColorChange createColorChange()
```

Color change etkisini oluşturur.

**Returns:**
[IColorChange](../../com.aspose.slides/icolorchange) - Color change etkisi.
### createColorReplace() {#createColorReplace--}
```
public final IColorReplace createColorReplace()
```

Color replace etkisini oluşturur.

**Returns:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Color replace etkisi.
### createDuotone() {#createDuotone--}
```
public final IDuotone createDuotone()
```

Duotone etkisini oluşturur.

**Returns:**
[IDuotone](../../com.aspose.slides/iduotone) - Duotone etkisi.
### createFillOverlay() {#createFillOverlay--}
```
public final IFillOverlay createFillOverlay()
```

Fill overlay etkisini oluşturur.

**Returns:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Fill overlay etkisi.
### createGrayScale() {#createGrayScale--}
```
public final IGrayScale createGrayScale()
```

Gray scale etkisini oluşturur.

**Returns:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Gray scale etkisini döndürür.
### createHSL(float hue, float saturation, float luminance) {#createHSL-float-float-float-}
```
public final IHSL createHSL(float hue, float saturation, float luminance)
```

Hue Saturation Luminance etkisini oluşturur.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| hue | float | Hue. |
| saturation | float | Saturation. |
| luminance | float | Luminance. |

**Returns:**
[IHSL](../../com.aspose.slides/ihsl) - HSL etkisi.
### createLuminance(float brightness, float contrast) {#createLuminance-float-float-}
```
public final ILuminance createLuminance(float brightness, float contrast)
```

Luminance etkisini oluşturur.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brightness | float | Brightness. |
| contrast | float | Contrast. |

**Returns:**
[ILuminance](../../com.aspose.slides/iluminance) - Luminance etkisi.
### createTint(float hue, float amount) {#createTint-float-float-}
```
public final ITint createTint(float hue, float amount)
```

Tint etkisini oluşturur.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| hue | float | Hue. |
| amount | float | Amount. |

**Returns:**
[ITint](../../com.aspose.slides/itint) - Tint etkisi.