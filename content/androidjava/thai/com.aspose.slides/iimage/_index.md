---
title: IImage
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงถึงภาพแบบแรสเตอร์หรือเวกเตอร์.
type: docs
url: /th/com.aspose.slides/iimage/
---
**อินเทอร์เฟซที่ใช้งานทั้งหมด:**
com.aspose.ms.System.IDisposable
```
public interface IImage extends System.IDisposable
```

แสดงถึงภาพแบบ raster หรือ vector

--------------------

อินเทอร์เฟซนี้ให้การสอดคล้องร่วมสำหรับการจัดการภาพ raster และ vector ทั้งสองประเภท การทำงานอาจแตกต่างกันไปตามชนิดของภาพพื้นฐาน

## เมธอด

| Method | Description |
| --- | --- |
| [save(String filename)](#save-java.lang.String-) | บันทึกภาพลงในไฟล์. |
| [save(String filename, int format)](#save-java.lang.String-int-) | บันทึกภาพลงในไฟล์ด้วยรูปแบบที่ระบุ. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | บันทึกภาพลงในสตรีมด้วยรูปแบบที่ระบุ. |
| [save(String filename, int format, int quality)](#save-java.lang.String-int-int-) | บันทึกภาพลงในไฟล์ด้วยรูปแบบและคุณภาพที่ระบุ. |
| [save(OutputStream stream, int format, int quality)](#save-java.io.OutputStream-int-int-) | บันทึกภาพลงในสตรีมด้วยรูปแบบและคุณภาพที่ระบุ. |
| [getSize()](#getSize--) | รับขนาดของภาพ. |
| [getWidth()](#getWidth--) | รับความกว้างของภาพเป็นพิกเซล. |
| [getHeight()](#getHeight--) | รับความสูงของภาพเป็นพิกเซล. |

### save(String filename) {#save-java.lang.String-}
```
public abstract void save(String filename)
```

บันทึกภาพลงในไฟล์.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| filename | java.lang.String | เส้นทางไปยังไฟล์ที่ภาพจะถูกบันทึก. |

### save(String filename, int format) {#save-java.lang.String-int-}
```
public abstract void save(String filename, int format)
```

บันทึกภาพลงในไฟล์ด้วยรูปแบบที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| filename | java.lang.String | เส้นทางไปยังไฟล์ที่ภาพจะถูกบันทึก. |
| format | int | รูปแบบของภาพ. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

บันทึกภาพลงในสตรีมด้วยรูปแบบที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.OutputStream | สตรีมที่ภาพจะถูกบันทึก. |
| format | int | รูปแบบของภาพ. |

### save(String filename, int format, int quality) {#save-java.lang.String-int-int-}
```
public abstract void save(String filename, int format, int quality)
```

บันทึกภาพลงในไฟล์ด้วยรูปแบบและคุณภาพที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| filename | java.lang.String | เส้นทางไปยังไฟล์ที่ภาพจะถูกบันทึก. |
| format | int | รูปแบบของภาพ. |
| quality | int | คุณภาพของภาพที่บันทึก (0 ถึง 100). พารามิเตอร์นี้มีผลต่อการบันทึกใน [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg) เท่านั้น; สำหรับรูปแบบอื่นทั้งหมด จะถูกละเว้น. |

### save(OutputStream stream, int format, int quality) {#save-java.io.OutputStream-int-int-}
```
public abstract void save(OutputStream stream, int format, int quality)
```

บันทึกภาพลงในสตรีมด้วยรูปแบบและคุณภาพที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.OutputStream | สตรีมที่ภาพจะถูกบันทึก. |
| format | int | รูปแบบของภาพ. |
| quality | int | คุณภาพของภาพที่บันทึก (0 ถึง 100). พารามิเตอร์นี้มีผลต่อการบันทึกใน [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg) เท่านั้น; สำหรับรูปแบบอื่นทั้งหมด จะถูกละเว้น. |

### getSize() {#getSize--}
```
public abstract Size getSize()
```

รับขนาดของภาพ.

**คืนค่า:**
[Size](../../com.aspose.slides.android/size)

### getWidth() {#getWidth--}
```
public abstract int getWidth()
```

รับความกว้างของภาพเป็นพิกเซล.

**คืนค่า:**
int

### getHeight() {#getHeight--}
```
public abstract int getHeight()
```

รับความสูงของภาพเป็นพิกเซล.

**คืนค่า:**
int