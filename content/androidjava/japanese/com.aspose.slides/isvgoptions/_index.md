---
title: ISVGOptions
second_title: Aspose.Slides for Android の Java API リファレンス
description: SVG オプションを表します。
type: docs
url: /ja/com.aspose.slides/isvgoptions/
---
**実装されたすべてのインターフェイス:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ISVGOptions extends ISaveOptions
```

SVG のオプションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getVectorizeText()](#getVectorizeText--) | スライド上のテキストがグラフィックとして保存されるかどうかを決定します。 |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | スライド上のテキストがグラフィックとして保存されるかどうかを決定します。 |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | メタファイルのラスター化の下限解像度を取得または設定します。 |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | メタファイルのラスター化の下限解像度を取得または設定します。 |
| [getDisable3DText()](#getDisable3DText--) | SVG で 3D テキストが無効化されているかどうかを決定します。 |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | SVG で 3D テキストが無効化されているかどうかを決定します。 |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | FromCornerX と FromCenter のグラデーション分割を無効にします。 |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | FromCornerX と FromCenter のグラデーション分割を無効にします。 |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | SVG 1.1 ではマーカーのインセットを定義する機能がありません。 |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | SVG 1.1 ではマーカーのインセットを定義する機能がありません。 |
| [getJpegQuality()](#getJpegQuality--) | JPEG エンコード品質を決定します。 |
| [setJpegQuality(int value)](#setJpegQuality-int-) | JPEG エンコード品質を決定します。 |
| [getShapeFormattingController()](#getShapeFormattingController--) | ユーザーがシェイプ変換を制御できるコールバックインターフェイスを取得および設定します。 |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | ユーザーがシェイプ変換を制御できるコールバックインターフェイスを取得および設定します。 |
| [getPicturesCompression()](#getPicturesCompression--) | 画像圧縮レベルを表します 読み取り/書き込み \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | 画像圧縮レベルを表します 読み取り/書き込み \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int). |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | クロップされた部分がドキュメントの一部として残るかどうかを示すブールフラグです。 |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | クロップされた部分がドキュメントの一部として残るかどうかを示すブールフラグです。 |
| [getUseFrameSize()](#getUseFrameSize--) | テキストフレームがレンダリング領域に含まれるかどうかを決定します。 |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | テキストフレームがレンダリング領域に含まれるかどうかを決定します。 |
| [getUseFrameRotation()](#getUseFrameRotation--) | レンダリング時にシェイプの指定された回転を実行するかどうかを決定します。 |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | レンダリング時にシェイプの指定された回転を実行するかどうかを決定します。 |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | 外部から読み込まれたフォントの取り扱い方法を決定します。 |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | 外部から読み込まれたフォントの取り扱い方法を決定します。 |
| [getInkOptions()](#getInkOptions--) | エクスポートされたドキュメント内の Ink オブジェクトの外観を制御するオプションを提供します。 |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | テキストが合字を使用せずに描画されるかどうかを示す値を取得または設定します。 |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | テキストが合字を使用せずに描画されるかどうかを示す値を取得または設定します。 |

### getVectorizeText() {#getVectorizeText--}
```
public abstract boolean getVectorizeText()
```

スライド上のテキストがグラフィックとして保存されるかどうかを決定します。読み取り/書き込み boolean。

**戻り値:**
boolean

### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public abstract void setVectorizeText(boolean value)
```

スライド上のテキストがグラフィックとして保存されるかどうかを決定します。読み取り/書き込み boolean。

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public abstract int getMetafileRasterizationDpi()
```

メタファイルのラスター化の下限解像度を取得または設定します。読み取り/書き込み int。

**戻り値:**
int

### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public abstract void setMetafileRasterizationDpi(int value)
```

