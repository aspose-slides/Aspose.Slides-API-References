---
title: HtmlOptions
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงตัวเลือกการส่งออก HTML.
type: docs
url: /th/com.aspose.slides/htmloptions/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**ส่วนต่อประสานที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.IHtmlOptions](../../com.aspose.slides/ihtmloptions)
```
public class HtmlOptions extends SaveOptions implements IHtmlOptions
```

แสดงตัวเลือกการส่งออก HTML.
## ผู้สร้าง

| ผู้สร้าง | คำอธิบาย |
| --- | --- |
| [HtmlOptions(ILinkEmbedController linkEmbedController)](#HtmlOptions-com.aspose.slides.ILinkEmbedController-) | สร้างอ็อบเจ็กต์ HtmlOptions ใหม่โดยระบุคอลแบ็ก |
| [HtmlOptions()](#HtmlOptions--) | สร้างอ็อบเจ็กต์ HtmlOptions ใหม่สำหรับการบันทึกเป็นไฟล์ HTML เดียว |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | รับหรือกำหนดโหมดที่สไลด์ถูกจัดวางบนหน้าเมื่อส่งออกงานนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | รับหรือกำหนดโหมดที่สไลด์ถูกจัดวางบนหน้าเมื่อส่งออกงานนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |
| [getInkOptions()](#getInkOptions--) | ให้ตัวเลือกที่ควบคุมลักษณะของอ็อบเจ็กต์ Ink ในเอกสารที่ส่งออก |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | ระบุว่าเอกสารที่สร้างควรรวมสไลด์ที่ซ่อนอยู่หรือไม่ |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | ระบุว่าเอกสารที่สร้างควรรวมสไลด์ที่ซ่อนอยู่หรือไม่ |
| [getHtmlFormatter()](#getHtmlFormatter--) | รับหรือกำหนดเทมเพลต HTML |
| [setHtmlFormatter(IHtmlFormatter value)](#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-) | รับหรือกำหนดเทมเพลต HTML |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | รับหรือกำหนดค่าที่บ่งบอกว่าข้อความถูกเรนเดอร์โดยไม่ใช้ลิแกเจอร์ |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | รับหรือกำหนดค่าที่บ่งบอกว่าข้อความถูกเรนเดอร์โดยไม่ใช้ลิแกเจอร์ |
| [getSlideImageFormat()](#getSlideImageFormat--) | รับหรือกำหนดตัวเลือกรูปแบบภาพสไลด์ |
| [setSlideImageFormat(ISlideImageFormat value)](#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-) | รับหรือกำหนดตัวเลือกรูปแบบภาพสไลด์ |
| [getJpegQuality()](#getJpegQuality--) | รับหรือกำหนดค่าที่กำหนดคุณภาพของภาพ JPEG ภายในเอกสาร PDF |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | รับหรือกำหนดค่าที่กำหนดคุณภาพของภาพ JPEG ภายในเอกสาร PDF |
| [getPicturesCompression()](#getPicturesCompression--) | แสดงระดับการบีบอัดรูปภาพ |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | แสดงระดับการบีบอัดรูปภาพ |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | ตัวบ่งชี้บูลีนระบุว่าตำแหน่งที่ถูกครอบตัดยังคงเป็นส่วนหนึ่งของเอกสารหรือไม่ |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | ตัวบ่งชี้บูลีนระบุว่าตำแหน่งที่ถูกครอบตัดยังคงเป็นส่วนหนึ่งของเอกสารหรือไม่ |
| [getSvgResponsiveLayout()](#getSvgResponsiveLayout--) | true เพื่อยกเว้นแอตริบิวต์ width และ height จากคอนเทนเนอร์ svg - จะทำให้การจัดวางตอบสนอง |
| [setSvgResponsiveLayout(boolean value)](#setSvgResponsiveLayout-boolean-) | true เพื่อยกเว้นแอตริบิวต์ width และ height จากคอนเทนเนอร์ svg - จะทำให้การจัดวางตอบสนอง |

### HtmlOptions(ILinkEmbedController linkEmbedController) {#HtmlOptions-com.aspose.slides.ILinkEmbedController-}
```
public HtmlOptions(ILinkEmbedController linkEmbedController)
```

สร้างอ็อบเจ็กต์ HtmlOptions ใหม่โดยระบุคอลแบ็ก

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | อ็อบเจ็กต์คอลแบ็กที่ควบคุมการบันทึกโครงการ |

### HtmlOptions() {#HtmlOptions--}
```
public HtmlOptions()
```

สร้างอ็อบเจ็กต์ HtmlOptions ใหม่สำหรับการบันทึกเป็นไฟล์ HTML เดียว

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

รับหรือกำหนดโหมดที่สไลด์ถูกจัดวางบนหน้าเมื่อส่งออกงานนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**ส่งกลับ:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

รับหรือกำหนดโหมดที่สไลด์ถูกจัดวางบนหน้าเมื่อส่งออกงานนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

ให้ตัวเลือกที่ควบคุมลักษณะของอ็อบเจ็กต์ Ink ในเอกสารที่ส่งออก อ่านอย่างเดียว [IInkOptions](../../com.aspose.slides/iinkoptions)

**ส่งกลับ:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

ระบุว่าเอกสารที่สร้างควรรวมสไลด์ที่ซ่อนอยู่หรือไม่ ค่าเริ่มต้นคือ false

**ส่งกลับ:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

ระบุว่าเอกสารที่สร้างควรรวมสไลด์ที่ซ่อนอยู่หรือไม่ ค่าเริ่มต้นคือ false

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getHtmlFormatter() {#getHtmlFormatter--}
```
public final IHtmlFormatter getHtmlFormatter()
```

รับหรือกำหนดเทมเพลต HTML อ่าน/เขียน [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**ส่งกลับ:**
[IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
### setHtmlFormatter(IHtmlFormatter value) {#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-}
```
public final void setHtmlFormatter(IHtmlFormatter value)
```

รับหรือกำหนดเทมเพลต HTML อ่าน/เขียน [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter) |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

รับหรือกำหนดค่าที่บ่งบอกว่าข้อความถูกเรนเดอร์โดยไม่ใช้ลิแกเจอร์ เมื่อกำหนดเป็น true ลิแกเจอร์จะถูกปิดการใช้งานในผลลัพธ์ที่เรนเดอร์ โดยค่าเริ่มต้นคุณสมบัตินี้ตั้งเป็น false

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      options.setDisableFontLigatures(true);
>      pres.save("presentation.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**ส่งกลับ:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public final void setDisableFontLigatures(boolean value)
```

รับหรือกำหนดค่าที่บ่งบอกว่าข้อความถูกเรนเดอร์โดยไม่ใช้ลิแกเจอร์ เมื่อกำหนดเป็น true ลิแกเจอร์จะถูกปิดการใช้งานในผลลัพธ์ที่เรนเดอร์ โดยค่าเริ่มต้นคุณสมบัตินี้ตั้งเป็น false

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      options.setDisableFontLigatures(true);
>      pres.save("presentation.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getSlideImageFormat() {#getSlideImageFormat--}
```
public final ISlideImageFormat getSlideImageFormat()
```

รับหรือกำหนดตัวเลือกรูปแบบภาพสไลด์ อ่าน/เขียน [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**ส่งกลับ:**
[ISlideImageFormat](../../com.aspose.slides/islideimageformat)
### setSlideImageFormat(ISlideImageFormat value) {#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-}
```
public final void setSlideImageFormat(ISlideImageFormat value)
```

รับหรือกำหนดตัวเลือกรูปแบบภาพสไลด์ อ่าน/เขียน [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [ISlideImageFormat](../../com.aspose.slides/islideimageformat) |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
```

รับหรือกำหนดค่าที่กำหนดคุณภาพของภาพ JPEG ภายในเอกสาร PDF อ่าน/เขียน byte.

--------------------

มีผลเฉพาะเมื่อเอกสารมีภาพ JPEG

ใช้คุณสมบัตินี้เพื่อรับหรือกำหนดคุณภาพของภาพภายในเอกสารเมื่อบันทึกเป็นรูปแบบ PDF ค่าอาจอยู่ระหว่าง 0 ถึง 100 โดย 0 หมายถึงคุณภาพแย่ที่สุดแต่การบีบอัดสูงสุดและ 100 หมายถึงคุณภาพดีที่สุดแต่การบีบอัดน้อยที่สุด

ค่าเริ่มต้นคือ **95**.

**ส่งกลับ:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```

รับหรือกำหนดค่าที่กำหนดคุณภาพของภาพ JPEG ภายในเอกสาร PDF อ่าน/เขียน byte.

--------------------

มีผลเฉพาะเมื่อเอกสารมีภาพ JPEG

ใช้คุณสมบัตินี้เพื่อรับหรือกำหนดคุณภาพของภาพภายในเอกสารเมื่อบันทึกเป็นรูปแบบ PDF ค่าอาจอยู่ระหว่าง 0 ถึง 100 โดย 0 หมายถึงคุณภาพแย่ที่สุดแต่การบีบอัดสูงสุดและ 100 หมายถึงคุณภาพดีที่สุดแต่การบีบอัดน้อยที่สุด

ค่าเริ่มต้นคือ **95**.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```

แสดงระดับการบีบอัดรูปภาพ

**ส่งกลับ:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public final void setPicturesCompression(int value)
```

แสดงระดับการบีบอัดรูปภาพ

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public final boolean getDeletePicturesCroppedAreas()
```

ตัวบ่งชี้บูลีนระบุว่าตำแหน่งที่ถูกครอบตัดยังคงเป็นส่วนหนึ่งของเอกสารหรือไม่ หากเป็น true จะลบส่วนที่ถูกครอบ ถ้าเป็น false จะถูกจัดเก็บไว้ในเอกสาร (ซึ่งอาจทำให้ไฟล์ใหญ่ขึ้น)

**ส่งกลับ:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```

ตัวบ่งชี้บูลีนระบุว่าตำแหน่งที่ถูกครอบตัดยังคงเป็นส่วนหนึ่งของเอกสารหรือไม่ หากเป็น true จะลบส่วนที่ถูกครอบ ถ้าเป็น false จะถูกจัดเก็บไว้ในเอกสาร (ซึ่งอาจทำให้ไฟล์ใหญ่ขึ้น)

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getSvgResponsiveLayout() {#getSvgResponsiveLayout--}
```
public final boolean getSvgResponsiveLayout()
```

true เพื่อยกเว้นแอตริบิวต์ width และ height จากคอนเทนเนอร์ svg - จะทำให้การจัดวางตอบสนอง False - มิฉะนั้น อ่าน/เขียน boolean.

**ส่งกลับ:**
boolean
### setSvgResponsiveLayout(boolean value) {#setSvgResponsiveLayout-boolean-}
```
public final void setSvgResponsiveLayout(boolean value)
```

true เพื่อยกเว้นแอตริบิวต์ width และ height จากคอนเทนเนอร์ svg - จะทำให้การจัดวางตอบสนอง False - มิฉะนั้น อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |