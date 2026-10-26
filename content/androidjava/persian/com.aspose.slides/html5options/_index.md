---
title: Html5Options
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: نمایانگر گزینه‌های خروجی HTML5.
type: docs
url: /fa/com.aspose.slides/html5options/
---
**Inheritance:**
وراثت: java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**All Implemented Interfaces:**
تمام رابط‌های پیاده‌سازی‌شده: [com.aspose.slides.IHtml5Options](../../com.aspose.slides/ihtml5options)
```
public class Html5Options extends SaveOptions implements IHtml5Options
```

نمایش گزینه‌های خروجی HTML5.

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
## سازنده‌ها

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
| [getEmbedImages()](#getEmbedImages--) | مقدار یا تنظیم گزینهٔ جاسازی تصویرها. |
| [setEmbedImages(boolean value)](#setEmbedImages-boolean-) | مقدار یا تنظیم گزینهٔ جاسازی تصویرها. |
| [getOutputPath()](#getOutputPath--) | مشخص می‌کند که منابع خارجی کجا ذخیره شوند. |
| [setOutputPath(String value)](#setOutputPath-java.lang.String-) | مشخص می‌کند که منابع خارجی کجا ذخیره شوند. |
| [getPicturesCompression()](#getPicturesCompression--) | سطح فشرده‌سازی تصاویر را نشان می‌دهد |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | سطح فشرده‌سازی تصاویر را نشان می‌دهد |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | دریافت یا تنظیم مقداری که نشان می‌دهد آیا متن بدون استفاده از لیگاتورها رندر می‌شود. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | دریافت یا تنظیم مقداری که نشان می‌دهد آیا متن بدون استفاده از لیگاتورها رندر می‌شود. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | دریافت یا تنظیم حالت قرارگیری اسلایدها روی صفحه هنگام خروجی‌گیری از ارائه [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | دریافت یا تنظیم حالت قرارگیری اسلایدها روی صفحه هنگام خروجی‌گیری از ارائه [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
### Html5Options() {#Html5Options--}
```
public Html5Options()
```

سازنده پیش‌فرض.

### getAnimateTransitions() {#getAnimateTransitions--}
```
public final boolean getAnimateTransitions()
```

مقدار یا تنظیم گزینهٔ انیمیشن انتقال‌ها. خواندن/نوشتن بولی.

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

**Returns:**
boolean
### setAnimateTransitions(boolean value) {#setAnimateTransitions-boolean-}
```
public final void setAnimateTransitions(boolean value)
```

مقدار یا تنظیم گزینهٔ انیمیشن انتقال‌ها. خواندن/نوشتن بولی.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAnimateShapes() {#getAnimateShapes--}
```
public final boolean getAnimateShapes()
```

مقدار یا تنظیم گزینهٔ انیمیشن اشکال. خواندن/نوشتن بولی.

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

**Returns:**
boolean
### setAnimateShapes(boolean value) {#setAnimateShapes-boolean-}
```
public final void setAnimateShapes(boolean value)
```

مقدار یا تنظیم گزینهٔ انیمیشن اشکال. خواندن/نوشتن بولی.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getEmbedImages() {#getEmbedImages--}
```
public final boolean getEmbedImages()
```

مقدار یا تنظیم گزینهٔ جاسازی تصویرها. خواندن/نوشتن بولی.

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

**Returns:**
boolean
### setEmbedImages(boolean value) {#setEmbedImages-boolean-}
```
public final void setEmbedImages(boolean value)
```

مقدار یا تنظیم گزینهٔ جاسازی تصویرها. خواندن/نوشتن بولی.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getOutputPath() {#getOutputPath--}
```
public final String getOutputPath()
```

مشخص می‌کند که منابع خارجی کجا ذخیره شوند. خواندن/نوشتن رشته.

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

**Returns:**
java.lang.String
### setOutputPath(String value) {#setOutputPath-java.lang.String-}
```
public final void setOutputPath(String value)
```

مشخص می‌کند که منابع خارجی کجا ذخیره شوند. خواندن/نوشتن رشته.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```

سطح فشرده‌سازی تصاویر را نشان می‌دهد

**Returns:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public final void setPicturesCompression(int value)
```

سطح فشرده‌سازی تصاویر را نشان می‌دهد

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

دریافت یا تنظیم مقداری که نشان می‌دهد آیا متن بدون استفاده از لیگاتورها رندر می‌شود. وقتی مقدار true باشد، لیگاتورها در خروجی رندر شده غیرفعال می‌شوند. به طور پیش‌فرض، این ویژگی روی false تنظیم شده است.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Html5Options options = new Html5Options();
>      options.setDisableFontLigatures(true); // غیرفعال‌سازی لیگاتورها در رندر متن
> 
>      pres.save("output.html", SaveFormat.Html5, options);
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

دریافت یا تنظیم مقداری که نشان می‌دهد آیا متن بدون استفاده از لیگاتورها رندر می‌شود. وقتی مقدار true باشد، لیگاتورها در خروجی رندر شده غیرفعال می‌شوند. به طور پیش‌فرض، این ویژگی روی false تنظیم شده است.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Html5Options options = new Html5Options();
>      options.setDisableFontLigatures(true); // غیرفعال‌سازی لیگاتورها در رندر متن
> 
>      pres.save("output.html", SaveFormat.Html5, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

دریافت یا تنظیم حالت قرارگیری اسلایدها روی صفحه هنگام خروجی‌گیری از ارائه [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

**Returns:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

دریافت یا تنظیم حالت قرارگیری اسلایدها روی صفحه هنگام خروجی‌گیری از ارائه [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |