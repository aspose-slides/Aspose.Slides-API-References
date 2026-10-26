---
title: IPatternFormat
second_title: Aspose.Slides for Java API Reference
description: Represents a pattern to fill a shape.
type: docs
url: /ja/com.aspose.slides/ipatternformat/
---```
public interface IPatternFormat
```

シェイプを塗りつぶすためのパターンを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | パターンスタイルを取得または設定します。 |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | パターンスタイルを取得または設定します。 |
| [getForeColor()](#getForeColor--) | 前景パターンカラーを取得します。 |
| [getBackColor()](#getBackColor--) | 背景パターンカラーを取得します。 |
| [getTile(Color background, Color foreground)](#getTile-java.awt.Color-java.awt.Color-) | 指定された色でパターン塗りつぶし用のタイル画像を作成します。 |
| [getTile(Color styleColor)](#getTile-java.awt.Color-) | パターン塗りつぶし用のタイル画像を作成します。 |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```

パターンスタイルを取得または設定します。読み取り/書き込み [PatternStyle](../../com.aspose.slides/patternstyle)。

**戻り値:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public abstract void setPatternStyle(byte value)
```

パターンスタイルを取得または設定します。読み取り/書き込み [PatternStyle](../../com.aspose.slides/patternstyle)。

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
### getTile(Color background, Color foreground) {#getTile-java.awt.Color-java.awt.Color-}
```
public abstract IImage getTile(Color background, Color foreground)
```

指定された色でパターン塗りつぶし用のタイル画像を作成します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| background | java.awt.Color | パターン用の背景 java.awt.Color。 |
| foreground | java.awt.Color | パターン用の前景 java.awt.Color。 |

**戻り値:**
[IImage](../../com.aspose.slides/iimage) - タイル java.awt.image.BufferedImage。
### getTile(Color styleColor) {#getTile-java.awt.Color-}
```
public abstract IImage getTile(Color styleColor)
```

パターン塗りつぶし用のタイル画像を作成します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| styleColor | java.awt.Color | ShapeEx の StyleEx オブジェクトで定義されたデフォルトの java.awt.Color。塗りつぶしの色はこれに依存する場合があります。 |

**戻り値:**
[IImage](../../com.aspose.slides/iimage) - タイル java.awt.image.BufferedImage。