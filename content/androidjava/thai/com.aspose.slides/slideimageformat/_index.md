---
title: SlideImageFormat
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: กำหนดรูปแบบที่ภาพสไลด์จะถูกบันทึกสำหรับการนำเสนอในการส่งออกเป็น HTML.
type: docs
url: /th/com.aspose.slides/slideimageformat/
---
**การสืบทอด:**
java.lang.Object

**ทุกอินเทอร์เฟซที่ทำไว้:**
[com.aspose.slides.ISlideImageFormat](../../com.aspose.slides/islideimageformat)
```
public class SlideImageFormat implements ISlideImageFormat
```

กำหนดรูปแบบที่ภาพสไลด์จะถูกบันทึกสำหรับการนำเสนอในการส่งออกเป็น HTML.

## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [SlideImageFormat()](#SlideImageFormat--) |  |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [svg(SVGOptions options)](#svg-com.aspose.slides.SVGOptions-) | สไลด์ควรถูกแปลงเป็นรูปแบบ SVG. |
| [bitmap(float scale, int imageFormat)](#bitmap-float-int-) | สไลด์ควรถูกแปลงเป็นภาพแบบแรสเตอร์. |

### SlideImageFormat() {#SlideImageFormat--}
```
public SlideImageFormat()
```

### svg(SVGOptions options) {#svg-com.aspose.slides.SVGOptions-}
```
public static SlideImageFormat svg(SVGOptions options)
```

สไลด์ควรถูกแปลงเป็นรูปแบบ SVG.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| options | [SVGOptions](../../com.aspose.slides/svgoptions) | ตัวเลือกสำหรับการส่งออก SVG. |

**ผลลัพธ์:**
[SlideImageFormat](../../com.aspose.slides/slideimageformat) - วัตถุ [SlideImageFormat](../../com.aspose.slides/slideimageformat)

### bitmap(float scale, int imageFormat) {#bitmap-float-int-}
```
public static SlideImageFormat bitmap(float scale, int imageFormat)
```

สไลด์ควรถูกแปลงเป็นภาพแบบแรสเตอร์.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| scale | float | ปัจจัยที่ใช้ในการปรับขนาดภาพผลลัพธ์. |
| imageFormat | int | รูปแบบของภาพที่ได้ (เช่น PNG, JPEG). |

**ผลลัพธ์:**
[SlideImageFormat](../../com.aspose.slides/slideimageformat) -