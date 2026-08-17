---
title: SmartArt
second_title: Java 用 Aspose.Slides API リファレンス
description: SmartArt ダイアグラムを表します
type: docs
url: /ja/com.aspose.slides/smartart/
---
**継承:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**実装されているすべてのインターフェイス:**
[com.aspose.slides.ISmartArt](../../com.aspose.slides/ismartart)
```
public class SmartArt extends GraphicalObject implements ISmartArt
```

SmartArt ダイアグラムを表します
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
| [isReversed()](#isReversed--) | SmartArt ダイアグラムが逆転をサポートしている場合、（左から右）LTR または（右から左）RTL に関する状態を取得または設定します。 |
| [setReversed(boolean value)](#setReversed-boolean-) | SmartArt ダイアグラムが逆転をサポートしている場合、（左から右）LTR または（右から左）RTL に関する状態を取得または設定します。 |
### getAllNodes() {#getAllNodes--}
```
public final ISmartArtNodeCollection getAllNodes()
```

SmartArt オブジェクト内のすべてのノードのコレクションを返します。 読み取り専用 [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**戻り値:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getNodes() {#getNodes--}
```
public final ISmartArtNodeCollection getNodes()
```

SmartArt オブジェクトのルートノードのコレクションを返します。 読み取り専用 [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**戻り値:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getLayout() {#getLayout--}
```
public final int getLayout()
```

SmartArt オブジェクトのレイアウトを取得または設定します。 読み書き可能 [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**戻り値:**
int
### setLayout(int value) {#setLayout-int-}
```
public final void setLayout(int value)
```

SmartArt オブジェクトのレイアウトを取得または設定します。 読み書き可能 [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getQuickStyle() {#getQuickStyle--}
```
public final int getQuickStyle()
```

SmartArt オブジェクトのクイックスタイルを取得または設定します。 読み書き可能 [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**戻り値:**
int
### setQuickStyle(int value) {#setQuickStyle-int-}
```
public final void setQuickStyle(int value)
```

SmartArt オブジェクトのクイックスタイルを取得または設定します。 読み書き可能 [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getColorStyle() {#getColorStyle--}
```
public final int getColorStyle()
```

SmartArt オブジェクトのカラースタイルを取得または設定します。 読み書き可能 [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**戻り値:**
int
### setColorStyle(int value) {#setColorStyle-int-}
```
public final void setColorStyle(int value)
```

SmartArt オブジェクトのカラースタイルを取得または設定します。 読み書き可能 [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### isReversed() {#isReversed--}
```
public final boolean isReversed()
```

SmartArt ダイアグラムが逆転をサポートしている場合、（左から右）LTR または（右から左）RTL に関する状態を取得または設定します。 読み書き可能 boolean .

**戻り値:**
boolean
### setReversed(boolean value) {#setReversed-boolean-}
```
public final void setReversed(boolean value)
```

SmartArt ダイアグラムが逆転をサポートしている場合、（左から右）LTR または（右から左）RTL に関する状態を取得または設定します。 読み書き可能 boolean .

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |