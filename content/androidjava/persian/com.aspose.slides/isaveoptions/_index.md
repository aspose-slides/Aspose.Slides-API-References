---
title: ISaveOptions
second_title: Aspose.Slides for Android via Java API Reference
description: گزینه‌هایی که نحوه ذخیرهٔ ارائه را کنترل می‌کنند.
type: docs
url: /fa/com.aspose.slides/isaveoptions/
---```
public interface ISaveOptions
```

گزینه‌هایی که نحوه ذخیرهٔ ارائه را کنترل می‌کنند.
## متدها

| متد | توضیح |
| --- | --- |
| [getWarningCallback()](#getWarningCallback--) | شیئی را برمی‌گرداند یا تنظیم می‌کند که هشدارها را دریافت می‌کند و تصمیم می‌گیرد آیا فرآیند بارگذاری ادامه یابد یا متوقف شود. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | شیئی را برمی‌گرداند یا تنظیم می‌کند که هشدارها را دریافت می‌کند و تصمیم می‌گیرد آیا فرآیند بارگذاری ادامه یابد یا متوقف شود. |
| [getProgressCallback()](#getProgressCallback--) | یک شیء باز‌گشت (callback) را که برای به‌روزرسانی پیشرفت ذخیره‌سازی به درصد استفاده می‌شود، نشان می‌دهد. |
| [setProgressCallback(IProgressCallback value)](#setProgressCallback-com.aspose.slides.IProgressCallback-) | یک شیء باز‌گشت (callback) را که برای به‌روزرسانی پیشرفت ذخیره‌سازی به درصد استفاده می‌شود، نشان می‌دهد. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | قلم را که در صورت یافت نشدن قلم منبع استفاده می‌شود، برمی‌گرداند یا تنظیم می‌کند. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | قلم را که در صورت یافت نشدن قلم منبع استفاده می‌شود، برمی‌گرداند یا تنظیم می‌کند. |
| [getGradientStyle()](#getGradientStyle--) | سبک بصری گرادیانت را برمی‌گرداند یا تنظیم می‌کند. |
| [setGradientStyle(int value)](#setGradientStyle-int-) | سبک بصری گرادیانت را برمی‌گرداند یا تنظیم می‌کند. |
| [getSkipJavaScriptLinks()](#getSkipJavaScriptLinks--) | مشخص می‌کند آیا هنگام ذخیره‌سازی ارائه، پیوندهای حاوی فراخوانی‌های JavaScript رد شوند یا خیر. |
| [setSkipJavaScriptLinks(boolean value)](#setSkipJavaScriptLinks-boolean-) | مشخص می‌کند آیا هنگام ذخیره‌سازی ارائه، پیوندهای حاوی فراخوانی‌های JavaScript رد شوند یا خیر. |

### getWarningCallback() {#getWarningCallback--}
```
public abstract IWarningCallback getWarningCallback()
```

شیئی را برمی‌گرداند یا تنظیم می‌کند که هشدارها را دریافت می‌کند و تصمیم می‌گیرد آیا فرآیند بارگذاری ادامه یابد یا متوقف شود. خواندن/نوشتن [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**بازگشت:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)

### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public abstract void setWarningCallback(IWarningCallback value)
```

شیئی را برمی‌گرداند یا تنظیم می‌کند که هشدارها را دریافت می‌کند و تصمیم می‌گیرد آیا فرآیند بارگذاری ادامه یابد یا متوقف شود. خواندن/نوشتن [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getProgressCallback() {#getProgressCallback--}
```
public abstract IProgressCallback getProgressCallback()
```

یک شیء باز‌گشت (callback) را که برای به‌روزرسانی پیشرفت ذخیره‌سازی به درصد استفاده می‌شود، نشان می‌دهد. مشاهده کنید [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**بازگشت:**
[IProgressCallback](../../com.aspose.slides/iprogresscallback)

### setProgressCallback(IProgressCallback value) {#setProgressCallback-com.aspose.slides.IProgressCallback-}
```
public abstract void setProgressCallback(IProgressCallback value)
```

یک شیء باز‌گشت (callback) را که برای به‌روزرسانی پیشرفت ذخیره‌سازی به درصد استفاده می‌شود، نشان می‌دهد. مشاهده کنید [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IProgressCallback](../../com.aspose.slides/iprogresscallback) |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public abstract String getDefaultRegularFont()
```

قلم را که در صورت یافت نشدن قلم منبع استفاده می‌شود، برمی‌گرداند یا تنظیم می‌کند. خواندن-نوشتن String.

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

قلم را که در صورت یافت نشدن قلم منبع استفاده می‌شود، برمی‌گرداند یا تنظیم می‌کند. خواندن-نوشتن String.

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

سبک بصری گرادیانت را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [GradientStyle](../../com.aspose.slides/gradientstyle).

**بازگشت:**
int

### setGradientStyle(int value) {#setGradientStyle-int-}
```
public abstract void setGradientStyle(int value)
```

سبک بصری گرادیانت را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [GradientStyle](../../com.aspose.slides/gradientstyle).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getSkipJavaScriptLinks() {#getSkipJavaScriptLinks--}
```
public abstract boolean getSkipJavaScriptLinks()
```

مشخص می‌کند آیا هنگام ذخیره‌سازی ارائه، پیوندهای حاوی فراخوانی‌های JavaScript رد شوند یا خیر. خواندن/نوشتن boolean. مقدار پیش‌فرض false است.

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

زمانی که این ویژگی برابر true تنظیم شود، پیوندهای حاوی فراخوانی‌های JavaScript در حین ذخیره‌سازی نادیده گرفته می‌شوند.

زمانی که این ویژگی برابر false تنظیم شود، تمام پیوندها ذخیره خواهند شد.

**بازگشت:**
boolean

### setSkipJavaScriptLinks(boolean value) {#setSkipJavaScriptLinks-boolean-}
```
public abstract void setSkipJavaScriptLinks(boolean value)
```

مشخص می‌کند آیا هنگام ذخیره‌سازی ارائه، پیوندهای حاوی فراخوانی‌های JavaScript رد شوند یا خیر. خواندن/نوشتن boolean. مقدار پیش‌فرض false است.

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

زمانی که این ویژگی برابر true تنظیم شود، پیوندهای حاوی فراخوانی‌های JavaScript در حین ذخیره‌سازی نادیده گرفته می‌شوند.

زمانی که این ویژگی برابر false تنظیم شود، تمام پیوندها ذخیره خواهند شد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |