---
title: EmbedAllFontsHtmlController
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: คลาสตัวควบคุมการจัดรูปแบบที่ใช้สำหรับฝังฟอนต์การนำเสนอทั้งหมดในรูปแบบ WOFF.
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

คลาสตัวควบคุมการจัดรูปแบบที่ใช้สำหรับฝังฟอนต์การนำเสนอทั้งหมดในรูปแบบ WOFF

## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [EmbedAllFontsHtmlController()](#EmbedAllFontsHtmlController--) | สร้างอินสแตนซ์ใหม่ |
| [EmbedAllFontsHtmlController(String[] fontNameExcludeList)](#EmbedAllFontsHtmlController-java.lang.String---) | สร้างอินสแตนซ์ใหม่ |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | ถูกเรียกเพื่อเขียนส่วนหัวของเอกสาร html. |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | ถูกเรียกเพื่อเขียนส่วนท้ายของเอกสาร html. |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | ถูกเรียกเพื่อเขียนส่วนหัวของสไลด์ html. |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | ถูกเรียกเพื่อเขียนส่วนท้ายของสไลด์ html. |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | ถูกเรียกก่อนการแสดงผลของ shape. |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | ถูกเรียกก่อนการแสดงผลของ shape. |
| [writeAllFonts(IHtmlGenerator generator, IPresentation presentation)](#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | เขียนฟอนต์ทั้งหมดที่อยู่ใน [Presentation](../../com.aspose.slides/presentation). |
| [writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)](#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---) | เขียนข้อมูลเป็น base64 ลงในเอกสาร HTML เอง |

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
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| fontNameExcludeList | java.lang.String[] | ฟอนต์ที่ต้องการยกเว้นจากการฝัง |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```

ถูกเรียกเพื่อเขียนส่วนหัวของเอกสาร html. ถูกเรียกหนึ่งครั้งต่อการแปลงการนำเสนอ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | ออบเจ็กต์ผลลัพธ์. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | การนำเสนอที่กำลังถูกเรนเดอร์อยู่. |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```

ถูกเรียกเพื่อเขียนส่วนท้ายของเอกสาร html. ถูกเรียกหนึ่งครั้งต่อการแปลงการนำเสนอ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | ออบเจ็กต์ผลลัพธ์. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | การนำเสนอที่กำลังถูกเรนเดอร์อยู่. |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```

ถูกเรียกเพื่อเขียนส่วนหัวของสไลด์ html. ถูกเรียกหนึ่งครั้งต่อแต่ละสไลด์

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | ออบเจ็กต์ผลลัพธ์. |
| slide | [ISlide](../../com.aspose.slides/islide) | สไลด์ที่กำลังถูกเรนเดอร์อยู่. |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```

ถูกเรียกเพื่อเขียนส่วนท้ายของสไลด์ html. ถูกเรียกหนึ่งครั้งต่อแต่ละสไลด์

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | ออบเจ็กต์ผลลัพธ์. |
| slide | [ISlide](../../com.aspose.slides/islide) | สไลด์ที่กำลังถูกเรนเดอร์อยู่. |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeStart(IHtmlGenerator generator, IShape shape)
```

ถูกเรียกก่อนการแสดงผลของ shape. ถูกเรียกหนึ่งครั้งต่อแต่ละ shape. หากฟังก์ชันนี้เขียนอะไรลงใน generator, การสร้างภาพสไลด์ปัจจุบันจะเสร็จสิ้น, แทรกส่วน html ที่เพิ่มเข้าไปและภาพใหม่จะเริ่มต้นบนภาพก่อนหน้า.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | ออบเจ็กต์ผลลัพธ์. |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape ที่กำลังจะเรนเดอร์. |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```

ถูกเรียกก่อนการแสดงผลของ shape. ถูกเรียกหนึ่งครั้งต่อแต่ละ shape. หากฟังก์ชันนี้เขียนอะไรลงใน generator, การสร้างภาพสไลด์ปัจจุบันจะเสร็จสิ้น, แทรกส่วน html ที่เพิ่มเข้าไปและภาพใหม่จะเริ่มต้นบนภาพก่อนหน้า.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | ออบเจ็กต์ผลลัพธ์. |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape ที่เรนเดอร์เป็นอันสุดท้าย. |

### writeAllFonts(IHtmlGenerator generator, IPresentation presentation) {#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeAllFonts(IHtmlGenerator generator, IPresentation presentation)
```

เขียนฟอนต์ทั้งหมดที่อยู่ใน [Presentation](../../com.aspose.slides/presentation).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | ออบเจ็กต์ผลลัพธ์. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | การนำเสนอที่กำลังถูกเรนเดอร์อยู่. |

### writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData) {#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---}
```
public void writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)
```

เขียนข้อมูลเป็น base64 ลงในเอกสาร HTML เอง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | ตัวสร้าง HTML |
| originalFont | [IFontData](../../com.aspose.slides/ifontdata) | ฟอนต์ที่จะทำการซีเรียลไลซ์ |
| substitutedFont | [IFontData](../../com.aspose.slides/ifontdata) | ฟอนต์ที่แทนที่ (หากมีการแทนที่ฟอนต์), มิฉะนั้นเป็น null |
| fontStyle | java.lang.String | สไตล์ฟอนต์ |
| fontWeight | java.lang.String | น้ำหนักฟอนต์ |
| fontData | byte[] | ข้อมูลฟอนต์ |