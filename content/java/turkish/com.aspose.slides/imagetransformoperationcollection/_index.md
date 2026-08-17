---
title: ImageTransformOperationCollection
second_title: Aspose.Slides için Java API Referansı
description: Bir görüntüye uygulanan etkilerin koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/imagetransformoperationcollection/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)
```
public final class ImageTransformOperationCollection extends PVIObject implements IImageTransformOperationCollection
```

Bir görüntüye uygulanmış etkilerin koleksiyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [get_Item(int index)](#get-Item-int-) | Koleksiyondan indeksine göre bir [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation) döndürür. |
| [removeAt(int index)](#removeAt-int-) | Belirtilen indeksteki bir görüntü etkisini koleksiyondan kaldırır. |
| [addAlphaBiLevelEffect(float threshold)](#addAlphaBiLevelEffect-float-) | Yeni Alpha İkili Düzey etkisini koleksiyonun sonuna ekler. |
| [addAlphaCeilingEffect()](#addAlphaCeilingEffect--) | Yeni Alpha Tavan etkisini koleksiyonun sonuna ekler. |
| [addAlphaFloorEffect()](#addAlphaFloorEffect--) | Yeni Alpha Tabana etkisini koleksiyonun sonuna ekler. |
| [addAlphaInverseEffect()](#addAlphaInverseEffect--) | Yeni Alpha Ters etkisini koleksiyonun sonuna ekler. |
| [addAlphaModulateEffect()](#addAlphaModulateEffect--) | Yeni Alpha Modülasyon etkisini koleksiyonun sonuna ekler. |
| [addAlphaModulateFixedEffect(float amount)](#addAlphaModulateFixedEffect-float-) | Yeni Alpha Sabit Modülasyon etkisini koleksiyonun sonuna ekler. |
| [addAlphaReplaceEffect(float alpha)](#addAlphaReplaceEffect-float-) | Yeni Alpha Değiştir etkisini koleksiyonun sonuna ekler. |
| [addBiLevelEffect(float threshold)](#addBiLevelEffect-float-) | Yeni İkili Düzey (siyah/beyaz) etkisini koleksiyonun sonuna ekler. |
| [addBlurEffect(double radius, boolean grow)](#addBlurEffect-double-boolean-) | Yeni Bulanıklaştırma etkisini koleksiyonun sonuna ekler. |
| [addColorChangeEffect()](#addColorChangeEffect--) | Yeni Renk Değiştirme etkisini koleksiyonun sonuna ekler. |
| [addColorReplaceEffect()](#addColorReplaceEffect--) | Yeni Renk Değiştirme (yerine koyma) etkisini koleksiyonun sonuna ekler. |
| [addDuotoneEffect()](#addDuotoneEffect--) | Yeni Duotone etkisini koleksiyonun sonuna ekler. |
| [addFillOverlayEffect()](#addFillOverlayEffect--) | Yeni Doldurma Örtüsü (Fill Overlay) etkisini koleksiyonun sonuna ekler. |
| [addGrayScaleEffect()](#addGrayScaleEffect--) | Yeni Gri Ölçek etkisini koleksiyonun sonuna ekler. |
| [addHSLEffect(float hue, float saturation, float luminance)](#addHSLEffect-float-float-float-) | Yeni Renk Tonu/Doygunluk/Parlaklık etkisini koleksiyonun sonuna ekler. |
| [addLuminanceEffect(float brightness, float contrast)](#addLuminanceEffect-float-float-) | Yeni Parlaklık etkisini koleksiyonun sonuna ekler. |
| [addTintEffect(float hue, float amount)](#addTintEffect-float-float-) | Yeni Ton (Tint) etkisini koleksiyonun sonuna ekler. |
| [addBrightnessContrastEffect(float brightness, float contrast)](#addBrightnessContrastEffect-float-float-) | Yeni Parlaklık/Kontrast etkisini koleksiyonun sonuna ekler. |
| [size()](#size--) | Koleksiyondaki görüntü etkilerinin sayısını döndürür. |
| [isReadOnly()](#isReadOnly--) | [IGenericCollection](../../com.aspose.slides/igenericcollection)'in salt okunur olup olmadığını belirten bir değeri alır. |
| [addItem(IImageTransformOperation operation)](#addItem-com.aspose.slides.IImageTransformOperation-) | Yeni görüntü etkisini koleksiyonun sonuna ekler. |
| [clear()](#clear--) | Koleksiyondan tüm görüntü etkilerini kaldırır. |
| [containsItem(IImageTransformOperation item)](#containsItem-com.aspose.slides.IImageTransformOperation-) | [IGenericCollection](../../com.aspose.slides/igenericcollection)'nin belirli bir değeri içerip içermediğini belirler. |
| [copyToTArray(IImageTransformOperation[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IImageTransformOperation---int-) | [IGenericCollection](../../com.aspose.slides/igenericcollection) öğelerini belirli bir dizi indeksinden başlayarak bir Array'e kopyalar. |
| [removeItem(IImageTransformOperation item)](#removeItem-com.aspose.slides.IImageTransformOperation-) | Belirli bir nesnenin ilk oluşumunu [IGenericCollection](../../com.aspose.slides/igenericcollection)'den kaldırır. |
| [iterator()](#iterator--) | Koleksiyonu yineleyen bir dizinleyici (enumerator) döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java yineleyicisi döndürür. |

### getVersion() {#getVersion--}
```
public long getVersion()
```


Versiyon. Salt okunur long.

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
| index | int | Elemanın indeksi. |

**Döndürür:**
[IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) - [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) nesnesi.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Belirtilen indeksteki bir görüntü etkisini koleksiyondan kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Silinmesi gereken görüntü etkisinin indeksi. |

### addAlphaBiLevelEffect(float threshold) {#addAlphaBiLevelEffect-float-}
```
public final IAlphaBiLevel addAlphaBiLevelEffect(float threshold)
```


Yeni Alpha İkili Düzey etkisini koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| threshold | float | Alpha ikili düzey etkisi için eşik değeri. |

**Döndürür:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Koleksiyondaki yeni görüntü etkisinin indeksi.
### addAlphaCeilingEffect() {#addAlphaCeilingEffect--}
```
public final IAlphaCeiling addAlphaCeilingEffect()
```


Yeni Alpha Tavan etkisini koleksiyonun sonuna ekler.

**Döndürür:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Koleksiyondaki yeni görüntü etkisinin indeksi.
### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public final IAlphaFloor addAlphaFloorEffect()
```


Yeni Alpha Tabana etkisini koleksiyonun sonuna ekler.

**Döndürür:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Koleksiyondaki yeni görüntü etkisinin indeksi.
### addAlphaInverseEffect() {#addAlphaInverseEffect--}
```
public final IAlphaInverse addAlphaInverseEffect()
```


Yeni Alpha Ters etkisini koleksiyonun sonuna ekler.

**Döndürür:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Koleksiyondaki yeni görüntü etkisinin indeksi.
### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public final IAlphaModulate addAlphaModulateEffect()
```


Yeni Alpha Modülasyon etkisini koleksiyonun sonuna ekler.

**Döndürür:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Koleksiyondaki yeni görüntü etkisinin indeksi.
### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public final IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
```


Yeni Alpha Sabit Modülasyon etkisini koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| amount | float | Alpha'yı ölçeklemek için yüzde miktarı. |

**Döndürür:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Koleksiyondaki yeni görüntü etkisinin indeksi.
### addAlphaReplaceEffect(float alpha) {#addAlphaReplaceEffect-float-}
```
public final IAlphaReplace addAlphaReplaceEffect(float alpha)
```


Yeni Alpha Değiştir etkisini koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| alpha | float | Yeni opaklık değeri. |

**Döndürür:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Koleksiyondaki yeni görüntü etkisinin indeksi.
### addBiLevelEffect(float threshold) {#addBiLevelEffect-float-}
```
public final IBiLevel addBiLevelEffect(float threshold)
```


Yeni İkili Düzey (siyah/beyaz) etkisini koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| threshold | float | İkili Düzey etkisi için parlaklık eşiği. Eşik değerine eşit veya büyük değerler beyaza, daha düşük değerler siyaha ayarlanır. |

**Döndürür:**
[IBiLevel](../../com.aspose.slides/ibilevel) - Koleksiyondaki yeni görüntü etkisinin indeksi.
### addBlurEffect(double radius, boolean grow) {#addBlurEffect-double-boolean-}
```
public final IBlur addBlurEffect(double radius, boolean grow)
```


Yeni Bulanıklaştırma etkisini koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| radius | double | Bulanıklaştırma yarıçapı. |
| grow | boolean | Nesnenin sınırlarının bulanıklaştırma sonucunda büyütülüp büyütülmeyeceğini belirler. True ise sınırlar büyütülür, false ise büyütülmez. |

**Döndürür:**
[IBlur](../../com.aspose.slides/iblur) - Koleksiyondaki yeni görüntü etkisinin indeksi.
### addColorChangeEffect() {#addColorChangeEffect--}
```
public final IColorChange addColorChangeEffect()
```


Yeni Renk Değiştirme etkisini koleksiyonun sonuna ekler.

**Döndürür:**
[IColorChange](../../com.aspose.slides/icolorchange) - Koleksiyondaki yeni görüntü etkisinin indeksi.
### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public final IColorReplace addColorReplaceEffect()
```


Yeni Renk Değiştirme (yerine koyma) etkisini koleksiyonun sonuna ekler.

**Döndürür:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Koleksiyondaki yeni görüntü etkisinin indeksi.
### addDuotoneEffect() {#addDuotoneEffect--}
```
public final IDuotone addDuotoneEffect()
```


Yeni Duotone etkisini koleksiyonun sonuna ekler.

**Döndürür:**
[IDuotone](../../com.aspose.slides/iduotone) - Koleksiyondaki yeni görüntü etkisinin indeksi.
### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public final IFillOverlay addFillOverlayEffect()
```


Yeni Doldurma Örtüsü (Fill Overlay) etkisini koleksiyonun sonuna ekler.

**Döndürür:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Koleksiyondaki yeni görüntü etkisinin indeksi.
### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public final IGrayScale addGrayScaleEffect()
```


Yeni Gri Ölçek etkisini koleksiyonun sonuna ekler.

**Döndürür:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Koleksiyondaki yeni görüntü etkisinin indeksi.
### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public final IHSL addHSLEffect(float hue, float saturation, float luminance)
```


Yeni Renk Tonu/Doygunluk/Parlaklık (Hue/Saturation/Luminance) etkisini koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| hue | float | Tonun ayarlandığı derece sayısı. |
| saturation | float | Doygunluğun ayarlandığı yüzde. |
| luminance | float | Parlaklığın ayarlandığı yüzde. |

**Döndürür:**
[IHSL](../../com.aspose.slides/ihsl) - Koleksiyondaki yeni görüntü etkisinin indeksi.
### addLuminanceEffect(float brightness, float contrast) {#addLuminanceEffect-float-float-}
```
public final ILuminance addLuminanceEffect(float brightness, float contrast)
```


Yeni Parlaklık etkisini koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brightness | float | Parlaklığı değiştirme yüzdesi. |
| contrast | float | Kontrastı değiştirme yüzdesi. |

**Döndürür:**
[ILuminance](../../com.aspose.slides/iluminance) - Koleksiyondaki yeni görüntü etkisinin indeksi.
### addTintEffect(float hue, float amount) {#addTintEffect-float-float-}
```
public final ITint addTintEffect(float hue, float amount)
```


Yeni Ton (Tint) etkisini koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| hue | float | Tonun yöneldiği renk. |
| amount | float | Renk değerinin ne kadar kaydırılacağını belirler. |

**Döndürür:**
[ITint](../../com.aspose.slides/itint) - Koleksiyondaki yeni görüntü etkisinin indeksi.
### addBrightnessContrastEffect(float brightness, float contrast) {#addBrightnessContrastEffect-float-float-}
```
public final IBrightnessContrast addBrightnessContrastEffect(float brightness, float contrast)
```


Yeni Parlaklık/Kontrast etkisini koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brightness | float | Parlaklığı değiştirme yüzdesi. |
| contrast | float | Kontrastı değiştirme yüzdesi. |

**Döndürür:**
[IBrightnessContrast](../../com.aspose.slides/ibrightnesscontrast) - Koleksiyondaki yeni görüntü etkisinin indeksi.
### size() {#size--}
```
public final int size()
```


Koleksiyondaki görüntü etkilerinin sayısını döndürür. Salt okunur  int .

**Döndürür:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```


[IGenericCollection](../../com.aspose.slides/igenericcollection)'in salt okunur olup olmadığını alır. Salt okunur boolean.

**Döndürür:**
boolean - [IGenericCollection](../../com.aspose.slides/igenericcollection) salt okunur ise true; aksi takdirde false.
### addItem(IImageTransformOperation operation) {#addItem-com.aspose.slides.IImageTransformOperation-}
```
public final void addItem(IImageTransformOperation operation)
```


Yeni görüntü etkisini koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| operation | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | Koleksiyonun sonuna eklenecek görüntü etkisi. |

### clear() {#clear--}
```
public final void clear()
```


Koleksiyondan tüm görüntü etkilerini kaldırır.
### containsItem(IImageTransformOperation item) {#containsItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean containsItem(IImageTransformOperation item)
```


[IGenericCollection](../../com.aspose.slides/igenericcollection)'nin belirli bir değeri içerip içermediğini belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | [IGenericCollection](../../com.aspose.slides/igenericcollection) içinde bulunacak nesne. |

**Döndürür:**
boolean - öğe [IGenericCollection](../../com.aspose.slides/igenericcollection) içinde bulunursa true; aksi takdirde false.
### copyToTArray(IImageTransformOperation[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IImageTransformOperation---int-}
```
public final void copyToTArray(IImageTransformOperation[] array, int arrayIndex)
```


[IGenericCollection](../../com.aspose.slides/igenericcollection) öğelerini belirli bir dizi indeksinden başlayarak bir Array'e kopyalar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| array | [IImageTransformOperation\[\]](../../com.aspose.slides/iimagetransformoperation) | [IGenericCollection](../../com.aspose.slides/igenericcollection)'dan kopyalanan öğelerin hedefi olan tek boyutlu Array. Array sıfır tabanlı indekslemeye sahip olmalıdır. |
| arrayIndex | int | Kopyalamanın başlayacağı dizi içindeki sıfır tabanlı indeks. |

### removeItem(IImageTransformOperation item) {#removeItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean removeItem(IImageTransformOperation item)
```


[IGenericCollection](../../com.aspose.slides/igenericcollection)'den belirli bir nesnenin ilk oluşumunu kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | [IGenericCollection](../../com.aspose.slides/igenericcollection)'dan kaldırılacak nesne. |

**Döndürür:**
boolean - öğe [IGenericCollection](../../com.aspose.slides/igenericcollection)'den başarıyla kaldırıldıysa true; aksi takdirde false. Bu yöntem ayrıca öğe orijinal [IGenericCollection](../../com.aspose.slides/igenericcollection) içinde bulunamazsa false döner.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iterator()
```


Koleksiyonu yineleyen bir dizinleyici (enumerator) döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - Kullanılabilecek bir IGenericEnumerator.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iteratorJava()
```


Tüm koleksiyon için bir java yineleyicisi döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - Bir java.util.Iterator.