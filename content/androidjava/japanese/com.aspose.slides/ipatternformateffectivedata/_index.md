---
title: IPatternFormatEffectiveData
second_title: Aspose.Slides for Android via Java API リファレンス
description: 効果的なパターン塗りつぶしプロパティを含む不変オブジェクト。
type: docs
url: /ja/com.aspose.slides/ipatternformateffectivedata/
---```
public interface IPatternFormatEffectiveData
```

効果的なパターン塗りつぶしプロパティを含む不変オブジェクト。

--------------------

このインターフェイスは [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) と [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata) の一部として使用されます。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | パターンのスタイルを返します。 |
| [getForeColor()](#getForeColor--) | 前景パターンカラーを返します。 |
| [getBackColor()](#getBackColor--) | 背景パターンカラーを返します。 |
| [getTileIImage(Integer background, Integer foreground)](#getTileIImage-java.lang.Integer-java.lang.Integer-) | 指定された色でパターン塗りつぶし用のタイル画像を作成します。 |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```

パターンのスタイルを返します。読み取り専用 [PatternStyle](../../com.aspose.slides/patternstyle)。

**戻り値:**
byte
### getForeColor() {#getForeColor--}
```
public abstract Integer getForeColor()
```

前景パターンカラーを返します。読み取り専用 java.lang.Integer。

**戻り値:**
java.lang.Integer
### getBackColor() {#getBackColor--}
```
public abstract Integer getBackColor()
```

背景パターンカラーを返します。読み取り専用 java.lang.Integer。

**戻り値:**
java.lang.Integer
### getTileIImage(Integer background, Integer foreground) {#getTileIImage-java.lang.Integer-java.lang.Integer-}
```
public abstract IImage getTileIImage(Integer background, Integer foreground)
```

指定された色でパターン塗りつぶし用のタイル画像を作成します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| background | java.lang.Integer | パターンの背景 java.lang.Integer。 |
| foreground | java.lang.Integer | パターンの前景 java.lang.Integer。 |

**戻り値:**
[IImage](../../com.aspose.slides/iimage) - タイル [IImage](../../com.aspose.slides/iimage)。