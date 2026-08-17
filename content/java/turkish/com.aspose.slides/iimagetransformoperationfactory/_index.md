---
title: IImageTransformOperationFactory
second_title: Aspose.Slides for Java API Reference
description: Görüntü efektlerinin örneklerini oluşturmayı sağlar
type: docs
url: /tr/com.aspose.slides/iimagetransformoperationfactory/
---```
public interface IImageTransformOperationFactory
```

Görüntü efektlerinin örneklerini oluşturmayı sağlar

--------------------

COM arayüzü için.
## Yöntemler

| Method | Description |
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
### createAlphaBiLevel(float threshold) {#createAlphaBiLevel-float-}
```
public abstract IAlphaBiLevel createAlphaBiLevel(float threshold)
```

Alpha BiLevel etkisi oluşturur.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| threshold | float | Eşik. |

**Dönüş:**  
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Alpha BiLevel etkisi.
### createAlphCeiling() {#createAlphCeiling--}
```
public abstract IAlphaCeiling createAlphCeiling()
```

Alpha Ceiling etkisi oluşturur.

**Dönüş:**  
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Alpha Ceiling etkisi.
### createAlphaFloor() {#createAlphaFloor--}
```
public abstract IAlphaFloor createAlphaFloor()
```

Alpha floor etkisi oluşturur.

**Dönüş:**  
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Alpha floor etkisi.
### createAlphaInverse() {#createAlphaInverse--}
```
public abstract IAlphaInverse createAlphaInverse()
```

Alpha inverse etkisi oluşturur.

**Dönüş:**  
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Alpha inverse etkisi.
### createAlphaModulate() {#createAlphaModulate--}
```
public abstract IAlphaModulate createAlphaModulate()
```

Alpha modulate etkisi oluşturur.

**Dönüş:**  
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Alpha modulate etkisi.
### createAlphaModulateFixed(float amount) {#createAlphaModulateFixed-float-}
```
public abstract IAlphaModulateFixed createAlphaModulateFixed(float amount)
```

Alpha modulate fixed etkisi oluşturur.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| amount | float | Miktar. |

**Dönüş:**  
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Alpha modulate fixed etkisi.
### createAlphaReplace(float alpha) {#createAlphaReplace-float-}
```
public abstract IAlphaReplace createAlphaReplace(float alpha)
```

Alpha replace etkisi oluşturur.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| alpha | float | Alpha |

**Dönüş:**  
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Alpha replace etkisi.
### createBiLevel(float threshold) {#createBiLevel-float-}
```
public abstract IBiLevel createBiLevel(float threshold)
```

BiLevel etkisi oluşturur.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| threshold | float | Eşik. |

**Dönüş:**  
[IBiLevel](../../com.aspose.slides/ibilevel) - BiLevel etkisi.
### createBlur(double radius, boolean grow) {#createBlur-double-boolean-}
```
public abstract IBlur createBlur(double radius, boolean grow)
```

Blur etkisi oluşturur.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| radius | double | Yarıçap. |
| grow | boolean | Büyüt. |

**Dönüş:**  
[IBlur](../../com.aspose.slides/iblur) - Blur etkisi.
### createColorChange() {#createColorChange--}
```
public abstract IColorChange createColorChange()
```

Color change etkisi oluşturur.

**Dönüş:**  
[IColorChange](../../com.aspose.slides/icolorchange) - Color change etkisi.
### createColorReplace() {#createColorReplace--}
```
public abstract IColorReplace createColorReplace()
```

Color replace etkisi oluşturur.

**Dönüş:**  
[IColorReplace](../../com.aspose.slides/icolorreplace) - Color replace etkisi.
### createDuotone() {#createDuotone--}
```
public abstract IDuotone createDuotone()
```

Duotone etkisi oluşturur.

**Dönüş:**  
[IDuotone](../../com.aspose.slides/iduotone) - Duotone etkisi.
### createFillOverlay() {#createFillOverlay--}
```
public abstract IFillOverlay createFillOverlay()
```

Fill overlay etkisi oluşturur.

**Dönüş:**  
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Fill overlay etkisi.
### createGrayScale() {#createGrayScale--}
```
public abstract IGrayScale createGrayScale()
```

Gray scale etkisi oluşturur.

**Dönüş:**  
[IGrayScale](../../com.aspose.slides/igrayscale) - Gray scale etkisi.
### createHSL(float hue, float saturation, float luminance) {#createHSL-float-float-float-}
```
public abstract IHSL createHSL(float hue, float saturation, float luminance)
```

Hue Saturation Luminance etkisi oluşturur.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| hue | float | Hue. |
| saturation | float | Saturation. |
| luminance | float | Luminance. |

**Dönüş:**  
[IHSL](../../com.aspose.slides/ihsl) - HSL etkisi.
### createLuminance(float brightness, float contrast) {#createLuminance-float-float-}
```
public abstract ILuminance createLuminance(float brightness, float contrast)
```

Luminance etkisi oluşturur.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| brightness | float | Parlaklık. |
| contrast | float | Kontrast. |

**Dönüş:**  
[ILuminance](../../com.aspose.slides/iluminance) - Luminance etkisi.
### createTint(float hue, float amount) {#createTint-float-float-}
```
public abstract ITint createTint(float hue, float amount)
```

Tint etkisi oluşturur.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| hue | float | Hue. |
| amount | float | Miktar. |

**Dönüş:**  
[ITint](../../com.aspose.slides/itint) - Tint etkisi.