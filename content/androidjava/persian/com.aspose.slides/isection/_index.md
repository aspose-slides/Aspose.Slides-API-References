---
title: ISection
second_title: Aspose.Slides for Android via Java API Reference
description: نمایانگر بخش اسلایدها.
type: docs
url: /fa/com.aspose.slides/isection/
---```
public interface ISection
```

نمایانگر بخش اسلایدها.
## متدها

| متد | توضیح |
| --- | --- |
| [getName()](#getName--) | نام بخش. |
| [setName(String value)](#setName-java.lang.String-) | نام بخش. |
| [getSectionId()](#getSectionId--) | شناسه بخش. |
| [getStartedFromSlide()](#getStartedFromSlide--) | اسلاید اول بخش را برمی‌گرداند. |
| [getSlidesListOfSection()](#getSlidesListOfSection--) | لیست اسلایدهای موجود در بخش را برمی‌گرداند. |
### getName() {#getName--}
```
public abstract String getName()
```

نام بخش.

**بازگشت:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

نام بخش.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |
### getSectionId() {#getSectionId--}
```
public abstract UUID getSectionId()
```

شناسه بخش.

**بازگشت:**
java.util.UUID
### getStartedFromSlide() {#getStartedFromSlide--}
```
public abstract ISlide getStartedFromSlide()
```

اسلاید اول بخش را برمی‌گرداند.

**بازگشت:**
[ISlide](../../com.aspose.slides/islide)
### getSlidesListOfSection() {#getSlidesListOfSection--}
```
public abstract ISectionSlideCollection getSlidesListOfSection()
```

لیست اسلایدهای موجود در بخش را برمی‌گرداند.

**بازگشت:**
[ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection) - لیست اسلایدها [ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection)