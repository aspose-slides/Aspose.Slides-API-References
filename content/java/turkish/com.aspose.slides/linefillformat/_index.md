---
title: LineFillFormat
second_title: Aspose.Slides Java API Referansı
description: Satır doldurma özelliklerini temsil eder.
type: docs
url: /tr/com.aspose.slides/linefillformat/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.ILineFillFormat](../../com.aspose.slides/ilinefillformat)
```
public final class LineFillFormat extends PVIObject implements ILineFillFormat
```

Satır doldurma özelliklerini temsil eder.
## Yöntemler

| Metot | Açıklama |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillType()](#getFillType--) | Dolgu türünü döndürür veya ayarlar. |
| [setFillType(byte value)](#setFillType-byte-) | Dolgu türünü döndürür veya ayarlar. |
| [getRotateWithShape()](#getRotateWithShape--) | Dolgunun bir şekil ile döndürülüp döndürülmeyeceğini belirler. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Dolgunun bir şekil ile döndürülüp döndürülmeyeceğini belirler. |
| [getSolidFillColor()](#getSolidFillColor--) | Katı dolgunun rengini döndürür. |
| [getGradientFormat()](#getGradientFormat--) | Gradyan dolgu biçimini döndürür. |
| [getPatternFormat()](#getPatternFormat--) | Desen dolgu biçimini döndürür. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Sürüm. Salt okunur uzun.

**Döndürür:**
long
### getFillType() {#getFillType--}
```
public final byte getFillType()
```

Dolgu türünü döndürür veya ayarlar. Okunur/yazılır [FillType](../../com.aspose.slides/filltype).

**Döndürür:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public final void setFillType(byte value)
```

Dolgu türünü döndürür veya ayarlar. Okunur/yazılır [FillType](../../com.aspose.slides/filltype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getRotateWithShape() {#getRotateWithShape--}
```
public final byte getRotateWithShape()
```

Dolgunun bir şekil ile döndürülüp döndürülmeyeceğini belirler. Okunur/yazılır [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public final void setRotateWithShape(byte value)
```

Dolgunun bir şekil ile döndürülüp döndürülmeyeceğini belirler. Okunur/yazılır [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getSolidFillColor() {#getSolidFillColor--}
```
public final IColorFormat getSolidFillColor()
```

Katı dolgunun rengini döndürür. Salt okunur [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public final IGradientFormat getGradientFormat()
```

Gradyan dolgu biçimini döndürür. Salt okunur [IGradientFormat](../../com.aspose.slides/igradientformat).

**Döndürür:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public final IPatternFormat getPatternFormat()
```

Desen dolgu biçimini döndürür. Salt okunur [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Döndürür:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)