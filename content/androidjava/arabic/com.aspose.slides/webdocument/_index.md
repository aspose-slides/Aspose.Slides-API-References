---
title: WebDocument
second_title: Aspose.Slides لـ Android عبر مرجع API الخاص بـ Java
description: يمثل نموذج تحويل للعرض لتخزينه بصيغة ويب.
type: docs
url: /ar/com.aspose.slides/webdocument/
---
**الإرث:**
java.lang.Object
```
public class WebDocument
```

يمثل نموذج تحويل للعرض لتخزينه بصيغة ويب.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [WebDocument(WebDocumentOptions options)](#WebDocument-com.aspose.slides.WebDocumentOptions-) | [WebDocument](../../com.aspose.slides/webdocument) المنشئ. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [save()](#save--) | Saves the document output. |
| [getInput()](#getInput--) | Returns collection of input elements (templates) of the document. |
| [getOutput()](#getOutput--) | Returns collection of output elements of the document. |
| [getGlobal()](#getGlobal--) | Returns global storage of the document. |
### WebDocument(WebDocumentOptions options) {#WebDocument-com.aspose.slides.WebDocumentOptions-}
```
public WebDocument(WebDocumentOptions options)
```

[WebDocument](../../com.aspose.slides/webdocument) المنشئ.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | [WebDocumentOptions](../../com.aspose.slides/webdocumentoptions) | Options set for the document. |

### save() {#save--}
```
public final void save()
```

Saves the document output.

### getInput() {#getInput--}
```
public final Input getInput()
```

Returns collection of input elements (templates) of the document. للقراءة فقط [Input](../../com.aspose.slides/input)(\#getInput.getInput).

**القيمة المرجعة:**
[Input](../../com.aspose.slides/input)
### getOutput() {#getOutput--}
```
public final Output getOutput()
```

Returns collection of output elements of the document. للقراءة فقط [Output](../../com.aspose.slides/output)(\#getOutput.getOutput).

--------------------

> ```
> WebDocumentOptions options = new WebDocumentOptions();
> 
>   WebDocument document = new WebDocument(options);
> 
>   // وضع خاصية "slideMargin" للاستخدام من القوالب
>   document.getGlobal().put("slideMargin", 10);
> 
>   // ... إعداد خيارات أخرى للمستند ثم حفظ المستند
>   document.save();
> ```

**القيمة المرجعة:**
[Output](../../com.aspose.slides/output)
### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```

Returns global storage of the document. للقراءة فقط [Storage](../../com.aspose.slides/storage).

--------------------

> ```
> Using this (#getGlobal.getGlobal) property (implementation of [Storage](../../com.aspose.slides/storage) interface) a
>   property can be put to use it later in the template:
>   
>   WebDocumentOptions options = new WebDocumentOptions();
> 
>   WebDocument document = new WebDocument(options);
> 
>   // وضع خاصية "slideMargin" للاستخدام من القوالب
>   document.getGlobal().put("slideMargin", 10);
> 
>   // ... إعداد خيارات أخرى للمستند ثم حفظ المستند
>   document.save();
> ```

**القيمة المرجعة:**
[Storage](../../com.aspose.slides/storage)