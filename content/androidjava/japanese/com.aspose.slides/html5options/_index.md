---
title: Html5Options
second_title: Aspose.Slides for Android 用 Java API リファレンス
description: HTML5 エクスポートオプションを表します。
type: docs
url: /ja/com.aspose.slides/html5options/
---
**継承:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IHtml5Options](../../com.aspose.slides/ihtml5options)
```
public class Html5Options extends SaveOptions implements IHtml5Options
```

HTML5 エクスポートオプションを表します。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateShapes(true);
>      htmlOptions.setAnimateTransitions(true);
> 
>      pres.save("demo-animate-shapes-and-transitions.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Html5Options()](#Html5Options--) | デフォルトコンストラクタ。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getAnimateTransitions()](#getAnimateTransitions--) | 遷移アニメーションオプションを取得または設定します。 |
| [setAnimateTransitions(boolean value)](#setAnimateTransitions-boolean-) | 遷移アニメーションオプションを取得または設定します。 |
| [getAnimateShapes()](#getAnimateShapes--) | シェイプ アニメーションオプションを取得または設定します。 |
| [setAnimateShapes(boolean value)](#setAnimateShapes-boolean-) | シェイプ アニメーションオプションを取得または設定します。 |
| [getEmbedImages()](#getEmbedImages--) | 画像埋め込みオプションを取得または設定します。 |
| [setEmbedImages(boolean value)](#setEmbedImages-boolean-) | 画像埋め込みオプションを取得または設定します。 |
| [getOutputPath()](#getOutputPath--) | 外部リソースの保存場所を決定します。 |
| [setOutputPath(String value)](#setOutputPath-java.lang.String-) | 外部リソースの保存場所を決定します。 |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | テキストをリガチャなしでレンダリングするかどうかを示す値を取得または設定します。 |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | テキストをリガチャなしでレンダリングするかどうかを示す値を取得または設定します。 |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | プレゼンテーション[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)をエクスポートする際に、スライドがページ上に配置されるモードを取得または設定します。 |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | プレゼンテーション[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)をエクスポートする際に、スライドがページ上に配置されるモードを取得または設定します。 |
### Html5Options() {#Html5Options--}
```
public Html5Options()
```


デフォルトコンストラクタ。

### getAnimateTransitions() {#getAnimateTransitions--}
```
public final boolean getAnimateTransitions()
```


遷移アニメーションオプションを取得または設定します。 読み取り/書き込み boolean。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateTransitions(true);
> 
>      pres.save("demo-animate-transitions.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**戻り値:**
boolean
### setAnimateTransitions(boolean value) {#setAnimateTransitions-boolean-}
```
public final void setAnimateTransitions(boolean value)
```


遷移アニメーションオプションを取得または設定します。 読み取り/書き込み boolean。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateTransitions(true);
> 
>      pres.save("demo-animate-transitions.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getAnimateShapes() {#getAnimateShapes--}
```
public final boolean getAnimateShapes()
```


シェイプ アニメーションオプションを取得または設定します。 読み取り/書き込み boolean。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateShapes(true);
> 
>      pres.save("demo-animate-shapes.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**戻り値:**
boolean
### setAnimateShapes(boolean value) {#setAnimateShapes-boolean-}
```
public final void setAnimateShapes(boolean value)
```


シェイプ アニメーションオプションを取得または設定します。 読み取り/書き込み boolean。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateShapes(true);
> 
>      pres.save("demo-animate-shapes.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getEmbedImages() {#getEmbedImages--}
```
public final boolean getEmbedImages()
```


画像埋め込みオプションを取得または設定します。 読み取り/書き込み boolean。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options html5Options = new Html5Options();
>      html5Options.setEmbedImages(false);
>      pres.save("demo-linked-images.html", SaveFormat.Html5, html5Options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**戻り値:**
boolean
### setEmbedImages(boolean value) {#setEmbedImages-boolean-}
```
public final void setEmbedImages(boolean value)
```


画像埋め込みオプションを取得または設定します。 読み取り/書き込み boolean。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options html5Options = new Html5Options();
>      html5Options.setEmbedImages(false);
>      pres.save("demo-linked-images.html", SaveFormat.Html5, html5Options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getOutputPath() {#getOutputPath--}
```
public final String getOutputPath()
```


外部リソースの保存場所を決定します。 読み取り/書き込み String。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options html5Options = new Html5Options();
>      html5Options.setEmbedImages(false);
>      html5Options.setOutputPath(the_desired_path);
>      pres.save("demo-linked-images.html", SaveFormat.Html5, html5Options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**戻り値:**
java.lang.String
### setOutputPath(String value) {#setOutputPath-java.lang.String-}
```
public final void setOutputPath(String value)
```


外部リソースの保存場所を決定します。 読み取り/書き込み String。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options html5Options = new Html5Options();
>      html5Options.setEmbedImages(false);
>      html5Options.setOutputPath(the_desired_path);
>      pres.save("demo-linked-images.html", SaveFormat.Html5, html5Options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```


リガチャを使わずにテキストがレンダリングされるかどうかを示す値を取得または設定します。 true に設定すると、レンダリングされた出力でリガチャが無効になります。 デフォルトでは、このプロパティは false に設定されています。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Html5Options options = new Html5Options();
>      options.setDisableFontLigatures(true); // テキストレンダリングでリガチャを無効にする
> 
>      pres.save("output.html", SaveFormat.Html5, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**戻り値:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public final void setDisableFontLigatures(boolean value)
```


リガチャを使わずにテキストがレンダリングされるかどうかを示す値を取得または設定します。 true に設定すると、レンダリングされた出力でリガチャが無効になります。 デフォルトでは、このプロパティは false に設定されています。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Html5Options options = new Html5Options();
>      options.setDisableFontLigatures(true); // テキストレンダリングでリガチャを無効にする
> 
>      pres.save("output.html", SaveFormat.Html5, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```


プレゼンテーション[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)をエクスポートする際に、スライドがページ上に配置されるモードを取得または設定します。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HandoutLayoutingOptions handoutLayoutingOptions = new HandoutLayoutingOptions();
>      handoutLayoutingOptions.setHandout(HandoutType.Handouts4Horizontal);
>      Html5Options options = new Html5Options();
>      options.setSlidesLayoutOptions(handoutLayoutingOptions);
> 
>      pres.save("pres.html", SaveFormat.Html5, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**戻り値:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```


プレゼンテーション[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)をエクスポートする際に、スライドがページ上に配置されるモードを取得または設定します。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HandoutLayoutingOptions handoutLayoutingOptions = new HandoutLayoutingOptions();
>      handoutLayoutingOptions.setHandout(HandoutType.Handouts4Horizontal);
>      Html5Options options = new Html5Options();
>      options.setSlidesLayoutOptions(handoutLayoutingOptions);
> 
>      pres.save("pres.html", SaveFormat.Html5, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |