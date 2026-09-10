---
title: Output
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: เป็นตัวแทนของคอลเลกชันขององค์ประกอบผลลัพธ์สำหรับ IWebDocument.
type: docs
url: /th/com.aspose.slides/output/
---
**การสืบทอด:**
java.lang.Object
```
public final class Output
```

เป็นตัวแทนของกลุ่มขององค์ประกอบผลลัพธ์สำหรับ IWebDocument.
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [<TContextObject>add(String path, String templateKey, TContextObject contextObject)](#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-) | เพิ่มองค์ประกอบผลลัพธ์สำหรับอ็อบเจ็กต์บริบท. |
| [add(String path, IPPImage image)](#add-java.lang.String-com.aspose.slides.IPPImage-) | เพิ่มองค์ประกอบผลลัพธ์สำหรับรูปภาพ. |
| [add(String path, IImage image)](#add-java.lang.String-com.aspose.slides.IImage-) | เพิ่มองค์ประกอบผลลัพธ์สำหรับรูปภาพ. |
| [add(String path, IVideo video)](#add-java.lang.String-com.aspose.slides.IVideo-) | เพิ่มองค์ประกอบผลลัพธ์สำหรับวิดีโอ. |
| [add(String path, IAudio audio)](#add-java.lang.String-com.aspose.slides.IAudio-) | เพิ่มองค์ประกอบผลลัพธ์สำหรับเสียง. |
| [add(String path, IFontData fontData, int fontStyle)](#add-java.lang.String-com.aspose.slides.IFontData-int-) | สร้างและเพิ่มองค์ประกอบไฟล์ผลลัพธ์สำหรับฟอนต์ที่ระบุ. |
| [add(String path, String textContent)](#add-java.lang.String-java.lang.String-) | เพิ่มองค์ประกอบผลลัพธ์สำหรับเนื้อหาข้อความ. |
| [bindResource(IOutputFile outputFile, Object obj)](#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-) | ผูกทรัพยากรกับไฟล์ผลลัพธ์. |
| [getResourcePath(Object obj)](#getResourcePath-java.lang.Object-) | คืนค่าเส้นทางสำหรับทรัพยากรที่กำหนด. |
### <TContextObject>add(String path, String templateKey, TContextObject contextObject) {#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-}
```
public final IOutputFile <TContextObject>add(String path, String templateKey, TContextObject contextObject)
```


เพิ่มองค์ประกอบผลลัพธ์สำหรับอ็อบเจ็กต์บริบท.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| path | java.lang.String | เส้นทางเอาต์พุต. |
| templateKey | java.lang.String | คีย์ของเทมเพลตที่ใช้สำหรับการแปลงอ็อบเจ็กต์บริบทก่อนการส่งออก. |
| contextObject | TContextObject | อ็อบเจ็กต์บริบท. |

**ผลลัพธ์:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) อ็อบเจ็กต์สำหรับอ็อบเจ็กต์บริบท.
### add(String path, IPPImage image) {#add-java.lang.String-com.aspose.slides.IPPImage-}
```
public final IOutputFile add(String path, IPPImage image)
```


เพิ่มองค์ประกอบผลลัพธ์สำหรับรูปภาพ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| path | java.lang.String | เส้นทางเอาต์พุต. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | รูปภาพที่ต้องการส่งออก. |

**ผลลัพธ์:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) อ็อบเจ็กต์สำหรับรูปภาพ.
### add(String path, IImage image) {#add-java.lang.String-com.aspose.slides.IImage-}
```
public final IOutputFile add(String path, IImage image)
```


เพิ่มองค์ประกอบผลลัพธ์สำหรับรูปภาพ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| path | java.lang.String | เส้นทางเอาต์พุต. |
| image | [IImage](../../com.aspose.slides/iimage) | รูปภาพที่ต้องการส่งออก. |

**ผลลัพธ์:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) อ็อบเจ็กต์สำหรับรูปภาพ.
### add(String path, IVideo video) {#add-java.lang.String-com.aspose.slides.IVideo-}
```
public final IOutputFile add(String path, IVideo video)
```


เพิ่มองค์ประกอบผลลัพธ์สำหรับวิดีโอ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| path | java.lang.String | เส้นทางเอาต์พุต. |
| video | [IVideo](../../com.aspose.slides/ivideo) | วิดีโอที่ต้องการส่งออก. |

**ผลลัพธ์:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) อ็อบเจ็กต์สำหรับวิดีโอ.
### add(String path, IAudio audio) {#add-java.lang.String-com.aspose.slides.IAudio-}
```
public final IOutputFile add(String path, IAudio audio)
```


เพิ่มองค์ประกอบผลลัพธ์สำหรับเสียง.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| path | java.lang.String | เส้นทางเอาต์พุต. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | เสียงที่ต้องการส่งออก. |

**ผลลัพธ์:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) อ็อบเจ็กต์สำหรับเสียง.
### add(String path, IFontData fontData, int fontStyle) {#add-java.lang.String-com.aspose.slides.IFontData-int-}
```
public final IOutputFile add(String path, IFontData fontData, int fontStyle)
```


สร้างและเพิ่มองค์ประกอบไฟล์ผลลัพธ์สำหรับฟอนต์ที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| path | java.lang.String | เส้นทางไฟล์ที่ผลลัพธ์ฟอนต์จะถูกบันทึก. |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | ข้อมูลฟอนต์ที่จะเขียนไปยังผลลัพธ์. |
| fontStyle | int | สไตล์ของฟอนต์ (เช่น Regular, Bold, Italic). |

**ผลลัพธ์:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - อินสแตนซ์ [IOutputFile](../../com.aspose.slides/ioutputfile) สำหรับฟอนต์ที่สร้างขึ้น.
### add(String path, String textContent) {#add-java.lang.String-java.lang.String-}
```
public final IOutputFile add(String path, String textContent)
```


เพิ่มองค์ประกอบผลลัพธ์สำหรับเนื้อหาข้อความ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| path | java.lang.String | เส้นทางเอาต์พุต. |
| textContent | java.lang.String | เนื้อหาที่จะส่งออก. |

**ผลลัพธ์:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) อ็อบเจ็กต์สำหรับเนื้อหาข้อความ.
### bindResource(IOutputFile outputFile, Object obj) {#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-}
```
public final void bindResource(IOutputFile outputFile, Object obj)
```


ผูกทรัพยากรกับไฟล์ผลลัพธ์.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| outputFile | [IOutputFile](../../com.aspose.slides/ioutputfile) | ไฟล์ผลลัพธ์. |
| obj | java.lang.Object | อ็อบเจ็กต์ทรัพยากร. |

### getResourcePath(Object obj) {#getResourcePath-java.lang.Object-}
```
public final String getResourcePath(Object obj)
```


คืนค่าเส้นทางสำหรับทรัพยากรที่กำหนด.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| obj | java.lang.Object | อ็อบเจ็กต์ทรัพยากร. |

**ผลลัพธ์:**
java.lang.String - เส้นทางของทรัพยากร.