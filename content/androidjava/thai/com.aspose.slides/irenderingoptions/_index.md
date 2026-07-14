---
title: IRenderingOptions
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: ให้ตัวเลือกที่ควบคุมวิธีการแสดงผลงานนำเสนอ/สไลด์.
type: docs
url: /th/com.aspose.slides/irenderingoptions/
---
**ส่วนต่อประสานที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IRenderingOptions extends ISaveOptions
```

ให้ตัวเลือกที่ควบคุมวิธีการแสดงผลงานนำเสนอ/สไลด์.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      IRenderingOptions renderingOpts = new RenderingOptions();
>      NotesCommentsLayoutingOptions notesCommentsLayoutingOptions = new NotesCommentsLayoutingOptions();
>      notesCommentsLayoutingOptions.setNotesPosition(NotesPositions.BottomTruncated);
>      renderingOpts.setSlidesLayoutOptions(notesCommentsLayoutingOptions);
>      FileOutputStream out = new FileOutputStream("pres-Original.png");
>      pres.getSlides().get_Item(0).getThumbnail(renderingOpts).compress(android.graphics.Bitmap.CompressFormat.JPEG, 100, out);
>      out.flush();
>      out.close();
>      renderingOpts.setDefaultRegularFont("Arial Black");
>      FileOutputStream out = new FileOutputStream("pres-ArialBlackDefault.png");
>      pres.getSlides().get_Item(0).getThumbnail(renderingOpts).compress(android.graphics.Bitmap.CompressFormat.JPEG, 100, out);
>      out.flush();
>      out.close();
>      renderingOpts.setDefaultRegularFont("Arial Narrow");
>      FileOutputStream out = new FileOutputStream("pres-ArialNarrowDefault.png");
>      pres.getSlides().get_Item(0).getThumbnail(renderingOpts).compress(android.graphics.Bitmap.CompressFormat.JPEG, 100, out);
>      out.flush();
>      out.close();
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | รับหรือกำหนดโหมดที่สไลด์จะถูกวางบนหน้าเมื่อส่งออกงานนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | รับหรือกำหนดโหมดที่สไลด์จะถูกวางบนหน้าเมื่อส่งออกงานนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | ให้ตัวเลือกที่ควบคุมลักษณะของอ็อบเจ็กต์ Ink ในเอกสารที่ส่งออก. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | รับหรือกำหนดค่าที่บ่งบอกว่าข้อความจะถูกแสดงโดยไม่ใช้ลิแกเชอร์. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | รับหรือกำหนดค่าที่บ่งบอกว่าข้อความจะถูกแสดงโดยไม่ใช้ลิแกเชอร์. |
### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

รับหรือกำหนดโหมดที่สไลด์จะถูกวางบนหน้าเมื่อส่งออกงานนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
>      android.graphics.Bitmap[] handoutSlides = pres.getThumbnails(options);
>      for (int index = 0; index < handoutSlides.length; index++)
>      {
>          FileOutputStream out = new FileOutputStream("handout-" + index + ".png");
>          handoutSlides[index].compress(android.graphics.Bitmap.CompressFormat.PNG, 100, out);
>          out.flush();
>          out.close();
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

รับหรือกำหนดโหมดที่สไลด์จะถูกวางบนหน้าเมื่อส่งออกงานนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
>      android.graphics.Bitmap[] handoutSlides = pres.getThumbnails(options);
>      for (int index = 0; index < handoutSlides.length; index++)
>      {
>          FileOutputStream out = new FileOutputStream("handout-" + index + ".png");
>          handoutSlides[index].compress(android.graphics.Bitmap.CompressFormat.PNG, 100, out);
>          out.flush();
>          out.close();
>      }
>  } catch (IOException e) {
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
public abstract IInkOptions getInkOptions()
```

ให้ตัวเลือกที่ควบคุมลักษณะของอ็อบเจ็กต์ Ink ในเอกสารที่ส่งออก อ่านอย่างเดียว [IInkOptions](../../com.aspose.slides/iinkoptions)

**คืนค่า:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

รับหรือกำหนดค่าที่บ่งบอกว่าข้อความจะถูกแสดงโดยไม่ใช้ลิแกเชอร์. เมื่อกำหนดเป็น true, ลิแกเชอร์จะถูกปิดใช้งานในผลลัพธ์ที่แสดง. ค่าเริ่มต้นของคุณสมบัตินี้คือ false.

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

รับหรือกำหนดค่าที่บ่งบอกว่าข้อความจะถูกแสดงโดยไม่ใช้ลิแกเชอร์. เมื่อกำหนดเป็น true, ลิแกเชอร์จะถูกปิดใช้งานในผลลัพธ์ที่แสดง. ค่าเริ่มต้นของคุณสมบัตินี้คือ false.

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
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |