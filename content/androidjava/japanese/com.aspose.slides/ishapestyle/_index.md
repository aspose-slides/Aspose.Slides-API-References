---
title: IShapeStyle
second_title: Aspose.Slides for Android via Java API Reference
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
| [getLineColor()](#getLineColor--) | シェイプの輪郭色を返します。 |
| [getLineStyleIndex()](#getLineStyleIndex--) | スタイル行列内の線の列インデックスを取得または設定します。 |
| [setLineStyleIndex(int value)](#setLineStyleIndex-int-) | スタイル行列内の線の列インデックスを取得または設定します。 |
| [getFillColor()](#getFillColor--) | シェイプの塗りつぶし色を返します。 |
| [getFillStyleIndex()](#getFillStyleIndex--) | スタイル行列内のシェイプの塗りつぶし列インデックスを取得または設定します。 |
| [setFillStyleIndex(short value)](#setFillStyleIndex-short-) | スタイル行列内のシェイプの塗りつぶし列インデックスを取得または設定します。 |
| [getEffectColor()](#getEffectColor--) | シェイプの効果色を返します。 |
| [getEffectStyleIndex()](#getEffectStyleIndex--) | スタイル行列内のシェイプの効果列インデックスを取得または設定します。 |
| [setEffectStyleIndex(long value)](#setEffectStyleIndex-long-) | スタイル行列内のシェイプの効果列インデックスを取得または設定します。 |
| [getFontColor()](#getFontColor--) | シェイプのフォント色を返します。 |
| [getFontCollectionIndex()](#getFontCollectionIndex--) | フォントコレクション内のシェイプのフォントインデックスを取得または設定します。 |
| [setFontCollectionIndex(byte value)](#setFontCollectionIndex-byte-) | フォントコレクション内のシェイプのフォントインデックスを取得または設定します。 |
### getLineColor() {#getLineColor--}
```
public abstract IColorFormat getLineColor()
```


シェイプの輪郭色を返します。読み取り専用 [IColorFormat](../../com.aspose.slides/icolorformat).

**戻り値:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getLineStyleIndex() {#getLineStyleIndex--}
```
public abstract int getLineStyleIndex()
```


スタイル行列内の線の列インデックスを取得または設定します。読み書き int.

**戻り値:**
int
### setLineStyleIndex(int value) {#setLineStyleIndex-int-}
```
public abstract void setLineStyleIndex(int value)
```


スタイル行列内の線の列インデックスを取得または設定します。読み書き int.

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### getFillColor() {#getFillColor--}
```
public abstract IColorFormat getFillColor()
```


シェイプの塗りつぶし色を返します。読み取り専用 [IColorFormat](../../com.aspose.slides/icolorformat).

**戻り値:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFillStyleIndex() {#getFillStyleIndex--}
```
public abstract short getFillStyleIndex()
```


スタイル行列内のシェイプの塗りつぶし列インデックスを取得または設定します。0 は塗りつぶしなしを意味し、正の値はテーマの塗りつぶしスタイルのインデックス、負の値はテーマの背景スタイルのインデックスを示します。読み書き short.

**戻り値:**
short
### setFillStyleIndex(short value) {#setFillStyleIndex-short-}
```
public abstract void setFillStyleIndex(short value)
```


スタイル行列内のシェイプの塗りつぶし列インデックスを取得または設定します。0 は塗りつぶしなしを意味し、正の値はテーマの塗りつぶしスタイルのインデックス、負の値はテーマの背景スタイルのインデックスを示します。読み書き short.

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | short |  |
### getEffectColor() {#getEffectColor--}
```
public abstract IColorFormat getEffectColor()
```


シェイプの効果色を返します。読み取り専用 [IColorFormat](../../com.aspose.slides/icolorformat).

**戻り値:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffectStyleIndex() {#getEffectStyleIndex--}
```
public abstract long getEffectStyleIndex()
```


スタイル行列内のシェイプの効果列インデックスを取得または設定します。読み書き long.

**戻り値:**
long
### setEffectStyleIndex(long value) {#setEffectStyleIndex-long-}
```
public abstract void setEffectStyleIndex(long value)
```


スタイル行列内のシェイプの効果列インデックスを取得または設定します。読み書き long.

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | long |  |
### getFontColor() {#getFontColor--}
```
public abstract IColorFormat getFontColor()
```


シェイプのフォント色を返します。読み取り専用 [IColorFormat](../../com.aspose.slides/icolorformat).

**戻り値:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFontCollectionIndex() {#getFontCollectionIndex--}
```
public abstract byte getFontCollectionIndex()
```


フォントコレクション内のシェイプのフォントインデックスを取得または設定します。読み書き [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**戻り値:**
byte
### setFontCollectionIndex(byte value) {#setFontCollectionIndex-byte-}
```
public abstract void setFontCollectionIndex(byte value)
```


フォントコレクション内のシェイプのフォントインデックスを取得または設定します。読み書き [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |