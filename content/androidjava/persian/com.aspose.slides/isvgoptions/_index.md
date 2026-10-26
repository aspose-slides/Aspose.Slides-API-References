---
title: ISVGOptions
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر گزینه‌های SVG است.
type: docs
url: /fa/com.aspose.slides/isvgoptions/
---
**همهٔ واسط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ISVGOptions extends ISaveOptions
```

نمایانگر گزینه‌های SVG است.
## متدها

| متد | توضیح |
| --- | --- |
| [getVectorizeText()](#getVectorizeText--) | مشخص می‌کند که متن روی یک اسلاید به صورت گرافیک ذخیره شود یا خیر. |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | مشخص می‌کند که متن روی یک اسلاید به صورت گرافیک ذخیره شود یا خیر. |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | مقدار یا تنظیم حد پایین وضوح برای رستریزه‌سازی متافایل را بر می‌گرداند یا تنظیم می‌کند. |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | مقدار یا تنظیم حد پایین وضوح برای رستریزه‌سازی متافایل را بر می‌گرداند یا تنظیم می‌کند. |
| [getDisable3DText()](#getDisable3DText--) | مشخص می‌کند که متن سه‌بعدی در SVG غیرفعال باشد یا نه. |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | مشخص می‌کند که متن سه‌بعدی در SVG غیرفعال باشد یا نه. |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | تقسیم گرادیان‌های FromCornerX و FromCenter را غیرفعال می‌کند. |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | تقسیم گرادیان‌های FromCornerX و FromCenter را غیرفعال می‌کند. |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | SVG 1.1 قابلیت تعریف حاشیه برای نشانگرها را ندارد. |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | SVG 1.1 قابلیت تعریف حاشیه برای نشانگرها را ندارد. |
| [getJpegQuality()](#getJpegQuality--) | کیفیت رمزگذاری JPEG را تعیین می‌کند. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | کیفیت رمزگذاری JPEG را تعیین می‌کند. |
| [getShapeFormattingController()](#getShapeFormattingController--) | یک رابط بازگشت‌خوان را بر می‌گرداند و تنظیم می‌کند که به کاربر امکان کنترل تبدیل شکل را می‌دهد. |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | یک رابط بازگشت‌خوان را بر می‌گرداند و تنظیم می‌کند که به کاربر امکان کنترل تبدیل شکل را می‌دهد. |
| [getPicturesCompression()](#getPicturesCompression--) | نمایانگر سطح فشرده‌سازی تصاویر است (قابل‌خواندن/قابل‌نوشتن) \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | نمایانگر سطح فشرده‌سازی تصاویر است (قابل‌خواندن/قابل‌نوشتن) \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int). |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | یک پرچم بولی نشان می‌دهد آیا بخش‌های برش‌خورده به عنوان بخشی از سند باقی می‌مانند یا خیر. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | یک پرچم بولی نشان می‌دهد آیا بخش‌های برش‌خورده به عنوان بخشی از سند باقی می‌مانند یا خیر. |
| [getUseFrameSize()](#getUseFrameSize--) | مشخص می‌کند آیا قاب متنی در ناحیه رندر گنجانده شود یا خیر. |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | مشخص می‌کند آیا قاب متنی در ناحیه رندر گنجانده شود یا خیر. |
| [getUseFrameRotation()](#getUseFrameRotation--) | مشخص می‌کند آیا چرخش مشخص‌شده شکل هنگام رندر انجام شود یا نه. |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | مشخص می‌کند آیا چرخش مشخص‌شده شکل هنگام رندر انجام شود یا نه. |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | روشی برای مدیریت فونت‌های بارگذاری‌شده از بیرون تعیین می‌کند. |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | روشی برای مدیریت فونت‌های بارگذاری‌شده از بیرون تعیین می‌کند. |
| [getInkOptions()](#getInkOptions--) | گزینه‌هایی را فراهم می‌کند که ظاهر اشیاء Ink را در سند صادرشده کنترل می‌کند. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | مقداری را بر می‌گرداند یا تنظیم می‌کند که نشان می‌دهد آیا متن بدون استفاده از لیگاتور رندر شود یا نه. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | مقداری را بر می‌گرداند یا تنظیم می‌کند که نشان می‌دهد آیا متن بدون استفاده از لیگاتور رندر شود یا نه. |
### getVectorizeText() {#getVectorizeText--}
```
public abstract boolean getVectorizeText()
```


مشخص می‌کند که متن روی یک اسلاید به صورت گرافیک ذخیره شود یا خیر. بولی (قابل‌خواندن/قابل‌نوشتن).

**باز می‌گردد:**
boolean
### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public abstract void setVectorizeText(boolean value)
```


مشخص می‌کند که متن روی یک اسلاید به صورت گرافیک ذخیره شود یا خیر. بولی (قابل‌خواندن/قابل‌نوشتن).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public abstract int getMetafileRasterizationDpi()
```


مقدار یا تنظیم حد پایین وضوح برای رستریزه‌سازی متافایل را بر می‌گرداند یا تنظیم می‌کند. عدد صحیح (قابل‌خواندن/قابل‌نوشتن).

**باز می‌گردد:**
int
### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public abstract void setMetafileRasterizationDpi(int value)
```


مقدار یا تنظیم حد پایین وضوح برای رستریزه‌سازی متافایل را بر می‌گرداند یا تنظیم می‌کند. عدد صحیح (قابل‌خواندن/قابل‌نوشتن).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### getDisable3DText() {#getDisable3DText--}
```
public abstract boolean getDisable3DText()
```


مشخص می‌کند که متن سه‌بعدی در SVG غیرفعال باشد یا نه. بولی (قابل‌خواندن/قابل‌نوشتن).

**باز می‌گردد:**
boolean
### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public abstract void setDisable3DText(boolean value)
```


مشخص می‌کند که متن سه‌بعدی در SVG غیرفعال باشد یا نه. بولی (قابل‌خواندن/قابل‌نوشتن).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public abstract boolean getDisableGradientSplit()
```


تقسیم گرادیان‌های FromCornerX و FromCenter را غیرفعال می‌کند. بولی (قابل‌خواندن/قابل‌نوشتن).

**باز می‌گردد:**
boolean
### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public abstract void setDisableGradientSplit(boolean value)
```


تقسیم گرادیان‌های FromCornerX و FromCenter را غیرفعال می‌کند. بولی (قابل‌خواندن/قابل‌نوشتن).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public abstract boolean getDisableLineEndCropping()
```


SVG 1.1 قابلیت تعریف حاشیه برای نشانگرها را ندارد. موتور نوشتن SVG Aspose.Slides راه‌حلی برای این مشکل دارد: انتهای خط با پیکان را برش می‌دهد، بنابراین خط روی نشانگرها همپوشانی نمی‌کند. این گزینه چنین رفتار را غیرفعال می‌کند. بولی (قابل‌خواندن/قابل‌نوشتن).

**باز می‌گردد:**
boolean
### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public abstract void setDisableLineEndCropping(boolean value)
```


SVG 1.1 قابلیت تعریف حاشیه برای نشانگرها را ندارد. موتور نوشتن SVG Aspose.Slides راه‌حلی برای این مشکل دارد: انتهای خط با پیکان را برش می‌دهد، بنابراین خط روی نشانگرها همپوشانی نمی‌کند. این گزینه چنین رفتار را غیرفعال می‌کند. بولی (قابل‌خواندن/قابل‌نوشتن).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getJpegQuality() {#getJpegQuality--}
```
public abstract int getJpegQuality()
```


کیفیت رمزگذاری JPEG را تعیین می‌کند. عدد صحیح (قابل‌خواندن/قابل‌نوشتن).

**باز می‌گردد:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public abstract void setJpegQuality(int value)
```


کیفیت رمزگذاری JPEG را تعیین می‌کند. عدد صحیح (قابل‌خواندن/قابل‌نوشتن).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### getShapeFormattingController() {#getShapeFormattingController--}
```
public abstract ISvgShapeFormattingController getShapeFormattingController()
```


یک رابط بازگشت‌خوان را بر می‌گرداند و تنظیم می‌کند که به کاربر امکان کنترل تبدیل شکل را می‌دهد. [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) (قابل‌خواندن/قابل‌نوشتن).

**باز می‌گردد:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public abstract void setShapeFormattingController(ISvgShapeFormattingController value)
```


یک رابط بازگشت‌خوان را بر می‌گرداند و تنظیم می‌کند که به کاربر امکان کنترل تبدیل شکل را می‌دهد. [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) (قابل‌خواندن/قابل‌نوشتن).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) |  |
### getPicturesCompression() {#getPicturesCompression--}
```
public abstract int getPicturesCompression()
```


نمایانگر سطح فشرده‌سازی تصاویر است (قابل‌خواندن/قابل‌نوشتن) \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int).

**باز می‌گردد:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```


نمایانگر سطح فشرده‌سازی تصاویر است (قابل‌خواندن/قابل‌نوشتن) \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public abstract boolean getDeletePicturesCroppedAreas()
```


یک پرچم بولی نشان می‌دهد آیا بخش‌های برش‌خورده به عنوان بخشی از سند باقی بمانند یا حذف شوند. اگر true باشد بخش‌های برش‌خورده حذف می‌شوند، اگر false باشند در سند سریال‌سازی می‌شوند (که ممکن است منجر به فایل بزرگتر شود). بولی (قابل‌خواندن/قابل‌نوشتن).

**باز می‌گردد:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public abstract void setDeletePicturesCroppedAreas(boolean value)
```


یک پرچم بولی نشان می‌دهد آیا بخش‌های برش‌خورده به عنوان بخشی از سند باقی بمانند یا حذف شوند. اگر true باشد بخش‌های برش‌خورده حذف می‌شوند، اگر false باشند در سند سریال‌سازی می‌شوند (که ممکن است منجر به فایل بزرگتر شود). بولی (قابل‌خواندن/قابل‌نوشتن).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getUseFrameSize() {#getUseFrameSize--}
```
public abstract boolean getUseFrameSize()
```


مشخص می‌کند آیا قاب متنی در ناحیه رندر گنجانده شود یا خیر. بولی (قابل‌خواندن/قابل‌نوشتن) . مقدار پیش‌فرض false است.

**باز می‌گردد:**
boolean
### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public abstract void setUseFrameSize(boolean value)
```


مشخص می‌کند آیا قاب متنی در ناحیه رندر گنجانده شود یا خیر. بولی (قابل‌خواندن/قابل‌نوشتن) . مقدار پیش‌فرض false است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getUseFrameRotation() {#getUseFrameRotation--}
```
public abstract boolean getUseFrameRotation()
```


مشخص می‌کند آیا چرخش مشخص‌شده شکل هنگام رندر انجام شود یا نه. بولی (قابل‌خواندن/قابل‌نوشتن) . مقدار پیش‌فرض true است.

**باز می‌گردد:**
boolean
### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public abstract void setUseFrameRotation(boolean value)
```


مشخص می‌کند آیا چرخش مشخص‌شده شکل هنگام رندر انجام شود یا نه. بولی (قابل‌خواندن/قابل‌نوشتن) . مقدار پیش‌فرض true است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public abstract int getExternalFontsHandling()
```


روشی برای مدیریت فونت‌های بارگذاری‌شده از بیرون تعیین می‌کند. [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling) (قابل‌خواندن/قابل‌نوشتن).

**باز می‌گردد:**
int
### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public abstract void setExternalFontsHandling(int value)
```


روشی برای مدیریت فونت‌های بارگذاری‌شده از بیرون تعیین می‌کند. [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling) (قابل‌خواندن/قابل‌نوشتن).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```


گزینه‌هایی را فراهم می‌کند که ظاهر اشیاء Ink را در سند صادرشده کنترل می‌کند. فقط‌خواندنی [IInkOptions](../../com.aspose.slides/iinkoptions)

**باز می‌گردد:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```


مقداری را بر می‌گرداند یا تنظیم می‌کند که نشان می‌دهد آیا متن بدون استفاده از لیگاتور رندر شود یا نه. وقتی به true تنظیم شود، لیگاتورها در خروجی رندر شده غیرفعال می‌شوند. به طور پیش‌فرض این ویژگی false است.

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

**باز می‌گردد:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public abstract void setDisableFontLigatures(boolean value)
```


مقداری را بر می‌گرداند یا تنظیم می‌کند که نشان می‌دهد آیا متن بدون استفاده از لیگاتور رندر شود یا نه. وقتی به true تنظیم شود، لیگاتورها در خروجی رندر شده غیرفعال می‌شوند. به طور پیش‌فرض این ویژگی false است.

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