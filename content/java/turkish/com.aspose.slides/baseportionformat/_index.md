---
title: BasePortionFormat
second_title: Aspose.Slides için Java API Referansı
description: Ortak metin bölümü biçimlendirme özellikleri.
type: docs
url: /tr/com.aspose.slides/baseportionformat/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat)
```
public abstract class BasePortionFormat extends PVIObject implements IBasePortionFormat
```

Metin bölümü biçimlendirme özellikleri ortak.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getLineFormat()](#getLineFormat--) | Metin taslağı için LineFormat özelliklerini döndürür. |
| [getFillFormat()](#getFillFormat--) | Metin FillFormat özelliklerini döndürür. |
| [getEffectFormat()](#getEffectFormat--) | Metin EffectFormat özelliklerini döndürür. |
| [getHighlightColor()](#getHighlightColor--) | Metni vurgulamak için kullanılan rengi döndürür. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | Alt çizgi satırını tasarlamak için kullanılan LineFormat özelliklerini döndürür. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | Alt çizgi satırı FillFormat özelliklerini döndürür. |
| [getFontBold()](#getFontBold--) | Yazı tipinin kalın olup olmadığını belirler. |
| [setFontBold(byte value)](#setFontBold-byte-) | Yazı tipinin kalın olup olmadığını belirler. |
| [getFontItalic()](#getFontItalic--) | Yazı tipinin italik olup olmadığını belirler. |
| [setFontItalic(byte value)](#setFontItalic-byte-) | Yazı tipinin italik olup olmadığını belirler. |
| [getKumimoji()](#getKumimoji--) | Numaraların, metnin doğu dili özgü dikey yerleşimini göz ardı edip etmeyeceğini belirler. |
| [setKumimoji(byte value)](#setKumimoji-byte-) | Numaraların, metnin doğu dili özgü dikey yerleşimini göz ardı edip etmeyeceğini belirler. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Metnin yüksekliğinin normalleştirilip normalleştirilmeyeceğini belirler. |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | Metnin yüksekliğinin normalleştirilip normalleştirilmeyeceğini belirler. |
| [getProofDisabled()](#getProofDisabled--) | Metnin denetlenmemesi gerektiğini belirler. |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | Metnin denetlenmemesi gerektiğini belirler. |
| [getFontUnderline()](#getFontUnderline--) | Metin alt çizgi tipini döndürür veya ayarlar. |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | Metin alt çizgi tipini döndürür veya ayarlar. |
| [getTextCapType()](#getTextCapType--) | Metin büyük harf tipini döndürür veya ayarlar. |
| [setTextCapType(byte value)](#setTextCapType-byte-) | Metin büyük harf tipini döndürür veya ayarlar. |
| [getStrikethroughType()](#getStrikethroughType--) | Metnin üstü çizili tipini döndürür veya ayarlar. |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | Metnin üstü çizili tipini döndürür veya ayarlar. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Alt çizgi stilinin kendi LineFormat özelliklerine sahip olup olmadığını veya metnin LineFormat özelliklerinden miras alıp almadığını belirler. |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | Alt çizgi stilinin kendi LineFormat özelliklerine sahip olup olmadığını veya metnin LineFormat özelliklerinden miras alıp almadığını belirler. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Alt çizgi stilinin kendi FillFormat özelliklerine sahip olup olmadığını veya metnin FillFormat özelliklerinden miras alıp almadığını belirler. |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | Alt çizgi stilinin kendi FillFormat özelliklerine sahip olup olmadığını veya metnin FillFormat özelliklerinden miras alıp almadığını belirler. |
| [getFontHeight()](#getFontHeight--) | Bir bölümün yazı tipi yüksekliğini döndürür veya ayarlar. |
| [setFontHeight(float value)](#setFontHeight-float-) | Bir bölümün yazı tipi yüksekliğini döndürür veya ayarlar. |
| [getLatinFont()](#getLatinFont--) | Latin yazı tipi bilgilerini döndürür veya ayarlar. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Latin yazı tipi bilgilerini döndürür veya ayarlar. |
| [getEastAsianFont()](#getEastAsianFont--) | Doğu Asya yazı tipi bilgilerini döndürür veya ayarlar. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Doğu Asya yazı tipi bilgilerini döndürür veya ayarlar. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Karmaşık betik (script) yazı tipi bilgilerini döndürür veya ayarlar. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Karmaşık betik (script) yazı tipi bilgilerini döndürür veya ayarlar. |
| [getSymbolFont()](#getSymbolFont--) | Sembolik yazı tipi bilgilerini döndürür veya ayarlar. |
| [setSymbolFont(IFontData value)](#setSymbolFont-com.aspose.slides.IFontData-) | Sembolik yazı tipi bilgilerini döndürür veya ayarlar. |
| [getEscapement()](#getEscapement--) | Üst veya alt simge (superscript/subscript) metnini döndürür veya ayarlar. |
| [setEscapement(float value)](#setEscapement-float-) | Üst veya alt simge (superscript/subscript) metnini döndürür veya ayarlar. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | Kerning'in etkinleştirileceği en düşük yazı tipi boyutunu döndürür veya ayarlar. |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | Kerning'in etkinleştirileceği en düşük yazı tipi boyutunu döndürür veya ayarlar. |
| [getLanguageId()](#getLanguageId--) | Bir denetleme dilinin kimliğini (Id) döndürür veya ayarlar. |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | Bir denetleme dilinin kimliğini (Id) döndürür veya ayarlar. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | Alternatif bir dilin kimliğini (Id) döndürür veya ayarlar. |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | Alternatif bir dilin kimliğini (Id) döndürür veya ayarlar. |
| [getSpacing()](#getSpacing--) | Karakterler arası boşluk artışını döndürür veya ayarlar. |
| [setSpacing(float value)](#setSpacing-float-) | Karakterler arası boşluk artışını döndürür veya ayarlar. |
| [getSpellCheck()](#getSpellCheck--) | Metin bölümü için yazım denetiminin etkin olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | Metin bölümü için yazım denetiminin etkin olup olmadığını gösteren bir değeri alır veya ayarlar. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Sürüm. Yalnızca okunabilir long.

**Döndürür:**
long

### getLineFormat() {#getLineFormat--}
```
public final ILineFormat getLineFormat()
```

Metin taslağı için LineFormat özelliklerini döndürür. Kalıtım uygulanmaz. Yalnızca okunabilir [ILineFormat](../../com.aspose.slides/ilineformat).

**Döndürür:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

Metin FillFormat özelliklerini döndürür. Kalıtım uygulanmaz. Yalnızca okunabilir [IFillFormat](../../com.aspose.slides/ifillformat).

**Döndürür:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getEffectFormat() {#getEffectFormat--}
```
public final IEffectFormat getEffectFormat()
```

Metin EffectFormat özelliklerini döndürür. Kalıtım uygulanmaz. Yalnızca okunabilir [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Döndürür:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getHighlightColor() {#getHighlightColor--}
```
public final IColorFormat getHighlightColor()
```

Metni vurgulamak için kullanılan rengi döndürür. Kalıtım uygulanmaz. Yalnızca okunabilir [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public final ILineFormat getUnderlineLineFormat()
```

Alt çizgi satırını tasarlamak için kullanılan LineFormat özelliklerini döndürür. Kalıtım uygulanmaz. Yalnızca okunabilir [ILineFormat](../../com.aspose.slides/ilineformat).

**Döndürür:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public final IFillFormat getUnderlineFillFormat()
```

Alt çizgi satırı FillFormat özelliklerini döndürür. Kalıtım uygulanmaz. Yalnızca okunabilir [IFillFormat](../../com.aspose.slides/ifillformat).

**Döndürür:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getFontBold() {#getFontBold--}
```
public final byte getFontBold()
```

Yazı tipinin kalın olup olmadığını belirler. Kalıtım uygulanmaz. Okunur/Yazılır [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte

### setFontBold(byte value) {#setFontBold-byte-}
```
public final void setFontBold(byte value)
```

Yazı tipinin kalın olup olmadığını belirler. Kalıtım uygulanmaz. Okunur/Yazılır [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getFontItalic() {#getFontItalic--}
```
public final byte getFontItalic()
```

Yazı tipinin italik olup olmadığını belirler. Kalıtım uygulanmaz. Okunur/Yazılır [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte

### setFontItalic(byte value) {#setFontItalic-byte-}
```
public final void setFontItalic(byte value)
```

Yazı tipinin italik olup olmadığını belirler. Kalıtım uygulanmaz. Okunur/Yazılır [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getKumimoji() {#getKumimoji--}
```
public final byte getKumimoji()
```

Numaraların, metnin doğu dili özgü dikey yerleşimini göz ardı edip etmeyeceğini belirler. Kalıtım uygulanmaz. Okunur/Yazılır [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte

### setKumimoji(byte value) {#setKumimoji-byte-}
```
public final void setKumimoji(byte value)
```

Numaraların, metnin doğu dili özgü dikey yerleşimini göz ardı edip etmeyeceğini belirler. Kalıtım uygulanmaz. Okunur/Yazılır [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getNormaliseHeight() {#getNormaliseHeight--}
```
public final byte getNormaliseHeight()
```

Metnin yüksekliğinin normalleştirilip normalleştirilmeyeceğini belirler. Kalıtım uygulanmaz. Okunur/Yazılır [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte

### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public final void setNormaliseHeight(byte value)
```

Metnin yüksekliğinin normalleştirilip normalleştirilmeyeceğini belirler. Kalıtım uygulanmaz. Okunur/Yazılır [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getProofDisabled() {#getProofDisabled--}
```
public final byte getProofDisabled()
```

Metnin denetlenmemesi gerektiğini belirler. Kalıtım uygulanmaz. Okunur/Yazılır [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte

### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public final void setProofDisabled(byte value)
```

Metnin denetlenmemesi gerektiğini belirler. Kalıtım uygulanmaz. Okunur/Yazılır [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getFontUnderline() {#getFontUnderline--}
```
public final byte getFontUnderline()
```

Metin alt çizgi tipini döndürür veya ayarlar. Kalıtım uygulanmaz. Okunur/Yazılır [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Döndürür:**
byte

### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public final void setFontUnderline(byte value)
```

Metin alt çizgi tipini döndürür veya ayarlar. Kalıtım uygulanmaz. Okunur/Yazılır [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getTextCapType() {#getTextCapType--}
```
public final byte getTextCapType()
```

Metin büyük harf tipini döndürür veya ayarlar. Kalıtım uygulanmaz. Okunur/Yazılır [TextCapType](../../com.aspose.slides/textcaptype).

**Döndürür:**
byte

### setTextCapType(byte value) {#setTextCapType-byte-}
```
public final void setTextCapType(byte value)
```

Metin büyük harf tipini döndürür veya ayarlar. Kalıtım uygulanmaz. Okunur/Yazılır [TextCapType](../../com.aspose.slides/textcaptype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getStrikethroughType() {#getStrikethroughType--}
```
public final byte getStrikethroughType()
```

Metnin üstü çizili tipini döndürür veya ayarlar. Kalıtım uygulanmaz. Okunur/Yazılır [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Döndürür:**
byte

### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public final void setStrikethroughType(byte value)
```

Metnin üstü çizili tipini döndürür veya ayarlar. Kalıtım uygulanmaz. Okunur/Yazılır [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public final byte isHardUnderlineLine()
```

Alt çizgi stilinin kendi LineFormat özelliklerine sahip olup olmadığını veya metnin LineFormat özelliklerinden miras alıp almadığını belirler. Okunur/Yazılır [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte

### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public final void setHardUnderlineLine(byte value)
```

Alt çizgi stilinin kendi LineFormat özelliklerine sahip olup olmadığını veya metnin LineFormat özelliklerinden miras alıp almadığını belirler. Okunur/Yazılır [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public final byte isHardUnderlineFill()
```

Alt çizgi stilinin kendi FillFormat özelliklerine sahip olup olmadığını veya metnin FillFormat özelliklerinden miras alıp almadığını belirler. Okunur/Yazılır [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte

### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public final void setHardUnderlineFill(byte value)
```

Alt çizgi stilinin kendi FillFormat özelliklerine sahip olup olmadığını veya metnin FillFormat özelliklerinden miras alıp almadığını belirler. Okunur/Yazılır [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getFontHeight() {#getFontHeight--}
```
public final float getFontHeight()
```

Bir bölümün yazı tipi yüksekliğini döndürür veya ayarlar. **Float.NaN** yükseklik tanımsızdır ve Master'dan miras alınmalıdır. Okunur/Yazılır  float .

**Döndürür:**
float

### setFontHeight(float value) {#setFontHeight-float-}
```
public final void setFontHeight(float value)
```

Bir bölümün yazı tipi yüksekliğini döndürür veya ayarlar. **Float.NaN** yükseklik tanımsızdır ve Master'dan miras alınmalıdır. Okunur/Yazılır  float .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getLatinFont() {#getLatinFont--}
```
public final IFontData getLatinFont()
```

Latin yazı tipi bilgilerini döndürür veya ayarlar. Null font tanımsızdır ve Master'dan miras alınmalıdır. Okunur/Yazılır [IFontData](../../com.aspose.slides/ifontdata).

**Döndürür:**
[IFontData](../../com.aspose.slides/ifontdata)

### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public final void setLatinFont(IFontData value)
```

Latin yazı tipi bilgilerini döndürür veya ayarlar. Null font tanımsızdır ve Master'dan miras alınmalıdır. Okunur/Yazılır [IFontData](../../com.aspose.slides/ifontdata).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public final IFontData getEastAsianFont()
```

Doğu Asya yazı tipi bilgilerini döndürür veya ayarlar. Null font tanımsızdır ve Master'dan miras alınmalıdır. Okunur/Yazılır [IFontData](../../com.aspose.slides/ifontdata).

**Döndürür:**
[IFontData](../../com.aspose.slides/ifontdata)

### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```

Doğu Asya yazı tipi bilgilerini döndürür veya ayarlar. Null font tanımsızdır ve Master'dan miras alınmalıdır. Okunur/Yazılır [IFontData](../../com.aspose.slides/ifontdata).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public final IFontData getComplexScriptFont()
```

Karmaşık betik (script) yazı tipi bilgilerini döndürür veya ayarlar. Null font tanımsızdır ve Master'dan miras alınmalıdır. Okunur/Yazılır [IFontData](../../com.aspose.slides/ifontdata).

**Döndürür:**
[IFontData](../../com.aspose.slides/ifontdata)

### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```

Karmaşık betik (script) yazı tipi bilgilerini döndürür veya ayarlar. Null font tanımsızdır ve Master'dan miras alınmalıdır. Okunur/Yazılır [IFontData](../../com.aspose.slides/ifontdata).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getSymbolFont() {#getSymbolFont--}
```
public final IFontData getSymbolFont()
```

Sembolik yazı tipi bilgilerini döndürür veya ayarlar. Null font tanımsızdır ve Master'dan miras alınmalıdır. Okunur/Yazılır [IFontData](../../com.aspose.slides/ifontdata).

**Döndürür:**
[IFontData](../../com.aspose.slides/ifontdata)

### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public final void setSymbolFont(IFontData value)
```

Sembolik yazı tipi bilgilerini döndürür veya ayarlar. Null font tanımsızdır ve Master'dan miras alınmalıdır. Okunur/Yazılır [IFontData](../../com.aspose.slides/ifontdata).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEscapement() {#getEscapement--}
```
public final float getEscapement()
```

Üst veya alt simge (superscript/subscript) metnini döndürür veya ayarlar. -100% (alt simge) ile 100% (üst simge) arasında değer. **Float.NaN** değer tanımsızdır ve Master'dan miras alınmalıdır. Okunur/Yazılır  float .

**Döndürür:**
float

### setEscapement(float value) {#setEscapement-float-}
```
public final void setEscapement(float value)
```

Üst veya alt simge (superscript/subscript) metnini döndürür veya ayarlar. -100% (alt simge) ile 100% (üst simge) arasında değer. **Float.NaN** değer tanımsızdır ve Master'dan miras alınmalıdır. Okunur/Yazılır  float .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public final float getKerningMinimalSize()
```

Kerning'in etkinleştirileceği en düşük yazı tipi boyutunu döndürür veya ayarlar. **Float.NaN** değer tanımsızdır ve Master'dan miras alınmalıdır. Okunur/Yazılır  float .

**Döndürür:**
float

### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public final void setKerningMinimalSize(float value)
```

Kerning'in etkinleştirileceği en düşük yazı tipi boyutunu döndürür veya ayarlar. **Float.NaN** değer tanımsızdır ve Master'dan miras alınmalıdır. Okunur/Yazılır  float .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getLanguageId() {#getLanguageId--}
```
public final String getLanguageId()
```

Denetleme dilinin kimliğini (Id) döndürür veya ayarlar. İmla ve dilbilgisi denetimi için kullanılır. Okunur/Yazılır String.

**Döndürür:**
java.lang.String

### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public final void setLanguageId(String value)
```

Denetleme dilinin kimliğini (Id) döndürür veya ayarlar. İmla ve dilbilgisi denetimi için kullanılır. Okunur/Yazılır String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public final String getAlternativeLanguageId()
```

Alternatif bir dilin kimliğini (Id) döndürür veya ayarlar. Okunur/Yazılır String.

**Döndürür:**
java.lang.String

### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public final void setAlternativeLanguageId(String value)
```

Alternatif bir dilin kimliğini (Id) döndürür veya ayarlar. Okunur/Yazılır String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getSpacing() {#getSpacing--}
```
public final float getSpacing()
```

Karakterler arası boşluk artışını döndürür veya ayarlar. **Float.NaN** değer tanımsızdır ve Master'dan miras alınmalıdır. Okunur/Yazılır  float .

**Döndürür:**
float

### setSpacing(float value) {#setSpacing-float-}
```
public final void setSpacing(float value)
```

Karakterler arası boşluk artışını döndürür veya ayarlar. **Float.NaN** değer tanımsızdır ve Master'dan miras alınmalıdır. Okunur/Yazılır  float .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getSpellCheck() {#getSpellCheck--}
```
public final boolean getSpellCheck()
```

Metin bölümü için yazım denetiminin etkin olup olmadığını gösteren bir değeri alır veya ayarlar. Bu özellik false olduğunda metin öğeleri için yazım denetimi engellenir. True olduğunda yazım denetimine izin verilir. Varsayılan değer false .

**Döndürür:**
boolean

### setSpellCheck(boolean value) {#setSpellCheck-boolean-}
```
public final void setSpellCheck(boolean value)
```

Metin bölümü için yazım denetiminin etkin olup olmadığını gösteren bir değeri alır veya ayarlar. Bu özellik false olduğunda metin öğeleri için yazım denetimi engellenir. True olduğunda yazım denetimine izin verilir. Varsayılan değer false .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

---  

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // İlk slayttaki ilk şekil içinde bulunan ilk metin bölümüne erişim
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

---  

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

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |