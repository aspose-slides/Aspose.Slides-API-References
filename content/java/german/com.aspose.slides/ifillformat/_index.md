---
title: IFillFormat
second_title: Aspose.Slides für Java API Referenz
description: Stellt Füllformatierungsoptionen dar.
type: docs
url: /de/com.aspose.slides/ifillformat/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormat extends IFillParamSource
```

Stellt Füllformatierungsoptionen dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFillType()](#getFillType--) | Gibt den Fülltyp zurück oder setzt ihn. |
| [setFillType(byte value)](#setFillType-byte-) | Gibt den Fülltyp zurück oder setzt ihn. |
| [getSolidFillColor()](#getSolidFillColor--) | Gibt die Füllfarbe zurück. |
| [getGradientFormat()](#getGradientFormat--) | Gibt das Farbverlauf-Füllformat zurück. |
| [getPatternFormat()](#getPatternFormat--) | Gibt das Musterfüllformat zurück. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Gibt das Bildfüllformat zurück. |
| [getRotateWithShape()](#getRotateWithShape--) | Bestimmt, ob die Füllung mit der Form rotiert werden soll. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Bestimmt, ob die Füllung mit der Form rotiert werden soll. |
| [getEffective()](#getEffective--) | Liefert die wirksamen Füllformatierungsdaten mit angewandter Vererbung. |
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


Gibt die Füllfarbe zurück. Nur lesen [IColorFormat](../../com.aspose.slides/icolorformat).

**Rückgabe:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormat getGradientFormat()
```


Gibt das Farbverlauf-Füllformat zurück. Nur lesen [IGradientFormat](../../com.aspose.slides/igradientformat).

**Rückgabe:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormat getPatternFormat()
```


Gibt das Musterfüllformat zurück. Nur lesen [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Rückgabe:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormat getPictureFillFormat()
```


Gibt das Bildfüllformat zurück. Nur lesen [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Rückgabe:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract byte getRotateWithShape()
```


Bestimmt, ob die Füllung mit der Form rotiert werden soll. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Rückgabe:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public abstract void setRotateWithShape(byte value)
```


Bestimmt, ob die Füllung mit der Form rotiert werden soll. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |
### getEffective() {#getEffective--}
```
public abstract IFillFormatEffectiveData getEffective()
```


Liefert die wirksamen Füllformatierungsdaten mit angewandter Vererbung.

**Rückgabe:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) - Ein [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).