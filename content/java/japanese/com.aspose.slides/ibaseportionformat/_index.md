---
title: IBasePortionFormat
second_title: Aspose.Slides for Java API Reference
description: This class contains the text portion formatting properties.
type: docs
url: /ja/com.aspose.slides/ibaseportionformat/
---```
public interface IBasePortionFormat
```

このクラスはテキスト部分の書式設定プロパティを含みます。[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)とは異なり、このクラスのすべてのプロパティは書き込み可能です。

--------------------

このクラスは、特定の部分に対して定義されたテキスト部分の書式設定プロパティを取得および操作するために使用されます。値を取得する際に継承が適用されないため、ほとんどの場合「未定義」を意味する値が取得されます。

継承されたものも含めた有効な書式パラメータ値を取得するには、[IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective) メソッドを使用する必要があります。このメソッドは [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) インスタンスを返します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | Returns the LineFormat properties for text outlining. |
| [getFillFormat()](#getFillFormat--) | Returns the text FillFormat properties. |
| [getEffectFormat()](#getEffectFormat--) | Returns the text EffectFormat properties. |
| [getHighlightColor()](#getHighlightColor--) | Returns the color used to highlight a text. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | Returns the LineFormat properties used to outline underline line. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | Returns the underline line FillFormat properties. |
| [getFontBold()](#getFontBold--) | Determines whether the font is bold. |
| [setFontBold(byte value)](#setFontBold-byte-) | Determines whether the font is bold. |
| [getFontItalic()](#getFontItalic--) | Determines whether the font is itallic. |
| [setFontItalic(byte value)](#setFontItalic-byte-) | Determines whether the font is itallic. |
| [getKumimoji()](#getKumimoji--) | Determines whether the numbers should ignore text eastern language-specific vertical text layout. |
| [setKumimoji(byte value)](#setKumimoji-byte-) | Determines whether the numbers should ignore text eastern language-specific vertical text layout. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Determines whether the height of a text should be normalized. |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | Determines whether the height of a text should be normalized. |
| [getProofDisabled()](#getProofDisabled--) | Determines whether the text shouldn't be proofed. |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | Determines whether the text shouldn't be proofed. |
| [getFontUnderline()](#getFontUnderline--) | Returns or sets the text underline type. |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | Returns or sets the text underline type. |
| [getTextCapType()](#getTextCapType--) | Returns or sets the type of text capitalization. |
| [setTextCapType(byte value)](#setTextCapType-byte-) | Returns or sets the type of text capitalization. |
| [getStrikethroughType()](#getStrikethroughType--) | Returns or sets the strikethrough type of a text. |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | Returns or sets the strikethrough type of a text. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Determines whether the underline style has own LineFormat properties or inherits it from the LineFormat properties of the text. |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | Determines whether the underline style has own LineFormat properties or inherits it from the LineFormat properties of the text. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Determines whether the underline style has own FillFormat properties or inherits it from the FillFormat properties of the text. |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | Determines whether the underline style has own FillFormat properties or inherits it from the FillFormat properties of the text. |
| [getFontHeight()](#getFontHeight--) | Returns or sets the font height of a portion. |
| [setFontHeight(float value)](#setFontHeight-float-) | Returns or sets the font height of a portion. |
| [getLatinFont()](#getLatinFont--) | Returns or sets the Latin font info. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Returns or sets the Latin font info. |
| [getEastAsianFont()](#getEastAsianFont--) | Returns or sets the East Asian font info. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Returns or sets the East Asian font info. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Returns or sets the complex script font info. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Returns or sets the complex script font info. |
| [getSymbolFont()](#getSymbolFont--) | Returns or sets the symbolic font info. |
| [setSymbolFont(IFontData value)](#setSymbolFont-com.aspose.slides.IFontData-) | Returns or sets the symbolic font info. |
| [getEscapement()](#getEscapement--) | Returns or sets the superscript or subscript text. |
| [setEscapement(float value)](#setEscapement-float-) | Returns or sets the superscript or subscript text. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | Returns or sets the minimal font size, for which kerning should be switched on. |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | Returns or sets the minimal font size, for which kerning should be switched on. |
| [getLanguageId()](#getLanguageId--) | Returns or sets the Id of a proofing language. |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | Returns or sets the Id of a proofing language. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | Returns or sets the Id of an alternative language. |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | Returns or sets the Id of an alternative language. |
| [getSpacing()](#getSpacing--) | Returns or sets the intercharacter spacing increment. |
| [setSpacing(float value)](#setSpacing-float-) | Returns or sets the intercharacter spacing increment. |
| [getSpellCheck()](#getSpellCheck--) | Gets or sets a value indicating whether spell checking is enabled for the text portion. |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | Gets or sets a value indicating whether spell checking is enabled for the text portion. |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```

テキストのアウトライン用の LineFormat プロパティを取得します。継承は適用されません。読み取り専用 [ILineFormat](../../com.aspose.slides/ilineformat)。

**戻り値:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

テキストの FillFormat プロパティを取得します。継承は適用されません。読み取り専用 [IFillFormat](../../com.aspose.slides/ifillformat)。

**戻り値:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

テキストの EffectFormat プロパティを取得します。継承は適用されません。読み取り専用 [IEffectFormat](../../com.aspose.slides/ieffectformat)。

**戻り値:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getHighlightColor() {#getHighlightColor--}
```
public abstract IColorFormat getHighlightColor()
```

テキストの強調表示に使用される色を取得します。継承は適用されません。読み取り専用 [IColorFormat](../../com.aspose.slides/icolorformat)。

**戻り値:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormat getUnderlineLineFormat()
```

下線線のアウトラインに使用される LineFormat プロパティを取得します。継承は適用されません。読み取り専用 [ILineFormat](../../com.aspose.slides/ilineformat)。

**戻り値:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormat getUnderlineFillFormat()
```

下線線の FillFormat プロパティを取得します。継承は適用されません。読み取り専用 [IFillFormat](../../com.aspose.slides/ifillformat)。

**戻り値:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getFontBold() {#getFontBold--}
```
public abstract byte getFontBold()
```

フォントが太字かどうかを判定します。継承は適用されません。読み書き可能 [NullableBool](../../com.aspose.slides/nullablebool)。

**戻り値:**
byte

### setFontBold(byte value) {#setFontBold-byte-}
```
public abstract void setFontBold(byte value)
```

フォントが太字かどうかを設定します。継承は適用されません。読み書き可能 [NullableBool](../../com.aspose.slides/nullablebool)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getFontItalic() {#getFontItalic--}
```
public abstract byte getFontItalic()
```

フォントがイタリックかどうかを判定します。継承は適用されません。読み書き可能 [NullableBool](../../com.aspose.slides/nullablebool)。

**戻り値:**
byte

### setFontItalic(byte value) {#setFontItalic-byte-}
```
public abstract void setFontItalic(byte value)
```

フォントがイタリックかどうかを設定します。継承は適用されません。読み書き可能 [NullableBool](../../com.aspose.slides/nullablebool)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getKumimoji() {#getKumimoji--}
```
public abstract byte getKumimoji()
```

数字がテキストの東アジア言語固有の縦書きレイアウトを無視すべきかどうかを判定します。継承は適用されません。読み書き可能 [NullableBool](../../com.aspose.slides/nullablebool)。

**戻り値:**
byte

### setKumimoji(byte value) {#setKumimoji-byte-}
```
public abstract void setKumimoji(byte value)
```

数字がテキストの東アジア言語固有の縦書きレイアウトを無視すべきかどうかを設定します。継承は適用されません。読み書き可能 [NullableBool](../../com.aspose.slides/nullablebool)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract byte getNormaliseHeight()
```

テキストの高さを正規化すべきかどうかを判定します。継承は適用されません。読み書き可能 [NullableBool](../../com.aspose.slides/nullablebool)。

**戻り値:**
byte

### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public abstract void setNormaliseHeight(byte value)
```

テキストの高さを正規化すべきかどうかを設定します。継承は適用されません。読み書き可能 [NullableBool](../../com.aspose.slides/nullablebool)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getProofDisabled() {#getProofDisabled--}
```
public abstract byte getProofDisabled()
```

テキストが校正対象でないかどうかを判定します。継承は適用されません。読み書き可能 [NullableBool](../../com.aspose.slides/nullablebool)。

**戻り値:**
byte

### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public abstract void setProofDisabled(byte value)
```

テキストが校正対象でないかどうかを設定します。継承は適用されません。読み書き可能 [NullableBool](../../com.aspose.slides/nullablebool)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```

テキストの下線タイプを取得または設定します。継承は適用されません。読み書き可能 [TextUnderlineType](../../com.aspose.slides/textunderlinetype)。

**戻り値:**
byte

### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public abstract void setFontUnderline(byte value)
```

テキストの下線タイプを取得または設定します。継承は適用されません。読み書き可能 [TextUnderlineType](../../com.aspose.slides/textunderlinetype)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```

テキストの大文字化タイプを取得または設定します。継承は適用されません。読み書き可能 [TextCapType](../../com.aspose.slides/textcaptype)。

**戻り値:**
byte

### setTextCapType(byte value) {#setTextCapType-byte-}
```
public abstract void setTextCapType(byte value)
```

テキストの大文字化タイプを取得または設定します。継承は適用されません。読み書き可能 [TextCapType](../../com.aspose.slides/textcaptype)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```

テキストの取り消し線タイプを取得または設定します。継承は適用されません。読み書き可能 [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype)。

**戻り値:**
byte

### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public abstract void setStrikethroughType(byte value)
```

テキストの取り消し線タイプを取得または設定します。継承は適用されません。読み書き可能 [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract byte isHardUnderlineLine()
```

下線スタイルが独自の LineFormat プロパティを持つか、テキストの LineFormat プロパティから継承するかを判定します。読み書き可能 [NullableBool](../../com.aspose.slides/nullablebool)。

**戻り値:**
byte

### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public abstract void setHardUnderlineLine(byte value)
```

下線スタイルが独自の LineFormat プロパティを持つか、テキストの LineFormat プロパティから継承するかを設定します。読み書き可能 [NullableBool](../../com.aspose.slides/nullablebool)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract byte isHardUnderlineFill()
```

下線スタイルが独自の FillFormat プロパティを持つか、テキストの FillFormat プロパティから継承するかを判定します。読み書き可能 [NullableBool](../../com.aspose.slides/nullablebool)。

**戻り値:**
byte

### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public abstract void setHardUnderlineFill(byte value)
```

下線スタイルが独自の FillFormat プロパティを持つか、テキストの FillFormat プロパティから継承するかを設定します。読み書き可能 [NullableBool](../../com.aspose.slides/nullablebool)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```

テキスト部分のフォント高さを取得または設定します。**Float.NaN** は高さが未定義であり、マスターから継承されることを意味します。読み書き可能 float。

**戻り値:**
float

### setFontHeight(float value) {#setFontHeight-float-}
```
public abstract void setFontHeight(float value)
```

テキスト部分のフォント高さを取得または設定します。**Float.NaN** は高さが未定義であり、マスターから継承されることを意味します。読み書き可能 float。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

ラテン文字フォント情報を取得または設定します。null はフォントが未定義であり、マスターから継承されることを意味します。読み書き可能 [IFontData](../../com.aspose.slides/ifontdata)。

**戻り値:**
[IFontData](../../com.aspose.slides/ifontdata)

### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```

ラテン文字フォント情報を取得または設定します。null はフォントが未定義であり、マスターから継承されることを意味します。読み書き可能 [IFontData](../../com.aspose.slides/ifontdata)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

東アジアフォント情報を取得または設定します。null はフォントが未定義であり、マスターから継承されることを意味します。読み書き可能 [IFontData](../../com.aspose.slides/ifontdata)。

**戻り値:**
[IFontData](../../com.aspose.slides/ifontdata)

### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```

東アジアフォント情報を取得または設定します。null はフォントが未定義であり、マスターから継承されることを意味します。読み書き可能 [IFontData](../../com.aspose.slides/ifontdata)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

複合文字スクリプトフォント情報を取得または設定します。null はフォントが未定義であり、マスターから継承されることを意味します。読み書き可能 [IFontData](../../com.aspose.slides/ifontdata)。

**戻り値:**
[IFontData](../../com.aspose.slides/ifontdata)

### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```

複合文字スクリプトフォント情報を取得または設定します。null はフォントが未定義であり、マスターから継承されることを意味します。読み書き可能 [IFontData](../../com.aspose.slides/ifontdata)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```

シンボリックフォント情報を取得または設定します。null はフォントが未定義であり、マスターから継承されることを意味します。読み書き可能 [IFontData](../../com.aspose.slides/ifontdata)。

**戻り値:**
[IFontData](../../com.aspose.slides/ifontdata)

### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public abstract void setSymbolFont(IFontData value)
```

シンボリックフォント情報を取得または設定します。null はフォントが未定義であり、マスターから継承されることを意味します。読み書き可能 [IFontData](../../com.aspose.slides/ifontdata)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```

上付きまたは下付きテキストを取得または設定します。値は -100%（下付き）から 100%（上付き）までです。**Float.NaN** は値が未定義であり、マスターから継承されることを意味します。読み書き可能 float。

**戻り値:**
float

### setEscapement(float value) {#setEscapement-float-}
```
public abstract void setEscapement(float value)
```

上付きまたは下付きテキストを取得または設定します。値は -100%（下付き）から 100%（上付き）までです。**Float.NaN** は値が未定義であり、マスターから継承されることを意味します。読み書き可能 float。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```

カーニングが有効になる最小フォントサイズを取得または設定します。**Float.NaN** は値が未定義であり、マスターから継承されることを意味します。読み書き可能 float。

**戻り値:**
float

### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public abstract void setKerningMinimalSize(float value)
```

カーニングが有効になる最小フォントサイズを取得または設定します。**Float.NaN** は値が未定義であり、マスターから継承されることを意味します。読み書き可能 float。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```

校正言語の Id を取得または設定します。スペルチェックおよび文法チェックに使用されます。読み書き可能 String。

**戻り値:**
java.lang.String

### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public abstract void setLanguageId(String value)
```

校正言語の Id を取得または設定します。スペルチェックおよび文法チェックに使用されます。読み書き可能 String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```

代替言語の Id を取得または設定します。読み書き可能 String。

**戻り値:**
java.lang.String

### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public abstract void setAlternativeLanguageId(String value)
```

代替言語の Id を取得または設定します。読み書き可能 String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```

文字間隔の増分を取得または設定します。**Float.NaN** は値が未定義であり、マスターから継承されることを意味します。読み書き可能 float。

**戻り値:**
float

### setSpacing(float value) {#setSpacing-float-}
```
public abstract void setSpacing(float value)
```

文字間隔の増分を取得または設定します。**Float.NaN** は値が未定義であり、マスターから継承されることを意味します。読み書き可能 float。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getSpellCheck() {#getSpellCheck--}
```
public abstract boolean getSpellCheck()
```

テキスト部分に対してスペルチェックが有効かどうかの値を取得または設定します。false に設定するとテキスト要素のスペルチェックが抑制され、true に設定するとスペルチェックが許可されます。デフォルトは false です。

--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // Access the first portion of text inside the first shape on the first slide
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Enable spell checking for this text portion
>      portion.getPortionFormat().setSpellCheck(true);
>      // Save the modified presentation
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**戻り値:**
boolean

### setSpellCheck(boolean value) {#setSpellCheck-boolean-}
```
public abstract void setSpellCheck(boolean value)
```

テキスト部分に対してスペルチェックが有効かどうかの値を取得または設定します。false に設定するとテキスト要素のスペルチェックが抑制され、true に設定するとスペルチェックが許可されます。デフォルトは false です。

--------------------

> ```
> 次の例は、プレゼンテーションを保存する前に SpellCheck フラグを有効にする方法を示しています:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // 最初のスライドの最初のシェイプ内の最初のテキスト部分にアクセスします
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // このテキスト部分のスペルチェックを有効にします
>      portion.getPortionFormat().setSpellCheck(true);
>      // 変更されたプレゼンテーションを保存します
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |