---
title: ISection
second_title: Aspose.Slides for Android via Java API Reference
description: Mewakili bagian slide.
type: docs
url: /id/com.aspose.slides/isection/
---```
public interface ISection
```

Mewakili bagian slide.
## Metode

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Name of the section. |
| [setName(String value)](#setName-java.lang.String-) | Name of the section. |
| [getSectionId()](#getSectionId--) | Section Id. |
| [getStartedFromSlide()](#getStartedFromSlide--) | Returns first slide of the section. |
| [getSlidesListOfSection()](#getSlidesListOfSection--) | Returns list of slides in the section. |
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
[ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection) - List of slides [ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection)