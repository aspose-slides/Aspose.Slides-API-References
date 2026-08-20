---
title: ISection
second_title: Aspose.Slides for Java API Reference
description: แสดงส่วนของสไลด์.
type: docs
url: /th/com.aspose.slides/isection/
---```
public interface ISection
```

แสดงส่วนของสไลด์.
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getName()](#getName--) | ชื่อของส่วน. |
| [setName(String value)](#setName-java.lang.String-) | ชื่อของส่วน. |
| [getSectionId()](#getSectionId--) | รหัสส่วน. |
| [getStartedFromSlide()](#getStartedFromSlide--) | ส่งกลับสไลด์แรกของส่วน. |
| [getSlidesListOfSection()](#getSlidesListOfSection--) | ส่งกลับรายการสไลด์ในส่วน. |
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
| พารามิเตอร์ | ประเภท | คำอธิบาย |
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


ส่งกลับสไลด์แรกของส่วน.

**คืนค่า:**
[ISlide](../../com.aspose.slides/islide)
### getSlidesListOfSection() {#getSlidesListOfSection--}
```
public abstract ISectionSlideCollection getSlidesListOfSection()
```


ส่งกลับรายการสไลด์ในส่วน.

**คืนค่า:**
[ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection) - รายการสไลด์ [ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection)