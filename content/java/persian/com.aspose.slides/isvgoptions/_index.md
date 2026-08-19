---
title: ISVGOptions
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایانگر گزینه‌های SVG است.
type: docs
url: /fa/com.aspose.slides/isvgoptions/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ISVGOptions extends ISaveOptions
```

نمایانگر گزینه‌های SVG است.
## متدها

| متد | توضیح |
| --- | --- |
| [getVectorizeText()](#getVectorizeText--) | مشخص می‌کند آیا متن روی اسلاید به‌صورت گرافیک ذخیره شود. |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | مشخص می‌کند آیا متن روی اسلاید به‌صورت گرافیک ذخیره شود. |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | مقدار یا تنظیم حد پایین رزولوشن برای رسترایز متافایل. |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | مقدار یا تنظیم حد پایین رزولوشن برای رسترایز متافایل. |
| [getDisable3DText()](#getDisable3DText--) | مشخص می‌کند آیا متن 3D در SVG غیرفعال باشد. |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | مشخص می‌کند آیا متن 3D در SVG غیرفعال باشد. |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | تقسیم گرادیان‌های FromCornerX و FromCenter را غیرفعال می‌کند. |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | تقسیم گرادیان‌های FromCornerX و FromCenter را غیرفعال می‌کند. |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | SVG 1.1 قابلیت تعریف حاشیه‌ها برای مارکرها را ندارد. |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | SVG 1.1 قابلیت تعریف حاشیه‌ها برای مارکرها را ندارد. |
| [getJpegQuality()](#getJpegQuality--) | کیفیت رمزنگاری JPEG را تعیین می‌کند. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | کیفیت رمزنگاری JPEG را تعیین می‌کند. |
| [getShapeFormattingController()](#getShapeFormattingController--) | یک رابط بازگشتی که به کاربر امکان کنترل تبدیل شکل را می‌دهد، باز می‌گرداند یا تنظیم می‌کند. |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | یک رابط بازگشتی که به کاربر امکان کنترل تبدیل شکل را می‌دهد، باز می‌گرداند یا تنظیم می‌کند. |
| [getPicturesCompression()](#getPicturesCompression--) | نمایانگر سطح فشرده‌سازی تصاویر Read/write \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | نمایانگر سطح فشرده‌سازی تصاویر Read/write \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int). |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | یک پرچم بولی نشان می‌دهد آیا بخش‌های برش خورده به عنوان بخشی از سند باقی می‌مانند. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | یک پرچم بولی نشان می‌دهد آیا بخش‌های برش خورده به عنوان بخشی از سند باقی می‌مانند. |
| [getUseFrameSize()](#getUseFrameSize--) | مشخص می‌کند آیا قاب متن در ناحیه رندر گنجانده شود یا نه. |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | مشخص می‌کند آیا قاب متن در ناحیه رندر گنجانده شود یا نه. |
| [getUseFrameRotation()](#getUseFrameRotation--) | مشخص می‌کند آیا چرخش مشخص‌شده شکل هنگام رندر انجام شود یا نه. |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | مشخص می‌کند آیا چرخش مشخص‌شده شکل هنگام رندر انجام شود یا نه. |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | یک روش برای مدیریت قلم‌های بارگذاری‌شده به‌صورت خارجی تعیین می‌کند. |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | یک روش برای مدیریت قلم‌های بارگذاری‌شده به‌صورت خارجی تعیین می‌کند. |
| [getInkOptions()](#getInkOptions--) | گزینه‌هایی را فراهم می‌کند که ظاهر اشیاء Ink را در سند صادرشده کنترل می‌کند. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | دریافت یا تنظیم مقدار نشان‌دهنده این که آیا متن بدون استفاده از لیگچرها رندر شود. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | دریافت یا تنظیم مقدار نشان‌دهنده این که آیا متن بدون استفاده از لیگچرها رندر شود. |
### getVectorizeText() {#getVectorizeText--}
```
public abstract boolean getVectorizeText()
```

مشخص می‌کند آیا متن روی اسلاید به‌صورت گرافیک ذخیره شود. خواندن/نوشتن boolean.

**بازگشت:**
boolean
### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public abstract void setVectorizeText(boolean value)
```

مشخص می‌کند آیا متن روی اسلاید به‌صورت گرافیک ذخیره شود. خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public abstract int getMetafileRasterizationDpi()
```

مقدار یا تنظیم حد پایین رزولوشن برای رسترایز متافایل. خواندن/نوشتن int.

**بازگشت:**
int
### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public abstract void setMetafileRasterizationDpi(int value)
```

مقدار یا تنظیم حد پایین رزولوشن برای رسترایز متافایل. خواندن/نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### getDisable3DText() {#getDisable3DText--}
```
public abstract boolean getDisable3DText()
```

مشخص می‌کند آیا متن 3D در SVG غیرفعال باشد. خواندن/نوشتن boolean.

**بازگشت:**
boolean
### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public abstract void setDisable3DText(boolean value)
```

مشخص می‌کند آیا متن 3D در SVG غیرفعال باشد. خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public abstract boolean getDisableGradientSplit()
```

تقسیم گرادیان‌های FromCornerX و FromCenter را غیرفعال می‌کند. خواندن/نوشتن boolean.

**بازگشت:**
boolean
### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public abstract void setDisableGradientSplit(boolean value)
```

تقسیم گرادیان‌های FromCornerX و FromCenter را غیرفعال می‌کند. خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public abstract boolean getDisableLineEndCropping()
```

SVG 1.1 قابلیت تعریف حاشیه‌ها برای مارکرها را ندارد. Aspose.Slides SVG writing engine یک راه‌حل برای این مشکل دارد: انتهای خط با پیکان را برش می‌دهد تا خط با مارکرها تداخل نداشته باشد. این گزینه رفتار فوق را غیرفعال می‌کند. خواندن/نوشتن boolean.

**بازگشت:**
boolean
### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public abstract void setDisableLineEndCropping(boolean value)
```

SVG 1.1 قابلیت تعریف حاشیه‌ها برای مارکرها را ندارد. Aspose.Slides SVG writing engine یک راه‌حل برای این مشکل دارد: انتهای خط با پیکان را برش می‌دهد تا خط با مارکرها تداخل نداشته باشد. این گزینه رفتار فوق را غیرفعال می‌کند. خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getJpegQuality() {#getJpegQuality--}
```
public abstract int getJpegQuality()
```

کیفیت رمزنگاری JPEG را تعیین می‌کند. خواندن/نوشتن int.

**بازگشت:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public abstract void setJpegQuality(int value)
```

کیفیت رمزنگاری JPEG را تعیین می‌کند. خواندن/نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### getShapeFormattingController() {#getShapeFormattingController--}
```
public abstract ISvgShapeFormattingController getShapeFormattingController()
```

یک رابط بازگشتی که به کاربر امکان کنترل تبدیل شکل را می‌دهد، باز می‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**بازگشت:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public abstract void setShapeFormattingController(ISvgShapeFormattingController value)
```

یک رابط بازگشتی که به کاربر امکان کنترل تبدیل شکل را می‌دهد، باز می‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) |  |
### getPicturesCompression() {#getPicturesCompression--}
```
public abstract int getPicturesCompression()
```

نمایانگر سطح فشرده‌سازی تصاویر Read/write \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int).

**بازگشت:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```

نمایانگر سطح فشرده‌سازی تصاویر Read/write \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public abstract boolean getDeletePicturesCroppedAreas()
```

یک پرچم بولی نشان می‌دهد آیا بخش‌های برش خورده به عنوان بخشی از سند باقی می‌مانند. اگر true باشد بخش‌های برش خورده حذف می‌شوند، اگر false باشند در سند سریال‌سازی می‌شوند (که ممکن است منجر به فایل بزرگتر شود). خواندن/نوشتن boolean.

**بازگشت:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public abstract void setDeletePicturesCroppedAreas(boolean value)
```

یک پرچم بولی نشان می‌دهد آیا بخش‌های برش خورده به عنوان بخشی از سند باقی می‌مانند. اگر true باشد بخش‌های برش خورده حذف می‌شوند، اگر false باشند در سند سریال‌سازی می‌شوند (که ممکن است منجر به فایل بزرگتر شود). خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getUseFrameSize() {#getUseFrameSize--}
```
public abstract boolean getUseFrameSize()
```

مشخص می‌کند آیا قاب متن در ناحیه رندر گنجانده شود یا نه. خواندن/نوشتن boolean. مقدار پیش‌فرض false است.

**بازگشت:**
boolean
### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public abstract void setUseFrameSize(boolean value)
```

مشخص می‌کند آیا قاب متن در ناحیه رندر گنجانده شود یا نه. خواندن/نوشتن boolean. مقدار پیش‌فرض false است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getUseFrameRotation() {#getUseFrameRotation--}
```
public abstract boolean getUseFrameRotation()
```

مشخص می‌کند آیا چرخش مشخص‌شده شکل هنگام رندر انجام شود یا نه. خواندن/نوشتن boolean. مقدار پیش‌فرض true است.

**بازگشت:**
boolean
### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public abstract void setUseFrameRotation(boolean value)
```

مشخص می‌کند آیا چرخش مشخص‌شده شکل هنگام رندر انجام شود یا نه. خواندن/نوشتن boolean. مقدار پیش‌فرض true است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public abstract int getExternalFontsHandling()
```

یک روش برای مدیریت قلم‌های بارگذاری‌شده به‌صورت خارجی تعیین می‌کند. خواندن/نوشتن [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**بازگشت:**
int
### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public abstract void setExternalFontsHandling(int value)
```

یک روش برای مدیریت قلم‌های بارگذاری‌شده به‌صورت خارجی تعیین می‌کند. خواندن/نوشتن [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

گزینه‌هایی را فراهم می‌کند که ظاهر اشیاء Ink را در سند صادرشده کنترل می‌کند. فقط-خواندنی [IInkOptions](../../com.aspose.slides/iinkoptions)

**بازگشت:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

دریافت یا تنظیم مقدار نشان‌دهنده این که آیا متن بدون استفاده از لیگچرها رندر شود. زمانی که true باشد، لیگچرها در خروجی رندر غیرفعال می‌شوند. به‌صورت پیش‌فرض این ویژگی false است.

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
public abstract void setDisableFontLigatures(boolean value)
```

دریافت یا تنظیم مقدار نشان‌دهنده این که آیا متن بدون استفاده از لیگچرها رندر شود. زمانی که true باشد، لیگچرها در خروجی رندر غیرفعال می‌شوند. به‌صورت پیش‌فرض این ویژگی false است.

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