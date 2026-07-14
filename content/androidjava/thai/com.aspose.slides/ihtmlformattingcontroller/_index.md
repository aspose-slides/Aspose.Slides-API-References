---
title: IHtmlFormattingController
second_title: Aspose.Slides for Android via Java API Reference
description: ควบคุมการสร้างไฟล์ HTML.
type: docs
url: /th/com.aspose.slides/ihtmlformattingcontroller/
---```
public interface IHtmlFormattingController
```

ควบคุมการสร้างไฟล์ HTML.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | เรียกเพื่อเขียนส่วนหัวของเอกสาร HTML. |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | เรียกเพื่อเขียนส่วนท้ายของเอกสาร HTML. |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | เรียกเพื่อเขียนส่วนหัวของสไลด์ HTML. |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | เรียกเพื่อเขียนส่วนท้ายของสไลด์ HTML. |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | เรียกก่อนการเรนเดอร์ของรูปร่าง. |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | เรียกก่อนการเรนเดอร์ของรูปร่าง. |
### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```

เรียกเพื่อเขียนส่วนหัวของเอกสาร HTML. เรียกหนึ่งครั้งต่อการแปลงงานนำเสนอ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | วัตถุผลลัพธ์. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | งานนำเสนอที่กำลังเรนเดอร์อยู่ในขณะนี้. |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```

เรียกเพื่อเขียนส่วนท้ายของเอกสาร HTML. เรียกหนึ่งครั้งต่อการแปลงงานนำเสนอ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | วัตถุผลลัพธ์. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | งานนำเสนอที่กำลังเรนเดอร์อยู่ในขณะนี้. |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```

เรียกเพื่อเขียนส่วนหัวของสไลด์ HTML. เรียกหนึ่งครั้งต่อแต่ละสไลด์.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | วัตถุผลลัพธ์. |
| slide | [ISlide](../../com.aspose.slides/islide) | สไลด์ที่กำลังเรนเดอร์อยู่ในขณะนี้. |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```

เรียกเพื่อเขียนส่วนท้ายของสไลด์ HTML. เรียกหนึ่งครั้งต่อแต่ละสไลด์.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | วัตถุผลลัพธ์. |
| slide | [ISlide](../../com.aspose.slides/islide) | สไลด์ที่กำลังเรนเดอร์อยู่ในขณะนี้. |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeStart(IHtmlGenerator generator, IShape shape)
```

เรียกก่อนการเรนเดอร์ของรูปร่าง. เรียกหนึ่งครั้งต่อแต่ละรูปร่าง. หากฟังก์ชันนี้เขียนอะไรลงใน generator การสร้างภาพสไลด์ปัจจุบันจะเสร็จสิ้น, ส่วน HTML ที่เพิ่มเข้าไปจะถูกแทรกและภาพใหม่จะเริ่มต้นเหนือภาพเดิม.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | วัตถุผลลัพธ์. |
| shape | [IShape](../../com.aspose.slides/ishape) | รูปร่างที่กำลังจะเรนเดอร์. |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```

เรียกก่อนการเรนเดอร์ของรูปร่าง. เรียกหนึ่งครั้งต่อแต่ละรูปร่าง. หากฟังก์ชันนี้เขียนอะไรลงใน generator การสร้างภาพสไลด์ปัจจุบันจะเสร็จสิ้น, ส่วน HTML ที่เพิ่มเข้าไปจะถูกแทรกและภาพใหม่จะเริ่มต้นเหนือภาพเดิม.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | วัตถุผลลัพธ์. |
| shape | [IShape](../../com.aspose.slides/ishape) | รูปร่างที่เรนเดอร์เป็นสุดท้าย. |