---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Slides for Android via Java API リファレンス
description: 有効なテキスト部分書式プロパティを含む不変オブジェクトのベースインターフェイスです。
type: docs
url: /ja/com.aspose.slides/ibaseportionformateffectivedata/
---```
public interface IBasePortionFormatEffectiveData
```

有効なテキスト部分書式プロパティを含む不変オブジェクトのベースインターフェイスです。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | テキストのアウトライン設定のための LineFormat プロパティを返します。 |
| [getFillFormat()](#getFillFormat--) | テキストの FillFormat プロパティを返します。 |
| [getEffectFormat()](#getEffectFormat--) | テキストの EffectFormat プロパティを返します。 |
| [getHighlightColor()](#getHighlightColor--) | テキストのハイライトに使用される色を返します。 |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | 下線線をアウトラインするために使用される LineFormat プロパティを返します。 |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | 下線線の FillFormat プロパティを返します。 |
| [getFontBold()](#getFontBold--) | フォントが太字かどうかを判定します。 |
| [getFontItalic()](#getFontItalic--) | フォントがイタリックかどうかを判定します。 |
| [getKumimoji()](#getKumimoji--) | 数字がテキストの東アジア言語固有の縦書きレイアウトを無視すべきかどうかを判定します。 |
| [getNormaliseHeight()](#getNormaliseHeight--) | テキストの高さを正規化すべきかどうかを判定します。 |
| [getProofDisabled()](#getProofDisabled--) | テキストが校正されないかどうかを判定します。 |
| [getFontUnderline()](#getFontUnderline--) | テキストの下線タイプを返します。 |
| [getTextCapType()](#getTextCapType--) | テキストの大文字化タイプを返します。 |
| [getStrikethroughType()](#getStrikethroughType--) | テキストの取り消し線タイプを返します。 |
| [getSmartTagClean()](#getSmartTagClean--) | スマートタグをクリアすべきかどうかを判定します。 |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | 下線スタイルが独自の LineFormat プロパティを持つか、テキストの LineFormat プロパティから継承するかを判定します。 |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | 下線スタイルが独自の FillFormat プロパティを持つか、テキストの FillFormat プロパティから継承するかを判定します。 |
| [getFontHeight()](#getFontHeight--) | テキスト部分のフォント高さをポイント単位で返します。 |
| [getLatinFont()](#getLatinFont--) | ラテンフォント情報を返します。 |
| [getEastAsianFont()](#getEastAsianFont--) | 東アジアフォント情報を返します。 |
| [getComplexScriptFont()](#getComplexScriptFont--) | 複雑スクリプトフォント情報を返します。 |
| [getSymbolFont()](#getSymbolFont--) | シンボリックフォント情報を返します。 |
| [getEscapement()](#getEscapement--) | 上付きまたは下付きテキストを返します。 |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | カーニングを有効にすべき最小フォントサイズを返します。 |
| [getLanguageId()](#getLanguageId--) | 言語の Id を返します。 |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | 代替言語の Id を返します。 |
| [getSpacing()](#getSpacing--) | 文字間隔増分をポイント単位で返します。 |
### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormatEffectiveData getLineFormat()
```

テキストのアウトライン設定のための LineFormat プロパティを返します。読み取り専用 [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)。

**戻り値:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```

テキストの FillFormat プロパティを返します。読み取り専用 [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)。

**戻り値:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormatEffectiveData getEffectFormat()
```

テキストの EffectFormat プロパティを返します。読み取り専用 [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata)。

**戻り値:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata)
### getHighlightColor() {#getHighlightColor--}
```
public abstract Integer getHighlightColor()
```

テキストのハイライトに使用される色を返します。読み取り専用 java.lang.Integer。

**戻り値:**
java.lang.Integer
### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormatEffectiveData getUnderlineLineFormat()
```

下線線をアウトラインするために使用される LineFormat プロパティを返します。読み取り専用 [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)。

**戻り値:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)
### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormatEffectiveData getUnderlineFillFormat()
```

下線線の FillFormat プロパティを返します。読み取り専用 [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)。

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

フォントがイタリックかどうかを判定します。読み取り専用 boolean。

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

テキストが校正されないかどうかを判定します。読み取り専用 boolean。

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

スマートタグをクリアすべきかどうかを判定します。読み取り専用 boolean。

**戻り値:**
boolean
### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract boolean isHardUnderlineLine()
```

下線スタイルが独自の LineFormat プロパティを持つか、テキストの LineFormat プロパティから継承するかを判定します。読み取り専用 boolean。

**戻り値:**
boolean
### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract boolean isHardUnderlineFill()
```

下線スタイルが独自の FillFormat プロパティを持つか、テキストの FillFormat プロパティから継承するかを判定します。読み取り専用 boolean。

**戻り値:**
boolean
### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```

テキスト部分のフォント高さをポイント単位で返します。読み取り専用 float。

**戻り値:**
float
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

ラテンフォント情報を返します。読み取り専用 [IFontData](../../com.aspose.slides/ifontdata)。

**戻り値:**
[IFontData](../../com.aspose.slides/ifontdata)
### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

東アジアフォント情報を返します。読み取り専用 [IFontData](../../com.aspose.slides/ifontdata)。

**戻り値:**
[IFontData](../../com.aspose.slides/ifontdata)
### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

複雑スクリプトフォント情報を返します。読み取り専用 [IFontData](../../com.aspose.slides/ifontdata)。

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

上付きまたは下付きテキストを返します。範囲は -100%（下付き）から 100%（上付き）です。読み取り専用 float。

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

言語の Id を返します。読み取り専用 String。

**戻り値:**
java.lang.String
### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```

代替言語の Id を返します。読み取り専用 String。

**戻り値:**
java.lang.String
### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```

文字間隔増分をポイント単位で返します。読み取り専用 float。

**戻り値:**
float