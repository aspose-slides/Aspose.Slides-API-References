---
title: Section
second_title: مرجع API Aspose.Slides للـ Java
description: يمثل قسمًا من الشرائح.
type: docs
url: /ar/com.aspose.slides/section/
---
**الوراثة:**
java.lang.Object, com.aspose.slides.DomObject

**جميع الواجهات المنفذة:**
[com.aspose.slides.ISection](../../com.aspose.slides/isection)
```
public class Section extends DomObject<SectionCollection> implements ISection
```

يمثل قسمًا من الشرائح.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getName()](#getName--) | اسم القسم. |
| [setName(String value)](#setName-java.lang.String-) | اسم القسم. |
| [getSectionId()](#getSectionId--) | معرف القسم. |
| [getStartedFromSlide()](#getStartedFromSlide--) | تُرجع الشريحة الأولى في القسم. |
| [getSlidesListOfSection()](#getSlidesListOfSection--) | تُرجع قائمة الشرائح في القسم. |
### getName() {#getName--}
```
public final String getName()
```


اسم القسم.

**إرجاع:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


اسم القسم.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getSectionId() {#getSectionId--}
```
public final UUID getSectionId()
```


معرف القسم.

**إرجاع:**
java.util.UUID
### getStartedFromSlide() {#getStartedFromSlide--}
```
public final ISlide getStartedFromSlide()
```


تُرجع الشريحة الأولى في القسم.

**إرجاع:**
[ISlide](../../com.aspose.slides/islide)
### getSlidesListOfSection() {#getSlidesListOfSection--}
```
public final ISectionSlideCollection getSlidesListOfSection()
```


تُرجع قائمة الشرائح في القسم.

**إرجاع:**
[ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection) - List of slides.