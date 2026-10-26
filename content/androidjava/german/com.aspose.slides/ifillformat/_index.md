---
title: IFillFormat
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt eine Füllformatierungsoption dar.
type: docs
url: /de/com.aspose.slides/ifillformat/
---
**All Implemented Interfaces:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormat extends IFillParamSource
```

Stellt eine Füllformatierungsoption dar.
## Methoden

| Method | Description |
| --- | --- |
| [getFillType()](#getFillType--) | Gibt den Fülltyp zurück oder legt ihn fest. |
| [setFillType(byte value)](#setFillType-byte-) | Gibt den Fülltyp zurück oder legt ihn fest. |
| [getSolidFillColor()](#getSolidFillColor--) | Gibt die Füllfarbe zurück. |
| [getGradientFormat()](#getGradientFormat--) | Gibt das Farbverlaufsfüllformat zurück. |
| [getPatternFormat()](#getPatternFormat--) | Gibt das Musterfüllformat zurück. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Gibt das Bildfüllformat zurück. |
| [getRotateWithShape()](#getRotateWithShape--) | Bestimmt, ob die Füllung mit der Form rotiert werden soll. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Bestimmt, ob die Füllung mit der Form rotiert werden soll. |
| [getEffective()](#getEffective--) | Ermittelt die effektiven Füllformatierungsdaten unter Anwendung der Vererbung. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


Gibt den Fülltyp zurück oder legt ihn fest. Lese/Schreib [FillType](../../com.aspose.slides/filltype).

**Rückgabe:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public abstract void setFillType(byte value)
```


Gibt den Fülltyp zurück oder legt ihn fest. Lese/Schreib [FillType](../../com.aspose.slides/filltype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getSolidFillColor() {#getSolidFillColor--}
```
public abstract IColorFormat getSolidFillColor()
```


Gibt die Füllfarbe zurück. Nur-lesen [IColorFormat](../../com.aspose.slides/icolorformat).

**Rückgabe:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormat getGradientFormat()
```


Gibt das Farbverlaufsfüllformat zurück. Nur-lesen [IGradientFormat](../../com.aspose.slides/igradientformat).

**Rückgabe:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormat getPatternFormat()
```


Gibt das Musterfüllformat zurück. Nur-lesen [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Rückgabe:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormat getPictureFillFormat()
```


Gibt das Bildfüllformat zurück. Nur-lesen [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Rückgabe:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract byte getRotateWithShape()
```


Bestimmt, ob die Füllung mit der Form rotiert werden soll. Lese/Schreib [NullableBool](../../com.aspose.slides/nullablebool).

**Rückgabe:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public abstract void setRotateWithShape(byte value)
```


Bestimmt, ob die Füllung mit der Form rotiert werden soll. Lese/Schreib [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getEffective() {#getEffective--}
```
public abstract IFillFormatEffectiveData getEffective()
```


Ermittelt die effektiven Füllformatierungsdaten unter Anwendung der Vererbung.

**Rückgabe:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) - A [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).