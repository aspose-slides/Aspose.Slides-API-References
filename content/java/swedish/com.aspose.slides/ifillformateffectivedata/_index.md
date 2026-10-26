---
title: IFillFormatEffectiveData
second_title: Aspose.Slides för Java API-referens
description: Oföränderligt objekt som innehåller effektiva fyllningsformateringsegenskaper.
type: docs
url: /sv/com.aspose.slides/ifillformateffectivedata/
---
**All Implemented Interfaces:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormatEffectiveData extends IFillParamSource
```

Oföränderligt objekt som innehåller effektiva fyllningsformateringsegenskaper.

--------------------

Det här gränssnittet används tillsammans med [IFillFormat](../../com.aspose.slides/ifillformat)-gränssnittet för att returnera effektiva formateringsvärden med arv tillämpade.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFillType()](#getFillType--) | Returnerar fyllningstypen. |
| [getSolidFillColor()](#getSolidFillColor--) | Returnerar fyllningsfärgen. |
| [getSolidFillSchemeColor()](#getSolidFillSchemeColor--) | Hämtar fyllningsfärgen som definieras av ett färgschema. |
| [getGradientFormat()](#getGradientFormat--) | Returnerar gradientfyllnadsformatet. |
| [getPatternFormat()](#getPatternFormat--) | Returnerar mönsterfyllnadsformatet. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Returnerar bildfyllnadsformatet. |
| [getRotateWithShape()](#getRotateWithShape--) | Avgör om fyllningen ska roteras med formen. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


Returnerar fyllningstypen. Skrivskyddad [FillType](../../com.aspose.slides/filltype).

**Returnerar:**
byte
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Color getSolidFillColor()
```


Returnerar fyllningsfärgen. Skrivskyddad java.awt.Color.

**Returnerar:**
java.awt.Color
### getSolidFillSchemeColor() {#getSolidFillSchemeColor--}
```
public abstract int getSolidFillSchemeColor()
```


Hämtar fyllningsfärgen som definieras av ett färgschema. Värdet [SchemeColor.NotDefined](../../com.aspose.slides/schemecolor\#NotDefined) indikerar att SolidFillColor (\#getSolidFillColor.getSolidFillColor) inte är en schemafärg. Skrivskyddad [SchemeColor](../../com.aspose.slides/schemecolor).

**Returnerar:**
int
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```


Returnerar gradientfyllnadsformatet. Skrivskyddad [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata).

**Returnerar:**
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```


Returnerar mönsterfyllnadsformatet. Skrivskyddad [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata).

**Returnerar:**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormatEffectiveData getPictureFillFormat()
```


Returnerar bildfyllnadsformatet. Skrivskyddad [IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata).

**Returnerar:**
[IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```


Avgör om fyllningen ska roteras med formen. Skrivskyddad boolean.

**Returnerar:**
boolean