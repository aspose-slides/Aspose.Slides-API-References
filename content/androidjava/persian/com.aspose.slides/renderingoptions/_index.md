---
title: RenderingOptions
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: گزینه‌هایی را فراهم می‌کند که نحوه رندر شدن ارائه/اسلاید را کنترل می‌کند.
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

گزینه‌هایی را فراهم می‌کند که نحوه رندر شدن ارائه/اسلاید را کنترل می‌کند.

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

## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [RenderingOptions()](#RenderingOptions--) | سازنده پیش‌فرض. |
## متدها

| متد | توضیح |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | حالت قرارگیری اسلایدها بر روی صفحه هنگام خروجی گرفتن از یک ارائه [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) را دریافت یا تنظیم می‌کند. |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | حالت قرارگیری اسلایدها بر روی صفحه هنگام خروجی گرفتن از یک ارائه [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) را دریافت یا تنظیم می‌کند. |
| [getInkOptions()](#getInkOptions--) | گزینه‌هایی را فراهم می‌کند که ظاهر اشیای Ink را در سند خروجی کنترل می‌کند. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | مقداری را که نشان می‌دهد متن بدون استفاده از لیگچرها رندر می‌شود، دریافت یا تنظیم می‌کند. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | مقداری را که نشان می‌دهد متن بدون استفاده از لیگچرها رندر می‌شود، دریافت یا تنظیم می‌کند. |
### RenderingOptions() {#RenderingOptions--}
```
public RenderingOptions()
```

سازنده پیش‌فرض.

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

حالت قرارگیری اسلایدها بر روی صفحه هنگام خروجی گرفتن از یک ارائه [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) را دریافت یا تنظیم می‌کند.

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


**بازگرداندن:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

حالت قرارگیری اسلایدها بر روی صفحه هنگام خروجی گرفتن از یک ارائه [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) را دریافت یا تنظیم می‌کند.

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


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

گزینه‌هایی را فراهم می‌کند که ظاهر اشیای Ink را در سند خروجی کنترل می‌کند. فقط-خواندنی [IInkOptions](../../com.aspose.slides/iinkoptions)

**بازگرداندن:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

مقداری را که نشان می‌دهد متن بدون استفاده از لیگچرها رندر می‌شود، دریافت یا تنظیم می‌کند. زمانی که به true تنظیم شود، لیگچرها در خروجی رندر شده غیرفعال خواهند شد. به‌طور پیش‌فرض، این ویژگی برابر false تنظیم شده است.

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


**بازگرداندن:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public final void setDisableFontLigatures(boolean value)
```

مقداری را که نشان می‌دهد متن بدون استفاده از لیگچرها رندر می‌شود، دریافت یا تنظیم می‌کند. زمانی که به true تنظیم شود، لیگچرها در خروجی رندر شده غیرفعال خواهند شد. به‌طور پیش‌فرض، این ویژگی برابر false تنظیم شده است.

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