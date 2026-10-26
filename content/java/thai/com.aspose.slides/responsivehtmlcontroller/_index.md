---
title: ResponsiveHtmlController
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: คอนโทรลเลอร์ HTML แบบตอบสนอง
type: docs
url: /th/com.aspose.slides/responsivehtmlcontroller/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IResponsiveHtmlController](../../com.aspose.slides/iresponsivehtmlcontroller)
```
public class ResponsiveHtmlController implements IResponsiveHtmlController
```

Responsive HTML Controller
## Constructors

| Constructor | Description |
| --- | --- |
| [ResponsiveHtmlController()](#ResponsiveHtmlController--) | สร้างอินสแตนซ์ใหม่ |
| [ResponsiveHtmlController(IHtmlFormattingController controller)](#ResponsiveHtmlController-com.aspose.slides.IHtmlFormattingController-) | สร้างอินสแตนซ์ใหม่ |
## Methods

| Method | Description |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) |  |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) |  |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) |  |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) |  |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) |  |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) |  |
### ResponsiveHtmlController() {#ResponsiveHtmlController--}
```
public ResponsiveHtmlController()
```


สร้างอินสแตนซ์ใหม่

### ResponsiveHtmlController(IHtmlFormattingController controller) {#ResponsiveHtmlController-com.aspose.slides.IHtmlFormattingController-}
```
public ResponsiveHtmlController(IHtmlFormattingController controller)
```


สร้างอินสแตนซ์ใหม่

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| controller | [IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller) | ตัวควบคุมการฟอร์แมต HTML |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public final void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```


ถูกเรียกเพื่อเขียนส่วนหัวของเอกสาร html. ถูกเรียกหนึ่งครั้งต่อการแปลงการนำเสนอ.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) |  |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public final void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```


ถูกเรียกเพื่อเขียนส่วนท้ายของเอกสาร html. ถูกเรียกหนึ่งครั้งต่อการแปลงการนำเสนอ.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) |  |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public final void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```


ถูกเรียกเพื่อเขียนส่วนหัวของสไลด์ html. ถูกเรียกหนึ่งครั้งต่อแต่ละสไลด์.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| slide | [ISlide](../../com.aspose.slides/islide) |  |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public final void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```


ถูกเรียกเพื่อเขียนส่วนท้ายของสไลด์ html. ถูกเรียกหนึ่งครั้งต่อแต่ละสไลด์.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| slide | [ISlide](../../com.aspose.slides/islide) |  |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeStart(IHtmlGenerator generator, IShape shape)
```


ถูกเรียกก่อนการเรนเดอร์ของ shape. ถูกเรียกหนึ่งครั้งต่อแต่ละ shape. หากฟังก์ชันนี้เขียนอะไรลงใน generator, การสร้างภาพสไลด์ปัจจุบันจะเสร็จสิ้น, ส่วน html ที่เพิ่มจะถูกแทรกและภาพใหม่จะเริ่มต้นเหนือภาพเดิม.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```


ถูกเรียกก่อนการเรนเดอร์ของ shape. ถูกเรียกหนึ่งครั้งต่อแต่ละ shape. หากฟังก์ชันนี้เขียนอะไรลงใน generator, การสร้างภาพสไลด์ปัจจุบันจะเสร็จสิ้น, ส่วน html ที่เพิ่มจะถูกแทรกและภาพใหม่จะเริ่มต้นเหนือภาพเดิม.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |