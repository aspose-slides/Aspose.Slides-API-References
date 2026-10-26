---
title: SectionCollection
second_title: Aspose.Slides for Java API Referansı
description: Bölümlerin bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/sectioncollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.ISectionCollection](../../com.aspose.slides/isectioncollection)
```
public final class SectionCollection extends DomObject<Presentation> implements ISectionCollection
```

Bölümlerin bir koleksiyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksdeki öğeyi alır. |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | Belirli bir slayttan başlayan slayt bölümünü ekler. |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | Koleksiyonun sonuna boş bir bölüm ekler. |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | Koleksiyonun belirtilen konumuna boş bir bölüm ekler. |
| [size()](#size--) | Koleksiyonun gerçekte içerdiği öğe sayısını alır. |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | Koleksiyonda belirtilen bölümün indeksini döndürür. |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | Bölümü ve bölümdeki slaytları kaldırır. |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | Bölümü kaldırır. |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | Bölümü ve slaytlarını koleksiyondan belirtilen konuma taşır. |
| [clear()](#clear--) | Koleksiyondaki tüm bölümleri kaldırır. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Tüm koleksiyonu belirtilen diziye kopyalar. |
| [isSynchronized()](#isSynchronized--) | Koleksiyona erişimin senkronize (thread-safe) olup olmadığını gösteren bir değeri döndürür. |
| [getSyncRoot()](#getSyncRoot--) | Bir senkronizasyon kökü döndürür. |
| [iterator()](#iterator--) | Koleksiyonun üzerinden dolaşan bir enumerator döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java iterator döndürür. |
### get_Item(int index) {#get-Item-int-}
```
public final ISection get_Item(int index)
```


Belirtilen indeksdeki öğeyi alır. Salt okunur [ISection](../../com.aspose.slides/isection).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Dönüş Değeri:**
[ISection](../../com.aspose.slides/isection)
### addSection(String name, ISlide startedFromSlide) {#addSection-java.lang.String-com.aspose.slides.ISlide-}
```
public final ISection addSection(String name, ISlide startedFromSlide)
```


Belirli bir slayttan başlayan slayt bölümünü ekler.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Bölümün adı |
| startedFromSlide | [ISlide](../../com.aspose.slides/islide) | Bölümün ilk slaytı |

**Dönüş Değeri:**
[ISection](../../com.aspose.slides/isection) - Eklenen bölüm.
### appendEmptySection(String name) {#appendEmptySection-java.lang.String-}
```
public final ISection appendEmptySection(String name)
```


Koleksiyonun sonuna boş bir bölüm ekler.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Bölümün adı |

**Dönüş Değeri:**
[ISection](../../com.aspose.slides/isection) - Eklenen bölüm.
### addEmptySection(String name, int index) {#addEmptySection-java.lang.String-int-}
```
public final ISection addEmptySection(String name, int index)
```


Koleksiyonun belirtilen konumuna boş bir bölüm ekler.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Bölümün adı |
| index | int | Yeni bölümün indeksi. |

**Dönüş Değeri:**
[ISection](../../com.aspose.slides/isection) - Eklenen bölüm.
### size() {#size--}
```
public final int size()
```


Koleksiyonun gerçekte içerdiği öğe sayısını alır. Salt okunur int.

**Dönüş Değeri:**
int
### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public final int indexOf(ISection section)
```


Koleksiyonda belirtilen bölümün indeksini döndürür.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Bulunacak bölüm. |

**Dönüş Değeri:**
int - Bölümün indeksi veya bölüm bu koleksiyona ait değilse -1.
### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public final void removeSectionWithSlides(ISection section)
```


Bölümü ve bölümdeki slaytları kaldırır.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Koleksiyondan kaldırılacak bölüm. |

### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public final void removeSection(ISection section)
```


Bölümü kaldırır. Bölümdeki slaytlar önceki bölüme birleştirilecektir.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Koleksiyondan kaldırılacak bölüm. |

### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public final void reorderSectionWithSlides(ISection section, int index)
```


Bölümü ve slaytlarını koleksiyondan belirtilen konuma taşır.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Taşınacak bölüm. |
| index | int | Hedef indeks. |

### clear() {#clear--}
```
public final void clear()
```


Koleksiyondaki tüm bölümleri kaldırır.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Tüm koleksiyonu belirtilen diziye kopyalar.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Hedef dizi |
| index | int | Hedef dizideki indeks. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Koleksiyona erişimin senkronize (thread-safe) olup olmadığını gösteren bir değeri döndürür. Salt okunur boolean.

**Dönüş Değeri:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Bir senkronizasyon kökü döndürür. Salt okunur Object.

**Dönüş Değeri:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISection> iterator()
```


Koleksiyonun üzerinden dolaşan bir enumerator döndürür.

**Dönüş Değeri:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - Koleksiyonun üzerinden dolaşmak için kullanılabilen bir IGenericEnumerator.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISection> iteratorJava()
```


Tüm koleksiyon için bir java iterator döndürür.

**Dönüş Değeri:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - Tüm koleksiyon için bir java.util.Iterator.