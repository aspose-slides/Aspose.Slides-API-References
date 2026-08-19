---
title: ISaveOptions
second_title: Aspose.Slides for Java API Reference
description: Options that control how a presentation is saved.
type: docs
url: /fa/com.aspose.slides/isaveoptions/
---```
public interface ISaveOptions
```

گزینه‌هایی که نحوه ذخیره‌سازی یک ارائه را کنترل می‌کنند.
## متدها

| متد | توضیح |
| --- | --- |
| [getWarningCallback()](#getWarningCallback--) | شیئی را که هشدارها را دریافت می‌کند و تصمیم می‌گیرد آیا فرآیند بارگذاری ادامه یابد یا متوقف شود، برمی‌گرداند یا تنظیم می‌کند. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | شیئی را که هشدارها را دریافت می‌کند و تصمیم می‌ دهد آیا فرآیند بارگذاری ادامه یابد یا متوقف شود، برمی‌گرداند یا تنظیم می‌کند. |
| [getProgressCallback()](#getProgressCallback--) | شیء callback را برای به‌روزرسانی‌های پیشرفت ذخیره‌سازی به درصد نشان می‌دهد. |
| [setProgressCallback(IProgressCallback value)](#setProgressCallback-com.aspose.slides.IProgressCallback-) | شیء callback را برای به‌روزرسانی‌های پیشرفت ذخیره‌سازی به درصد نشان می‌دهد. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | فونتی را که در صورتی که فونت منبع پیدا نشود، استفاده می‌شود، برمی‌گرداند یا تنظیم می‌کند. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | فونتی را که در صورتی که فونت منبع پیدا نشود، استفاده می‌شود، برمی‌گرداند یا تنظیم می‌کند. |
| [getGradientStyle()](#getGradientStyle--) | سبک بصری گرادینت را برمی‌گرداند یا تنظیم می‌کند. |
| [setGradientStyle(int value)](#setGradientStyle-int-) | سبک بصری گرادینت را برمی‌گرداند یا تنظیم می‌کند. |
| [getSkipJavaScriptLinks()](#getSkipJavaScriptLinks--) | مشخص می‌کند که هنگام ذخیره‌سازی ارائه لینک‌های هیپرمتنی با فراخوانی‌های JavaScript نادیده گرفته شوند یا خیر. |
| [setSkipJavaScriptLinks(boolean value)](#setSkipJavaScriptLinks-boolean-) | مشخص می‌کند که هنگام ذخیره‌سازی ارائه لینک‌های هیپرمتنی با فراخوانی‌های JavaScript نادیده گرفته شوند یا خیر. |

### getWarningCallback() {#getWarningCallback--}
```
public abstract IWarningCallback getWarningCallback()
```

شیئی را که هشدارها را دریافت می‌کند و تصمیم می‌گیرد آیا فرآیند بارگذاری ادامه یابد یا متوقف شود، برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**بازگشت:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)

### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public abstract void setWarningCallback(IWarningCallback value)
```

شیئی را که هشدارها را دریافت می‌کند و تصمیم می‌گیرد آیا فرآیند بارگذاری ادامه یابد یا متوقف شود، برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getProgressCallback() {#getProgressCallback--}
```
public abstract IProgressCallback getProgressCallback()
```

شیء callback را برای به‌روزرسانی‌های پیشرفت ذخیره‌سازی به درصد نشان می‌دهد. ببینید [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**بازگشت:**
[IProgressCallback](../../com.aspose.slides/iprogresscallback)

### setProgressCallback(IProgressCallback value) {#setProgressCallback-com.aspose.slides.IProgressCallback-}
```
public abstract void setProgressCallback(IProgressCallback value)
```

شیء callback را برای به‌روزرسانی‌های پیشرفت ذخیره‌سازی به درصد نشان می‌دهد. ببینید [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IProgressCallback](../../com.aspose.slides/iprogresscallback) |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public abstract String getDefaultRegularFont()
```

فونتی را که در صورتی که فونت منبع پیدا نشود، استفاده می‌شود، برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

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
public abstract void setDefaultRegularFont(String value)
```

فونتی را که در صورتی که فونت منبع پیدا نشود، استفاده می‌شود، برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

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
public abstract int getGradientStyle()
```

سبک بصری گرادینت را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [GradientStyle](../../com.aspose.slides/gradientstyle).

**بازگشت:**
int

### setGradientStyle(int value) {#setGradientStyle-int-}
```
public abstract void setGradientStyle(int value)
```

سبک بصری گرادینت را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [GradientStyle](../../com.aspose.slides/gradientstyle).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getSkipJavaScriptLinks() {#getSkipJavaScriptLinks--}
```
public abstract boolean getSkipJavaScriptLinks()
```

مشخص می‌کند که هنگام ذخیره‌سازی ارائه لینک‌های هیپرمتنی با فراخوانی‌های JavaScript نادیده گرفته شوند یا خیر. قابل خواندن/نوشتن boolean. مقدار پیش‌فرض false است.

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

--------------------

زمانی که این ویژگی true باشد، لینک‌های هیپرمتنی با فراخوانی‌های JavaScript هنگام ذخیره‌سازی نادیده گرفته می‌شوند.

زمانی که این ویژگی false باشد، تمام لینک‌های هیپرمتنی ذخیره می‌شوند.

**بازگشت:**
boolean

### setSkipJavaScriptLinks(boolean value) {#setSkipJavaScriptLinks-boolean-}
```
public abstract void setSkipJavaScriptLinks(boolean value)
```

مشخص می‌کند که هنگام ذخیره‌سازی ارائه لینک‌های هیپرمتنی با فراخوانی‌های JavaScript نادیده گرفته شوند یا خیر. قابل خواندن/نوشتن boolean. مقدار پیش‌فرض false است.

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

--------------------

زمانی که این ویژگی true باشد، لینک‌های هیپرمتنی با فراخوانی‌های JavaScript هنگام ذخیره‌سازی نادیده گرفته می‌شوند.

زمانی که این ویژگی false باشد، تمام لینک‌های هیپرمتنی ذخیره می‌شوند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |