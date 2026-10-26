---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Base interface for immutable objects which contain effective text portion formatting properties.
type: docs
url: /tr/com.aspose.slides/ibaseportionformateffectivedata/
---```
public interface IBasePortionFormatEffectiveData
```

Etkili metin bölümü biçimlendirme özelliklerini içeren değiştirilemez nesneler için temel arayüz.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | Metin kontur için LineFormat özelliklerini döndürür. |
| [getFillFormat()](#getFillFormat--) | Metin FillFormat özelliklerini döndürür. |
| [getEffectFormat()](#getEffectFormat--) | Metin EffectFormat özelliklerini döndürür. |
| [getHighlightColor()](#getHighlightColor--) | Metni vurgulamak için kullanılan rengi döndürür. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | Alt çizgi hattını konturlamak için kullanılan LineFormat özelliklerini döndürür. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | Alt çizgi hattının FillFormat özelliklerini döndürür. |
| [getFontBold()](#getFontBold--) | Yazı tipinin kalın olup olmadığını belirler. |
| [getFontItalic()](#getFontItalic--) | Yazı tipinin italik olup olmadığını belirler. |
| [getKumimoji()](#getKumimoji--) | Sayının, metnin Doğu Asya diline özgü dikey metin düzenini ihmal edip etmeyeceğini belirler. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Metnin yüksekliğinin normalleştirilip normalleştirilmeyeceğini belirler. |
| [getProofDisabled()](#getProofDisabled--) | Metnin denetlenip denetlenmeyeceğini belirler. |
| [getFontUnderline()](#getFontUnderline--) | Metin alt çizgi tipini döndürür. |
| [getTextCapType()](#getTextCapType--) | Metin büyük harf kullanım tipini döndürür. |
| [getStrikethroughType()](#getStrikethroughType--) | Metnin üstü çizili tipini döndürür. |
| [getSmartTagClean()](#getSmartTagClean--) | Akıllı etiketin temizlenip temizlenmeyeceğini belirler. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Alt çizgi stilinin kendi LineFormat özelliklerine sahip olup olmadığını ya da metnin LineFormat özelliklerinden devralınıp devralınmadığını belirler. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Alt çizgi stilinin kendi FillFormat özelliklerine sahip olup olmadığını ya da metnin FillFormat özelliklerinden devralınıp devralınmadığını belirler. |
| [getFontHeight()](#getFontHeight--) | Metin bölümünün punto cinsinden yazı tipi yüksekliğini döndürür. |
| [getLatinFont()](#getLatinFont--) | Latin yazı tipi bilgisini döndürür. |
| [getEastAsianFont()](#getEastAsianFont--) | Doğu Asya yazı tipi bilgisini döndürür. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Karmaşık betik yazı tipi bilgisini döndürür. |
| [getSymbolFont()](#getSymbolFont--) | Sembolik yazı tipi bilgisini döndürür. |
| [getEscapement()](#getEscapement--) | Üst simge ya da alt simge metnini döndürür. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | Kerningi etkinleştirmek için gereken asgari yazı tipi boyutunu döndürür. |
| [getLanguageId()](#getLanguageId--) | Bir dilin kimliğini döndürür. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | Alternatif bir dilin kimliğini döndürür. |
| [getSpacing()](#getSpacing--) | Karakterler arası boşluk artışını, punto cinsinden döndürür. |
### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormatEffectiveData getLineFormat()
```


Metin kontur için LineFormat özelliklerini döndürür. Yalnızca okunabilir [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).

**Döndürür:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```


Metin FillFormat özelliklerini döndürür. Yalnızca okunabilir [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**Döndürür:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormatEffectiveData getEffectFormat()
```


Metin EffectFormat özelliklerini döndürür. Yalnızca okunabilir [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).

**Döndürür:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata)
### getHighlightColor() {#getHighlightColor--}
```
public abstract Color getHighlightColor()
```


Metni vurgulamak için kullanılan rengi döndürür. Yalnızca okunabilir java.awt.Color.

**Döndürür:**
java.awt.Color
### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormatEffectiveData getUnderlineLineFormat()
```


Alt çizgi hattını konturlamak için kullanılan LineFormat özelliklerini döndürür. Yalnızca okunabilir [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).

**Döndürür:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)
### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormatEffectiveData getUnderlineFillFormat()
```


Alt çizgi hattının FillFormat özelliklerini döndürür. Yalnızca okunabilir [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**Döndürür:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getFontBold() {#getFontBold--}
```
public abstract boolean getFontBold()
```


Yazı tipinin kalın olup olmadığını belirler. Yalnızca okunabilir boolean.

**Döndürür:**
boolean
### getFontItalic() {#getFontItalic--}
```
public abstract boolean getFontItalic()
```


Yazı tipinin italik olup olmadığını belirler. Yalnızca okunabilir boolean.

**Döndürür:**
boolean
### getKumimoji() {#getKumimoji--}
```
public abstract boolean getKumimoji()
```


Sayının, metnin Doğu Asya diline özgü dikey metin düzenini ihmal edip etmeyeceğini belirler. Yalnızca okunabilir boolean.

**Döndürür:**
boolean
### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract boolean getNormaliseHeight()
```


Metnin yüksekliğinin normalleştirilip normalleştirilmeyeceğini belirler. Yalnızca okunabilir boolean.

**Döndürür:**
boolean
### getProofDisabled() {#getProofDisabled--}
```
public abstract boolean getProofDisabled()
```


Metnin denetlenip denetlenmeyeceğini belirler. Yalnızca okunabilir boolean.

**Döndürür:**
boolean
### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```


Metin alt çizgi tipini döndürür. Yalnızca okunabilir [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Döndürür:**
byte
### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```


Metin büyük harf kullanım tipini döndürür. Yalnızca okunabilir [TextCapType](../../com.aspose.slides/textcaptype).

**Döndürür:**
byte
### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```


Metnin üstü çizili tipini döndürür. Yalnızca okunabilir [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Döndürür:**
byte
### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```


Akıllı etiketin temizlenip temizlenmeyeceğini belirler. Yalnızca okunabilir boolean.

**Döndürür:**
boolean
### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract boolean isHardUnderlineLine()
```


Alt çizgi stilinin kendi LineFormat özelliklerine sahip olup olmadığını ya da metnin LineFormat özelliklerinden devralınıp devralınmadığını belirler. Yalnızca okunabilir boolean.

**Döndürür:**
boolean
### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract boolean isHardUnderlineFill()
```


Alt çizgi stilinin kendi FillFormat özelliklerine sahip olup olmadığını ya da metnin FillFormat özelliklerinden devralınıp devralınmadığını belirler. Yalnızca okunabilir boolean.

**Döndürür:**
boolean
### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```


Metin bölümünün punto cinsinden yazı tipi yüksekliğini döndürür. Yalnızca okunabilir float.

**Döndürür:**
float
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```


Latin yazı tipi bilgisini döndürür. Yalnızca okunabilir [IFontData](../../com.aspose.slides/ifontdata).

**Döndürür:**
[IFontData](../../com.aspose.slides/ifontdata)
### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```


Doğu Asya yazı tipi bilgisini döndürür. Yalnızca okunabilir [IFontData](../../com.aspose.slides/ifontdata).

**Döndürür:**
[IFontData](../../com.aspose.slides/ifontdata)
### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```


Karmaşık betik yazı tipi bilgisini döndürür. Yalnızca okunabilir [IFontData](../../com.aspose.slides/ifontdata).

**Döndürür:**
[IFontData](../../com.aspose.slides/ifontdata)
### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```


Sembolik yazı tipi bilgisini döndürür. Yalnızca okunabilir [IFontData](../../com.aspose.slides/ifontdata).

**Döndürür:**
[IFontData](../../com.aspose.slides/ifontdata)
### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```


Üst simge ya da alt simge metnini döndürür. Değer -100% (alt simge) ile 100% (üst simge) arasında. Yalnızca okunabilir float.

**Döndürür:**
float
### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```


Kerningi etkinleştirmek için gereken asgari yazı tipi boyutunu döndürür. Yalnızca okunabilir float.

**Döndürür:**
float
### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```


Bir dilin kimliğini döndürür. Yalnızca okunabilir String.

**Döndürür:**
java.lang.String
### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```


Alternatif bir dilin kimliğini döndürür. Yalnızca okunabilir String.

**Döndürür:**
java.lang.String
### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```


Karakterler arası boşluk artışını, punto cinsinden döndürür. Yalnızca okunabilir float.

**Döndürür:**
float