---
title: IHtmlFormattingController
second_title: Aspose.Slides สำหรับ Java API Reference
description: ควบคุมการสร้างไฟล์ html
type: docs
url: /th/com.aspose.slides/ihtmlformattingcontroller/
---```
public interface IHtmlFormattingController
```

ควบคุมการสร้างไฟล์ html
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | เรียกเพื่อเขียนส่วนหัวของเอกสาร html |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | เรียกเพื่อเขียนส่วนท้ายของเอกสาร html |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | เรียกเพื่อเขียนส่วนหัวของสไลด์ html |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | เรียกเพื่อเขียนส่วนท้ายของสไลด์ html |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | เรียกก่อนการเรนเดอร์ของ shape |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | เรียกก่อนการเรนเดอร์ของ shape |
### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```

เรียกเพื่อเขียนส่วนหัวของเอกสาร html เรียกครั้งเดียวต่อการแปลงพรีเซนเทชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | วัตถุผลลัพธ์ |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | พรีเซนเทชันที่กำลังเรนเดอร์อยู่ |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```

เรียกเพื่อเขียนส่วนท้ายของเอกสาร html เรียกครั้งเดียวต่อการแปลงพรีเซนเทชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | วัตถุผลลัพธ์ |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | พรีเซนเทชันที่กำลังเรนเดอร์อยู่ |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```

เรียกเพื่อเขียนส่วนหัวของสไลด์ html เรียกครั้งเดียวต่อแต่ละสไลด์

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | วัตถุผลลัพธ์ |
| slide | [ISlide](../../com.aspose.slides/islide) | สไลด์ที่กำลังเรนเดอร์อยู่ |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```

เรียกเพื่อเขียนส่วนท้ายของสไลด์ html เรียกครั้งเดียวต่อแต่ละสไลด์

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | วัตถุผลลัพธ์ |
| slide | [ISlide](../../com.aspose.slides/islide) | สไลด์ที่กำลังเรนเดอร์อยู่ |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeStart(IHtmlGenerator generator, IShape shape)
```

เรียกก่อนการเรนเดอร์ของ shape เรียกครั้งเดียวต่อแต่ละ shape หากฟังก์ชันนี้เขียนอะไรไปยัง generator การสร้างภาพสไลด์ปัจจุบันจะเสร็จสิ้น ส่วนประกอบ html ที่เพิ่มเข้ามาจะถูกแทรกและภาพใหม่จะเริ่มต้นที่ด้านบนของภาพก่อนหน้า

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | วัตถุผลลัพธ์ |
| shape | [IShape](../../com.aspose.slides/ishape) | shape ที่กำลังจะเรนเดอร์ |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```

เรียกก่อนการเรนเดอร์ของ shape เรียกครั้งเดียวต่อแต่ละ shape หากฟังก์ชันนี้เขียนอะไรไปยัง generator การสร้างภาพสไลด์ปัจจุบันจะเสร็จสิ้น ส่วนประกอบ html ที่เพิ่มเข้ามาจะถูกแทรกและภาพใหม่จะเริ่มต้นที่ด้านบนของภาพก่อนหน้า

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | วัตถุผลลัพธ์ |
| shape | [IShape](../../com.aspose.slides/ishape) | shape ที่เรนเดอร์เป็นล่าสุด |