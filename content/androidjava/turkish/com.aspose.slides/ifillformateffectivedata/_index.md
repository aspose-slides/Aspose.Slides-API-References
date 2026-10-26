---
title: IFillFormatEffectiveData
second_title: Aspose.Slides for Android, Java API Referansı aracılığıyla
description: Etkin dolgu biçimlendirme özelliklerini içeren değiştirilemez nesne.
type: docs
url: /tr/com.aspose.slides/ifillformateffectivedata/
---
**Tüm Gerçekleştirilen Arayüzler:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormatEffectiveData extends IFillParamSource
```

Etkin dolgu biçimlendirme özelliklerini içeren değiştirilemez nesne.

--------------------

Bu arayüz, [IFillFormat](../../com.aspose.slides/ifillformat) arayüzüyle birlikte, kalıtım uygulanmış etkili biçimlendirme değerlerini döndürmek için kullanılır.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getFillType()](#getFillType--) | Dolgu tipini döndürür. |
| [getSolidFillColor()](#getSolidFillColor--) | Dolgu rengini döndürür. |
| [getSolidFillSchemeColor()](#getSolidFillSchemeColor--) | Renk şeması tarafından tanımlanan dolgu rengini alır. |
| [getGradientFormat()](#getGradientFormat--) | Gradient dolgu biçimini döndürür. |
| [getPatternFormat()](#getPatternFormat--) | Desen dolgu biçimini döndürür. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Resim dolgu biçimini döndürür. |
| [getRotateWithShape()](#getRotateWithShape--) | Dolgunun şekil ile birlikte döndürülüp döndürülmeyeceğini belirler. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


Dolgu tipini döndürür. Salt okunur [FillType](../../com.aspose.slides/filltype).

**Döndürür:**
byte
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Integer getSolidFillColor()
```


Dolgu rengini döndürür. Salt okunur java.lang.Integer.

**Döndürür:**
java.lang.Integer
### getSolidFillSchemeColor() {#getSolidFillSchemeColor--}
```
public abstract int getSolidFillSchemeColor()
```


Renk şeması tarafından tanımlanan dolgu rengini alır. [SchemeColor.NotDefined](../../com.aspose.slides/schemecolor\#NotDefined) değeri, SolidFillColor (\#getSolidFillColor.getSolidFillColor) değerinin bir şema rengi olmadığını gösterir. Salt okunur [SchemeColor](../../com.aspose.slides/schemecolor).

**Döndürür:**
int
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```


Gradient dolgu biçimini döndürür. Salt okunur [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata).

**Döndürür:**
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```


Desen dolgu biçimini döndürür. Salt okunur [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata).

**Döndürür:**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPPictureFillFormatEffectiveData getPictureFillFormat()
```


Resim dolgu biçimini döndürür. Salt okunur [IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata).

**Döndürür:**
[IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```


Dolgunun şekil ile birlikte döndürülüp döndürülmeyeceğini belirler. Salt okunur boolean.

**Döndürür:**
boolean