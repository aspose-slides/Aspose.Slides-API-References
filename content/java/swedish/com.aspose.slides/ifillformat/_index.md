---
title: IFillFormat
second_title: Aspose.Slides för Java API-referens
description: Representerar ett fyllningsformateringsalternativ.
type: docs
url: /sv/com.aspose.slides/ifillformat/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormat extends IFillParamSource
```

Representerar ett fyllningsformateringsalternativ.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFillType()](#getFillType--) | Returnerar eller anger fyllningstypen. |
| [setFillType(byte value)](#setFillType-byte-) | Returnerar eller anger fyllningstypen. |
| [getSolidFillColor()](#getSolidFillColor--) | Returnerar fyllningsfärgen. |
| [getGradientFormat()](#getGradientFormat--) | Returnerar gradientfyllningsformatet. |
| [getPatternFormat()](#getPatternFormat--) | Returnerar mönsterfyllningsformatet. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Returnerar bildfyllningsformatet. |
| [getRotateWithShape()](#getRotateWithShape--) | Avgör om fyllningen ska roteras med formen. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Avgör om fyllningen ska roteras med formen. |
| [getEffective()](#getEffective--) | Hämtar effektiv fyllningsformateringsdata med arv tillämpat. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


Returnerar eller angår fyllningstypen. Läs/skriv [FillType](../../com.aspose.slides/filltype).

**Returnerar:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public abstract void setFillType(byte value)
```


Returnerar eller anger fyllningstypen. Läs/skriv [FillType](../../com.aspose.slides/filltype).

**Parametrar:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getSolidFillColor() {#getSolidFillColor--}
```
public abstract IColorFormat getSolidFillColor()
```


Returnerar fyllningsfärgen. Endast läsning [IColorFormat](../../com.aspose.slides/icolorformat).

**Returnerar:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormat getGradientFormat()
```


Returnerar gradientfyllningsformatet. Endast läsning [IGradientFormat](../../com.aspose.slides/igradientformat).

**Returnerar:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormat getPatternFormat()
```


Returnerar mönsterfyllningsformatet. Endast läsning [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Returnerar:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormat getPictureFillFormat()
```


Returnerar bildfyllningsformatet. Endast läsning [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Returnerar:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract byte getRotateWithShape()
```


Avgör om fyllningen ska roteras med formen. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public abstract void setRotateWithShape(byte value)
```


Avgör om fyllningen ska roteras med formen. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Parametrar:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getEffective() {#getEffective--}
```
public abstract IFillFormatEffectiveData getEffective()
```


Hämtar effektiv fyllningsformateringsdata med arv tillämpat.

**Returnerar:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) - En [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).