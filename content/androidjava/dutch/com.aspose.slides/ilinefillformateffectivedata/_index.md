---
title: ILineFillFormatEffectiveData
second_title: Aspose.Slides voor Android via Java API-referentie
description: Onveranderlijk object dat effectieve lijnvullings-eigenschappen bevat.
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

Deze interface wordt gebruikt als onderdeel van [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getFillType()](#getFillType--) | Retourneert het vultype. |
| [getSolidFillColor()](#getSolidFillColor--) | Retourneert de kleur van een effen vulling. |
| [getGradientFormat()](#getGradientFormat--) | Retourneert het verloopvullingsformaat. |
| [getPatternFormat()](#getPatternFormat--) | Retourneert het patroonvullingsformaat. |
| [getRotateWithShape()](#getRotateWithShape--) | Bepaalt of de vulling moet roteren met een vorm. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


Retourneert het vultype. Alleen-lezen [FillType](../../com.aspose.slides/filltype).

**Retourneert:**
byte
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Integer getSolidFillColor()
```


Retourneert de kleur van een effen vulling. Alleen-lezen java.lang.Integer.

**Retourneert:**
java.lang.Integer
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```


Retourneert het verloopvullingsformaat. Alleen-lezen [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata).

**Retourneert:**
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```


Retourneert het patroonvullingsformaat. Alleen-lezen [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata).

**Retourneert:**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```


Bepaalt of de vulling moet roteren met een vorm. Alleen-lezen boolean.

**Retourneert:**
boolean