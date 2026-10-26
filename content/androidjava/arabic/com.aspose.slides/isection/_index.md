---
title: ISection
second_title: Aspose.Slides for Android via Java API Reference
description: Represents section of slides.
type: docs
url: /ar/com.aspose.slides/isection/
---```
public interface ISection
```

يمثل قسمًا من الشرائح.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getName()](#getName--) | اسم القسم. |
| [setName(String value)](#setName-java.lang.String-) | اسم القسم. |
| [getSectionId()](#getSectionId--) | معرف القسم. |
| [getStartedFromSlide()](#getStartedFromSlide--) | يعيد الشريحة الأولى في القسم. |
| [getSlidesListOfSection()](#getSlidesListOfSection--) | يعيد قائمة الشرائح في القسم. |
### getName() {#getName--}
```
public abstract String getName()
```


اسم القسم.

**الإرجاع:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


اسم القسم.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getSectionId() {#getSectionId--}
```
public abstract UUID getSectionId()
```


معرف القسم.

**الإرجاع:**
java.util.UUID
### getStartedFromSlide() {#getStartedFromSlide--}
```
public abstract ISlide getStartedFromSlide()
```


يعيد الشريحة الأولى في القسم.

**الإرجاع:**
[ISlide](../../com.aspose.slides/islide)
### getSlidesListOfSection() {#getSlidesListOfSection--}
```
public abstract ISectionSlideCollection getSlidesListOfSection()
```


يعيد قائمة الشرائح في القسم.

**الإرجاع:**
[ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection) - قائمة الشرائح [ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection)