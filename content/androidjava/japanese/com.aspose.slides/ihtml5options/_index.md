---
title: IHtml5Options
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: HTML5 エクスポートオプションを表します。
type: docs
url: /ja/com.aspose.slides/ihtml5options/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IHtml5Options extends ISaveOptions
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
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getAnimateTransitions()](#getAnimateTransitions--) | 遷移アニメーションオプションを取得または設定します。 |
| [setAnimateTransitions(boolean value)](#setAnimateTransitions-boolean-) | 遷移アニメーションオプションを取得または設定します。 |
| [getAnimateShapes()](#getAnimateShapes--) | シェイプアニメーションオプションを取得または設定します。 |
| [setAnimateShapes(boolean value)](#setAnimateShapes-boolean-) | シェイプアニメーションオプションを取得または設定します。 |
| [getEmbedImages()](#getEmbedImages--) | 画像埋め込みオプションを取得または設定します。 |
| [setEmbedImages(boolean value)](#setEmbedImages-boolean-) | 画像埋め込みオプションを取得または設定します。 |
| [getOutputPath()](#getOutputPath--) | 外部リソースの保存場所を決定します。 |
| [setOutputPath(String value)](#setOutputPath-java.lang.String-) | 外部リソースの保存場所を決定します。 |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | リガチャを使用せずにテキストが描画されるかどうかを示す値を取得または設定します。 |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | リガチャを使用せずにテキストが描画されるかどうかを示す値を取得または設定します。 |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | プレゼンテーション [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) をエクスポートする際に、スライドがページ上に配置されるモードを取得または設定します。 |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | プレゼンテーション [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) をエクスポートする際に、スライドがページ上に配置されるモードを取得または設定します。 |
### getAnimateTransitions() {#getAnimateTransitions--}
```
public abstract boolean getAnimateTransitions()
```

遷移アニメーションオプションを取得または設定します。読み書き可能な boolean。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateTransitions(true);
> 
>      pres.save("demo-animate-shapes-and-transitions.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**戻り値:**
boolean
### setAnimateTransitions(boolean value) {#setAnimateTransitions-boolean-}
```
public abstract void setAnimateTransitions(boolean value)
```

遷移アニメーションオプションを取得または設定します。読み書き可能な boolean。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateTransitions(true);
> 
>      pres.save("demo-animate-shapes-and-transitions.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getAnimateShapes() {#getAnimateShapes--}
```
public abstract boolean getAnimateShapes()
```

シェイプアニメーションオプションを取得または設定します。読み書き可能な boolean。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateShapes(true);
> 
>      pres.save("demo-animate-shapes-and-transitions.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**戻り値:**
boolean
### setAnimateShapes(boolean value) {#setAnimateShapes-boolean-}
```
public abstract void setAnimateShapes(boolean value)
```

シェイプアニメーションオプションを取得または設定します。読み書き可能な boolean。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateShapes(true);
> 
>      pres.save("demo-animate-shapes-and-transitions.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getEmbedImages() {#getEmbedImages--}
```
public abstract boolean getEmbedImages()
```

画像埋め込みオプションを取得または設定します。読み書き可能な boolean。

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
public abstract void setEmbedImages(boolean value)
```

画像埋め込みオプションを取得または設定します。読み書き可能な boolean。

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

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getOutputPath() {#getOutputPath--}
```
public abstract String getOutputPath()
```

外部リソースの保存場所を決定します。読み書き可能な String。

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
public abstract void setOutputPath(String value)
```

外部リソースの保存場所を決定します。読み書き可能な String。

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

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |
### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

リガチャを使用せずにテキストが描画されるかどうかを示す値を取得または設定します。true に設定すると、レンダリングされた出力でリガチャが無効になります。既定では、このプロパティは false に設定されています。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Html5Options options = new Html5Options();
>      options.setDisableFontLigatures(true); // テキスト描画時にリガチャを無効にする
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
public abstract void setDisableFontLigatures(boolean value)
```

リガチャを使用せずにテキストが描画されるかどうかを示す値を取得または設定します。true に設定すると、レンダリングされた出力でリガチャが無効になります。既定では、このプロパティは false に設定されています。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Html5Options options = new Html5Options();
>      options.setDisableFontLigatures(true); // テキスト描画時にリガチャを無効にする
> 
>      pres.save("output.html", SaveFormat.Html5, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

プレゼンテーション [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) をエクスポートする際に、スライドがページ上に配置されるモードを取得または設定します。

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
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

プレゼンテーション [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) をエクスポートする際に、スライドがページ上に配置されるモードを取得または設定します。

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

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |