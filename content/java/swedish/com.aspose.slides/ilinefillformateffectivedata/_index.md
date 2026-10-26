---
title: ILineFillFormatEffectiveData
second_title: Aspose.Slides för Java API-referens
description: Oföränderligt objekt som innehåller effektiva linjefyllningsegenskaper.
type: docs
url: /sv/com.aspose.slides/ilinefillformateffectivedata/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormatEffectiveData extends IFillParamSource
```

Omuterbart objekt som innehåller effektiva radfyllningsegenskaper.

--------------------

Detta gränssnitt används som en del av [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFillType()](#getFillType--) | Returnerar fyllningstypen. |
| [getSolidFillColor()](#getSolidFillColor--) | Returnerar färgen på en solid fyllning. |
| [getGradientFormat()](#getGradientFormat--) | Returnerar gradientfyllningsformatet. |
| [getPatternFormat()](#getPatternFormat--) | Returnerar mönsterfyllningsformatet. |
| [getRotateWithShape()](#getRotateWithShape--) | Bestämmer om fyllningen ska roteras med en form. |
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


Returnerar färgen på en solid fyllning. Skrivskyddad java.awt.Color.

**Returnerar:**
java.awt.Color
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
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```


Bestämmer om fyllningen ska roteras med en form. Skrivskyddad boolean.

**Returnerar:**
boolean