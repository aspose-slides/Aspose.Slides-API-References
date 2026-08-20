---
title: ISlidesPicture
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: เป็นการแทนรูปภาพในงานนำเสนอ.
type: docs
url: /th/com.aspose.slides/islidespicture/
---
**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ISlidesPicture extends ISlideComponent
```

เป็นการแทนรูปภาพในงานนำเสนอ.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getImage()](#getImage--) | คืนค่า หรือ กำหนดภาพที่ฝังอยู่. |
| [setImage(IPPImage value)](#setImage-com.aspose.slides.IPPImage-) | คืนค่า หรือ กำหนดภาพที่ฝังอยู่. |
| [getLinkPathLong()](#getLinkPathLong--) | คืนค่า หรือ กำหนด URL ของภาพที่เชื่อมโยง. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | คืนค่า หรือ กำหนด URL ของภาพที่เชื่อมโยง. |
| [getImageTransform()](#getImageTransform--) | คืนค่าคอลเลกชันของเอฟเฟกต์การแปลงภาพ. |
### getImage() {#getImage--}
```
public abstract IPPImage getImage()
```

คืนค่า หรือ กำหนดภาพที่ฝังอยู่. อ่าน/เขียน [IPPImage](../../com.aspose.slides/ippimage).

**คืนค่า:**
[IPPImage](../../com.aspose.slides/ippimage)
### setImage(IPPImage value) {#setImage-com.aspose.slides.IPPImage-}
```
public abstract void setImage(IPPImage value)
```

คืนค่า หรือ กำหนดภาพที่ฝังอยู่. อ่าน/เขียน [IPPImage](../../com.aspose.slides/ippimage).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

คืนค่า หรือ กำหนด URL ของภาพที่เชื่อมโยง. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

คืนค่า หรือ กำหนด URL ของภาพที่เชื่อมโยง. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getImageTransform() {#getImageTransform--}
```
public abstract IImageTransformOperationCollection getImageTransform()
```

คืนค่าคอลเลกชันของเอฟเฟกต์การแปลงภาพ. อ่านอย่างเดียว [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection).

**คืนค่า:**
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)