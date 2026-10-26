---
title: Picture
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงถึงรูปภาพในงานนำเสนอ.
type: docs
url: /th/com.aspose.slides/picture/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**
com.aspose.slides.IPVIObject, [com.aspose.slides.ISlidesPicture](../../com.aspose.slides/islidespicture)
```
public final class Picture implements IPVIObject, ISlidesPicture
```

แสดงถึงรูปภาพในงานนำเสนอ.
## เมธอด

| เมธอด | รายละเอียด |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getImage()](#getImage--) | คืนค่าหรือกำหนดภาพที่ฝังอยู่. |
| [setImage(IPPImage value)](#setImage-com.aspose.slides.IPPImage-) | คืนค่าหรือกำหนดภาพที่ฝังอยู่. |
| [getLinkPathLong()](#getLinkPathLong--) | คืนค่าหรือกำหนด URL ของภาพที่เชื่อมโยง. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | คืนค่าหรือกำหนด URL ของภาพที่เชื่อมโยง. |
| [getImageTransform()](#getImageTransform--) | คืนค่าคอลเลกชันของเอฟเฟกต์การแปลงภาพ. |
| [getPresentation()](#getPresentation--) | คืนค่าการนำเสนอ. |
| [equals(Object obj)](#equals-java.lang.Object-) | เปรียบเทียบกับอ็อบเจกต์ที่ระบุ. |
| [hashCode()](#hashCode--) | คืนค่าแฮช. |
| [getSlide()](#getSlide--) | คืนค่าพาเรนท์สไลด์ของรูปภาพ. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

คืนค่า Parent_Immediate object. อ่านอย่างเดียว IDOMObject.

**คืนค่า:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```

รุ่น. อ่านอย่างเดียว long.

**คืนค่า:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

คืนค่าพาเรนท์ IPresentationComponent. อ่านอย่างเดียว [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**คืนค่า:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### getImage() {#getImage--}
```
public final IPPImage getImage()
```

คืนค่าหรือกำหนดภาพที่ฝังอยู่. อ่าน/เขียน [IPPImage](../../com.aspose.slides/ippimage).

**คืนค่า:**
[IPPImage](../../com.aspose.slides/ippimage)
### setImage(IPPImage value) {#setImage-com.aspose.slides.IPPImage-}
```
public final void setImage(IPPImage value)
```

คืนค่าหรือกำหนดภาพที่ฝังอยู่. อ่าน/เขียน [IPPImage](../../com.aspose.slides/ippimage).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | รายละเอียด |
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
| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| value | java.lang.String |  |

### getImageTransform() {#getImageTransform--}
```
public final IImageTransformOperationCollection getImageTransform()
```

คืนค่าคอลเลกชันของเอฟเฟกต์การแปลงภาพ. อ่านอย่างเดียว [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection).

**คืนค่า:**
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

คืนค่าการนำเสนอ. อ่านอย่างเดียว [IPresentation](../../com.aspose.slides/ipresentation).

**คืนค่า:**
[IPresentation](../../com.aspose.slides/ipresentation)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

เปรียบเทียบกับอ็อบเจกต์ที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| obj | java.lang.Object | อ็อบเจกต์ที่จะเปรียบเทียบ. |

**คืนค่า:**
boolean - true หากอ็อบเจกต์เท่ากัน, ไม่เช่นนั้น false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

คืนค่าแฮช.

**คืนค่า:**
int - แฮช.
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

คืนค่าพาเรนท์สไลด์ของรูปภาพ. อ่านอย่างเดียว [IBaseSlide](../../com.aspose.slides/ibaseslide).

**คืนค่า:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)