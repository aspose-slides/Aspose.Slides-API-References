---
title: Picture
second_title: Aspose.Slides สำหรับ Java API Reference
description: แสดงภาพในงานนำเสนอ.
type: docs
url: /th/com.aspose.slides/picture/
---
**การสืบทอด:**
java.lang.Object

**ส่วนต่อประสานที่ทำทั้งหมด:**
com.aspose.slides.IPVIObject, [com.aspose.slides.ISlidesPicture](../../com.aspose.slides/islidespicture)
```
public final class Picture implements IPVIObject, ISlidesPicture
```

แสดงภาพในงานนำเสนอ.
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getImage()](#getImage--) | คืนค่าหรือกำหนดภาพที่ฝังไว้. |
| [setImage(IPPImage value)](#setImage-com.aspose.slides.IPPImage-) | คืนค่าหรือกำหนดภาพที่ฝังไว้. |
| [getLinkPathLong()](#getLinkPathLong--) | คืนค่าหรือกำหนด URL ของภาพที่เชื่อมโยง. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | คืนค่าหรือกำหนด URL ของภาพที่เชื่อมโยง. |
| [getImageTransform()](#getImageTransform--) | คืนค่าคอลเลคชันของเอฟเฟกต์การแปลงภาพ. |
| [getPresentation()](#getPresentation--) | คืนค่างานนำเสนอ. |
| [equals(Object obj)](#equals-java.lang.Object-) | เปรียบเทียบกับอ็อบเจ็กต์ที่กำหนด. |
| [hashCode()](#hashCode--) | คืนค่าแฮช. |
| [getSlide()](#getSlide--) | คืนค่าสไลด์แม่ของภาพ. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

คืนค่าอ็อบเจ็กต์ Parent_Immediate. อ่านอย่างเดียว IDOMObject.

**คืนค่า:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```

เวอร์ชัน. อ่านอย่างเดียว long.

**คืนค่า:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

คืนค่าอ็อบเจ็กต์ IPresentationComponent พารents. อ่านอย่างเดียว [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**คืนค่า:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### getImage() {#getImage--}
```
public final IPPImage getImage()
```

คืนค่าหรือกำหนดภาพที่ฝังไว้. อ่าน/เขียน [IPPImage](../../com.aspose.slides/ippimage).

**คืนค่า:**
[IPPImage](../../com.aspose.slides/ippimage)
### setImage(IPPImage value) {#setImage-com.aspose.slides.IPPImage-}
```
public final void setImage(IPPImage value)
```

คืนค่าหรือกำหนดภาพที่ฝังไว้. อ่าน/เขียน [IPPImage](../../com.aspose.slides/ippimage).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |
### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

คืนค่าหรือกำหนด URL ของภาพที่เชื่อมโยง. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

คืนค่าหรือกำหนด URL ของภาพที่เชื่อมโยง. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |
### getImageTransform() {#getImageTransform--}
```
public final IImageTransformOperationCollection getImageTransform()
```

คืนค่าคอลเลคชันของเอฟเฟกต์การแปลงภาพ. อ่านอย่างเดียว [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection).

**คืนค่า:**
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

คืนค่างานนำเสนอ. อ่านอย่างเดียว [IPresentation](../../com.aspose.slides/ipresentation).

**คืนค่า:**
[IPresentation](../../com.aspose.slides/ipresentation)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

เปรียบเทียบกับอ็อบเจ็กต์ที่กำหนด.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| obj | java.lang.Object | อ็อบเจ็กต์เพื่อเปรียบเทียบ. |

**คืนค่า:**
boolean - True if objects are equal, otherwise false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

คืนค่าแฮช.

**คืนค่า:**
int - Hash.
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

คืนค่าสไลด์แม่ของภาพ. อ่านอย่างเดียว [IBaseSlide](../../com.aspose.slides/ibaseslide).

**คืนค่า:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)