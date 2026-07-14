---
title: EmbeddedWoffFontsHtmlController
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: คลาสตัวควบคุมการจัดรูปแบบที่ใช้สำหรับฝังฟอนต์ในรูปแบบ WOFF
type: docs
url: /th/com.aspose.slides/embeddedwofffontshtmlcontroller/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.IEmbeddedWoffFontsHtmlController](../../com.aspose.slides/iembeddedwofffontshtmlcontroller)
```
public class EmbeddedWoffFontsHtmlController implements IEmbeddedWoffFontsHtmlController
```

คลาสตัวควบคุมการจัดรูปแบบที่ใช้สำหรับฝังฟอนต์ในรูปแบบ WOFF
## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| --- | --- |
| [EmbeddedWoffFontsHtmlController()](#EmbeddedWoffFontsHtmlController--) | Creates new instance. |
| [EmbeddedWoffFontsHtmlController(IHtmlFormattingController controller)](#EmbeddedWoffFontsHtmlController-com.aspose.slides.IHtmlFormattingController-) | Creates new instance. |
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) |  |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) |  |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) |  |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) |  |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) |  |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) |  |
### EmbeddedWoffFontsHtmlController() {#EmbeddedWoffFontsHtmlController--}
```
public EmbeddedWoffFontsHtmlController()
```


สร้างอินสแตนซ์ใหม่.

### EmbeddedWoffFontsHtmlController(IHtmlFormattingController controller) {#EmbeddedWoffFontsHtmlController-com.aspose.slides.IHtmlFormattingController-}
```
public EmbeddedWoffFontsHtmlController(IHtmlFormattingController controller)
```


สร้างอินสแตนซ์ใหม่.

พารามิเตอร์:
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| controller | [IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller) | ตัวควบคุมการจัดรูปแบบ HTML. |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public final void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```


เรียกเพื่อเขียนส่วนหัวของเอกสาร html. เรียกใช้ครั้งเดียวต่อการแปลงงานนำเสนอ.

พารามิเตอร์:
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) |  |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public final void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```


เรียกเพื่อเขียนส่วนท้ายของเอกสาร html. เรียกใช้ครั้งเดียวต่อการแปลงงานนำเสนอ.

พารามิเตอร์:
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) |  |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public final void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```


เรียกเพื่อเขียนส่วนหัวของสไลด์ html. เรียกใช้ครั้งเดียวต่อแต่ละสไลด์.

พารามิเตอร์:
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| slide | [ISlide](../../com.aspose.slides/islide) |  |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public final void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```


เรียกเพื่อเขียนส่วนท้ายของสไลด์ html. เรียกใช้ครั้งเดียวต่อแต่ละสไลด์.

พารามิเตอร์:
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| slide | [ISlide](../../com.aspose.slides/islide) |  |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeStart(IHtmlGenerator generator, IShape shape)
```


เรียกก่อนการเรนเดอร์ของรูปทรง. เรียกใช้ครั้งเดียวต่อแต่ละรูปทรง. หากฟังก์ชันนี้เขียนอะไรลงใน generator การสร้างรูปภาพสไลด์ปัจจุบันจะสิ้นสุด, แทรกส่วน html ที่เพิ่มเข้ามาและเริ่มสร้างภาพใหม่บนส่วนก่อนหน้า.

พารามิเตอร์:
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```


เรียกก่อนการเรนเดอร์ของรูปทรง. เรียกใช้ครั้งเดียวต่อแต่ละรูปทรง. หากฟังก์ชันนี้เขียนอะไรลงใน generator การสร้างรูปภาพสไลด์ปัจจุบันจะสิ้นสุด, แทรกส่วน html ที่เพิ่มเข้ามาและเริ่มสร้างภาพใหม่บนส่วนก่อนหน้า.

พารามิเตอร์:
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |