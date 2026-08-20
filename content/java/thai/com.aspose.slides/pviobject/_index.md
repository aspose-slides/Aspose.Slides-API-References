---
title: PVIObject
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: ห่อหุ้มโครงสร้างพื้นฐานการให้บริการพื้นฐานสำหรับวัตถุที่อาจเป็นหัวข้อของการสืบทอดค่าคุณสมบัติ
type: docs
url: /th/com.aspose.slides/pviobject/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
com.aspose.slides.IPVIObject, [com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public abstract class PVIObject implements IPVIObject, ISlideComponent
```

ห่อหุ้มโครงสร้างพื้นฐานการให้บริการพื้นฐานสำหรับวัตถุที่อาจเป็นหัวข้อของการสืบทอดค่าคุณสมบัติ
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getParent_ISlideComponent()](#getParent-ISlideComponent--) |  |
| [getSlide()](#getSlide--) |  |
| [getPresentation()](#getPresentation--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | เปรียบเทียบกับอ็อบเจ็กต์ที่ระบุ |
| [hashCode()](#hashCode--) | ส่งคืนค่าแฮชโค้ด |
### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```


คืนค่า Parent_Immediate object. แบบอ่านอย่างเดียว IDOMObject.

**คืนค่า:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public long getVersion()
```


เวอร์ชัน. แบบอ่านอย่างเดียว long.

**คืนค่า:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public IPresentationComponent getParent_IPresentationComponent()
```


คืนค่า parent IPresentationComponent. แบบอ่านอย่างเดียว [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

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


คืนค่า base slide. แบบอ่านอย่างเดียว [IBaseSlide](../../com.aspose.slides/ibaseslide).

**คืนค่า:**
[BaseSlide](../../com.aspose.slides/baseslide)
### getPresentation() {#getPresentation--}
```
public Presentation getPresentation()
```


คืนค่า presentation. แบบอ่านอย่างเดียว [IPresentation](../../com.aspose.slides/ipresentation).

**คืนค่า:**
[Presentation](../../com.aspose.slides/presentation)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


เปรียบเทียบกับอ็อบเจ็กต์ที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| obj | java.lang.Object | อ็อบเจ็กต์ที่ต้องการเปรียบเทียบ |

**คืนค่า:**
boolean - True หากวัตถุเท่ากัน, มิฉะนั้น false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


ส่งคืนค่าแฮชโค้ด

**คืนค่า:**
int - ค่ารหัสแฮช