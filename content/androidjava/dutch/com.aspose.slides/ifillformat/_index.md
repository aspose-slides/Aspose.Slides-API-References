---
title: IFillFormat
second_title: Aspose.Slides voor Android via Java API-referentie
description: Vertegenwoordigt een vulopmaakoptie.
type: docs
url: /nl/com.aspose.slides/ifillformat/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormat extends IFillParamSource
```

Vertegenwoordigt een vulopmaakoptie.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getFillType()](#getFillType--) | Retourneert of stelt het type vulling in. |
| [setFillType(byte value)](#setFillType-byte-) | Retourneert of stelt het type vulling in. |
| [getSolidFillColor()](#getSolidFillColor--) | Retourneert de vulkleur. |
| [getGradientFormat()](#getGradientFormat--) | Retourneert het verloopvulopmaak. |
| [getPatternFormat()](#getPatternFormat--) | Retourneert het patroonvulopmaak. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Retourneert het afbeeldingsvulopmaak. |
| [getRotateWithShape()](#getRotateWithShape--) | Bepaalt of de vulling met de vorm moet roteren. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Bepaalt of de vulling met de vorm moet roteren. |
| [getEffective()](#getEffective--) | Haalt de effectieve vulopmaakgegevens op met de toegepaste overerving. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```

Retourneert of stelt het type vulling in. Lezen/Schrijven [FillType](../../com.aspose.slides/filltype).

**Retour:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public abstract void setFillType(byte value)
```

Retourneert of stelt het type vulling in. Lezen/Schrijven [FillType](../../com.aspose.slides/filltype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract IColorFormat getSolidFillColor()
```

Retourneert de vulkleur. Alleen-lezen [IColorFormat](../../com.aspose.slides/icolorformat).

**Retour:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormat getGradientFormat()
```

Retourneert het verloopvulopmaak. Alleen-lezen [IGradientFormat](../../com.aspose.slides/igradientformat).

**Retour:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormat getPatternFormat()
```

Retourneert het patroonvulopmaak. Alleen-lezen [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Retour:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormat getPictureFillFormat()
```

Retourneert het afbeeldingsvulopmaak. Alleen-lezen [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Retour:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract byte getRotateWithShape()
```

Bepaalt of de vulling met de vorm moet roteren. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retour:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public abstract void setRotateWithShape(byte value)
```

Bepaalt of de vulling met de vorm moet roteren. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |
### getEffective() {#getEffective--}
```
public abstract IFillFormatEffectiveData getEffective()
```

Haalt de effectieve vulopmaakgegevens op met de toegepaste overerving.

**Retour:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) - A [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).