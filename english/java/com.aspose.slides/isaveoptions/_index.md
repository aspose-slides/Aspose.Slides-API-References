---
title: ISaveOptions
second_title: Aspose.Slides for Java API Reference
description: Options that control how a presentation is saved.
type: docs
weight: 1003
url: /java/com.aspose.slides/isaveoptions/
---```
public interface ISaveOptions
```

Options that control how a presentation is saved.
## Methods

| Method | Description |
| --- | --- |
| [getWarningCallback()](#getWarningCallback--) | Returns or sets an object which receives warnings and decides whether loading process will continue or will be aborted. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Returns or sets an object which receives warnings and decides whether loading process will continue or will be aborted. |
| [getProgressCallback()](#getProgressCallback--) | Represents a callback object for saving progress updates in percentage. |
| [setProgressCallback(IProgressCallback value)](#setProgressCallback-com.aspose.slides.IProgressCallback-) | Represents a callback object for saving progress updates in percentage. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Returns or sets font used in case source font is not found. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Returns or sets font used in case source font is not found. |
### getWarningCallback() {#getWarningCallback--}
```
public abstract IWarningCallback getWarningCallback()
```


Returns or sets an object which receives warnings and decides whether loading process will continue or will be aborted. Read/write [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Returns:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public abstract void setWarningCallback(IWarningCallback value)
```


Returns or sets an object which receives warnings and decides whether loading process will continue or will be aborted. Read/write [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getProgressCallback() {#getProgressCallback--}
```
public abstract IProgressCallback getProgressCallback()
```


Represents a callback object for saving progress updates in percentage. See [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**Returns:**
[IProgressCallback](../../com.aspose.slides/iprogresscallback)
### setProgressCallback(IProgressCallback value) {#setProgressCallback-com.aspose.slides.IProgressCallback-}
```
public abstract void setProgressCallback(IProgressCallback value)
```


Represents a callback object for saving progress updates in percentage. See [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IProgressCallback](../../com.aspose.slides/iprogresscallback) |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public abstract String getDefaultRegularFont()
```


Returns or sets font used in case source font is not found. Read-write String.

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

**Returns:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public abstract void setDefaultRegularFont(String value)
```


Returns or sets font used in case source font is not found. Read-write String.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

