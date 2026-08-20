---
title: IRenderingOptions
second_title: Aspose.Slides สำหรับ Java เอกสารอ้างอิง API
description: ให้ตัวเลือกที่ควบคุมการเรนเดอร์งานนำเสนอ/สไลด์
type: docs
url: /th/com.aspose.slides/irenderingoptions/
---
**ส่วนต่อประสานที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IRenderingOptions extends ISaveOptions
```

ให้ตัวเลือกที่ควบคุมการแสดงผลของงานนำเสนอ/สไลด์

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      IRenderingOptions renderingOpts = new RenderingOptions();
>      NotesCommentsLayoutingOptions notesCommentsLayoutingOptions = new NotesCommentsLayoutingOptions();
>      notesCommentsLayoutingOptions.setNotesPosition(NotesPositions.BottomTruncated);
>      renderingOpts.setSlidesLayoutOptions(notesCommentsLayoutingOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(renderingOpts), "PNG", new File("pres-Original.png"));
> 
>      renderingOpts.setDefaultRegularFont("Arial Black");
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(renderingOpts), "PNG", new File("pres-ArialBlackDefault.png"));
> 
>      renderingOpts.setDefaultRegularFont("Arial Narrow");
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(renderingOpts), "PNG", new File("pres-ArialNarrowDefault.png"));
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## เมธอด

| Method | Description |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | รับหรือกำหนดโหมดที่สไลด์ถูกวางบนหน้าเมื่อส่งออกงานนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | รับหรือกำหนดโหมดที่สไลด์ถูกวางบนหน้าเมื่อส่งออกงานนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | ให้ตัวเลือกที่ควบคุมลักษณะของอ็อบเจ็กต์ Ink ในเอกสารที่ส่งออก |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | รับหรือกำหนดค่าที่บ่งชี้ว่าข้อความถูกเรนเดอร์โดยไม่ใช้ลิการเจอร์ |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | รับหรือกำหนดค่าที่บ่งชี้ว่าข้อความถูกเรนเดอร์โดยไม่ใช้ลิการเจอร์ |
### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

รับหรือกำหนดโหมดที่สไลด์ถูกวางบนหน้าเมื่อส่งออกงานนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
> 
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintSlideNumbers(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      BufferedImage[] handoutSlides = pres.getThumbnails(options);
>      for (int index = 0; index < handoutSlides.length; index++)
>      {
>          ImageIO.write(handoutSlides[index], "PNG", new java.io.File("handout-" + index + ".png"));
>      }
>  } catch (IOException e) {
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

รับหรือกำหนดโหมดที่สไลด์ถูกวางบนหน้าเมื่อส่งออกงานนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
> 
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintSlideNumbers(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      BufferedImage[] handoutSlides = pres.getThumbnails(options);
>      for (int index = 0; index < handoutSlides.length; index++)
>      {
>          ImageIO.write(handoutSlides[index], "PNG", new java.io.File("handout-" + index + ".png"));
>      }
>  } catch (IOException e) {
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

ให้ตัวเลือกที่ควบคุมลักษณะของอ็อบเจ็กต์ Ink ในเอกสารที่ส่งออก อ่านอย่างเดียว [IInkOptions](../../com.aspose.slides/iinkoptions)

**คืนค่า:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

รับหรือกำหนดค่าที่บ่งชี้ว่าข้อความถูกเรนเดอร์โดยไม่ใช้ลิการเจอร์ เมื่อกำหนดเป็น true ลิการเจอร์จะถูกปิดในผลลัพธ์ที่เรนเดอร์ โดยค่าเริ่มต้นคุณสมบัตินี้ตั้งเป็น false

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      options.setDisableFontLigatures(true);
> 
>      IImage[] renderedSlides = pres.getImages(options);
>      for (int index = 0; index < renderedSlides.length; index++)
>      {
>          IImage slideImage = renderedSlides[index];
>          slideImage.save("slide-" + index + ".png");
>      }
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

รับหรือกำหนดค่าที่บ่งชี้ว่าข้อความถูกเรนเดอร์โดยไม่ใช้ลิการเจอร์ เมื่อกำหนดเป็น true ลิการเจอร์จะถูกปิดในผลลัพธ์ที่เรนเดอร์โดยค่าเริ่มต้นคุณสมบัตินี้ตั้งเป็น false

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      options.setDisableFontLigatures(true);
> 
>      IImage[] renderedSlides = pres.getImages(options);
>      for (int index = 0; index < renderedSlides.length; index++)
>      {
>          IImage slideImage = renderedSlides[index];
>          slideImage.save("slide-" + index + ".png");
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |