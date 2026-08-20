---
title: Section
second_title: Aspose.Slides สำหรับ Java API Reference
description: แสดงส่วนของสไลด์.
type: docs
url: /th/com.aspose.slides/section/
---
**การสืบทอด:**  
java.lang.Object, com.aspose.slides.DomObject

**อินเทอร์เฟซที่นำมาใช้ทั้งหมด:**  
[com.aspose.slides.ISection](../../com.aspose.slides/isection)  
```
public class Section extends DomObject<SectionCollection> implements ISection
```

แทนส่วนของสไลด์.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getName()](#getName--) | ชื่อของส่วน. |
| [setName(String value)](#setName-java.lang.String-) | ชื่อของส่วน. |
| [getSectionId()](#getSectionId--) | รหัสส่วน. |
| [getStartedFromSlide()](#getStartedFromSlide--) | คืนสไลด์แรกของส่วน. |
| [getSlidesListOfSection()](#getSlidesListOfSection--) | คืนรายการสไลด์ในส่วน. |
### getName() {#getName--}
```
public final String getName()
```

ชื่อของส่วน.

**คืนค่า:**  
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

รหัสส่วน.

**คืนค่า:**  
java.util.UUID
### getStartedFromSlide() {#getStartedFromSlide--}
```
public final ISlide getStartedFromSlide()
```

คืนสไลด์แรกของส่วน.

**คืนค่า:**  
[ISlide](../../com.aspose.slides/islide)
### getSlidesListOfSection() {#getSlidesListOfSection--}
```
public final ISectionSlideCollection getSlidesListOfSection()
```

คืนรายการสไลด์ในส่วน.

**คืนค่า:**  
[ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection) - รายการสไลด์.