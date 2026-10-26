---
title: Html5Options
second_title: Aspose.Slides برای مرجع API جاوا
description: نمایشگر گزینه‌های خروجی HTML5.
type: docs
url: /fa/com.aspose.slides/html5options/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**All Implemented Interfaces:**
[com.aspose.slides.IHtml5Options](../../com.aspose.slides/ihtml5options)
```
public class Html5Options extends SaveOptions implements IHtml5Options
```

نمایشگر گزینه‌های خروجی HTML5.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateShapes(true);
>      htmlOptions.setAnimateTransitions(true);
> 
>      pres.save("demo-animate-shapes-and-transitions.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## سازندگان

| سازنده | توضیح |
| --- | --- |
| [Html5Options()](#Html5Options--) | سازنده پیش‌فرض. |
## متدها

| متد | توضیح |
| --- | --- |
| [getAnimateTransitions()](#getAnimateTransitions--) | مقدار یا تنظیم گزینهٔ انیمیشن انتقال‌ها. |
| [setAnimateTransitions(boolean value)](#setAnimateTransitions-boolean-) | مقدار یا تنظیم گزینهٔ انیمیشن انتقال‌ها. |
| [getAnimateShapes()](#getAnimateShapes--) | مقدار یا تنظیم گزینهٔ انیمیشن اشکال. |
| [setAnimateShapes(boolean value)](#setAnimateShapes-boolean-) | مقدار یا تنظیم گزینهٔ انیمیشن اشکال. |
| [getEmbedImages()](#getEmbedImages--) | مقدار یا تنظیم گزینهٔ درج تصاویر. |
| [setEmbedImages(boolean value)](#setEmbedImages-boolean-) | مقدار یا تنظیم گزینهٔ درج تصاویر. |
| [getOutputPath()](#getOutputPath--) | تعیین مکان ذخیره‌سازی منابع خارجی. |
| [setOutputPath(String value)](#setOutputPath-java.lang.String-) | تعیین مکان ذخیره‌سازی منابع خارجی. |
| [getPicturesCompression()](#getPicturesCompression--) | نمایانگر سطح فشرده‌سازی تصاویر |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | نمایانگر سطح فشرده‌سازی تصاویر |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | دریافت یا تنظیم مقداری که نشان می‌دهد متن بدون استفاده از لیگاتورها رندر می‌شود. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | دریافت یا تنظیم مقداری که نشان می‌دهد متن بدون استفاده از لیگاتورها رندر می‌شود. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | دریافت یا تنظیم حالت قرارگیری اسلایدها در صفحه هنگام خروجی گرفتن یک ارائه [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | دریافت یا تنظیم حالت قرارگیری اسلایدها در صفحه هنگام خروجی گرفتن یک ارائه [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
### Html5Options() {#Html5Options--}
```
public Html5Options()
```

سازنده پیش‌فرض.

### getAnimateTransitions() {#getAnimateTransitions--}
```
public final boolean getAnimateTransitions()
```

دریافت یا تنظیم گزینهٔ انیمیشن انتقال‌ها. متغیر boolean قابل خواندن/نوشتن.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateTransitions(true);
> 
>      pres.save("demo-animate-transitions.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**بازگشت:**
boolean
### setAnimateTransitions(boolean value) {#setAnimateTransitions-boolean-}
```
public final void setAnimateTransitions(boolean value)
```

دریافت یا تنظیم گزینهٔ انیمیشن انتقال‌ها. متغیر boolean قابل خواندن/نوشتن.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateTransitions(true);
> 
>      pres.save("demo-animate-transitions.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getAnimateShapes() {#getAnimateShapes--}
```
public final boolean getAnimateShapes()
```

دریافت یا تنظیم گزینهٔ انیمیشن اشکال. متغیر boolean قابل خواندن/نوشتن.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateShapes(true);
> 
>      pres.save("demo-animate-shapes.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**بازگشت:**
boolean
### setAnimateShapes(boolean value) {#setAnimateShapes-boolean-}
```
public final void setAnimateShapes(boolean value)
```

دریافت یا تنظیم گزینهٔ انیمیشن اشکال. متغیر boolean قابل خواندن/نوشتن.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateShapes(true);
> 
>      pres.save("demo-animate-shapes.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getEmbedImages() {#getEmbedImages--}
```
public final boolean getEmbedImages()
```

دریافت یا تنظیم گزینهٔ درج تصاویر. متغیر boolean قابل خواندن/نوشتن.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options html5Options = new Html5Options();
>      html5Options.setEmbedImages(false);
>      pres.save("demo-linked-images.html", SaveFormat.Html5, html5Options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**بازگشت:**
boolean
### setEmbedImages(boolean value) {#setEmbedImages-boolean-}
```
public final void setEmbedImages(boolean value)
```

دریافت یا تنظیم گزینهٔ درج تصاویر. متغیر boolean قابل خواندن/نوشتن.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options html5Options = new Html5Options();
>      html5Options.setEmbedImages(false);
>      pres.save("demo-linked-images.html", SaveFormat.Html5, html5Options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getOutputPath() {#getOutputPath--}
```
public final String getOutputPath()
```

تعیین مکان ذخیره‌سازی منابع خارجی. متغیر String قابل خواندن/نوشتن.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options html5Options = new Html5Options();
>      html5Options.setEmbedImages(false);
>      html5Options.setOutputPath(the_desired_path);
>      pres.save("demo-linked-images.html", SaveFormat.Html5, html5Options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**بازگشت:**
java.lang.String
### setOutputPath(String value) {#setOutputPath-java.lang.String-}
```
public final void setOutputPath(String value)
```

تعیین مکان ذخیره‌سازی منابع خارجی. متغیر String قابل خواندن/نوشتن.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options html5Options = new Html5Options();
>      html5Options.setEmbedImages(false);
>      html5Options.setOutputPath(the_desired_path);
>      pres.save("demo-linked-images.html", SaveFormat.Html5, html5Options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```

نمایانگر سطح فشرده‌سازی تصاویر

**بازگشت:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public final void setPicturesCompression(int value)
```

نمایانگر سطح فشرده‌سازی تصاویر

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

دریافت یا تنظیم مقداری که نشان می‌دهد متن بدون استفاده از لیگاتورها رندر می‌شود. هنگام تنظیم به true، لیگاتورها در خروجی رندر شده غیرفعال می‌شوند. به‌طور پیش‌فرض، این ویژگی برابر false است.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Html5Options options = new Html5Options();
>      options.setDisableFontLigatures(true); // در رندر متن لیگاتورها را غیرفعال کنید
> 
>      pres.save("output.html", SaveFormat.Html5, options);
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

دریافت یا تنظیم مقداری که نشان می‌دهد متن بدون استفاده از لیگاتورها رندر می‌شود. هنگام تنظیم به true، لیگاتورها در خروجی رندر شده غیرفعال می‌شوند. به‌طور پیش‌فرض، این ویژگی برابر false است.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Html5Options options = new Html5Options();
>      options.setDisableFontLigatures(true); // در رندر متن لیگاتورها را غیرفعال کنید
> 
>      pres.save("output.html", SaveFormat.Html5, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

دریافت یا تنظیم حالت قرارگیری اسلایدها در صفحه هنگام خروجی گرفتن یک ارائه [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HandoutLayoutingOptions handoutLayoutingOptions = new HandoutLayoutingOptions();
>      handoutLayoutingOptions.setHandout(HandoutType.Handouts4Horizontal);
>      Html5Options options = new Html5Options();
>      options.setSlidesLayoutOptions(handoutLayoutingOptions);
> 
>      pres.save("pres.html", SaveFormat.Html5, options);
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

دریافت یا تنظیم حالت قرارگیری اسلایدها در صفحه هنگام خروجی گرفتن یک ارائه [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HandoutLayoutingOptions handoutLayoutingOptions = new HandoutLayoutingOptions();
>      handoutLayoutingOptions.setHandout(HandoutType.Handouts4Horizontal);
>      Html5Options options = new Html5Options();
>      options.setSlidesLayoutOptions(handoutLayoutingOptions);
> 
>      pres.save("pres.html", SaveFormat.Html5, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |