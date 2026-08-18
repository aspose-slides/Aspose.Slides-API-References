---
title: XpsOptions
second_title: Aspose.Slides for Java API リファレンス
description: プレゼンテーションを XPS 形式で保存する方法を制御するオプションを提供します。
type: docs
url: /ja/com.aspose.slides/xpsoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**All Implemented Interfaces:**
[com.aspose.slides.IXpsOptions](../../com.aspose.slides/ixpsoptions)
```
public class XpsOptions extends SaveOptions implements IXpsOptions
```

プレゼンテーションを XPS 形式で保存する方法を制御するオプションを提供します。

--------------------

> ```
> The following example shows how to converting presentations to XPS using default settings.
>  
>  // プレゼンテーションファイルを表す Presentation オブジェクトをインスタンス化します
>  Presentation pres = new Presentation("Convert_XPS.pptx");
>  try {
>      // プレゼンテーションを XPS ドキュメントに保存します
>      pres.save("XPS_Output_Without_XPSOption_out.xps", SaveFormat.Xps);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to converting presentations to XPS using custom settings.
>  
>  // プレゼンテーションファイルを表す Presentation オブジェクトをインスタンス化します
>  Presentation pres = new Presentation("Convert_XPS_Options.pptx");
>  try {
>      // TiffOptions クラスをインスタンス化します
>      XpsOptions options = new XpsOptions();
>      // メタファイルを PNG として保存します
>      options.setSaveMetafilesAsPng(true);
>      // プレゼンテーションを XPS ドキュメントに保存します
>      pres.save("XPS_With_Options_out.xps", SaveFormat.Xps, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [XpsOptions()](#XpsOptions--) | デフォルトコンストラクタ。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | 生成されたドキュメントに非表示スライドを含めるかどうかを指定します。 |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | 生成されたドキュメントに非表示スライドを含めるかどうかを指定します。 |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | プレゼンテーションで使用されるすべてのメタファイルを PNG 画像に変換します。 |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | プレゼンテーションで使用されるすべてのメタファイルを PNG 画像に変換します。 |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | 各スライドの周囲に黒いフレームを描画します。 |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | 各スライドの周囲に黒いフレームを描画します。 |
### XpsOptions() {#XpsOptions--}
```
public XpsOptions()
```


デフォルトコンストラクタ。

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


生成されたドキュメントに非表示スライドを含めるかどうかを指定します。 デフォルトは false です。

**戻り値:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


生成されたドキュメントに非表示スライドを含めるかどうかを指定します。 デフォルトは false です。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public final boolean getSaveMetafilesAsPng()
```


プレゼンテーションで使用されるすべてのメタファイルを PNG 画像に変換します。 読み書き可能な boolean。

--------------------

デフォルトは **true** です。

**戻り値:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```


プレゼンテーションで使用されるすべてのメタファイルを PNG 画像に変換します。 読み書き可能な boolean。

--------------------

デフォルトは **true** です。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public final boolean getDrawSlidesFrame()
```


各スライドの周囲に黒いフレームを描画します。 読み書き可能な boolean。

--------------------

デフォルトは **false** です。

**戻り値:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```


各スライドの周囲に黒いフレームを描画します。 読み書き可能な boolean。

--------------------

デフォルトは **false** です。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |