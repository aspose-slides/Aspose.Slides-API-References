---
title: ILineFillFormatEffectiveData
second_title: Aspose.Slides för Android via Java API-referens
description: Oföränderligt objekt som innehåller effektiva radfyllningsegenskaper.
type: docs
url: /sv/com.aspose.slides/ilinefillformateffectivedata/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormatEffectiveData extends IFillParamSource
```

Oföränderligt objekt som innehåller effektiva radfyllningsegenskaper.

--------------------

Detta gränssnitt används som en del av [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFillType()](#getFillType--) | Returnerar fyllningstypen. |
| [getSolidFillColor()](#getSolidFillColor--) | Returnerar färgen för en solid fyllning. |
| [getGradientFormat()](#getGradientFormat--) | Returnerar gradientfyllningsformatet. |
| [getPatternFormat()](#getPatternFormat--) | Returnerar mönsterfyllningsformatet. |
| [getRotateWithShape()](#getRotateWithShape--) | Avgör om fyllningen ska roteras med en form. |
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

Returnerar färgen för en solid fyllning. Skrivskyddad java.lang.Integer.

**Returnerar:**
java.lang.Integer
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

Avgör om fyllningen ska roteras med en form. Skrivskyddad boolean.

**Returnerar:**
boolean