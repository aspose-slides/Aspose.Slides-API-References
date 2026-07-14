---
title: ISlidesPicture
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงภาพในงานนำเสนอ
type: docs
url: /th/com.aspose.slides/islidespicture/
---
**อินเทอร์เฟซทั้งหมดที่ทำการใช้งาน:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ISlidesPicture extends ISlideComponent
```

แสดงภาพในงานนำเสนอ.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getImage()](#getImage--) | คืนค่า หรือ ตั้งค่าภาพที่ฝังไว้. |
| [setImage(IPPImage value)](#setImage-com.aspose.slides.IPPImage-) | คืนค่า หรือ ตั้งค่าภาพที่ฝังไว้. |
| [getLinkPathLong()](#getLinkPathLong--) | คืนค่า หรือ ตั้งค่า URL ของภาพที่เชื่อมโยง. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | คืนค่า หรือ ตั้งค่า URL ของภาพที่เชื่อมโยง. |
| [getImageTransform()](#getImageTransform--) | คืนค่าชุดของเอฟเฟกต์การแปลงภาพ. |
### getImage() {#getImage--}
```
public abstract IPPImage getImage()
```

คืนค่า หรือ ตั้งค่าภาพที่ฝังไว้. อ่าน/เขียน [IPPImage](../../com.aspose.slides/ippimage).

**คืนค่า:**
[IPPImage](../../com.aspose.slides/ippimage)
### setImage(IPPImage value) {#setImage-com.aspose.slides.IPPImage-}
```
public abstract void setImage(IPPImage value)
```

คืนค่า หรือ ตั้งค่าภาพที่ฝังไว้. อ่าน/เขียน [IPPImage](../../com.aspose.slides/ippimage).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

คืนค่า หรือ ตั้งค่า URL ของภาพที่เชื่อมโยง. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

คืนค่า หรือ ตั้งค่า URL ของภาพที่เชื่อมโยง. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |
### getImageTransform() {#getImageTransform--}
```
public abstract IImageTransformOperationCollection getImageTransform()
```

คืนค่าชุดของเอฟเฟกต์การแปลงภาพ. อ่านอย่างเดียว [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection).

**คืนค่า:**
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)