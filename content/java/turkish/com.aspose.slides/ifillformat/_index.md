---
title: IFillFormat
second_title: Aspose.Slides Java API Referansı
description: Dolgu biçimlendirme seçeneklerini temsil eder.
type: docs
url: /tr/com.aspose.slides/ifillformat/
---
**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormat extends IFillParamSource
```

Dolgu formatı seçeneklerini temsil eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getFillType()](#getFillType--) | Dolgu tipini döndürür veya ayarlar. |
| [setFillType(byte value)](#setFillType-byte-) | Dolgu tipini döndürür veya ayarlar. |
| [getSolidFillColor()](#getSolidFillColor--) | Dolgu rengini döndürür. |
| [getGradientFormat()](#getGradientFormat--) | Gradient dolgu formatını döndürür. |
| [getPatternFormat()](#getPatternFormat--) | Desen dolgu formatını döndürür. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Resim dolgu formatını döndürür. |
| [getRotateWithShape()](#getRotateWithShape--) | Dolgunun şekil ile döndürülüp döndürülmeyeceğini belirler. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Dolgunun şekil ile döndürülüp döndürülmeyeceğini belirler. |
| [getEffective()](#getEffective--) | Kalıtım uygulanmış etkili dolgu formatı verilerini alır. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```

Dolgu tipini döndürür veya ayarlar. Okunur/Yazılabilir [FillType](../../com.aspose.slides/filltype).

**Döndürür:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public abstract void setFillType(byte value)
```

Dolgu tipini döndürür veya ayarlar. Okunur/Yazılabilir [FillType](../../com.aspose.slides/filltype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract IColorFormat getSolidFillColor()
```

Dolgu rengini döndürür. Salt okunur [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormat getGradientFormat()
```

Gradient dolgu formatını döndürür. Salt okunur [IGradientFormat](../../com.aspose.slides/igradientformat).

**Döndürür:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormat getPatternFormat()
```

Desen dolgu formatını döndürür. Salt okunur [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Döndürür:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormat getPictureFillFormat()
```

Resim dolgu formatını döndürür. Salt okunur [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Döndürür:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract byte getRotateWithShape()
```

Dolgunun şekil ile döndürülüp döndürülmeyeceğini belirler. Okunur/Yazılabilir [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public abstract void setRotateWithShape(byte value)
```

Dolgunun şekil ile döndürülüp döndürülmeyeceğini belirler. Okunur/Yazılabilir [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getEffective() {#getEffective--}
```
public abstract IFillFormatEffectiveData getEffective()
```

Kalıtım uygulanmış etkili dolgu formatı verilerini alır.

**Döndürür:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) - A [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).