---
title: IHtml5Options
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر گزینه‌های خروجی‌گیری HTML5 است.
type: docs
url: /fa/com.aspose.slides/ihtml5options/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IHtml5Options extends ISaveOptions
```

یک گزینه‌ی خروجی‌گیری HTML5 را نشان می‌دهد.

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

| Method | Description |
| --- | --- |
| [getAnimateTransitions()](#getAnimateTransitions--) | گزینه‌ی انیمیشن تغییرات را برمی‌گرداند یا تنظیم می‌کند. |
| [setAnimateTransitions(boolean value)](#setAnimateTransitions-boolean-) | گزینه‌ی انیمیشن تغییرات را برمی‌گرداند یا تنظیم می‌کند. |
| [getAnimateShapes()](#getAnimateShapes--) | گزینه‌ی انیمیشن اشکال را برمی‌گرداند یا تنظیم می‌کند. |
| [setAnimateShapes(boolean value)](#setAnimateShapes-boolean-) | گزینه‌ی انیمیشن اشکال را برمی‌گرداند یا تنظیم می‌کند. |
| [getEmbedImages()](#getEmbedImages--) | گزینه‌ی جاسازی تصویرها را برمی‌گرداند یا تنظیم می‌کند. |
| [setEmbedImages(boolean value)](#setEmbedImages-boolean-) | گزینه‌ی جاسازی تصویرها را برمی‌گرداند یا تنظیم می‌کند. |
| [getOutputPath()](#getOutputPath--) | محل ذخیره‌سازی منابع خارجی را تعیین می‌کند. |
| [setOutputPath(String value)](#setOutputPath-java.lang.String-) | محل ذخیره‌سازی منابع خارجی را تعیین می‌کند. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | مقداری که نشان می‌دهد آیا متن بدون استفاده از لیگچرها رندر می‌شود را دریافت یا تنظیم می‌کند. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | مقداری که نشان می‌دهد آیا متن بدون استفاده از لیگچرها رندر می‌شود را دریافت یا تنظیم می‌کند. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | حالت قرارگیری اسلایدها بر روی صفحه هنگام خروجی‌گیری یک ارائه [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) را دریافت یا تنظیم می‌کند. |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | حالت قرارگیری اسلایدها بر روی صفحه هنگام خروجی‌گیری یک ارائه [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) را دریافت یا تنظیم می‌کند. |

### getAnimateTransitions() {#getAnimateTransitions--}
```
public abstract boolean getAnimateTransitions()
```

گزینه‌ی انیمیشن تغییرات را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن boolean.

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

گزینه‌ی انیمیشن تغییرات را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن boolean.

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

گزینه‌ی انیمیشن اشکال را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن boolean.

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

گزینه‌ی انیمیشن اشکال را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن boolean.

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

گزینه‌ی جاسازی تصویرها را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن boolean.

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

گزینه‌ی جاسازی تصویرها را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن boolean.

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

محل ذخیره‌سازی منابع خارجی را تعیین می‌کند. قابل خواندن/نوشتن String.

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

محل ذخیره‌سازی منابع خارجی را تعیین می‌کند. قابل خواندن/نوشتن String.

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
public abstract boolean getDisableFontLigatures()
```

یک مقدار را که نشان می‌دهد آیا متن بدون استفاده از لیگچرها رندر می‌شود را دریافت یا تنظیم می‌کند. وقتی به true تنظیم شود، لیگچرها در خروجی رندر شده غیرفعال خواهند شد. به طور پیش‌فرض، این خصوصیت false تنظیم شده است.

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

**بازگشت:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public abstract void setDisableFontLigatures(boolean value)
```

یک مقدار را که نشان می‌دهد آیا متن بدون استفاده از لیگچرها رندر می‌شود را دریافت یا تنظیم می‌کند. وقتی به true تنظیم شود، لیگچرها در خروجی رندر شده غیرفعال خواهند شد. به طور پیش‌فرض، این خصوصیت false تنظیم شده است.

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
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

حالت قرارگیری اسلایدها بر روی صفحه هنگام خروجی‌گیری یک ارائه [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) را دریافت یا تنظیم می‌کند.

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

حالت قرارگیری اسلایدها بر روی صفحه هنگام خروجی‌گیری یک ارائه [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) را دریافت یا تنظیم می‌کند.

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