---
title: IShapeStyle
second_title: Aspose.Slides for Java API Reference
description: Represent shapes style reference.
type: docs
url: /ja/com.aspose.slides/ishapestyle/
---```
public interface IShapeStyle
```

シェイプのスタイル参照を表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getLineColor()](#getLineColor--) | シェイプのアウトラインカラーを返します。 |
| [getLineStyleIndex()](#getLineStyleIndex--) | スタイルマトリックスでラインの列インデックスを取得または設定します。 |
| [setLineStyleIndex(int value)](#setLineStyleIndex-int-) | スタイルマトリックスでラインの列インデックスを取得または設定します。 |
| [getFillColor()](#getFillColor--) | シェイプの塗りつぶしカラーを返します。 |
| [getFillStyleIndex()](#getFillStyleIndex--) | スタイルマトリックスでシェイプの塗りつぶし列インデックスを取得または設定します。 |
| [setFillStyleIndex(short value)](#setFillStyleIndex-short-) | スタイルマトリックスでシェイプの塗りつぶし列インデックスを取得または設定します。 |
| [getEffectColor()](#getEffectColor--) | シェイプのエフェクトカラーを返します。 |
| [getEffectStyleIndex()](#getEffectStyleIndex--) | スタイルマトリックスでシェイプのエフェクト列インデックスを取得または設定します。 |
| [setEffectStyleIndex(long value)](#setEffectStyleIndex-long-) | スタイルマトリックスでシェイプのエフェクト列インデックスを取得または設定します。 |
| [getFontColor()](#getFontColor--) | シェイプのフォントカラーを返します。 |
| [getFontCollectionIndex()](#getFontCollectionIndex--) | フォントコレクションでシェイプのフォントインデックスを取得または設定します。 |
| [setFontCollectionIndex(byte value)](#setFontCollectionIndex-byte-) | フォントコレクションでシェイプのフォントインデックスを取得または設定します。 |

### getLineColor() {#getLineColor--}
```
public abstract IColorFormat getLineColor()
```

シェイプのアウトラインカラーを返します。読み取り専用 [IColorFormat](../../com.aspose.slides/icolorformat)。

**戻り値:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getLineStyleIndex() {#getLineStyleIndex--}
```
public abstract int getLineStyleIndex()
```

スタイルマトリックスでラインの列インデックスを取得または設定します。読み取り/書き込み int。

**戻り値:**
int

### setLineStyleIndex(int value) {#setLineStyleIndex-int-}
```
public abstract void setLineStyleIndex(int value)
```

スタイルマトリックスでラインの列インデックスを取得または設定します。読み取り/書き込み int。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getFillColor() {#getFillColor--}
```
public abstract IColorFormat getFillColor()
```

シェイプの塗りつぶしカラーを返します。読み取り専用 [IColorFormat](../../com.aspose.slides/icolorformat)。

**戻り値:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getFillStyleIndex() {#getFillStyleIndex--}
```
public abstract short getFillStyleIndex()
```

スタイルマトリックスでシェイプの塗りつぶし列インデックスを取得または設定します。0 は塗りなし、正の値はテーマの塗りつぶしスタイルのインデックス、負の値はテーマの背景スタイルのインデックスを表します。読み取り/書き込み short。

**戻り値:**
short

### setFillStyleIndex(short value) {#setFillStyleIndex-short-}
```
public abstract void setFillStyleIndex(short value)
```

スタイルマトリックスでシェイプの塗りつぶし列インデックスを取得または設定します。0 は塗りなし、正の値はテーマの塗りつぶしスタイルのインデックス、負の値はテーマの背景スタイルのインデックスを表します。読み取り/書き込み short。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | short |  |

### getEffectColor() {#getEffectColor--}
```
public abstract IColorFormat getEffectColor()
```

シェイプのエフェクトカラーを返します。読み取り専用 [IColorFormat](../../com.aspose.slides/icolorformat)。

**戻り値:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getEffectStyleIndex() {#getEffectStyleIndex--}
```
public abstract long getEffectStyleIndex()
```

スタイルマトリックスでシェイプのエフェクト列インデックスを取得または設定します。読み取り/書き込み long。

**戻り値:**
long

### setEffectStyleIndex(long value) {#setEffectStyleIndex-long-}
```
public abstract void setEffectStyleIndex(long value)
```

スタイルマトリックスでシェイプのエフェクト列インデックスを取得または設定します。読み取り/書き込み long。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | long |  |

### getFontColor() {#getFontColor--}
```
public abstract IColorFormat getFontColor()
```

シェイプのフォントカラーを返します。読み取り専用 [IColorFormat](../../com.aspose.slides/icolorformat)。

**戻り値:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getFontCollectionIndex() {#getFontCollectionIndex--}
```
public abstract byte getFontCollectionIndex()
```

フォントコレクションでシェイプのフォントインデックスを取得または設定します。読み取り/書き込み [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex)。

**戻り値:**
byte

### setFontCollectionIndex(byte value) {#setFontCollectionIndex-byte-}
```
public abstract void setFontCollectionIndex(byte value)
```

フォントコレクションでシェイプのフォントインデックスを取得または設定します。読み取り/書き込み [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |