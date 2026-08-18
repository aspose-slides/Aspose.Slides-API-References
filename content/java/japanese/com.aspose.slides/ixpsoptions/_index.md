---
title: IXpsOptions
second_title: Aspose.Slides for Java API リファレンス
description: プレゼンテーションが XPS 形式で保存される方法を制御するオプションを提供します。
type: docs
url: /ja/com.aspose.slides/ixpsoptions/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IXpsOptions extends ISaveOptions
```

プレゼンテーションが XPS 形式で保存される方法を制御するオプションを提供します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | True：プレゼンテーションで使用されるすべてのメタファイルを PNG 画像に変換します。 |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | True：プレゼンテーションで使用されるすべてのメタファイルを PNG 画像に変換します。 |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | True：各スライドの周囲に黒い枠線を描画します。 |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | True：各スライドの周囲に黒い枠線を描画します。 |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | 生成されたドキュメントに非表示スライドを含めるかどうかを指定します。 |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | 生成されたドキュメントに非表示スライドを含めるかどうかを指定します。 |
### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public abstract boolean getSaveMetafilesAsPng()
```


True：プレゼンテーションで使用されるすべてのメタファイルを PNG 画像に変換します。 読み取り/書き込み可能なブール値。

--------------------

デフォルトは **true** です。

**戻り値:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```


True：プレゼンテーションで使用されるすべてのメタファイルを PNG 画像に変換します。 読み取り/書き込み可能なブール値。

--------------------

デフォルトは **true** です。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public abstract boolean getDrawSlidesFrame()
```


True：各スライドの周囲に黒い枠線を描画します。 読み取り/書き込み可能なブール値。

--------------------

デフォルトは **false** です。

**戻り値:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```


True：各スライドの周囲に黒い枠線を描画します。 読み取り/書き込み可能なブール値。

--------------------

デフォルトは **false** です。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```


生成されたドキュメントに非表示スライドを含めるかどうかを指定します。 デフォルトは false です。

**戻り値:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```


生成されたドキュメントに非表示スライドを含めるかどうかを指定します。 デフォルトは false です。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |