---
title: SaveOptions
second_title: Java API 参照による Android 用 Aspose.Slides
description: プレゼンテーションの保存方法を制御するオプションを持つ抽象クラスです。
type: docs
url: /ja/com.aspose.slides/saveoptions/
---
**継承:**  
java.lang.Object

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)  
```
public abstract class SaveOptions implements ISaveOptions
```

プレゼンテーションの保存方法を制御するオプションを持つ抽象クラスです。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [SaveOptions()](#SaveOptions--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getWarningCallback()](#getWarningCallback--) | 警告を受け取り、ロードプロセスを継続するか中止するかを決定するオブジェクトを取得または設定します。 |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | 警告を受け取り、ロードプロセスを継続するか中止するかを決定するオブジェクトを取得または設定します。 |
| [getProgressCallback()](#getProgressCallback--) | 保存進行状況をパーセンテージで更新するコールバックオブジェクトを表します。 |
| [setProgressCallback(IProgressCallback value)](#setProgressCallback-com.aspose.slides.IProgressCallback-) | 保存進行状況をパーセンテージで更新するコールバックオブジェクトを表します。 |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | 元のフォントが見つからない場合に使用するフォントを取得または設定します。 |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | 元のフォントが見つからない場合に使用するフォントを取得または設定します。 |
| [getGradientStyle()](#getGradientStyle--) | グラデーションの視覚的スタイルを取得または設定します。 |
| [setGradientStyle(int value)](#setGradientStyle-int-) | グラデーションの視覚的スタイルを取得または設定します。 |
| [getSkipJavaScriptLinks()](#getSkipJavaScriptLinks--) | プレゼンテーションを保存する際に、JavaScript 呼び出しを含むハイパーリンクをスキップするかどうかを指定します。 |
| [setSkipJavaScriptLinks(boolean value)](#setSkipJavaScriptLinks-boolean-) | プレゼンテーションを保存する際に、JavaScript 呼び出しを含むハイパーリンクをスキップするかどうかを指定します。 |
### SaveOptions() {#SaveOptions--}
```
public SaveOptions()
```

### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```

警告を受け取り、ロードプロセスを継続するか中止するかを決定するオブジェクトを取得または設定します。読み取り/書き込み [IWarningCallback](../../com.aspose.slides/iwarningcallback)。

**戻り値:**  
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```

警告を受け取り、ロードプロセスを継続するか中止するかを決定するオブジェクトを取得または設定します。読み取り/書き込み [IWarningCallback](../../com.aspose.slides/iwarningcallback)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getProgressCallback() {#getProgressCallback--}
```
public final IProgressCallback getProgressCallback()
```

保存進行状況をパーセンテージで更新するコールバックオブジェクトを表します。参照 [IProgressCallback](../../com.aspose.slides/iprogresscallback)。

**戻り値:**  
[IProgressCallback](../../com.aspose.slides/iprogresscallback)
### setProgressCallback(IProgressCallback value) {#setProgressCallback-com.aspose.slides.IProgressCallback-}
```
public final void setProgressCallback(IProgressCallback value)
```

保存進行状況をパーセンテージで更新するコールバックオブジェクトを表します。参照 [IProgressCallback](../../com.aspose.slides/iprogresscallback)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IProgressCallback](../../com.aspose.slides/iprogresscallback) |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public final String getDefaultRegularFont()
```

元のフォントが見つからない場合に使用するフォントを取得または設定します。読み取り/書き込み String。

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
public final void setDefaultRegularFont(String value)
```

元のフォントが見つからない場合に使用するフォントを取得または設定します。読み取り/書き込み String。

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
public final int getGradientStyle()
```

グラデーションの視覚的スタイルを取得または設定します。読み取り/書き込み [GradientStyle](../../com.aspose.slides/gradientstyle)。

**戻り値:**  
int
### setGradientStyle(int value) {#setGradientStyle-int-}
```
public final void setGradientStyle(int value)
```

グラデーションの視覚的スタイルを取得または設定します。読み取り/書き込み [GradientStyle](../../com.aspose.slides/gradientstyle)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getSkipJavaScriptLinks() {#getSkipJavaScriptLinks--}
```
public final boolean getSkipJavaScriptLinks()
```

プレゼンテーションを保存する際に、JavaScript 呼び出しを含むハイパーリンクをスキップするかどうかを指定します。読み取り/書き込み boolean。既定値は false です。

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

このプロパティが true に設定されている場合、JavaScript 呼び出しを含むハイパーリンクは保存時に無視されます。

このプロパティが false に設定されている場合、すべてのハイパーリンクが保存されます。

**戻り値:**  
boolean
### setSkipJavaScriptLinks(boolean value) {#setSkipJavaScriptLinks-boolean-}
```
public final void setSkipJavaScriptLinks(boolean value)
```

プレゼンテーションを保存する際に、JavaScript 呼び出しを含むハイパーリンクをスキップするかどうかを指定します。読み取り/書き込み boolean。既定値は false です。

--------------------

> ```
public final void setSkipJavaScriptLinks(boolean value)
```

--------------------

このプロパティが true に設定されている場合、JavaScript 呼び出しを含むハイパーリンクは保存時に無視されます。

このプロパティが false に設定されている場合、すべてのハイパーリンクが保存されます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |