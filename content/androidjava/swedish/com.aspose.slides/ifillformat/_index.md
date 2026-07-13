---
title: IFillFormat
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar ett fyllningsformateringsalternativ.
type: docs
url: /sv/com.aspose.slides/ifillformat/
---
**All Implemented Interfaces:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormat extends IFillParamSource
```

Representerar ett fyllningsformateringsalternativ.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFillType()](#getFillType--) | Returnerar eller sätter fyllningstypen. |
| [setFillType(byte value)](#setFillType-byte-) | Returnerar eller sätter fyllningstypen. |
| [getSolidFillColor()](#getSolidFillColor--) | Returnerar fyllningsfärgen. |
| [getGradientFormat()](#getGradientFormat--) | Returnerar gradientfyllningsformatet. |
| [getPatternFormat()](#getPatternFormat--) | Returnerar mönsterfyllningsformatet. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Returnerar bildfyllningsformatet. |
| [getRotateWithShape()](#getRotateWithShape--) | Avgör om fyllningen ska roteras med formen. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Avgör om fyllningen ska roteras med formen. |
| [getEffective()](#getEffective--) | Hämtar effektiv fyllningsformatering med ärvda inställningar tillämpade. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


Returnerar eller sätter fyllningstypen. Läs/skriv [FillType](../../com.aspose.slides/filltype).

**Returnerar:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public abstract void setFillType(byte value)
```


Returnerar eller sätter fyllningstypen. Läs/skriv [FillType](../../com.aspose.slides/filltype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getSolidFillColor() {#getSolidFillColor--}
```
public abstract IColorFormat getSolidFillColor()
```


Returnerar fyllningsfärgen. Skrivskyddad [IColorFormat](../../com.aspose.slides/icolorformat).

**Returnerar:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormat getGradientFormat()
```


Returnerar gradientfyllningsformatet. Skrivskyddad [IGradientFormat](../../com.aspose.slides/igradientformat).

**Returnerar:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormat getPatternFormat()
```


Returnerar mönsterfyllningsformatet. Skrivskyddad [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Returnerar:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormat getPictureFillFormat()
```


Returnerar bildfyllningsformatet. Skrivskyddad [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getEffective() {#getEffective--}
```
public abstract IFillFormatEffectiveData getEffective()
```


Hämtar effektiv fyllningsformatering med ärvda inställningar tillämpade.

**Returnerar:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) - En [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).