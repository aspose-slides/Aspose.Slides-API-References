---
title: SaveOptions
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: فئة تجريدية تحتوي على خيارات تتحكم في كيفية حفظ العرض التقديمي.
type: docs
url: /ar/com.aspose.slides/saveoptions/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المطبقة:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public abstract class SaveOptions implements ISaveOptions
```

فئة تجريدية مع خيارات تتحكم في كيفية حفظ العرض التقديمي.
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [SaveOptions()](#SaveOptions--) |  |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getWarningCallback()](#getWarningCallback--) | إرجاع أو تعيين كائن يتلقى التحذيرات ويقرر ما إذا كانت عملية التحميل ستستمر أو سيتم إلغاؤها. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | إرجاع أو تعيين كائن يتلقى التحذيرات ويقرر ما إذا كانت عملية التحميل ستستمر أو سيتم إلغاؤها. |
| [getProgressCallback()](#getProgressCallback--) | يمثل كائن رد نداء لتحديثات تقدم الحفظ بالنسبة المئوية. |
| [setProgressCallback(IProgressCallback value)](#setProgressCallback-com.aspose.slides.IProgressCallback-) | يمثل كائن رد نداء لتحديثات تقدم الحفظ بالنسبة المئوية. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | إرجاع أو تعيين الخط المستخدم في حالة عدم العثور على الخط المصدر. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | إرجاع أو تعيين الخط المستخدم في حالة عدم العثور على الخط المصدر. |
| [getGradientStyle()](#getGradientStyle--) | إرجاع أو تعيين النمط البصري للانحدار. |
| [setGradientStyle(int value)](#setGradientStyle-int-) | إرجاع أو تعيين النمط البصري للانحدار. |
| [getSkipJavaScriptLinks()](#getSkipJavaScriptLinks--) | يحدد ما إذا كان يجب تخطي الروابط الفائقة ذات استدعاءات JavaScript عند حفظ العرض التقديمي. |
| [setSkipJavaScriptLinks(boolean value)](#setSkipJavaScriptLinks-boolean-) | يحدد ما إذا كان يجب تخطي الروابط الفائقة ذات استدعاءات JavaScript عند حفظ العرض التقديمي. |
### SaveOptions() {#SaveOptions--}
```
public SaveOptions()
```

### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```

إرجاع أو تعيين كائن يتلقى التحذيرات ويقرر ما إذا كانت عملية التحميل ستستمر أو سيتم إلغاؤها. قراءة/كتابة [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**الإرجاع:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```

إرجاع أو تعيين كائن يتلقى التحذيرات ويقرر ما إذا كانت عملية التحميل ستستمر أو سيتم إلغاؤها. قراءة/كتابة [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getProgressCallback() {#getProgressCallback--}
```
public final IProgressCallback getProgressCallback()
```

يمثل كائن رد نداء لتحديثات تقدم الحفظ بالنسبة المئوية. راجع [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**الإرجاع:**
[IProgressCallback](../../com.aspose.slides/iprogresscallback)
### setProgressCallback(IProgressCallback value) {#setProgressCallback-com.aspose.slides.IProgressCallback-}
```
public final void setProgressCallback(IProgressCallback value)
```

يمثل كائن رد نداء لتحديثات تقدم الحفظ بالنسبة المئوية. راجع [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IProgressCallback](../../com.aspose.slides/iprogresscallback) |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public final String getDefaultRegularFont()
```

إرجاع أو تعيين الخط المستخدم في حالة عدم العثور على الخط المصدر. قراءة-كتابة String.

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


**الإرجاع:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public final void setDefaultRegularFont(String value)
```

إرجاع أو تعيين الخط المستخدم في حالة عدم العثور على الخط المصدر. قراءة-كتابة String.

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


**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getGradientStyle() {#getGradientStyle--}
```
public final int getGradientStyle()
```

إرجاع أو تعيين النمط البصري للانحدار. قراءة/كتابة [GradientStyle](../../com.aspose.slides/gradientstyle).

**الإرجاع:**
int
### setGradientStyle(int value) {#setGradientStyle-int-}
```
public final void setGradientStyle(int value)
```

إرجاع أو تعيين النمط البصري للانحدار. قراءة/كتابة [GradientStyle](../../com.aspose.slides/gradientstyle).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getSkipJavaScriptLinks() {#getSkipJavaScriptLinks--}
```
public final boolean getSkipJavaScriptLinks()
```

يحدد ما إذا كان يجب تخطي الروابط الفائقة ذات استدعاءات JavaScript عند حفظ العرض التقديمي. قراءة/كتابة boolean. القيمة الافتراضية هي false.

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

عند تعيين هذه الخاصية إلى true، سيتم تجاهل الروابط الفائقة ذات استدعاءات JavaScript أثناء الحفظ.

عند تعيين هذه الخاصية إلى false، سيتم حفظ جميع الروابط الفائقة.

**الإرجاع:**
boolean
### setSkipJavaScriptLinks(boolean value) {#setSkipJavaScriptLinks-boolean-}
```
public final void setSkipJavaScriptLinks(boolean value)
```

يحدد ما إذا كان يجب تخطي الروابط الفائقة ذات استدعاءات JavaScript عند حفظ العرض التقديمي. قراءة/كتابة boolean. القيمة الافتراضية هي false.

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

عند تعيين هذه الخاصية إلى true، سيتم تجاهل الروابط الفائقة ذات استدعاءات JavaScript أثناء الحفظ.

عند تعيين هذه الخاصية إلى false، سيتم حفظ جميع الروابط الفائقة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |