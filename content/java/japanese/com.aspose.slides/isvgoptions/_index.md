---
title: ISVGOptions
second_title: Aspose.Slides for Java API リファレンス
description: SVG オプションを表します。
type: docs
url: /ja/com.aspose.slides/isvgoptions/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ISVGOptions extends ISaveOptions
```

SVG オプションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getVectorizeText()](#getVectorizeText--) | スライド上のテキストがグラフィックとして保存されるかどうかを決定します。 |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | スライド上のテキストがグラフィックとして保存されるかどうかを決定します。 |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | メタファイルのラスター化の下限解像度を取得または設定します。 |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | メタファイルのラスター化の下限解像度を取得または設定します。 |
| [getDisable3DText()](#getDisable3DText--) | SVG で 3D テキストが無効化されているかどうかを決定します。 |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | SVG で 3D テキストが無効化されているかどうかを決定します。 |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | FromCornerX および FromCenter グラデーションの分割を無効にします。 |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | FromCornerX および FromCenter グラデーションの分割を無効にします。 |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | SVG 1.1 ではマーカーのインセットを定義する機能がありません。 |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | SVG 1.1 ではマーカーのインセットを定義する機能がありません。 |
| [getJpegQuality()](#getJpegQuality--) | JPEG エンコードの品質を決定します。 |
| [setJpegQuality(int value)](#setJpegQuality-int-) | JPEG エンコードの品質を決定します。 |
| [getShapeFormattingController()](#getShapeFormattingController--) | 形状変換を制御できるコールバック インターフェイスを取得および設定します。 |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | 形状変換を制御できるコールバック インターフェイスを取得および設定します。 |
| [getPicturesCompression()](#getPicturesCompression--) | 画像圧縮レベルを表します Read/write \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | 画像圧縮レベルを表します Read/write \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int). |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | 切り取られた部分がドキュメントの一部として残るかどうかを示すブール フラグです。 |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | 切り取られた部分がドキュメントの一部として残るかどうかを示すブール フラグです。 |
| [getUseFrameSize()](#getUseFrameSize--) | テキスト フレームがレンダリング領域に含まれるかどうかを決定します。 |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | テキスト フレームがレンダリング領域に含まれるかどうかを決定します。 |
| [getUseFrameRotation()](#getUseFrameRotation--) | レンダリング時に形状の指定された回転を実行するかどうかを決定します。 |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | レンダリング時に形状の指定された回転を実行するかどうかを決定します。 |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | 外部からロードされたフォントの処理方法を決定します。 |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | 外部からロードされたフォントの処理方法を決定します。 |
| [getInkOptions()](#getInkOptions--) | エクスポートされたドキュメント内の Ink オブジェクトの外観を制御するオプションを提供します。 |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | テキストが合字を使用せずにレンダリングされるかどうかを示す値を取得または設定します。 |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | テキストが合字を使用せずにレンダリングされるかどうかを示す値を取得または設定します。 |

### getVectorizeText() {#getVectorizeText--}
```
public abstract boolean getVectorizeText()
```

スライド上のテキストがグラフィックとして保存されるかどうかを決定します。 Read/write boolean.

**戻り値:**
boolean
### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public abstract void setVectorizeText(boolean value)
```

スライド上のテキストがグラフィックとして保存されるかどうかを決定します。 Read/write boolean.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public abstract int getMetafileRasterizationDpi()
```

メタファイルのラスター化の下限解像度を取得または設定します。 Read/write int.

**戻り値:**
int
### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public abstract void setMetafileRasterizationDpi(int value)
```

メタファイルのラスター化の下限解像度を取得または設定します。 Read/write int.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getDisable3DText() {#getDisable3DText--}
```
public abstract boolean getDisable3DText()
```

SVG で 3D テキストが無効化されているかどうかを決定します。 Read/write boolean.

**戻り値:**
boolean
### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public abstract void setDisable3DText(boolean value)
```

SVG で 3D テキストが無効化されているかどうかを決定します。 Read/write boolean.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public abstract boolean getDisableGradientSplit()
```

FromCornerX および FromCenter グラデーションの分割を無効にします。 Read/write boolean.

**戻り値:**
boolean
### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public abstract void setDisableGradientSplit(boolean value)
```

FromCornerX および FromCenter グラデーションの分割を無効にします。 Read/write boolean.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public abstract boolean getDisableLineEndCropping()
```

SVG 1.1 ではマーカーのインセットを定義する機能がありません。 Aspose.Slides SVG 書き込みエンジンはこの問題に対する回避策として、矢印付きのラインの端を切り取ります。その結果、ラインがマーカーと重なりません。このオプションはその動作をオフにします。 Read/write boolean.

**戻り値:**
boolean
### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public abstract void setDisableLineEndCropping(boolean value)
```

SVG 1.1 ではマーカーのインセットを定義する機能がありません。 Aspose.Slides SVG 書き込みエンジンはこの問題に対する回避策として、矢印付きのラインの端を切り取ります。その結果、ラインがマーカーと重なりません。このオプションはその動作をオフにします。 Read/write boolean.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract int getJpegQuality()
```

JPEG エンコードの品質を決定します。 Read/write int.

**戻り値:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public abstract void setJpegQuality(int value)
```

JPEG エンコードの品質を決定します。 Read/write int.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getShapeFormattingController() {#getShapeFormattingController--}
```
public abstract ISvgShapeFormattingController getShapeFormattingController()
```

形状変換を制御できるコールバック インターフェイスを取得および設定します。 Read/write [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**戻り値:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public abstract void setShapeFormattingController(ISvgShapeFormattingController value)
```

形状変換を制御できるコールバック インターフェイスを取得および設定します。 Read/write [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public abstract int getPicturesCompression()
```

画像圧縮レベルを表します Read/write \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int).

**戻り値:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```

画像圧縮レベルを表します Read/write \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int).

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public abstract boolean getDeletePicturesCroppedAreas()
```

切り取られた部分がドキュメントの一部として残るかどうかを示すブール フラグです。true の場合、切り取られた部分は削除され、false の場合、ドキュメントにシリアライズされます（これによりファイルが大きくなる可能性があります）。 Read/write boolean.

**戻り値:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public abstract void setDeletePicturesCroppedAreas(boolean value)
```

切り取られた部分がドキュメントの一部として残るかどうかを示すブール フラグです。true の場合、切り取られた部分は削除され、false の場合、ドキュメントにシリアライズされます（これによりファイルが大きくなる可能性があります）。 Read/write boolean.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameSize() {#getUseFrameSize--}
```
public abstract boolean getUseFrameSize()
```

テキスト フレームがレンダリング領域に含まれるかどうかを決定します。 Read/write  boolean . デフォルト値は false です。

**戻り値:**
boolean
### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public abstract void setUseFrameSize(boolean value)
```

テキスト フレームがレンダリング領域に含まれるかどうかを決定します。 Read/write  boolean . デフォルト値は false です。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameRotation() {#getUseFrameRotation--}
```
public abstract boolean getUseFrameRotation()
```

レンダリング時に形状の指定された回転を実行するかどうかを決定します。 Read/write  boolean . デフォルト値は true です。

**戻り値:**
boolean
### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public abstract void setUseFrameRotation(boolean value)
```

レンダリング時に形状の指定された回転を実行するかどうかを決定します。 Read/write  boolean . デフォルト値は true です。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public abstract int getExternalFontsHandling()
```

外部からロードされたフォントの処理方法を決定します。 Read/write [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**戻り値:**
int
### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public abstract void setExternalFontsHandling(int value)
```

外部からロードされたフォントの処理方法を決定します。 Read/write [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

エクスポートされたドキュメント内の Ink オブジェクトの外観を制御するオプションを提供します。 Read-only [IInkOptions](../../com.aspose.slides/iinkoptions)

**戻り値:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

テキストが合字を使用せずにレンダリングされるかどうかを示す値を取得または設定します。true に設定すると、レンダリング出力で合字が無効になります。デフォルトでは、このプロパティは false に設定されています。

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
public abstract void setDisableFontLigatures(boolean value)
```

テキストが合字を使用せずにレンダリングされるかどうかを示す値を取得または設定します。true に設定すると、レンダリング出力で合字が無効になります。デフォルトでは、このプロパティは false に設定されています。

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

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |