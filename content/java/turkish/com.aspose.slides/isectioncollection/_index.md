---
title: ISectionCollection
second_title: Aspose.Slides for Java API Referansı
description: Bölümlerin bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/isectioncollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface ISectionCollection extends IGenericCollection<ISection>
```

Bölümlerin bir koleksiyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki öğeyi alır. |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | Belirli bir slayttan başlayan yeni bölüm ekler. |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | Koleksiyonun belirtilen konumuna boş bölüm ekler. |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | Bölümü ve bölümde bulunan slaytları kaldırır. |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | Bölümü kaldırır. |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | Bölümü ve slaytlarını koleksiyondan belirtilen konuma taşır. |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | Koleksiyonun sonuna boş bir bölüm ekler. |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | Belirtilen bölümün koleksiyondaki indeksini döndürür. |
| [clear()](#clear--) | Koleksiyondaki tüm bölümleri kaldırır. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISection get_Item(int index)
```


Belirtilen indeksteki öğeyi alır. Salt okunur [ISection](../../com.aspose.slides/isection).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[ISection](../../com.aspose.slides/isection)
### addSection(String name, ISlide startedFromSlide) {#addSection-java.lang.String-com.aspose.slides.ISlide-}
```
public abstract ISection addSection(String name, ISlide startedFromSlide)
```


Belirli bir slayttan başlayan yeni bölüm ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Bölümün adı |
| startedFromSlide | [ISlide](../../com.aspose.slides/islide) | Bölümün ilk slaytı |

**Döndürür:**
[ISection](../../com.aspose.slides/isection) - Eklenen bölüm.
### addEmptySection(String name, int index) {#addEmptySection-java.lang.String-int-}
```
public abstract ISection addEmptySection(String name, int index)
```


Koleksiyonun belirtilen konumuna boş bölüm ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Bölümün adı |
| index | int | Yeni bölümün indeksi. |

**Döndürür:**
[ISection](../../com.aspose.slides/isection) - Eklenen bölüm.
### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public abstract void removeSectionWithSlides(ISection section)
```


Bölümü ve bölümde bulunan slaytları kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Koleksiyondan kaldırılacak bölüm. |
### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public abstract void removeSection(ISection section)
```


Bölümü kaldırır. Bölümde bulunan slaytlar önceki bölüme birleştirilecektir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Koleksiyondan kaldırılacak bölüm. |
### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public abstract void reorderSectionWithSlides(ISection section, int index)
```


Bölümü ve slaytlarını koleksiyondan belirtilen konuma taşır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Taşınacak bölüm. |
| index | int | Hedef indeks. |
### appendEmptySection(String name) {#appendEmptySection-java.lang.String-}
```
public abstract ISection appendEmptySection(String name)
```


Koleksiyonun sonuna boş bir bölüm ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Bölümün adı |

**Döndürür:**
[ISection](../../com.aspose.slides/isection) - Eklenen bölüm.
### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public abstract int indexOf(ISection section)
```


Belirtilen bölümün koleksiyondaki indeksini döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Bulunacak bölüm. |

**Döndürür:**
int - Bir bölümün indeksi veya bölüm bu koleksiyona ait değilse -1.
### clear() {#clear--}
```
public abstract void clear()
```


Koleksiyondaki tüm bölümleri kaldırır.