メタファイルのラスター化の下限解像度を取得または設定します。読み取り/書き込み int。

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDisable3DText() {#getDisable3DText--}
```
public abstract boolean getDisable3DText()
```

SVG で 3D テキストが無効化されているかどうかを決定します。読み取り/書き込み boolean。

**戻り値:**
boolean

### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public abstract void setDisable3DText(boolean value)
```

SVG で 3D テキストが無効化されているかどうかを決定します。読み取り/書き込み boolean。

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public abstract boolean getDisableGradientSplit()
```

FromCornerX と FromCenter のグラデーション分割を無効にします。読み取り/書き込み boolean。

**戻り値:**
boolean

### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public abstract void setDisableGradientSplit(boolean value)
```

FromCornerX と FromCenter のグラデーション分割を無効にします。読み取り/書き込み boolean。

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public abstract boolean getDisableLineEndCropping()
```

SVG 1.1 ではマーカーのインセットを定義する機能がありません。Aspose.Slides SVG 書き出しエンジンはこの問題に対処するため、矢印付きの線端をクロップし、線がマーカーと重ならないようにします。このオプションはその動作をオフにします。読み取り/書き込み boolean。

**戻り値:**
boolean

### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public abstract void setDisableLineEndCropping(boolean value)
```

SVG 1.1 ではマーカーのインセットを定義する機能がありません。Aspose.Slides SVG 書き出しエンジンはこの問題に対処するため、矢印付きの線端をクロップし、線がマーカーと重ならないようにします。このオプションはその動作をオフにします。読み取り/書き込み boolean。

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract int getJpegQuality()
```

JPEG エンコード品質を決定します。読み取り/書き込み int。

**戻り値:**
int

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public abstract void setJpegQuality(int value)
```

JPEG エンコード品質を決定します。読み取り/書き込み int。

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getShapeFormattingController() {#getShapeFormattingController--}
```
public abstract ISvgShapeFormattingController getShapeFormattingController()
```

ユーザーがシェイプ変換を制御できるコールバックインターフェイスを取得および設定します。読み取り/書き込み [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)。

**戻り値:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)

### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public abstract void setShapeFormattingController(ISvgShapeFormattingController value)
```

ユーザーがシェイプ変換を制御できるコールバックインターフェイスを取得および設定します。読み取り/書き込み [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)。

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public abstract int getPicturesCompression()
```

画像圧縮レベルを表します 読み取り/書き込み \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)。

**戻り値:**
int

### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```

画像圧縮レベルを表します 読み取り/書き込み \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)。

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public abstract boolean getDeletePicturesCroppedAreas()
```

クロップされた部分がドキュメントの一部として残るかどうかを示すブールフラグです。true の場合はクロップされた部分が削除され、false の場合はドキュメントにシリアライズされます（ファイルが大きくなる可能性があります）。読み取り/書き込み boolean。

**戻り値:**
boolean

### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public abstract void setDeletePicturesCroppedAreas(boolean value)
```

クロップされた部分がドキュメントの一部として残るかどうかを示すブールフラグです。true の場合はクロップされた部分が削除され、false の場合はドキュメントにシリアライズされます（ファイルが大きくなる可能性があります）。読み取り/書き込み boolean。

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameSize() {#getUseFrameSize--}
```
public abstract boolean getUseFrameSize()
```

テキストフレームがレンダリング領域に含まれるかどうかを決定します。読み取り/書き込み boolean。デフォルト値は false です。

**戻り値:**
boolean

### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public abstract void setUseFrameSize(boolean value)
```

テキストフレームがレンダリング領域に含まれるかどうかを決定します。読み取り/書き込み boolean。デフォルト値は false です。

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameRotation() {#getUseFrameRotation--}
```
public abstract boolean getUseFrameRotation()
```

レンダリング時にシェイプの指定された回転を実行するかどうかを決定します。読み取り/書き込み boolean。デフォルト値は true です。

**戻り値:**
boolean

### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public abstract void setUseFrameRotation(boolean value)
```

レンダリング時にシェイプの指定された回転を実行するかどうかを決定します。読み取り/書き込み boolean。デフォルト値は true です。

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public abstract int getExternalFontsHandling()
```

外部から読み込まれたフォントの取り扱い方法を決定します。読み取り/書き込み [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling)。

**戻り値:**
int

### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public abstract void setExternalFontsHandling(int value)
```

外部から読み込まれたフォントの取り扱い方法を決定します。読み取り/書き込み [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling)。

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

エクスポートされたドキュメント内の Ink オブジェクトの外観を制御するオプションを提供します。読み取り専用 [IInkOptions](../../com.aspose.slides/iinkoptions)

**戻り値:**
[IInkOptions](../../com.aspose.slides/iinkoptions)

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

テキストが合字を使用せずに描画されるかどうかを示す値を取得または設定します。true に設定すると、合字は描画出力で無効になります。既定ではこのプロパティは false に設定されています。

**戻り値:**
boolean

### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public abstract void setDisableFontLigatures(boolean value)
```

テキストが合字を使用せずに描画されるかどうかを示す値を取得または設定します。true に設定すると、合字は描画出力で無効になります。既定ではこのプロパティは false に設定されています。

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |