---
title: Output
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงถึงคอลเลกชันขององค์ประกอบผลลัพธ์สำหรับ IWebDocument.
type: docs
url: /th/com.aspose.slides/output/
---
**การสืบทอด:**
java.lang.Object
```
public final class Output
```

แสดงถึงคอลเลกชันขององค์ประกอบผลลัพธ์สำหรับ IWebDocument.
## Methods

| Method | Description |
| --- | --- |
| [<TContextObject>add(String path, String templateKey, TContextObject contextObject)](#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-) | เพิ่มองค์ประกอบผลลัพธ์สำหรับวัตถุบริบท |
| [add(String path, IPPImage image)](#add-java.lang.String-com.aspose.slides.IPPImage-) | เพิ่มองค์ประกอบผลลัพธ์สำหรับภาพ |
| [add(String path, IImage image)](#add-java.lang.String-com.aspose.slides.IImage-) | เพิ่มองค์ประกอบผลลัพธ์สำหรับภาพ |
| [add(String path, IVideo video)](#add-java.lang.String-com.aspose.slides.IVideo-) | เพิ่มองค์ประกอบผลลัพธ์สำหรับวิดีโอ |
| [add(String path, IAudio audio)](#add-java.lang.String-com.aspose.slides.IAudio-) | เพิ่มองค์ประกอบผลลัพธ์สำหรับเสียง |
| [add(String path, IFontData fontData, int fontStyle)](#add-java.lang.String-com.aspose.slides.IFontData-int-) | สร้างและเพิ่มองค์ประกอบไฟล์ผลลัพธ์สำหรับฟอนท์ที่ระบุ |
| [add(String path, String textContent)](#add-java.lang.String-java.lang.String-) | เพิ่มองค์ประกอบผลลัพธ์สำหรับเนื้อหาข้อความ |
| [bindResource(IOutputFile outputFile, Object obj)](#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-) | ผูกทรัพยากรกับไฟล์ผลลัพธ์ |
| [getResourcePath(Object obj)](#getResourcePath-java.lang.Object-) | คืนค่าเส้นทางสำหรับทรัพยากรที่ระบุ |
### <TContextObject>add(String path, String templateKey, TContextObject contextObject) {#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-}
```
public final IOutputFile <TContextObject>add(String path, String templateKey, TContextObject contextObject)
```

เพิ่มองค์ประกอบผลลัพธ์สำหรับวัตถุบริบท

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | เส้นทางผลลัพธ์ |
| templateKey | java.lang.String | คีย์ของเทมเพลตที่ใช้ในการแปลงวัตถุบริบทก่อนการส่งออก |
| contextObject | TContextObject | วัตถุบริบท |

**Returns:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) object สำหรับวัตถุบริบท
### add(String path, IPPImage image) {#add-java.lang.String-com.aspose.slides.IPPImage-}
```
public final IOutputFile add(String path, IPPImage image)
```

เพิ่มองค์ประกอบผลลัพธ์สำหรับภาพ

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | เส้นทางผลลัพธ์ |
| image | [IPPImage](../../com.aspose.slides/ippimage) | ภาพที่ต้องการส่งออก |

**Returns:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) object สำหรับภาพ
### add(String path, IImage image) {#add-java.lang.String-com.aspose.slides.IImage-}
```
public final IOutputFile add(String path, IImage image)
```

เพิ่มองค์ประกอบผลลัพธ์สำหรับภาพ

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | เส้นทางผลลัพธ์ |
| image | [IImage](../../com.aspose.slides/iimage) | ภาพที่ต้องการส่งออก |

**Returns:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) object สำหรับภาพ
### add(String path, IVideo video) {#add-java.lang.String-com.aspose.slides.IVideo-}
```
public final IOutputFile add(String path, IVideo video)
```

เพิ่มองค์ประกอบผลลัพธ์สำหรับวิดีโอ

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | เส้นทางผลลัพธ์ |
| video | [IVideo](../../com.aspose.slides/ivideo) | วิดีโอที่ต้องการส่งออก |

**Returns:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) object สำหรับวิดีโอ
### add(String path, IAudio audio) {#add-java.lang.String-com.aspose.slides.IAudio-}
```
public final IOutputFile add(String path, IAudio audio)
```

เพิ่มองค์ประกอบผลลัพธ์สำหรับเสียง

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | เส้นทางผลลัพธ์ |
| audio | [IAudio](../../com.aspose.slides/iaudio) | เสียงที่ต้องการส่งออก |

**Returns:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) object สำหรับเสียง
### add(String path, IFontData fontData, int fontStyle) {#add-java.lang.String-com.aspose.slides.IFontData-int-}
```
public final IOutputFile add(String path, IFontData fontData, int fontStyle)
```

สร้างและเพิ่มองค์ประกอบไฟล์ผลลัพธ์สำหรับฟอนท์ที่ระบุ

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | เส้นทางไฟล์ที่ฟอนท์ผลลัพธ์จะถูกบันทึก |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | ข้อมูลฟอนท์ที่จะเขียนลงไฟล์ผลลัพธ์ |
| fontStyle | int | สไตล์ของฟอนท์ (เช่น Regular, Bold, Italic) |

**Returns:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - ตัวอย่างของ [IOutputFile](../../com.aspose.slides/ioutputfile) สำหรับฟอนท์ที่สร้างขึ้น
### add(String path, String textContent) {#add-java.lang.String-java.lang.String-}
```
public final IOutputFile add(String path, String textContent)
```

เพิ่มองค์ประกอบผลลัพธ์สำหรับเนื้อหาข้อความ

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | เส้นทางผลลัพธ์ |
| textContent | java.lang.String | เนื้อหาที่จะส่งออก |

**Returns:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) object สำหรับเนื้อหาข้อความ
### bindResource(IOutputFile outputFile, Object obj) {#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-}
```
public final void bindResource(IOutputFile outputFile, Object obj)
```

ผูกทรัพยากรกับไฟล์ผลลัพธ์

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | [IOutputFile](../../com.aspose.slides/ioutputfile) | ไฟล์ผลลัพธ์ |
| obj | java.lang.Object | วัตถุทรัพยากร |
### getResourcePath(Object obj) {#getResourcePath-java.lang.Object-}
```
public final String getResourcePath(Object obj)
```

คืนค่าเส้นทางสำหรับทรัพยากรที่ระบุ

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | วัตถุทรัพยากร |

**Returns:**
java.lang.String - เส้นทางของทรัพยากร