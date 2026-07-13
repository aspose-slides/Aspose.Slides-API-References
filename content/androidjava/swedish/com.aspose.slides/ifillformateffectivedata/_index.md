---
title: IFillFormatEffectiveData
second_title: Aspose.Slides för Android via Java API-referens
description: Oföränderligt objekt som innehåller effektiva fyllningsformaterings-egenskaper.
type: docs
url: /sv/com.aspose.slides/ifillformateffectivedata/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormatEffectiveData extends IFillParamSource
```

Oföränderligt objekt som innehåller effektiva fyllningsformaterings-egenskaper.

--------------------

Detta gränssnitt används tillsammans med [IFillFormat](../../com.aspose.slides/ifillformat)-gränssnittet för att returnera effektiva formateringsvärden med arv tillämpat.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFillType()](#getFillType--) | Returnerar fyllningstypen. |
| [getSolidFillColor()](#getSolidFillColor--) | Returnerar fyllningsfärgen. |
| [getSolidFillSchemeColor()](#getSolidFillSchemeColor--) | Hämtar fyllningsfärgen som definieras av ett färgschema. |
| [getGradientFormat()](#getGradientFormat--) | Returnerar gradientfyllningsformatet. |
| [getPatternFormat()](#getPatternFormat--) | Returnerar mönsterfyllningsformatet. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Returnerar bildfyllningsformatet. |
| [getRotateWithShape()](#getRotateWithShape--) | Bestämmer om fyllningen ska roteras med formen. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


Returnerar fyllningstypen. Skrivskyddad [FillType](../../com.aspose.slides/filltype).

**Returnerar:**
byte
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Integer getSolidFillColor()
```


Returnerar fyllningsfärgen. Skrivskyddad java.lang.Integer.

**Returnerar:**
java.lang.Integer
### getSolidFillSchemeColor() {#getSolidFillSchemeColor--}
```
public abstract int getSolidFillSchemeColor()
```


Hämtar fyllningsfärgen som definieras av ett färgschema. Värdet [SchemeColor.NotDefined](../../com.aspose.slides/schemecolor\#NotDefined) indikerar att SolidFillColor (\#getSolidFillColor.getSolidFillColor) inte är en schema-färg. Skrivskyddad [SchemeColor](../../com.aspose.slides/schemecolor).

**Returnerar:**
int
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```


Returnerar gradientfyllningsformatet. Skrivskyddad [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata).

**Returnerar:**
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```


Returnerar mönsterfyllningsformatet. Skrivskyddad [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata).

**Returnerar:**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormatEffectiveData getPictureFillFormat()
```


Returnerar bildfyllningsformatet. Skrivskyddad [IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata).

**Returnerar:**
[IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```


Bestämmer om fyllningen ska roteras med formen. Skrivskyddad boolean.

**Returnerar:**
boolean