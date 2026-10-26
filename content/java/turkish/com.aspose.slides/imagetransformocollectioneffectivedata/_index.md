---
title: ImageTransformOCollectionEffectiveData
second_title: Aspose.Slides for Java API Referansı
description: Etkili görüntü dönüşüm efektlerinin salt okunur bir koleksiyonunu temsil eden değiştirilemez nesne.
type: docs
url: /tr/com.aspose.slides/imagetransformocollectioneffectivedata/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arayüzler:**
com.aspose.slides.IEffectiveData, [com.aspose.slides.IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata)
```
public class ImageTransformOCollectionEffectiveData implements IEffectiveData, IImageTransformOCollectionEffectiveData
```

Değiştirilemez nesne, etkili görüntü dönüşüm efektlerinin salt okunur bir koleksiyonunu temsil eder.

--------------------

Ad IImageTransformOperationCollectionEffectiveData, COM isim uzunluğu 39 karakteri aşamayacağı için IImageTransformOCollectionEffectiveData olarak kısaltıldı.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ImageTransformOCollectionEffectiveData()](#ImageTransformOCollectionEffectiveData--) |  |
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [size()](#size--) | Bir koleksiyondaki görüntü efektlerinin sayısını döndürür. |
| [get_Item(int index)](#get-Item-int-) | İndekse göre öğeyi döndürür. |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen nesnenin mevcut nesneye eşit olup olmadığını belirler. |
| [hashCode()](#hashCode--) | Belirli bir tür için hash işlevi olarak hizmet verir; hash tabloları gibi veri yapılarında ve hash algoritmalarında kullanılmaya uygundur. |
| [iterator()](#iterator--) | Koleksiyon içinde yineleme yapan bir enumeratörü döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java iterator'ü döndürür. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Koleksiyondaki tüm öğeleri belirtilen diziye kopyalar. |
| [isSynchronized()](#isSynchronized--) | Koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını gösteren bir değer döndürür. |
| [getSyncRoot()](#getSyncRoot--) | Bir senkronizasyon kökü döndürür. |
### ImageTransformOCollectionEffectiveData() {#ImageTransformOCollectionEffectiveData--}
```
public ImageTransformOCollectionEffectiveData()
```


### size() {#size--}
```
public final int size()
```


Bir koleksiyondaki görüntü efektlerinin sayısını döndürür. Salt okunur int.

**Döndürür:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IEffectEffectiveData get_Item(int index)
```


İndekse göre öğeyi döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Öğenin indeksi. |

**Döndürür:**
[IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata) - [IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata) nesnesi.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Belirtilen nesnenin mevcut nesneye eşit olup olmadığını belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Mevcut nesneyle karşılaştırılacak nesne. |

**Döndürür:**
boolean - belirli nesne mevcut nesneye eşitse true; aksi takdirde false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Belirli bir tür için hash işlevi olarak hizmet verir; hash tabloları gibi veri yapılarında ve hash algoritmalarında kullanılmaya uygundur.

**Döndürür:**
int - Mevcut nesne için bir hash kodu.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectEffectiveData> iterator()
```


Koleksiyon içinde yineleme yapan bir enumeratörü döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectEffectiveData> - Koleksiyon içinde yineleme yapmak için kullanılabilecek bir IGenericEnumerator.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectEffectiveData> iteratorJava()
```


Tüm koleksiyon için bir java iterator'ü döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectEffectiveData> - Tüm koleksiyon için bir java.util.Iterator.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Koleksiyondaki tüm öğeleri belirtilen diziye kopyalar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Doldurulacak dizi. |
| index | int | Hedef dizideki başlangıç konumu. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını gösteren bir değer döndürür. Salt okunur boolean.

**Döndürür:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Bir senkronizasyon kökü döndürür. Salt okunur Object.

**Döndürür:**
java.lang.Object