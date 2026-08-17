---
title: ShapeStyle
second_title: Aspose.Slides for Java API リファレンス
description: シェイプのスタイル参照を表します。
type: docs
url: /ja/com.aspose.slides/shapestyle/
---
**継承:**  
java.lang.Object, com.aspose.slides.DomObject

**すべての実装インターフェイス:**  
[com.aspose.slides.IShapeStyle](../../com.aspose.slides/ishapestyle)  
```
public class ShapeStyle extends DomObject<Shape> implements IShapeStyle
```

シェイプのスタイル参照を表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getLineColor()](#getLineColor--) | シェイプの輪郭色を返します。 |
| [getLineStyleIndex()](#getLineStyleIndex--) | スタイルマトリックスで線の列インデックスを取得または設定します。 |
| [setLineStyleIndex(int value)](#setLineStyleIndex-int-) | スタイルマトリックスで線の列インデックスを取得または設定します。 |
| [getFillColor()](#getFillColor--) | シェイプの塗りつぶし色を返します。 |
| [getFillStyleIndex()](#getFillStyleIndex--) | スタイルマトリックスでシェイプの塗りつぶし列インデックスを取得または設定します。 |
| [setFillStyleIndex(short value)](#setFillStyleIndex-short-) | スタイルマトリックスでシェイプの塗りつぶし列インデックスを取得または設定します。 |
| [getEffectColor()](#getEffectColor--) | シェイプの効果色を返します。 |
| [getEffectStyleIndex()](#getEffectStyleIndex--) | スタイルマトリックスでシェイプの効果列インデックスを取得または設定します。 |
| [setEffectStyleIndex(long value)](#setEffectStyleIndex-long-) | スタイルマトリックスでシェイプの効果列インデックスを取得または設定します。 |
| [getFontColor()](#getFontColor--) | シェイプのフォント色を返します。 |
| [getFontCollectionIndex()](#getFontCollectionIndex--) | フォントコレクションでシェイプのフォントインデックスを取得または設定します。 |
| [setFontCollectionIndex(byte value)](#setFontCollectionIndex-byte-) | フォントコレクションでシェイプのフォントインデックスを取得または設定します。 |

### getLineColor() {#getLineColor--}
```
public final IColorFormat getLineColor()
```

シェイプの輪郭色を返します。読み取り専用 [IColorFormat](../../com.aspose.slides/icolorformat)。

**戻り値:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getLineStyleIndex() {#getLineStyleIndex--}
```
public final int getLineStyleIndex()
```

スタイルマトリックスで線の列インデックスを取得または設定します。読み書き int。

**戻り値:**
int

### setLineStyleIndex(int value) {#setLineStyleIndex-int-}
```
public final void setLineStyleIndex(int value)
```

スタイルマトリックスで線の列インデックスを取得または設定します。読み書き int。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getFillColor() {#getFillColor--}
```
public final IColorFormat getFillColor()
```

シェイプの塗りつぶし色を返します。読み取り専用 [IColorFormat](../../com.aspose.slides/icolorformat)。

**戻り値:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getFillStyleIndex() {#getFillStyleIndex--}
```
public final short getFillStyleIndex()
```

スタイルマトリックスでシェイプの塗りつぶし列インデックスを取得または設定します。0 は塗りつぶしなし、正の値はテーマの塗りつぶしスタイルのインデックス、負の値はテーマの背景スタイルのインデックスです。読み書き short。

**戻り値:**
short

### setFillStyleIndex(short value) {#setFillStyleIndex-short-}
```
public final void setFillStyleIndex(short value)
```

スタイルマトリックスでシェイプの塗りつぶし列インデックスを取得または設定します。0 は塗りつぶしなし、正の値はテーマの塗りつぶしスタイルのインデックス、負の値はテーマの背景スタイルのインデックスです。読み書き short。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | short |  |

### getEffectColor() {#getEffectColor--}
```
public final IColorFormat getEffectColor()
```

シェイプの効果色を返します。読み取り専用 [IColorFormat](../../com.aspose.slides/icolorformat)。

**戻り値:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getEffectStyleIndex() {#getEffectStyleIndex--}
```
public final long getEffectStyleIndex()
```

スタイルマトリックスでシェイプの効果列インデックスを取得または設定します。読み書き long。

**戻り値:**
long

### setEffectStyleIndex(long value) {#setEffectStyleIndex-long-}
```
public final void setEffectStyleIndex(long value)
```

スタイルマトリックスでシェイプの効果列インデックスを取得または設定します。読み書き long。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | long |  |

### getFontColor() {#getFontColor--}
```
public final IColorFormat getFontColor()
```

シェイプのフォント色を返します。読み取り専用 [IColorFormat](../../com.aspose.slides/icolorformat)。

**戻り値:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getFontCollectionIndex() {#getFontCollectionIndex--}
```
public final byte getFontCollectionIndex()
```

フォントコレクションでシェイプのフォントインデックスを取得または設定します。読み書き [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex)。

**戻り値:**
byte

### setFontCollectionIndex(byte value) {#setFontCollectionIndex-byte-}
```
public final void setFontCollectionIndex(byte value)
```

フォントコレクションでシェイプのフォントインデックスを取得または設定します。読み書き [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |