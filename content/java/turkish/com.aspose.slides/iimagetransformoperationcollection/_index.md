---
title: IImageTransformOperationCollection
second_title: Aspose.Slides for Java API Referansı
description: Bir görüntüye uygulanan efektlerin bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/iimagetransformoperationcollection/
---
**Uygulanan Tüm Arabirimler:**
com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public interface IImageTransformOperationCollection extends System.Collections.Generic.IGenericCollection<IImageTransformOperation>
```

Bir görüntüye uygulanan efekt koleksiyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Koleksiyondan indeksiyle bir [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) döndürür. |
| [removeAt(int index)](#removeAt-int-) | Belirtilen indeksteki bir görüntü efektini koleksiyondan kaldırır. |
| [addAlphaBiLevelEffect(float threshold)](#addAlphaBiLevelEffect-float-) | Yeni Alpha Bi-Level efektini koleksiyonun sonuna ekler. |
| [addAlphaCeilingEffect()](#addAlphaCeilingEffect--) | Yeni Alpha Ceiling efektini koleksiyonun sonuna ekler. |
| [addAlphaFloorEffect()](#addAlphaFloorEffect--) | Yeni Alpha Floor efektini koleksiyonun sonuna ekler. |
| [addAlphaInverseEffect()](#addAlphaInverseEffect--) | Yeni Alpha Inverse efektini koleksiyonun sonuna ekler. |
| [addAlphaModulateEffect()](#addAlphaModulateEffect--) | Yeni Alpha Modulate efektini koleksiyonun sonuna ekler. |
| [addAlphaModulateFixedEffect(float amount)](#addAlphaModulateFixedEffect-float-) | Yeni Alpha Modulate Fixed efektini koleksiyonun sonuna ekler. |
| [addAlphaReplaceEffect(float alpha)](#addAlphaReplaceEffect-float-) | Yeni Alpha Replace efektini koleksiyonun sonuna ekler. |
| [addBiLevelEffect(float threshold)](#addBiLevelEffect-float-) | Yeni Bi-Level (siyah/beyaz) efektini koleksiyonun sonuna ekler. |
| [addBlurEffect(double radius, boolean grow)](#addBlurEffect-double-boolean-) | Yeni Blur efektini koleksiyonun sonuna ekler. |
| [addColorChangeEffect()](#addColorChangeEffect--) | Yeni Color Change efektini koleksiyonun sonuna ekler. |
| [addColorReplaceEffect()](#addColorReplaceEffect--) | Yeni Color Replacement efektini koleksiyonun sonuna ekler. |
| [addDuotoneEffect()](#addDuotoneEffect--) | Yeni Duotone efektini koleksiyonun sonuna ekler. |
| [addFillOverlayEffect()](#addFillOverlayEffect--) | Yeni Fill Overlay efektini koleksiyonun sonuna ekler. |
| [addGrayScaleEffect()](#addGrayScaleEffect--) | Yeni Gray Scale efektini koleksiyonun sonuna ekler. |
| [addHSLEffect(float hue, float saturation, float luminance)](#addHSLEffect-float-float-float-) | Yeni Hue/Saturation/Luminance efektini koleksiyonun sonuna ekler. |
| [addLuminanceEffect(float brightness, float contrast)](#addLuminanceEffect-float-float-) | Yeni Luminance efektini koleksiyonun sonuna ekler. |
| [addTintEffect(float hue, float amount)](#addTintEffect-float-float-) | Yeni Tint efektini koleksiyonun sonuna ekler. |
| [addBrightnessContrastEffect(float brightness, float contrast)](#addBrightnessContrastEffect-float-float-) | Yeni BrightnessContrast efektini koleksiyonun sonuna ekler. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IImageTransformOperation get_Item(int index)
```

