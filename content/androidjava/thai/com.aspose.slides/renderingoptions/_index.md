---
title: RenderingOptions
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: ให้ตัวเลือกที่ควบคุมวิธีการแสดงผลของงานนำเสนอ/สไลด์.
type: docs
url: /th/com.aspose.slides/renderingoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**All Implemented Interfaces:**
[com.aspose.slides.IRenderingOptions](../../com.aspose.slides/irenderingoptions)
```
public class RenderingOptions extends SaveOptions implements IRenderingOptions
```

ให้ตัวเลือกที่ควบคุมวิธีการแสดงผลของงานนำเสนอ/สไลด์

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      IRenderingOptions renderingOpts = new RenderingOptions();
>      renderingOpts.getNotesCommentsLayouting().setNotesPosition(NotesPositions.BottomTruncated);
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

## คอนสตรัคเตอร์

| Constructor | Description |
| --- | --- |
| [RenderingOptions()](#RenderingOptions--) | คอนสตรัคเตอร์เริ่มต้น |
## เมธอด

| Method | Description |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | รับหรือกำหนดโหมดที่สไลด์ถูกจัดวางบนหน้าเมื่อส่งออกงานนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | รับหรือกำหนดโหมดที่สไลด์ถูกจัดวางบนหน้าเมื่อส่งออกงานนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |
| [getInkOptions()](#getInkOptions--) | ให้ตัวเลือกที่ควบคุมลักษณะของวัตถุ Ink ในเอกสารที่ส่งออก |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | รับหรือกำหนดค่าที่ระบุว่าข้อความจะถูกเรนเดอร์โดยไม่ใช้ ligatures |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | รับหรือกำหนดค่าที่ระบุว่าข้อความจะถูกเรนเดอร์โดยไม่ใช้ ligatures |
### RenderingOptions() {#RenderingOptions--}
```
public RenderingOptions()
```


คอนสตรัคเตอร์เริ่มต้น

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
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```


รับหรือกำหนดโหมดที่สไลด์ถูกจัดวางบนหน้าเมื่อส่งออกงานนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```


ให้ตัวเลือกที่ควบคุมลักษณะของวัตถุ Ink ในเอกสารที่ส่งออก แบบอ่านอย่างเดียว [IInkOptions](../../com.aspose.slides/iinkoptions)

**คืนค่า:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```


รับหรือกำหนดค่าที่ระบุว่าข้อความจะถูกเรนเดอร์โดยไม่ใช้ ligatures เมื่อกำหนดเป็น true ligatures จะถูกปิดใช้งานในผลลัพธ์ที่เรนเดอร์ โดยค่าเริ่มต้นคุณสมบัตินี้จะเป็น false

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
public final void setDisableFontLigatures(boolean value)
```


รับหรือกำหนดค่าที่ระบุว่าข้อความจะถูกเรนเดอร์โดยไม่ใช้ ligatures เมื่อกำหนดเป็น true ligatures จะถูกปิดใช้งานในผลลัพธ์ที่เรนเดอร์ โดยค่าเริ่มต้นคุณสมบัตินี้จะเป็น false

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |