---
title: IFillFormat
second_title: Aspose.Slides for Android Java API Referansı
description: Dolgu biçimlendirme seçeneklerini temsil eder.
type: docs
url: /tr/com.aspose.slides/ifillformat/
---
**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormat extends IFillParamSource
```

Dolgu biçimlendirme seçeneklerini temsil eder.
## Yöntemler

| Metot | Açıklama |
| --- | --- |
| [getFillType()](#getFillType--) | Returns or sets the type of filling. |
| [setFillType(byte value)](#setFillType-byte-) | Returns or sets the type of filling. |
| [getSolidFillColor()](#getSolidFillColor--) | Returns the fill color. |
| [getGradientFormat()](#getGradientFormat--) | Returns the gradient fill format. |
| [getPatternFormat()](#getPatternFormat--) | Returns the pattern fill format. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Returns the picture fill format. |
| [getRotateWithShape()](#getRotateWithShape--) | Determines whether the fill should be rotated with shape. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Determines whether the fill should be rotated with shape. |
| [getEffective()](#getEffective--) | Gets effective fill formatting data with the inheritance applied. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


Dolgu tipini döndürür veya ayarlar. Okunur/Yazılır [FillType](../../com.aspose.slides/filltype).

**Döndürür:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public abstract void setFillType(byte value)
```


Dolgu tipini döndürür veya ayarlar. Okunur/Yazılır [FillType](../../com.aspose.slides/filltype).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getSolidFillColor() {#getSolidFillColor--}
```
public abstract IColorFormat getSolidFillColor()
```


Dolgu rengini döndürür. Sadece Okunur [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormat getGradientFormat()
```


Gradyan dolgu biçimini döndürür. Sadece Okunur [IGradientFormat](../../com.aspose.slides/igradientformat).

**Döndürür:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormat getPatternFormat()
```


Desen dolgu biçimini döndürür. Sadece Okunur [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Döndürür:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormat getPictureFillFormat()
```


Resim dolgu biçimini döndürür. Sadece Okunur [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Döndürür:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract byte getRotateWithShape()
```


Dolgunun şekille birlikte döndürülüp döndürülmeyeceğini belirler. Okunur/Yazılır [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public abstract void setRotateWithShape(byte value)
```


Dolgunun şekille birlikte döndürülüp döndürülmeyeceğini belirler. Okunur/Yazılır [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getEffective() {#getEffective--}
```
public abstract IFillFormatEffectiveData getEffective()
```


Miras uygulanarak etkili dolgu biçimlendirme verilerini alır.

**Döndürür:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) - Bir [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).