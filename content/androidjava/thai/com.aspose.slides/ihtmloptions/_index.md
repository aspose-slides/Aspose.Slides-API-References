---
title: IHtmlOptions
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: เป็นตัวเลือกการส่งออก HTML.
type: docs
url: /th/com.aspose.slides/ihtmloptions/
---
**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IHtmlOptions extends ISaveOptions
```

เป็นตัวเลือกการส่งออก HTML
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getHtmlFormatter()](#getHtmlFormatter--) | รับหรือกำหนดแม่แบบ HTML. |
| [setHtmlFormatter(IHtmlFormatter value)](#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-) | รับหรือกำหนดแม่แบบ HTML. |
| [getSlideImageFormat()](#getSlideImageFormat--) | รับหรือกำหนดตัวเลือกรูปแบบภาพสไลด์. |
| [setSlideImageFormat(ISlideImageFormat value)](#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-) | รับหรือกำหนดตัวเลือกรูปแบบภาพสไลด์. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | ระบุว่าหนังสือที่สร้างควรรวมสไลด์ที่ซ่อนอยู่หรือไม่. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | ระบุว่าหนังสือที่สร้างควรรวมสไลด์ที่ซ่อนอยู่หรือไม่. |
| [getJpegQuality()](#getJpegQuality--) | รับหรือกำหนดค่าที่กำหนดคุณภาพของภาพ JPEG ภายในเอกสาร PDF. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | รับหรือกำหนดค่าที่กำหนดคุณภาพของภาพ JPEG ภายในเอกสาร PDF. |
| [getPicturesCompression()](#getPicturesCompression--) | แสดงระดับการบีบอัดรูปภาพ อ่าน/เขียน [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | แสดงระดับการบีบอัดรูปภาพ อ่าน/เขียน [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)). |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | แฟล็กแบบบูลีนบ่งชี้ว่าบริเวณที่ถูกตัดจะคงอยู่เป็นส่วนหนึ่งของเอกสารหรือไม่. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | แฟล็กแบบบูลีนบ่งชี้ว่าบริเวณที่ถูกตัดจะคงอยู่เป็นส่วนหนึ่งของเอกสารหรือไม่. |
| [getSvgResponsiveLayout()](#getSvgResponsiveLayout--) | True เพื่อยกเว้นแอตทริบิวต์ความกว้างและความสูงจากคอนเทนเนอร์ SVG - ซึ่งจะทำให้การจัดวางตอบสนองได้. |
| [setSvgResponsiveLayout(boolean value)](#setSvgResponsiveLayout-boolean-) | True เพื่อยกเว้นแอตทริบิวต์ความกว้างและความสูงจากคอนเทนเนอร์ SVG - ซึ่งจะทำให้การจัดวางตอบสนองได้. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | รับหรือกำหนดค่าที่บ่งชี้ว่าข้อความถูกแสดงโดยไม่ใช้ ligatures. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | รับหรือกำหนดค่าที่บ่งชี้ว่าข้อความถูกแสดงโดยไม่ใช้ ligatures. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | รับหรือกำหนดโหมดที่สไลด์ถูกจัดวางบนหน้าเมื่อส่งออกงานนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | รับหรือกำหนดโหมดที่สไลด์ถูกจัดวางบนหน้าเมื่อส่งออกงานนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | ให้ตัวเลือกที่ควบคุมรูปลักษณ์ของวัตถุ Ink ในเอกสารที่ส่งออก. |
### getHtmlFormatter() {#getHtmlFormatter--}
```
public abstract IHtmlFormatter getHtmlFormatter()
```


รับหรือกำหนดแม่แบบ HTML. อ่าน/เขียน [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**คืนค่า:**
[IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
### setHtmlFormatter(IHtmlFormatter value) {#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-}
```
public abstract void setHtmlFormatter(IHtmlFormatter value)
```


รับหรือกำหนดแม่แบบ HTML. อ่าน/เขียน [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter) |  |

### getSlideImageFormat() {#getSlideImageFormat--}
```
public abstract ISlideImageFormat getSlideImageFormat()
```


รับหรือกำหนดตัวเลือกรูปแบบภาพสไลด์. อ่าน/เขียน [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**คืนค่า:**
[ISlideImageFormat](../../com.aspose.slides/islideimageformat)
### setSlideImageFormat(ISlideImageFormat value) {#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-}
```
public abstract void setSlideImageFormat(ISlideImageFormat value)
```


รับหรือกำหนดตัวเลือกรูปแบบภาพสไลด์. อ่าน/เขียน [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [ISlideImageFormat](../../com.aspose.slides/islideimageformat) |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```


ระบุว่าหนังสือที่สร้างควรรวมสไลด์ที่ซ่อนอยู่หรือไม่. ค่าเริ่มต้นคือ false.

**คืนค่า:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```


ระบุว่าหนังสือที่สร้างควรรวมสไลด์ที่ซ่อนอยู่หรือไม่. ค่าเริ่มต้นคือ false.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract byte getJpegQuality()
```


รับหรือกำหนดค่าที่กำหนดคุณภาพของภาพ JPEG ภายในเอกสาร PDF. อ่าน/เขียน byte.

--------------------

มีผลเฉพาะเมื่อเอกสารมีภาพ JPEG

ใช้คุณสมบัตินี้เพื่อรับหรือกำหนดคุณภาพของภาพภายในเอกสารเมื่อบันทึกเป็น PDF. ค่าจะอยู่ระหว่าง 0 ถึง 100 โดย 0 หมายถึงคุณภาพต่ำสุดแต่การบีบอัดสูงสุดและ 100 หมายถึงคุณภาพดีที่สุดแต่การบีบอัดต่ำสุด.

ค่าเริ่มต้นคือ **95**.

**คืนค่า:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```


รับหรือกำหนดค่าที่กำหนดคุณภาพของภาพ JPEG ภายในเอกสาร PDF. อ่าน/เขียน byte.

--------------------

มีผลเฉพาะเมื่อเอกสารมีภาพ JPEG

ใช้คุณสมบัตินี้เพื่อรับหรือกำหนดคุณภาพของภาพภายในเอกสารเมื่อบันทึกเป็น PDF. ค่าจะอยู่ระหว่าง 0 ถึง 100 โดย 0 หมายถึงคุณภาพต่ำสุดแต่การบีบอัดสูงสุดและ 100 หมายถึงคุณภาพดีที่สุดแต่การบีบอัดต่ำสุด.

ค่าเริ่มต้นคือ **95**.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public abstract int getPicturesCompression()
```


แสดงระดับการบีบอัดรูปภาพ อ่าน/เขียน [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)).

**คืนค่า:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```


แสดงระดับการบีบอัดรูปภาพ อ่าน/เขียน [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public abstract boolean getDeletePicturesCroppedAreas()
```


แฟล็กแบบบูลีนบ่งชี้ว่าบริเวณที่ถูกตัดจะคงอยู่เป็นส่วนหนึ่งของเอกสารหรือไม่. หากเป็น true จะลบบริเวณที่ถูกตัดออก; หากเป็น false จะทำการซีเรียลไลซ์ในเอกสาร (ซึ่งอาจทำให้ไฟล์ใหญ่ขึ้น) อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public abstract void setDeletePicturesCroppedAreas(boolean value)
```


แฟล็กแบบบูลีนบ่งชี้ว่าบริเวณที่ถูกตัดจะคงอยู่เป็นส่วนหนึ่งของเอกสารหรือไม่. หากเป็น true จะลบบริเวณที่ถูกตัดออก; หากเป็น false จะทำการซีเรียลไลซ์ในเอกสาร (ซึ่งอาจทำให้ไฟล์ใหญ่ขึ้น) อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getSvgResponsiveLayout() {#getSvgResponsiveLayout--}
```
public abstract boolean getSvgResponsiveLayout()
```


True เพื่อยกเว้นแอตทริบิวต์ความกว้างและความสูงจากคอนเทนเนอร์ SVG - ซึ่งจะทำให้การจัดวางตอบสนองได้. False - ในกรณีอื่น. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setSvgResponsiveLayout(boolean value) {#setSvgResponsiveLayout-boolean-}
```
public abstract void setSvgResponsiveLayout(boolean value)
```


True เพื่อยกเว้นแอตทริบิวต์ความกว้างและความสูงจากคอนเทนเนอร์ SVG - ซึ่งจะทำให้การจัดวางตอบสนองได้. False - ในกรณีอื่น. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```


รับหรือกำหนดค่าที่บ่งชี้ว่าข้อความถูกแสดงโดยไม่ใช้ ligatures. เมื่อกำหนดเป็น true ligatures จะถูกปิดในผลลัพธ์ที่เรนเดอร์. ค่าเริ่มต้นคือ false.

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
public abstract void setDisableFontLigatures(boolean value)
```


รับหรือกำหนดค่าที่บ่งชี้ว่าข้อความถูกแสดงโดยไม่ใช้ ligatures. เมื่อกำหนดเป็น true ligatures จะถูกปิดในผลลัพธ์ที่เรนเดอร์. ค่าเริ่มต้นคือ false.

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

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```


รับหรือกำหนดโหมดที่สไลด์ถูกจัดวางบนหน้าเมื่อส่งออกงานนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```


รับหรือกำหนดโหมดที่สไลด์ถูกจัดวางบนหน้าเมื่อส่งออกงานนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
public abstract IInkOptions getInkOptions()
```


ให้ตัวเลือกที่ควบคุมรูปลักษณ์ของวัตถุ Ink ในเอกสารที่ส่งออก. อ่านเท่านั้น [IInkOptions](../../com.aspose.slides/iinkoptions)

**คืนค่า:**
[IInkOptions](../../com.aspose.slides/iinkoptions)