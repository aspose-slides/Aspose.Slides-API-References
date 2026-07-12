---
title: ILineFillFormat
second_title: Aspose.Slides für Android über die Java API Referenz
description: Stellt Eigenschaften für die Füllung von Linien dar.
type: docs
url: /de/com.aspose.slides/ilinefillformat/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormat extends IFillParamSource
```

Stellt Eigenschaften für die Füllung von Linien dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFillType()](#getFillType--) | Gibt den Fülltyp zurück oder legt ihn fest. |
| [setFillType(byte value)](#setFillType-byte-) | Gibt den Fülltyp zurück oder legt ihn fest. |
| [getSolidFillColor()](#getSolidFillColor--) | Gibt die Farbe einer Vollfüllung zurück. |
| [getGradientFormat()](#getGradientFormat--) | Gibt das Verlauffüllformat zurück. |
| [getPatternFormat()](#getPatternFormat--) | Gibt das Musterfüllformat zurück. |
| [getRotateWithShape()](#getRotateWithShape--) | Bestimmt, ob die Füllung mit einer Form rotiert werden soll. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Bestimmt, ob die Füllung mit einer Form rotiert werden soll. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


Gibt den Fülltyp zurück oder legt ihn fest. Lesen/Schreiben [FillType](../../com.aspose.slides/filltype).

**Rückgabe:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public abstract void setFillType(byte value)
```


Gibt den Fülltyp zurück oder legt ihn fest. Lesen/Schreiben [FillType](../../com.aspose.slides/filltype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getSolidFillColor() {#getSolidFillColor--}
```
public abstract IColorFormat getSolidFillColor()
```


Gibt die Farbe einer Vollfüllung zurück. Nur-Lesen [IColorFormat](../../com.aspose.slides/icolorformat).

**Rückgabe:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormat getGradientFormat()
```


Gibt das Verlauffüllformat zurück. Nur-Lesen [IGradientFormat](../../com.aspose.slides/igradientformat).

**Rückgabe:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormat getPatternFormat()
```


Gibt das Musterfüllformat zurück. Nur-Lesen [IPatternFormat](../../com.aspose.slides/ipatternformat).

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