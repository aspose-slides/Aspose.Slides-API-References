---
title: ISection
second_title: Aspose.Slides for Android via Java API Reference
description: Represents section of slides.
type: docs
url: /vi/com.aspose.slides/isection/
---```
public interface ISection
```

Biểu diễn phần của các slide.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getName()](#getName--) | Tên của phần. |
| [setName(String value)](#setName-java.lang.String-) | Tên của phần. |
| [getSectionId()](#getSectionId--) | Id của phần. |
| [getStartedFromSlide()](#getStartedFromSlide--) | Trả về slide đầu tiên của phần. |
| [getSlidesListOfSection()](#getSlidesListOfSection--) | Trả về danh sách các slide trong phần. |
### getName() {#getName--}
```
public abstract String getName()
```

Tên của phần.

**Trả về:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Tên của phần.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |
### getSectionId() {#getSectionId--}
```
public abstract UUID getSectionId()
```

Id của phần.

**Trả về:**
java.util.UUID
### getStartedFromSlide() {#getStartedFromSlide--}
```
public abstract ISlide getStartedFromSlide()
```

Trả về slide đầu tiên của phần.

**Trả về:**
[ISlide](../../com.aspose.slides/islide)
### getSlidesListOfSection() {#getSlidesListOfSection--}
```
public abstract ISectionSlideCollection getSlidesListOfSection()
```

Trả về danh sách các slide trong phần.

**Trả về:**
[ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection) - Danh sách các slide [ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection)