---
title: LineFillFormat
second_title: Aspose.Slides for Android için Java API Referansı
description: Satır doldurma için özellikleri temsil eder.
type: docs
url: /tr/com.aspose.slides/linefillformat/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Tüm Gerçekleştirilen Arabirimler:**
[com.aspose.slides.ILineFillFormat](../../com.aspose.slides/ilinefillformat)
```
public final class LineFillFormat extends PVIObject implements ILineFillFormat
```

Satır doldurma için özellikleri temsil eder.
## Yöntemler

| Metod | Açıklama |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillType()](#getFillType--) | Dolgu tipini alır veya ayarlar. |
| [setFillType(byte value)](#setFillType-byte-) | Dolgu tipini alır veya ayarlar. |
| [getRotateWithShape()](#getRotateWithShape--) | Dolgunun bir şekil ile döndürülüp döndürülmeyeceğini belirler. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Dolgunun bir şekil ile döndürülüp döndürülmeyeceğini belirler. |
| [getSolidFillColor()](#getSolidFillColor--) | Katı dolgunun rengini döndürür. |
| [getGradientFormat()](#getGradientFormat--) | Gradyan dolgu biçimini döndürür. |
| [getPatternFormat()](#getPatternFormat--) | Desen dolgu biçimini döndürür. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Sürüm. Salt okunur long.

**Döndürülen:**
long
### getFillType() {#getFillType--}
```
public final byte getFillType()
```


Dolgu tipini alır veya ayarlar. Okunur/Yazılabilir [FillType](../../com.aspose.slides/filltype).

**Döndürülen:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public final void setFillType(byte value)
```


Dolgu tipini alır veya ayarlar. Okunur/Yazılabilir [FillType](../../com.aspose.slides/filltype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getRotateWithShape() {#getRotateWithShape--}
```
public final byte getRotateWithShape()
```


Dolgunun bir şekil ile döndürülüp döndürülmeyeceğini belirler. Okunur/Yazılabilir [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürülen:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public final void setRotateWithShape(byte value)
```


Dolgunun bir şekil ile döndürülüp döndürülmeyeceğini belirler. Okunur/Yazılabilir [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getSolidFillColor() {#getSolidFillColor--}
```
public final IColorFormat getSolidFillColor()
```


Katı dolgunun rengini döndürür. Salt okunur [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürülen:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public final IGradientFormat getGradientFormat()
```


Gradyan dolgu biçimini döndürür. Salt okunur [IGradientFormat](../../com.aspose.slides/igradientformat).

**Döndürülen:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public final IPatternFormat getPatternFormat()
```


Desen dolgu biçimini döndürür. Salt okunur [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Döndürülen:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)