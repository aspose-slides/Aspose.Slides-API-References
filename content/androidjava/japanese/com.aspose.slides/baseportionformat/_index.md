---
title: BasePortionFormat
second_title: Java API リファレンスを介した Android 用 Aspose.Slides
description: テキスト部分の共通書式プロパティです。
type: docs
url: /ja/com.aspose.slides/baseportionformat/
---
**継承:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat)
```
public abstract class BasePortionFormat extends PVIObject implements IBasePortionFormat
```

テキスト部分の共通書式プロパティです。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getLineFormat()](#getLineFormat--) | テキストのアウトライン用のLineFormatプロパティを取得します。 |
| [getFillFormat()](#getFillFormat--) | テキストのFillFormatプロパティを取得します。 |
| [getEffectFormat()](#getEffectFormat--) | テキストのEffectFormatプロパティを取得します。 |
| [getHighlightColor()](#getHighlightColor--) | テキストのハイライトに使用される色を取得します。 |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | 下線線のアウトラインに使用されるLineFormatプロパティを取得します。 |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | 下線線のFillFormatプロパティを取得します。 |
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
| [getFontUnderline()](#getFontUnderline--) | テキスト下線タイプを取得または設定します。 |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | テキスト下線タイプを取得または設定します。 |
| [getTextCapType()](#getTextCapType--) | テキストの大文字化タイプを取得または設定します。 |
| [setTextCapType(byte value)](#setTextCapType-byte-) | テキストの大文字化タイプを取得または設定します。 |
| [getStrikethroughType()](#getStrikethroughType--) | テキストの取り消し線タイプを取得または設定します。 |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | テキストの取り消し線タイプを取得または設定します。 |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | 下線スタイルが独自のLineFormatプロパティを持つか、テキストのLineFormatプロパティから継承するかを判定します。 |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | 下線スタイルが独自のLineFormatプロパティを持つか、テキストのLineFormatプロパティから継承するかを判定します。 |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | 下線スタイルが独自のFillFormatプロパティを持つか、テキストのFillFormatプロパティから継承するかを判定します。 |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | 下線スタイルが独自のFillFormatプロパティを持つか、テキストのFillFormatプロパティから継承するかを判定します。 |
| [getFontHeight()](#getFontHeight--) | テキスト部分のフォントサイズを取得または設定します。 |
| [setFontHeight(float value)](#setFontHeight-float-) | テキスト部分のフォントサイズを取得または設定します。 |
| [getLatinFont()](#getLatinFont--) | ラテンフォント情報を取得または設定します。 |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | ラテンフォント情報を取得または設定します。 |
| [getEastAsianFont()](#getEastAsianFont--) | 東アジアフォント情報を取得または設定します。 |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | 東アジアフォント情報を取得または設定します。 |
| [getComplexScriptFont()](#getComplexScriptFont--) | 複合スクリプトフォント情報を取得または設定します。 |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | 複合スクリプトフォント情報を取得または設定します。 |
| [getSymbolFont()](#getSymbolFont--) | シンボリックフォント情報を取得または設定します。 |
| [setSymbolFont(IFontData value)](#setSymbolFont-com.aspose.slides.IFontData-) | シンボリックフォント情報を取得または設定します。 |
| [getEscapement()](#getEscapement--) | 上付きまたは下付きテキストを取得または設定します。 |
| [setEscapement(float value)](#setEscapement-float-) | 上付きまたは下付きテキストを取得または設定します。 |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | カーニングがオンになる最小フォントサイズを取得または設定します。 |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | カーニングがオンになる最小フォントサイズを取得または設定します。 |
| [getLanguageId()](#getLanguageId--) | 校正言語のIDを取得または設定します。 |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | 校正言語のIDを取得または設定します。 |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | 代替言語のIDを取得または設定します。 |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | 代替言語のIDを取得または設定します。 |
| [getSpacing()](#getSpacing--) | 文字間スペース増分を取得または設定します。 |
| [setSpacing(float value)](#setSpacing-float-) | 文字間スペース増分を取得または設定します。 |
| [getSpellCheck()](#getSpellCheck--) | テキスト部分でスペルチェックが有効かどうかを取得または設定します。 |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | テキスト部分でスペルチェックが有効かどうかを取得または設定します。 |

### getVersion() {#getVersion--}
```
public long getVersion()
```

バージョン。読み取り専用 long。

**戻り値:**
long

### getLineFormat() {#getLineFormat--}
```
public final ILineFormat getLineFormat()
```

テキストのアウトライン用のLineFormatプロパティを取得します。継承は適用されません。読み取り専用 [ILineFormat](../../com.aspose.slides/ilineformat)。

**戻り値:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

テキストのFillFormatプロパティを取得します。継承は適用されません。読み取り専用 [IFillFormat](../../com.aspose.slides/ifillformat)。

**戻り値:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getEffectFormat() {#getEffectFormat--}
```
public final IEffectFormat getEffectFormat()
```

テキストのEffectFormatプロパティを取得します。継承は適用されません。読み取り専用 [IEffectFormat](../../com.aspose.slides/ieffectformat)。

**戻り値:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getHighlightColor() {#getHighlightColor--}
```
public final IColorFormat getHighlightColor()
```

テキストのハイライトに使用される色を取得します。継承は適用されません。読み取り専用 [IColorFormat](../../com.aspose.slides/icolorformat)。

**戻り値:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public final ILineFormat getUnderlineLineFormat()
```

下線線のアウトラインに使用されるLineFormatプロパティを取得します。継承は適用されません。読み取り専用 [ILineFormat](../../com.aspose.slides/ilineformat)。

**戻り値:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public final IFillFormat getUnderlineFillFormat()
```

下線線のFillFormatプロパティを取得します。継承は適用されません。読み取り専用 [IFillFormat](../../com.aspose.slides/ifillformat)。

**戻り値:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getFontBold() {#getFontBold--}
```
public final byte getFontBold()
```

フォントが太字かどうかを判定します。継承は適用されません。読み書き可能 [NullableBool](../../com.aspose.slides/nullablebool)。

**戻り値:**
byte

### setFontBold(byte value) {#setFontBold-byte-}
```
public final void setFontBold(byte value)
```

フォントが太字かどうかを判定します。継承は適用されません。読み書き可能 [NullableBool](../../com.aspose.slides/nullablebool)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getFontItalic() {#getFontItalic--}
```
public final byte getFontItalic()
```

フォントが斜体かどうかを判定します。継承は適用されません。読み書き可能 [NullableBool](../../com.aspose.slides/nullablebool)。

**戻り値:**
byte

### setFontItalic(byte value) {#setFontItalic-byte-}
```
public final void setFontItalic(byte value)
```

フォントが斜体かどうかを判定します。継承は適用されません。読み書き可能 [NullableBool](../../com.aspose.slides/nullablebool)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getKumimoji() {#getKumimoji--}
```
public final byte getKumimoji()
```

数字がテキストの東アジア言語固有の縦書きレイアウトを無視すべきかどうかを判定します。継承は適用されません。読み書き可能 [NullableBool](../../com.aspose.slides/nullablebool)。

**戻り値:**
byte

### setKumimoji(byte value) {#setKumimoji-byte-}
```
public final void setKumimoji(byte value)
```

数字がテキストの東アジア言語固有の縦書きレイアウトを無視すべきかどうかを判定します。継承は適用されません。読み書き可能 [NullableBool](../../com.aspose.slides/nullablebool)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getNormaliseHeight() {#getNormaliseHeight--}
```
public final byte getNormaliseHeight()
```

テキストの高さを正規化すべきかどうかを判定します。継承は適用されません。読み書き可能 [NullableBool](../../com.aspose.slides/nullablebool)。

**戻り値:**
byte

### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public final void setNormaliseHeight(byte value)
```

テキストの高さを正規化すべきかどうかを判定します。継承は適用されません。読み書き可能 [NullableBool](../../com.aspose.slides/nullablebool)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getProofDisabled() {#getProofDisabled--}
```
public final byte getProofDisabled()
```

テキストが校正されないかどうかを判定します。継承は適用されません。読み書き可能 [NullableBool](../../com.aspose.slides/nullablebool)。

**戻り値:**
byte

### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public final void setProofDisabled(byte value)
```

テキストが校正されないかどうかを判定します。継承は適用されません。読み書き可能 [NullableBool](../../com.aspose.slides/nullablebool)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getFontUnderline() {#getFontUnderline--}
```
public final byte getFontUnderline()
```

テキスト下線タイプを取得または設定します。継承は適用されません。読み書き可能 [TextUnderlineType](../../com.aspose.slides/textunderlinetype)。

**戻り値:**
byte

### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public final void setFontUnderline(byte value)
```

テキスト下線タイプを取得または設定します。継承は適用されません。読み書き可能 [TextUnderlineType](../../com.aspose.slides/textunderlinetype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getTextCapType() {#getTextCapType--}
```
public final byte getTextCapType()
```

テキストの大文字化タイプを取得または設定します。継承は適用されません。読み書き可能 [TextCapType](../../com.aspose.slides/textcaptype)。

**戻り値:**
byte

### setTextCapType(byte value) {#setTextCapType-byte-}
```
public final void setTextCapType(byte value)
```

テキストの大文字化タイプを取得または設定します。継承は適用されません。読み書き可能 [TextCapType](../../com.aspose.slides/textcaptype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getStrikethroughType() {#getStrikethroughType--}
```
public final byte getStrikethroughType()
```

テキストの取り消し線タイプを取得または設定します。継承は適用されません。読み書き可能 [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype)。

**戻り値:**
byte

### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public final void setStrikethroughType(byte value)
```

テキストの取り消し線タイプを取得または設定します。継承は適用されません。読み書き可能 [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public final byte isHardUnderlineLine()
```

下線スタイルが独自のLineFormatプロパティを持つか、テキストのLineFormatプロパティから継承するかを判定します。読み書き可能 [NullableBool](../../com.aspose.slides/nullablebool)。

**戻り値:**
byte

### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public final void setHardUnderlineLine(byte value)
```

下線スタイルが独自のLineFormatプロパティを持つか、テキストのLineFormatプロパティから継承するかを判定します。読み書き可能 [NullableBool](../../com.aspose.slides/nullablebool)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public final byte isHardUnderlineFill()
```

下線スタイルが独自のFillFormatプロパティを持つか、テキストのFillFormatプロパティから継承するかを判定します。読み書き可能 [NullableBool](../../com.aspose.slides/nullablebool)。

**戻り値:**
byte

### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public final void setHardUnderlineFill(byte value)
```

下線スタイルが独自のFillFormatプロパティを持つか、テキストのFillFormatプロパティから継承するかを判定します。読み書き可能 [NullableBool](../../com.aspose.slides/nullablebool)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getFontHeight() {#getFontHeight--}
```
public final float getFontHeight()
```

テキスト部分のフォントサイズを取得または設定します。**Float.NaN** はサイズが未定義であり、マスターから継承されることを意味します。読み書き可能 float 。

**戻り値:**
float

### setFontHeight(float value) {#setFontHeight-float-}
```
public final void setFontHeight(float value)
```

テキスト部分のフォントサイズを取得または設定します。**Float.NaN** はサイズが未定義であり、マスターから継承されることを意味します。読み書き可能 float 。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getLatinFont() {#getLatinFont--}
```
public final IFontData getLatinFont()
```

ラテンフォント情報を取得または設定します。null はフォントが未定義であり、マスターから継承されることを意味します。読み書き可能 [IFontData](../../com.aspose.slides/ifontdata)。

**戻り値:**
[IFontData](../../com.aspose.slides/ifontdata)

### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public final void setLatinFont(IFontData value)
```

ラテンフォント情報を取得または設定します。null はフォントが未定義であり、マスターから継承されることを意味します。読み書き可能 [IFontData](../../com.aspose.slides/ifontdata)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public final IFontData getEastAsianFont()
```

東アジアフォント情報を取得または設定します。null はフォントが未定義であり、マスターから継承されることを意味します。読み書き可能 [IFontData](../../com.aspose.slides/ifontdata)。

**戻り値:**
[IFontData](../../com.aspose.slides/ifontdata)

### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```

東アジアフォント情報を取得または設定します。null はフォントが未定義であり、マスターから継承されることを意味します。読み書き可能 [IFontData](../../com.aspose.slides/ifontdata)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public final IFontData getComplexScriptFont()
```

複合スクリプトフォント情報を取得または設定します。null はフォントが未定義であり、マスターから継承されることを意味します。読み書き可能 [IFontData](../../com.aspose.slides/ifontdata)。

**戻り値:**
[IFontData](../../com.aspose.slides/ifontdata)

### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```

複合スクリプトフォント情報を取得または設定します。null はフォントが未定義であり、マスターから継承されることを意味します。読み書き可能 [IFontData](../../com.aspose.slides/ifontdata)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getSymbolFont() {#getSymbolFont--}
```
public final IFontData getSymbolFont()
```

シンボリックフォント情報を取得または設定します。null はフォントが未定義であり、マスターから継承されることを意味します。読み書き可能 [IFontData](../../com.aspose.slides/ifontdata)。

**戻り値:**
[IFontData](../../com.aspose.slides/ifontdata)

### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public final void setSymbolFont(IFontData value)
```

シンボリックフォント情報を取得または設定します。null はフォントが未定義であり、マスターから継承されることを意味します。読み書き可能 [IFontData](../../com.aspose.slides/ifontdata)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEscapement() {#getEscapement--}
```
public final float getEscapement()
```

上付きまたは下付きテキストを取得または設定します。-100%（下付き）から 100%（上付き）までの値です。**Float.NaN** は値が未定義であり、マスターから継承されることを意味します。読み書き可能 float 。

**戻り値:**
float

### setEscapement(float value) {#setEscapement-float-}
```
public final void setEscapement(float value)
```

上付きまたは下付きテキストを取得または設定します。-100%（下付き）から 100%（上付き）までの値です。**Float.NaN** は値が未定義であり、マスターから継承されることを意味します。読み書き可能 float 。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public final float getKerningMinimalSize()
```

カーニングがオンになる最小フォントサイズを取得または設定します。**Float.NaN** は値が未定義であり、マスターから継承されることを意味します。読み書き可能 float 。

**戻り値:**
float

### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public final void setKerningMinimalSize(float value)
```

カーニングがオンになる最小フォントサイズを取得または設定します。**Float.NaN** は値が未定義であり、マスターから継承されることを意味します。読み書き可能 float 。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getLanguageId() {#getLanguageId--}
```
public final String getLanguageId()
```

校正言語のIDを取得または設定します。スペルチェックと文法チェックに使用されます。読み書き可能 String。

**戻り値:**
java.lang.String

### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public final void setLanguageId(String value)
```

校正言語のIDを取得または設定します。スペルチェックと文法チェックに使用されます。読み書き可能 String。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public final String getAlternativeLanguageId()
```

代替言語のIDを取得または設定します。読み書き可能 String。

**戻り値:**
java.lang.String

### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public final void setAlternativeLanguageId(String value)
```

代替言語のIDを取得または設定します。読み書き可能 String。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getSpacing() {#getSpacing--}
```
public final float getSpacing()
```

文字間スペース増分を取得または設定します。**Float.NaN** は値が未定義であり、マスターから継承されることを意味します。読み書き可能 float 。

**戻り値:**
float

### setSpacing(float value) {#setSpacing-float-}
```
public final void setSpacing(float value)
```

文字間スペース増分を取得または設定します。**Float.NaN** は値が未定義であり、マスターから継承されることを意味します。読み書き可能 float 。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getSpellCheck() {#getSpellCheck--}
```
public final boolean getSpellCheck()
```

テキスト部分でスペルチェックが有効かどうかを取得または設定します。false に設定するとテキスト要素のスペルチェックが抑制されます。true に設定するとスペルチェックが許可されます。デフォルト値は false です。

**戻り値:**
boolean

### setSpellCheck(boolean value) {#setSpellCheck-boolean-}
```
public final void setSpellCheck(boolean value)
```

テキスト部分でスペルチェックが有効かどうかを取得または設定します。false に設定するとテキスト要素のスペルチェックが抑制されます。true に設定するとスペルチェックが許可されます。デフォルト値は false です。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

```markdown
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
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


**戻り値:**
boolean

```markdown
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


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |