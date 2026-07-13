---
title: LineFillFormat
second_title: Aspose.Slides voor Android via Java API Referentie
description: Stelt eigenschappen voor het vullen van lijnen voor.
type: docs
url: /nl/com.aspose.slides/linefillformat/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ILineFillFormat](../../com.aspose.slides/ilinefillformat)
```
public final class LineFillFormat extends PVIObject implements ILineFillFormat
```

Stelt eigenschappen voor het vullen van lijnen voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillType()](#getFillType--) | Geeft of stelt het vultype in. |
| [setFillType(byte value)](#setFillType-byte-) | Geeft of stelt het vultype in. |
| [getRotateWithShape()](#getRotateWithShape--) | Bepaalt of de vulling met een vorm moet worden geroteerd. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Bepaalt of de vulling met een vorm moet worden geroteerd. |
| [getSolidFillColor()](#getSolidFillColor--) | Geeft de kleur van een effen vulling terug. |
| [getGradientFormat()](#getGradientFormat--) | Geeft het verloopvullingsformaat terug. |
| [getPatternFormat()](#getPatternFormat--) | Geeft het patroonvullingsformaat terug. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Versie. Alleen-lezen long.

**Retour:**
long
### getFillType() {#getFillType--}
```
public final byte getFillType()
```

Geeft of stelt het vultype in. Lezen/Schrijven [FillType](../../com.aspose.slides/filltype).

**Retour:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public final void setFillType(byte value)
```

Geeft of stelt het vultype in. Lezen/Schrijven [FillType](../../com.aspose.slides/filltype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |
### getRotateWithShape() {#getRotateWithShape--}
```
public final byte getRotateWithShape()
```

Bepaalt of de vulling met een vorm moet worden geroteerd. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retour:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public final void setRotateWithShape(byte value)
```

Bepaalt of de vulling met een vorm moet worden geroteerd. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |
### getSolidFillColor() {#getSolidFillColor--}
```
public final IColorFormat getSolidFillColor()
```

Geeft de kleur van een effen vulling terug. Alleen-lezen [IColorFormat](../../com.aspose.slides/icolorformat).

**Retour:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public final IGradientFormat getGradientFormat()
```

Geeft het verloopvullingsformaat terug. Alleen-lezen [IGradientFormat](../../com.aspose.slides/igradientformat).

**Retour:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public final IPatternFormat getPatternFormat()
```

Geeft het patroonvullingsformaat terug. Alleen-lezen [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Retour:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)