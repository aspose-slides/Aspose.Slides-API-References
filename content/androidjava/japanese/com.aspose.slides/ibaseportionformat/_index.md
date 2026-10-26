---
title: IBasePortionFormat
second_title: Aspose.Slides for Android の Java API リファレンス
description: このクラスはテキスト部分の書式設定プロパティを含みます。
type: docs
url: /ja/com.aspose.slides/ibaseportionformat/
---```
public interface IBasePortionFormat
```

このクラスはテキスト部分の書式設定プロパティを含みます。[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)とは異なり、このクラスのすべてのプロパティは書き込み可能です。

--------------------

このクラスは、特定の部分に定義されたテキスト部分の書式設定プロパティを取得および操作するために使用されます。つまり、値を取得する際に継承は適用されず、ほとんどの場合「未定義」を意味する値が返されます。

継承された値を含む実際の書式設定パラメータ値を取得するには、[IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective) メソッドを使用してください。このメソッドは [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) インスタンスを返します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | テキストのアウトラインに対するLineFormatプロパティを返します。 |
| [getFillFormat()](#getFillFormat--) | テキストのFillFormatプロパティを返します。 |
| [getEffectFormat()](#getEffectFormat--) | テキストのEffectFormatプロパティを返します。 |
| [getHighlightColor()](#getHighlightColor--) | テキストのハイライトに使用される色を返します。 |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | 下線ラインのアウトラインに使用されるLineFormatプロパティを返します。 |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | 下線ラインのFillFormatプロパティを返します。 |
| [getFontBold()](#getFontBold--) | フォントが太字かどうかを判定します。 |
| [setFontBold(byte value)](#setFontBold-byte-) | フォントが太字かどうかを判定します。 |
| [getFontItalic()](#getFontItalic--) | フォントが斜体かどうかを判定します。 |
| [setFontItalic(byte value)](#setFontItalic-byte-) | フォントが斜体かどうかを判定します。 |
| [getKumimoji()](#getKumimoji--) | 数字がテキストの東アジア言語固有の縦書きレイアウトを無視すべきかどうかを判定します。 |
| [setKumimoji(byte value)](#setKumimoji-byte-) | 数字がテキストの東アジア言語固有の縦書きレイアウトを無視すべきかどうかを判定します。 |
| [getNormaliseHeight()](#getNormaliseHeight--) | テキストの高さを正規化すべきかどうかを判定します。 |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | テキストの高さを正規化すべきかどうかを判定します。 |
| [getProofDisabled()](#getProofDisabled--) | テキストが校正されないかどうかを判定します。 |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | テキストが校正されないかどうかを判定します。 |
| [getFontUnderline()](#getFontUnderline--) | テキストの下線タイプを取得または設定します。 |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | テキストの下線タイプを取得または設定します。 |
| [getTextCapType()](#getTextCapType--) | テキストの大文字小文字の種類を取得または設定します。 |
| [setTextCapType(byte value)](#setTextCapType-byte-) | テキストの大文字小文字の種類を取得または設定します。 |
| [getStrikethroughType()](#getStrikethroughType--) | テキストの取り消し線の種類を取得または設定します。 |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | テキストの取り消し線の種類を取得または設定します。 |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | 下線スタイルが独自のLineFormatプロパティを持つか、テキストのLineFormatプロパティから継承するかを判定します。 |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | 下線スタイルが独自のLineFormatプロパティを持つか、テキストのLineFormatプロパティから継承するかを判定します。 |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | 下線スタイルが独自のFillFormatプロパティを持つか、テキストのFillFormatプロパティから継承するかを判定します。 |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | 下線スタイルが独自のFillFormatプロパティを持つか、テキストのFillFormatプロパティから継承するかを判定します。 |
| [getFontHeight()](#getFontHeight--) | 部分のフォントサイズを取得または設定します。 |
| [setFontHeight(float value)](#setFontHeight-float-) | 部分のフォントサイズを取得または設定します。 |
| [getLatinFont()](#getLatinFont--) | ラテンフォント情報を取得または設定します。 |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | ラテンフォント情報を取得または設定します。 |
| [getEastAsianFont()](#getEastAsianFont--) | 東アジアフォント情報を取得または設定します。 |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | 東アジアフォント情報を取得または設定します。 |
| [getComplexScriptFont()](#getComplexScriptFont--) | 複合スクリプトフォント情報を取得または設定します。 |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | 複合スクリプトフォント情報を取得または設定します。 |
| [getSymbolFont()](#getSymbolFont--) | シンボリックフォント情報を取得または設定します。 |
| [setSymbolFont(IFontData value)](#setSymbolFont-com.aspose.slides.IFontData-) | シンボリックフォント情報を取得または設定します。 |
| [getEscapement()](#getEscapement--) | 上付き文字または下付き文字を取得または設定します。 |
| [setEscapement(float value)](#setEscapement-float-) | 上付き文字または下付き文字を取得または設定します。 |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | カーニングを有効にすべき最小フォントサイズを取得または設定します。 |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | カーニングを有効にすべき最小フォントサイズを取得または設定します。 |
| [getLanguageId()](#getLanguageId--) | 校正言語のIDを取得または設定します。 |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | 校正言語のIDを取得または設定します。 |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | 代替言語のIDを取得または設定します。 |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | 代替言語のIDを取得または設定します。 |
| [getSpacing()](#getSpacing--) | 文字間の間隔増分を取得または設定します。 |
| [setSpacing(float value)](#setSpacing-float-) | 文字間の間隔増分を取得または設定します。 |
| [getSpellCheck()](#getSpellCheck--) | テキスト部分のスペルチェックが有効かどうかを取得または設定します。 |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | テキスト部分のスペルチェックが有効かどうかを取得または設定します。 |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```

テキストのアウトラインに対するLineFormatプロパティを返します。継承は適用されません。読み取り専用 [ILineFormat](../../com.aspose.slides/ilineformat)。

**戻り値:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

テキストのFillFormatプロパティを返します。継承は適用されません。読み取り専用 [IFillFormat](../../com.aspose.slides/ifillformat)。

**戻り値:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

テキストのEffectFormatプロパティを返します。継承は適用されません。読み取り専用 [IEffectFormat](../../com.aspose.slides/ieffectformat)。

**戻り値:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getHighlightColor() {#getHighlightColor--}
```
public abstract IColorFormat getHighlightColor()
```

テキストのハイライトに使用される色を返します。継承は適用されません。読み取り専用 [IColorFormat](../../com.aspose.slides/icolorformat)。

**戻り値:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormat getUnderlineLineFormat()
```

下線ラインのアウトラインに使用されるLineFormatプロパティを返します。継承は適用されません。読み取り専用 [ILineFormat](../../com.aspose.slides/ilineformat)。

**戻り値:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormat getUnderlineFillFormat()
```

下線ラインのFillFormatプロパティを返します。継承は適用されません。読み取り専用 [IFillFormat](../../com.aspose.slides/ifillformat)。

**戻り値:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getFontBold() {#getFontBold--}
```
public abstract byte getFontBold()
```

フォントが太字かどうかを判定します。継承は適用されません。読み書き [NullableBool](../../com.aspose.slides/nullablebool)。

**戻り値:**
byte

### setFontBold(byte value) {#setFontBold-byte-}
```
public abstract void setFontBold(byte value)
```

フォントが太字かどうかを判定します。継承は適用されません。読み書き [NullableBool](../../com.aspose.slides/nullablebool)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getFontItalic() {#getFontItalic--}
```
public abstract byte getFontItalic()
```

フォントが斜体かどうかを判定します。継承は適用されません。読み書き [NullableBool](../../com.aspose.slides/nullablebool)。

**戻り値:**
byte

### setFontItalic(byte value) {#setFontItalic-byte-}
```
public abstract void setFontItalic(byte value)
```

フォントが斜体かどうかを判定します。継承は適用されません。読み書き [NullableBool](../../com.aspose.slides/nullablebool)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getKumimoji() {#getKumimoji--}
```
public abstract byte getKumimoji()
```

数字がテキストの東アジア言語固有の縦書きレイアウトを無視すべきかどうかを判定します。継承は適用されません。読み書き [NullableBool](../../com.aspose.slides/nullablebool)。

**戻り値:**
byte

### setKumimoji(byte value) {#setKumimoji-byte-}
```
public abstract void setKumimoji(byte value)
```

数字がテキストの東アジア言語固有の縦書きレイアウトを無視すべきかどうかを判定します。継承は適用されません。読み書き [NullableBool](../../com.aspose.slides/nullablebool)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract byte getNormaliseHeight()
```

テキストの高さを正規化すべきかどうかを判定します。継承は適用されません。読み書き [NullableBool](../../com.aspose.slides/nullablebool)。

**戻り値:**
byte

### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public abstract void setNormaliseHeight(byte value)
```

テキストの高さを正規化すべきかどうかを判定します。継承は適用されません。読み書き [NullableBool](../../com.aspose.slides/nullablebool)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getProofDisabled() {#getProofDisabled--}
```
public abstract byte getProofDisabled()
```

テキストが校正されないかどうかを判定します。継承は適用されません。読み書き [NullableBool](../../com.aspose.slides/nullablebool)。

**戻り値:**
byte

### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public abstract void setProofDisabled(byte value)
```

テキストが校正されないかどうかを判定します。継承は適用されません。読み書き [NullableBool](../../com.aspose.slides/nullablebool)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```

テキストの下線タイプを取得または設定します。継承は適用されません。読み書き [TextUnderlineType](../../com.aspose.slides/textunderlinetype)。

**戻り値:**
byte

### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public abstract void setFontUnderline(byte value)
```

テキストの下線タイプを取得または設定します。継承は適用されません。読み書き [TextUnderlineType](../../com.aspose.slides/textunderlinetype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```

テキストの大文字小文字の種類を取得または設定します。継承は適用されません。読み書き [TextCapType](../../com.aspose.slides/textcaptype)。

**戻り値:**
byte

### setTextCapType(byte value) {#setTextCapType-byte-}
```
public abstract void setTextCapType(byte value)
```

テキストの大文字小文字の種類を取得または設定します。継承は適用されません。読み書き [TextCapType](../../com.aspose.slides/textcaptype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```

テキストの取り消し線の種類を取得または設定します。継承は適用されません。読み書き [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype)。

**戻り値:**
byte

### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public abstract void setStrikethroughType(byte value)
```

テキストの取り消し線の種類を取得または設定します。継承は適用されません。読み書き [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract byte isHardUnderlineLine()
```

下線スタイルが独自のLineFormatプロパティを持つか、テキストのLineFormatプロパティから継承するかを判定します。読み書き [NullableBool](../../com.aspose.slides/nullablebool)。

**戻り値:**
byte

### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public abstract void setHardUnderlineLine(byte value)
```

下線スタイルが独自のLineFormatプロパティを持つか、テキストのLineFormatプロパティから継承するかを判定します。読み書き [NullableBool](../../com.aspose.slides/nullablebool)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract byte isHardUnderlineFill()
```

下線スタイルが独自のFillFormatプロパティを持つか、テキストのFillFormatプロパティから継承するかを判定します。読み書き [NullableBool](../../com.aspose.slides/nullablebool)。

**戻り値:**
byte

### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public abstract void setHardUnderlineFill(byte value)
```

下線スタイルが独自のFillFormatプロパティを持つか、テキストのFillFormatプロパティから継承するかを判定します。読み書き [NullableBool](../../com.aspose.slides/nullablebool)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```

部分のフォントサイズを取得または設定します。**Float.NaN** は高さが未定義であり、マスターから継承されることを意味します。読み書き float。

**戻り値:**
float

### setFontHeight(float value) {#setFontHeight-float-}
```
public abstract void setFontHeight(float value)
```

部分のフォントサイズを取得または設定します。**Float.NaN** は高さが未定義であり、マスターから継承されることを意味します。読み書き float。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

ラテンフォント情報を取得または設定します。Null はフォントが未定義であり、マスターから継承されることを意味します。読み書き [IFontData](../../com.aspose.slides/ifontdata)。

**戻り値:**
[IFontData](../../com.aspose.slides/ifontdata)

### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```

ラテンフォント情報を取得または設定します。Null はフォントが未定義であり、マスターから継承されることを意味します。読み書き [IFontData](../../com.aspose.slides/ifontdata)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

東アジアフォント情報を取得または設定します。Null はフォントが未定義であり、マスターから継承されることを意味します。読み書き [IFontData](../../com.aspose.slides/ifontdata)。

**戻り値:**
[IFontData](../../com.aspose.slides/ifontdata)

### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```

東アジアフォント情報を取得または設定します。Null はフォントが未定義であり、マスターから継承されることを意味します。読み書き [IFontData](../../com.aspose.slides/ifontdata)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

複合スクリプトフォント情報を取得または設定します。Null はフォントが未定義であり、マスターから継承されることを意味します。読み書き [IFontData](../../com.aspose.slides/ifontdata)。

**戻り値:**
[IFontData](../../com.aspose.slides/ifontdata)

### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```

複合スクリプトフォント情報を取得または設定します。Null はフォントが未定義であり、マスターから継承されることを意味します。読み書き [IFontData](../../com.aspose.slides/ifontdata)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```

シンボリックフォント情報を取得または設定します。Null はフォントが未定義であり、マスターから継承されることを意味します。読み書き [IFontData](../../com.aspose.slides/ifontdata)。

**戻り値:**
[IFontData](../../com.aspose.slides/ifontdata)

### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public abstract void setSymbolFont(IFontData value)
```

シンボリックフォント情報を取得または設定します。Null はフォントが未定義であり、マスターから継承されることを意味します。読み書き [IFontData](../../com.aspose.slides/ifontdata)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```

上付き文字または下付き文字を取得または設定します。-100%（下付き）から 100%（上付き）までの値です。**Float.NaN** は値が未定義であり、マスターから継承されることを意味します。読み書き float。

**戻り値:**
float

### setEscapement(float value) {#setEscapement-float-}
```
public abstract void setEscapement(float value)
```

上付き文字または下付き文字を取得または設定します。-100%（下付き）から 100%（上付き）までの値です。**Float.NaN** は値が未定義であり、マスターから継承されることを意味します。読み書き float。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```

カーニングを有効にすべき最小フォントサイズを取得または設定します。**Float.NaN** は値が未定義であり、マスターから継承されることを意味します。読み書き float。

**戻り値:**
float

### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public abstract void setKerningMinimalSize(float value)
```

カーニングを有効にすべき最小フォントサイズを取得または設定します。**Float.NaN** は値が未定義であり、マスターから継承されることを意味します。読み書き float。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```

校正言語のIDを取得または設定します。スペルチェックと文法チェックに使用されます。読み書き String。

**戻り値:**
java.lang.String

### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public abstract void setLanguageId(String value)
```

校正言語のIDを取得または設定します。スペルチェックと文法チェックに使用されます。読み書き String。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```

代替言語のIDを取得または設定します。読み書き String。

**戻り値:**
java.lang.String

### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public abstract void setAlternativeLanguageId(String value)
```

代替言語のIDを取得または設定します。読み書き String。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```

文字間の間隔増分を取得または設定します。**Float.NaN** は値が未定義であり、マスターから継承されることを意味します。読み書き float。

**戻り値:**
float

### setSpacing(float value) {#setSpacing-float-}
```
public abstract void setSpacing(float value)
```

文字間の間隔増分を取得または設定します。**Float.NaN** は値が未定義であり、マスターから継承されることを意味します。読み書き float。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getSpellCheck() {#getSpellCheck--}
```
public abstract boolean getSpellCheck()
```

テキスト部分のスペルチェックが有効かどうかを取得または設定します。このプロパティが false に設定されると、テキスト要素のスペルチェックが抑制されます。true に設定するとスペルチェックが許可されます。デフォルトは false。

--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // 最初のスライドの最初のシェイプ内のテキストの最初の部分にアクセスします
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // このテキスト部分のスペルチェックを有効にします
>      portion.getPortionFormat().setSpellCheck(true);
>      // 修正されたプレゼンテーションを保存します
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

テキスト部分のスペルチェックが有効かどうかを取得または設定します。このプロパティが false に設定されると、テキスト要素のスペルチェックが抑制されます。true に設定するとスペルチェックが許可されます。デフォルトは false。

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

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |