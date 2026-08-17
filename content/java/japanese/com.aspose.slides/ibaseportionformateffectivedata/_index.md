---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Slides for Java APIリファレンス
description: 効果的なテキスト部分の書式設定プロパティを含む不変オブジェクトの基本インターフェイスです。
type: docs
url: /ja/com.aspose.slides/ibaseportionformateffectivedata/
---```
public interface IBasePortionFormatEffectiveData
```

効果的なテキスト部分の書式設定プロパティを含む不変オブジェクトの基本インターフェイスです。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | テキストの輪郭描画用のLineFormatプロパティを返します。 |
| [getFillFormat()](#getFillFormat--) | テキストのFillFormatプロパティを返します。 |
| [getEffectFormat()](#getEffectFormat--) | テキストのEffectFormatプロパティを返します。 |
| [getHighlightColor()](#getHighlightColor--) | テキストのハイライトに使用される色を返します。 |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | 下線の輪郭描画に使用されるLineFormatプロパティを返します。 |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | 下線のFillFormatプロパティを返します。 |
| [getFontBold()](#getFontBold--) | フォントが太字かどうかを判定します。 |
| [getFontItalic()](#getFontItalic--) | フォントが斜体かどうかを判定します。 |
| [getKumimoji()](#getKumimoji--) | 数字がテキストの東アジア言語固有の縦書きレイアウトを無視すべきかどうかを判定します。 |
| [getNormaliseHeight()](#getNormaliseHeight--) | テキストの高さを正規化すべきかどうかを判定します。 |
| [getProofDisabled()](#getProofDisabled--) | テキストが校正されないようにすべきかどうかを判定します。 |
| [getFontUnderline()](#getFontUnderline--) | テキストの下線タイプを返します。 |
| [getTextCapType()](#getTextCapType--) | テキストの大文字化タイプを返します。 |
| [getStrikethroughType()](#getStrikethroughType--) | テキストの取り消し線タイプを返します。 |
| [getSmartTagClean()](#getSmartTagClean--) | スマートタグをクリーニングすべきかどうかを判定します。 |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | 下線スタイルが独自のLineFormatプロパティを持つか、テキストのLineFormatプロパティから継承するかを判定します。 |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | 下線スタイルが独自のFillFormatプロパティを持つか、テキストのFillFormatプロパティから継承するかを判定します。 |
| [getFontHeight()](#getFontHeight--) | テキスト部分のフォント高さ（ポイント単位）を返します。 |
| [getLatinFont()](#getLatinFont--) | ラテン文字フォント情報を返します。 |
| [getEastAsianFont()](#getEastAsianFont--) | 東アジア文字フォント情報を返します。 |
| [getComplexScriptFont()](#getComplexScriptFont--) | 複合スクリプトフォント情報を返します。 |
| [getSymbolFont()](#getSymbolFont--) | シンボリックフォント情報を返します。 |
| [getEscapement()](#getEscapement--) | 上付きまたは下付きテキストを返します。 |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | カーニングを有効にすべき最小フォントサイズを返します。 |
| [getLanguageId()](#getLanguageId--) | 言語のIdを返します。 |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | 代替言語のIdを返します。 |
| [getSpacing()](#getSpacing--) | 文字間隔の増分（ポイント単位）を返します。 |
### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormatEffectiveData getLineFormat()
```


テキストの輪郭描画用のLineFormatプロパティを返します。読み取り専用 [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)。

**戻り値:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```


テキストのFillFormatプロパティを返します。読み取り専用 [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)。

**戻り値:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormatEffectiveData getEffectFormat()
```


テキストのEffectFormatプロパティを返します。読み取り専用 [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata)。

**戻り値:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata)
### getHighlightColor() {#getHighlightColor--}
```
public abstract Color getHighlightColor()
```


テキストのハイライトに使用される色を返します。読み取り専用 java.awt.Color。

**戻り値:**
java.awt.Color
### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormatEffectiveData getUnderlineLineFormat()
```


下線の輪郭描画に使用されるLineFormatプロパティを返します。読み取り専用 [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)。

**戻り値:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)
### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormatEffectiveData getUnderlineFillFormat()
```


下線のFillFormatプロパティを返します。読み取り専用 [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)。

**戻り値:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getFontBold() {#getFontBold--}
```
public abstract boolean getFontBold()
```


フォントが太字かどうかを判定します。読み取り専用 boolean。

**戻り値:**
boolean
### getFontItalic() {#getFontItalic--}
```
public abstract boolean getFontItalic()
```


フォントが斜体かどうかを判定します。読み取り専用 boolean。

**戻り値:**
boolean
### getKumimoji() {#getKumimoji--}
```
public abstract boolean getKumimoji()
```


数字がテキストの東アジア言語固有の縦書きレイアウトを無視すべきかどうかを判定します。読み取り専用 boolean。

**戻り値:**
boolean
### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract boolean getNormaliseHeight()
```


テキストの高さを正規化すべきかどうかを判定します。読み取り専用 boolean。

**戻り値:**
boolean
### getProofDisabled() {#getProofDisabled--}
```
public abstract boolean getProofDisabled()
```


テキストが校正されないようにすべきかどうかを判定します。読み取り専用 boolean。

**戻り値:**
boolean
### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```


テキストの下線タイプを返します。読み取り専用 [TextUnderlineType](../../com.aspose.slides/textunderlinetype)。

**戻り値:**
byte
### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```


テキストの大文字化タイプを返します。読み取り専用 [TextCapType](../../com.aspose.slides/textcaptype)。

**戻り値:**
byte
### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```


テキストの取り消し線タイプを返します。読み取り専用 [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype)。

**戻り値:**
byte
### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```


スマートタグをクリーニングすべきかどうかを判定します。読み取り専用 boolean。

**戻り値:**
boolean
### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract boolean isHardUnderlineLine()
```


下線スタイルが独自のLineFormatプロパティを持つか、テキストのLineFormatプロパティから継承するかを判定します。読み取り専用 boolean。

**戻り値:**
boolean
### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract boolean isHardUnderlineFill()
```


下線スタイルが独自のFillFormatプロパティを持つか、テキストのFillFormatプロパティから継承するかを判定します。読み取り専用 boolean。

**戻り値:**
boolean
### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```


テキスト部分のフォント高さ（ポイント単位）を返します。読み取り専用 float。

**戻り値:**
float
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```


ラテン文字フォント情報を返します。読み取り専用 [IFontData](../../com.aspose.slides/ifontdata)。

**戻り値:**
[IFontData](../../com.aspose.slides/ifontdata)
### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```


東アジア文字フォント情報を返します。読み取り専用 [IFontData](../../com.aspose.slides/ifontdata)。

**戻り値:**
[IFontData](../../com.aspose.slides/ifontdata)
### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```


複合スクリプトフォント情報を返します。読み取り専用 [IFontData](../../com.aspose.slides/ifontdata)。

**戻り値:**
[IFontData](../../com.aspose.slides/ifontdata)
### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```


シンボリックフォント情報を返します。読み取り専用 [IFontData](../../com.aspose.slides/ifontdata)。

**戻り値:**
[IFontData](../../com.aspose.slides/ifontdata)
### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```


上付きまたは下付きテキストを返します。-100%（下付き）から100%（上付き）の範囲の値です。読み取り専用 float。

**戻り値:**
float
### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```


カーニングを有効にすべき最小フォントサイズを返します。読み取り専用 float。

**戻り値:**
float
### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```


言語のIdを返します。読み取り専用 String。

**戻り値:**
java.lang.String
### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```


代替言語のIdを返します。読み取り専用 String。

**戻り値:**
java.lang.String
### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```


文字間隔の増分（ポイント単位）を返します。読み取り専用 float。

**戻り値:**
float