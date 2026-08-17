---
title: IFillFormatEffectiveData
second_title: Aspose.Slides for Java API Referansı
description: Etkili dolgu biçimlendirme özelliklerini içeren değişmez nesne.
type: docs
url: /tr/com.aspose.slides/ifillformateffectivedata/
---
**Tüm Gerçekleştirilen Arayüzler:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormatEffectiveData extends IFillParamSource
```

Etkili dolgu biçimlendirme özelliklerini içeren değişmez nesne.

--------------------

Bu arayüz, [IFillFormat](../../com.aspose.slides/ifillformat) arayüzü ile birlikte, kalıtım uygulanmış etkili biçimlendirme değerlerini döndürmek için kullanılır.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFillType()](#getFillType--) | Dolgu tipini döndürür. |
| [getSolidFillColor()](#getSolidFillColor--) | Dolgu rengini döndürür. |
| [getSolidFillSchemeColor()](#getSolidFillSchemeColor--) | Renk şeması tarafından tanımlanan dolgu rengini alır. |
| [getGradientFormat()](#getGradientFormat--) | Gradyan dolgu biçimini döndürür. |
| [getPatternFormat()](#getPatternFormat--) | Desen dolgu biçimini döndürür. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Resim dolgu biçimini döndürür. |
| [getRotateWithShape()](#getRotateWithShape--) | Dolgunun şekil ile birlikte döndürülüp döndürülmeyeceğini belirler. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


Dolgu tipini döndürür. Yalnızca okuma [FillType](../../com.aspose.slides/filltype).

**Döndürür:**
byte
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Color getSolidFillColor()
```


Dolgu rengini döndürür. Yalnızca okuma java.awt.Color.

**Döndürür:**
java.awt.Color
### getSolidFillSchemeColor() {#getSolidFillSchemeColor--}
```
public abstract int getSolidFillSchemeColor()
```


Renk şeması tarafından tanımlanan dolgu rengini alır. [SchemeColor.NotDefined](../../com.aspose.slides/schemecolor\#NotDefined) değeri, SolidFillColor (\#getSolidFillColor.getSolidFillColor) değerinin bir şema rengi olmadığını gösterir. Yalnızca okuma [SchemeColor](../../com.aspose.slides/schemecolor).

**Döndürür:**
int
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```


Gradyan dolgu biçimini döndürür. Yalnızca okuma [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata).

**Döndürür:**
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```


Desen dolgu biçimini döndürür. Yalnızca okuma [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata).

**Döndürür:**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormatEffectiveData getPictureFillFormat()
```


Resim dolgu biçimini döndürür. Yalnızca okuma [IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata).

**Döndürür:**
[IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```


Dolgunun şekil ile birlikte döndürülüp döndürülmeyeceğini belirler. Yalnızca okuma boolean.

**Döndürür:**
boolean