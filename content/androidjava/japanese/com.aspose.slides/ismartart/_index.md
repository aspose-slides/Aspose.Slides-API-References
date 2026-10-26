---
title: ISmartArt
second_title: Aspose.Slides for Android 用 Java API リファレンス
description: SmartArt ダイアグラムを表します。
type: docs
url: /ja/com.aspose.slides/ismartart/
---
**実装されたすべてのインターフェイス:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ISmartArt extends IGraphicalObject
```

SmartArt ダイアグラムを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getAllNodes()](#getAllNodes--) | SmartArt オブジェクト内のすべてのノードのコレクションを返します。 |
| [getNodes()](#getNodes--) | SmartArt オブジェクト内のルートノードのコレクションを返します。 |
| [getLayout()](#getLayout--) | SmartArt オブジェクトのレイアウトを取得または設定します。 |
| [setLayout(int value)](#setLayout-int-) | SmartArt オブジェクトのレイアウトを取得または設定します。 |
| [getQuickStyle()](#getQuickStyle--) | SmartArt オブジェクトのクイックスタイルを取得または設定します。 |
| [setQuickStyle(int value)](#setQuickStyle-int-) | SmartArt オブジェクトのクイックスタイルを取得または設定します。 |
| [getColorStyle()](#getColorStyle--) | SmartArt オブジェクトのカラー スタイルを取得または設定します。 |
| [setColorStyle(int value)](#setColorStyle-int-) | SmartArt オブジェクトのカラー スタイルを取得または設定します。 |
| [isReversed()](#isReversed--) | SmartArt 図の（左から右への）LTR または（右から左への）RTL の状態を取得または設定します（図が反転をサポートしている場合）。 |
| [setReversed(boolean value)](#setReversed-boolean-) | SmartArt 図の（左から右への）LTR または（右から左への）RTL の状態を取得または設定します（図が反転をサポートしている場合）。 |

### getAllNodes() {#getAllNodes--}
```
public abstract ISmartArtNodeCollection getAllNodes()
```

SmartArt オブジェクト内のすべてのノードのコレクションを返します。 読み取り専用 [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)。

**戻り値:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)

### getNodes() {#getNodes--}
```
public abstract ISmartArtNodeCollection getNodes()
```

SmartArt オブジェクト内のルートノードのコレクションを返します。 読み取り専用 [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)。

**戻り値:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)

### getLayout() {#getLayout--}
```
public abstract int getLayout()
```

SmartArt オブジェクトのレイアウトを取得または設定します。 読み取り/書き込み [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype)。

**戻り値:**
int

### setLayout(int value) {#setLayout-int-}
```
public abstract void setLayout(int value)
```

SmartArt オブジェクトのレイアウトを取得または設定します。 読み取り/書き込み [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getQuickStyle() {#getQuickStyle--}
```
public abstract int getQuickStyle()
```

SmartArt オブジェクトのクイックスタイルを取得または設定します。 読み取り/書き込み [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype)。

**戻り値:**
int

### setQuickStyle(int value) {#setQuickStyle-int-}
```
public abstract void setQuickStyle(int value)
```

SmartArt オブジェクトのクイックスタイルを取得または設定します。 読み取り/書き込み [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getColorStyle() {#getColorStyle--}
```
public abstract int getColorStyle()
```

SmartArt オブジェクトのカラー スタイルを取得または設定します。 読み取り/書き込み [SmartArtColorType](../../com.aspose.slides/smartartcolortype)。

**戻り値:**
int

### setColorStyle(int value) {#setColorStyle-int-}
```
public abstract void setColorStyle(int value)
```

SmartArt オブジェクトのカラー スタイルを取得または設定します。 読み取り/書き込み [SmartArtColorType](../../com.aspose.slides/smartartcolortype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### isReversed() {#isReversed--}
```
public abstract boolean isReversed()
```

SmartArt 図の（左から右への）LTR または（右から左への）RTL の状態を取得または設定します（図が反転をサポートしている場合）。 読み取り/書き込み boolean。

**戻り値:**
boolean

### setReversed(boolean value) {#setReversed-boolean-}
```
public abstract void setReversed(boolean value)
```

SmartArt 図の（左から右への）LTR または（右から左への）RTL の状態を取得または設定します（図が反転をサポートしている場合）。 読み取り/書き込み boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |