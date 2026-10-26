---
title: SVGOptions
second_title: Aspose.Slides برای جاوا مرجع API
description: گزینه‌های SVG را نمایان می‌کند.
type: docs
url: /fa/com.aspose.slides/svgoptions/
---
**ارث‌برداری:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**تمامی واسط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ISVGOptions](../../com.aspose.slides/isvgoptions), java.lang.Cloneable
```
public final class SVGOptions extends SaveOptions implements ISVGOptions, Cloneable
```

نمایانگر یک گزینه SVG است.

## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [SVGOptions()](#SVGOptions--) | یک نمونه جدید از کلاس SVGOptions را مقداردهی اولیه می‌کند. |
| [SVGOptions(ILinkEmbedController linkEmbedController)](#SVGOptions-com.aspose.slides.ILinkEmbedController-) | یک نمونه جدید از کلاس SVGOptions را با مشخص کردن شیء کنترل‌کننده تعبیه لینک مقداردهی اولیه می‌کند. |

## متدها

| متد | توضیح |
| --- | --- |
| [getInkOptions()](#getInkOptions--) | گزینه‌هایی را فراهم می‌کند که ظاهر اشیاء Ink را در سند صادرشده کنترل می‌کند. |
| [getUseFrameSize()](#getUseFrameSize--) | تعیین می‌کند که آیا قاب متن در ناحیه رندر گنجانده شود یا نه. |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | تعیین می‌کند که آیا قاب متن در ناحیه رندر گنجانده شود یا نه. |
| [getUseFrameRotation()](#getUseFrameRotation--) | تعیین می‌کند که آیا دوران مشخص‌شده شکل هنگام رندر اجرا شود یا نه. |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | تعیین می‌کند که آیا دوران مشخص‌شده شکل هنگام رندر اجرا شود یا نه. |
| [getVectorizeText()](#getVectorizeText--) | تعیین می‌کند که آیا متن روی اسلاید به صورت گرافیک ذخیره شود یا نه. |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | تعیین می‌کند که آیا متن روی اسلاید به صورت گرافیک ذخیره شود یا نه. |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | محدودیت رزولوشن پایین‌تر برای رستر‌سازی متافایل را برمی‌گرداند یا تنظیم می‌کند. |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | محدودیت رزولوشن پایین‌تر برای رستر‌سازی متافایل را برمی‌گرداند یا تنظیم می‌کند. |
| [getDisable3DText()](#getDisable3DText--) | تعیین می‌کند که آیا متن 3D در SVG غیرفعال است یا نه. |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | تعیین می‌کند که آیا متن 3D در SVG غیرفعال است یا نه. |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | تقسیم‌پذیری گرادیان‌های FromCornerX و FromCenter را غیرفعال می‌کند. |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | تقسیم‌پذیری گرادیان‌های FromCornerX و FromCenter را غیرفعال می‌کند. |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | SVG 1.1 قابلیت تعریف حاشیه‌ها برای نشانگرها را ندارد. |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | SVG 1.1 قابلیت تعریف حاشیه‌ها برای نشانگرها را ندارد. |
| [getDefault()](#getDefault--) | تنظیمات پیش‌فرض را برمی‌گرداند. |
| [getSimple()](#getSimple--) | تنظیمات برای تولید ساده‌ترین و کوچک‌ترین فایل SVG را برمی‌گرداند. |
| [getWYSIWYG()](#getWYSIWYG--) | تنظیمات برای دقیق‌ترین تولید فایل SVG را برمی‌گرداند. |
| [getJpegQuality()](#getJpegQuality--) | کیفیت رمزنگاری JPEG را تعیین می‌کند. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | کیفیت رمزنگاری JPEG را تعیین می‌کند. |
| [getShapeFormattingController()](#getShapeFormattingController--) | یک رابط فراخوانی‌پذیر را برمی‌گرداند و تنظیم می‌کند که به کاربر امکان کنترل تبدیل شکل را می‌دهد. |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | یک رابط فراخوانی‌پذیر را برمی‌گرداند و تنظیم می‌کند که به کاربر امکان کنترل تبدیل شکل را می‌دهد. |
| [getPicturesCompression()](#getPicturesCompression--) | سطح فشرده‌سازی تصاویر را نمایش می‌دهد. |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | سطح فشرده‌سازی تصاویر را نمایش می‌دهد. |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | یک پرچم منطقی نشان می‌دهد که آیا بخش‌های بریده‌شده به عنوان بخشی از سند باقی می‌مانند یا خیر. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | یک پرچم منطقی نشان می‌دهد که آیا بخش‌های بریده‌شده به عنوان بخشی از سند باقی می‌مانند یا خیر. |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | یک روش برای مدیریت قلم‌های بارگذاری شده از خارج را تعیین می‌کند. |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | یک روش برای مدیریت قلم‌های بارگذاری شده از خارج را تعیین می‌کند. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | مقداری را برمی‌گرداند یا تنظیم می‌کند که نشان می‌دهد آیا متن بدون استفاده از لیگچرها رندر می‌شود یا نه. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | مقداری را برمی‌گرداند یا تنظیم می‌کند که نشان می‌دهد آیا متن بدون استفاده از لیگچرها رندر می‌شود یا نه. |

### SVGOptions() {#SVGOptions--}
```
public SVGOptions()
```

یک نمونه جدید از کلاس SVGOptions را مقداردهی اولیه می‌کند.

### SVGOptions(ILinkEmbedController linkEmbedController) {#SVGOptions-com.aspose.slides.ILinkEmbedController-}
```
public SVGOptions(ILinkEmbedController linkEmbedController)
```

یک نمونه جدید از کلاس SVGOptions را با مشخص کردن شیء کنترل‌کننده تعبیه لینک مقداردهی اولیه می‌کند.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | ارجاع به کنترل‌کننده تعبیه لینک. |

--------------------

کنترل‌کننده تعبیه لینک یک شیء نماینده است که مسئول تصمیم‌گیری در مورد اینکه آیا منابع (مانند تصاویر) باید تعبیه شوند یا به عنوان منابع خارجی ارجاع داده شوند. |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

گزینه‌هایی را فراهم می‌کند که ظاهر اشیاء Ink را در سند صادرشده کنترل می‌کند. فقط-خواندنی [IInkOptions](../../com.aspose.slides/iinkoptions)

**Returns:**
[IInkOptions](../../com.aspose.slides/iinkoptions)

### getUseFrameSize() {#getUseFrameSize--}
```
public final boolean getUseFrameSize()
```

تعیین می‌کند که آیا قاب متن در ناحیه رندر گنجانده شود یا نه. خواندنی-نوشتنی boolean. مقدار پیش‌فرض false است.

**Returns:**
boolean

### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public final void setUseFrameSize(boolean value)
```

تعیین می‌کند که آیا قاب متن در ناحیه رندر گنجانده شود یا نه. خواندنی-نوشتنی boolean. مقدار پیش‌فرض false است.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameRotation() {#getUseFrameRotation--}
```
public final boolean getUseFrameRotation()
```

تعیین می‌کند که آیا دوران مشخص‌شده شکل هنگام رندر اجرا شود یا نه. خواندنی-نوشتنی boolean. مقدار پیش‌فرض true است.

**Returns:**
boolean

### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public final void setUseFrameRotation(boolean value)
```

تعیین می‌کند که آیا دوران مشخص‌شده شکل هنگام رندر اجرا شود یا نه. خواندنی-نوشتنی boolean. مقدار پیش‌فرض true است.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getVectorizeText() {#getVectorizeText--}
```
public final boolean getVectorizeText()
```

تعیین می‌کند که آیا متن روی اسلاید به صورت گرافیک ذخیره شود یا نه. خواندنی-نوشتنی boolean.

**Returns:**
boolean

### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public final void setVectorizeText(boolean value)
```

تعیین می‌کند که آیا متن روی اسلاید به صورت گرافیک ذخیره شود یا نه. خواندنی-نوشتنی boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public final int getMetafileRasterizationDpi()
```

محدودیت رزولوشن پایین‌تر برای رستر‌سازی متافایل را برمی‌گرداند یا تنظیم می‌کند. خواندنی-نوشتنی int.

**Returns:**
int

### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public final void setMetafileRasterizationDpi(int value)
```

محدودیت رزولوشن پایین‌تر برای رستر‌سازی متافایل را برمی‌گرداند یا تنظیم می‌کند. خواندنی-نوشتنی int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDisable3DText() {#getDisable3DText--}
```
public final boolean getDisable3DText()
```

تعیین می‌کند که آیا متن 3D در SVG غیرفعال است یا نه. خواندنی-نوشتنی boolean.

**Returns:**
boolean

### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public final void setDisable3DText(boolean value)
```

تعیین می‌کند که آیا متن 3D در SVG غیرفعال است یا نه. خواندنی-نوشتنی boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public final boolean getDisableGradientSplit()
```

تقسیم‌پذیری گرادیان‌های FromCornerX و FromCenter را غیرفعال می‌کند. خواندنی-نوشتنی boolean.

**Returns:**
boolean

### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public final void setDisableGradientSplit(boolean value)
```

تقسیم‌پذیری گرادیان‌های FromCornerX و FromCenter را غیرفعال می‌کند. خواندنی-نوشتنی boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public final boolean getDisableLineEndCropping()
```

SVG 1.1 قابلیت تعریف حاشیه‌ها برای نشانگرها را ندارد. موتور نوشتن SVG Aspose.Slides یک راه‌حل برای این مشکل دارد: انتهای خط با پیکان را برش می‌دهد تا خط روی نشانگرها نبندد. این گزینه این رفتار را خاموش می‌کند. خواندنی-نوشتنی boolean.

**Returns:**
boolean

### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public final void setDisableLineEndCropping(boolean value)
```

SVG 1.1 قابلیت تعریف حاشیه‌ها برای نشانگرها را ندارد. موتور نوشتن SVG Aspose.Slides یک راه‌حل برای این مشکل دارد: انتهای خط با پیکان را برش می‌دهد تا خط روی نشانگرها نبندد. این گزینه این رفتار را خاموش می‌کند. خواندنی-نوشتنی boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDefault() {#getDefault--}
```
public static SVGOptions getDefault()
```

تنظیمات پیش‌فرض را برمی‌گرداند. فقط-خواندنی [SVGOptions](../../com.aspose.slides/svgoptions).

**Returns:**
[SVGOptions](../../com.aspose.slides/svgoptions)

### getSimple() {#getSimple--}
```
public static SVGOptions getSimple()
```

تنظیمات برای تولید ساده‌ترین و کوچک‌ترین فایل SVG را برمی‌گرداند. فقط-خواندنی [SVGOptions](../../com.aspose.slides/svgoptions).

**Returns:**
[SVGOptions](../../com.aspose.slides/svgoptions)

### getWYSIWYG() {#getWYSIWYG--}
```
public static SVGOptions getWYSIWYG()
```

تنظیمات برای دقیق‌ترین تولید فایل SVG را برمی‌گرداند. فقط-خواندنی [SVGOptions](../../com.aspose.slides/svgoptions).

**Returns:**
[SVGOptions](../../com.aspose.slides/svgoptions)

### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```

کیفیت رمزنگاری JPEG را تعیین می‌کند. خواندنی-نوشتنی int.

**Returns:**
int

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```

کیفیت رمزنگاری JPEG را تعیین می‌کند. خواندنی-نوشتنی int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getShapeFormattingController() {#getShapeFormattingController--}
```
public final ISvgShapeFormattingController getShapeFormattingController()
```

یک رابط فراخوانی‌پذیر را برمی‌گرداند و تنظیم می‌کند که به کاربر امکان کنترل تبدیل شکل را می‌دهد. خواندنی-نوشتنی [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Returns:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)

### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public final void setShapeFormattingController(ISvgShapeFormattingController value)
```

یک رابط فراخوانی‌پذیر را برمی‌گرداند و تنظیم می‌کند که به کاربر امکان کنترل تبدیل شکل را می‌دهد. خواندنی-نوشتنی [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```

سطح فشرده‌سازی تصاویر را نمایش می‌دهد.

**Returns:**
int

### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public final void setPicturesCompression(int value)
```

سطح فشرده‌سازی تصاویر را نمایش می‌دهد.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public final boolean getDeletePicturesCroppedAreas()
```

یک پرچم منطقی نشان می‌دهد که آیا بخش‌های بریده‌شده به عنوان بخشی از سند باقی می‌مانند یا خیر. اگر مقدار true باشد، بخش‌های بریده‌شده حذف می‌شوند؛ اگر false باشد، در سند سریال‌سازی می‌شوند (که ممکن است منجر به فایل بزرگتر شود).

**Returns:**
boolean

### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```

یک پرچم منطقی نشان می‌دهد که آیا بخش‌های بریده‌شده به عنوان بخشی از سند باقی می‌مانند یا خیر. اگر مقدار true باشد، بخش‌های بریده‌شده حذف می‌شوند؛ اگر false باشد، در سند سریال‌سازی می‌شوند (که ممکن است منجر به فایل بزرگتر شود).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public final int getExternalFontsHandling()
```

یک روش برای مدیریت قلم‌های بارگذاری شده از خارج را تعیین می‌کند. خواندنی-نوشتنی [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Returns:**
int

### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public final void setExternalFontsHandling(int value)
```

یک روش برای مدیریت قلم‌های بارگذاری شده از خارج را تعیین می‌کند. خواندنی-نوشتنی [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

مقداری را برمی‌گرداند یا تنظیم می‌کند که نشان می‌دهد آیا متن بدون استفاده از لیگچرها رندر می‌شود یا نه. وقتی به true تنظیم شود، لیگچرها در خروجی رندر شده غیرفعال می‌شوند. به‌طور پیش‌فرض این خصوصیت false است.

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


**Returns:**
boolean

### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public final void setDisableFontLigatures(boolean value)
```

مقداری را برمی‌گرداند یا تنظیم می‌کند که نشان می‌دهد آیا متن بدون استفاده از لیگچرها رندر می‌شود یا نه. وقتی به true تنظیم شود، لیگچرها در خروجی رندر شده غیرفعال می‌شوند. به‌طور پیش‌فرض این خصوصیت false است.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |