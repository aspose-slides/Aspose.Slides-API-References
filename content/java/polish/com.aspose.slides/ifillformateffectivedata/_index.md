---
title: IFillFormatEffectiveData
second_title: Aspose.Slides dla Java – dokumentacja API
description: Niezmienny obiekt zawierający efektywne właściwości formatowania wypełnienia.
type: docs
url: /pl/com.aspose.slides/ifillformateffectivedata/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormatEffectiveData extends IFillParamSource
```

Niezmienny obiekt zawierający efektywne właściwości formatowania wypełnienia.

--------------------

Ten interfejs jest używany razem z interfejsem [IFillFormat](../../com.aspose.slides/ifillformat) do zwracania efektywnych wartości formatowania z zastosowanym dziedziczeniem.
## Metody

| Method | Description |
| --- | --- |
| [getFillType()](#getFillType--) | Zwraca typ wypełnienia. |
| [getSolidFillColor()](#getSolidFillColor--) | Zwraca kolor wypełnienia. |
| [getSolidFillSchemeColor()](#getSolidFillSchemeColor--) | Pobiera kolor wypełnienia zdefiniowany przez schemat kolorów. |
| [getGradientFormat()](#getGradientFormat--) | Zwraca format wypełnienia gradientowego. |
| [getPatternFormat()](#getPatternFormat--) | Zwraca format wypełnienia wzoru. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Zwraca format wypełnienia obrazu. |
| [getRotateWithShape()](#getRotateWithShape--) | Określa, czy wypełnienie powinno być obracane wraz z kształtem. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


Zwraca typ wypełnienia. Tylko do odczytu [FillType](../../com.aspose.slides/filltype).

**Zwraca:**
byte
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Color getSolidFillColor()
```


Zwraca kolor wypełnienia. Tylko do odczytu java.awt.Color.

**Zwraca:**
java.awt.Color
### getSolidFillSchemeColor() {#getSolidFillSchemeColor--}
```
public abstract int getSolidFillSchemeColor()
```


Pobiera kolor wypełnienia zdefiniowany przez schemat kolorów. Wartość [SchemeColor.NotDefined](../../com.aspose.slides/schemecolor\#NotDefined) wskazuje, że SolidFillColor (\#getSolidFillColor.getSolidFillColor) nie jest kolorem schematu. Tylko do odczytu [SchemeColor](../../com.aspose.slides/schemecolor).

**Zwraca:**
int
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```


Zwraca format wypełnienia gradientowego. Tylko do odczytu [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata).

**Zwraca:**
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```


Zwraca format wypełnienia wzoru. Tylko do odczytu [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata).

**Zwraca:**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormatEffectiveData getPictureFillFormat()
```


Zwraca format wypełnienia obrazu. Tylko do odczytu [IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata).

**Zwraca:**
[IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```


Określa, czy wypełnienie powinno być obracane razem z kształtem. Tylko do odczytu boolean.

**Zwraca:**
boolean