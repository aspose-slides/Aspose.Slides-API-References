---
title: Section
second_title: Java API Referansı aracılığıyla Android için Aspose.Slides
description: Slayt bölümünü temsil eder.
type: docs
url: /tr/com.aspose.slides/section/
---
**Kalıtım:**
java.lang.Object, com.aspose.slides.DomObject

**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.ISection](../../com.aspose.slides/isection)
```
public class Section extends DomObject<SectionCollection> implements ISection
```

Slayt bölümünü temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getName()](#getName--) | Bölümün adı. |
| [setName(String value)](#setName-java.lang.String-) | Bölümün adı. |
| [getSectionId()](#getSectionId--) | Bölüm Kimliği. |
| [getStartedFromSlide()](#getStartedFromSlide--) | Bölümün ilk slaytını döndürür. |
| [getSlidesListOfSection()](#getSlidesListOfSection--) | Bölümdeki slaytların listesini döndürür. |
### getName() {#getName--}
```
public final String getName()
```


Bölümün adı.

**Döndürür:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Bölümün adı.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getSectionId() {#getSectionId--}
```
public final UUID getSectionId()
```


Bölüm Kimliği.

**Döndürür:**
java.util.UUID
### getStartedFromSlide() {#getStartedFromSlide--}
```
public final ISlide getStartedFromSlide()
```


Bölümün ilk slaytını döndürür.

**Döndürür:**
[ISlide](../../com.aspose.slides/islide)
### getSlidesListOfSection() {#getSlidesListOfSection--}
```
public final ISectionSlideCollection getSlidesListOfSection()
```


Bölümdeki slaytların listesini döndürür.

**Döndürür:**
[ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection) - Slaytların listesi.