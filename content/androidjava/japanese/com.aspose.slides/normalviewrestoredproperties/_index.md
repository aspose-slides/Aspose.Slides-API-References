---
title: NormalViewRestoredProperties
second_title: Aspose.Slides for Android の Java API リファレンス
description: スライド領域のサイズを指定します。通常ビューで、領域が可変の復元サイズ（最小化でも最大化でもない）の場合、子が restoredTop のときは幅、子が restoredLeft のときは高さです。
type: docs
url: /ja/com.aspose.slides/normalviewrestoredproperties/
---
**継承:**  
java.lang.Object

**実装されたすべてのインターフェイス:**  
[com.aspose.slides.INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)  
```
public class NormalViewRestoredProperties implements INormalViewRestoredProperties
```

スライド領域のサイズを指定します（通常ビューで、領域が可変の復元サイズ（最小化でも最大化でもない）である場合、子が restoredTop のときは幅、子が restoredLeft のときは高さ）。

## メソッド

| Method | Description |
| --- | --- |
| [getDimensionSize()](#getDimensionSize--) | スライド領域のサイズを指定します（RestoredTop の子の場合は幅、RestoredLeft の子の場合は高さ）。 |
| [setDimensionSize(float value)](#setDimensionSize-float-) | スライド領域のサイズを指定します（RestoredTop の子の場合は幅、RestoredLeft の子の場合は高さ）。 |
| [getAutoAdjust()](#getAutoAdjust--) | アプリケーション内でビューを含むウィンドウのサイズ変更時に、サイドコンテンツ領域のサイズが新しいサイズに合わせて補正されるかどうかを指定します。Read/write boolean |
| [setAutoAdjust(boolean value)](#setAutoAdjust-boolean-) | アプリケーション内でビューを含むウィンドウのサイズ変更時に、サイドコンテンツ領域のサイズが新しいサイズに合わせて補正されるかどうかを指定します。Read/write boolean |

### getDimensionSize() {#getDimensionSize--}
```
public final float getDimensionSize()
```

スライド領域のサイズを指定します（RestoredTop の子の場合は幅、RestoredLeft の子の場合は高さ）。Read/write float.

**戻り値:**  
float

### setDimensionSize(float value) {#setDimensionSize-float-}
```
public final void setDimensionSize(float value)
```

スライド領域のサイズを指定します（RestoredTop の子の場合は幅、RestoredLeft の子の場合は高さ）。Read/write float.

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getAutoAdjust() {#getAutoAdjust--}
```
public final boolean getAutoAdjust()
```

アプリケーション内でビューを含むウィンドウのサイズ変更時に、サイドコンテンツ領域のサイズが新しいサイズに合わせて補正されるかどうかを指定します。Read/write boolean

**戻り値:**  
boolean

### setAutoAdjust(boolean value) {#setAutoAdjust-boolean-}
```
public final void setAutoAdjust(boolean value)
```

アプリケーション内でビューを含むウィンドウのサイズ変更時に、サイドコンテンツ領域のサイズが新しいサイズに合わせて補正されるかどうかを指定します。Read/write boolean

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |