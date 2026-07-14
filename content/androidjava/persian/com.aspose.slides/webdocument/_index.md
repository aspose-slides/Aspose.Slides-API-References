---
title: WebDocument
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: یک فرم انتقال از ارائه برای ذخیره در قالب وب را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/webdocument/
---
**وراثت:**
java.lang.Object
```
public class WebDocument
```

یک فرم انتقال از ارائه برای ذخیره در قالب وب را نشان می‌دهد.
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [WebDocument(WebDocumentOptions options)](#WebDocument-com.aspose.slides.WebDocumentOptions-) | [WebDocument](../../com.aspose.slides/webdocument) سازنده. |
## متدها

| متد | توضیح |
| --- | --- |
| [save()](#save--) | خروجی سند را ذخیره می‌کند. |
| [getInput()](#getInput--) | مجموعه‌ای از عناصر ورودی (قالب‌ها) سند را باز می‌گرداند. |
| [getOutput()](#getOutput--) | مجموعه‌ای از عناصر خروجی سند را باز می‌گرداند. |
| [getGlobal()](#getGlobal--) | ذخیره‌سازی سراسری سند را باز می‌گرداند. |
### WebDocument(WebDocumentOptions options) {#WebDocument-com.aspose.slides.WebDocumentOptions-}
```
public WebDocument(WebDocumentOptions options)
```

[WebDocument](../../com.aspose.slides/webdocument) سازنده.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [WebDocumentOptions](../../com.aspose.slides/webdocumentoptions) | گزینه‌های تنظیم شده برای سند. |

### save() {#save--}
```
public final void save()
```

خروجی سند را ذخیره می‌کند.

### getInput() {#getInput--}
```
public final Input getInput()
```

مجموعه‌ای از عناصر ورودی (قالب‌ها) سند را باز می‌گرداند. فقط خواندنی [Input](../../com.aspose.slides/input)(\#getInput.getInput).

**بازگشت:**
[Input](../../com.aspose.slides/input)
### getOutput() {#getOutput--}
```
public final Output getOutput()
```

مجموعه‌ای از عناصر خروجی سند را باز می‌گرداند. فقط خواندنی [Output](../../com.aspose.slides/output)(\#getOutput.getOutput).

--------------------

> ```
> WebDocumentOptions options = new WebDocumentOptions();
> 
>   WebDocument document = new WebDocument(options);
> 
>   // قرار دادن ویژگی "slideMargin" برای استفاده از قالب‌ها
>   document.getGlobal().put("slideMargin", 10);
> 
>   // ... تنظیم گزینه‌های دیگر سند و سپس ذخیره سند
>   document.save();
> ```

**بازگشت:**
[Output](../../com.aspose.slides/output)
### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```

ذخیره‌سازی سراسری سند را باز می‌گرداند. فقط خواندنی [Storage](../../com.aspose.slides/storage).

--------------------

> ```
> Using this (#getGlobal.getGlobal) property (implementation of [Storage](../../com.aspose.slides/storage) interface) a
>   property can be put to use it later in the template:
>   
>   WebDocumentOptions options = new WebDocumentOptions();
> 
>   WebDocument document = new WebDocument(options);
> 
>   // قرار دادن ویژگی "slideMargin" برای استفاده از قالب‌ها
>   document.getGlobal().put("slideMargin", 10);
> 
>   // ... تنظیم گزینه‌های دیگر سند و سپس ذخیره سند
>   document.save();
> ```

**بازگشت:**
[Storage](../../com.aspose.slides/storage)