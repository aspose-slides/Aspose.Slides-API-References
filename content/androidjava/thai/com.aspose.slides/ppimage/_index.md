---
title: PPImage
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: เป็นการแสดงภาพในงานนำเสนอ.
type: docs
url: /th/com.aspose.slides/ppimage/
---
**การสืบทอด:**  
java.lang.Object

**ส่วนต่อประสานที่ใช้งานทั้งหมด:**  
[com.aspose.slides.IPPImage](../../com.aspose.slides/ippimage), com.aspose.ms.System.IDisposable  
```
public class PPImage implements IPPImage, System.IDisposable
```

แสดงถึงภาพในงานนำเสนอ.

## เมธอด

| Method | Description |
| --- | --- |
| [getBinaryData()](#getBinaryData--) | คืนสำเนาข้อมูลของภาพ. |
| [getImage()](#getImage--) | คืนสำเนาภาพ. |
| [getSvgImage()](#getSvgImage--) | คืนค่า หรือกำหนดวัตถุ ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage) |
| [setSvgImage(ISvgImage value)](#setSvgImage-com.aspose.slides.ISvgImage-) | คืนค่า หรือกำหนดวัตถุ ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage) |
| [replaceImage(byte[] newImageData)](#replaceImage-byte---) | แทนที่ข้อมูลภาพ. |
| [replaceImage(IImage newImage)](#replaceImage-com.aspose.slides.IImage-) | แทนที่ข้อมูลภาพ. |
| [replaceImage(IPPImage newImage)](#replaceImage-com.aspose.slides.IPPImage-) | แทนที่ข้อมูลภาพ. |
| [getContentType()](#getContentType--) | คืน MIME type ของภาพ, เข้ารหัสใน BinaryData (\#getBinaryData.getBinaryData). |
| [getWidth()](#getWidth--) | คืนค่าความกว้างของภาพ. |
| [getHeight()](#getHeight--) | คืนความสูงของภาพ. |
| [getX()](#getX--) | คืนค่า X-offset ของภาพ. |
| [getY()](#getY--) | คืนค่า Y-offset ของภาพ. |
| [hashCode()](#hashCode--) | คืนค่าแฮชโค้ดของภาพ. |
| [dispose()](#dispose--) | ทำลายวัตถุ. |

### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

คืนสำเนาข้อมูลของภาพ. อ่านอย่างเดียว  byte[] .

**ส่งคืน:**  
byte[] - อาร์เรย์ของไบต์

### getImage() {#getImage--}
```
public final IImage getImage()
```

คืนสำเนาของภาพ. อ่านอย่างเดียว [IImage](../../com.aspose.slides/iimage).

**ส่งคืน:**  
[IImage](../../com.aspose.slides/iimage)

### getSvgImage() {#getSvgImage--}
```
public final ISvgImage getSvgImage()
```

คืนค่า หรือกำหนดวัตถุ ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

ค่านี้บ่งชี้ว่าภาพนี้สร้างจาก SVG.

**ส่งคืน:**  
[ISvgImage](../../com.aspose.slides/isvgimage)

### setSvgImage(ISvgImage value) {#setSvgImage-com.aspose.slides.ISvgImage-}
```
public final void setSvgImage(ISvgImage value)
```

คืนค่า หรือกำหนดวัตถุ ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

ค่านี้บ่งชี้ว่าภาพนี้สร้างจาก SVG.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [ISvgImage](../../com.aspose.slides/isvgimage) |  |

### replaceImage(byte[] newImageData) {#replaceImage-byte---}
```
public final void replaceImage(byte[] newImageData)
```

แทนที่ข้อมูลภาพ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| newImageData | byte[] | ข้อมูลของภาพใหม่. |

### replaceImage(IImage newImage) {#replaceImage-com.aspose.slides.IImage-}
```
public final void replaceImage(IImage newImage)
```

แทนที่ข้อมูลภาพ. หมายเหตุ: เมื่อ Image เป็นเมทาฟาไฟล์ - จะถูกแปลงเป็นเรสเตอร์. ใช้ ReplaceImage(byte[]) แทน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| newImage | [IImage](../../com.aspose.slides/iimage) | ภาพใหม่. |

### replaceImage(IPPImage newImage) {#replaceImage-com.aspose.slides.IPPImage-}
```
public final void replaceImage(IPPImage newImage)
```

แทนที่ข้อมูลภาพ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| newImage | [IPPImage](../../com.aspose.slides/ippimage) | IPPImage ใหม่. |

### getContentType() {#getContentType--}
```
public final String getContentType()
```

คืน MIME type ของภาพ, เข้ารหัสใน BinaryData (\#getBinaryData.getBinaryData). อ่านอย่างเดียว String.

**ส่งคืน:**  
java.lang.String

### getWidth() {#getWidth--}
```
public final int getWidth()
```

คืนค่าความกว้างของภาพ. อ่านอย่างเดียว  int .

**ส่งคืน:**  
int

### getHeight() {#getHeight--}
```
public final int getHeight()
```

คืนความสูงของภาพ. อ่านอย่างเดียว  int .

**ส่งคืน:**  
int

### getX() {#getX--}
```
public final int getX()
```

คืนค่า X-offset ของภาพ. อ่านอย่างเดียว  int .

**ส่งคืน:**  
int

### getY() {#getY--}
```
public final int getY()
```

คืนค่า Y-offset ของภาพ. อ่านอย่างเดียว  int .

**ส่งคืน:**  
int

### hashCode() {#hashCode--}
```
public int hashCode()
```

คืนค่าแฮชโค้ดของภาพ.

**ส่งคืน:**  
int - แฮชโค้ด.

### dispose() {#dispose--}
```
public final void dispose()
```

ทำลายวัตถุ.