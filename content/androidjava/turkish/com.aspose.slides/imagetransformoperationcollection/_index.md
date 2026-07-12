---
title: ImageTransformOperationCollection
second_title: Aspose.Slides for Android için Java API Referansı
description: Bir görüntüye uygulanmış efektlerin koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/imagetransformoperationcollection/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)
```
public final class ImageTransformOperationCollection extends PVIObject implements IImageTransformOperationCollection
```

Bir görüntüye uygulanmış efektlerin bir koleksiyonunu temsil eder.
## Yöntemler

| Metod | Açıklama |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [get_Item(int index)](#get-Item-int-) | Koleksiyondan indeksine göre bir [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation) döndürür. |
| [removeAt(int index)](#removeAt-int-) | Bir koleksiyondaki belirli indisteki görüntü efektini kaldırır. |
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
| [size()](#size--) | Bir koleksiyondaki görüntü efektlerinin sayısını döndürür. |
| [isReadOnly()](#isReadOnly--) | [IGenericCollection](../../com.aspose.slides/igenericcollection)'in salt-okunur olup olmadığını gösteren bir değeri alır. |
| [addItem(IImageTransformOperation operation)](#addItem-com.aspose.slides.IImageTransformOperation-) | Yeni görüntü efektini koleksiyonun sonuna ekler. |
| [clear()](#clear--) | Bir koleksiyondaki tüm görüntü efektlerini kaldırır. |
| [containsItem(IImageTransformOperation item)](#containsItem-com.aspose.slides.IImageTransformOperation-) | [IGenericCollection](../../com.aspose.slides/igenericcollection)'nin belirli bir değeri içerip içermediğini belirler. |
| [copyToTArray(IImageTransformOperation[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IImageTransformOperation---int-) | [IGenericCollection](../../com.aspose.slides/igenericcollection) elemanlarını belirli bir dizi indeksinden başlayarak bir Array'e kopyalar. |
| [removeItem(IImageTransformOperation item)](#removeItem-com.aspose.slides.IImageTransformOperation-) | [IGenericCollection](../../com.aspose.slides/igenericcollection) içerisinden belirli bir nesnenin ilk örneğini kaldırır. |
| [iterator()](#iterator--) | Koleksiyonu yineleyen bir enumerator döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java iterator döndürür. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Sürüm. Salt-okunur long.

**Döndürür:**
long

### get_Item(int index) {#get-Item-int-}
```
public final IImageTransformOperation get_Item(int index)
```

Koleksiyondan indeksine göre bir [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation) döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Öğenin indeksi. |

**Döndürür:**
[IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) - [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) nesnesi.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Belirtilen indeksteki görüntü efektini koleksiyondan kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Silinmesi gereken görüntü efektinin indeksi. |

### addAlphaBiLevelEffect(float threshold) {#addAlphaBiLevelEffect-float-}
```
public final IAlphaBiLevel addAlphaBiLevelEffect(float threshold)
```

Yeni Alpha Bi-Level efektini koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| threshold | float | Alpha bi-level efekti için eşik değeri. |

**Döndürür:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Yeni görüntü efektinin koleksiyondaki indeksi.

### addAlphaCeilingEffect() {#addAlphaCeilingEffect--}
```
public final IAlphaCeiling addAlphaCeilingEffect()
```

Yeni Alpha Ceiling efektini koleksiyonun sonuna ekler.

**Döndürür:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Yeni görüntü efektinin koleksiyondaki indeksi.

### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public final IAlphaFloor addAlphaFloorEffect()
```

Yeni Alpha Floor efektini koleksiyonun sonuna ekler.

**Döndürür:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Yeni görüntü efektinin koleksiyondaki indeksi.

### addAlphaInverseEffect() {#addAlphaInverseEffect--}
```
public final IAlphaInverse addAlphaInverseEffect()
```

Yeni Alpha Inverse efektini koleksiyonun sonuna ekler.

**Döndürür:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Yeni görüntü efektinin koleksiyondaki indeksi.

### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public final IAlphaModulate addAlphaModulateEffect()
```

Yeni Alpha Modulate efektini koleksiyonun sonuna ekler.

**Döndürür:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Yeni görüntü efektinin koleksiyondaki indeksi.

### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public final IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
```

Yeni Alpha Modulate Fixed efektini koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| amount | float | Alpha'yı ölçeklendirmek için yüzde miktarı. |

**Döndürür:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Yeni görüntü efektinin koleksiyondaki indeksi.

### addAlphaReplaceEffect(float alpha) {#addAlphaReplaceEffect-float-}
```
public final IAlphaReplace addAlphaReplaceEffect(float alpha)
```

Yeni Alpha Replace efektini koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| alpha | float | Yeni opaklık değeri. |

**Döndürür:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Yeni görüntü efektinin koleksiyondaki indeksi.

### addBiLevelEffect(float threshold) {#addBiLevelEffect-float-}
```
public final IBiLevel addBiLevelEffect(float threshold)
```

Yeni Bi-Level (siyah/beyaz) efektini koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| threshold | float | Bi-Level efekti için parlaklık eşiği. Eşiğe eşit veya büyük değerler beyaz, daha düşük değerler siyah olur. |

**Döndürür:**
[IBiLevel](../../com.aspose.slides/ibilevel) - Yeni görüntü efektinin koleksiyondaki indeksi.

### addBlurEffect(double radius, boolean grow) {#addBlurEffect-double-boolean-}
```
public final IBlur addBlurEffect(double radius, boolean grow)
```

Yeni Blur efektini koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| radius | double | Bulanıklık yarıçapı. |
| grow | boolean | Bulanıklık sonucunda nesnenin sınırlarının büyütülüp büyütülmeyeceğini belirler. true ise sınırlar büyür, false ise büyümez. |

**Döndürür:**
[IBlur](../../com.aspose.slides/iblur) - Yeni görüntü efektinin koleksiyondaki indeksi.

### addColorChangeEffect() {#addColorChangeEffect--}
```
public final IColorChange addColorChangeEffect()
```

Yeni Color Change efektini koleksiyonun sonuna ekler.

**Döndürür:**
[IColorChange](../../com.aspose.slides/icolorchange) - Yeni görüntü efektinin koleksiyondaki indeksi.

### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public final IColorReplace addColorReplaceEffect()
```

Yeni Color Replacement efektini koleksiyonun sonuna ekler.

**Döndürür:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Yeni görüntü efektinin koleksiyondaki indeksi.

### addDuotoneEffect() {#addDuotoneEffect--}
```
public final IDuotone addDuotoneEffect()
```

Yeni Duotone efektini koleksiyonun sonuna ekler.

**Döndürür:**
[IDuotone](../../com.aspose.slides/iduotone) - Yeni görüntü efektinin koleksiyondaki indeksi.

### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public final IFillOverlay addFillOverlayEffect()
```

Yeni Fill Overlay efektini koleksiyonun sonuna ekler.

**Döndürür:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Yeni görüntü efektinin koleksiyondaki indeksi.

### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public final IGrayScale addGrayScaleEffect()
```

Yeni Gray Scale efektini koleksiyonun sonuna ekler.

**Döndürür:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Yeni görüntü efektinin koleksiyondaki indeksi.

### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public final IHSL addHSLEffect(float hue, float saturation, float luminance)
```

Yeni Hue/Saturation/Luminance efektini koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| hue | float | Tonun ayarlandığı derece sayısı. |
| saturation | float | Doygunluğun ayarlandığı yüzde. |
| luminance | float | Parlaklığın ayarlandığı yüzde. |

**Döndürür:**
[IHSL](../../com.aspose.slides/ihsl) - Yeni görüntü efektinin koleksiyondaki indeksi.

### addLuminanceEffect(float brightness, float contrast) {#addLuminanceEffect-float-float-}
```
public final ILuminance addLuminanceEffect(float brightness, float contrast)
```

Yeni Luminance efektini koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brightness | float | Parlaklığı değiştirme yüzdesi. |
| contrast | float | Kontrastı değiştirme yüzdesi. |

**Döndürür:**
[ILuminance](../../com.aspose.slides/iluminance) - Yeni görüntü efektinin koleksiyondaki indeksi.

### addTintEffect(float hue, float amount) {#addTintEffect-float-float-}
```
public final ITint addTintEffect(float hue, float amount)
```

Yeni Tint efektini koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| hue | float | Tonlama yapılacak hue değeri. |
| amount | float | Renk değerinin ne kadar kaydırılacağını belirtir. |

**Döndürür:**
[ITint](../../com.aspose.slides/itint) - Yeni görüntü efektinin koleksiyondaki indeksi.

### addBrightnessContrastEffect(float brightness, float contrast) {#addBrightnessContrastEffect-float-float-}
```
public final IBrightnessContrast addBrightnessContrastEffect(float brightness, float contrast)
```

Yeni BrightnessContrast efektini koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brightness | float | Parlaklığı değiştirme yüzdesi. |
| contrast | float | Kontrastı değiştirme yüzdesi. |

**Döndürür:**
[IBrightnessContrast](../../com.aspose.slides/ibrightnesscontrast) - Yeni görüntü efektinin koleksiyondaki indeksi.

### size() {#size--}
```
public final int size()
```

Bir koleksiyondaki görüntü efektlerinin sayısını döndürür. Salt-okunur int.

**Döndürür:**
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

[IGenericCollection](../../com.aspose.slides/igenericcollection)'in salt-okunur olup olmadığını gösteren bir değeri alır. Salt-okunur boolean.

**Döndürür:**
boolean - [IGenericCollection](../../com.aspose.slides/igenericcollection) salt-okunur ise true; aksi takdirde false.

### addItem(IImageTransformOperation operation) {#addItem-com.aspose.slides.IImageTransformOperation-}
```
public final void addItem(IImageTransformOperation operation)
```

Yeni görüntü efektini koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| operation | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | Koleksiyonun sonuna eklenecek görüntü efekti. |

### clear() {#clear--}
```
public final void clear()
```

Bir koleksiyondaki tüm görüntü efektlerini kaldırır.

### containsItem(IImageTransformOperation item) {#containsItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean containsItem(IImageTransformOperation item)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection)'nin belirli bir değeri içerip içermediğini belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | [IGenericCollection](../../com.aspose.slides/igenericcollection) içinde aranacak nesne. |

**Döndürür:**
boolean - [IGenericCollection](../../com.aspose.slides/igenericcollection) içinde öğe bulunursa true; aksi takdirde false.

### copyToTArray(IImageTransformOperation[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IImageTransformOperation---int-}
```
public final void copyToTArray(IImageTransformOperation[] array, int arrayIndex)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) elemanlarını belirli bir dizi indeksinden başlayarak bir Array'e kopyalar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| array | [IImageTransformOperation\[\]](../../com.aspose.slides/iimagetransformoperation) | [IGenericCollection](../../com.aspose.slides/igenericcollection)'dan kopyalanan elemanların hedefi olan tek boyutlu Array. Dizi sıfır tabanlı indekslemeye sahip olmalıdır. |
| arrayIndex | int | Kopyalamanın başlayacağı dizi indeksi (sıfır tabanlı). |

### removeItem(IImageTransformOperation item) {#removeItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean removeItem(IImageTransformOperation item)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) içerisinden belirli bir nesnenin ilk örneğini kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | [IGenericCollection](../../com.aspose.slides/igenericcollection)'dan kaldırılacak nesne. |

**Döndürür:**
boolean - [IGenericCollection](../../com.aspose.slides/igenericcollection) içinde öğe başarıyla kaldırıldıysa true; aksi takdirde false. Bu yöntem, öğe orijinal [IGenericCollection](../../com.aspose.slides/igenericcollection)'de bulunamazsa da false döndürür.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iterator()
```

Koleksiyonu yineleyen bir enumerator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - Koleksiyonu yinelemek için kullanılabilecek bir IGenericEnumerator.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iteratorJava()
```

Tüm koleksiyon için bir java iterator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - Tüm koleksiyon için bir java.util.Iterator.