---
title: BasePortionFormat
second_title: Aspose.Slides for Android üzerinden Java API Referansı
description: Ortak metin bölümü biçimlendirme özellikleri.
type: docs
url: /tr/com.aspose.slides/baseportionformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat)
```
public abstract class BasePortionFormat extends PVIObject implements IBasePortionFormat
```

Ortak metin bölümü biçimlendirme özellikleri.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getLineFormat()](#getLineFormat--) | Metin ana hatları için LineFormat özelliklerini döndürür. |
| [getFillFormat()](#getFillFormat--) | Metin FillFormat özelliklerini döndürür. |
| [getEffectFormat()](#getEffectFormat--) | Metin EffectFormat özelliklerini döndürür. |
| [getHighlightColor()](#getHighlightColor--) | Metni vurgulamak için kullanılan rengi döndürür. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | Alt çizgi hattını ana hatlamak için kullanılan LineFormat özelliklerini döndürür. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | Alt çizgi hattının FillFormat özelliklerini döndürür. |
| [getFontBold()](#getFontBold--) | Yazı tipinin kalın olup olmadığını belirler. |
| [setFontBold(byte value)](#setFontBold-byte-) | Yazı tipinin kalın olup olmadığını belirler. |
| [getFontItalic()](#getFontItalic--) | Yazı tipinin italik olup olmadığını belirler. |
| [setFontItalic(byte value)](#setFontItalic-byte-) | Yazı tipinin italik olup olmadığını belirler. |
| [getKumimoji()](#getKumimoji--) | Sayıların, metnin doğu diline özgü dikey metin düzenini göz ardı edip etmeyeceğini belirler. |
| [setKumimoji(byte value)](#setKumimoji-byte-) | Sayıların, metnin doğu diline özgü dikey metin düzenini göz ardı edip etmeyeceğini belirler. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Metnin yüksekliğinin normalize edilip edilmeyeceğini belirler. |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | Metnin yüksekliğinin normalize edilip edilmeyeceğini belirler. |
| [getProofDisabled()](#getProofDisabled--) | Metnin denetlenmemesi gerekip gerekmediğini belirler. |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | Metnin denetlenmemesi gerekip gerekmediğini belirler. |
| [getFontUnderline()](#getFontUnderline--) | Metin alt çizgi tipini döndürür veya ayarlar. |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | Metin alt çizgi tipini döndürür veya ayarlar. |
| [getTextCapType()](#getTextCapType--) | Metin büyük harf kullanım tipini döndürür veya ayarlar. |
| [setTextCapType(byte value)](#setTextCapType-byte-) | Metin büyük harf kullanım tipini döndürür veya ayarlar. |
| [getStrikethroughType()](#getStrikethroughType--) | Metin üstü çizili tipini döndürür veya ayarlar. |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | Metin üstü çizili tipini döndürür veya ayarlar. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Alt çizgi stilinin kendi LineFormat özelliklerine sahip olup metnin LineFormat özelliklerinden devralınıp devralınmadığını belirler. |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | Alt çizgi stilinin kendi LineFormat özelliklerine sahip olup metnin LineFormat özelliklerinden devralınıp devralınmadığını belirler. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Alt çizgi stilinin kendi FillFormat özelliklerine sahip olup metnin FillFormat özelliklerinden devralınıp devralınmadığını belirler. |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | Alt çizgi stilinin kendi FillFormat özelliklerine sahip olup metnin FillFormat özelliklerinden devralınıp devralınmadığını belirler. |
| [getFontHeight()](#getFontHeight--) | Bir bölümün yazı tipi yüksekliğini döndürür veya ayarlar. |
| [setFontHeight(float value)](#setFontHeight-float-) | Bir bölümün yazı tipi yüksekliğini döndürür veya ayarlar. |
| [getLatinFont()](#getLatinFont--) | Latin yazı tipi bilgisini döndürür veya ayarlar. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Latin yazı tipi bilgisini döndürür veya ayarlar. |
| [getEastAsianFont()](#getEastAsianFont--) | Doğu Asya yazı tipi bilgisini döndürür veya ayarlar. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Doğu Asya yazı tipi bilgisini döndürür veya ayarlar. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Kompleks betik yazı tipi bilgisini döndürür veya ayarlar. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Kompleks betik yazı tipi bilgisini döndürür veya ayarlar. |
| [getSymbolFont()](#getSymbolFont--) | Sembolik yazı tipi bilgisini döndürür veya ayarlar. |
| [setSymbolFont(IFontData value)](#setSymbolFont-com.aspose.slides.IFontData-) | Sembolik yazı tipi bilgisini döndürür veya ayarlar. |
| [getEscapement()](#getEscapement--) | Üst ya da alt simge metnini döndürür veya ayarlar. |
| [setEscapement(float value)](#setEscapement-float-) | Üst ya da alt simge metnini döndürür veya ayarlar. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | Kerning'in etkinleştirileceği minimum yazı tipi boyutunu döndürür veya ayarlar. |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | Kerning'in etkinleştirileceği minimum yazı tipi boyutunu döndürür veya ayarlar. |
| [getLanguageId()](#getLanguageId--) | Denetleme dilinin kimliğini döndürür veya ayarlar. |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | Denetleme dilinin kimliğini döndürür veya ayarlar. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | Alternatif dilin kimliğini döndürür veya ayarlar. |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | Alternatif dilin kimliğini döndürür veya ayarlar. |
| [getSpacing()](#getSpacing--) | Karakterler arası boşluk artışını döndürür veya ayarlar. |
| [setSpacing(float value)](#setSpacing-float-) | Karakterler arası boşluk artışını döndürür veya ayarlar. |
| [getSpellCheck()](#getSpellCheck--) | Metin bölümü için yazım denetiminin etkin olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | Metin bölümü için yazım denetiminin etkin olup olmadığını gösteren bir değeri alır veya ayarlar. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Sürüm. Salt okunur long.

**Döndürür:**
long

### getLineFormat() {#getLineFormat--}
```
public final ILineFormat getLineFormat()
```

Metin ana hatları için LineFormat özelliklerini döndürür. Kalıtım uygulanmaz. Salt okunur [ILineFormat](../../com.aspose.slides/ilineformat).

**Döndürür:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

Metin FillFormat özelliklerini döndürür. Kalıtım uygulanmaz. Salt okunur [IFillFormat](../../com.aspose.slides/ifillformat).

**Döndürür:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getEffectFormat() {#getEffectFormat--}
```
public final IEffectFormat getEffectFormat()
```

Metin EffectFormat özelliklerini döndürür. Kalıtım uygulanmaz. Salt okunur [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Döndürür:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getHighlightColor() {#getHighlightColor--}
```
public final IColorFormat getHighlightColor()
```

Metni vurgulamak için kullanılan rengi döndürür. Kalıtım uygulanmaz. Salt okunur [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public final ILineFormat getUnderlineLineFormat()
```

Alt çizgi hattını ana hatlamak için kullanılan LineFormat özelliklerini döndürür. Kalıtım uygulanmaz. Salt okunur [ILineFormat](../../com.aspose.slides/ilineformat).

**Döndürür:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public final IFillFormat getUnderlineFillFormat()
```

Alt çizgi hattının FillFormat özelliklerini döndürür. Kalıtım uygulanmaz. Salt okunur [IFillFormat](../../com.aspose.slides/ifillformat).

**Döndürür:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getFontBold() {#getFontBold--}
```
public final byte getFontBold()
```

Yazı tipinin kalın olup olmadığını belirler. Kalıtım uygulanmaz. Okunur/yazılabilir [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte

### setFontBold(byte value) {#setFontBold-byte-}
```
public final void setFontBold(byte value)
```

Yazı tipinin kalın olup olmadığını belirler. Kalıtım uygulanmaz. Okunur/yazılabilir [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getFontItalic() {#getFontItalic--}
```
public final byte getFontItalic()
```

Yazı tipinin italik olup olmadığını belirler. Kalıtım uygulanmaz. Okunur/yazılabilir [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte

### setFontItalic(byte value) {#setFontItalic-byte-}
```
public final void setFontItalic(byte value)
```

Yazı tipinin italik olup olmadığını belirler. Kalıtım uygulanmaz. Okunur/yazılabilir [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getKumimoji() {#getKumimoji--}
```
public final byte getKumimoji()
```

Sayıların, metnin doğu diline özgü dikey metin düzenini göz ardı edip etmeyeceğini belirler. Kalıtım uygulanmaz. Okunur/yazılabilir [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte

### setKumimoji(byte value) {#setKumimoji-byte-}
```
public final void setKumimoji(byte value)
```

Sayıların, metnin doğu diline özgü dikey metin düzenini göz ardı edip etmeyeceğini belirler. Kalıtım uygulanmaz. Okunur/yazılabilir [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getNormaliseHeight() {#getNormaliseHeight--}
```
public final byte getNormaliseHeight()
```

Metnin yüksekliğinin normalize edilip edilmeyeceğini belirler. Kalıtım uygulanmaz. Okunur/yazılabilir [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte

### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public final void setNormaliseHeight(byte value)
```

Metnin yüksekliğinin normalize edilip edilmeyeceğini belirler. Kalıtım uygulanmaz. Okunur/yazılabilir [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getProofDisabled() {#getProofDisabled--}
```
public final byte getProofDisabled()
```

Metnin denetlenmemesi gerekip gerekmediğini belirler. Kalıtım uygulanmaz. Okunur/yazılabilir [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte

### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public final void setProofDisabled(byte value)
```

Metnin denetlenmemesi gerekip gerekmediğini belirler. Kalıtım uygulanmaz. Okunur/yazılabilir [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getFontUnderline() {#getFontUnderline--}
```
public final byte getFontUnderline()
```

Metin alt çizgi tipini döndürür veya ayarlar. Kalıtım uygulanmaz. Okunur/yazılabilir [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Döndürür:**
byte

### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public final void setFontUnderline(byte value)
```

Metin alt çizgi tipini döndürür veya ayarlar. Kalıtım uygulanmaz. Okunur/yazılabilir [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getTextCapType() {#getTextCapType--}
```
public final byte getTextCapType()
```

Metin büyük harf kullanım tipini döndürür veya ayarlar. Kalıtım uygulanmaz. Okunur/yazılabilir [TextCapType](../../com.aspose.slides/textcaptype).

**Döndürür:**
byte

### setTextCapType(byte value) {#setTextCapType-byte-}
```
public final void setTextCapType(byte value)
```

Metin büyük harf kullanım tipini döndürür veya ayarlar. Kalıtım uygulanmaz. Okunur/yazılabilir [TextCapType](../../com.aspose.slides/textcaptype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getStrikethroughType() {#getStrikethroughType--}
```
public final byte getStrikethroughType()
```

Metin üstü çizili tipini döndürür veya ayarlar. Kalıtım uygulanmaz. Okunur/yazılabilir [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Döndürür:**
byte

### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public final void setStrikethroughType(byte value)
```

Metin üstü çizili tipini döndürür veya ayarlar. Kalıtım uygulanmaz. Okunur/yazılabilir [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public final byte isHardUnderlineLine()
```

Alt çizgi stilinin kendi LineFormat özelliklerine sahip olup metnin LineFormat özelliklerinden devralınıp devralınmadığını belirler. Okunur/yazılabilir [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte

### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public final void setHardUnderlineLine(byte value)
```

Alt çizgi stilinin kendi LineFormat özelliklerine sahip olup metnin LineFormat özelliklerinden devralınıp devralınmadığını belirler. Okunur/yazılabilir [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public final byte isHardUnderlineFill()
```

Alt çizgi stilinin kendi FillFormat özelliklerine sahip olup metnin FillFormat özelliklerinden devralınıp devralınmadığını belirler. Okunur/yazılabilir [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte

### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public final void setHardUnderlineFill(byte value)
```

Alt çizgi stilinin kendi FillFormat özelliklerine sahip olup metnin FillFormat özelliklerinden devralınıp devralınmadığını belirler. Okunur/yazılabilir [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getFontHeight() {#getFontHeight--}
```
public final float getFontHeight()
```

Bir bölümün yazı tipi yüksekliğini döndürür veya ayarlar. **Float.NaN** yüksekliğin tanımsız olduğunu ve Master'dan devralınması gerektiğini gösterir. Okunur/yazılabilir  float .

**Döndürür:**
float

### setFontHeight(float value) {#setFontHeight-float-}
```
public final void setFontHeight(float value)
```

Bir bölümün yazı tipi yüksekliğini döndürür veya ayarlar. **Float.NaN** yüksekliğin tanımsız olduğunu ve Master'dan devralınması gerektiğini gösterir. Okunur/yazılabilir  float .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getLatinFont() {#getLatinFont--}
```
public final IFontData getLatinFont()
```

Latin yazı tipi bilgisini döndürür veya ayarlar. Null, yazı tipinin tanımsız olduğunu ve Master'dan devralınması gerektiğini gösterir. Okunur/yazılabilir [IFontData](../../com.aspose.slides/ifontdata).

**Döndürür:**
[IFontData](../../com.aspose.slides/ifontdata)

### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public final void setLatinFont(IFontData value)
```

Latin yazı tipi bilgisini döndürür veya ayarlar. Null, yazı tipinin tanımsız olduğunu ve Master'dan devralınması gerektiğini gösterir. Okunur/yazılabilir [IFontData](../../com.aspose.slides/ifontdata).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public final IFontData getEastAsianFont()
```

Doğu Asya yazı tipi bilgisini döndürür veya ayarlar. Null, yazı tipinin tanımsız olduğunu ve Master'dan devralınması gerektiğini gösterir. Okunur/yazılabilir [IFontData](../../com.aspose.slides/ifontdata).

**Döndürür:**
[IFontData](../../com.aspose.slides/ifontdata)

### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```

Doğu Asya yazı tipi bilgisini döndürür veya ayarlar. Null, yazı tipinin tanımsız olduğunu ve Master'dan devralınması gerektiğini gösterir. Okunur/yazılabilir [IFontData](../../com.aspose.slides/ifontdata).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public final IFontData getComplexScriptFont()
```

Kompleks betik yazı tipi bilgisini döndürür veya ayarlar. Null, yazı tipinin tanımsız olduğunu ve Master'dan devralınması gerektiğini gösterir. Okunur/yazılabilir [IFontData](../../com.aspose.slides/ifontdata).

**Döndürür:**
[IFontData](../../com.aspose.slides/ifontdata)

### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```

Kompleks betik yazı tipi bilgisini döndürür veya ayarlar. Null, yazı tipinin tanımsız olduğunu ve Master'dan devralınması gerektiğini gösterir. Okunur/yazılabilir [IFontData](../../com.aspose.slides/ifontdata).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getSymbolFont() {#getSymbolFont--}
```
public final IFontData getSymbolFont()
```

Sembolik yazı tipi bilgisini döndürür veya ayarlar. Null, yazı tipinin tanımsız olduğunu ve Master'dan devralınması gerektiğini gösterir. Okunur/yazılabilir [IFontData](../../com.aspose.slides/ifontdata).

**Döndürür:**
[IFontData](../../com.aspose.slides/ifontdata)

### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public final void setSymbolFont(IFontData value)
```

Sembolik yazı tipi bilgisini döndürür veya ayarlar. Null, yazı tipinin tanımsız olduğunu ve Master'dan devralınması gerektiğini gösterir. Okunur/yazılabilir [IFontData](../../com.aspose.slides/ifontdata).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEscapement() {#getEscapement--}
```
public final float getEscapement()
```

Üst ya da alt simge metnini döndürür veya ayarlar. -100% (alt simge) ile 100% (üst simge) arasında değer alır. **Float.NaN** değerin tanımsız olduğunu ve Master'dan devralınması gerektiğini gösterir. Okunur/yazılabilir  float .

**Döndürür:**
float

### setEscapement(float value) {#setEscapement-float-}
```
public final void setEscapement(float value)
```

Üst ya da alt simge metnini döndürür veya ayarlar. -100% (alt simge) ile 100% (üst simge) arasında değer alır. **Float.NaN** değerin tanımsız olduğunu ve Master'dan devralınması gerektiğini gösterir. Okunur/yazılabilir  float .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public final float getKerningMinimalSize()
```

Kerning'in etkinleştirileceği minimum yazı tipi boyutunu döndürür veya ayarlar. **Float.NaN** değerin tanımsız olduğunu ve Master'dan devralınması gerektiğini gösterir. Okunur/yazılabilir  float .

**Döndürür:**
float

### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public final void setKerningMinimalSize(float value)
```

Kerning'in etkinleştirileceği minimum yazı tipi boyutunu döndürür veya ayarlar. **Float.NaN** değerin tanımsız olduğunu ve Master'dan devralınması gerektiğini gösterir. Okunur/yazılabilir  float .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getLanguageId() {#getLanguageId--}
```
public final String getLanguageId()
```

Denetleme dilinin kimliğini döndürür veya ayarlar. Yazım ve dilbilgisi denetimi için kullanılır. Okunur/yazılabilir String.

**Döndürür:**
java.lang.String

### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public final void setLanguageId(String value)
```

Denetleme dilinin kimliğini döndürür veya ayarlar. Yazım ve dilbilgisi denetimi için kullanılır. Okunur/yazılabilir String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public final String getAlternativeLanguageId()
```

Alternatif dilin kimliğini döndürür veya ayarlar. Okunur/yazılabilir String.

**Döndürür:**
java.lang.String

### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public final void setAlternativeLanguageId(String value)
```

Alternatif dilin kimliğini döndürür veya ayarlar. Okunur/yazılabilir String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getSpacing() {#getSpacing--}
```
public final float getSpacing()
```

Karakterler arası boşluk artışını döndürür veya ayarlar. **Float.NaN** değerin tanımsız olduğunu ve Master'dan devralınması gerektiğini gösterir. Okunur/yazılabilir  float .

**Döndürür:**
float

### setSpacing(float value) {#setSpacing-float-}
```
public final void setSpacing(float value)
```

Karakterler arası boşluk artışını döndürür veya ayarlar. **Float.NaN** değerin tanımsız olduğunu ve Master'dan devralınması gerektiğini gösterir. Okunur/yazılabilir  float .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getSpellCheck() {#getSpellCheck--}
```
public final boolean getSpellCheck()
```

Metin bölümü için yazım denetiminin etkin olup olmadığını gösteren bir değeri alır veya ayarlar. Bu özellik false olarak ayarlandığında, metin öğeleri için yazım denetimi bastırılır. true olarak ayarlandığında, yazım denetimine izin verilir. Varsayılan değer false'tur.

--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // İlk slayttaki ilk şeklin içindeki ilk metin bölümüne erişir
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

### setSpellCheck(boolean value) {#setSpellCheck-boolean-}
```
public final void setSpellCheck(boolean value)
```

Metin bölümü için yazım denetiminin etkin olup olmadığını gösteren bir değeri alır veya ayarlar. Bu özellik false olarak ayarlandığında, metin öğeleri için yazım denetimi bastırılır. true olarak ayarlandığında, yazım denetimine izin verilir. Varsayılan değer false'tur.

--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // İlk slayttaki ilk şeklin içindeki ilk metin bölümüne erişir
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |