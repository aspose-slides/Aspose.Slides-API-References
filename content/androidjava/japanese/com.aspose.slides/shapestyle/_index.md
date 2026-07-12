---
title: ShapeStyle
second_title: Android 用 Aspose.Slides の Java API リファレンス
description: シェイプのスタイル参照を表します。
type: docs
url: /ja/com.aspose.slides/shapestyle/
---
**継承:**
java.lang.Object, com.aspose.slides.DomObject

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IShapeStyle](../../com.aspose.slides/ishapestyle)
```
public class ShapeStyle extends DomObject<Shape> implements IShapeStyle
```

シェイプのスタイル参照を表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getLineColor()](#getLineColor--) | シェイプのアウトラインカラーを返します。 |
| [getLineStyleIndex()](#getLineStyleIndex--) | スタイル行列内の線の列インデックスを取得または設定します。 |
| [setLineStyleIndex(int value)](#setLineStyleIndex-int-) | スタイル行列内の線の列インデックスを取得または設定します。 |
| [getFillColor()](#getFillColor--) | シェイプの塗りつぶしカラーを返します。 |
| [getFillStyleIndex()](#getFillStyleIndex--) | スタイル行列内のシェイプの塗りつぶし列インデックスを取得または設定します。 |
| [setFillStyleIndex(short value)](#setFillStyleIndex-short-) | スタイル行列内のシェイプの塗りつぶし列インデックスを取得または設定します。 |
| [getEffectColor()](#getEffectColor--) | シェイプのエフェクトカラーを返します。 |
| [getEffectStyleIndex()](#getEffectStyleIndex--) | スタイル行列内のシェイプのエフェクト列インデックスを取得または設定します。 |
| [setEffectStyleIndex(long value)](#setEffectStyleIndex-long-) | スタイル行列内のシェイプのエフェクト列インデックスを取得または設定します。 |
| [getFontColor()](#getFontColor--) | シェイプのフォントカラーを返します。 |
| [getFontCollectionIndex()](#getFontCollectionIndex--) | フォントコレクション内のシェイプのフォントインデックスを取得または設定します。 |
| [setFontCollectionIndex(byte value)](#setFontCollectionIndex-byte-) | フォントコレクション内のシェイプのフォントインデックスを取得または設定します。 |
### getLineColor() {#getLineColor--}
```
public final IColorFormat getLineColor()
```

シェイプのアウトラインカラーを返します。読み取り専用 [IColorFormat](../../com.aspose.slides/icolorformat)。

**戻り値:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getLineStyleIndex() {#getLineStyleIndex--}
```
public final int getLineStyleIndex()
```

スタイル行列内の線の列インデックスを取得または設定します。読み書き可能 int。

**戻り値:**
int
### setLineStyleIndex(int value) {#setLineStyleIndex-int-}
```
public final void setLineStyleIndex(int value)
```

スタイル行列内の線の列インデックスを取得または設定します。読み書き可能 int。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### getFillColor() {#getFillColor--}
```
public final IColorFormat getFillColor()
```

シェイプの塗りつぶしカラーを返します。読み取り専用 [IColorFormat](../../com.aspose.slides/icolorformat)。

**戻り値:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFillStyleIndex() {#getFillStyleIndex--}
```
public final short getFillStyleIndex()
```

スタイル行列内のシェイプの塗りつぶし列インデックスを取得または設定します。0 は塗りつぶしなしを意味し、正の値はテーマの塗りつぶしスタイルのインデックス、負の値はテーマの背景スタイルのインデックスを表します。読み書き可能 short。

**戻り値:**
short
### setFillStyleIndex(short value) {#setFillStyleIndex-short-}
```
public final void setFillStyleIndex(short value)
```

スタイル行列内のシェイプの塗りつぶし列インデックスを取得または設定します。0 は塗りつぶしなしを意味し、正の値はテーマの塗りつぶしスタイルのインデックス、負の値はテーマの背景スタイルのインデックスを表します。読み書き可能 short。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | short |  |
### getEffectColor() {#getEffectColor--}
```
public final IColorFormat getEffectColor()
```

シェイプのエフェクトカラーを返します。読み取り専用 [IColorFormat](../../com.aspose.slides/icolorformat)。

**戻り値:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffectStyleIndex() {#getEffectStyleIndex--}
```
public final long getEffectStyleIndex()
```

スタイル行列内のシェイプのエフェクト列インデックスを取得または設定します。読み書き可能 long。

**戻り値:**
long
### setEffectStyleIndex(long value) {#setEffectStyleIndex-long-}
```
public final void setEffectStyleIndex(long value)
```

スタイル行列内のシェイプのエフェクト列インデックスを取得または設定します。読み書き可能 long。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | long |  |
### getFontColor() {#getFontColor--}
```
public final IColorFormat getFontColor()
```

シェイプのフォントカラーを返します。読み取り専用 [IColorFormat](../../com.aspose.slides/icolorformat)。

**戻り値:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFontCollectionIndex() {#getFontCollectionIndex--}
```
public final byte getFontCollectionIndex()
```

フォントコレクション内のシェイプのフォントインデックスを取得または設定します。読み書き可能 [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex)。

**戻り値:**
byte
### setFontCollectionIndex(byte value) {#setFontCollectionIndex-byte-}
```
public final void setFontCollectionIndex(byte value)
```

フォントコレクション内のシェイプのフォントインデックスを取得または設定します。読み書き可能 [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |