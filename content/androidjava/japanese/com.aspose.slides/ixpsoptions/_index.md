---
title: IXpsOptions
second_title: Aspose.Slides for Android の Java API リファレンス
description: プレゼンテーションを XPS 形式で保存する方法を制御するオプションを提供します。
type: docs
url: /ja/com.aspose.slides/ixpsoptions/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IXpsOptions extends ISaveOptions
```

プレゼンテーションを XPS 形式で保存する方法を制御するオプションを提供します。

## Methods

| Method | Description |
| --- | --- |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | プレゼンテーションで使用されるすべてのメタファイルを PNG 画像に変換するかどうかを true に設定します。 |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | プレゼンテーションで使用されるすべてのメタファイルを PNG 画像に変換するかどうかを true に設定します。 |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | 各スライドの周囲に黒いフレームを描画するかどうかを true に設定します。 |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | 各スライドの周囲に黒いフレームを描画するかどうかを true に設定します。 |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | 生成されたドキュメントに非表示スライドを含めるかどうかを指定します。 |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | 生成されたドキュメントに非表示スライドを含めるかどうかを指定します。 |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public abstract boolean getSaveMetafilesAsPng()
```

プレゼンテーションで使用されるすべてのメタファイルを PNG 画像に変換するかどうかを true に設定します。Read/write boolean.

--------------------

デフォルトは **true** です。

**Returns:**
boolean

### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```

プレゼンテーションで使用されるすべてのメタファイルを PNG 画像に変換するかどうかを true に設定します。Read/write boolean.

--------------------

デフォルトは **true** です。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public abstract boolean getDrawSlidesFrame()
```

各スライドの周囲に黒いフレームを描画するかどうかを true に設定します。Read/write boolean.

--------------------

デフォルトは **false** です。

**Returns:**
boolean

### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```

各スライドの周囲に黒いフレームを描画するかどうかを true に設定します。Read/write boolean.

--------------------

デフォルトは **false** です。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

生成されたドキュメントに非表示スライドを含めるかどうかを指定します。Default is false.

**Returns:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

生成されたドキュメントに非表示スライドを含めるかどうかを指定します。Default is false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |