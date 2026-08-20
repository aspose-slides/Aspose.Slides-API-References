---
title: WebDocument
second_title: مرجع API Aspose.Slides للـ Java
description: يمثل صيغة انتقالية للعرض لتخزينها بتنسيق ويب.
type: docs
url: /ar/com.aspose.slides/webdocument/
---
**الوراثة:**
java.lang.Object
```
public class WebDocument
```

يمثل صيغة انتقالية للعرض لتخزينها بتنسيق ويب.
## المنشئات

| Constructor | Description |
| --- | --- |
| [WebDocument(WebDocumentOptions options)](#WebDocument-com.aspose.slides.WebDocumentOptions-) | [WebDocument](../../com.aspose.slides/webdocument) منشئ. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [save()](#save--) | يحفظ ناتج المستند. |
| [getInput()](#getInput--) | يعيد مجموعة عناصر الإدخال (القوالب) للمستند. |
| [getOutput()](#getOutput--) | يعيد مجموعة عناصر الإخراج للمستند. |
| [getGlobal()](#getGlobal--) | يعيد التخزين العالمي للمستند. |
### WebDocument(WebDocumentOptions options) {#WebDocument-com.aspose.slides.WebDocumentOptions-}
```
public WebDocument(WebDocumentOptions options)
```

[WebDocument](../../com.aspose.slides/webdocument) منشئ.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | [WebDocumentOptions](../../com.aspose.slides/webdocumentoptions) | الخيارات المحددة للمستند. |
### save() {#save--}
```
public final void save()
```

يحفظ ناتج المستند.

### getInput() {#getInput--}
```
public final Input getInput()
```

يعيد مجموعة عناصر الإدخال (القوالب) للمستند. للقراءة فقط [Input](../../com.aspose.slides/input)(\#getInput.getInput).

**الإرجاع:**
[Input](../../com.aspose.slides/input)
### getOutput() {#getOutput--}
```
public final Output getOutput()
```

يعيد مجموعة عناصر الإخراج للمستند. للقراءة فقط [Output](../../com.aspose.slides/output)(\#getOutput.getOutput).

--------------------

> ```
> WebDocumentOptions options = new WebDocumentOptions();
> 
>   WebDocument document = new WebDocument(options);
> 
>   // ضع خاصية "slideMargin" للاستخدام من القوالب
>   document.getGlobal().put("slideMargin", 10);
> 
>   // ... إعداد خيارات أخرى للمستند ثم حفظ المستند
>   document.save();
> ```

**الإرجاع:**
[Output](../../com.aspose.slides/output)
### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```

يعيد التخزين العالمي للمستند. للقراءة فقط [Storage](../../com.aspose.slides/storage).

--------------------

> ```
> Using this (#getGlobal.getGlobal) property (implementation of [Storage](../../com.aspose.slides/storage) interface) a
>   property can be put to use it later in the template:
>   
>   WebDocumentOptions options = new WebDocumentOptions();
> 
>   WebDocument document = new WebDocument(options);
> 
>   // ضع خاصية "slideMargin" للاستخدام من القوالب
>   document.getGlobal().put("slideMargin", 10);
> 
>   // ... إعداد خيارات أخرى للمستند ثم حفظ المستند
>   document.save();
> ```

**الإرجاع:**
[Storage](../../com.aspose.slides/storage)