---
title: SaveOptions
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 抽象類別，提供控制投影片儲存方式的選項。
type: docs
url: /zh-hant/com.aspose.slides/saveoptions/
---
**繼承:**  
java.lang.Object

**已實作的介面:**  
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)  
```
public abstract class SaveOptions implements ISaveOptions
```

抽象類別，提供控制投影片儲存方式的選項。

## 建構式

| 建構式 | 說明 |
| --- | --- |
| [SaveOptions()](#SaveOptions--) |  |

## 方法

| 方法 | 說明 |
| --- | --- |
| [getWarningCallback()](#getWarningCallback--) | 傳回或設定接收警告並決定載入程序是否繼續或中止的物件。 |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | 傳回或設定接收警告並決定載入程序是否繼續或中止的物件。 |
| [getProgressCallback()](#getProgressCallback--) | 表示用於儲存進度更新（百分比）的回呼物件。 |
| [setProgressCallback(IProgressCallback value)](#setProgressCallback-com.aspose.slides.IProgressCallback-) | 表示用於儲存進度更新（百分比）的回呼物件。 |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | 傳回或設定在找不到來源字型時使用的字型。 |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | 傳回或設定在找不到來源字型時使用的字型。 |
| [getGradientStyle()](#getGradientStyle--) | 傳回或設定漸層的視覺樣式。 |
| [setGradientStyle(int value)](#setGradientStyle-int-) | 傳回或設定漸層的視覺樣式。 |
| [getSkipJavaScriptLinks()](#getSkipJavaScriptLinks--) | 指定在儲存投影片時是否跳過包含 JavaScript 呼叫的超連結。 |
| [setSkipJavaScriptLinks(boolean value)](#setSkipJavaScriptLinks-boolean-) | 指定在儲存投影片時是否跳過包含 JavaScript 呼叫的超連結。 |

### SaveOptions() {#SaveOptions--}
```
public SaveOptions()
```

### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```

傳回或設定接收警告並決定載入程序是否繼續或中止的物件。可讀寫 [IWarningCallback](../../com.aspose.slides/iwarningcallback)。

**傳回:**  
[IWarningCallback](../../com.aspose.slides/iwarningcallback)

### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```

傳回或設定接收警告並決定載入程序是否繼續或中止的物件。可讀寫 [IWarningCallback](../../com.aspose.slides/iwarningcallback)。

**參數:**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getProgressCallback() {#getProgressCallback--}
```
public final IProgressCallback getProgressCallback()
```

表示用於儲存進度更新（百分比）的回呼物件。參見 [IProgressCallback](../../com.aspose.slides/iprogresscallback)。

**傳回:**  
[IProgressCallback](../../com.aspose.slides/iprogresscallback)

### setProgressCallback(IProgressCallback value) {#setProgressCallback-com.aspose.slides.IProgressCallback-}
```
public final void setProgressCallback(IProgressCallback value)
```

表示用於儲存進度更新（百分比）的回呼物件。參見 [IProgressCallback](../../com.aspose.slides/iprogresscallback)。

**參數:**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | [IProgressCallback](../../com.aspose.slides/iprogresscallback) |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public final String getDefaultRegularFont()
```

傳回或設定在找不到來源字型時使用的字型。可讀寫 String。

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

**傳回:**  
java.lang.String

### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public final void setDefaultRegularFont(String value)
```

傳回或設定在找不到來源字型時使用的字型。可讀寫 String。

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

**參數:**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getGradientStyle() {#getGradientStyle--}
```
public final int getGradientStyle()
```

傳回或設定漸層的視覺樣式。可讀寫 [GradientStyle](../../com.aspose.slides/gradientstyle)。

**傳回:**  
int

### setGradientStyle(int value) {#setGradientStyle-int-}
```
public final void setGradientStyle(int value)
```

傳回或設定漸層的視覺樣式。可讀寫 [GradientStyle](../../com.aspose.slides/gradientstyle)。

**參數:**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |

### getSkipJavaScriptLinks() {#getSkipJavaScriptLinks--}
```
public final boolean getSkipJavaScriptLinks()
```

指定在儲存投影片時是否跳過包含 JavaScript 呼叫的超連結。可讀寫 boolean。預設值為 false。

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

當此屬性設為 true 時，包含 JavaScript 呼叫的超連結將在儲存時被忽略。

當此屬性設為 false 時，所有超連結皆會被儲存。

**傳回:**  
boolean

### setSkipJavaScriptLinks(boolean value) {#setSkipJavaScriptLinks-boolean-}
```
public final void setSkipJavaScriptLinks(boolean value)
```

指定在儲存投影片時是否跳過包含 JavaScript 呼叫的超連結。可讀寫 boolean。預設值為 false。

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

當此屬性設為 true 時，包含 JavaScript 呼叫的超連結將在儲存時被忽略。

當此屬性設為 false 時，所有超連結皆會被儲存。

**參數:**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |