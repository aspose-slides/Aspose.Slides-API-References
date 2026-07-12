---
title: INormalViewRestoredProperties
second_title: Aspose.Slides for Android の Java API リファレンス
description: 正規ビューの子要素が restoredTop のときの幅、restoredLeft のときの高さを指定し、領域が可変の復元サイズ（最小化でも最大化でもない）である場合のスライド領域のサイズ設定を定義します。
type: docs
url: /ja/com.aspose.slides/inormalviewrestoredproperties/
---```
public interface INormalViewRestoredProperties
```

正規ビューの子要素が restoredTop のときの幅、restoredLeft のときの高さを指定し、領域が可変の復元サイズ（最小化でも最大化でもない）である場合のスライド領域のサイズ設定を定義します。

## Methods

| Method | Description |
| --- | --- |
| [getDimensionSize()](#getDimensionSize--) | スライド領域のサイズを指定します（RestoredTop の子要素の場合は幅、RestoredLeft の子要素の場合は高さ）。 |
| [setDimensionSize(float value)](#setDimensionSize-float-) | スライド領域のサイズを指定します（RestoredTop の子要素の場合は幅、RestoredLeft の子要素の場合は高さ）。 |
| [getAutoAdjust()](#getAutoAdjust--) | ウィンドウ内のビューをリサイズした際に、サイドコンテンツ領域のサイズが新しいサイズに合わせて補正されるかどうかを指定します。Read/write boolean |
| [setAutoAdjust(boolean value)](#setAutoAdjust-boolean-) | ウィンドウ内のビューをリサイズした際に、サイドコンテンツ領域のサイズが新しいサイズに合わせて補正されるかどうかを指定します。Read/write boolean |

### getDimensionSize() {#getDimensionSize--}
```
public abstract float getDimensionSize()
```

スライド領域のサイズを指定します（RestoredTop の子要素の場合は幅、RestoredLeft の子要素の場合は高さ）。Read/write float。

**Returns:**
float

### setDimensionSize(float value) {#setDimensionSize-float-}
```
public abstract void setDimensionSize(float value)
```

スライド領域のサイズを指定します（RestoredTop の子要素の場合は幅、RestoredLeft の子要素の場合は高さ）。Read/write float。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getAutoAdjust() {#getAutoAdjust--}
```
public abstract boolean getAutoAdjust()
```

ウィンドウ内のビューをリサイズした際に、サイドコンテンツ領域のサイズが新しいサイズに合わせて補正されるかどうかを指定します。Read/write boolean。

**Returns:**
boolean

### setAutoAdjust(boolean value) {#setAutoAdjust-boolean-}
```
public abstract void setAutoAdjust(boolean value)
```

ウィンドウ内のビューをリサイズした際に、サイドコンテンツ領域のサイズが新しいサイズに合わせて補正されるかどうかを指定します。Read/write boolean。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |