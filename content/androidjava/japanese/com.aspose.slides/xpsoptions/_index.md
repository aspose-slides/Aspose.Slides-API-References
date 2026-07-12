---
title: XpsOptions
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: プレゼンテーションを XPS 形式で保存する方法を制御するオプションを提供します。
type: docs
url: /ja/com.aspose.slides/xpsoptions/
---
**継承:**  
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**実装されたすべてのインターフェイス:**  
[com.aspose.slides.IXpsOptions](../../com.aspose.slides/ixpsoptions)  
```
public class XpsOptions extends SaveOptions implements IXpsOptions
```

プレゼンテーションをXPS形式で保存する方法を制御するオプションを提供します。

--------------------

> ```
> The following example shows how to converting presentations to XPS using default settings.
>  
>  // プレゼンテーション ファイルを表す Presentation オブジェクトをインスタンス化します
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
>  // プレゼンテーション ファイルを表す Presentation オブジェクトをインスタンス化します
>  Presentation pres = new Presentation("Convert_XPS_Options.pptx");
>  try {
>      // TiffOptions クラスをインスタンス化します
>      XpsOptions options = new XpsOptions();
>      // MetaFiles を PNG として保存します
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
| [XpsOptions()](#XpsOptions--) | デフォルトコンストラクタです。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | 生成されたドキュメントに非表示スライドを含めるかどうかを指定します。 |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | 生成されたドキュメントに非表示スライドを含めるかどうかを指定します。 |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | プレゼンテーションで使用されるすべてのメタファイルをPNG画像に変換する場合はTrueです。 |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | プレゼンテーションで使用されるすべてのメタファイルをPNG画像に変換する場合はTrueです。 |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | 各スライドの周囲に黒いフレームを描画する場合はTrueです。 |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | 各スライドの周囲に黒いフレームを描画する場合はTrueです。 |
### XpsOptions() {#XpsOptions--}
```
public XpsOptions()
```

デフォルトコンストラクタです。

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

生成されたドキュメントに非表示スライドを含めるかどうかを指定します。デフォルトは false です。

**戻り値:**  
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

生成されたドキュメントに非表示スライドを含めるかどうかを指定します。デフォルトは false です。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public final boolean getSaveMetafilesAsPng()
```

プレゼンテーションで使用されるすべてのメタファイルをPNG画像に変換する場合はTrueです。読み取り/書き込み boolean.

--------------------

デフォルトは **true** です。

**戻り値:**  
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```

プレゼンテーションで使用されるすべてのメタファイルをPNG画像に変換する場合はTrueです。読み取り/書き込み boolean.

--------------------

デフォルトは **true** です。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public final boolean getDrawSlidesFrame()
```

各スライドの周囲に黒いフレームを描画する場合はTrueです。読み取り/書き込み boolean.

--------------------

デフォルトは **false** です。

**戻り値:**  
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```

各スライドの周囲に黒いフレームを描画する場合はTrueです。読み取り/書き込み boolean.

--------------------

デフォルトは **false** です。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |