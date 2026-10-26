---
title: WebDocument
second_title: مرجع API Aspose.Slides برای Java
description: نمایانگر یک فرم انتقال ارائه برای ذخیره‌سازی در قالب وب است.
type: docs
url: /fa/com.aspose.slides/webdocument/
---
**ارث‌بری:**
java.lang.Object
```
public class WebDocument
```

نمایانگر یک فرم انتقال ارائه برای ذخیره‌سازی در قالب وب است.
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [WebDocument(WebDocumentOptions options)](#WebDocument-com.aspose.slides.WebDocumentOptions-) | [WebDocument](../../com.aspose.slides/webdocument) سازنده. |
## متدها

| متد | توضیح |
| --- | --- |
| [save()](#save--) | خروجی سند را ذخیره می‌کند. |
| [getInput()](#getInput--) | مجموعه‌ای از عناصر ورودی (قالب‌ها) سند را برمی‌گرداند. |
| [getOutput()](#getOutput--) | مجموعه‌ای از عناصر خروجی سند را برمی‌گرداند. |
| [getGlobal()](#getGlobal--) | ذخیره‌سازی سراسری سند را برمی‌گرداند. |
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


مجموعه‌ای از عناصر ورودی (قالب‌ها) سند را برمی‌گرداند. فقط خواندنی [Input](../../com.aspose.slides/input)(\#getInput.getInput).

**بازگرداندن:**
[Input](../../com.aspose.slides/input)
### getOutput() {#getOutput--}
```
public final Output getOutput()
```


مجموعه‌ای از عناصر خروجی سند را برمی‌گرداند. فقط خواندنی [Output](../../com.aspose.slides/output)(\#getOutput.getOutput).

--------------------

> ```
> WebDocumentOptions options = new WebDocumentOptions();
> 
>   WebDocument document = new WebDocument(options);
> 
>   // افزودن ویژگی "slideMargin" برای استفاده از قالب‌ها
>   document.getGlobal().put("slideMargin", 10);
> 
>   // ... تنظیم گزینه‌های دیگر سند و سپس ذخیره سند
>   document.save();
> ```

**بازگرداندن:**
[Output](../../com.aspose.slides/output)
### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```


ذخیره‌سازی سراسری سند را برمی‌گرداند. فقط خواندنی [Storage](../../com.aspose.slides/storage).

--------------------

> ```
> Using this (#getGlobal.getGlobal) property (implementation of [Storage](../../com.aspose.slides/storage) interface) a
>   property can be put to use it later in the template:
>   
>   WebDocumentOptions options = new WebDocumentOptions();
> 
>   WebDocument document = new WebDocument(options);
> 
>   // اضافه کردن ویژگی "slideMargin" برای استفاده از قالب‌ها
>   document.getGlobal().put("slideMargin", 10);
> 
>   // ... تنظیم گزینه‌های دیگر سند و سپس ذخیره سند
>   document.save();
> ```

**بازگرداندن:**
[Storage](../../com.aspose.slides/storage)