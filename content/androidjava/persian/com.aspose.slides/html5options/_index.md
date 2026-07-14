---
title: Html5Options
second_title: مرجع API جاوا برای Aspose.Slides برای Android
description: نمایانگر گزینه‌های خروجی HTML5 است.
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

نمایانگر گزینه‌های خروجی HTML5 است.

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
| [Html5Options()](#Html5Options--) | سازندهٔ پیش‌فرض. |
## متدها

| متد | توضیح |
| --- | --- |
| [getAnimateTransitions()](#getAnimateTransitions--) | مقدار گزینهٔ انیمیشن انتقال‌ها را برمی‌گرداند یا تنظیم می‌کند. |
| [setAnimateTransitions(boolean value)](#setAnimateTransitions-boolean-) | مقدار گزینهٔ انیمیشن انتقال‌ها را برمی‌گرداند یا تنظیم می‌کند. |
| [getAnimateShapes()](#getAnimateShapes--) | مقدار گزینهٔ انیمیشن اشکال را برمی‌گرداند یا تنظیم می‌کند. |
| [setAnimateShapes(boolean value)](#setAnimateShapes-boolean-) | مقدار گزینهٔ انیمیشن اشکال را برمی‌گرداند یا تنظیم می‌کند. |
| [getEmbedImages()](#getEmbedImages--) | مقدار گزینهٔ جاسازی تصاویر را برمی‌گرداند یا تنظیم می‌کند. |
| [setEmbedImages(boolean value)](#setEmbedImages-boolean-) | مقدار گزینهٔ جاسازی تصاویر را برمی‌گرداند یا تنظیم می‌کند. |
| [getOutputPath()](#getOutputPath--) | تعیین می‌کند منابع خارجی در کجا ذخیره شوند. |
| [setOutputPath(String value)](#setOutputPath-java.lang.String-) | تعیین می‌کند منابع خارجی در کجا ذخیره شوند. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | مقدار نشان‌دهندهٔ اینکه متن بدون استفاده از لیگچرها رندر شود را می‌گیرد یا تنظیم می‌کند. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | مقدار نشان‌دهندهٔ اینکه متن بدون استفاده از لیگچرها رندر شود را می‌گیرد یا تنظیم می‌کند. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | حالت قرارگیری اسلایدها روی صفحه هنگام خروجی گرفتن ارائه [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) را می‌گیرد یا تنظیم می‌کند. |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | حالت قرارگیری اسلایدها روی صفحه هنگام خروجی گرفتن ارائه [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) را می‌گیرد یا تنظیم می‌کند. |
### Html5Options() {#Html5Options--}
```
public Html5Options()
```

سازندهٔ پیش‌فرض.

### getAnimateTransitions() {#getAnimateTransitions--}
```
public final boolean getAnimateTransitions()
```

مقدار گزینهٔ انیمیشن انتقال‌ها را برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل‌نوشتن Boolean.

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

**برگشت:**
boolean
### setAnimateTransitions(boolean value) {#setAnimateTransitions-boolean-}
```
public final void setAnimateTransitions(boolean value)
```

مقدار گزینهٔ انیمیشن انتقال‌ها را برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل‌نوشتن Boolean.

====================

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

مقدار گزینهٔ انیمیشن اشکال را برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل‌نوشتن Boolean.

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

**برگشت:**
boolean
### setAnimateShapes(boolean value) {#setAnimateShapes-boolean-}
```
public final void setAnimateShapes(boolean value)
```

مقدار گزینهٔ انیمیشن اشکال را برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل‌نوشتن Boolean.

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

مقدار گزینهٔ جاسازی تصاویر را برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل‌نوشتن Boolean.

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

**برگشت:**
boolean
### setEmbedImages(String value) {#setEmbedImages-boolean-}
```
public final void setEmbedImages(boolean value)
```

مقدار گزینهٔ جاسازی تصاویر را برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل‌نوشتن Boolean.

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

تعیین می‌کند منابع خارجی در کجا ذخیره شوند. خواندنی/قابل‌نوشتن String.

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

**برگشت:**
java.lang.String
### setOutputPath(String value) {#setOutputPath-java.lang.String-}
```
public final void setOutputPath(String value)
```

تعیین می‌کند منابع خارجی در کجا ذخیره شوند. خواندنی/قابل‌نوشتن String.

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

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

مقدار نشان‌دهندهٔ اینکه متن بدون استفاده از لیگچرها رندر شود را می‌گیرد یا تنظیم می‌کند. هنگام تنظیم روی true، لیگچرها در خروجی رندر شده غیر فعال می‌شوند. به طور پیش‌فرض، این ویژگی روی false تنظیم شده است.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Html5Options options = new Html5Options();
>      options.setDisableFontLigatures(true); // غیرفعال کردن لیگچرها در رندر متن
> 
>      pres.save("output.html", SaveFormat.Html5, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**برگشت:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public final void setDisableFontLigatures(boolean value)
```

مقدار نشان‌دهندهٔ اینکه متن بدون استفاده از لیگچرها رندر شود را می‌گیرد یا تنظیم می‌کند. هنگام تنظیم روی true، لیگچرها در خروجی رندر شده غیر فعال می‌شوند. به طور پیش‌فرض، این ویژگی روی false تنظیم شده است.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Html5Options options = new Html5Options();
>      options.setDisableFontLigatures(true); // غیرفعال کردن لیگچرها در رندر متن
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

حالت قرارگیری اسلایدها روی صفحه هنگام خروجی گرفتن ارائه [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) را می‌گیرد یا تنظیم می‌کند.

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

**برگشت:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

حالت قرارگیری اسلایدها روی صفحه هنگام خروجی گرفتن ارائه [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) را می‌گیرد یا تنظیم می‌کند.

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