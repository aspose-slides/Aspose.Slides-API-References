---
title: PatternFormat
second_title: Java API リファレンスによる Android 用 Aspose.Slides
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
| [getForeColor()](#getForeColor--) | 前景パターンの色を取得します。 |
| [getBackColor()](#getBackColor--) | 背景パターンの色を取得します。 |
| [getTile(Integer background, Integer foreground)](#getTile-java.lang.Integer-java.lang.Integer-) | 指定された色でパターン塗りつぶし用のタイル画像を作成します。 |
| [getTile(Integer styleColor)](#getTile-java.lang.Integer-) | パターン塗りつぶし用のタイル画像を作成します。 |

### getVersion() {#getVersion--}
```
public long getVersion()
```

バージョン。読み取り専用 long.

**戻り値:**  
long

### getPatternStyle() {#getPatternStyle--}
```
public final byte getPatternStyle()
```

パターンスタイルを取得または設定します。読み取り/書き込み [PatternStyle](../../com.aspose.slides/patternstyle)。

**戻り値:**  
byte

### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public final void setPatternStyle(byte value)
```

パターンスタイルを取得または設定します。読み取り/書き込み [PatternStyle](../../com.aspose.slides/patternstyle)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getForeColor() {#getForeColor--}
```
public final IColorFormat getForeColor()
```

前景パターンの色を取得します。読み取り専用 [IColorFormat](../../com.aspose.slides/icolorformat)。

**戻り値:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getBackColor() {#getBackColor--}
```
public final IColorFormat getBackColor()
```

背景パターンの色を取得します。読み取り専用 [IColorFormat](../../com.aspose.slides/icolorformat)。

**戻り値:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getTile(Integer background, Integer foreground) {#getTile-java.lang.Integer-java.lang.Integer-}
```
public final IImage getTile(Integer background, Integer foreground)
```

指定された色でパターン塗りつぶし用のタイル画像を作成します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| background | java.lang.Integer | パターンの背景 java.lang.Integer。 |
| foreground | java.lang.Integer | パターンの前景 java.lang.Integer。 |

**戻り値:**  
[IImage](../../com.aspose.slides/iimage) - Tile [IImage](../../com.aspose.slides/iimage)。

### getTile(Integer styleColor) {#getTile-java.lang.Integer-}
```
public final IImage getTile(Integer styleColor)
```

パターン塗りつぶし用のタイル画像を作成します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| styleColor | java.lang.Integer | デフォルト java.lang.Integer |

**戻り値:**  
[IImage](../../com.aspose.slides/iimage) - Tile [IImage](../../com.aspose.slides/iimage)。