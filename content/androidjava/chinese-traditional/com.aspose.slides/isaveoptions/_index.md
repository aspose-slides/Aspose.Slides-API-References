---
title: ISaveOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Options that control how a presentation is saved.
type: docs
url: /zh-hant/com.aspose.slides/isaveoptions/
---```
public interface ISaveOptions
```

控制投影片儲存方式的選項。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getWarningCallback()](#getWarningCallback--) | 返回或設定一個接收警告並決定載入過程是否繼續或中止的物件。 |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | 返回或設定一個接收警告並決定載入過程是否繼續或中止的物件。 |
| [getProgressCallback()](#getProgressCallback--) | 代表用於儲存進度更新（百分比）的回呼物件。 |
| [setProgressCallback(IProgressCallback value)](#setProgressCallback-com.aspose.slides.IProgressCallback-) | 代表用於儲存進度更新（百分比）的回呼物件。 |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | 返回或設定當找不到來源字型時使用的字型。 |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | 返回或設定當找不到來源字型時使用的字型。 |
| [getGradientStyle()](#getGradientStyle--) | 返回或設定漸層的視覺樣式。 |
| [setGradientStyle(int value)](#setGradientStyle-int-) | 返回或設定漸層的視覺樣式。 |
| [getSkipJavaScriptLinks()](#getSkipJavaScriptLinks--) | 指定在儲存投影片時是否跳過含 JavaScript 呼叫的超連結。 |
| [setSkipJavaScriptLinks(boolean value)](#setSkipJavaScriptLinks-boolean-) | 指定在儲存投影片時是否跳過含 JavaScript 呼叫的超連結。 |
### getWarningCallback() {#getWarningCallback--}
```
public abstract IWarningCallback getWarningCallback()
```


返回或設定一個接收警告並決定載入過程是否繼續或中止的物件。讀/寫 [IWarningCallback](../../com.aspose.slides/iwarningcallback)。

**返回:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public abstract void setWarningCallback(IWarningCallback value)
```


返回或設定一個接收警告並決定載入過程是否繼續或中止的物件。讀/寫 [IWarningCallback](../../com.aspose.slides/iwarningcallback)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getProgressCallback() {#getProgressCallback--}
```
public abstract IProgressCallback getProgressCallback()
```


代表用於儲存進度更新（百分比）的回呼物件。請參見 [IProgressCallback](../../com.aspose.slides/iprogresscallback)。

**返回:**
[IProgressCallback](../../com.aspose.slides/iprogresscallback)
### setProgressCallback(IProgressCallback value) {#setProgressCallback-com.aspose.slides.IProgressCallback-}
```
public abstract void setProgressCallback(IProgressCallback value)
```


代表用於儲存進度更新（百分比）的回呼物件。請參見 [IProgressCallback](../../com.aspose.slides/iprogresscallback)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IProgressCallback](../../com.aspose.slides/iprogresscallback) |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public abstract String getDefaultRegularFont()
```


返回或設定當找不到來源字型時使用的字型。讀/寫 String。

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


**返回:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public abstract void setDefaultRegularFont(String value)
```


返回或設定當找不到來源字型時使用的字型。讀/寫 String。

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
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getGradientStyle() {#getGradientStyle--}
```
public abstract int getGradientStyle()
```


返回或設定漸層的視覺樣式。讀/寫 [GradientStyle](../../com.aspose.slides/gradientstyle)。

**返回:**
int
### setGradientStyle(int value) {#setGradientStyle-int-}
```
public abstract void setGradientStyle(int value)
```


返回或設定漸層的視覺樣式。讀/寫 [GradientStyle](../../com.aspose.slides/gradientstyle)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getSkipJavaScriptLinks() {#getSkipJavaScriptLinks--}
```
public abstract boolean getSkipJavaScriptLinks()
```


指定在儲存投影片時是否跳過含 JavaScript 呼叫的超連結。讀/寫 boolean。預設值為 false。

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

當此屬性設定為 true 時，儲存時會忽略含 JavaScript 呼叫的超連結。

當此屬性設定為 false 時，所有超連結都會被儲存。

**返回:**
boolean
### setSkipJavaScriptLinks(boolean value) {#setSkipJavaScriptLinks-boolean-}
```
public abstract void setSkipJavaScriptLinks(boolean value)
```


指定在儲存投影片時是否跳過含 JavaScript 呼叫的超連結。讀/寫 boolean。預設值為 false。

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

當此屬性設定為 true 時，儲存時會忽略含 JavaScript 呼叫的超連結。

當此屬性設定為 false 時，所有超連結都會被儲存。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |