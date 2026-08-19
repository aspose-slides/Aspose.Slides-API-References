---
title: IFillFormat
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een vulopmaakoptie voor.
type: docs
url: /nl/com.aspose.slides/ifillformat/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormat extends IFillParamSource
```

Stelt een vulopmaakoptie voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getFillType()](#getFillType--) | Geeft de vultype terug of stelt deze in. |
| [setFillType(byte value)](#setFillType-byte-) | Geeft de vultype terug of stelt deze in. |
| [getSolidFillColor()](#getSolidFillColor--) | Geeft de vulkleur terug. |
| [getGradientFormat()](#getGradientFormat--) | Geeft het verloopvulformaat terug. |
| [getPatternFormat()](#getPatternFormat--) | Geeft het patroonvulformaat terug. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Geeft het afbeeldingsvulformaat terug. |
| [getRotateWithShape()](#getRotateWithShape--) | Bepaalt of de vulling moet roteren met de vorm. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Bepaalt of de vulling moet roteren met de vorm. |
| [getEffective()](#getEffective--) | Haalt de effectieve vulopmaakgegevens op met de toegepaste overerving. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


Geeft de vultype terug of stelt deze in. Lezen/schrijven [FillType](../../com.aspose.slides/filltype).

**Retour:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public abstract void setFillType(byte value)
```


Geeft de vultype terug of stelt deze in. Lezen/schrijven [FillType](../../com.aspose.slides/filltype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getSolidFillColor() {#getSolidFillColor--}
```
public abstract IColorFormat getSolidFillColor()
```


Geeft de vulkleur terug. Alleen-lezen [IColorFormat](../../com.aspose.slides/icolorformat).

**Retour:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormat getGradientFormat()
```


Geeft het verloopvulformaat terug. Alleen-lezen [IGradientFormat](../../com.aspose.slides/igradientformat).

**Retour:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormat getPatternFormat()
```


Geeft het patroonvulformaat terug. Alleen-lezen [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Retour:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormat getPictureFillFormat()
```


Geeft het afbeeldingsvulformaat terug. Alleen-lezen [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Retour:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract byte getRotateWithShape()
```


Bepaalt of de vulling moet roteren met de vorm. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retour:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public abstract void setRotateWithShape(byte value)
```


Bepaalt of de vulling moet roteren met de vorm. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

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
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) - Een [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).