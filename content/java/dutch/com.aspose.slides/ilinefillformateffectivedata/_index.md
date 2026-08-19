---
title: ILineFillFormatEffectiveData
second_title: Aspose.Slides voor Java API Referentie
description: Onveranderlijk object dat effectieve lijnvullingseigenschappen bevat.
type: docs
url: /nl/com.aspose.slides/ilinefillformateffectivedata/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormatEffectiveData extends IFillParamSource
```

Onveranderlijk object dat effectieve lijnvullings-eigenschappen bevat.

--------------------

Dit interface wordt gebruikt als onderdeel van [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getFillType()](#getFillType--) | Retourneert het vultype. |
| [getSolidFillColor()](#getSolidFillColor--) | Retourneert de kleur van een effen vulling. |
| [getGradientFormat()](#getGradientFormat--) | Retourneert het gradientvulformaat. |
| [getPatternFormat()](#getPatternFormat--) | Retourneert het patroonvulformaat. |
| [getRotateWithShape()](#getRotateWithShape--) | Bepaalt of de vulling met een vorm moet roteren. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


Retourneert het vultype. Alleen-lezen [FillType](../../com.aspose.slides/filltype).

**Retour:**
byte
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Color getSolidFillColor()
```


Retourneert de kleur van een effen vulling. Alleen-lezen java.awt.Color.

**Retour:**
java.awt.Color
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```


Retourneert het gradientvulformaat. Alleen-lezen [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata).

**Retour:**
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```


Retourneert het patroonvulformaat. Alleen-lezen [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata).

**Retour:**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```


Bepaalt of de vulling met een vorm moet roteren. Alleen-lezen boolean.

**Retour:**
boolean