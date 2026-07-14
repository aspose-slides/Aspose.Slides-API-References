---
title: ISection
second_title: Aspose.Slides for Android via Java API Reference
description: เป็นตัวแทนของส่วนของสไลด์.
type: docs
url: /th/com.aspose.slides/isection/
---```
public interface ISection
```

เป็นตัวแทนของส่วนของสไลด์.
## วิธีการ

| วิธี | คำอธิบาย |
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

ชื่อของส่วน.

**คืนค่า:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

ชื่อของส่วน.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |
### getSectionId() {#getSectionId--}
```
public abstract UUID getSectionId()
```

รหัสส่วน.

**คืนค่า:**
java.util.UUID
### getStartedFromSlide() {#getStartedFromSlide--}
```
public abstract ISlide getStartedFromSlide()
```

คืนค่าสไลด์แรกของส่วน.

**คืนค่า:**
[ISlide](../../com.aspose.slides/islide)
### getSlidesListOfSection() {#getSlidesListOfSection--}
```
public abstract ISectionSlideCollection getSlidesListOfSection()
```

คืนค่ารายการสไลด์ในส่วน.

**คืนค่า:**
[ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection) - รายการสไลด์ [ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection)