---
title: IPPImage
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แทนภาพในงานนำเสนอ.
type: docs
url: /th/com.aspose.slides/ippimage/
---```
public interface IPPImage
```

แทนภาพในงานนำเสนอ.
## เมธอด

| Method | Description |
| --- | --- |
| [getBinaryData()](#getBinaryData--) | คืนสำเนาข้อมูลของภาพ. |
| [getImage()](#getImage--) | คืนสำเนาภาพ. |
| [getSvgImage()](#getSvgImage--) | คืนหรือกำหนดอ็อบเจกต์ ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage) |
| [setSvgImage(ISvgImage value)](#setSvgImage-com.aspose.slides.ISvgImage-) | คืนหรือกำหนดอ็อบเจกต์ ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage) |
| [replaceImage(byte[] newImageData)](#replaceImage-byte---) | แทนที่ข้อมูลภาพ. |
| [replaceImage(IImage newImage)](#replaceImage-com.aspose.slides.IImage-) | แทนที่ภาพ. |
| [replaceImage(IPPImage newImage)](#replaceImage-com.aspose.slides.IPPImage-) | แทนที่ภาพ. |
| [getContentType()](#getContentType--) | คืนประเภท MIME ของภาพที่เข้ารหัสใน \#getBinaryData.getBinaryData. |
| [getWidth()](#getWidth--) | คืนค่าความกว้างของภาพ. |
| [getHeight()](#getHeight--) | คืนค่าความสูงของภาพ. |
| [getX()](#getX--) | คืนค่า X-offset ของภาพ. |
| [getY()](#getY--) | คืนค่า Y-offset ของภาพ. |
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

คืนสำเนาข้อมูลของภาพ. อ่านอย่างเดียว byte[].

**คืนค่า:**
byte[]
### getImage() {#getImage--}
```
public abstract IImage getImage()
```

คืนสำเนาภาพ. อ่านอย่างเดียว \#getImage.getImage.

**คืนค่า:**
[IImage](../../com.aspose.slides/iimage)
### getSvgImage() {#getSvgImage--}
```
public abstract ISvgImage getSvgImage()
```

คืนหรือกำหนดอ็อบเจกต์ ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

ค่านี้บ่งชี้ว่าภาพนี้ถูกสร้างจาก SVG.

**คืนค่า:**
[ISvgImage](../../com.aspose.slides/isvgimage)
### setSvgImage(ISvgImage value) {#setSvgImage-com.aspose.slides.ISvgImage-}
```
public abstract void setSvgImage(ISvgImage value)
```

คืนหรือกำหนดอ็อบเจกต์ ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

ค่านี้บ่งชี้ว่าภาพนี้ถูกสร้างจาก SVG.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [ISvgImage](../../com.aspose.slides/isvgimage) |  |
### replaceImage(byte[] newImageData) {#replaceImage-byte---}
```
public abstract void replaceImage(byte[] newImageData)
```

แทนที่ภาพ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| newImageData | byte[] | ข้อมูลของภาพใหม่. |
### replaceImage(IImage newImage) {#replaceImage-com.aspose.slides.IImage-}
```
public abstract void replaceImage(IImage newImage)
```

แทนที่ภาพ. หมายเหตุ: เมื่อ Image เป็นเมตาฟไฟล์ - จะถูกแปลงเป็นเรสเตอร์. ใช้ replaceImage(byte[]) แทน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| newImage | [IImage](../../com.aspose.slides/iimage) | ภาพใหม่. |
### replaceImage(IPPImage newImage) {#replaceImage-com.aspose.slides.IPPImage-}
```
public abstract void replaceImage(IPPImage newImage)
```

แทนที่ภาพ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| newImage | [IPPImage](../../com.aspose.slides/ippimage) | IPPImage ใหม่. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

คืนประเภท MIME ของภาพที่เข้ารหัสใน \#getBinaryData.getBinaryData. อ่านอย่างเดียว String.

**คืนค่า:**
java.lang.String
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```

คืนค่าความกว้างของภาพ. อ่านอย่างเดียว int.

**คืนค่า:**
int
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```

คืนค่าความสูงของภาพ. อ่านอย่างเดียว int.

**คืนค่า:**
int
### getX() {#getX--}
```
public abstract int getX()
```

คืนค่า X-offset ของภาพ. อ่านอย่างเดียว int.

**คืนค่า:**
int
### getY() {#getY--}
```
public abstract int getY()
```

คืนค่า Y-offset ของภาพ. อ่านอย่างเดียว int.

**คืนค่า:**
int