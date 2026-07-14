---
title: PVIObject
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: บรรจุโครงสร้างพื้นฐานของบริการพื้นฐานสำหรับอ็อบเจกต์ที่อาจเป็นหัวข้อของการสืบทอดค่าคุณสมบัติ
type: docs
url: /th/com.aspose.slides/pviobject/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ถูกนำไปใช้ทั้งหมด:**
com.aspose.slides.IPVIObject, [com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public abstract class PVIObject implements IPVIObject, ISlideComponent
```

บรรจุโครงสร้างพื้นฐานของบริการพื้นฐานสำหรับอ็อบเจกต์ที่อาจเป็นหัวข้อของการสืบทอดค่าคุณสมบัติ.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getParent_ISlideComponent()](#getParent-ISlideComponent--) |  |
| [getSlide()](#getSlide--) |  |
| [getPresentation()](#getPresentation--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Compares with specified object. |
| [hashCode()](#hashCode--) | Returns hash code. |
### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

คืนค่าอ็อบเจกต์ Parent_Immediate. อ่านอย่างเดียว IDOMObject.

**คืนค่า:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public long getVersion()
```

เวอร์ชัน. อ่านอย่างเดียว long.

**คืนค่า:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public IPresentationComponent getParent_IPresentationComponent()
```

คืนค่า parent IPresentationComponent. อ่านอย่างเดียว [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**คืนค่า:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### getParent_ISlideComponent() {#getParent-ISlideComponent--}
```
public ISlideComponent getParent_ISlideComponent()
```

**คืนค่า:**
[ISlideComponent](../../com.aspose.slides/islidecomponent)
### getSlide() {#getSlide--}
```
public BaseSlide getSlide()
```

คืนค่า base slide. อ่านอย่างเดียว [IBaseSlide](../../com.aspose.slides/ibaseslide).

**คืนค่า:**
[BaseSlide](../../com.aspose.slides/baseslide)
### getPresentation() {#getPresentation--}
```
public Presentation getPresentation()
```

คืนค่า presentation. อ่านอย่างเดียว [IPresentation](../../com.aspose.slides/ipresentation).

**คืนค่า:**
[Presentation](../../com.aspose.slides/presentation)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

เปรียบเทียบกับอ็อบเจกต์ที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| obj | java.lang.Object | อ็อบเจกต์ที่จะเปรียบเทียบ |

**คืนค่า:**
boolean - true หากอ็อบเจกต์เท่ากัน, มิฉะนั้น false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

คืนค่าแฮชโค้ด.

**คืนค่า:**
int - แฮชโค้ด.