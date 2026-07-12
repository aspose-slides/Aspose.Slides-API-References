---
title: ILineFillFormatEffectiveData
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Unveränderliches Objekt, das effektive Zeilenfüllungseigenschaften enthält.
type: docs
url: /de/com.aspose.slides/ilinefillformateffectivedata/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormatEffectiveData extends IFillParamSource
```

Unveränderliches Objekt, das effektive Zeilenfüllungseigenschaften enthält.

--------------------

Dieses Interface wird als Teil von [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) verwendet.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFillType()](#getFillType--) | Gibt den Fülltyp zurück. |
| [getSolidFillColor()](#getSolidFillColor--) | Gibt die Farbe einer einfarbigen Füllung zurück. |
| [getGradientFormat()](#getGradientFormat--) | Gibt das Farbverlaufsfüllformat zurück. |
| [getPatternFormat()](#getPatternFormat--) | Gibt das Musterfüllformat zurück. |
| [getRotateWithShape()](#getRotateWithShape--) | Bestimmt, ob die Füllung mit einer Form rotiert werden soll. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```

Gibt den Fülltyp zurück. Nur lesbar [FillType](../../com.aspose.slides/filltype).

**Rückgabewert:**
byte
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Integer getSolidFillColor()
```

Gibt die Farbe einer einfarbigen Füllung zurück. Nur lesbar java.lang.Integer.

**Rückgabewert:**
java.lang.Integer
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```

Gibt das Farbverlaufsfüllformat zurück. Nur lesbar [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata).

**Rückgabewert:**
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```

Gibt das Musterfüllformat zurück. Nur lesbar [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata).

**Rückgabewert:**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```

Bestimmt, ob die Füllung mit einer Form rotiert werden soll. Nur lesbar boolean.

**Rückgabewert:**
boolean