Koleksiyondan indeksiyle bir [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Öğenin indeksi. |

**Döndürür:**
[IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) - [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) nesnesi.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Belirtilen indeksteki bir görüntü efektini koleksiyondan kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Silinmesi gereken bir görüntü efektinin indeksi. |
### addAlphaBiLevelEffect(float threshold) {#addAlphaBiLevelEffect-float-}
```
public abstract IAlphaBiLevel addAlphaBiLevelEffect(float threshold)
```

Yeni Alpha Bi-Level efektini koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| threshold | float | Alpha Bi-Level efekti için eşik değeri. |

**Döndürür:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Koleksiyondaki yeni görüntü efektinin indeks değeri.
### addAlphaCeilingEffect() {#addAlphaCeilingEffect--}
```
public abstract IAlphaCeiling addAlphaCeilingEffect()
```

Yeni Alpha Ceiling efektini koleksiyonun sonuna ekler.

**Döndürür:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Koleksiyondaki yeni görüntü efektinin indeks değeri.
### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public abstract IAlphaFloor addAlphaFloorEffect()
```

Yeni Alpha Floor efektini koleksiyonun sonuna ekler.

**Döndürür:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Koleksiyondaki yeni görüntü efektinin indeks değeri.
### addAlphaInverseEffect() {#addAlphaInverseEffect--}
```
public abstract IAlphaInverse addAlphaInverseEffect()
```

Yeni Alpha Inverse efektini koleksiyonun sonuna ekler.

**Döndürür:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Koleksiyondaki yeni görüntü efektinin indeks değeri.
### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public abstract IAlphaModulate addAlphaModulateEffect()
```

Yeni Alpha Modulate efektini koleksiyonun sonuna ekler.

**Döndürür:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Koleksiyondaki yeni görüntü efektinin indeks değeri.
### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public abstract IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
```

Yeni Alpha Modulate Fixed efektini koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| amount | float | Alfa değerini ölçeklemek için yüzde miktarı. |

**Döndürür:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Koleksiyondaki yeni görüntü efektinin indeks değeri.
### addAlphaReplaceEffect(float alpha) {#addAlphaReplaceEffect-float-}
```
public abstract IAlphaReplace addAlphaReplaceEffect(float alpha)
```

Yeni Alpha Replace efektini koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| alpha | float | Yeni opaklık değeri. |

**Döndürür:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Koleksiyondaki yeni görüntü efektinin indeks değeri.
### addBiLevelEffect(float threshold) {#addBiLevelEffect-float-}
```
public abstract IBiLevel addBiLevelEffect(float threshold)
```

Yeni Bi-Level (siyah/beyaz) efektini koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| threshold | float | Bi-Level efekti için aydınlık eşiği. Eşiğe eşit ya da büyük değerler beyaz, eşiğin altındaki değerler siyah olur. |

**Döndürür:**
[IBiLevel](../../com.aspose.slides/ibilevel) - Koleksiyondaki yeni görüntü efektinin indeks değeri.
### addBlurEffect(double radius, boolean grow) {#addBlurEffect-double-boolean-}
```
public abstract IBlur addBlurEffect(double radius, boolean grow)
```

Yeni Blur efektini koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| radius | double | Bulanıklık yarıçapı. |
| grow | boolean | Bulanıklaştırma sonucunda nesnenin sınırlarının genişletilip genişletilmeyeceğini belirler. true ise sınırlar genişletilir, false ise genişletilmez. |

**Döndürür:**
[IBlur](../../com.aspose.slides/iblur) - Koleksiyondaki yeni görüntü efektinin indeks değeri.
### addColorChangeEffect() {#addColorChangeEffect--}
```
public abstract IColorChange addColorChangeEffect()
```

Yeni Color Change efektini koleksiyonun sonuna ekler.

**Döndürür:**
[IColorChange](../../com.aspose.slides/icolorchange) - Koleksiyondaki yeni görüntü efektinin indeks değeri.
### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public abstract IColorReplace addColorReplaceEffect()
```

Yeni Color Replacement efektini koleksiyonun sonuna ekler.

**Döndürür:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Koleksiyondaki yeni görüntü efektinin indeks değeri.
### addDuotoneEffect() {#addDuotoneEffect--}
```
public abstract IDuotone addDuotoneEffect()
```

Yeni Duotone efektini koleksiyonun sonuna ekler.

**Döndürür:**
[IDuotone](../../com.aspose.slides/iduotone) - Koleksiyondaki yeni görüntü efektinin indeks değeri.
### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public abstract IFillOverlay addFillOverlayEffect()
```

Yeni Fill Overlay efektini koleksiyonun sonuna ekler.

**Döndürür:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Koleksiyondaki yeni görüntü efektinin indeks değeri.
### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public abstract IGrayScale addGrayScaleEffect()
```

Yeni Gray Scale efektini koleksiyonun sonuna ekler.

**Döndürür:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Koleksiyondaki yeni görüntü efektinin indeks değeri.
### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public abstract IHSL addHSLEffect(float hue, float saturation, float luminance)
```

Yeni Hue/Saturation/Luminance efektini koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| hue | float | Tonun ayarlandığı derece sayısı. |
| saturation | float | Doygunluğun ayarlandığı yüzde. |
| luminance | float | Parlaklığın ayarlandığı yüzde. |

**Döndürür:**
[IHSL](../../com.aspose.slides/ihsl) - Koleksiyondaki yeni görüntü efektinin indeks değeri.
### addLuminanceEffect(float brightness, float contrast) {#addLuminanceEffect-float-float-}
```
public abstract ILuminance addLuminanceEffect(float brightness, float contrast)
```

Yeni Luminance efektini koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brightness | float | Parlaklığı değiştirme yüzdesi. |
| contrast | float | Kontrastı değiştirme yüzdesi. |

**Döndürür:**
[ILuminance](../../com.aspose.slides/iluminance) - Koleksiyondaki yeni görüntü efektinin indeks değeri.
### addTintEffect(float hue, float amount) {#addTintEffect-float-float-}
```
public abstract ITint addTintEffect(float hue, float amount)
```

Yeni Tint efektini koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| hue | float | Ton yönündeki renk tonu. |
| amount | float | Renk değerinin ne kadar kaydırılacağı. |

**Döndürür:**
[ITint](../../com.aspose.slides/itint) - Koleksiyondaki yeni görüntü efektinin indeks değeri.
### addBrightnessContrastEffect(float brightness, float contrast) {#addBrightnessContrastEffect-float-float-}
```
public abstract IBrightnessContrast addBrightnessContrastEffect(float brightness, float contrast)
```

Yeni BrightnessContrast efektini koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brightness | float | Parlaklığı değiştirme yüzdesi. |
| contrast | float | Kontrastı değiştirme yüzdesi. |

**Döndürür:**
[IBrightnessContrast](../../com.aspose.slides/ibrightnesscontrast) - Koleksiyondaki yeni görüntü efektinin indeks değeri.