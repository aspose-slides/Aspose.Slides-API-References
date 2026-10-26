---
title: FontSubstRule
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: フォント置換情報を表します
type: docs
url: /ja/com.aspose.slides/fontsubstrule/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IFontSubstRule](../../com.aspose.slides/ifontsubstrule)
```
public class FontSubstRule implements IFontSubstRule
```

フォント置換情報を表します
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [FontSubstRule(IFontData sourceFont, IFontData destFont)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | 新しいインスタンスを作成します。 |
| [FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-) | 新しいインスタンスを作成します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getSourceFont()](#getSourceFont--) | 置換するフォント。 |
| [getDestFont()](#getDestFont--) | 置換に使用するフォント。 |
| [getReplaceFontCondition()](#getReplaceFontCondition--) | 置換に適用するルール。 |
### FontSubstRule(IFontData sourceFont, IFontData destFont) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont)
```


新しいインスタンスを作成します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | ソースフォント。 |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | 宛先フォント。 |

### FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)
```


新しいインスタンスを作成します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | ソースフォント。 |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | 宛先フォント。 |
| fontSubstRule | int | フォント置換ルール。 |

### getSourceFont() {#getSourceFont--}
```
public final IFontData getSourceFont()
```


置換するフォント。 読み取り専用 [IFontData](../../com.aspose.slides/ifontdata)。

**戻り値:**
[IFontData](../../com.aspose.slides/ifontdata)
### getDestFont() {#getDestFont--}
```
public final IFontData getDestFont()
```


置換に使用するフォント。 読み取り専用 [IFontData](../../com.aspose.slides/ifontdata)。

**戻り値:**
[IFontData](../../com.aspose.slides/ifontdata)
### getReplaceFontCondition() {#getReplaceFontCondition--}
```
public final int getReplaceFontCondition()
```


置換に適用するルール。 読み取り専用 [FontSubstCondition](../../com.aspose.slides/fontsubstcondition)。

**戻り値:**
int