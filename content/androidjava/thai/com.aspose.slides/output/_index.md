---
title: Output
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
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
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [<TContextObject>add(String path, String templateKey, TContextObject contextObject)](#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-) | เพิ่มองค์ประกอบผลลัพธ์สำหรับอ็อบเจ็กต์บริบท. |
| [add(String path, IPPImage image)](#add-java.lang.String-com.aspose.slides.IPPImage-) | เพิ่มองค์ประกอบผลลัพธ์สำหรับภาพ. |
| [add(String path, IImage image)](#add-java.lang.String-com.aspose.slides.IImage-) | เพิ่มองค์ประกอบผลลัพธ์สำหรับภาพ. |
| [add(String path, IVideo video)](#add-java.lang.String-com.aspose.slides.IVideo-) | เพิ่มองค์ประกอบผลลัพธ์สำหรับวิดีโอ. |
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
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| path | java.lang.String | เส้นทางผลลัพธ์. |
| templateKey | java.lang.String | คีย์ของเทมเพลตที่ใช้สำหรับการแปลงอ็อบเจ็กต์บริบทก่อนการส่งออก. |
| contextObject | TContextObject | อ็อบเจ็กต์บริบท. |

**คืนค่า:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) อ็อบเจ็กต์สำหรับอ็อบเจ็กต์บริบท.
### add(String path, IPPImage image) {#add-java.lang.String-com.aspose.slides.IPPImage-}
```
public final IOutputFile add(String path, IPPImage image)
```

เพิ่มองค์ประกอบผลลัพธ์สำหรับภาพ.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| path | java.lang.String | เส้นทางผลลัพธ์. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | ภาพสำหรับส่งออก. |

**คืนค่า:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) อ็อบเจ็กต์สำหรับภาพ.
### add(String path, IImage image) {#add-java.lang.String-com.aspose.slides.IImage-}
```
public final IOutputFile add(String path, IImage image)
```

เพิ่มองค์ประกอบผลลัพธ์สำหรับภาพ.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| path | java.lang.String | เส้นทางผลลัพธ์. |
| image | [IImage](../../com.aspose.slides/iimage) | ภาพสำหรับส่งออก. |

**คืนค่า:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) อ็อบเจ็กต์สำหรับภาพ.
### add(String path, IVideo video) {#add-java.lang.String-com.aspose.slides.IVideo-}
```
public final IOutputFile add(String path, IVideo video)
```

เพิ่มองค์ประกอบผลลัพธ์สำหรับวิดีโอ.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| path | java.lang.String | เส้นทางผลลัพธ์. |
| video | [IVideo](../../com.aspose.slides/ivideo) | วิดีโอสำหรับส่งออก. |

**คืนค่า:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) อ็อบเจ็กต์สำหรับวิดีโอ.
### add(String path, IFontData fontData, int fontStyle) {#add-java.lang.String-com.aspose.slides.IFontData-int-}
```
public final IOutputFile add(String path, IFontData fontData, int fontStyle)
```

สร้างและเพิ่มองค์ประกอบไฟล์ผลลัพธ์สำหรับฟอนต์ที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| path | java.lang.String | เส้นทางไฟล์ที่ฟอนต์ผลลัพธ์จะถูกบันทึก. |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | ข้อมูลฟอนต์ที่ต้องเขียนไปยังผลลัพธ์. |
| fontStyle | int | สไตล์ของฟอนต์ (เช่น Regular, Bold, Italic). |

**คืนค่า:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - อินสแตนซ์ [IOutputFile](../../com.aspose.slides/ioutputfile) สำหรับฟอนต์ที่สร้างขึ้น.
### add(String path, String textContent) {#add-java.lang.String-java.lang.String-}
```
public final IOutputFile add(String path, String textContent)
```

เพิ่มองค์ประกอบผลลัพธ์สำหรับเนื้อหาข้อความ.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| path | java.lang.String | เส้นทางผลลัพธ์. |
| textContent | java.lang.String | เนื้อหาที่จะส่งออก. |

**คืนค่า:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) อ็อบเจ็กต์สำหรับเนื้อหาข้อความ.
### bindResource(IOutputFile outputFile, Object obj) {#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-}
```
public final void bindResource(IOutputFile outputFile, Object obj)
```

ผูกทรัพยากรกับไฟล์ผลลัพธ์.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| outputFile | [IOutputFile](../../com.aspose.slides/ioutputfile) | ไฟล์ผลลัพธ์. |
| obj | java.lang.Object | อ็อบเจ็กต์ทรัพยากร. |
### getResourcePath(Object obj) {#getResourcePath-java.lang.Object-}
```
public final String getResourcePath(Object obj)
```

คืนค่าเส้นทางสำหรับทรัพยากรที่กำหนด.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| obj | java.lang.Object | อ็อบเจ็กต์ทรัพยากร. |

**คืนค่า:**
java.lang.String - เส้นทางของทรัพยากร.