---
title: ISection
second_title: Aspose.Slides for Android via Java API Reference
description: Slaytların bir bölümünü temsil eder.
type: docs
url: /tr/com.aspose.slides/isection/
---```
public interface ISection
```

Slaytların bir bölümünü temsil eder.
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
public abstract String getName()
```

Bölümün adı.

**Döndürür:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Bölümün adı.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getSectionId() {#getSectionId--}
```
public abstract UUID getSectionId()
```

Bölüm Kimliği.

**Döndürür:**
java.util.UUID
### getStartedFromSlide() {#getStartedFromSlide--}
```
public abstract ISlide getStartedFromSlide()
```

Bölümün ilk slaytını döndürür.

**Döndürür:**
[ISlide](../../com.aspose.slides/islide)
### getSlidesListOfSection() {#getSlidesListOfSection--}
```
public abstract ISectionSlideCollection getSlidesListOfSection()
```

Bölümdeki slaytların listesini döndürür.

**Döndürür:**
[ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection) - Slaytların Listesi [ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection)