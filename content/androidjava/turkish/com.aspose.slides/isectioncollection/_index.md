---
title: ISectionCollection
second_title: Aspose.Slides for Android için Java API Referansı
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
| [get_Item(int index)](#get-Item-int-) | Belirtilen dizindeki öğeyi alır. |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | Belirli bir slayttan başlayan yeni bölümü ekler. |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | Koleksiyonda belirtilen konuma boş bir bölüm ekler. |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | Bölümü ve içinde bulunan slaytları kaldırır. |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | Bölümü kaldırır. |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | Bölümü ve slaytlarını koleksiyondan belirtilen konuma taşır. |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | Koleksiyonun sonuna boş bir bölüm ekler. |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | Belirtilen bölümün koleksiyondaki dizinini döndürür. |
| [clear()](#clear--) | Koleksiyondaki tüm bölümleri kaldırır. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISection get_Item(int index)
```

Belirtilen dizindeki öğeyi alır. Yalnızca okunabilir [ISection](../../com.aspose.slides/isection).

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

Belirli bir slayttan başlayan yeni bölümü ekler.

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

Koleksiyonda belirtilen konuma boş bir bölüm ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Bölümün adı |
| index | int | Yeni bölümün dizini. |

**Döndürür:**
[ISection](../../com.aspose.slides/isection) - Eklenen bölüm.
### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public abstract void removeSectionWithSlides(ISection section)
```

Bölümü ve içinde bulunan slaytları kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Koleksiyondan kaldırılacak bölüm. |
### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public abstract void removeSection(ISection section)
```

Bölümü kaldırır. Bölümdeki slaytlar önceki bölüme birleştirilecektir.

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
| index | int | Hedef dizin. |
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

Belirtilen bölümün koleksiyondaki dizinini döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Bulunacak bölüm. |

**Döndürür:**
int - Bir bölümün dizini veya bölüm bu koleksiyonda değilse -1.
### clear() {#clear--}
```
public abstract void clear()
```

Koleksiyondaki tüm bölümleri kaldırır.