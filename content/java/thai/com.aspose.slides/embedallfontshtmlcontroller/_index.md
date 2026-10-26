---
title: EmbedAllFontsHtmlController
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: คลาสตัวควบคุมการจัดรูปแบบที่ใช้สำหรับฝังฟอนต์ทั้งหมดของงานนำเสนอในรูปแบบ WOFF.
type: docs
url: /th/com.aspose.slides/embedallfontshtmlcontroller/
---
**การสืบทอด:**  
java.lang.Object

**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**  
[com.aspose.slides.IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller)  
```
public class EmbedAllFontsHtmlController implements IHtmlFormattingController
```

คลาสคอนโทรลเลอร์การจัดรูปแบบที่ใช้สำหรับฝังฟอนต์ทั้งหมดของงานนำเสนอในรูปแบบ WOFF.  
## คอนสตรัคเตอร์

| Constructor | Description |
| --- | --- |
| [EmbedAllFontsHtmlController()](#EmbedAllFontsHtmlController--) | สร้างอินสแตนซ์ใหม่ |
| [EmbedAllFontsHtmlController(String[] fontNameExcludeList)](#EmbedAllFontsHtmlController-java.lang.String---) | สร้างอินสแตนซ์ใหม่ |

## เมธอด

| Method | Description |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | เรียกเพื่อเขียนส่วนหัวของเอกสาร html. |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | เรียกเพื่อเขียนส่วนท้ายของเอกสาร html. |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | เรียกเพื่อเขียนส่วนหัวของสไลด์ html. |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | เรียกเพื่อเขียนส่วนท้ายของสไลด์ html. |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | เรียกก่อนการเรนเดอร์ของ shape. |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | เรียกก่อนการเรนเดอร์ของ shape. |
| [writeAllFonts(IHtmlGenerator generator, IPresentation presentation)](#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | เขียนฟอนต์ทั้งหมดที่อยู่ใน [Presentation](../../com.aspose.slides/presentation). |
| [writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)](#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---) | เขียนข้อมูลเป็น base64 ลงใน HTML document เอง |

### EmbedAllFontsHtmlController() {#EmbedAllFontsHtmlController--}
```
public EmbedAllFontsHtmlController()
```

สร้างอินสแตนซ์ใหม่

### EmbedAllFontsHtmlController(String[] fontNameExcludeList) {#EmbedAllFontsHtmlController-java.lang.String---}
```
public EmbedAllFontsHtmlController(String[] fontNameExcludeList)
```

สร้างอินสแตนซ์ใหม่

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontNameExcludeList | java.lang.String[] | ฟอนต์ที่ต้องการยกเว้นจากการฝัง |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```

เรียกเพื่อเขียนส่วนหัวของเอกสาร html. เรียกครั้งเดียวต่อการแปลงงานนำเสนอ.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | อ็อบเจ็กต์ output. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | งานนำเสนอที่กำลังเรนเดอร์อยู่ |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```

เรียกเพื่อเขียนส่วนท้ายของเอกสาร html. เรียกครั้งเดียวต่อการแปลงงานนำเสนอ.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | อ็อบเจ็กต์ output. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | งานนำเสนอที่กำลังเรนเดอร์อยู่ |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```

เรียกเพื่อเขียนส่วนหัวของสไลด์ html. เรียกครั้งเดียวต่อแต่ละสไลด์.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | อ็อบเจ็กต์ output. |
| slide | [ISlide](../../com.aspose.slides/islide) | สไลด์ที่กำลังเรนเดอร์อยู่ |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```

เรียกเพื่อเขียนส่วนท้ายของสไลด์ html. เรียกครั้งเดียวต่อแต่ละสไลด์.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | อ็อบเจ็กต์ output. |
| slide | [ISlide](../../com.aspose.slides/islide) | สไลด์ที่เรนเดอร์เป็นสุดท้าย |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeStart(IHtmlGenerator generator, IShape shape)
```

เรียกก่อนการเรนเดอร์ของ shape. เรียกครั้งเดียวต่อแต่ละ shape. หากฟังก์ชันนี้เขียนอะไรไปยัง generator, การสร้างรูปภาพสไลด์ปัจจุบันจะเสร็จสิ้น, ส่วน fragment ของ html ที่เพิ่มจะถูกแทรกและรูปภาพใหม่จะเริ่มต้นเหนือรูปภาพก่อนหน้า.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | อ็อบเจ็กต์ output. |
| shape | [IShape](../../com.aspose.slides/ishape) | shape ที่กำลังจะเรนเดอร์ |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```

เรียกก่อนการเรนเดอร์ของ shape. เรียกครั้งเดียวต่อแต่ละ shape. หากฟังก์ชันนี้เขียนอะไรไปยัง generator, การสร้างรูปภาพสไลด์ปัจจุบันจะเสร็จสิ้น, ส่วน fragment ของ html ที่เพิ่มจะถูกแทรกและรูปภาพใหม่จะเริ่มต้นเหนือรูปภาพก่อนหน้า.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | อ็อบเจ็กต์ output. |
| shape | [IShape](../../com.aspose.slides/ishape) | shape ที่เรนเดอร์เป็นสุดท้าย |

### writeAllFonts(IHtmlGenerator generator, IPresentation presentation) {#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeAllFonts(IHtmlGenerator generator, IPresentation presentation)
```

เขียนฟอนต์ทั้งหมดที่อยู่ใน [Presentation](../../com.aspose.slides/presentation).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | อ็อบเจ็กต์ output. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | งานนำเสนอที่กำลังเรนเดอร์อยู่ |

### writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData) {#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---}
```
public void writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)
```

เขียนข้อมูลเป็น base64 ลงใน HTML document เอง

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | ตัวสร้าง HTML |
| originalFont | [IFontData](../../com.aspose.slides/ifontdata) | ฟอนต์ที่จะทำการ serialize |
| substitutedFont | [IFontData](../../com.aspose.slides/ifontdata) | ฟอนต์ที่แทนที่ (หากมีการแทนที่ฟอนต์), null หากไม่มี |
| fontStyle | java.lang.String | สไตล์ของฟอนต์ |
| fontWeight | java.lang.String | น้ำหนักของฟอนต์ |
| fontData | byte[] | ข้อมูลฟอนต์ |