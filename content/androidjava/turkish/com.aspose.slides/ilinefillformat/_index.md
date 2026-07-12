---
title: ILineFillFormat
second_title: Aspose.Slides for Android via Java API Referansı
description: Satır doldurma için özellikleri temsil eder.
type: docs
url: /tr/com.aspose.slides/ilinefillformat/
---
**Tüm Gerçekleştirilen Arayüzler:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormat extends IFillParamSource
```

Satır doldurma için özellikleri temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFillType()](#getFillType--) | Dolgu türünü döndürür veya ayarlar. |
| [setFillType(byte value)](#setFillType-byte-) | Dolgu türünü döndürür veya ayarlar. |
| [getSolidFillColor()](#getSolidFillColor--) | Katı dolgunun rengini döndürür. |
| [getGradientFormat()](#getGradientFormat--) | Gradyan dolgu biçimini döndürür. |
| [getPatternFormat()](#getPatternFormat--) | Desen dolgu biçimini döndürür. |
| [getRotateWithShape()](#getRotateWithShape--) | Dolgunun şekil ile döndürülüp döndürülmeyeceğini belirler. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Dolgunun şekil ile döndürülüp döndürülmeyeceğini belirler. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```

Dolgu türünü döndürür veya ayarlar. Okunur/yazılır [FillType](../../com.aspose.slides/filltype).

**Döndürür:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public abstract void setFillType(byte value)
```

Dolgu türünü döndürür veya ayarlar. Okunur/yazılır [FillType](../../com.aspose.slides/filltype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract IColorFormat getSolidFillColor()
```

Katı dolgunun rengini döndürür. Salt-okunur [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormat getGradientFormat()
```

Gradyan dolgu biçimini döndürür. Salt-okunur [IGradientFormat](../../com.aspose.slides/igradientformat).

**Döndürür:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormat getPatternFormat()
```

Desen dolgu biçimini döndürür. Salt-okunur [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Döndürür:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract byte getRotateWithShape()
```

Dolgunun şekil ile döndürülüp döndürülmeyeceğini belirler. Okunur/yazılır [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public abstract void setRotateWithShape(byte value)
```

Dolgunun şekil ile döndürülüp döndürülmeyeceğini belirler. Okunur/yazılır [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |