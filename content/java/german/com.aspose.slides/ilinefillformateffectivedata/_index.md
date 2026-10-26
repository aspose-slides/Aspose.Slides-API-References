---
title: ILineFillFormatEffectiveData
second_title: Aspose.Slides für Java API-Referenz
description: Unveränderliches Objekt, das wirksame Zeilenfüllungs-Eigenschaften enthält.
type: docs
url: /de/com.aspose.slides/ilinefillformateffectivedata/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormatEffectiveData extends IFillParamSource
```

Unveränderliches Objekt, das wirksame Zeilenfüllungs-Eigenschaften enthält.

--------------------

Dieses Interface wird als Teil von [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) verwendet.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFillType()](#getFillType--) | Gibt den Fülltyp zurück. |
| [getSolidFillColor()](#getSolidFillColor--) | Gibt die Farbe einer einfarbigen Füllung zurück. |
| [getGradientFormat()](#getGradientFormat--) | Gibt das Farbverlaufs-Füllformat zurück. |
| [getPatternFormat()](#getPatternFormat--) | Gibt das Muster-Füllformat zurück. |
| [getRotateWithShape()](#getRotateWithShape--) | Bestimmt, ob die Füllung mit einer Form rotiert werden soll. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


Gibt den Fülltyp zurück. Nurlesbar [FillType](../../com.aspose.slides/filltype).

**Rückgabewert:**
byte
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Color getSolidFillColor()
```


Gibt die Farbe einer einfarbigen Füllung zurück. Nurlesbar java.awt.Color.

**Rückgabewert:**
java.awt.Color
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```


Gibt das Farbverlaufs-Füllformat zurück. Nurlesbar [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata).

**Rückgabewert:**
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```


Gibt das Muster-Füllformat zurück. Nurlesbar [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata).

**Rückgabewert:**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```


Bestimmt, ob die Füllung mit einer Form rotiert werden soll. Nurlesbar boolean.

**Rückgabewert:**
boolean