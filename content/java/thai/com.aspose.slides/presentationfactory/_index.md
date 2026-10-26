---
title: PresentationFactory
second_title: อ้างอิง API Aspose.Slides สำหรับ Java
description: อนุญาตให้สร้างงานนำเสนอผ่านอินเทอร์เฟซ COM
type: docs
url: /th/com.aspose.slides/presentationfactory/
---
**การสืบทอด:**  
java.lang.Object

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**  
[com.aspose.slides.IPresentationFactory](../../com.aspose.slides/ipresentationfactory)  
```
public class PresentationFactory implements IPresentationFactory
```

อนุญาตให้สร้างงานนำเสนอผ่านอินเทอร์เฟซ COM

--------------------

> ```
> The following example shows how to checking a Presentation Format.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  System.out.println(info.getLoadFormat()); // PPTX
>  IPresentationInfo info2 = PresentationFactory.getInstance().getPresentationInfo("pres.ppt");
>  System.out.println(info2.getLoadFormat()); // PPT
>  IPresentationInfo info3 = PresentationFactory.getInstance().getPresentationInfo("pres.odp");
>  System.out.println(info3.getLoadFormat()); // ODP
>  
>  The following example shows how to getting the properties of a Presentation.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  System.out.println(props.getCreatedTime());
>  System.out.println(props.getSubject());
>  System.out.println(props.getTitle());
>  // ..
>  
>  The following example shows how to updating the properties of a Presentation.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  props.setTitle("My title");
>  info.updateDocumentProperties(props);
> ```

## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [PresentationFactory()](#PresentationFactory--) |  |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getInstance()](#getInstance--) | Presentation factory อินสแตนซ์สเตติก |
| [createPresentation()](#createPresentation--) | สร้าง Presentation ใหม่ |
| [createPresentation(ILoadOptions options)](#createPresentation-com.aspose.slides.ILoadOptions-) | สร้าง Presentation ใหม่พร้อมตัวเลือกการโหลดเพิ่มเติม |
| [getPresentationInfo(String file)](#getPresentationInfo-java.lang.String-) | สร้างอ็อบเจ็กต์ PresentationInfo ใหม่จากไฟล์และผูก Presentation กับมัน |
| [getPresentationInfo(InputStream stream)](#getPresentationInfo-java.io.InputStream-) | สร้างอ็อบเจ็กต์ PresentationInfo ใหม่จากสตรีมและผูก Presentation กับมัน |
| [readPresentation(byte[] data)](#readPresentation-byte---) | อ่าน Presentation ที่มีอยู่จากอาเรย์ |
| [readPresentation(byte[] data, ILoadOptions options)](#readPresentation-byte---com.aspose.slides.ILoadOptions-) | อ่าน Presentation ที่มีอยู่จากอาเรย์พร้อมตัวเลือกการโหลดเพิ่มเติม |
| [readPresentation(InputStream stream)](#readPresentation-java.io.InputStream-) | อ่าน Presentation ที่มีอยู่จากสตรีม |
| [readPresentation(InputStream stream, ILoadOptions options)](#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-) | อ่าน Presentation ที่มีอยู่จากสตรีมพร้อมตัวเลือกการโหลดเพิ่มเติม |
| [readPresentation(String file)](#readPresentation-java.lang.String-) | อ่าน Presentation ที่มีอยู่จากไฟล์ |
| [readPresentation(String file, ILoadOptions options)](#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-) | อ่าน Presentation ที่มีอยู่จากสตรีมพร้อมตัวเลือกการโหลดเพิ่มเติม |
| [getPresentationText(String file, int mode)](#getPresentationText-java.lang.String-int-) | ดึงข้อความดิบจากสไลด์ |
| [getPresentationText(InputStream stream, int mode)](#getPresentationText-java.io.InputStream-int-) | ดึงข้อความดิบจากสไลด์ |
| [getPresentationText(InputStream stream, int mode, ILoadOptions options)](#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-) | ดึงข้อความดิบจากสไลด์ |
### PresentationFactory() {#PresentationFactory--}
```
public PresentationFactory()
```

### getInstance() {#getInstance--}
```
public static PresentationFactory getInstance()
```

Presentation factory อินสแตนซ์สเตติก. อ่านอย่างเดียว [PresentationFactory](../../com.aspose.slides/presentationfactory).

**คืนค่า:**  
[PresentationFactory](../../com.aspose.slides/presentationfactory)
### createPresentation() {#createPresentation--}
```
public final IPresentation createPresentation()
```

สร้าง Presentation ใหม่.

**คืนค่า:**  
[IPresentation](../../com.aspose.slides/ipresentation) - Presentation ใหม่
### createPresentation(ILoadOptions options) {#createPresentation-com.aspose.slides.ILoadOptions-}
```
public final IPresentation createPresentation(ILoadOptions options)
```

สร้าง Presentation ใหม่พร้อมตัวเลือกการโหลดเพิ่มเติม

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | ตัวเลือกการโหลด |

**คืนค่า:**  
[IPresentation](../../com.aspose.slides/ipresentation) - Presentation ใหม่
### getPresentationInfo(String file) {#getPresentationInfo-java.lang.String-}
```
public final IPresentationInfo getPresentationInfo(String file)
```

สร้างอ็อบเจ็กต์ PresentationInfo ใหม่จากไฟล์และผูก Presentation กับมัน

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| file | java.lang.String | ไฟล์ Presentation |

**คืนค่า:**  
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - ข้อมูล Presentation ที่ผูกกับ Presentation
### getPresentationInfo(InputStream stream) {#getPresentationInfo-java.io.InputStream-}
```
public final IPresentationInfo getPresentationInfo(InputStream stream)
```

สร้างอ็อบเจ็กต์ PresentationInfo ใหม่จากสตรีมและผูก Presentation กับมัน. รับข้อมูลเกี่ยวกับ Presentation ในสตรีมที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.InputStream | สตรีม Presentation |

**คืนค่า:**  
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - ข้อมูล Presentation ที่ผูกกับ Presentation
### readPresentation(byte[] data) {#readPresentation-byte---}
```
public final IPresentation readPresentation(byte[] data)
```

อ่าน Presentation ที่มีอยู่จากอาเรย์

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| data | byte[] | อาเรย์สำหรับอ่าน |

**คืนค่า:**  
[IPresentation](../../com.aspose.slides/ipresentation) - Presentation ที่อ่าน
### readPresentation(byte[] data, ILoadOptions options) {#readPresentation-byte---com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(byte[] data, ILoadOptions options)
```

อ่าน Presentation ที่มีอยู่จากอาเรย์พร้อมตัวเลือกการโหลดเพิ่มเติม

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| data | byte[] | อาเรย์สำหรับอ่าน |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | ตัวเลือกการโหลด |

**คืนค่า:**  
[IPresentation](../../com.aspose.slides/ipresentation) - Presentation ที่อ่าน
### readPresentation(InputStream stream) {#readPresentation-java.io.InputStream-}
```
public final IPresentation readPresentation(InputStream stream)
```

อ่าน Presentation ที่มีอยู่จากสตรีม

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.InputStream | สตรีมสำหรับอ่าน |

**คืนค่า:**  
[IPresentation](../../com.aspose.slides/ipresentation) - Presentation ที่อ่าน
### readPresentation(InputStream stream, ILoadOptions options) {#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(InputStream stream, ILoadOptions options)
```

อ่าน Presentation ที่มีอยู่จากสตรีมพร้อมตัวเลือกการโหลดเพิ่มเติม

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.InputStream | สตรีมสำหรับอ่าน |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | ตัวเลือกการโหลด |

**คืนค่า:**  
[IPresentation](../../com.aspose.slides/ipresentation) - Presentation ที่อ่าน
### readPresentation(String file) {#readPresentation-java.lang.String-}
```
public final IPresentation readPresentation(String file)
```

อ่าน Presentation ที่มีอยู่จากไฟล์

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| file | java.lang.String | ชื่อไฟล์ |

**คืนค่า:**  
[IPresentation](../../com.aspose.slides/ipresentation) - Presentation ที่อ่าน
### readPresentation(String file, ILoadOptions options) {#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-}
```
public final IPPresentation readPresentation(String file, ILoadOptions options)
```

อ่าน Presentation ที่มีอยู่จากไฟล์พร้อมตัวเลือกการโหลดเพิ่มเติม

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| file | java.lang.String | ชื่อไฟล์ |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | ตัวเลือกการโหลด |

**คืนค่า:**  
[IPresentation](../../com.aspose.slides/ipresentation) - Presentation ที่อ่าน
### getPresentationText(String file, int mode) {#getPresentationText-java.lang.String-int-}
```
public final IPresentationText getPresentationText(String file, int mode)
```

ดึงข้อความดิบจากสไลด์

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| file | java.lang.String | ไฟล์อินพุต |
| mode | int | โหมดการสกัดข้อมูล |

**คืนค่า:**  
[IPresentationText](../../com.aspose.slides/ipresentationtext) - อินสแตนซ์ของ PresentationText ที่ประกอบด้วยอาร์เรย์ SlideText ซึ่งแสดงข้อความดิบของสไลด์
### getPresentationText(InputStream stream, int mode) {#getPresentationText-java.io.InputStream-int-}
```
public final IPresentationText getPresentationText(InputStream stream, int mode)
```

ดึงข้อความดิบจากสไลด์

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.InputStream | สตรีมอินพุต |
| mode | int | โหมดการสกัดข้อมูล |

**คืนค่า:**  
[IPresentationText](../../com.aspose.slides/ipresentationtext) - อินสแตนซ์ของ PresentationText ที่ประกอบด้วยอาร์เรย์ SlideText ซึ่งแสดงข้อความดิบของสไลด์
### getPresentationText(InputStream stream, int mode, ILoadOptions options) {#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-}
```
public final IPresentationText getPresentationText(InputStream stream, int mode, ILoadOptions options)
```

ดึงข้อความดิบจากสไลด์

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.InputStream | สตรีมอินพุต |
| mode | int | โหมดการสกัดข้อมูล |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | ตัวเลือกการโหลด |

**คืนค่า:**  
[IPresentationText](../../com.aspose.slides/ipresentationtext) - อินสแตนซ์ของ PresentationText ที่ประกอบด้วยอาร์เรย์ SlideText ซึ่งแสดงข้อความดิบของสไลด์