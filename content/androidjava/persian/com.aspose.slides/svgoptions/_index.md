---
title: SVGOptions
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: نمایانگر گزینه‌های SVG است.
type: docs
url: /fa/com.aspose.slides/svgoptions/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**تمام اینترفیس‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ISVGOptions](../../com.aspose.slides/isvgoptions), java.lang.Cloneable
```
public final class SVGOptions extends SaveOptions implements ISVGOptions, Cloneable
```

نمایانگر گزینه‌های SVG است.
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [SVGOptions()](#SVGOptions--) | یک نمونه جدید از کلاس SVGOptions را مقداردهی اولیه می‌کند. |
| [SVGOptions(ILinkEmbedController linkEmbedController)](#SVGOptions-com.aspose.slides.ILinkEmbedController-) | یک نمونه جدید از کلاس SVGOptions را با تعیین شیء کنترل‌کننده تعبیه‌پیوند مقداردهی اولیه می‌کند. |
## متدها

| متد | توضیح |
| --- | --- |
| [getInkOptions()](#getInkOptions--) | گزینه‌هایی را فراهم می‌کند که ظاهر اشیای Ink را در سند صادرشده کنترل می‌کند. |
| [getUseFrameSize()](#getUseFrameSize--) | مشخص می‌کند که آیا قاب متن در یک ناحیه نمایشی گنجانده شود یا نه. |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | مشخص می‌کند که آیا قاب متن در یک ناحیه نمایشی گنجانده شود یا نه. |
| [getUseFrameRotation()](#getUseFrameRotation--) | مشخص می‌کند که آیا چرخش مشخص شکل هنگام رندر انجام شود یا نه. |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | مشخص می‌کند که آیا چرخش مشخص شکل هنگام رندر انجام شود یا نه. |
| [getVectorizeText()](#getVectorizeText--) | مشخص می‌کند که آیا متن در یک اسلاید به‌صورت گرافیک ذخیره شود یا نه. |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | مشخص می‌کند که آیا متن در یک اسلاید به‌صورت گرافیک ذخیره شود یا نه. |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | محدودیت وضوح پایین‌تر برای رستر‌سازی متافایل را برمی‌گرداند یا تنظیم می‌کند. |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | محدودیت وضوح پایین‌تر برای رستر‌سازی متافایل را برمی‌گرداند یا تنظیم می‌کند. |
| [getDisable3DText()](#getDisable3DText--) | مشخص می‌کند که آیا متن 3D در SVG غیرفعال باشد یا نه. |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | مشخص می‌کند که آیا متن 3D در SVG غیرفعال باشد یا نه. |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | تقسیم گرادیان‌های FromCornerX و FromCenter را غیرفعال می‌کند. |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | تقسیم گرادیان‌های FromCornerX و FromCenter را غیرفعال می‌کند. |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | SVG 1.1 توانایی تعریف حاشیه‌های داخلی برای نشانگرها را ندارد. |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | SVG 1.1 توانایی تعریف حاشیه‌های داخلی برای نشانگرها را ندارد. |
| [getDefault()](#getDefault--) | تنظیمات پیش‌فرض را برمی‌گرداند. |
| [getSimple()](#getSimple--) | تنظیمات برای ساده‌ترین و کوچک‌ترین تولید فایل SVG را برمی‌گرداند. |
| [getWYSIWYG()](#getWYSIWYG--) | تنظیمات برای دقیق‌ترین تولید فایل SVG را برمی‌گرداند. |
| [getJpegQuality()](#getJpegQuality--) | کیفیت رمزگذاری JPEG را تعیین می‌کند. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | کیفیت رمزگذاری JPEG را تعیین می‌کند. |
| [getShapeFormattingController()](#getShapeFormattingController--) | یک رابط callback را که به کاربر امکان کنترل تبدیل شکل را می‌دهد، برمی‌گرداند و تنظیم می‌کند. |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | یک رابط callback را که به کاربر امکان کنترل تبدیل شکل را می‌دهد، برمی‌گرداند و تنظیم می‌کند. |
| [getPicturesCompression()](#getPicturesCompression--) | سطح فشرده‌سازی تصاویر را نشان می‌دهد |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | سطح فشرده‌سازی تصاویر را نشان می‌دهد |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | پرچم بولی نشان می‌دهد که آیا بخش‌های بریده‌شده به عنوان بخشی از سند باقی می‌مانند یا نه. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | پرچم بولی نشان می‌دهد که آیا بخش‌های بریده‌شده به عنوان بخشی از سند باقی می‌مانند یا نه. |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | روشی برای مدیریت فونت‌های بارگذاری‌شده به‌صورت خارجی تعیین می‌کند. |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | روشی برای مدیریت فونت‌های بارگذاری‌شده به‌صورت خارجی تعیین می‌کند. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | مقداری را که نشان می‌دهد متن بدون استفاده از لیگاتورها رندر می‌شود، دریافت یا تنظیم می‌کند. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | مقداری را که نشان می‌دهد متن بدون استفاده از لیگاتورها رندر می‌شود، دریافت یا تنظیم می‌کند. |

### SVGOptions() {#SVGOptions--}
```
public SVGOptions()
```

یک نمونه جدید از کلاس SVGOptions را مقداردهی اولیه می‌کند.

### SVGOptions(ILinkEmbedController linkEmbedController) {#SVGOptions-com.aspose.slides.ILinkEmbedController-}
```
public SVGOptions(ILinkEmbedController linkEmbedController)
```

یک نمونه جدید از کلاس SVGOptions را با تعیین شیء کنترل‌کننده تعبیه‌پیوند مقداردهی اولیه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | مرجع کنترل‌کننده تعبیه‌پیوند. |

--------------------

Link embedding controller is a delegate object that is responsible for making decisions if resources (such as images) need to be embedded or referenced as external resources. |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

گزینه‌هایی را فراهم می‌کند که ظاهر اشیای Ink را در سند صادرشده کنترل می‌کند. فقط خواندنی [IInkOptions](../../com.aspose.slides/iinkoptions)

**بازگشت:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getUseFrameSize() {#getUseFrameSize--}
```
public final boolean getUseFrameSize()
```

مشخص می‌کند که آیا قاب متن در یک ناحیه نمایشی گنجانده شود یا نه. خواندنی/نوشتنی  boolean . مقدار پیش‌فرض false است.

**بازگشت:**
boolean
### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public final void setUseFrameSize(boolean value)
```

مشخص می‌کند که آیا قاب متن در یک ناحیه نمایشی گنجانده شود یا نه. خواندنی/نوشتنی  boolean . مقدار پیش‌فرض false است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameRotation() {#getUseFrameRotation--}
```
public final boolean getUseFrameRotation()
```

مشخص می‌کند که آیا چرخش مشخص شکل هنگام رندر انجام شود یا نه. خواندنی/نوشتنی  boolean . مقدار پیش‌فرض true است.

**بازگشت:**
boolean
### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public final void setUseFrameRotation(boolean value)
```

مشخص می‌کند که آیا چرخش مشخص شکل هنگام رندر انجام شود یا نه. خواندنی/نوشتنی  boolean . مقدار پیش‌فرض true است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getVectorizeText() {#getVectorizeText--}
```
public final boolean getVectorizeText()
```

مشخص می‌کند که آیا متن در یک اسلاید به‌صورت گرافیک ذخیره شود یا نه. خواندنی/نوشتنی boolean.

**بازگشت:**
boolean
### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public final void setVectorizeText(boolean value)
```

مشخص می‌کند که آیا متن در یک اسلاید به‌صورت گرافیک ذخیره شود یا نه. خواندنی/نوشتنی boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public final int getMetafileRasterizationDpi()
```

محدودیت وضوح پایین‌تر برای رستر‌سازی متافایل را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی int.

**بازگشت:**
int
### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public final void setMetafileRasterizationDpi(int value)
```

محدودیت وضوح پایین‌تر برای رستر‌سازی متافایل را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getDisable3DText() {#getDisable3DText--}
```
public final boolean getDisable3DText()
```

مشخص می‌کند که آیا متن 3D در SVG غیرفعال باشد یا نه. خواندنی/نوشتنی boolean.

**بازگشت:**
boolean
### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public final void setDisable3DText(boolean value)
```

مشخص می‌کند که آیا متن 3D در SVG غیرفعال باشد یا نه. خواندنی/نوشتنی boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public final boolean getDisableGradientSplit()
```

تقسیم گرادیان‌های FromCornerX و FromCenter را غیرفعال می‌کند. خواندنی/نوشتنی boolean.

**بازگشت:**
boolean
### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public final void setDisableGradientSplit(boolean value)
```

تقسیم گرادیان‌های FromCornerX و FromCenter را غیرفعال می‌کند. خواندنی/نوشتنی boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public final boolean getDisableLineEndCropping()
```

SVG 1.1 توانایی تعریف حاشیه‌های داخلی برای نشانگرها را ندارد. موتور نوشتن SVG Aspose.Slides راه‌حلی برای این مشکل دارد: انتهای خط با پیکان برش می‌دهد تا خط با نشانگرها همپوشانی نکند. این گزینه این رفتار را غیرفعال می‌کند. خواندنی/نوشتنی boolean.

**بازگشت:**
boolean
### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public final void setDisableLineEndCropping(boolean value)
```

SVG 1.1 توانایی تعریف حاشیه‌های داخلی برای نشانگرها را ندارد. موتور نوشتن SVG Aspose.Slides راه‌حلی برای این مشکل دارد: انتهای خط با پیکان برش می‌دهد تا خط با نشانگرها همپوشانی نکند. این گزینه این رفتار را غیرفعال می‌کند. خواندنی/نوشتنی boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getDefault() {#getDefault--}
```
public static SVGOptions getDefault()
```

تنظیمات پیش‌فرض را برمی‌گرداند. فقط خواندنی [SVGOptions](../../com.aspose.slides/svgoptions).

**بازگشت:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getSimple() {#getSimple--}
```
public static SVGOptions getSimple()
```

تنظیمات برای ساده‌ترین و کوچک‌ترین تولید فایل SVG را برمی‌گرداند. فقط خواندنی [SVGOptions](../../com.aspose.slides/svgoptions).

**بازگشت:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getWYSIWYG() {#getWYSIWYG--}
```
public static SVGOptions getWYSIWYG()
```

تنظیمات برای دقیق‌ترین تولید فایل SVG را برمی‌گرداند. فقط خواندنی [SVGOptions](../../com.aspose.slides/svgoptions).

**بازگشت:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```

کیفیت رمزگذاری JPEG را تعیین می‌کند. خواندنی/نوشتنی int.

**بازگشت:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```

کیفیت رمزگذاری JPEG را تعیین می‌کند. خواندنی/نوشتنی int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getShapeFormattingController() {#getShapeFormattingController--}
```
public final ISvgShapeFormattingController getShapeFormattingController()
```

یک رابط callback را که به کاربر امکان کنترل تبدیل شکل را می‌دهد، برمی‌گرداند و تنظیم می‌کند. خواندنی/نوشتنی [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**بازگشت:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public final void setShapeFormattingController(ISvgShapeFormattingController value)
```

یک رابط callback را که به کاربر امکان کنترل تبدیل شکل را می‌دهد، برمی‌گرداند و تنظیم می‌کند. خواندنی/نوشتنی [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```

سطح فشرده‌سازی تصاویر را نشان می‌دهد

**بازگشت:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public final void setPicturesCompression(int value)
```

سطح فشرده‌سازی تصاویر را نشان می‌دهد

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public final boolean getDeletePicturesCroppedAreas()
```

پرچم بولی نشان می‌دهد که آیا بخش‌های بریده‌شده به عنوان بخشی از سند باقی می‌مانند یا نه. اگر true باشد بخش‌های بریده‌شده حذف می‌شوند، اگر false باشند در سند سریالیزه می‌شوند (که ممکن است منجر به فایل بزرگتر شود)

**بازگشت:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```

پرچم بولی نشان می‌دهد که آیا بخش‌های بریده‌شده به عنوان بخشی از سند باقی می‌مانند یا نه. اگر true باشد بخش‌های بریده‌شده حذف می‌شوند، اگر false باشند در سند سریالیزه می‌شوند (که ممکن است منجر به فایل بزرگتر شود)

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public final int getExternalFontsHandling()
```

روشی برای مدیریت فونت‌های بارگذاری‌شده به‌صورت خارجی تعیین می‌کند. خواندنی/نوشتنی [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**بازگشت:**
int
### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public final void setExternalFontsHandling(int value)
```

روشی برای مدیریت فونت‌های بارگذاری‌شده به‌صورت خارجی تعیین می‌کند. خواندنی/نوشتنی [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

مقداری را که نشان می‌دهد متن بدون استفاده از لیگاتورها رندر می‌شود، دریافت یا تنظیم می‌کند. وقتی به true تنظیم شود، لیگاتورها در خروجی رندر شده غیرفعال می‌شوند. به‌طور پیش‌فرض این خصوصیت false است.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      SVGOptions options = new SVGOptions();
>      options.setDisableFontLigatures(true);
> 
>      FileOutputStream fileStream = new FileOutputStream("slide-0.svg");
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream);
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

مقداری را که نشان می‌دهد متن بدون استفاده از لیگاتورها رندر می‌شود، دریافت یا تنظیم می‌کند. وقتی به true تنظیم شود، لیگاتورها در خروجی رندر شده غیرفعال می‌شوند. به‌طور پیش‌فرض این خصوصیت false است.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      SVGOptions options = new SVGOptions();
>      options.setDisableFontLigatures(true);
> 
>      FileOutputStream fileStream = new FileOutputStream("slide-0.svg");
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |