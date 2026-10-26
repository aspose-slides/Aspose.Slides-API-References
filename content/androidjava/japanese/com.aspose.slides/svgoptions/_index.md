---
title: SVGOptions
second_title: Aspose.Slides for Android via Java API リファレンス
description: SVG オプションを表します。
type: docs
url: /ja/com.aspose.slides/svgoptions/
---
**継承:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**実装されているすべてのインターフェイス:**
[com.aspose.slides.ISVGOptions](../../com.aspose.slides/isvgoptions), java.lang.Cloneable
```
public final class SVGOptions extends SaveOptions implements ISVGOptions, Cloneable
```

SVG オプションを表します。
## コンストラクター

| コンストラクター | 説明 |
| --- | --- |
| [SVGOptions()](#SVGOptions--) | SVGOptions クラスの新しいインスタンスを初期化します。 |
| [SVGOptions(ILinkEmbedController linkEmbedController)](#SVGOptions-com.aspose.slides.ILinkEmbedController-) | リンク埋め込みコントローラーオブジェクトを指定して、SVGOptions クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getInkOptions()](#getInkOptions--) | エクスポートされたドキュメント内の Ink オブジェクトの外観を制御するオプションを提供します。 |
| [getUseFrameSize()](#getUseFrameSize--) | テキストフレームがレンダリング領域に含まれるかどうかを決定します。 |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | テキストフレームがレンダリング領域に含まれるかどうかを決定します。 |
| [getUseFrameRotation()](#getUseFrameRotation--) | レンダリング時にシェイプの指定された回転を実行するかどうかを決定します。 |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | レンダリング時にシェイプの指定された回転を実行するかどうかを決定します。 |
| [getVectorizeText()](#getVectorizeText--) | スライド上のテキストがグラフィックとして保存されるかどうかを決定します。 |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | スライド上のテキストがグラフィックとして保存されるかどうかを決定します。 |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | メタファイルのラスター化に対する下限解像度を取得または設定します。 |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | メタファイルのラスター化に対する下限解像度を取得または設定します。 |
| [getDisable3DText()](#getDisable3DText--) | SVG で 3D テキストが無効化されているかどうかを決定します。 |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | SVG で 3D テキストが無効化されているかどうかを決定します。 |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | FromCornerX および FromCenter グラデーションの分割を無効にします。 |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | FromCornerX および FromCenter グラデーションの分割を無効にします。 |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | SVG 1.1 ではマーカーのインセットを定義する機能がありません。 |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | SVG 1.1 ではマーカーのインセットを定義する機能がありません。 |
| [getDefault()](#getDefault--) | デフォルト設定を返します。 |
| [getSimple()](#getSimple--) | 最も簡易で小さな SVG ファイル生成の設定を返します。 |
| [getWYSIWYG()](#getWYSIWYG--) | 最も正確な SVG ファイル生成の設定を返します。 |
| [getJpegQuality()](#getJpegQuality--) | JPEG エンコーディングの品質を決定します。 |
| [setJpegQuality(int value)](#setJpegQuality-int-) | JPEG エンコーディングの品質を決定します。 |
| [getShapeFormattingController()](#getShapeFormattingController--) | シェイプ変換を制御できるコールバックインターフェイスを取得および設定します。 |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | シェイプ変換を制御できるコールバックインターフェイスを取得および設定します。 |
| [getPicturesCompression()](#getPicturesCompression--) | 画像圧縮レベルを表します |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | 画像圧縮レベルを表します |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | 切り抜かれた部分が文書の一部として残るかどうかを示すブールフラグです。 |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | 切り抜かれた部分が文書の一部として残るかどうかを示すブールフラグです。 |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | 外部から読み込まれたフォントの取り扱い方法を決定します。 |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | 外部から読み込まれたフォントの取り扱い方法を決定します。 |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | テキストが合字を使用せずにレンダリングされるかどうかを示す値を取得または設定します。 |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | テキストが合字を使用せずにレンダリングされるかどうかを示す値を取得または設定します。 |

### SVGOptions() {#SVGOptions--}
```
public SVGOptions()
```

SVGOptions クラスの新しいインスタンスを初期化します。

### SVGOptions(ILinkEmbedController linkEmbedController) {#SVGOptions-com.aspose.slides.ILinkEmbedController-}
```
public SVGOptions(ILinkEmbedController linkEmbedController)
```

リンク埋め込みコントローラーオブジェクトを指定して、SVGOptions クラスの新しいインスタンスを初期化します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | リンク埋め込みコントローラーの参照。 |

--------------------

リンク埋め込みコントローラーは、リソース（画像など）を埋め込むか外部リソースとして参照するかを判断するデリゲートオブジェクトです。

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

エクスポートされたドキュメント内の Ink オブジェクトの外観を制御するオプションを提供します。 読み取り専用 [IInkOptions](../../com.aspose.slides/iinkoptions)

**戻り値:**
[IInkOptions](../../com.aspose.slides/iinkoptions)

### getUseFrameSize() {#getUseFrameSize--}
```
public final boolean getUseFrameSize()
```

テキストフレームがレンダリング領域に含まれるかどうかを決定します。 読み書き可能 boolean 。 デフォルト値は false です。

**戻り値:**
boolean

### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public final void setUseFrameSize(boolean value)
```

テキストフレームがレンダリング領域に含まれるかどうかを決定します。 読み書き可能 boolean 。 デフォルト値は false です。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameRotation() {#getUseFrameRotation--}
```
public final boolean getUseFrameRotation()
```

レンダリング時にシェイプの指定された回転を実行するかどうかを決定します。 読み書き可能 boolean 。 デフォルト値は true です。

**戻り値:**
boolean

### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public final void setUseFrameRotation(boolean value)
```

レンダリング時にシェイプの指定された回転を実行するかどうかを決定します。 読み書き可能 boolean 。 デフォルト値は true です。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getVectorizeText() {#getVectorizeText--}
```
public final boolean getVectorizeText()
```

スライド上のテキストがグラフィックとして保存されるかどうかを決定します。 読み書き可能 boolean 。

**戻り値:**
boolean

### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public final void setVectorizeText(boolean value)
```

スライド上のテキストがグラフィックとして保存されるかどうかを決定します。 読み書き可能 boolean 。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public final int getMetafileRasterizationDpi()
```

メタファイルのラスター化に対する下限解像度を取得または設定します。 読み書き可能 int 。

**戻り値:**
int

### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public final void setMetafileRasterizationDpi(int value)
```

メタファイルのラスター化に対する下限解像度を取得または設定します。 読み書き可能 int 。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getDisable3DText() {#getDisable3DText--}
```
public final boolean getDisable3DText()
```

SVG で 3D テキストが無効化されているかどうかを決定します。 読み書き可能 boolean 。

**戻り値:**
boolean

### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public final void setDisable3DText(boolean value)
```

SVG で 3D テキストが無効化されているかどうかを決定します。 読み書き可能 boolean 。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public final boolean getDisableGradientSplit()
```

FromCornerX および FromCenter グラデーションの分割を無効にします。 読み書き可能 boolean 。

**戻り値:**
boolean

### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public final void setDisableGradientSplit(boolean value)
```

FromCornerX および FromCenter グラデーションの分割を無効にします。 読み書き可能 boolean 。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public final boolean getDisableLineEndCropping()
```

SVG 1.1 ではマーカーのインセットを定義する機能がありません。Aspose.Slides SVG ライティングエンジンはこの問題への回避策として、矢印付きの線端を切り取ることでマーカーと重ならないようにします。このオプションはその動作をオフにします。 読み書き可能 boolean 。

**戻り値:**
boolean

### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public final void setDisableLineEndCropping(boolean value)
```

SVG 1.1 ではマーカーのインセットを定義する機能がありません。Aspose.Slides SVG ライティングエンジンはこの問題への回避策として、矢印付きの線端を切り取ることでマーカーと重ならないようにします。このオプションはその動作をオフにします。 読み書き可能 boolean 。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getDefault() {#getDefault--}
```
public static SVGOptions getDefault()
```

デフォルト設定を返します。 読み取り専用 [SVGOptions](../../com.aspose.slides/svgoptions)。

**戻り値:**
[SVGOptions](../../com.aspose.slides/svgoptions)

### getSimple() {#getSimple--}
```
public static SVGOptions getSimple()
```

最も簡易で小さな SVG ファイル生成の設定を返します。 読み取り専用 [SVGOptions](../../com.aspose.slides/svgoptions)。

**戻り値:**
[SVGOptions](../../com.aspose.slides/svgoptions)

### getWYSIWYG() {#getWYSIWYG--}
```
public static SVGOptions getWYSIWYG()
```

最も正確な SVG ファイル生成の設定を返します。 読み取り専用 [SVGOptions](../../com.aspose.slides/svgoptions)。

**戻り値:**
[SVGOptions](../../com.aspose.slides/svgoptions)

### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```

JPEG エンコーディングの品質を決定します。 読み書き可能 int 。

**戻り値:**
int

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```

JPEG エンコーディングの品質を決定します。 読み書き可能 int 。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getShapeFormattingController() {#getShapeFormattingController--}
```
public final ISvgShapeFormattingController getShapeFormattingController()
```

シェイプ変換を制御できるコールバックインターフェイスを取得および設定します。 読み書き可能 [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)。

**戻り値:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)

### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public final void setShapeFormattingController(ISvgShapeFormattingController value)
```

シェイプ変換を制御できるコールバックインターフェイスを取得および設定します。 読み書き可能 [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```

画像圧縮レベルを表します

**戻り値:**
int

### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public final void setPicturesCompression(int value)
```

画像圧縮レベルを表します

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public final boolean getDeletePicturesCroppedAreas()
```

切り抜かれた部分が文書の一部として残るかどうかを示すブールフラグです。true の場合は切り抜かれた部分が削除され、false の場合は文書にシリアライズされます（これによりファイルが大きくなる可能性があります）。

**戻り値:**
boolean

### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```

切り抜かれた部分が文書の一部として残るかどうかを示すブールフラグです。true の場合は切り抜かれた部分が削除され、false の場合は文書にシリアライズされます（これによりファイルが大きくなる可能性があります）。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public final int getExternalFontsHandling()
```

外部から読み込まれたフォントの取り扱い方法を決定します。 読み書き可能 [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling)。

**戻り値:**
int

### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public final void setExternalFontsHandling(int value)
```

外部から読み込まれたフォントの取り扱い方法を決定します。 読み書き可能 [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

テキストが合字を使用せずにレンダリングされるかどうかを示す値を取得または設定します。true に設定すると、レンダリング出力で合字が無効になります。デフォルトではこのプロパティは false に設定されています。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      SVGOptions options = new SVGOptions();
>      options.setDisableFontLigatures(true);
> 
>      FileOutputStream fileStream = new FileOutputStream("slide-0.svg");
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream);
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

テキストが合字を使用せずにレンダリングされるかどうかを示す値を取得または設定します。true に設定すると、レンダリング出力で合字が無効になります。デフォルトではこのプロパティは false に設定されています。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      SVGOptions options = new SVGOptions();
>      options.setDisableFontLigatures(true);
> 
>      FileOutputStream fileStream = new FileOutputStream("slide-0.svg");
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |