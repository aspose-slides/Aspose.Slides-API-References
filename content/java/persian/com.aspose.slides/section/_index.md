---
title: Section
second_title: مرجع API Aspose.Slides برای جاوا
description: بخش اسلایدها را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/section/
---
**وراثت:**
java.lang.Object, com.aspose.slides.DomObject

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ISection](../../com.aspose.slides/isection)
```
public class Section extends DomObject<SectionCollection> implements ISection
```

بخش اسلایدها را نشان می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [getName()](#getName--) | نام بخش. |
| [setName(String value)](#setName-java.lang.String-) | نام بخش. |
| [getSectionId()](#getSectionId--) | شناسه بخش. |
| [getStartedFromSlide()](#getStartedFromSlide--) | باز می‌گردد اولین اسلاید بخش. |
| [getSlidesListOfSection()](#getSlidesListOfSection--) | باز می‌گردد فهرست اسلایدهای بخش. |
### getName() {#getName--}
```
public final String getName()
```


نام بخش.

**باز می‌گردد:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


نام بخش.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getSectionId() {#getSectionId--}
```
public final UUID getSectionId()
```


شناسه بخش.

**باز می‌گردد:**
java.util.UUID
### getStartedFromSlide() {#getStartedFromSlide--}
```
public final ISlide getStartedFromSlide()
```


باز می‌گردد اولین اسلاید بخش.

**باز می‌گردد:**
[ISlide](../../com.aspose.slides/islide)
### getSlidesListOfSection() {#getSlidesListOfSection--}
```
public final ISectionSlideCollection getSlidesListOfSection()
```


باز می‌گردد فهرست اسلایدهای بخش.

**باز می‌گردد:**
[ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection) - فهرست اسلایدها.