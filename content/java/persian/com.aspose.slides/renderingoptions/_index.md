---
title: RenderingOptions
second_title: مرجع API Aspose.Slides برای Java
description: گزینه‌هایی را فراهم می‌کند که نحوه رندر یک ارائه/اسلاید را کنترل می‌کند.
type: docs
url: /fa/com.aspose.slides/renderingoptions/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IRenderingOptions](../../com.aspose.slides/irenderingoptions)
```
public class RenderingOptions extends SaveOptions implements IRenderingOptions
```

گزینه‌هایی را فراهم می‌کند که نحوه رندر کردن یک ارائه/اسلاید را کنترل می‌کند.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      IRenderingOptions renderingOpts = new RenderingOptions();
>      renderingOpts.getNotesCommentsLayouting().setNotesPosition(NotesPositions.BottomTruncated);
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

## سازندگان

| سازنده | توضیح |
| --- | --- |
| [RenderingOptions()](#RenderingOptions--) | سازنده پیش‌فرض. |
## متدها

| متد | توضیح |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | دریافت یا تنظیم حالت قرارگیری اسلایدها بر روی صفحه هنگام خروجی‌گیری از یک ارائه [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | دریافت یا تنظیم حالت قرارگیری اسلایدها بر روی صفحه هنگام خروجی‌گیری از یک ارائه [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | گزینه‌هایی را فراهم می‌کند که ظاهر اشیای Ink را در سند خروجی کنترل می‌کند. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | دریافت یا تنظیم مقدار نشان‌دهنده این که آیا متن بدون استفاده از حروف ترکیبی رندر می‌شود یا خیر. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | دریافت یا تنظیم مقدار نشان‌دهنده این که آیا متن بدون استفاده از حروف ترکیبی رندر می‌شود یا خیر. |
### RenderingOptions() {#RenderingOptions--}
```
public RenderingOptions()
```


سازنده پیش‌فرض.

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```


دریافت یا تنظیم حالت قرارگیری اسلایدها بر روی صفحه هنگام خروجی‌گیری از یک ارائه [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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


**بازگشت:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```


دریافت یا تنظیم حالت قرارگیری اسلایدها بر روی صفحه هنگام خروجی‌گیری از یک ارائه [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```


گزینه‌هایی را فراهم می‌کند که ظاهر اشیای Ink را در سند خروجی کنترل می‌کند. فقط-خواندنی [IInkOptions](../../com.aspose.slides/iinkoptions)

**بازگشت:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```


دریافت یا تنظیم مقدار نشان‌دهنده این که آیا متن بدون استفاده از حروف ترکیبی رندر می‌شود یا خیر. وقتی به true تنظیم شود، حروف ترکیبی در خروجی رندر شده غیرفعال خواهند شد. به طور پیش‌فرض، این ویژگی به false تنظیم شده است.

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


**بازگشت:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public final void setDisableFontLigatures(boolean value)
```


دریافت یا تنظیم مقدار نشان‌دهنده این که آیا متن بدون استفاده از حروف ترکیبی رندر می‌شود یا خیر. وقتی به true تنظیم شود، حروف ترکیبی در خروجی رندر شده غیرفعال خواهند شد. به طور پیش‌فرض، این ویژگی به false تنظیم شده است.

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


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |