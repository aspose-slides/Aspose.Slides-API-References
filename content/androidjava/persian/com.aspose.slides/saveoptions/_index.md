---
title: SaveOptions
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: کلاس انتزاعی با گزینه‌هایی که نحوه ذخیره‌سازی یک ارائه را کنترل می‌کند.
type: docs
url: /fa/com.aspose.slides/saveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public abstract class SaveOptions implements ISaveOptions
```

کلاس انتزاعی با گزینه‌هایی که نحوه ذخیره‌سازی یک ارائه را کنترل می‌کند.
## Constructors

| Constructor | Description |
| --- | --- |
| [SaveOptions()](#SaveOptions--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getWarningCallback()](#getWarningCallback--) | بازگرداندن یا تنظیم یک شیء که هشدارها را دریافت می‌کند و تصمیم می‌گیرد آیا فرآیند بارگذاری ادامه یابد یا لغو شود. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | بازگرداندن یا تنظیم یک شیء که هشدارها را دریافت می‌کند و تصمیم می‌گیرد آیا فرآیند بارگذاری ادامه یابد یا لغو شود. |
| [getProgressCallback()](#getProgressCallback--) | نمایانگر یک شیء callback برای به‌روزرسانی درصد پیشرفت ذخیره‌سازی. |
| [setProgressCallback(IProgressCallback value)](#setProgressCallback-com.aspose.slides.IProgressCallback-) | نمایانگر یک شیء callback برای به‌روزرسانی درصد پیشرفت ذخیره‌سازی. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | بازگرداندن یا تنظیم قلم مورد استفاده در صورت عدم یافتن قلم منبع. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | بازگرداندن یا تنظیم قلم مورد استفاده در صورت عدم یافتن قلم منبع. |
| [getGradientStyle()](#getGradientStyle--) | بازگرداندن یا تنظیم سبک بصری گرادیان. |
| [setGradientStyle(int value)](#setGradientStyle-int-) | بازگرداندن یا تنظیم سبک بصری گرادیان. |
| [getSkipJavaScriptLinks()](#getSkipJavaScriptLinks--) | مشخص می‌کند آیا هنگام ذخیره‌سازی ارائه، پیوندهای فراخوانی JavaScript نادیده گرفته شوند. |
| [setSkipJavaScriptLinks(boolean value)](#setSkipJavaScriptLinks-boolean-) | مشخص می‌کند آیا هنگام ذخیره‌سازی ارائه، پیوندهای فراخوانی JavaScript نادیده گرفته شوند. |
### SaveOptions() {#SaveOptions--}
```
public SaveOptions()
```


### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```


بازگرداندن یا تنظیم یک شیء که هشدارها را دریافت می‌کند و تصمیم می‌گیرد آیا فرآیند بارگذاری ادامه یابد یا لغو شود. قابل خواندن/نوشتن [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Returns:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```


بازگرداندن یا تنظیم یک شیء که هشدارها را دریافت می‌کند و تصمیم می‌گیرد آیا فرآیند بارگذاری ادامه یابد یا لغو شود. قابل خواندن/نوشتن [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getProgressCallback() {#getProgressCallback--}
```
public final IProgressCallback getProgressCallback()
```


نمایانگر یک شیء callback برای به‌روزرسانی درصد پیشرفت ذخیره‌سازی. نگاه کنید به [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**Returns:**
[IProgressCallback](../../com.aspose.slides/iprogresscallback)
### setProgressCallback(IProgressCallback value) {#setProgressCallback-com.aspose.slides.IProgressCallback-}
```
public final void setProgressCallback(IProgressCallback value)
```


نمایانگر یک شیء callback برای به‌روزرسانی درصد پیشرفت ذخیره‌سازی. نگاه کنید به [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IProgressCallback](../../com.aspose.slides/iprogresscallback) |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public final String getDefaultRegularFont()
```


بازگرداندن یا تنظیم قلم مورد استفاده در صورت عدم یافتن قلم منبع. قابل خواندن و نوشتن String.

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


**Returns:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public final void setDefaultRegularFont(String value)
```


بازگرداندن یا تنظیم قلم مورد استفاده در صورت عدم یافتن قلم منبع. قابل خواندن و نوشتن String.

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


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getGradientStyle() {#getGradientStyle--}
```
public final int getGradientStyle()
```


بازگرداندن یا تنظیم سبک بصری گرادیان. قابل خواندن/نوشتن [GradientStyle](../../com.aspose.slides/gradientstyle).

**Returns:**
int
### setGradientStyle(int value) {#setGradientStyle-int-}
```
public final void setGradientStyle(int value)
```


بازگرداندن یا تنظیم سبک بصری گرادیان. قابل خواندن/نوشتن [GradientStyle](../../com.aspose.slides/gradientstyle).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSkipJavaScriptLinks() {#getSkipJavaScriptLinks--}
```
public final boolean getSkipJavaScriptLinks()
```


مشخص می‌کند آیا هنگام ذخیره‌سازی ارائه، پیوندهای فراخوانی JavaScript نادیده گرفته شوند. قابل خواندن/نوشتن boolean. مقدار پیش‌فرض false.

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

زمانی که این ویژگی به true تنظیم شود، پیوندهای فراخوانی JavaScript هنگام ذخیره‌سازی نادیده گرفته می‌شوند.

زمانی که این ویژگی به false تنظیم شود، تمام پیوندها ذخیره می‌شوند.

**Returns:**
boolean
### setSkipJavaScriptLinks(boolean value) {#setSkipJavaScriptLinks-boolean-}
```
public final void setSkipJavaScriptLinks(boolean value)
```


مشخص می‌کند آیا هنگام ذخیره‌سازی ارائه، پیوندهای فراخوانی JavaScript نادیده گرفته شوند. قابل خواندن/نوشتن boolean. مقدار پیش‌فرض false.

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

زمانی که این ویژگی به true تنظیم شود، پیوندهای فراخوانی JavaScript هنگام ذخیره‌سازی نادیده گرفته می‌شوند.

زمانی که این ویژگی به false تنظیم شود، تمام پیوندها ذخیره می‌شوند.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |