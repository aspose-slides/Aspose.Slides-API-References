---
title: Section
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایش‌دهنده بخش اسلایدها.
type: docs
url: /fa/com.aspose.slides/section/
---
**ارث‌بری:**
java.lang.Object, com.aspose.slides.DomObject

**همه رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ISection](../../com.aspose.slides/isection)
```
public class Section extends DomObject<SectionCollection> implements ISection
```

نمایش‌دهنده بخش اسلایدها.
## متدها

| متد | توضیح |
| --- | --- |
| [getName()](#getName--) | نام بخش. |
| [setName(String value)](#setName-java.lang.String-) | نام بخش. |
| [getSectionId()](#getSectionId--) | شناسه بخش. |
| [getStartedFromSlide()](#getStartedFromSlide--) | اسلاید اول بخش را برمی‌گرداند. |
| [getSlidesListOfSection()](#getSlidesListOfSection--) | فهرست اسلایدهای بخش را برمی‌گرداند. |
### getName() {#getName--}
```
public final String getName()
```


نام بخش.

**بازمی‌گرداند:**
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

**بازمی‌گرداند:**
java.util.UUID
### getStartedFromSlide() {#getStartedFromSlide--}
```
public final ISlide getStartedFromSlide()
```


اسلاید اول بخش را برمی‌گرداند.

**بازمی‌گرداند:**
[ISlide](../../com.aspose.slides/islide)
### getSlidesListOfSection() {#getSlidesListOfSection--}
```
public final ISectionSlideCollection getSlidesListOfSection()
```


فهرست اسلایدهای بخش را برمی‌گرداند.

**بازمی‌گرداند:**
[ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection) - فهرست اسلایدها.