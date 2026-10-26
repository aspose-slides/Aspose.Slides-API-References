---
title: ImageTransformOperationFactory
second_title: Aspose.Slides Java API Referansı
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
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ImageTransformOperationFactory()](#ImageTransformOperationFactory--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [createAlphaBiLevel(float threshold)](#createAlphaBiLevel-float-) | Alpha BiLevel etkisi oluşturur. |
| [createAlphCeiling()](#createAlphCeiling--) | Alpha Ceiling etkisi oluşturur. |
| [createAlphaFloor()](#createAlphaFloor--) | Alpha floor etkisi oluşturur. |
| [createAlphaInverse()](#createAlphaInverse--) | Alpha inverse etkisi oluşturur. |
| [createAlphaModulate()](#createAlphaModulate--) | Alpha modulate etkisi oluşturur. |
| [createAlphaModulateFixed(float amount)](#createAlphaModulateFixed-float-) | Alpha modulate fixed etkisi oluşturur. |
| [createAlphaReplace(float alpha)](#createAlphaReplace-float-) | Alpha replace etkisi oluşturur. |
| [createBiLevel(float threshold)](#createBiLevel-float-) | BiLevel etkisi oluşturur. |
| [createBlur(double radius, boolean grow)](#createBlur-double-boolean-) | Blur etkisi oluşturur. |
| [createColorChange()](#createColorChange--) | Color change etkisi oluşturur. |
| [createColorReplace()](#createColorReplace--) | Color replace etkisi oluşturur. |
| [createDuotone()](#createDuotone--) | Duotone etkisi oluşturur. |
| [createFillOverlay()](#createFillOverlay--) | Fill overlay etkisi oluşturur. |
| [createGrayScale()](#createGrayScale--) | Gray scale etkisi oluşturur. |
| [createHSL(float hue, float saturation, float luminance)](#createHSL-float-float-float-) | Hue Saturation Luminance etkisi oluşturur. |
| [createLuminance(float brightness, float contrast)](#createLuminance-float-float-) | Luminance etkisi oluşturur. |
| [createTint(float hue, float amount)](#createTint-float-float-) | Tint etkisi oluşturur. |
### ImageTransformOperationFactory() {#ImageTransformOperationFactory--}
```
public ImageTransformOperationFactory()
```


### createAlphaBiLevel(float threshold) {#createAlphaBiLevel-float-}
```
public final IAlphaBiLevel createAlphaBiLevel(float threshold)
```


Alpha BiLevel etkisi oluşturur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| threshold | float | Eşik. |

**Döndürür:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Alpha BiLevel etkisi.
### createAlphCeiling() {#createAlphCeiling--}
```
public final IAlphaCeiling createAlphCeiling()
```


Alpha Ceiling etkisi oluşturur.

**Döndürür:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Alpha Ceiling etkisi.
### createAlphaFloor() {#createAlphaFloor--}
```
public final IAlphaFloor createAlphaFloor()
```


Alpha floor etkisi oluşturur.

**Döndürür:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Alpha floor etkisi.
### createAlphaInverse() {#createAlphaInverse--}
```
public final IAlphaInverse createAlphaInverse()
```


Alpha inverse etkisi oluşturur.

**Döndürür:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Alpha inverst etkisi.
### createAlphaModulate() {#createAlphaModulate--}
```
public final IAlphaModulate createAlphaModulate()
```


Alpha modulate etkisi oluşturur.

**Döndürür:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Alpha modulate etkisi.
### createAlphaModulateFixed(float amount) {#createAlphaModulateFixed-float-}
```
public final IAlphaModulateFixed createAlphaModulateFixed(float amount)
```


Alpha modulate fixed etkisi oluşturur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| amount | float | Miktar. |

**Döndürür:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Alpha modulate fixed etkisi.
### createAlphaReplace(float alpha) {#createAlphaReplace-float-}
```
public final IAlphaReplace createAlphaReplace(float alpha)
```


Alpha replace etkisi oluşturur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| alpha | float | Alpha |

**Döndürür:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Alpha replace etkisi.
### createBiLevel(float threshold) {#createBiLevel-float-}
```
public final IBiLevel createBiLevel(float threshold)
```


BiLevel etkisi oluşturur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| threshold | float | Eşik. |

**Döndürür:**
[IBiLevel](../../com.aspose.slides/ibilevel) - BiLevel etkisi.
### createBlur(double radius, boolean grow) {#createBlur-double-boolean-}
```
public final IBlur createBlur(double radius, boolean grow)
```


Blur etkisi oluşturur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| radius | double | Yarıçap. |
| grow | boolean | Büyüt. |

**Döndürür:**
[IBlur](../../com.aspose.slides/iblur) - Blur etkisi.
### createColorChange() {#createColorChange--}
```
public final IColorChange createColorChange()
```


Color change etkisi oluşturur.

**Döndürür:**
[IColorChange](../../com.aspose.slides/icolorchange) - Color change etkisi.
### createColorReplace() {#createColorReplace--}
```
public final IColorReplace createColorReplace()
```


Color replace etkisi oluşturur.

**Döndürür:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Color replace etkisi.
### createDuotone() {#createDuotone--}
```
public final IDuotone createDuotone()
```


Duotone etkisi oluşturur.

**Döndürür:**
[IDuotone](../../com.aspose.slides/iduotone) - Duotone etkisi.
### createFillOverlay() {#createFillOverlay--}
```
public final IFillOverlay createFillOverlay()
```


Fill overlay etkisi oluşturur.

**Döndürür:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Fill overlay etkisi.
### createGrayScale() {#createGrayScale--}
```
public final IGrayScale createGrayScale()
```


Gray scale etkisi oluşturur.

**Döndürür:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Gray scale etkisi oluşturur.
### createHSL(float hue, float saturation, float luminance) {#createHSL-float-float-float-}
```
public final IHSL createHSL(float hue, float saturation, float luminance)
```


Hue Saturation Luminance etkisi oluşturur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| hue | float | Renk tonu. |
| saturation | float | Doygunluk. |
| luminance | float | Luminance. |

**Döndürür:**
[IHSL](../../com.aspose.slides/ihsl) - HSL etkisi.
### createLuminance(float brightness, float contrast) {#createLuminance-float-float-}
```
public final ILuminance createLuminance(float brightness, float contrast)
```


Luminance etkisi oluşturur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brightness | float | Parlaklık. |
| contrast | float | Kontrast. |

**Döndürür:**
[ILuminance](../../com.aspose.slides/iluminance) - Luminance etkisi.
### createTint(float hue, float amount) {#createTint-float-float-}
```
public final ITint createTint(float hue, float amount)
```


Tint etkisi oluşturur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| hue | float | Renk tonu. |
| amount | float | Miktar. |

**Döndürür:**
[ITint](../../com.aspose.slides/itint) - Tint etkisi.