---
title: Section
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل قسمًا من الشرائح.
type: docs
url: /ar/com.aspose.slides/section/
---
**الوراثة:**  
java.lang.Object, com.aspose.slides.DomObject

**جميع الواجهات المُطبقة:**  
[com.aspose.slides.ISection](../../com.aspose.slides/isection)  
```
public class Section extends DomObject<SectionCollection> implements ISection
```

يمثل قسمًا من الشرائح.  
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getName()](#getName--) | اسم القسم. |
| [setName(String value)](#setName-java.lang.String-) | اسم القسم. |
| [getSectionId()](#getSectionId--) | معرّف القسم. |
| [getStartedFromSlide()](#getStartedFromSlide--) | إرجاع الشريحة الأولى في القسم. |
| [getSlidesListOfSection()](#getSlidesListOfSection--) | إرجاع قائمة الشرائح في القسم. |
### getName() {#getName--}
```
public final String getName()
```

اسم القسم.

**الإرجاع:**  
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

اسم القسم.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getSectionId() {#getSectionId--}
```
public final UUID getSectionId()
```

معرّف القسم.

**الإرجاع:**  
java.util.UUID
### getStartedFromSlide() {#getStartedFromSlide--}
```
public final ISlide getStartedFromSlide()
```

إرجاع الشريحة الأولى في القسم.

**الإرجاع:**  
[ISlide](../../com.aspose.slides/islide)
### getSlidesListOfSection() {#getSlidesListOfSection--}
```
public final ISectionSlideCollection getSlidesListOfSection()
```

إرجاع قائمة الشرائح في القسم.

**الإرجاع:**  
[ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection) - قائمة الشرائح.