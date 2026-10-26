---
title: IPatternFormat
second_title: Aspose.Slides for Android via Java API Reference
description: シェイプを塗りつぶすパターンを表します。
type: docs
url: /ja/com.aspose.slides/ipatternformat/
---```
public interface IPatternFormat
```

シェイプを塗りつぶすパターンを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | パターンスタイルを取得または設定します。 |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | パターンスタイルを取得または設定します。 |
| [getForeColor()](#getForeColor--) | 前景パターンカラーを取得します。 |
| [getBackColor()](#getBackColor--) | 背景パターンカラーを取得します。 |
| [getTile(Integer background, Integer foreground)](#getTile-java.lang.Integer-java.lang.Integer-) | 指定された色でパターン塗りつぶしのタイル画像を作成します。 |
| [getTile(Integer styleColor)](#getTile-java.lang.Integer-) | パターン塗りつぶしのタイル画像を作成します。 |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```

パターンスタイルを取得または設定します。読み書き [PatternStyle](../../com.aspose.slides/patternstyle)。

**戻り値:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public abstract void setPatternStyle(byte value)
```

パターンスタイルを取得または設定します。読み書き [PatternStyle](../../com.aspose.slides/patternstyle)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |
### getForeColor() {#getForeColor--}
```
public abstract IColorFormat getForeColor()
```

前景パターンカラーを取得します。読み取り専用 [IColorFormat](../../com.aspose.slides/icolorformat)。

**戻り値:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public abstract IColorFormat getBackColor()
```

背景パターンカラーを取得します。読み取り専用 [IColorFormat](../../com.aspose.slides/icolorformat)。

**戻り値:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Integer background, Integer foreground) {#getTile-java.lang.Integer-java.lang.Integer-}
```
public abstract IImage getTile(Integer background, Integer foreground)
```

指定された色でパターン塗りつぶしのタイル画像を作成します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| background | java.lang.Integer | パターンの背景 java.lang.Integer。 |
| foreground | java.lang.Integer | パターンの前景 java.lang.Integer。 |

**戻り値:**
[IImage](../../com.aspose.slides/iimage) - タイル android.graphics.Bitmap.
### getTile(Integer styleColor) {#getTile-java.lang.Integer-}
```
public abstract IImage getTile(Integer styleColor)
```

パターン塗りつぶしのタイル画像を作成します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| styleColor | java.lang.Integer | ShapeEx の StyleEx オブジェクトで定義されたデフォルトの java.lang.Integer。塗りつぶしの色はこれに依存する可能性があります。 |

**戻り値:**
[IImage](../../com.aspose.slides/iimage) - タイル android.graphics.Bitmap.