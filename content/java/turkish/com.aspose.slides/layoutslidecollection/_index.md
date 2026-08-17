---
title: LayoutSlideCollection
second_title: Aspose.Slides için Java API Referansı
description: Düzen slaytlarının bir koleksiyonu için temel sınıfı temsil eder.
type: docs
url: /tr/com.aspose.slides/layoutslidecollection/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection), com.aspose.slides.IDOMObject
```
public class LayoutSlideCollection implements ILayoutSlideCollection, IDOMObject
```

Düzen slaytlarının bir koleksiyonu için temel sınıfı temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [size()](#size--) | Koleksiyondaki düzen slaytlarının sayısını döndürür. |
| [get_Item(int index)](#get-Item-int-) | İndekse göre düzen slaytını döndürür. |
| [getByType(byte type)](#getByType-byte-) | Belirtilen türdeki ilk düzen slaytını döndürür. |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | Koleksiyondan bir düzeni kaldırır. |
| [removeUnused()](#removeUnused--) | Kullanılmayan düzen slaytlarını kaldırır (HasDependingSlides özelliği false olan düzen slaytları). |
| [iterator()](#iterator--) | Koleksiyon içinde gezinmek için bir enumerator döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java iterator döndürür. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Koleksiyondaki tüm öğeleri belirtilen diziye kopyalar. |
| [isSynchronized()](#isSynchronized--) | Koleksiyona erişimin senkronize (çok iş parçacıklı) olup olmadığını gösteren bir değer döndürür. |
| [getSyncRoot()](#getSyncRoot--) | Bir senkronizasyon kökü döndürür. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### size() {#size--}
```
public final int size()
```


Koleksiyondaki düzen slaytlarının sayısını döndürür. Salt-okunur int.

**Döndürür:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ILayoutSlide get_Item(int index)
```


İndekse göre düzen slaytını döndürür. Salt-okunur [LayoutSlide](../../com.aspose.slides/layoutslide).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### getByType(byte type) {#getByType-byte-}
```
public final ILayoutSlide getByType(byte type)
```


Belirtilen türdeki ilk düzen slaytını döndürür.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| type | byte | Bulunacak düzen slaytının türü. |

**Döndürür:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - [LayoutSlide](../../com.aspose.slides/layoutslide) belirtilen türde veya bulunamazsa null.
### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public final void remove(ILayoutSlide value)
```


Koleksiyondan bir düzeni kaldırır.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Koleksiyondan kaldırılacak düzen slaytı. |

--------------------

1) PptxEditException oluşumunu önlemek için önce düzenin HasDependingSlides özelliğini kontrol edin. 2) Kodu basitleştirmek için ayrıca [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) yöntemini kullanabilirsiniz. |
### removeUnused() {#removeUnused--}
```
public final void removeUnused()
```


Kullanılmayan düzen slaytlarını kaldırır (HasDependingSlides özelliği false olan düzen slaytları).

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ILayoutSlide> iterator()
```


Koleksiyon içinde gezinmek için bir enumerator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILayoutSlide> - Koleksiyon içinde gezinmek için kullanılabilen bir IGenericEnumerator.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ILayoutSlide> iteratorJava()
```


Tüm koleksiyon için bir java iterator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILayoutSlide> - Tüm koleksiyon için bir java.util.Iterator.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Koleksiyondaki tüm öğeleri belirtilen diziye kopyalar.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Hedef dizi. |
| index | int | Hedef dizideki başlangıç indeksi. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Koleksiyona erişimin senkronize (çok iş parçacıklı) olup olmadığını gösteren bir değer döndürür. Salt-okunur boolean.

**Döndürür:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Bir senkronizasyon kökü döndürür. Salt-okunur Object.

**Döndürür:**
java.lang.Object
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Parent_Immediate nesnesini döndürür. Salt-okunur IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject