---
title: SaveOptions
second_title: مرجع API Aspose.Slides برای جاوا
description: کلاس انتزاعی با گزینه‌هایی که نحوه ذخیره‌سازی یک ارائه را کنترل می‌کند.
type: docs
url: /fa/com.aspose.slides/saveoptions/
---
**ارث‌بری:**
java.lang.Object

**همه رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public abstract class SaveOptions implements ISaveOptions
```

کلاس انتزاعی با گزینه‌هایی که نحوه ذخیره‌سازی یک ارائه را کنترل می‌کند.
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [SaveOptions()](#SaveOptions--) |  |
## متدها

| متد | توضیح |
| --- | --- |
| [getWarningCallback()](#getWarningCallback--) | یک شی را که هشدارها را دریافت می‌کند و تصمیم می‌گیرد آیا فرآیند بارگذاری ادامه یابد یا متوقف شود، بازمی‌گرداند یا تنظیم می‌کند. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | یک شی را که هشدارها را دریافت می‌کند و تصمیم می‌گیرد آیا فرآیند بارگذاری ادامه یابد یا متوقف شود، بازمی‌گرداند یا تنظیم می‌کند. |
| [getProgressCallback()](#getProgressCallback--) | یک شی بازگشت‌صدا برای به‌روزرسانی پیشرفت ذخیره‌سازی بر حسب درصد را نشان می‌دهد. |
| [setProgressCallback(IProgressCallback value)](#setProgressCallback-com.aspose.slides.IProgressCallback-) | یک شی بازگشت‌صدا برای به‌روزرسانی پیشرفت ذخیره‌سازی بر حسب درصد را نشان می‌دهد. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | فونتی را که در صورت عدم یافتن فونت منبع استفاده می‌شود، بازمی‌گرداند یا تنظیم می‌کند. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | فونتی را که در صورت عدم یافتن فونت منبع استفاده می‌شود، بازمی‌گرداند یا تنظیم می‌کند. |
| [getGradientStyle()](#getGradientStyle--) | سبک بصری گرادیان را بازمی‌گرداند یا تنظیم می‌کند. |
| [setGradientStyle(int value)](#setGradientStyle-int-) | سبک بصری گرادیان را بازمی‌گرداند یا تنظیم می‌کند. |
| [getSkipJavaScriptLinks()](#getSkipJavaScriptLinks--) | مشخص می‌کند آیا هنگام ذخیره‌سازی ارائه، لینک‌های فراخوانی JavaScript نادیده گرفته شوند یا نه. |
| [setSkipJavaScriptLinks(boolean value)](#setSkipJavaScriptLinks-boolean-) | مشخص می‌کند آیا هنگام ذخیره‌سازی ارائه، لینک‌های فراخوانی JavaScript نادیده گرفته شوند یا نه. |
### SaveOptions() {#SaveOptions--}
```
public SaveOptions()
```


### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```


یک شی را که هشدارها را دریافت می‌کند و تصمیم می‌گیرد آیا فرآیند بارگذاری ادامه یابد یا متوقف شود، بازمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**بازگشت:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```


یک شی را که هشدارها را دریافت می‌کند و تصمیم می‌گیرد آیا فرآیند بارگذاری ادامه یابد یا متوقف شود، بازمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getProgressCallback() {#getProgressCallback--}
```
public final IProgressCallback getProgressCallback()
```


یک شی بازگشت‌صدا برای به‌روزرسانی پیشرفت ذخیره‌سازی بر حسب درصد را نشان می‌دهد. ببینید [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**بازگشت:**
[IProgressCallback](../../com.aspose.slides/iprogresscallback)
### setProgressCallback(IProgressCallback value) {#setProgressCallback-com.aspose.slides.IProgressCallback-}
```
public final void setProgressCallback(IProgressCallback value)
```


یک شی بازگشت‌صدا برای به‌روزرسانی پیشرفت ذخیره‌سازی بر حسب درصد را نشان می‌دهد. ببینید [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IProgressCallback](../../com.aspose.slides/iprogresscallback) |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public final String getDefaultRegularFont()
```


فونتی را که در صورت عدم یافتن فونت منبع استفاده می‌شود، بازمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن String.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try
>  {
>      HtmlOptions htmlOpts = new HtmlOptions();
>      htmlOpts.setDefaultRegularFont("Arial Black");
>      pres.save("SomePresentation-out-ArialBlack.html", SaveFormat.Html, htmlOpts);
>      htmlOpts.setDefaultRegularFont("Lucida Console");
>      pres.save("Somepresentation-out-LucidaConsole.html", SaveFormat.Html, htmlOpts);
>      PdfOptions pdfOpts = new PdfOptions();
>      pdfOpts.setDefaultRegularFont("Arial Black");
>      pres.save("SomePresentation-out-ArialBlack.pdf", SaveFormat.Pdf, pdfOpts);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**بازگشت:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public final void setDefaultRegularFont(String value)
```


فونتی را که در صورت عدم یافتن فونت منبع استفاده می‌شود، بازمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن String.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try
>  {
>      HtmlOptions htmlOpts = new HtmlOptions();
>      htmlOpts.setDefaultRegularFont("Arial Black");
>      pres.save("SomePresentation-out-ArialBlack.html", SaveFormat.Html, htmlOpts);
>      htmlOpts.setDefaultRegularFont("Lucida Console");
>      pres.save("Somepresentation-out-LucidaConsole.html", SaveFormat.Html, htmlOpts);
>      PdfOptions pdfOpts = new PdfOptions();
>      pdfOpts.setDefaultRegularFont("Arial Black");
>      pres.save("SomePresentation-out-ArialBlack.pdf", SaveFormat.Pdf, pdfOpts);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getGradientStyle() {#getGradientStyle--}
```
public final int getGradientStyle()
```


سبک بصری گرادیان را بازمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن [GradientStyle](../../com.aspose.slides/gradientstyle).

**بازگشت:**
int
### setGradientStyle(int value) {#setGradientStyle-int-}
```
public final void setGradientStyle(int value)
```


سبک بصری گرادیان را بازمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن [GradientStyle](../../com.aspose.slides/gradientstyle).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getSkipJavaScriptLinks() {#getSkipJavaScriptLinks--}
```
public final boolean getSkipJavaScriptLinks()
```


مشخص می‌کند آیا هنگام ذخیره‌سازی ارائه، لینک‌های فراخوانی JavaScript نادیده گرفته شوند یا نه. قابل‌خواندن/قابل‌نوشتن boolean. مقدار پیش‌فرض false است.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      HtmlOptions htmlOptions = new HtmlOptions();
>      htmlOptions.setSkipJavaScriptLinks(true);
>      pres.save("result_without_JavaScript_links.html", SaveFormat.Html, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


زمانی که این ویژگی به true تنظیم شود، لینک‌های فراخوانی JavaScript هنگام ذخیره‌سازی نادیده گرفته می‌شوند.

زمانی که این ویژگی به false تنظیم شود، تمام لینک‌ها ذخیره می‌شوند.

**بازگشت:**
boolean
### setSkipJavaScriptLinks(boolean value) {#setSkipJavaScriptLinks-boolean-}
```
public final void setSkipJavaScriptLinks(boolean value)
```


مشخص می‌کند آیا هنگام ذخیره‌سازی ارائه، لینک‌های فراخوانی JavaScript نادیده گرفته شوند یا نه. قابل‌خواندن/قابل‌نوشتن boolean. مقدار پیش‌فرض false است.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      HtmlOptions htmlOptions = new HtmlOptions();
>      htmlOptions.setSkipJavaScriptLinks(true);
>      pres.save("result_without_JavaScript_links.html", SaveFormat.Html, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

زمانی که این ویژگی به true تنظیم شود، لینک‌های فراخوانی JavaScript هنگام ذخیره‌سازی نادیده گرفته می‌شوند.

زمانی که این ویژگی به false تنظیم شود، تمام لینک‌ها ذخیره می‌شوند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |