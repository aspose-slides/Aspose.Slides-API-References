---
title: IFillFormatEffectiveData
second_title: Aspose.Slides voor Java API-referentie
description: Onafhankelijk object dat effectieve vulopmaak-eigenschappen bevat.
type: docs
url: /nl/com.aspose.slides/ifillformateffectivedata/
---
**All Implemented Interfaces:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormatEffectiveData extends IFillParamSource
```

Onafhankelijk object dat effectieve vulopmaak-eigenschappen bevat.

--------------------

Deze interface wordt samen met de [IFillFormat](../../com.aspose.slides/ifillformat) interface gebruikt om effectieve opmaakwaarden met toegepast overerven te retourneren.
## Methods

| Methode | Beschrijving |
| --- | --- |
| [getFillType()](#getFillType--) | Retourneert het type vulling. |
| [getSolidFillColor()](#getSolidFillColor--) | Retourneert de vulkleur. |
| [getSolidFillSchemeColor()](#getSolidFillSchemeColor--) | Haalt de vulkleur op die is gedefinieerd door een kleurenschema. |
| [getGradientFormat()](#getGradientFormat--) | Retourneert het verloopvullingsformaat. |
| [getPatternFormat()](#getPatternFormat--) | Retourneert het patroonvullingsformaat. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Retourneert het afbeeldingvullingsformaat. |
| [getRotateWithShape()](#getRotateWithShape--) | Bepaalt of de vulling moet roteren met de vorm. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


Retourneert het type vulling. Alleen-lezen [FillType](../../com.aspose.slides/filltype).

**Returns:**
byte
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Color getSolidFillColor()
```


Retourneert de vulkleur. Alleen-lezen java.awt.Color.

**Returns:**
java.awt.Color
### getSolidFillSchemeColor() {#getSolidFillSchemeColor--}
```
public abstract int getSolidFillSchemeColor()
```


Haalt de vulkleur op die is gedefinieerd door een kleurenschema. De [SchemeColor.NotDefined](../../com.aspose.slides/schemecolor\#NotDefined)-waarde geeft aan dat de SolidFillColor (\#getSolidFillColor.getSolidFillColor) geen schema-kleur is. Alleen-lezen [SchemeColor](../../com.aspose.slides/schemecolor).

**Returns:**
int
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```


Retourneert het verloopvullingsformaat. Alleen-lezen [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata).

**Returns:**
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```


Retourneert het patroonvullingsformaat. Alleen-lezen [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata).

**Returns:**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPPictureFillFormatEffectiveData getPictureFillFormat()
```


Retourneert het afbeeldingvullingsformaat. Alleen-lezen [IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata).

**Returns:**
[IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```


Bepaalt of de vulling moet roteren met de vorm. Alleen-lezen boolean.

**Returns:**
boolean