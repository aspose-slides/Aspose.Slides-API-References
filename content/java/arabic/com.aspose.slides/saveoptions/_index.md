---
title: SaveOptions
second_title: مرجع API لـ Aspose.Slides للغة Java
description: فئة مجردة تحتوي على خيارات تتحكم في طريقة حفظ العرض التقديمي.
type: docs
url: /ar/com.aspose.slides/saveoptions/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public abstract class SaveOptions implements ISaveOptions
```

فئة مجردة مع خيارات تتحكم في كيفية حفظ العرض التقديمي.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [SaveOptions()](#SaveOptions--) |  |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getWarningCallback()](#getWarningCallback--) | يرجع أو يضبط كائنًا يتلقى التحذيرات ويقرر ما إذا كانت عملية التحميل ستستمر أو ستُلغى. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | يرجع أو يضبط كائنًا يتلقى التحذيرات ويقرر ما إذا كانت عملية التحميل ستستمر أو ستُلغى. |
| [getProgressCallback()](#getProgressCallback--) | يمثل كائنًا لاستدعاء رد الاتصال لتحديثات تقدم الحفظ كنسبة مئوية. |
| [setProgressCallback(IProgressCallback value)](#setProgressCallback-com.aspose.slides.IProgressCallback-) | يمثل كائنًا لاستدعاء رد الاتصال لتحديثات تقدم الحفظ كنسبة مئوية. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | يرجع أو يضبط الخط المستخدم في حال عدم العثور على الخط المصدر. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | يرجع أو يضبط الخط المستخدم في حال عدم العثور على الخط المصدر. |
| [getGradientStyle()](#getGradientStyle--) | يرجع أو يضبط النمط البصري للتدرج. |
| [setGradientStyle(int value)](#setGradientStyle-int-) | يرجع أو يضبط النمط البصري للتدرج. |
| [getSkipJavaScriptLinks()](#getSkipJavaScriptLinks--) | حدد ما إذا كان يجب تخطي الروابط التشعبية التي تحتوي على استدعاءات JavaScript عند حفظ العرض التقديمي. |
| [setSkipJavaScriptLinks(boolean value)](#setSkipJavaScriptLinks-boolean-) | حدد ما إذا كان يجب تخطي الروابط التشعبية التي تحتوي على استدعاءات JavaScript عند حفظ العرض التقديمي. |
### SaveOptions() {#SaveOptions--}
```
public SaveOptions()
```


### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```


يرجع أو يضبط كائنًا يتلقى التحذيرات ويقرر ما إذا كانت عملية التحميل ستستمر أو ستُلغى. قراءة/كتابة [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**القيمة المرجعة:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```


يرجع أو يضبط كائنًا يتلقى التحذيرات ويقرر ما إذا كانت عملية التحميل ستستمر أو ستُلغى. قراءة/كتابة [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getProgressCallback() {#getProgressCallback--}
```
public final IProgressCallback getProgressCallback()
```


يمثل كائنًا لاستدعاء رد الاتصال لتحديثات تقدم الحفظ كنسبة مئوية. راجع [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**القيمة المرجعة:**
[IProgressCallback](../../com.aspose.slides/iprogresscallback)
### setProgressCallback(IProgressCallback value) {#setProgressCallback-com.aspose.slides.IProgressCallback-}
```
public final void setProgressCallback(IProgressCallback value)
```


يمثل كائنًا لاستدعاء رد الاتصال لتحديثات تقدم الحفظ كنسبة مئوية. راجع [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IProgressCallback](../../com.aspose.slides/iprogresscallback) |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public final String getDefaultRegularFont()
```


يرجع أو يضبط الخط المستخدم في حال عدم العثور على الخط المصدر. قراءة-كتابة String.

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


**القيمة المرجعة:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public final void setDefaultRegularFont(String value)
```


يرجع أو يضبط الخط المستخدم في حال عدم العثور على الخط المصدر. قراءة-كتابة String.

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


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getGradientStyle() {#getGradientStyle--}
```
public final int getGradientStyle()
```


يرجع أو يضبط النمط البصري للتدرج. قراءة/كتابة [GradientStyle](../../com.aspose.slides/gradientstyle).

**القيمة المرجعة:**
int
### setGradientStyle(int value) {#setGradientStyle-int-}
```
public final void setGradientStyle(int value)
```


يرجع أو يضبط النمط البصري للتدرج. قراءة/كتابة [GradientStyle](../../com.aspose.slides/gradientstyle).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getSkipJavaScriptLinks() {#getSkipJavaScriptLinks--}
```
public final boolean getSkipJavaScriptLinks()
```


حدد ما إذا كان يجب تخطي الروابط التشعبية التي تحتوي على استدعاءات JavaScript عند حفظ العرض التقديمي. قراءة/كتابة boolean. القيمة الافتراضية هي false.

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

عندما يتم ضبط هذه الخاصية على true، سيتم تجاهل الروابط التشعبية التي تحتوي على استدعاءات JavaScript أثناء الحفظ.

عندما يتم ضبط هذه الخاصية على false، سيتم حفظ جميع الروابط التشعبية.

**القيمة المرجعة:**
boolean
### setSkipJavaScriptLinks(boolean value) {#setSkipJavaScriptLinks-boolean-}
```
public final void setSkipJavaScriptLinks(boolean value)
```


حدد ما إذا كان يجب تخطي الروابط التشعبية التي تحتوي على استدعاءات JavaScript عند حفظ العرض التقديمي. قراءة/كتابة boolean. القيمة الافتراضية هي false.

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

عندما يتم ضبط هذه الخاصية على true، سيتم تجاهل الروابط التشعبية التي تحتوي على استدعاءات JavaScript أثناء الحفظ.

عندما يتم ضبط هذه الخاصية على false، سيتم حفظ جميع الروابط التشعبية.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |