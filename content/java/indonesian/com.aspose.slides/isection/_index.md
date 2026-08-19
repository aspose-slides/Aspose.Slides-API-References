---
title: ISection
second_title: Aspose.Slides for Java API Reference
description: Represents section of slides.
type: docs
url: /id/com.aspose.slides/isection/
---```
public interface ISection
```

Mewakili bagian slide.
## Metode

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Nama bagian. |
| [setName(String value)](#setName-java.lang.String-) | Nama bagian. |
| [getSectionId()](#getSectionId--) | Id Bagian. |
| [getStartedFromSlide()](#getStartedFromSlide--) | Mengembalikan slide pertama dari bagian. |
| [getSlidesListOfSection()](#getSlidesListOfSection--) | Mengembalikan daftar slide dalam bagian. |
### getName() {#getName--}
```
public abstract String getName()
```

Nama bagian.

**Mengembalikan:**  
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Nama bagian.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getSectionId() {#getSectionId--}
```
public abstract UUID getSectionId()
```

Id Bagian.

**Mengembalikan:**  
java.util.UUID
### getStartedFromSlide() {#getStartedFromSlide--}
```
public abstract ISlide getStartedFromSlide()
```

Mengembalikan slide pertama dari bagian.

**Mengembalikan:**  
[ISlide](../../com.aspose.slides/islide)
### getSlidesListOfSection() {#getSlidesListOfSection--}
```
public abstract ISectionSlideCollection getSlidesListOfSection()
```

Mengembalikan daftar slide dalam bagian.

**Mengembalikan:**  
[ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection) - Daftar slide [ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection)