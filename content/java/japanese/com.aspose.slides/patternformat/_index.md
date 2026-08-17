---
title: PatternFormat
second_title: Aspose.Slides for Java API リファレンス
description: シェイプを塗りつぶすためのパターンを表します。
type: docs
url: /ja/com.aspose.slides/patternformat/
---
**継承:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IPatternFormat](../../com.aspose.slides/ipatternformat)
```
public final class PatternFormat extends PVIObject implements IPatternFormat
```

シェイプを塗りつぶすためのパターンを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPatternStyle()](#getPatternStyle--) | パターンスタイルを取得または設定します。 |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | パターンスタイルを取得または設定します。 |
| [getForeColor()](#getForeColor--) | 前景パターンカラーを取得します。 |
| [getBackColor()](#getBackColor--) | 背景パターンカラーを取得します。 |
| [getTile(Color background, Color foreground)](#getTile-java.awt.Color-java.awt.Color-) | 指定された色でパターン塗りつぶし用のタイル画像を作成します。 |
| [getTile(Color styleColor)](#getTile-java.awt.Color-) | パターン塗りつぶし用のタイル画像を作成します。 |
### getVersion() {#getVersion--}
```
public long getVersion()
```

バージョン。読み取り専用の long。

**戻り値:**
long
### getPatternStyle() {#getPatternStyle--}
```
public final byte getPatternStyle()
```

パターンスタイルを取得または設定します。読み書き可能 [PatternStyle](../../com.aspose.slides/patternstyle)。

**戻り値:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public final void setPatternStyle(byte value)
```

パターンスタイルを取得または設定します。読み書き可能 [PatternStyle](../../com.aspose.slides/patternstyle)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getForeColor() {#getForeColor--}
```
public final IColorFormat getForeColor()
```

前景パターンカラーを取得します。読み取り専用 [IColorFormat](../../com.aspose.slides/icolorformat)。

**戻り値:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public final IColorFormat getBackColor()
```

背景パターンカラーを取得します。読み取り専用 [IColorFormat](../../com.aspose.slides/icolorformat)。

**戻り値:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Color background, Color foreground) {#getTile-java.awt.Color-java.awt.Color-}
```
public final IImage getTile(Color background, Color foreground)
```

指定された色でパターン塗りつぶし用のタイル画像を作成します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| background | java.awt.Color | パターンの背景 java.awt.Color。 |
| foreground | java.awt.Color | パターンの前景 java.awt.Color。 |

**戻り値:**
[IImage](../../com.aspose.slides/iimage) - Tile [IImage](../../com.aspose.slides/iimage)。
### getTile(Color styleColor) {#getTile-java.awt.Color-}
```
public final IImage getTile(Color styleColor)
```

パターン塗りつぶし用のタイル画像を作成します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| styleColor | java.awt.Color | デフォルト java.awt.Color |

**戻り値:**
[IImage](../../com.aspose.slides/iimage) - Tile [IImage](../../com.aspose.slides/iimage).