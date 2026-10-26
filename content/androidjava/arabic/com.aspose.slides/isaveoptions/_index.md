---  
title: ISaveOptions  
second_title: Aspose.Slides for Android via Java API Reference  
description: Options that control how a presentation is saved.  
type: docs  
url: /ar/com.aspose.slides/isaveoptions/  
---```
public interface ISaveOptions
```

الخيارات التي تتحكم في طريقة حفظ العرض التقديمي.  
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getWarningCallback()](#getWarningCallback--) | ترجع أو تعين كائنًا يتلقى التحذيرات ويقرر ما إذا كانت عملية التحميل ستستمر أم سيتم إلغاؤها. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | ترجع أو تعين كائنًا يتلقى التحذيرات ويقرر ما إذا كانت عملية التحميل ستستمر أم سيتم إلغاؤها. |
| [getProgressCallback()](#getProgressCallback--) | يمثل كائنًا استدعائيًا لتحديثات تقدم الحفظ بالنسبة المئوية. |
| [setProgressCallback(IProgressCallback value)](#setProgressCallback-com.aspose.slides.IProgressCallback-) | يمثل كائنًا استدعائيًا لتحديثات تقدم الحفظ بالنسبة المئوية. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | ترجع أو تعين الخط المستخدم في حال عدم العثور على الخط الأصلي. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | ترجع أو تعين الخط المستخدم في حال عدم العثور على الخط الأصلي. |
| [getGradientStyle()](#getGradientStyle--) | ترجع أو تعين النمط البصري للتدرج. |
| [setGradientStyle(int value)](#setGradientStyle-int-) | ترجع أو تعين النمط البصري للتدرج. |
| [getSkipJavaScriptLinks()](#getSkipJavaScriptLinks--) | يحدد ما إذا كان سيتم تخطي الروابط ذات نداءات JavaScript عند حفظ العرض التقديمي. |
| [setSkipJavaScriptLinks(boolean value)](#setSkipJavaScriptLinks-boolean-) | يحدد ما إذا كان سيتم تخطي الروابط ذات نداءات JavaScript عند حفظ العرض التقديمي. |

### getWarningCallback() {#getWarningCallback--}
```
public abstract IWarningCallback getWarningCallback()
```

ترجع أو تعين كائنًا يتلقى التحذيرات ويقرر ما إذا كانت عملية التحميل ستستمر أم سيتم إلغاؤها. قراءة/كتابة [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**الإرجاع:**  
[IWarningCallback](../../com.aspose.slides/iwarningcallback)

### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public abstract void setWarningCallback(IWarningCallback value)
```

ترجع أو تعين كائنًا يتلقى التحذيرات ويقرر ما إذا كانت عملية التحميل ستستمر أم سيتم إلغاؤها. قراءة/كتابة [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getProgressCallback() {#getProgressCallback--}
```
public abstract IProgressCallback getProgressCallback()
```

يمثل كائنًا استدعائيًا لتحديثات تقدم الحفظ بالنسبة المئوية. انظر [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**الإرجاع:**  
[IProgressCallback](../../com.aspose.slides/iprogresscallback)

### setProgressCallback(IProgressCallback value) {#setProgressCallback-com.aspose.slides.IProgressCallback-}
```
public abstract void setProgressCallback(IProgressCallback value)
```

يمثل كائنًا استدعائيًا لتحديثات تقدم الحفظ بالنسبة المئوية. انظر [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IProgressCallback](../../com.aspose.slides/iprogresscallback) |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public abstract String getDefaultRegularFont()
```

ترجع أو تعين الخط المستخدم في حال عدم العثور على الخط الأصلي. قراءة-كتابة String.

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
public abstract void setDefaultRegularFont(String value)
```

ترجع أو تعين الخط المستخدم في حال عدم العثور على الخط الأصلي. قراءة-كتابة String.

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
public abstract int getGradientStyle()
```

ترجع أو تعين النمط البصري للتدرج. قراءة/كتابة [GradientStyle](../../com.aspose.slides/gradientstyle).

**الإرجاع:**  
int

### setGradientStyle(int value) {#setGradientStyle-int-}
```
public abstract void setGradientStyle(int value)
```

ترجع أو تعين النمط البصري للتدرج. قراءة/كتابة [GradientStyle](../../com.aspose.slides/gradientstyle).

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getSkipJavaScriptLinks() {#getSkipJavaScriptLinks--}
```
public abstract boolean getSkipJavaScriptLinks()
```

يحدد ما إذا كان سيتم تخطي الروابط ذات نداءات JavaScript عند حفظ العرض التقديمي. قراءة/كتابة boolean. القيمة الافتراضية هي false.

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

عند تعيين هذه الخاصية إلى true، سيتم تجاهل الروابط ذات نداءات JavaScript أثناء الحفظ.

عند تعيين هذه الخاصية إلى false، سيتم حفظ جميع الروابط.

**الإرجاع:**  
boolean

### setSkipJavaScriptLinks(boolean value) {#setSkipJavaScriptLinks-boolean-}
```
public abstract void setSkipJavaScriptLinks(boolean value)
```

يحدد ما إذا كان سيتم تخطي الروابط ذات نداءات JavaScript عند حفظ العرض التقديمي. قراءة/كتابة boolean. القيمة الافتراضية هي false.

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

عند تعيين هذه الخاصية إلى true، سيتم تجاهل الروابط ذات نداءات JavaScript أثناء الحفظ.

عند تعيين هذه الخاصية إلى false، سيتم حفظ جميع الروابط.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |