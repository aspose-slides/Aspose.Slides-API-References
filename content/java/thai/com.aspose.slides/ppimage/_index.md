---
title: PPImage
second_title: อ้างอิง API Aspose.Slides สำหรับ Java
description: เป็นการแทนภาพในงานพรีเซนเทชั่น.
type: docs
url: /th/com.aspose.slides/ppimage/
---
**สืบทอดจาก:**
java.lang.Object

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IPPImage](../../com.aspose.slides/ippimage), com.aspose.ms.System.IDisposable
```
public class PPImage implements IPPImage, System.IDisposable
```

เป็นการแทนภาพในงานพรีเซนเทชั่น.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getBinaryData()](#getBinaryData--) | ส่งคืนสำเนาข้อมูลของภาพ. |
| [getImage()](#getImage--) | ส่งคืนสำเนาของภาพ. |
| [getSvgImage()](#getSvgImage--) | ส่งคืนหรือกำหนดอ็อบเจกต์ ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage) |
| [setSvgImage(ISvgImage value)](#setSvgImage-com.aspose.slides.ISvgImage-) | ส่งคืนหรือกำหนดอ็อบเจกต์ ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage) |
| [replaceImage(byte[] newImageData)](#replaceImage-byte---) | แทนที่ข้อมูลภาพ. |
| [replaceImage(IImage newImage)](#replaceImage-com.aspose.slides.IImage-) | แทนที่ข้อมูลภาพ. |
| [replaceImage(IPPImage newImage)](#replaceImage-com.aspose.slides.IPPImage-) | แทนที่ข้อมูลภาพ. |
| [getContentType()](#getContentType--) | ส่งคืน MIME type ของภาพที่เข้ารหัสใน BinaryData (\#getBinaryData.getBinaryData). |
| [getWidth()](#getWidth--) | ส่งคืนความกว้างของภาพ. |
| [getHeight()](#getHeight--) | ส่งคืนความสูงของภาพ. |
| [getX()](#getX--) | ส่งคืนค่า X-offset ของภาพ. |
| [getY()](#getY--) | ส่งคืนค่า Y-offset ของภาพ. |
| [hashCode()](#hashCode--) | ส่งคืนค่า hash code ของภาพ. |
| [dispose()](#dispose--) | ทำลายอ็อบเจกต์. |
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```


ส่งคืนสำเนาข้อมูลของภาพ. อ่านอย่างเดียว  byte[] .

**คืนค่า:**
byte[] - อาเรย์ของไบต์
### getImage() {#getImage--}
```
public final IImage getImage()
```


ส่งคืนสำเนาของภาพ. อ่านอย่างเดียว [IImage](../../com.aspose.slides/iimage).

**คืนค่า:**
[IImage](../../com.aspose.slides/iimage)
### getSvgImage() {#getSvgImage--}
```
public final ISvgImage getSvgImage()
```


ส่งคืนหรือกำหนดอ็อบเจกต์ ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

ค่านี้บ่งชี้ว่าภาพนี้ถูกสร้างจาก SVG.

**คืนค่า:**
[ISvgImage](../../com.aspose.slides/isvgimage)
### setSvgImage(ISvgImage value) {#setSvgImage-com.aspose.slides.ISvgImage-}
```
public final void setSvgImage(ISvgImage value)
```


ส่งคืนหรือกำหนดอ็อบเจกต์ ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

ค่านี้บ่งชี้ว่าภาพนี้ถูกสร้างจาก SVG.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [ISvgImage](../../com.aspose.slides/isvgimage) |  |

### replaceImage(byte[] newImageData) {#replaceImage-byte---}
```
public final void replaceImage(byte[] newImageData)
```


แทนที่ข้อมูลภาพ.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| newImageData | byte[] | ข้อมูลของภาพใหม่. |

### replaceImage(IImage newImage) {#replaceImage-com.aspose.slides.IImage-}
```
public final void replaceImage(IImage newImage)
```


แทนที่ข้อมูลภาพ. หมายเหตุ: เมื่อ Image เป็น metafile - จะถูกแปลงเป็น raster. ใช้ ReplaceImage(byte[]) แทน

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| newImage | [IImage](../../com.aspose.slides/iimage) | ภาพใหม่. |

### replaceImage(IPPImage newImage) {#replaceImage-com.aspose.slides.IPPImage-}
```
public final void replaceImage(IPPImage newImage)
```


แทนที่ข้อมูลภาพ.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| newImage | [IPPImage](../../com.aspose.slides/ippimage) | IPPImage ใหม่. |

### getContentType() {#getContentType--}
```
public final String getContentType()
```


ส่งคืน MIME type ของภาพที่เข้ารหัสใน BinaryData (\#getBinaryData.getBinaryData). อ่านอย่างเดียว String.

**คืนค่า:**
java.lang.String
### getWidth() {#getWidth--}
```
public final int getWidth()
```


ส่งคืนความกว้างของภาพ. อ่านอย่างเดียว  int .

**คืนค่า:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


ส่งคืนความสูงของภาพ. อ่านอย่างเดียว  int .

**คืนค่า:**
int
### getX() {#getX--}
```
public final int getX()
```


ส่งคืนค่า X-offset ของภาพ. อ่านอย่างเดียว  int .

**คืนค่า:**
int
### getY() {#getY--}
```
public final int getY()
```


ส่งคืนค่า Y-offset ของภาพ. อ่านอย่างเดียว  int .

**คืนค่า:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


ส่งคืนค่า hash code ของภาพ.

**คืนค่า:**
int - Hash code.
### dispose() {#dispose--}
```
public final void dispose()
```


ทำลายอ็อบเจกต์.