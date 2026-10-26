---
title: ILineFillFormat
second_title: Aspose.Slides voor Android via Java API-referentie
description: Vertegenwoordigt eigenschappen voor het vullen van lijnen.
type: docs
url: /nl/com.aspose.slides/ilinefillformat/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormat extends IFillParamSource
```

Vertegenwoordigt eigenschappen voor het vullen van lijnen.
## Methoden

| Method | Description |
| --- | --- |
| [getFillType()](#getFillType--) | Retourneert of stelt het vultype in. |
| [setFillType(byte value)](#setFillType-byte-) | Retourneert of stelt het vultype in. |
| [getSolidFillColor()](#getSolidFillColor--) | Retourneert de kleur van een eenkleurige vulling. |
| [getGradientFormat()](#getGradientFormat--) | Retourneert het gradientvullingsformaat. |
| [getPatternFormat()](#getPatternFormat--) | Retourneert het patroonvullingsformaat. |
| [getRotateWithShape()](#getRotateWithShape--) | Bepaalt of de vulling moet roteren met een vorm. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Bepaalt of de vulling moet roteren met een vorm. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```

Retourneert of stelt het vultype in. Lezen/Schrijven [FillType](../../com.aspose.slides/filltype).

**Retour:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public abstract void setFillType(byte value)
```

Retourneert of stelt het vultype in. Lezen/Schrijven [FillType](../../com.aspose.slides/filltype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract IColorFormat getSolidFillColor()
```

Retourneert de kleur van een eenkleurige vulling. Alleen-lezen [IColorFormat](../../com.aspose.slides/icolorformat).

**Retour:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormat getGradientFormat()
```

Retourneert het gradientvullingsformaat. Alleen-lezen [IGradientFormat](../../com.aspose.slides/igradientformat).

**Retour:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormat getPatternFormat()
```

Retourneert het patroonvullingsformaat. Alleen-lezen [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Retour:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract byte getRotateWithShape()
```

Bepaalt of de vulling moet roteren met een vorm. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retour:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public abstract void setRotateWithShape(byte value)
```

Bepaalt of de vulling moet roteren met een vorm. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |