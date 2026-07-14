---
title: ImageCollection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API Java
description: เป็นตัวแทนของคอลเลกชันของ PPImage.
type: docs
url: /th/com.aspose.slides/imagecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IImageCollection](../../com.aspose.slides/iimagecollection)
```
public final class ImageCollection extends DomObject<Presentation> implements IImageCollection
```

เป็นตัวแทนของคอลเลกชันของ PPImage.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [size()](#size--) | คืนค่าจำนวนภาพในคอลเลกชัน |
| [get_Item(int index)](#get-Item-int-) | รับองค์ประกอบที่ตำแหน่งที่ระบุ |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | เพิ่มสำเนาของภาพจากงานนำเสนออื่น |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | เพิ่มภาพไปยังงานนำเสนอ |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | เพิ่มภาพไปยังงานนำเสนอจากสตรีม |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | สร้างและเพิ่มภาพไปยังงานนำเสนอจากสตรีม |
| [addImage(byte[] buffer)](#addImage-byte---) | เพิ่มภาพไปยังงานนำเสนอจากบัฟเฟอร์ที่ระบุ |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | เพิ่มภาพไปยังงานนำเสนอจากอ็อบเจ็กต์ Svg |
| [iterator()](#iterator--) | คืนค่า enumerator ที่ทำการวนซ้ำคอลเลกชัน |
| [iteratorJava()](#iteratorJava--) | คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกทุกองค์ประกอบจากคอลเลกชันไปยังอาร์เรย์ที่ระบุ |
| [isSynchronized()](#isSynchronized--) | คืนค่าที่บ่งชี้ว่าการเข้าถึงคอลเลกชันเป็นแบบซิงโครไนซ์ (ปลอดภัยต่อเธรด) หรือไม่ |
| [getSyncRoot()](#getSyncRoot--) | คืนค่า root ของการซิงโครไนซ์ |
### size() {#size--}
```
public final int size()
```


คืนค่าจำนวนภาพในคอลเลกชัน อ่านอย่างเดียว  int .

**คืนค่า:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IPPImage get_Item(int index)
```


รับองค์ประกอบที่ตำแหน่งที่ระบุ อ่านอย่างเดียว [IPPImage](../../com.aspose.slides/ippimage).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**คืนค่า:**
[IPPImage](../../com.aspose.slides/ippimage)
### addImage(IPPImage imageSource) {#addImage-com.aspose.slides.IPPImage-}
```
public final IPPImage addImage(IPPImage imageSource)
```


เพิ่มสำเนาของภาพจากงานนำเสนออื่น

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | รูปภาพต้นฉบับ |

**คืนค่า:**
[IPPImage](../../com.aspose.slides/ippimage) - ภาพที่เพิ่ม
### addImage(IImage image) {#addImage-com.aspose.slides.IImage-}
```
public final IPPImage addImage(IImage image)
```


เพิ่มภาพไปยังงานนำเสนอ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | ภาพที่จะเพิ่ม

--------------------

วิธีการนี้แปลงไฟล์เมตาฟายล์ WMF/EMF เป็นภาพ PNG แบบแรสเตอร์ก่อนแทรกเข้าสู่งานนำเสนอ

**คืนค่า:**
[IPPImage](../../com.aspose.slides/ippimage) - ภาพที่เพิ่ม
### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public final IPPImage addImage(InputStream stream)
```


เพิ่มภาพไปยังงานนำเสนอจากสตรีม

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.InputStream | สตรีมที่ใช้เพิ่มภาพจาก

--------------------

วิธีการนี้สามารถเพิ่มไฟล์เมตาฟายล์ WMF/EMF ไปยังงานนำเสนอโดยไม่แปลงเป็นภาพ PNG แบบแรสเตอร์

**คืนค่า:**
[IPPImage](../../com.aspose.slides/ippimage) - ภาพที่เพิ่ม
### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public final IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```


สร้างและเพิ่มภาพไปยังงานนำเสนอจากสตรีม

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.InputStream | สตรีมที่ใช้เพิ่มไฟล์ภาพจาก |
| loadingStreamBehavior | int | พฤติกรรมที่ใช้กับสตรีม |

**คืนค่า:**
[IPPImage](../../com.aspose.slides/ippimage) - เพิ่ม [IPPImage](../../com.aspose.slides/ippimage).
### addImage(byte[] buffer) {#addImage-byte---}
```
public final IPPImage addImage(byte[] buffer)
```


เพิ่มภาพไปยังงานนำเสนอจากบัฟเฟอร์ที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | byte[] | บัฟเฟอร์ |

**คืนค่า:**
[IPPImage](../../com.aspose.slides/ippimage) - ภาพที่เพิ่ม
### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public final IPPImage addImage(ISvgImage svgImage)
```


เพิ่มภาพไปยังงานนำเสนอจากอ็อบเจ็กต์ Svg

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | อ็อบเจ็กต์ภาพ Svg [ISvgImage](../../com.aspose.slides/isvgimage) |

**คืนค่า:**
[IPPImage](../../com.aspose.slides/ippimage) - ภาพที่เพิ่ม
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPPImage> iterator()
```


คืนค่า enumerator ที่ทำการวนซ้ำคอลเลกชัน

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPPImage> - IGenericEnumerator ที่สามารถใช้เพื่อวนซ้ำคอลเลกชัน
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPPImage> iteratorJava()
```


คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPPImage> - java.util.Iterator สำหรับคอลเลกชันทั้งหมด
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


คัดลอกทุกองค์ประกอบจากคอลเลกชันไปยังอาร์เรย์ที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | อาร์เรย์เป้าหมาย |
| index | int | ดัชนีเริ่มต้นในอาร์เรย์เป้าหมาย |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


คืนค่าที่บ่งชี้ว่าการเข้าถึงคอลเลกชันเป็นแบบซิงโครไนซ์ (ปลอดภัยต่อเธรด) อ่านอย่างเดียว  boolean .

**คืนค่า:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


คืนค่า root ของการซิงโครไนซ์ อ่านอย่างเดียว  Object .

**คืนค่า:**
java.lang.Object