---
title: ISaveOptions
second_title: Aspose.Slides for Java API Reference
description: Options that control how a presentation is saved.
type: docs
url: /ar/com.aspose.slides/isaveoptions/
---```
public interface ISaveOptions
```

الخيارات التي تتحكم في كيفية حفظ العرض التقديمي.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getWarningCallback()](#getWarningCallback--) | إرجاع أو تعيين كائن يتلقى التحذيرات ويقرر ما إذا كانت عملية التحميل سيتم الاستمرار فيها أو إلغاؤها. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | إرجاع أو تعيين كائن يتلقى التحذيرات ويقرر ما إذا كانت عملية التحميل سيتم الاستمرار فيها أو إلغاؤها. |
| [getProgressCallback()](#getProgressCallback--) | يمثل كائن استدعاء للعودة لتحديثات تقدم الحفظ بالنسبة المئوية. |
| [setProgressCallback(IProgressCallback value)](#setProgressCallback-com.aspose.slides.IProgressCallback-) | يمثل كائن استدعاء للعودة لتحديثات تقدم الحفظ بالنسبة المئوية. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | إرجاع أو تعيين الخط المستخدم في حالة عدم العثور على الخط المصدر. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | إرجاع أو تعيين الخط المستخدم في حالة عدم العثور على الخط المصدر. |
| [getGradientStyle()](#getGradientStyle--) | إرجاع أو تعيين النمط البصري للتدرج. |
| [setGradientStyle(int value)](#setGradientStyle-int-) | إرجاع أو تعيين النمط البصري للتدرج. |
| [getSkipJavaScriptLinks()](#getSkipJavaScriptLinks--) | تحديد ما إذا كان يجب تخطي الروابط التشعبية التي تستدعي جافاس سكريبت عند حفظ العرض التقديمي. |
| [setSkipJavaScriptLinks(boolean value)](#setSkipJavaScriptLinks-boolean-) | تحديد ما إذا كان يجب تخطي الروابط التشعبية التي تستدعي جافاس سكريبت عند حفظ العرض التقديمي. |
### getWarningCallback() {#getWarningCallback--}
```
public abstract IWarningCallback getWarningCallback()
```


إرجاع أو تعيين كائن يتلقى التحذيرات ويقرر ما إذا كانت عملية التحميل سيتم الاستمرار فيها أو إلغاؤها. قراءة/كتابة [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**الإرجاع:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public abstract void setWarningCallback(IWarningCallback value)
```


إرجاع أو تعيين كائن يتلقى التحذيرات ويقرر ما إذا كانت عملية التحميل سيتم الاستمرار فيها أو إلغاؤها. قراءة/كتابة [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |
### getProgressCallback() {#getProgressCallback--}
```
public abstract IProgressCallback getProgressCallback()
```


يمثل كائن استدعاء للعودة لتحديثات تقدم الحفظ بالنسبة المئوية. راجع [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**الإرجاع:**
[IProgressCallback](../../com.aspose.slides/iprogresscallback)
### setProgressCallback(IProgressCallback value) {#setProgressCallback-com.aspose.slides.IProgressCallback-}
```
public abstract void setProgressCallback(IProgressCallback value)
```


يمثل كائن استدعاء للعودة لتحديثات تقدم الحفظ بالنسبة المئوية. راجع [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [IProgressCallback](../../com.aspose.slides/iprogresscallback) |  |
### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public abstract String getDefaultRegularFont()
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
public abstract void setDefaultRegularFont(String value)
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


**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |
### getGradientStyle() {#getGradientStyle--}
```
public abstract int getGradientStyle()
```


إرجاع أو تعيين النمط البصري للتدرج. قراءة/كتابة [GradientStyle](../../com.aspose.slides/gradientstyle).

**الإرجاع:**
int
### setGradientStyle(int value) {#setGradientStyle-int-}
```
public abstract void setGradientStyle(int value)
```


إرجاع أو تعيين النمط البصري للتدرج. قراءة/كتابة [GradientStyle](../../com.aspose.slides/gradientstyle).

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getSkipJavaScriptLinks() {#getSkipJavaScriptLinks--}
```
public abstract boolean getSkipJavaScriptLinks()
```


تحديد ما إذا كان يجب تخطي الروابط التشعبية التي تستدعي جافاس سكريبت عند حفظ العرض التقديمي. قراءة/كتابة boolean. القيمة الافتراضية هي false.

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

عند ضبط هذه الخاصية إلى true، سيتم تجاهل الروابط التشعبية التي تستدعي جافاس سكريبت أثناء الحفظ.

عند ضبط هذه الخاصية إلى false، سيتم حفظ جميع الروابط التشعبية.

**الإرجاع:**
boolean
### setSkipJavaScriptLinks(boolean value) {#setSkipJavaScriptLinks-boolean-}
```
public abstract void setSkipJavaScriptLinks(boolean value)
```


تحديد ما إذا كان يجب تخطي الروابط التشعبية التي تستدعي جافاس سكريبت عند حفظ العرض التقديمي. قراءة/كتابة boolean. القيمة الافتراضية هي false.

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

عند ضبط هذه الخاصية إلى true، سيتم تجاهل الروابط التشعبية التي تستدعي جافاس سكريبت أثناء الحفظ.

عند ضبط هذه الخاصية إلى false، سيتم حفظ جميع الروابط التشعبية.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean |  |