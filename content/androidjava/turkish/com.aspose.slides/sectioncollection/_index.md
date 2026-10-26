---
title: SectionCollection
second_title: Aspose.Slides Android için Java API Referansı
description: Bölümler koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/sectioncollection/
---
**Kalıtım:**
java.lang.Object, com.aspose.slides.DomObject

**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.ISectionCollection](../../com.aspose.slides/isectioncollection)
```
public final class SectionCollection extends DomObject<Presentation> implements ISectionCollection
```

Bölümler koleksiyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki öğeyi alır. |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | Belirli bir slayttan başlayan slayt bölümünü ekler. |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | Koleksiyonun sonuna boş bir bölüm ekler. |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | Koleksiyonda belirtilen konuma boş bir bölüm ekler. |
| [size()](#size--) | Koleksiyonda gerçekten bulunan öğe sayısını alır. |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | Koleksiyonda belirtilen bölümün dizinini döndürür. |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | Bölümü ve bölümdeki slaytları kaldırır. |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | Bölümü kaldırır. |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | Bölümü ve slaytlarını koleksiyondan belirtilen konuma taşır. |
| [clear()](#clear--) | Koleksiyon içindeki tüm bölümleri kaldırır. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Tüm koleksiyonu belirtilen diziye kopyalar. |
| [isSynchronized()](#isSynchronized--) | Koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını gösteren bir değer döndürür. |
| [getSyncRoot()](#getSyncRoot--) | Bir senkronizasyon kökü döndürür. |
| [iterator()](#iterator--) | Koleksiyon içinde yineleme yapan bir enumerator döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java iterator döndürür. |
### get_Item(int index) {#get-Item-int-}
```
public final ISection get_Item(int index)
```

Belirtilen indeksteki öğeyi alır. Yalnızca-okunur [ISection](../../com.aspose.slides/isection).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[ISection](../../com.aspose.slides/isection)
### addSection(String name, ISlide startedFromSlide) {#addSection-java.lang.String-com.aspose.slides.ISlide-}
```
public final ISection addSection(String name, ISlide startedFromSlide)
```

Belirli bir slayttan başlayan slayt bölümünü ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Bölümün adı |
| startedFromSlide | [ISlide](../../com.aspose.slides/islide) | Bölümün ilk slaytı |

**Döndürür:**
[ISection](../../com.aspose.slides/isection) - Eklenen bölüm.
### appendEmptySection(String name) {#appendEmptySection-java.lang.String-}
```
public final ISection appendEmptySection(String name)
```

Koleksiyonun sonuna boş bir bölüm ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Bölümün adı |

**Döndürür:**
[ISection](../../com.aspose.slides/isection) - Eklenen bölüm.
### addEmptySection(String name, int index) {#addEmptySection-java.lang.String-int-}
```
public final ISection addEmptySection(String name, int index)
```

Koleksiyonda belirtilen konuma boş bir bölüm ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Bölümün adı |
| index | int | Yeni bölümün dizini. |

**Döndürür:**
[ISection](../../com.aspose.slides/isection) - Eklenen bölüm.
### size() {#size--}
```
public final int size()
```

Koleksiyonda gerçekten bulunan öğe sayısını alır. Yalnızca-okunur int.

**Döndürür:**
int
### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public final int indexOf(ISection section)
```

Koleksiyonda belirtilen bölümün dizinini döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Bulunacak bölüm. |

**Döndürür:**
int - Bölümün dizini veya -1 eğer bölüm bu koleksiyona ait değil.
### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public final void removeSectionWithSlides(ISection section)
```

Bölümü ve bölümdeki slaytları kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Koleksiyondan kaldırılacak bölüm. |

### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public final void removeSection(ISection section)
```

Bölümü kaldırır. Bölümdeki slaytlar önceki bölüme birleştirilecektir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Koleksiyondan kaldırılacak bölüm. |

### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public final void reorderSectionWithSlides(ISection section, int index)
```

Bölümü ve slaytlarını koleksiyondan belirtilen konuma taşır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Taşınacak bölüm. |
| index | int | Hedef dizin. |

### clear() {#clear--}
```
public final void clear()
```

Koleksiyon içindeki tüm bölümleri kaldırır.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Tüm koleksiyonu belirtilen diziye kopyalar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Hedef dizi |
| index | int | Hedef dizideki indeks. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını gösteren bir değer döndürür. Yalnızca-okunur boolean.

**Döndürür:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Bir senkronizasyon kökü döndürür. Yalnızca-okunur Object.

**Döndürür:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISection> iterator()
```

Koleksiyon içinde yineleme yapan bir enumerator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - Koleksiyon içinde yineleme yapılabilen bir IGenericEnumerator.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISection> iteratorJava()
```

Tüm koleksiyon için bir java iterator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - Tüm koleksiyon için bir java.util.Iterator.