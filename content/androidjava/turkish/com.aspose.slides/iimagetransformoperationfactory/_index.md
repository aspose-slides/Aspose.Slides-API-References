---
title: IImageTransformOperationFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create image effects instances
type: docs
url: /tr/com.aspose.slides/iimagetransformoperationfactory/
---```
public interface IImageTransformOperationFactory
```

Görüntü efektlerinin örneklerini oluşturmayı sağlar

--------------------

COM arabirimi için.
## Yöntemler

| Yöntem | Açıklama |
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
### createAlphaBiLevel(float threshold) {#createAlphaBiLevel-float-}
```
public abstract IAlphaBiLevel createAlphaBiLevel(float threshold)
```


Alpha BiLevel etkisini oluşturur.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| threshold | float | Eşik. |

**Döndürür:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Alpha BiLevel etkisi.
### createAlphCeiling() {#createAlphCeiling--}
```
public abstract IAlphaCeiling createAlphCeiling()
```


Alpha Ceiling etkisini oluşturur.

**Döndürür:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Alpha Ceiling etkisi.
### createAlphaFloor() {#createAlphaFloor--}
```
public abstract IAlphaFloor createAlphaFloor()
```


Alpha floor etkisini oluşturur.

**Döndürür:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Alpha floor etkisi.
### createAlphaInverse() {#createAlphaInverse--}
```
public abstract IAlphaInverse createAlphaInverse()
```


Alpha inverse etkisini oluşturur.

**Döndürür:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Alpha inverst etkisi.
### createAlphaModulate() {#createAlphaModulate--}
```
public abstract IAlphaModulate createAlphaModulate()
```


Alpha modulate etkisini oluşturur.

**Döndürür:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Alpha modulate etkisi.
### createAlphaModulateFixed(float amount) {#createAlphaModulateFixed-float-}
```
public abstract IAlphaModulateFixed createAlphaModulateFixed(float amount)
```


Alpha modulate fixed etkisini oluşturur.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| amount | float | Miktar. |

**Döndürür:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Alpha modulate fixed etkisi.
### createAlphaReplace(float alpha) {#createAlphaReplace-float-}
```
public abstract IAlphaReplace createAlphaReplace(float alpha)
```


Alpha replace etkisini oluşturur.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| alpha | float | Alpha |

**Döndürür:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Alpha replace etkisi.
### createBiLevel(float threshold) {#createBiLevel-float-}
```
public abstract IBiLevel createBiLevel(float threshold)
```


BiLevel etkisini oluşturur.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| threshold | float | Eşik. |

**Döndürür:**
[IBiLevel](../../com.aspose.slides/ibilevel) - BiLevel etkisi.
### createBlur(double radius, boolean grow) {#createBlur-double-boolean-}
```
public abstract IBlur createBlur(double radius, boolean grow)
```


Blur etkisini oluşturur.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| radius | double | Yarıçap. |
| grow | boolean | Büyüt. |

**Döndürür:**
[IBlur](../../com.aspose.slides/iblur) - Blur etkisi.
### createColorChange() {#createColorChange--}
```
public abstract IColorChange createColorChange()
```


Color change etkisini oluşturur.

**Döndürür:**
[IColorChange](../../com.aspose.slides/icolorchange) - Color change etkisi.
### createColorReplace() {#createColorReplace--}
```
public abstract IColorReplace createColorReplace()
```


Color replace etkisini oluşturur.

**Döndürür:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Color replace etkisi.
### createDuotone() {#createDuotone--}
```
public abstract IDuotone createDuotone()
```


Duotone etkisini oluşturur.

**Döndürür:**
[IDuotone](../../com.aspose.slides/iduotone) - Duotone etkisi.
### createFillOverlay() {#createFillOverlay--}
```
public abstract IFillOverlay createFillOverlay()
```


Fill overlay etkisini oluşturur.

**Döndürür:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Fill overlay etkisi.
### createGrayScale() {#createGrayScale--}
```
public abstract IGrayScale createGrayScale()
```


Gray scale etkisini oluşturur.

**Döndürür:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Gray scale etkisi.
### createHSL(float hue, float saturation, float luminance) {#createHSL-float-float-float-}
```
public abstract IHSL createHSL(float hue, float saturation, float luminance)
```


Hue Saturation Luminance etkisini oluşturur.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| hue | float | Hue. |
| saturation | float | Saturation. |
| luminance | float | Luminance. |

**Döndürür:**
[IHSL](../../com.aspose.slides/ihsl) - HSL etkisi.
### createLuminance(float brightness, float contrast) {#createLuminance-float-float-}
```
public abstract ILuminance createLuminance(float brightness, float contrast)
```


Luminance etkisini oluşturur.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| brightness | float | Parlaklık. |
| contrast | float | Kontrast. |

**Döndürür:**
[ILuminance](../../com.aspose.slides/iluminance) - Luminance etkisi.
### createTint(float hue, float amount) {#createTint-float-float-}
```
public abstract ITint createTint(float hue, float amount)
```


Tint etkisini oluşturur.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| hue | float | Hue. |
| amount | float | Miktar. |

**Döndürür:**
[ITint](../../com.aspose.slides/itint) - Tint etkisi.