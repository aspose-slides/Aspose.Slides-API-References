---
title: Section
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงส่วนของสไลด์.
type: docs
url: /th/com.aspose.slides/section/
---
**Inheritance:**  
สืบทอด:

java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**  
อินเทอร์เฟซที่นำมาใช้งานทั้งหมด:

[com.aspose.slides.ISection](../../com.aspose.slides/isection)
```
public class Section extends DomObject<SectionCollection> implements ISection
```

Represents section of slides.  
แสดงส่วนของสไลด์.

## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getName()](#getName--) | ชื่อของส่วน. |
| [setName(String value)](#setName-java.lang.String-) | ชื่อของส่วน. |
| [getSectionId()](#getSectionId--) | ไอดีของส่วน. |
| [getStartedFromSlide()](#getStartedFromSlide--) | คืนสไลด์แรกของส่วน. |
| [getSlidesListOfSection()](#getSlidesListOfSection--) | คืนรายการสไลด์ในส่วน. |
### getName() {#getName--}
```
public final String getName()
```


ชื่อของส่วน.

**Returns:**  
คืนค่า:
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


ชื่อของส่วน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getSectionId() {#getSectionId--}
```
public final UUID getSectionId()
```


ไอดีของส่วน.

**Returns:**  
คืนค่า:
java.util.UUID
### getStartedFromSlide() {#getStartedFromSlide--}
```
public final ISlide getStartedFromSlide()
```


คืนสไลด์แรกของส่วน.

**Returns:**  
คืนค่า:
[ISlide](../../com.aspose.slides/islide)
### getSlidesListOfSection() {#getSlidesListOfSection--}
```
public final ISectionSlideCollection getSlidesListOfSection()
```


คืนรายการสไลด์ในส่วน.

**Returns:**  
คืนค่า:
[ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection) - List of slides.