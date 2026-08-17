---
title: IBasePortionFormat
second_title: Aspose.Slides for Java API Reference
description: This class contains the text portion formatting properties.
type: docs
url: /tr/com.aspose.slides/ibaseportionformat/
---```
public interface IBasePortionFormat
```

Bu sınıf, metin bölümü biçimlendirme özelliklerini içerir. [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)'nin aksine, bu sınıfın tüm özellikleri yazılabilir.

--------------------

Bu sınıf, belirli bir bölüm için tanımlanan metin bölümü biçimlendirme özelliklerini döndürmek ve değiştirmek için kullanılır. Bu, değer alınırken kalıtım uygulanmadığı anlamına gelir, bu yüzden çoğu durumda "tanımsız" anlamına gelen değerler alırsınız.

Kalıtım dahil olmak üzere etkili biçimlendirme parametre değerlerini almak için [IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective) metodunu kullanmanız gerekir; bu metod bir [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) örneği döndürür.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | Metin konturunu çizmek için LineFormat özelliklerini döndürür. |
| [getFillFormat()](#getFillFormat--) | Metin FillFormat özelliklerini döndürür. |
| [getEffectFormat()](#getEffectFormat--) | Metin EffectFormat özelliklerini döndürür. |
| [getHighlightColor()](#getHighlightColor--) | Metni vurgulamak için kullanılan rengi döndürür. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | Alt çizgi hattını konturlamak için kullanılan LineFormat özelliklerini döndürür. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | Alt çizgi hattının FillFormat özelliklerini döndürür. |
| [getFontBold()](#getFontBold--) | Yazı tipinin kalın olup olmadığını belirler. |
| [setFontBold(byte value)](#setFontBold-byte-) | Yazı tipinin kalın olup olmadığını belirler. |
| [getFontItalic()](#getFontItalic--) | Yazı tipinin italik olup olmadığını belirler. |
| [setFontItalic(byte value)](#setFontItalic-byte-) | Yazı tipinin italik olup olmadığını belirler. |
| [getKumimoji()](#getKumimoji--) | Sayıların, metnin doğu dili özgü dikey metin düzenini görmezden gelmesini belirler. |
| [setKumimoji(byte value)](#setKumimoji-byte-) | Sayıların, metnin doğu dili özgü dikey metin düzenini görmezden gelmesini belirler. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Metnin yüksekliğinin normalize edilip edilmemesi gerektiğini belirler. |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | Metnin yüksekliğinin normalize edilip edilmemesi gerektiğini belirler. |
| [getProofDisabled()](#getProofDisabled--) | Metnin denetlenmemesi gerektiğini belirler. |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | Metnin denetlenmemesi gerektiğini belirler. |
| [getFontUnderline()](#getFontUnderline--) | Metin altı çizgi tipini döndürür veya ayarlar. |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | Metin altı çizgi tipini döndürür veya ayarlar. |
| [getTextCapType()](#getTextCapType--) | Metin büyük/küçük harf tipini döndürür veya ayarlar. |
| [setTextCapType(byte value)](#setTextCapType-byte-) | Metin büyük/küçük harf tipini döndürür veya ayarlar. |
| [getStrikethroughType()](#getStrikethroughType--) | Metnin üstü çizili tipini döndürür veya ayarlar. |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | Metnin üstü çizili tipini döndürür veya ayarlar. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Alt çizgi stilinin kendi LineFormat özelliklerine sahip olup metnin LineFormat özelliklerinden kalıtım alıp almadığını belirler. |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | Alt çizgi stilinin kendi LineFormat özelliklerine sahip olup metnin LineFormat özelliklerinden kalıtım alıp almadığını belirler. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Alt çizgi stilinin kendi FillFormat özelliklerine sahip olup metnin FillFormat özelliklerinden kalıtım alıp almadığını belirler. |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | Alt çizgi stilinin kendi FillFormat özelliklerine sahip olup metnin FillFormat özelliklerinden kalıtım alıp almadığını belirler. |
| [getFontHeight()](#getFontHeight--) | Bir bölümün yazı tipi yüksekliğini döndürür veya ayarlar. |
| [setFontHeight(float value)](#setFontHeight-float-) | Bir bölümün yazı tipi yüksekliğini döndürür veya ayarlar. |
| [getLatinFont()](#getLatinFont--) | Latin yazı tipi bilgilerini döndürür veya ayarlar. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Latin yazı tipi bilgilerini döndürür veya ayarlar. |
| [getEastAsianFont()](#getEastAsianFont--) | Doğu Asya yazı tipi bilgilerini döndürür veya ayarlar. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Doğu Asya yazı tipi bilgilerini döndürür veya ayarlar. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Karmaşık betik yazı tipi bilgilerini döndürür veya ayarlar. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Karmaşık betik yazı tipi bilgilerini döndürür veya ayarlar. |
| [getSymbolFont()](#getSymbolFont--) | Sembolik yazı tipi bilgilerini döndürür veya ayarlar. |
| [setSymbolFont(IFontData value)](#setSymbolFont-com.aspose.slides.IFontData-) | Sembolik yazı tipi bilgilerini döndürür veya ayarlar. |
| [getEscapement()](#getEscapement--) | Üst simge veya alt simge metnini döndürür veya ayarlar. |
| [setEscapement(float value)](#setEscapement-float-) | Üst simge veya alt simge metnini döndürür veya ayarlar. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | Kerning'in etkinleştirileceği minimum yazı tipi boyutunu döndürür veya ayarlar. |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | Kerning'in etkinleştirileceği minimum yazı tipi boyutunu döndürür veya ayarlar. |
| [getLanguageId()](#getLanguageId--) | Bir düzeltme dilinin kimliğini döndürür veya ayarlar. |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | Bir düzeltme dilinin kimliğini döndürür veya ayarlar. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | Alternatif bir dilin kimliğini döndürür veya ayarlar. |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | Alternatif bir dilin kimliğini döndürür veya ayarlar. |
| [getSpacing()](#getSpacing--) | Karakterler arasındaki boşluk artışını döndürür veya ayarlar. |
| [setSpacing(float value)](#setSpacing-float-) | Karakterler arasındaki boşluk artışını döndürür veya ayarlar. |
| [getSpellCheck()](#getSpellCheck--) | Metin bölümü için imla denetiminin etkin olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | Metin bölümü için imla denetiminin etkin olup olmadığını gösteren bir değeri alır veya ayarlar. |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```

Metin konturunu çizmek için LineFormat özelliklerini döndürür. Kalıtım uygulanmaz. Salt okunur [ILineFormat](../../com.aspose.slides/ilineformat).

**Döndürür:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Metin FillFormat özelliklerini döndürür. Kalıtım uygulanmaz. Salt okunur [IFillFormat](../../com.aspose.slides/ifillformat).

**Döndürür:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

Metin EffectFormat özelliklerini döndürür. Kalıtım uygulanmaz. Salt okunur [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Döndürür:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getHighlightColor() {#getHighlightColor--}
```
public abstract IColorFormat getHighlightColor()
```

Metni vurgulamak için kullanılan rengi döndürür. Kalıtım uygulanmaz. Salt okunur [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormat getUnderlineLineFormat()
```

Alt çizgi hattını konturlamak için kullanılan LineFormat özelliklerini döndürür. Kalıtım uygulanmaz. Salt okunur [ILineFormat](../../com.aspose.slides/ilineformat).

**Döndürür:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormat getUnderlineFillFormat()
```

Alt çizgi hattının FillFormat özelliklerini döndürür. Kalıtım uygulanmaz. Salt okunur [IFillFormat](../../com.aspose.slides/ifillformat).

**Döndürür:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getFontBold() {#getFontBold--}
```
public abstract byte getFontBold()
```

Yazı tipinin kalın olup olmadığını belirler. Kalıtım uygulanmaz. Okuma/yazma [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte

### setFontBold(byte value) {#setFontBold-byte-}
```
public abstract void setFontBold(byte value)
```

Yazı tipinin kalın olup olmadığını belirler. Kalıtım uygulanmaz. Okuma/yazma [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getFontItalic() {#getFontItalic--}
```
public abstract byte getFontItalic()
```

Yazı tipinin italik olup olmadığını belirler. Kalıtım uygulanmaz. Okuma/yazma [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte

### setFontItalic(byte value) {#setFontItalic-byte-}
```
public abstract void setFontItalic(byte value)
```

Yazı tipinin italik olup olmadığını belirler. Kalıtım uygulanmaz. Okuma/yazma [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getKumimoji() {#getKumimoji--}
```
public abstract byte getKumimoji()
```

Sayılara, metnin doğu dili özgü dikey metin düzenini görmezden gelmesini belirler. Kalıtım uygulanmaz. Okuma/yazma [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte

### setKumimoji(byte value) {#setKumimoji-byte-}
```
public abstract void setKumimoji(byte value)
```

Sayılara, metnin doğu dili özgü dikey metin düzenini görmezden gelmesini belirler. Kalıtım uygulanmaz. Okuma/yazma [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract byte getNormaliseHeight()
```

Metnin yüksekliğinin normalize edilip edilmemesi gerektiğini belirler. Kalıtım uygulanmaz. Okuma/yazma [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte

### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public abstract void setNormaliseHeight(byte value)
```

Metnin yüksekliğinin normalize edilip edilmemesi gerektiğini belirler. Kalıtım uygulanmaz. Okuma/yazma [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getProofDisabled() {#getProofDisabled--}
```
public abstract byte getProofDisabled()
```

Metnin denetlenmemesi gerektiğini belirler. Kalıtım uygulanmaz. Okuma/yazma [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte

### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public abstract void setProofDisabled(byte value)
```

Metnin denetlenmemesi gerektiğini belirler. Kalıtım uygulanmaz. Okuma/yazma [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```

Metin altı çizgi tipini döndürür veya ayarlar. Kalıtım uygulanmaz. Okuma/yazma [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Döndürür:**
byte

### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public abstract void setFontUnderline(byte value)
```

Metin altı çizgi tipini döndürür veya ayarlar. Kalıtım uygulanmaz. Okuma/yazma [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```

Metin büyük/küçük harf tipini döndürür veya ayarlar. Kalıtım uygulanmaz. Okuma/yazma [TextCapType](../../com.aspose.slides/textcaptype).

**Döndürür:**
byte

### setTextCapType(byte value) {#setTextCapType-byte-}
```
public abstract void setTextCapType(byte value)
```

Metin büyük/küçük harf tipini döndürür veya ayarlar. Kalıtım uygulanmaz. Okuma/yazma [TextCapType](../../com.aspose.slides/textcaptype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```

Metnin üstü çizili tipini döndürür veya ayarlar. Kalıtım uygulanmaz. Okuma/yazma [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Döndürür:**
byte

### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public abstract void setStrikethroughType(byte value)
```

Metnin üstü çizili tipini döndürür veya ayarlar. Kalıtım uygulanmaz. Okuma/yazma [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract byte isHardUnderlineLine()
```

Alt çizgi stilinin kendi LineFormat özelliklerine sahip olup metnin LineFormat özelliklerinden kalıtım alıp almadığını belirler. Okuma/yazma [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte

### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public abstract void setHardUnderlineLine(byte value)
```

Alt çizgi stilinin kendi LineFormat özelliklerine sahip olup metnin LineFormat özelliklerinden kalıtım alıp almadığını belirler. Okuma/yazma [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract byte isHardUnderlineFill()
```

Alt çizgi stilinin kendi FillFormat özelliklerine sahip olup metnin FillFormat özelliklerinden kalıtım alıp almadığını belirler. Okuma/yazma [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte

### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public abstract void setHardUnderlineFill(byte value)
```

Alt çizgi stilinin kendi FillFormat özelliklerine sahip olup metnin FillFormat özelliklerinden kalıtım alıp almadığını belirler. Okuma/yazma [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```

Bir bölümün yazı tipi yüksekliğini döndürür veya ayarlar. **Float.NaN** yüksekliğin tanımsız olduğu ve Master'dan kalıtılacağı anlamına gelir. Okuma/yazma float.

**Döndürür:**
float

### setFontHeight(float value) {#setFontHeight-float-}
```
public abstract void setFontHeight(float value)
```

Bir bölümün yazı tipi yüksekliğini döndürür veya ayarlar. **Float.NaN** yüksekliğin tanımsız olduğu ve Master'dan kalıtılacağı anlamına gelir. Okuma/yazma float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

Latin yazı tipi bilgilerini döndürür veya ayarlar. Null, yazı tipinin tanımsız olduğu ve Master'dan kalıtılacağı anlamına gelir. Okuma/yazma [IFontData](../../com.aspose.slides/ifontdata).

**Döndürür:**
[IFontData](../../com.aspose.slides/ifontdata)

### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```

Latin yazı tipi bilgilerini döndürür veya ayarlar. Null, yazı tipinin tanımsız olduğu ve Master'dan kalıtılacağı anlamına gelir. Okuma/yazma [IFontData](../../com.aspose.slides/ifontdata).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

Doğu Asya yazı tipi bilgilerini döndürür veya ayarlar. Null, yazı tipinin tanımsız olduğu ve Master'dan kalıtılacağı anlamına gelir. Okuma/yazma [IFontData](../../com.aspose.slides/ifontdata).

**Döndürür:**
[IFontData](../../com.aspose.slides/ifontdata)

### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```

Doğu Asya yazı tipi bilgilerini döndürür veya ayarlar. Null, yazı tipinin tanımsız olduğu ve Master'dan kalıtılacağı anlamına gelir. Okuma/yazma [IFontData](../../com.aspose.slides/ifontdata).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

Karmaşık betik yazı tipi bilgilerini döndürür veya ayarlar. Null, yazı tipinin tanımsız olduğu ve Master'dan kalıtılacağı anlamına gelir. Okuma/yazma [IFontData](../../com.aspose.slides/ifontdata).

**Döndürür:**
[IFontData](../../com.aspose.slides/ifontdata)

### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```

Karmaşık betik yazı tipi bilgilerini döndürür veya ayarlar. Null, yazı tipinin tanımsız olduğu ve Master'dan kalıtılacağı anlamına gelir. Okuma/yazma [IFontData](../../com.aspose.slides/ifontdata).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```

Sembolik yazı tipi bilgilerini döndürür veya ayarlar. Null, yazı tipinin tanımsız olduğu ve Master'dan kalıtılacağı anlamına gelir. Okuma/yazma [IFontData](../../com.aspose.slides/ifontdata).

**Döndürür:**
[IFontData](../../com.aspose.slides/ifontdata)

### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public abstract void setSymbolFont(IFontData value)
```

Sembolik yazı tipi bilgilerini döndürür veya ayarlar. Null, yazı tipinin tanımsız olduğu ve Master'dan kalıtılacağı anlamına gelir. Okuma/yazma [IFontData](../../com.aspose.slides/ifontdata).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```

Üst simge veya alt simge metnini döndürür veya ayarlar. Değer -%100 (alt simge) ile %100 (üst simge) arasındadır. **Float.NaN** değerin tanımsız olduğu ve Master'dan kalıtılacağı anlamına gelir. Okuma/yazma float.

**Döndürür:**
float

### setEscapement(float value) {#setEscapement-float-}
```
public abstract void setEscapement(float value)
```

Üst simge veya alt simge metnini döndürür veya ayarlar. Değer -%100 (alt simge) ile %100 (üst simge) arasındadır. **Float.NaN** değerin tanımsız olduğu ve Master'dan kalıtılacağı anlamına gelir. Okuma/yazma float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```

Kerning'in etkinleştirileceği minimum yazı tipi boyutunu döndürür veya ayarlar. **Float.NaN** değerin tanımsız olduğu ve Master'dan kalıtılacağı anlamına gelir. Okuma/yazma float.

**Döndürür:**
float

### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public abstract void setKerningMinimalSize(float value)
```

Kerning'in etkinleştirileceği minimum yazı tipi boyutunu döndürür veya ayarlar. **Float.NaN** değerin tanımsız olduğu ve Master'dan kalıtılacağı anlamına gelir. Okuma/yazma float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```

Bir düzeltme dilinin kimliğini döndürür veya ayarlar. Yazım ve dilbilgisi denetimi için kullanılır. Okuma/yazma String.

**Döndürür:**
java.lang.String

### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public abstract void setLanguageId(String value)
```

Bir düzeltme dilinin kimliğini döndürür veya ayarlar. Yazım ve dilbilgisi denetimi için kullanılır. Okuma/yazma String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```

Alternatif bir dilin kimliğini döndürür veya ayarlar. Okuma/yazma String.

**Döndürür:**
java.lang.String

### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public abstract void setAlternativeLanguageId(String value)
```

Alternatif bir dilin kimliğini döndürür veya ayarlar. Okuma/yazma String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```

Karakterler arasındaki boşluk artışını döndürür veya ayarlar. **Float.NaN** değerin tanımsız olduğu ve Master'dan kalıtılacağı anlamına gelir. Okuma/yazma float.

**Döndürür:**
float

### setSpacing(float value) {#setSpacing-float-}
```
public abstract void setSpacing(float value)
```

Karakterler arasındaki boşluk artışını döndürür veya ayarlar. **Float.NaN** değerin tanımsız olduğu ve Master'dan kalıtılacağı anlamına gelir. Okuma/yazma float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getSpellCheck() {#getSpellCheck--}
```
public abstract boolean getSpellCheck()
```

Metin bölümü için imla denetiminin etkin olup olmadığını gösteren bir değeri alır veya ayarlar. Bu özellik false olarak ayarlandığında, metin öğeleri için imla denetimi engellenir. True olarak ayarlandığında, imla denetimine izin verilir. Varsayılan değer false'tur.

**Döndürür:**
boolean

--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // İlk slayttaki ilk şeklin içindeki metnin ilk bölümüne erişim
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Bu metin bölümü için imla denetimini etkinleştir
>      portion.getPortionFormat().setSpellCheck(true);
>      // Değiştirilmiş sunumu kaydet
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Döndürür:**
boolean

### setSpellCheck(boolean value) {#setSpellCheck-boolean-}
```
public abstract void setSpellCheck(boolean value)
```

Metin bölümü için imla denetiminin etkin olup olmadığını gösteren bir değeri alır veya ayarlar. Bu özellik false olarak ayarlandığında, metin öğeleri için imla denetimi engellenir. True olarak ayarlandığında, imla denetimine izin verilir. Varsayılan değer false'tur.

--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // İlk slayttaki ilk şeklin içindeki metnin ilk bölümüne erişim
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Bu metin bölümü için imla denetimini etkinleştir
>      portion.getPortionFormat().setSpellCheck(true);
>      // Değiştirilmiş sunumu kaydet
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |