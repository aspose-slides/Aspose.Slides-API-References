---
title: ISaveOptions
second_title: Aspose.Slides for Java API Reference
description: プレゼンテーションの保存方法を制御するオプション。
type: docs
url: /ja/com.aspose.slides/isaveoptions/
---```
public interface ISaveOptions
```

プレゼンテーションの保存方法を制御するオプション。
## メソッド

| Method | Description |
| --- | --- |
| [getWarningCallback()](#getWarningCallback--) | 警告を受け取り、読み込みプロセスを続行するか中止するかを決定するオブジェクトを取得または設定します。 |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | 警告を受け取り、読み込みプロセスを続行するか中止するかを決定するオブジェクトを取得または設定します。 |
| [getProgressCallback()](#getProgressCallback--) | 進捗率での保存進行状況更新のコールバックオブジェクトを表します。 |
| [setProgressCallback(IProgressCallback value)](#setProgressCallback-com.aspose.slides.IProgressCallback-) | 進捗率での保存進行状況更新のコールバックオブジェクトを表します。 |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | ソースフォントが見つからない場合に使用されるフォントを取得または設定します。 |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | ソースフォントが見つからない場合に使用されるフォントを取得または設定します。 |
| [getGradientStyle()](#getGradientStyle--) | グラデーションの視覚スタイルを取得または設定します。 |
| [setGradientStyle(int value)](#setGradientStyle-int-) | グラデーションの視覚スタイルを取得または設定します。 |
| [getSkipJavaScriptLinks()](#getSkipJavaScriptLinks--) | プレゼンテーションを保存する際に、JavaScript 呼び出しを含むハイパーリンクをスキップするかどうかを指定します。 |
| [setSkipJavaScriptLinks(boolean value)](#setSkipJavaScriptLinks-boolean-) | プレゼンテーションを保存する際に、JavaScript 呼び出しを含むハイパーリンクをスキップするかどうかを指定します。 |
### getWarningCallback() {#getWarningCallback--}
```
public abstract IWarningCallback getWarningCallback()
```

警告を受け取り、読み込みプロセスを続行するか中止するかを決定するオブジェクトを取得または設定します。 読み取り/書き込み [IWarningCallback](../../com.aspose.slides/iwarningcallback)。

**戻り値:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public abstract void setWarningCallback(IWarningCallback value)
```

警告を受け取り、読み込みプロセスを続行するか中止するかを決定するオブジェクトを取得または設定します。 読み取り/書き込み [IWarningCallback](../../com.aspose.slides/iwarningcallback)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getProgressCallback() {#getProgressCallback--}
```
public abstract IProgressCallback getProgressCallback()
```

保存進行状況更新をパーセンテージで受け取るコールバックオブジェクトを表します。 参照 [IProgressCallback](../../com.aspose.slides/iprogresscallback)。

**戻り値:**
[IProgressCallback](../../com.aspose.slides/iprogresscallback)
### setProgressCallback(IProgressCallback value) {#setProgressCallback-com.aspose.slides.IProgressCallback-}
```
public abstract void setProgressCallback(IProgressCallback value)
```

保存進行状況更新をパーセンテージで受け取るコールバックオブジェクトを表します。 参照 [IProgressCallback](../../com.aspose.slides/iprogresscallback)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IProgressCallback](../../com.aspose.slides/iprogresscallback) |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public abstract String getDefaultRegularFont()
```

ソースフォントが見つからない場合に使用されるフォントを取得または設定します。 読み書き String。

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


**戻り値:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public abstract void setDefaultRegularFont(String value)
```

ソースフォントが見つからない場合に使用されるフォントを取得または設定します。 読み書き String。

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


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getGradientStyle() {#getGradientStyle--}
```
public abstract int getGradientStyle()
```

グラデーションの視覚スタイルを取得または設定します。 読み取り/書き込み [GradientStyle](../../com.aspose.slides/gradientstyle)。

**戻り値:**
int
### setGradientStyle(int value) {#setGradientStyle-int-}
```
public abstract void setGradientStyle(int value)
```

グラデーションの視覚スタイルを取得または設定します。 読み取り/書き込み [GradientStyle](../../com.aspose.slides/gradientstyle)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getSkipJavaScriptLinks() {#getSkipJavaScriptLinks--}
```
public abstract boolean getSkipJavaScriptLinks()
```

プレゼンテーションを保存する際に、JavaScript 呼び出しを含むハイパーリンクをスキップするかどうかを指定します。 読み取り/書き込み boolean。 デフォルト値は false です。

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

このプロパティが true に設定されている場合、保存中に JavaScript 呼び出しを含むハイパーリンクは無視されます。

このプロパティが false に設定されている場合、すべてのハイパーリンクが保存されます。

**戻り値:**
boolean
### setSkipJavaScriptLinks(boolean value) {#setSkipJavaScriptLinks-boolean-}
```
public abstract void setSkipJavaScriptLinks(boolean value)
```

プレゼンテーションを保存する際に、JavaScript 呼び出しを含むハイパーリンクをスキップするかどうかを指定します。 読み取り/書き込み boolean。 デフォルト値は false です。

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

このプロパティが true に設定されている場合、保存中に JavaScript 呼び出しを含むハイパーリンクは無視されます。

このプロパティが false に設定されている場合、すべてのハイパーリンクが保存されます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |