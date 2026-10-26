---
title: IHtmlOptions
second_title: Aspose.Slides สำหรับ Java อ้างอิง API
description: เป็นตัวเลือกการส่งออก HTML.
type: docs
url: /th/com.aspose.slides/ihtmloptions/
---
**อินเทอร์เฟซที่ใช้งานทั้งหมด:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IHtmlOptions extends ISaveOptions
```

เป็นตัวเลือกสำหรับการส่งออก HTML.
## วิธีการ

| Method | Description |
| --- | --- |
| [getHtmlFormatter()](#getHtmlFormatter--) | คืนค่า หรือกำหนดเทมเพลต HTML. |
| [setHtmlFormatter(IHtmlFormatter value)](#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-) | คืนค่า หรือกำหนดเทมเพลต HTML. |
| [getSlideImageFormat()](#getSlideImageFormat--) | คืนค่า หรือกำหนดตัวเลือกรูปแบบภาพสไลด์. |
| [setSlideImageFormat(ISlideImageFormat value)](#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-) | คืนค่า หรือกำหนดตัวเลือกรูปแบบภาพสไลด์. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | ระบุว่าเอกสารที่สร้างควรรวมสไลด์ที่ซ่อนอยู่หรือไม่. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | ระบุว่าเอกสารที่สร้างควรรวมสไลด์ที่ซ่อนอยู่หรือไม่. |
| [getJpegQuality()](#getJpegQuality--) | คืนค่า หรือกำหนดค่าที่กำหนดคุณภาพของภาพ JPEG ภายในเอกสาร PDF. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | คืนค่า หรือกำหนดค่าที่กำหนดคุณภาพของภาพ JPEG ภายในเอกสาร PDF. |
| [getPicturesCompression()](#getPicturesCompression--) | แสดงระดับการบีบอัดรูปภาพ อ่าน/เขียน [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | แสดงระดับการบีบอัดรูปภาพ อ่าน/เขียน [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)). |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | แฟล็กบูลีนบ่งชี้ว่าพื้นที่ที่ถูกตัดต่อจะยังคงอยู่เป็นส่วนหนึ่งของเอกสารหรือไม่. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | แฟล็กบูลีนบ่งชี้ว่าพื้นที่ที่ถูกตัดต่อจะยังคงอยู่เป็นส่วนหนึ่งของเอกสารหรือไม่. |
| [getSvgResponsiveLayout()](#getSvgResponsiveLayout--) | ตั้งค่าเป็น true เพื่อไม่รวมแอตทริบิวต์ความกว้างและความสูงจากคอนเทนเนอร์ SVG - ซึ่งจะทำให้เลย์เอาต์ตอบสนองต่อขนาดหน้าจอ. |
| [setSvgResponsiveLayout(boolean value)](#setSvgResponsiveLayout-boolean-) | ตั้งค่าเป็น true เพื่อไม่รวมแอตทริบิวต์ความกว้างและความสูงจากคอนเทนเนอร์ SVG - ซึ่งจะทำให้เลย์เอาต์ตอบสนองต่อขนาดหน้าจอ. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | รับหรือกำหนดค่าที่บ่งบอกว่าข้อความถูกเรนเดอร์โดยไม่ใช้ลิเกเจอร์. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | รับหรือกำหนดค่าที่บ่งบอกว่าข้อความถูกเรนเดอร์โดยไม่ใช้ลิเกเจอร์. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | รับหรือกำหนดโหมดที่สไลด์จะวางบนหน้าเมื่อส่งออกงานนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | รับหรือกำหนดโหมดที่สไลด์จะวางบนหน้าเมื่อส่งออกงานนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | ให้ตัวเลือกที่ควบคุมลักษณะของวัตถุ Ink ในเอกสารที่ส่งออก. |

### getHtmlFormatter() {#getHtmlFormatter--}
```
public abstract IHtmlFormatter getHtmlFormatter()
```

คืนค่า หรือกำหนดเทมเพลต HTML. อ่าน/เขียน [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**คืนค่า:**
[IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
### setHtmlFormatter(IHtmlFormatter value) {#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-}
```
public abstract void setHtmlFormatter(IHtmlFormatter value)
```

คืนค่า หรือกำหนดเทมเพลต HTML. อ่าน/เขียน [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter) |  |

### getSlideImageFormat() {#getSlideImageFormat--}
```
public abstract ISlideImageFormat getSlideImageFormat()
```

คืนค่า หรือกำหนดตัวเลือกรูปแบบภาพสไลด์. อ่าน/เขียน [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**คืนค่า:**
[ISlideImageFormat](../../com.aspose.slides/islideimageformat)
### setSlideImageFormat(ISlideImageFormat value) {#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-}
```
public abstract void setSlideImageFormat(ISlideImageFormat value)
```

คืนค่า หรือกำหนดตัวเลือกรูปแบบภาพสไลด์. อ่าน/เขียน [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | [ISlideImageFormat](../../com.aspose.slides/islideimageformat) |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

ระบุว่าเอกสารที่สร้างควรรวมสไลด์ที่ซ่อนอยู่หรือไม่. ค่าเริ่มต้นคือ false.

**คืนค่า:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

ระบุว่าเอกสารที่สร้างควรรวมสไลด์ที่ซ่อนอยู่หรือไม่. ค่าเริ่มต้นคือ false.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract byte getJpegQuality()
```

คืนค่า หรือกำหนดค่าที่กำหนดคุณภาพของภาพ JPEG ภายในเอกสาร PDF. อ่าน/เขียน byte.

--------------------

มีผลเฉพาะเมื่อเอกสารมีภาพ JPEG.

ใช้คุณสมบัตินี้เพื่อรับหรือกำหนดคุณภาพของภาพภายในเอกสารเมื่อบันทึกเป็นรูปแบบ PDF. ค่าอาจอยู่ระหว่าง 0 ถึง 100 โดยที่ 0 หมายถึงคุณภาพแย่ที่สุดแต่บีบอัดสูงสุดและ 100 หมายถึงคุณภาพดีที่สุดแต่บีบอัดต่ำสุด.

ค่าเริ่มต้นคือ **95**.

**คืนค่า:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```

คืนค่า หรือกำหนดค่าที่กำหนดคุณภาพของภาพ JPEG ภายในเอกสาร PDF. อ่าน/เขียน byte.

--------------------

มีผลเฉพาะเมื่อเอกสารมีภาพ JPEG.

ใช้คุณสมบัตินี้เพื่อรับหรือกำหนดคุณภาพของภาพภายในเอกสารเมื่อบันทึกเป็นรูปแบบ PDF. ค่าอาจอยู่ระหว่าง 0 ถึง 100 โดยที่ 0 หมายถึงคุณภาพแย่ที่สุดแต่บีบอัดสูงสุดและ 100 หมายถึงคุณภาพดีที่สุดแต่บีบอัดต่ำสุด.

ค่าเริ่มต้นคือ **95**.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
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
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public abstract boolean getDeletePicturesCroppedAreas()
```

แฟล็กบูลีนบ่งชี้ว่าพื้นที่ที่ถูกตัดต่อจะยังคงอยู่เป็นส่วนหนึ่งของเอกสารหรือไม่. หาก true พื้นที่ที่ถูกตัดต่อจะถูกลบ, หาก false จะถูกจัดเก็บในเอกสาร (อาจทำให้ไฟล์ใหญ่ขึ้น) อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public abstract void setDeletePicturesCroppedAreas(boolean value)
```

แฟล็กบูลีนบ่งชี้ว่าพื้นที่ที่ถูกตัดต่อจะยังคงอยู่เป็นส่วนหนึ่งของเอกสารหรือไม่. หาก true พื้นที่ที่ถูกตัดต่อจะถูกลบ, หาก false จะถูกจัดเก็บในเอกสาร (อาจทำให้ไฟล์ใหญ่ขึ้น) อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | boolean |  |

### getSvgResponsiveLayout() {#getSvgResponsiveLayout--}
```
public abstract boolean getSvgResponsiveLayout()
```

ตั้งค่าเป็น true เพื่อไม่รวมแอตทริบิวต์ความกว้างและความสูงจากคอนเทนเนอร์ SVG - ซึ่งจะทำให้เลย์เอาต์ตอบสนองต่อขนาดหน้าจอ. false - ไม่เช่นนั้น. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setSvgResponsiveLayout(boolean value) {#setSvgResponsiveLayout-boolean-}
```
public abstract void setSvgResponsiveLayout(boolean value)
```

ตั้งค่าเป็น true เพื่อไม่รวมแอตทริบิวต์ความกว้างและความสูงจากคอนเทนเนอร์ SVG - ซึ่งจะทำให้เลย์เอาต์ตอบสนองต่อขนาดหน้าจอ. false - ไม่เช่นนั้น. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | boolean |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

รับหรือกำหนดค่าที่บ่งบอกว่าข้อความถูกเรนเดอร์โดยไม่ใช้ลิเกเจอร์. เมื่อกำหนดเป็น true, ลิเกเจอร์จะถูกปิดใช้งานในการแสดงผล. โดยค่าเริ่มต้น, คุณสมบัตินี้ตั้งเป็น false.

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

รับหรือกำหนดค่าที่บ่งบอกว่าข้อความถูกเรนเดอร์โดยไม่ใช้ลิเกเจอร์. เมื่อกำหนดเป็น true, ลิเกเจอร์จะถูกปิดใช้งานในการแสดงผล. โดยค่าเริ่มต้น, คุณสมบัตินี้ตั้งเป็น false.

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
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | boolean |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

รับหรือกำหนดโหมดที่สไลด์จะวางบนหน้าเมื่อส่งออกงานนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

รับหรือกำหนดโหมดที่สไลด์จะวางบนหน้าเมื่อส่งออกงานนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

ให้ตัวเลือกที่ควบคุมลักษณะของวัตถุ Ink ในเอกสารที่ส่งออก. อ่านอย่างเดียว [IInkOptions](../../com.aspose.slides/iinkoptions)

**คืนค่า:**
[IInkOptions](../../com.aspose.slides/iinkoptions)