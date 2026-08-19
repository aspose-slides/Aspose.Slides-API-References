---
title: IHtml5Options
second_title: Aspose.Slides برای مرجع API جاوا
description: نمایانگر گزینه‌های خروجی HTML5 است.
type: docs
url: /fa/com.aspose.slides/ihtml5options/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IHtml5Options extends ISaveOptions
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
## متدها

| متد | توضیح |
| --- | --- |
| [getAnimateTransitions()](#getAnimateTransitions--) | مقدار گزینهٔ انیمیشن انتقال‌ها را برمی‌گرداند یا تنظیم می‌کند. |
| [setAnimateTransitions(boolean value)](#setAnimateTransitions-boolean-) | مقدار گزینهٔ انیمیشن انتقال‌ها را برمی‌گرداند یا تنظیم می‌کند. |
| [getAnimateShapes()](#getAnimateShapes--) | مقدار گزینهٔ انیمیشن اشکال را برمی‌گرداند یا تنظیم می‌کند. |
| [setAnimateShapes(boolean value)](#setAnimateShapes-boolean-) | مقدار گزینهٔ انیمیشن اشکال را برمی‌گرداند یا تنظیم می‌کند. |
| [getEmbedImages()](#getEmbedImages--) | مقدار گزینهٔ جاسازی تصاویر را برمی‌گرداند یا تنظیم می‌کند. |
| [setEmbedImages(boolean value)](#setEmbedImages-boolean-) | مقدار گزینهٔ جاسازی تصاویر را برمی‌گرداند یا تنظیم می‌کند. |
| [getOutputPath()](#getOutputPath--) | محل ذخیره‌سازی منابع خارجی را تعیین می‌کند. |
| [setOutputPath(String value)](#setOutputPath-java.lang.String-) | محل ذخیره‌سازی منابع خارجی را تعیین می‌کند. |
| [getPicturesCompression()](#getPicturesCompression--) | نمایانگر سطح فشرده‌سازی تصاویر است. خواندنی/قابل نوشتن PicturesCompression (\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | نمایانگر سطح فشرده‌سازی تصاویر است. خواندنی/قابل نوشتن PicturesCompression (\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)). |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | مقدار نشان‌دهندهٔ اینکه متن بدون استفاده از لیگیچرها رندر شود را برمی‌گرداند یا تنظیم می‌کند. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | مقدار نشان‌دهندهٔ اینکه متن بدون استفاده از لیگیچرها رندر شود را برمی‌گرداند یا تنظیم می‌کند. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | حالت قرارگیری اسلایدها بر صفحه هنگام خروجی‌گیری ارائه را برمی‌گرداند یا تنظیم می‌کند [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | حالت قرارگیری اسلایدها بر صفحه هنگام خروجی‌گیری ارائه را برمی‌گرداند یا تنظیم می‌کند [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |

### getAnimateTransitions() {#getAnimateTransitions--}
```
public abstract boolean getAnimateTransitions()
```

مقدار گزینهٔ انیمیشن انتقال‌ها را برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateTransitions(true);
> 
>      pres.save("demo-animate-shapes-and-transitions.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**بازگشت:**
boolean
### setAnimateTransitions(boolean value) {#setAnimateTransitions-boolean-}
```
public abstract void setAnimateTransitions(boolean value)
```

مقدار گزینهٔ انیمیشن انتقال‌ها را برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateTransitions(true);
> 
>      pres.save("demo-animate-shapes-and-transitions.html", SaveFormat.Html5, htmlOptions);
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
public abstract boolean getAnimateShapes()
```

مقدار گزینهٔ انیمیشن اشکال را برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateShapes(true);
> 
>      pres.save("demo-animate-shapes-and-transitions.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**بازگشت:**
boolean
### setAnimateShapes(boolean value) {#setAnimateShapes-boolean-}
```
public abstract void setAnimateShapes(boolean value)
```

مقدار گزینهٔ انیمیشن اشکال را برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateShapes(true);
> 
>      pres.save("demo-animate-shapes-and-transitions.html", SaveFormat.Html5, htmlOptions);
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
public abstract boolean getEmbedImages()
```

مقدار گزینهٔ جاسازی تصاویر را برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن boolean.

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
public abstract void setEmbedImages(boolean value)
```

مقدار گزینهٔ جاسازی تصاویر را برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن boolean.

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
public abstract String getOutputPath()
```

محل ذخیره‌سازی منابع خارجی را تعیین می‌کند. خواندنی/قابل نوشتن String.

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
public abstract void setOutputPath(String value)
```

محل ذخیره‌سازی منابع خارجی را تعیین می‌کند. خواندنی/قابل نوشتن String.

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
public abstract int getPicturesCompression()
```

نمایانگر سطح فشرده‌سازی تصاویر است. خواندنی/قابل نوشتن PicturesCompression (\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)).

**بازگشت:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```

نمایانگر سطح فشرده‌سازی تصاویر است. خواندنی/قابل نوشتن PicturesCompression (\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

مقدار نشان‌دهندهٔ اینکه متن بدون استفاده از لیگیچرها رندر شود را برمی‌گرداند یا تنظیم می‌کند. وقتی به true تنظیم شود، لیگیچرها در خروجی رندر شده غیرفعال می‌شوند. به‌طور پیش‌فرض این ویژگی برابر false است.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Html5Options options = new Html5Options();
>      options.setDisableFontLigatures(true); // غیرفعال کردن لیگیچرها در رندر متن
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
public abstract void setDisableFontLigatures(boolean value)
```

مقدار نشان‌دهندهٔ اینکه متن بدون استفاده از لیگیچرها رندر شود را برمی‌گرداند یا تنظیم می‌کند. وقتی به true تنظیم شود، لیگیچرها در خروجی رندر شده غیرفعال می‌شوند. به‌طور پیش‌فرض این ویژگی برابر false است.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Html5Options options = new Html5Options();
>      options.setDisableFontLigatures(true); // غیرفعال کردن لیگیچرها در رندر متن
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
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

حالت قرارگیری اسلایدها بر صفحه هنگام خروجی‌گیری ارائه را برمی‌گرداند یا تنظیم می‌کند [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

حالت قرارگیری اسلایدها بر صفحه هنگام خروجی‌گیری ارائه را برمی‌گرداند یا تنظیم می‌کند [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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