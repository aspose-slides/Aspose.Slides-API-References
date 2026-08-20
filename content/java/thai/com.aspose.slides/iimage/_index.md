---
title: IImage
second_title: Aspose.Slides สำหรับ Java API Reference
description: แสดงถึงภาพแบบราสเตอร์หรือเวกเตอร์
type: docs
url: /th/com.aspose.slides/iimage/
---
**อินเทอร์เฟซที่ดำเนินการทั้งหมด:**
com.aspose.ms.System.IDisposable
```
public interface IImage extends System.IDisposable
```

แสดงถึงภาพแบบราสเตอร์หรือเวคเตอร์

--------------------

อินเทอร์เฟซนี้ให้การสรุปเชิงนามธรรมที่สอดคล้องสำหรับการจัดการทั้งภาพราสเตอร์และเวคเตอร์ การนำไปใช้อาจแตกต่างกันตามประเภทของภาพพื้นฐาน
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [save(String filename)](#save-java.lang.String-) | Saves the image to a file. |
| [save(String filename, int format)](#save-java.lang.String-int-) | Saves the image to a file in the specified format. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Saves the image to a stream in the specified format. |
| [save(String filename, int format, int quality)](#save-java.lang.String-int-int-) | Saves the image to a file in the specified format and quality. |
| [save(OutputStream stream, int format, int quality)](#save-java.io.OutputStream-int-int-) | Saves the image to a stream in the specified format and quality. |
| [getSize()](#getSize--) | Gets the size of the image. |
| [getWidth()](#getWidth--) | Gets the width of the image in pixels. |
| [getHeight()](#getHeight--) | Gets the height of the image in pixels. |
### save(String filename) {#save-java.lang.String-}
```
public abstract void save(String filename)
```


บันทึกภาพลงในไฟล์

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| filename | java.lang.String | เส้นทางไปยังไฟล์ที่ต้องการบันทึกภาพ |

### save(String filename, int format) {#save-java.lang.String-int-}
```
public abstract void save(String filename, int format)
```


บันทึกภาพลงในไฟล์ในรูปแบบที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| filename | java.lang.String | เส้นทางไปยังไฟล์ที่ต้องการบันทึกภาพ |
| format | int | รูปแบบของภาพ |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```


บันทึกภาพลงในสตรีมในรูปแบบที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.OutputStream | สตรีมที่ต้องการบันทึกภาพ |
| format | int | รูปแบบของภาพ |

### save(String filename, int format, int quality) {#save-java.lang.String-int-int-}
```
public abstract void save(String filename, int format, int quality)
```


บันทึกภาพลงในไฟล์ในรูปแบบและคุณภาพที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| filename | java.lang.String | เส้นทางไปยังไฟล์ที่ต้องการบันทึกภาพ |
| format | int | รูปแบบของภาพ |
| quality | int | คุณภาพของภาพที่บันทึก (0 ถึง 100) พารามิเตอร์นี้มีผลต่อการบันทึกเฉพาะใน [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg); สำหรับรูปแบบอื่นจะถูกละเว้น |

### save(OutputStream stream, int format, int quality) {#save-java.io.OutputStream-int-int-}
```
public abstract void save(OutputStream stream, int format, int quality)
```


บันทึกภาพลงในสตรีมในรูปแบบและคุณภาพที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.OutputStream | สตรีมที่ต้องการบันทึกภาพ |
| format | int | รูปแบบของภาพ |
| quality | int | คุณภาพของภาพที่บันทึก (0 ถึง 100) พารามิเตอร์นี้มีผลต่อการบันทึกเฉพาะใน [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg); สำหรับรูปแบบอื่นจะถูกละเว้น |

### getSize() {#getSize--}
```
public abstract Dimension getSize()
```


รับขนาดของภาพ

**ผลลัพธ์:**
java.awt.Dimension
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


รับความกว้างของภาพเป็นพิกเซล

**ผลลัพธ์:**
int
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


รับความสูงของภาพเป็นพิกเซล

**ผลลัพธ์:**
int