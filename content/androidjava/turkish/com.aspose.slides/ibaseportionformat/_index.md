---
title: IBasePortionFormat
second_title: Aspose.Slides for Android via Java API Reference
description: This class contains the text portion formatting properties.
type: docs
url: /tr/com.aspose.slides/ibaseportionformat/
---```
public interface IBasePortionFormat
```

Bu sınıf, metin bölümü biçimlendirme özelliklerini içerir. [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)'in aksine, bu sınıfın tüm özellikleri yazılabilir.

--------------------

Bu sınıf, belirli bölüm için tanımlanan metin bölümü biçimlendirme özelliklerini döndürmek ve değiştirmek için kullanılır. Bu, değerler alınırken hiçbir kalıtım uygulanmadığı anlamına gelir, bu yüzden çoğu durumda "tanımsız" anlamına gelen değerler alırsınız.

Kalıtım dahil olmak üzere etkili biçimlendirme parametresi değerlerini elde etmek için [IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective) yöntemini kullanmanız gerekir; bu yöntem bir [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) örneği döndürür.
## Metodlar

| Metod | Açıklama |
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
| [getKerningMinimalSize()](#getKerningMinimalSize--) | Returns or sets the minimal font size, for which kerting should be switched on. |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | Returns or sets the minimal font size, for which kerting should be switched on. |
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

Metin taslağı için LineFormat özelliklerini döndürür. Kalıtım uygulanmaz. **Salt okunur** [ILineFormat](../../com.aspose.slides/ilineformat).

**Döndürür:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Metin FillFormat özelliklerini döndürür. Kalıtım uygulanmaz. **Salt okunur** [IFillFormat](../../com.aspose.slides/ifillformat).

**Döndürür:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

Metin EffectFormat özelliklerini döndürür. Kalıtım uygulanmaz. **Salt okunur** [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Döndürür:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getHighlightColor() {#getHighlightColor--}
```
public abstract IColorFormat getHighlightColor()
```

Bir metni vurgulamak için kullanılan rengi döndürür. Kalıtım uygulanmaz. **Salt okunur** [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormat getUnderlineLineFormat()
```

Alt çizgi satırını taslaklamak için kullanılan LineFormat özelliklerini döndürür. Kalıtım uygulanmaz. **Salt okunur** [ILineFormat](../../com.aspose.slides/ilineformat).

**Döndürür:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormat getUnderlineFillFormat()
```

Alt çizgi satırının FillFormat özelliklerini döndürür. Kalıtım uygulanmaz. **Salt okunur** [IFillFormat](../../com.aspose.slides/ifillformat).

**Döndürür:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getFontBold() {#getFontBold--}
```
public abstract byte getFontBold()
```

Yazı tipinin kalın olup olmadığını belirler. Kalıtım uygulanmaz. **Okunur/yazılabilir** [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte

### setFontBold(byte value) {#setFontBold-byte-}
```
public abstract void setFontBold(byte value)
```

Yazı tipinin kalın olup olmadığını belirler. Kalıtım uygulanmaz. **Okunur/yazılabilir** [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getFontItalic() {#getFontItalic--}
```
public abstract byte getFontItalic()
```

Yazı tipinin italik olup olmadığını belirler. Kalıtım uygulanmaz. **Okunur/yazılabilir** [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte

### setFontItalic(byte value) {#setFontItalic-byte-}
```
public abstract void setFontItalic(byte value)
```

Yazı tipinin italik olup olmadığını belirler. Kalıtım uygulanmaz. **Okunur/yazılabilir** [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getKumimoji() {#getKumimoji--}
```
public abstract byte getKumimoji()
```

Sayının, metin Doğu Asya dili özel dikey metin düzenini görmezden gelip gelmeyeceğini belirler. Kalıtım uygulanmaz. **Okunur/yazılabilir** [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte

### setKumimoji(byte value) {#setKumimoji-byte-}
```
public abstract void setKumimoji(byte value)
```

Sayının, metin Doğu Asya dili özel dikey metin düzenini görmezden gelip gelmeyeceğini belirler. Kalıtım uygulanmaz. **Okunur/yazılabilir** [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract byte getNormaliseHeight()
```

Metnin yüksekliğinin normalleştirilip normalleştirilmeyeceğini belirler. Kalıtım uygulanmaz. **Okunur/yazılabilir** [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte

### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public abstract void setNormaliseHeight(byte value)
```

Metnin yüksekliğinin normalleştirilip normalleştirilmeyeceğini belirler. Kalıtım uygulanmaz. **Okunur/yazılabilir** [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getProofDisabled() {#getProofDisabled--}
```
public abstract byte getProofDisabled()
```

Metnin düzeltme yapılmaması gerektiğini belirler. Kalıtım uygulanmaz. **Okunur/yazılabilir** [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte

### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public abstract void setProofDisabled(byte value)
```

Metnin düzeltme yapılmaması gerektiğini belirler. Kalıtım uygulanmaz. **Okunur/yazılabilir** [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```

Metin alt çizgi tipini döndürür veya ayarlar. Kalıtım uygulanmaz. **Okunur/yazılabilir** [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Döndürür:**
byte

### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public abstract void setFontUnderline(byte value)
```

Metin alt çizgi tipini döndürür veya ayarlar. Kalıtım uygulanmaz. **Okunur/yazılabilir** [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```

Metin büyük/küçük harf tipini döndürür veya ayarlar. Kalıtım uygulanmaz. **Okunur/yazılabilir** [TextCapType](../../com.aspose.slides/textcaptype).

**Döndürür:**
byte

### setTextCapType(byte value) {#setTextCapType-byte-}
```
public abstract void setTextCapType(byte value)
```

Metin büyük/küçük harf tipini döndürür veya ayarlar. Kalıtım uygulanmaz. **Okunur/yazılabilir** [TextCapType](../../com.aspose.slides/textcaptype).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```

Metnin üstü çizili tipini döndürür veya ayarlar. Kalıtım uygulanmaz. **Okunur/yazılabilir** [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Döndürür:**
byte

### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public abstract void setStrikethroughType(byte value)
```

Metnin üstü çizili tipini döndürür veya ayarlar. Kalıtım uygulanmaz. **Okunur/yazılabilir** [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract byte isHardUnderlineLine()
```

Alt çizgi stilinin kendi LineFormat özelliklerine sahip olup olmadığını veya metnin LineFormat özelliklerinden kalıtım alıp almadığını belirler. **Okunur/yazılabilir** [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte

### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public abstract void setHardUnderlineLine(byte value)
```

Alt çizgi stilinin kendi LineFormat özelliklerine sahip olup olmadığını veya metnin LineFormat özelliklerinden kalıtım alıp almadığını belirler. **Okunur/yazılabilir** [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract byte isHardUnderlineFill()
```

Alt çizgi stilinin kendi FillFormat özelliklerine sahip olup olmadığını veya metnin FillFormat özelliklerinden kalıtım alıp almadığını belirler. **Okunur/yazılabilir** [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte

### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public abstract void setHardUnderlineFill(byte value)
```

Alt çizgi stilinin kendi FillFormat özelliklerine sahip olup olmadığını veya metnin FillFormat özelliklerinden kalıtım alıp almadığını belirler. **Okunur/yazılabilir** [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```

Bir bölümün yazı tipi yüksekliğini döndürür veya ayarlar. **Float.NaN**, yüksekliğin tanımsız olduğunu ve Ana'dan kalıtım alınması gerektiğini gösterir. **Okunur/yazılabilir** float.

**Döndürür:**
float

### setFontHeight(float value) {#setFontHeight-float-}
```
public abstract void setFontHeight(float value)
```

Bir bölümün yazı tipi yüksekliğini döndürür veya ayarlar. **Float.NaN**, yüksekliğin tanımsız olduğunu ve Ana'dan kalıtım alınması gerektiğini gösterir. **Okunur/yazılabilir** float.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

Latin yazı tipi bilgisini döndürür veya ayarlar. Null, yazı tipinin tanımsız olduğunu ve Ana'dan kalıtım alınması gerektiğini gösterir. **Okunur/yazılabilir** [IFontData](../../com.aspose.slides/ifontdata).

**Döndürür:**
[IFontData](../../com.aspose.slides/ifontdata)

### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```

Latin yazı tipi bilgisini döndürür veya ayarlar. Null, yazı tipinin tanımsız olduğunu ve Ana'dan kalıtım alınması gerektiğini gösterir. **Okunur/yazılabilir** [IFontData](../../com.aspose.slides/ifontdata).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

Doğu Asya yazı tipi bilgisini döndürür veya ayarlar. Null, yazı tipinin tanımsız olduğunu ve Ana'dan kalıtım alınması gerektiğini gösterir. **Okunur/yazılabilir** [IFontData](../../com.aspose.slides/ifontdata).

**Döndürür:**
[IFontData](../../com.aspose.slides/ifontdata)

### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```

Doğu Asya yazı tipi bilgisini döndürür veya ayarlar. Null, yazı tipinin tanımsız olduğunu ve Ana'dan kalıtım alınması gerektiğini gösterir. **Okunur/yazılabilir** [IFontData](../../com.aspose.slides/ifontdata).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

Karmaşık betik yazı tipi bilgisini döndürür veya ayarlar. Null, yazı tipinin tanımsız olduğunu ve Ana'dan kalıtım alınması gerektiğini gösterir. **Okunur/yazılabilir** [IFontData](../../com.aspose.slides/ifontdata).

**Döndürür:**
[IFontData](../../com.aspose.slides/ifontdata)

### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```

Karmaşık betik yazı tipi bilgisini döndürür veya ayarlar. Null, yazı tipinin tanımsız olduğunu ve Ana'dan kalıtım alınması gerektiğini gösterir. **Okunur/yazılabilir** [IFontData](../../com.aspose.slides/ifontdata).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```

Sembolik yazı tipi bilgisini döndürür veya ayarlar. Null, yazı tipinin tanımsız olduğunu ve Ana'dan kalıtım alınması gerektiğini gösterir. **Okunur/yazılabilir** [IFontData](../../com.aspose.slides/ifontdata).

**Döndürür:**
[IFontData](../../com.aspose.slides/ifontdata)

### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public abstract void setSymbolFont(IFontData value)
```

Sembolik yazı tipi bilgisini döndürür veya ayarlar. Null, yazı tipinin tanımsız olduğunu ve Ana'dan kalıtım alınması gerektiğini gösterir. **Okunur/yazılabilir** [IFontData](../../com.aspose.slides/ifontdata).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```

Üst simge ya da alt simge metnini döndürür veya ayarlar. Değer -%100 (alt simge) ile %100 (üst simge) arasındadır. **Float.NaN**, değerin tanımsız olduğunu ve Ana'dan kalıtım alınması gerektiğini gösterir. **Okunur/yazılabilir** float.

**Döndürür:**
float

### setEscapement(float value) {#setEscapement-float-}
```
public abstract void setEscapement(float value)
```

Üst simge ya da alt simge metnini döndürür veya ayarlar. Değer -%100 (alt simge) ile %100 (üst simge) arasındadır. **Float.NaN**, değerin tanımsız olduğunu ve Ana'dan kalıtım alınması gerektiğini gösterir. **Okunur/yazılabilir** float.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```

Kerlingsi açılması gereken minimal yazı tipi boyutunu döndürür veya ayarlar. **Float.NaN**, değerin tanımsız olduğunu ve Ana'dan kalıtım alınması gerektiğini gösterir. **Okunur/yazılabilir** float.

**Döndürür:**
float

### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public abstract void setKerningMinimalSize(float value)
```

Kerlingsi açılması gereken minimal yazı tipi boyutunu döndürür veya ayarlar. **Float.NaN**, değerin tanımsız olduğunu ve Ana'dan kalıtım alınması gerektiğini gösterir. **Okunur/yazılabilir** float.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```

Düzeltme dili kimliğini döndürür veya ayarlar. Yazım ve dilbilgisi denetimi için kullanılır. **Okunur/yazılabilir** String.

**Döndürür:**
java.lang.String

### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public abstract void setLanguageId(String value)
```

Düzeltme dili kimliğini döndürür veya ayarlar. Yazım ve dilbilgisi denetimi için kullanılır. **Okunur/yazılabilir** String.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```

Alternatif dil kimliğini döndürür veya ayarlar. **Okunur/yazılabilir** String.

**Döndürür:**
java.lang.String

### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public abstract void setAlternativeLanguageId(String value)
```

Alternatif dil kimliğini döndürür veya ayarlar. **Okunur/yazılabilir** String.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```

Karakter arası boşluk artışını döndürür veya ayarlar. **Float.NaN**, değerin tanımsız olduğunu ve Ana'dan kalıtım alınması gerektiğini gösterir. **Okunur/yazılabilir** float.

**Döndürür:**
float

### setSpacing(float value) {#setSpacing-float-}
```
public abstract void setSpacing(float value)
```

Karakter arası boşluk artışını döndürür veya ayarlar. **Float.NaN**, değerin tanımsız olduğunu ve Ana'dan kalıtım alınması gerektiğini gösterir. **Okunur/yazılabilir** float.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getSpellCheck() {#getSpellCheck--}
```
public abstract boolean getSpellCheck()
```

Metin kısmı için yazım denetiminin etkin olup olmadığını belirten bir değeri alır veya ayarlar. Bu özellik false olarak ayarlandığında, metin öğelerinin yazım denetimi engellenir. True olarak ayarlandığında, yazım denetimine izin verilir. Varsayılan değer false'tur.

**Döndürür:**
boolean

### setSpellCheck(boolean value) {#setSpellCheck-boolean-}
```
public abstract void setSpellCheck(boolean value)
```

Metin kısmı için yazım denetiminin etkin olup olmadığını belirten bir değeri alır veya ayarlar. Bu özellik false olarak ayarlandığında, metin öğelerinin yazım denetimi engellenir. True olarak ayarlandığında, yazım denetimine izin verilir. Varsayılan değer false'tur.

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // İlk slayttaki ilk şeklin içindeki metnin ilk bölümüne erişim
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Bu metin bölümü için yazım denetimini etkinleştir
>      portion.getPortionFormat().setSpellCheck(true);
>      // Değiştirilmiş sunumu kaydet
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Döndürür:**
boolean

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // İlk slayttaki ilk şeklin içinde bulunan metnin ilk bölümüne erişim
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Bu metin bölümü için yazım denetimini etkinleştir
>      portion.getPortionFormat().setSpellCheck(true);
>      // Değiştirilmiş sunumu kaydet
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |