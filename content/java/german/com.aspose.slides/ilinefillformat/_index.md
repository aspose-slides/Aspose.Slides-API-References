---
title: ILineFillFormat
second_title: Aspose.Slides für Java API-Referenz
description: Stellt Eigenschaften für das Füllen von Linien dar.
type: docs
url: /de/com.aspose.slides/ilinefillformat/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormat extends IFillParamSource
```

Stellt Eigenschaften für das Füllen von Linien dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFillType()](#getFillType--) | Gibt den Fülltyp zurück oder setzt ihn. |
| [setFillType(byte value)](#setFillType-byte-) | Gibt den Fülltyp zurück oder setzt ihn. |
| [getSolidFillColor()](#getSolidFillColor--) | Gibt die Farbe einer soliden Füllung zurück. |
| [getGradientFormat()](#getGradientFormat--) | Gibt das Gradient-Füllformat zurück. |
| [getPatternFormat()](#getPatternFormat--) | Gibt das Muster-Füllformat zurück. |
| [getRotateWithShape()](#getRotateWithShape--) | Bestimmt, ob die Füllung mit einer Form rotiert werden soll. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Bestimmt, ob die Füllung mit einer Form rotiert werden soll. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```

Gibt den Fülltyp zurück oder setzt ihn. Lesen/Schreiben [FillType](../../com.aspose.slides/filltype).

**Rückgabe:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public abstract void setFillType(byte value)
```

Gibt den Fülltyp zurück oder setzt ihn. Lesen/Schreiben [FillType](../../com.aspose.slides/filltype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract IColorFormat getSolidFillColor()
```

Gibt die Farbe einer soliden Füllung zurück. Nur lesen [IColorFormat](../../com.aspose.slides/icolorformat).

**Rückgabe:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormat getGradientFormat()
```

Gibt das Gradient-Füllformat zurück. Nur lesen [IGradientFormat](../../com.aspose.slides/igradientformat).

**Rückgabe:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormat getPatternFormat()
```

Gibt das Muster-Füllformat zurück. Nur lesen [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Rückgabe:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract byte getRotateWithShape()
```

Bestimmt, ob die Füllung mit einer Form rotiert werden soll. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Rückgabe:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public abstract void setRotateWithShape(byte value)
```

Bestimmt, ob die Füllung mit einer Form rotiert werden soll. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |