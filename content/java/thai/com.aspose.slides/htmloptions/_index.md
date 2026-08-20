---
title: HtmlOptions
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงตัวเลือกการส่งออก HTML.
type: docs
url: /th/com.aspose.slides/htmloptions/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IHtmlOptions](../../com.aspose.slides/ihtmloptions)
```
public class HtmlOptions extends SaveOptions implements IHtmlOptions
```

แสดงตัวเลือกการส่งออก HTML
## ตัวสร้าง

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [HtmlOptions(ILinkEmbedController linkEmbedController)](#HtmlOptions-com.aspose.slides.ILinkEmbedController-) | สร้างวัตถุ HtmlOptions ใหม่โดยระบุ callback. |
| [HtmlOptions()](#HtmlOptions--) | สร้างวัตถุ HtmlOptions ใหม่สำหรับการบันทึกเป็นไฟล์ HTML เดียว. |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | รับหรือกำหนดโหมดที่สไลด์ถูกวางบนหน้าขณะส่งออกการนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | รับหรือกำหนดโหมดที่สไลด์ถูกวางบนหน้าขณะส่งออกการนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | จัดหาออปชันที่ควบคุมลักษณะของวัตถุ Ink ในเอกสารที่ส่งออก. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | ระบุว่าควรรวมสไลด์ที่ซ่อนอยู่ในเอกสารที่สร้างหรือไม่. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | ระบุว่าควรรวมสไลด์ที่ซ่อนอยู่ในเอกสารที่สร้างหรือไม่. |
| [getHtmlFormatter()](#getHtmlFormatter--) | คืนค่า或กำหนดเทมเพลต HTML. |
| [setHtmlFormatter(IHtmlFormatter value)](#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-) | คืนค่า或กำหนดเทมเพลต HTML. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | รับหรือกำหนดค่าที่บ่งบอกว่าข้อความจะถูกเรนเดอร์โดยไม่ใช้ ligatures. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | รับหรือกำหนดค่าที่บ่งบอกว่าข้อความจะถูกเรนเดอร์โดยไม่ใช้ ligatures. |
| [getSlideImageFormat()](#getSlideImageFormat--) | คืนค่า或กำหนดออปชันรูปแบบภาพสไลด์. |
| [setSlideImageFormat(ISlideImageFormat value)](#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-) | คืนค่า或กำหนดออปชันรูปแบบภาพสไลด์. |
| [getJpegQuality()](#getJpegQuality--) | คืนค่า或กำหนดค่าที่กำหนดคุณภาพของภาพ JPEG ในเอกสาร PDF. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | คืนค่า或กำหนดค่าที่กำหนดคุณภาพของภาพ JPEG ในเอกสาร PDF. |
| [getPicturesCompression()](#getPicturesCompression--) | แสดงระดับการบีบอัดของรูปภาพ |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | แสดงระดับการบีบอัดของรูปภาพ |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | ธงบูลีนบ่งชี้ว่าพื้นที่ที่ถูกตัดเหลืออยู่เป็นส่วนหนึ่งของเอกสารหรือไม่. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | ธงบูลีนบ่งชี้ว่าพื้นที่ที่ถูกตัดเหลืออยู่เป็นส่วนหนึ่งของเอกสารหรือไม่. |
| [getSvgResponsiveLayout()](#getSvgResponsiveLayout--) | ตั้งค่าเป็น true เพื่อยกเลิกแอตทริบิวต์ width และ height จากคอนเทนเนอร์ svg - ซึ่งจะทำให้เลย์เอาต์ตอบสนองได้. |
| [setSvgResponsiveLayout(boolean value)](#setSvgResponsiveLayout-boolean-) | ตั้งค่าเป็น true เพื่อยกเลิกแอตทริบิวต์ width และ height จากคอนเทนเนอร์ svg - ซึ่งจะทำให้เลย์เอาต์ตอบสนองได้. |
### HtmlOptions(ILinkEmbedController linkEmbedController) {#HtmlOptions-com.aspose.slides.ILinkEmbedController-}
```
public HtmlOptions(ILinkEmbedController linkEmbedController)
```

สร้างวัตถุ HtmlOptions ใหม่โดยระบุ callback.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | วัตถุ callback ที่ควบคุมการบันทึกโครงการ. |

### HtmlOptions() {#HtmlOptions--}
```
public HtmlOptions()
```

สร้างวัตถุ HtmlOptions ใหม่สำหรับการบันทึกเป็นไฟล์ HTML เดียว.

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

รับหรือกำหนดโหมดที่สไลด์ถูกวางบนหน้าขณะส่งออกการนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

**คืนค่า:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

รับหรือกำหนดโหมดที่สไลด์ถูกวางบนหน้าขณะส่งออกการนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

จัดหาออปชันที่ควบคุมลักษณะของวัตถุ Ink ในเอกสารที่ส่งออก. อ่านอย่างเดียว [IInkOptions](../../com.aspose.slides/iinkoptions)

**คืนค่า:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

ระบุว่าควรรวมสไลด์ที่ซ่อนอยู่ในเอกสารที่สร้างหรือไม่. ค่าเริ่มต้นคือ false.

**คืนค่า:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

ระบุว่าควรรวมสไลด์ที่ซ่อนอยู่ในเอกสารที่สร้างหรือไม่. ค่าเริ่มต้นคือ false.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getHtmlFormatter() {#getHtmlFormatter--}
```
public final IHtmlFormatter getHtmlFormatter()
```

คืนค่า或กำหนดเทมเพลต HTML. อ่าน/เขียน [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**คืนค่า:**
[IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
### setHtmlFormatter(IHtmlFormatter value) {#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-}
```
public final void setHtmlFormatter(IHtmlFormatter value)
```

คืนค่า或กำหนดเทมเพลต HTML. อ่าน/เขียน [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter) |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

รับหรือกำหนดค่าที่บ่งบอกว่าข้อความจะถูกเรนเดอร์โดยไม่ใช้ ligatures. เมื่อกำหนดเป็น true จะปิดการใช้ ligatures ในผลลัพธ์ที่เรนเดอร์. ค่าเริ่มต้นคือ false.

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

**คืนค่า:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public final void setDisableFontLigatures(boolean value)
```

รับหรือกำหนดค่าที่บ่งบอกว่าข้อความจะถูกเรนเดอร์โดยไม่ใช้ ligatures. เมื่อกำหนดเป็น true จะปิดการใช้ ligatures ในผลลัพธ์ที่เรนเดอร์. ค่าเริ่มต้นคือ false.

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
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getSlideImageFormat() {#getSlideImageFormat--}
```
public final ISlideImageFormat getSlideImageFormat()
```

คืนค่า或กำหนดออปชันรูปแบบภาพสไลด์. อ่าน/เขียน [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**คืนค่า:**
[ISlideImageFormat](../../com.aspose.slides/islideimageformat)
### setSlideImageFormat(ISlideImageFormat value) {#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-}
```
public final void setSlideImageFormat(ISlideImageFormat value)
```

คืนค่า或กำหนดออปชันรูปแบบภาพสไลด์. อ่าน/เขียน [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [ISlideImageFormat](../../com.aspose.slides/islideimageformat) |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
```

คืนค่า或กำหนดค่าที่กำหนดคุณภาพของภาพ JPEG ในเอกสาร PDF. อ่าน/เขียน byte.

--------------------

มีผลเฉพาะเมื่อเอกสารมีภาพ JPEG.

ใช้คุณสมบัตินี้เพื่อรับหรือกำหนดคุณภาพของภาพภายในเอกสารเมื่อบันทึกเป็น PDF. ค่าจะอยู่ระหว่าง 0 ถึง 100 โดย 0 หมายถึงคุณภาพแย่ที่สุดแต่การบีบอัดสูงสุดและ 100 หมายถึงคุณภาพดีที่สุดแต่การบีบอัดต่ำสุด.

ค่าเริ่มต้นคือ **95**.

**คืนค่า:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```

คืนค่า或กำหนดค่าที่กำหนดคุณภาพของภาพ JPEG ในเอกสาร PDF. อ่าน/เขียน byte.

--------------------

มีผลเฉพาะเมื่อเอกสารมีภาพ JPEG.

ใช้คุณสมบัตินี้เพื่อรับหรือกำหนดคุณภาพของภาพภายในเอกสารเมื่อบันทึกเป็น PDF. ค่าจะอยู่ระหว่าง 0 ถึง 100 โดย 0 หมายถึงคุณภาพแย่ที่สุดแต่การบีบอัดสูงสุดและ 100 หมายถึงคุณภาพดีที่สุดแต่การบีบอัดต่ำสุด.

ค่าเริ่มต้นคือ **95**.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```

แสดงระดับการบีบอัดของรูปภาพ

**คืนค่า:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public final void setPicturesCompression(int value)
```

แสดงระดับการบีบอัดของรูปภาพ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public final boolean getDeletePicturesCroppedAreas()
```

ธงบูลีนบ่งชี้ว่าพื้นที่ที่ถูกตัดเหลืออยู่เป็นส่วนหนึ่งของเอกสารหรือไม่. หากตั้งค่าเป็น true พื้นที่ที่ถูกตัดจะถูกลบ, หากตั้งค่าเป็น false พื้นที่จะถูกทำให้เป็นส่วนหนึ่งของเอกสาร (ซึ่งอาจทำให้ไฟล์ใหญ่ขึ้น)

**คืนค่า:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```

ธงบูลีนบ่งชี้ว่าพื้นที่ที่ถูกตัดเหลืออยู่เป็นส่วนหนึ่งของเอกสารหรือไม่. หากตั้งค่าเป็น true พื้นที่ที่ถูกตัดจะถูกลบ, หากตั้งค่าเป็น false พื้นที่จะถูกทำให้เป็นส่วนหนึ่งของเอกสาร (ซึ่งอาจทำให้ไฟล์ใหญ่ขึ้น)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getSvgResponsiveLayout() {#getSvgResponsiveLayout--}
```
public final boolean getSvgResponsiveLayout()
```

ตั้งค่าเป็น true เพื่อยกเลิกแอตทริบิวต์ width และ height จากคอนเทนเนอร์ svg - ซึ่งจะทำให้เลย์เอาต์ตอบสนองได้. ตั้งค่าเป็น false - มิฉะนั้น. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setSvgResponsiveLayout(boolean value) {#setSvgResponsiveLayout-boolean-}
```
public final void setSvgResponsiveLayout(boolean value)
```

ตั้งค่าเป็น true เพื่อยกเลิกแอตทริบิวต์ width และ height จากคอนเทนเนอร์ svg - ซึ่งจะทำให้เลย์เอาต์ตอบสนองได้. ตั้งค่าเป็น false - มิฉะนั้น. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |