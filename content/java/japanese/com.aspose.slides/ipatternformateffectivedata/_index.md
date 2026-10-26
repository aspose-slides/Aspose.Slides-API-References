---
title: IPatternFormatEffectiveData
second_title: Aspose.Slides for Java API リファレンス
description: 有効なパターン塗りつぶしプロパティを含む不変オブジェクトです。
type: docs
url: /ja/com.aspose.slides/ipatternformateffectivedata/
---```
public interface IPatternFormatEffectiveData
```

有効なパターン塗りつぶしプロパティを含む不変オブジェクトです。

--------------------

このインターフェイスは [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) と [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata) の一部として使用されます。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | パターンスタイルを返します。 |
| [getForeColor()](#getForeColor--) | 前景パターンの色を返します。 |
| [getBackColor()](#getBackColor--) | 背景パターンの色を返します。 |
| [getTileIImage(Color background, Color foreground)](#getTileIImage-java.awt.Color-java.awt.Color-) | 指定された色でパターン塗りつぶし用のタイル画像を作成します。 |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```


パターンスタイルを返します。読み取り専用 [PatternStyle](../../com.aspose.slides/patternstyle)。

**戻り値:**
byte
### getForeColor() {#getForeColor--}
```
public abstract Color getForeColor()
```


前景パターンの色を返します。読み取り専用 java.awt.Color。

**戻り値:**
java.awt.Color
### getBackColor() {#getBackColor--}
```
public abstract Color getBackColor()
```


背景パターンの色を返します。読み取り専用 java.awt.Color。

**戻り値:**
java.awt.Color
### getTileIImage(Color background, Color foreground) {#getTileIImage-java.awt.Color-java.awt.Color-}
```
public abstract IImage getTileIImage(Color background, Color foreground)
```


指定された色でパターン塗りつぶし用のタイル画像を作成します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| background | java.awt.Color | パターンの背景になる java.awt.Color。 |
| foreground | java.awt.Color | パターンの前景になる java.awt.Color。 |

**戻り値:**
[IImage](../../com.aspose.slides/iimage) - タイル [IImage](../../com.aspose.slides/iimage)。