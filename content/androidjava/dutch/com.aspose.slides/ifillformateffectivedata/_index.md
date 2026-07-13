---
title: IFillFormatEffectiveData
second_title: Aspose.Slides voor Android via Java API-referentie
description: Onveranderlijk object dat effectieve opvulopmaak-eigenschappen bevat.
type: docs
url: /nl/com.aspose.slides/ifillformateffectivedata/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormatEffectiveData extends IFillParamSource
```

Onveranderlijk object dat effectieve opvulopmaak-eigenschappen bevat.

--------------------

Deze interface wordt samen met de [IFillFormat](../../com.aspose.slides/ifillformat) interface gebruikt om effectieve opmaakwaarden terug te geven met geërfde waarden toegepast.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getFillType()](#getFillType--) | Retourneert het type vulling. |
| [getSolidFillColor()](#getSolidFillColor--) | Retourneert de opvulkleur. |
| [getSolidFillSchemeColor()](#getSolidFillSchemeColor--) | Haalt de opvulkleur op die is gedefinieerd door een kleurschema. |
| [getGradientFormat()](#getGradientFormat--) | Retourneert het verloop-opvulformaat. |
| [getPatternFormat()](#getPatternFormat--) | Retourneert het patroon-opvulformaat. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Retourneert het afbeelding-opvulformaat. |
| [getRotateWithShape()](#getRotateWithShape--) | Bepaalt of de opvulling met de vorm moet worden geroteerd. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


Retourneert het type vulling. Alleen-lezen [FillType](../../com.aspose.slides/filltype).

**Retour:**
byte
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Integer getSolidFillColor()
```


Retourneert de opvulkleur. Alleen-lezen java.lang.Integer.

**Retour:**
java.lang.Integer
### getSolidFillSchemeColor() {#getSolidFillSchemeColor--}
```
public abstract int getSolidFillSchemeColor()
```


Haalt de opvulkleur op die is gedefinieerd door een kleurschema. De [SchemeColor.NotDefined](../../com.aspose.slides/schemecolor\#NotDefined)-waarde geeft aan dat de SolidFillColor (\#getSolidFillColor.getSolidFillColor) geen schemakleur is. Alleen-lezen [SchemeColor](../../com.aspose.slides/schemecolor).

**Retour:**
int
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```


Retourneert het verloop-opvulformaat. Alleen-lezen [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata).

**Retour:**
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```


Retourneert het patroon-opvulformaat. Alleen-lezen [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata).

**Retour:**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormatEffectiveData getPictureFillFormat()
```


Retourneert het afbeelding-opvulformaat. Alleen-lezen [IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata).

**Retour:**
[IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```


Bepaalt of de opvulling met de vorm moet worden geroteerd. Alleen-lezen boolean.

**Retour:**
boolean