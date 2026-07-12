---
title: SmartArt
second_title: Aspose.Slides for Android の Java API リファレンス
description: SmartArt 図を表します
type: docs
url: /ja/com.aspose.slides/smartart/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**All Implemented Interfaces:**
[com.aspose.slides.ISmartArt](../../com.aspose.slides/ismartart)
```
public class SmartArt extends GraphicalObject implements ISmartArt
```

SmartArt 図を表します
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getAllNodes()](#getAllNodes--) | SmartArt オブジェクト内のすべてのノードのコレクションを返します。 |
| [getNodes()](#getNodes--) | SmartArt オブジェクトのルートノードのコレクションを返します。 |
| [getLayout()](#getLayout--) | SmartArt オブジェクトのレイアウトを取得または設定します。 |
| [setLayout(int value)](#setLayout-int-) | SmartArt オブジェクトのレイアウトを取得または設定します。 |
| [getQuickStyle()](#getQuickStyle--) | SmartArt オブジェクトのクイックスタイルを取得または設定します。 |
| [setQuickStyle(int value)](#setQuickStyle-int-) | SmartArt オブジェクトのクイックスタイルを取得または設定します。 |
| [getColorStyle()](#getColorStyle--) | SmartArt オブジェクトのカラースタイルを取得または設定します。 |
| [setColorStyle(int value)](#setColorStyle-int-) | SmartArt オブジェクトのカラースタイルを取得または設定します。 |
| [isReversed()](#isReversed--) | SmartArt 図の左右方向 (LTR) または右から左 (RTL) の状態を取得または設定します（図が反転に対応している場合）。 |
| [setReversed(boolean value)](#setReversed-boolean-) | SmartArt 図の左右方向 (LTR) または右から左 (RTL) の状態を取得または設定します（図が反転に対応している場合）。 |
### getAllNodes() {#getAllNodes--}
```
public final ISmartArtNodeCollection getAllNodes()
```


SmartArt オブジェクト内のすべてのノードのコレクションを返します。読み取り専用 [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)。

**戻り値:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getNodes() {#getNodes--}
```
public final ISmartArtNodeCollection getNodes()
```


SmartArt オブジェクトのルートノードのコレクションを返します。読み取り専用 [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)。

**戻り値:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getLayout() {#getLayout--}
```
public final int getLayout()
```


SmartArt オブジェクトのレイアウトを取得または設定します。読み取り/書き込み [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype)。

**戻り値:**
int
### setLayout(int value) {#setLayout-int-}
```
public final void setLayout(int value)
```


SmartArt オブジェクトのレイアウトを取得または設定します。読み取り/書き込み [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getQuickStyle() {#getQuickStyle--}
```
public final int getQuickStyle()
```


SmartArt オブジェクトのクイックスタイルを取得または設定します。読み取り/書き込み [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype)。

**戻り値:**
int
### setQuickStyle(int value) {#setQuickStyle-int-}
```
public final void setQuickShape(int value)
```


SmartArt オブジェクトのクイックスタイルを取得または設定します。読み取り/書き込み [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getColorStyle() {#getColorStyle--}
```
public final int getColorStyle()
```


SmartArt オブジェクトのカラースタイルを取得または設定します。読み取り/書き込み [SmartArtColorType](../../com.aspose.slides/smartartcolortype)。

**戻り値:**
int
### setColorStyle(int value) {#setColorStyle-int-}
```
public final void setColorStyle(int value)
```


SmartArt オブジェクトのカラースタイルを取得または設定します。読み取り/書き込み [SmartArtColorType](../../com.aspose.slides/smartartcolortype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### isReversed() {#isReversed--}
```
public final boolean isReversed()
```


SmartArt 図の左右方向 (LTR) または右から左 (RTL) の状態を取得または設定します（図が反転に対応している場合）。読み取り/書き込み boolean 。

**戻り値:**
boolean
### setReversed(boolean value) {#setReversed-boolean-}
```
public final void setReversed(boolean value)
```


SmartArt 図の左右方向 (LTR) または右から左 (RTL) の状態を取得または設定します（図が反転に対応している場合）。読み取り/書き込み boolean 。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |