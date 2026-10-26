---
title: IFillFormatEffectiveData
second_title: Aspose.Slides für Java API Referenz
description: Unveränderliches Objekt, das wirksame Füllformatierungseigenschaften enthält.
type: docs
url: /de/com.aspose.slides/ifillformateffectivedata/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormatEffectiveData extends IFillParamSource
```

Unveränderliches Objekt, das wirksame Füllformatierungseigenschaften enthält.

--------------------

Dieses Schnittstelle wird zusammen mit dem [IFillFormat](../../com.aspose.slides/ifillformat) Schnittstelle verwendet, um wirksame Formatierungswerte mit angewandter Vererbung zurückzugeben.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFillType()](#getFillType--) | Gibt den Fülltyp zurück. |
| [getSolidFillColor()](#getSolidFillColor--) | Gibt die Füllfarbe zurück. |
| [getSolidFillSchemeColor()](#getSolidFillSchemeColor--) | Ermittelt die durch ein Farbschema definierte Füllfarbe. |
| [getGradientFormat()](#getGradientFormat--) | Gibt das Verlauffüllformat zurück. |
| [getPatternFormat()](#getPatternFormat--) | Gibt das Musterfüllformat zurück. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Gibt das Bildfüllformat zurück. |
| [getRotateWithShape()](#getRotateWithShape--) | Bestimmt, ob die Füllung mit der Form rotiert werden soll. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


Gibt den Fülltyp zurück. Nur lesbar [FillType](../../com.aspose.slides/filltype).

**Rückgabewert:**
byte
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Color getSolidFillColor()
```


Gibt die Füllfarbe zurück. Nur lesbar java.awt.Color.

**Rückgabewert:**
java.awt.Color
### getSolidFillSchemeColor() {#getSolidFillSchemeColor--}
```
public abstract int getSolidFillSchemeColor()
```


Ermittelt die durch ein Farbschema definierte Füllfarbe. Der [SchemeColor.NotDefined](../../com.aspose.slides/schemecolor\#NotDefined) Wert zeigt an, dass die SolidFillColor (\#getSolidFillColor.getSolidFillColor) keine Schemafarbe ist. Nur lesbar [SchemeColor](../../com.aspose.slides/schemecolor).

**Rückgabewert:**
int
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```


Gibt das Verlauffüllformat zurück. Nur lesbar [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata).

**Rückgabewert:**
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```


Gibt das Musterfüllformat zurück. Nur lesbar [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata).

**Rückgabewert:**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormatEffectiveData getPictureFillFormat()
```


Gibt das Bildfüllformat zurück. Nur lesbar [IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata).

**Rückgabewert:**
[IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```


Bestimmt, ob die Füllung mit der Form rotiert werden soll. Nur lesbar boolean.

**Rückgabewert:**
boolean