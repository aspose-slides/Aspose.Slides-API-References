---
title: ILineFillFormatEffectiveData
second_title: Aspose.Slides dla Androida poprzez referencję Java API
description: Niezmienny obiekt, który zawiera efektywne właściwości wypełniania linii.
type: docs
url: /pl/com.aspose.slides/ilinefillformateffectivedata/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormatEffectiveData extends IFillParamSource
```

Niezmienny obiekt, który zawiera efektywne właściwości wypełniania linii.

--------------------

Ten interfejs jest używany jako część [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).
## Metody

| Metoda | Opis |
| --- | --- |
| [getFillType()](#getFillType--) | Zwraca typ wypełnienia. |
| [getSolidFillColor()](#getSolidFillColor--) | Zwraca kolor jednolitego wypełnienia. |
| [getGradientFormat()](#getGradientFormat--) | Zwraca format wypełnienia gradientowego. |
| [getPatternFormat()](#getPatternFormat--) | Zwraca format wypełnienia wzoru. |
| [getRotateWithShape()](#getRotateWithShape--) | Określa, czy wypełnienie powinno być obracane razem z kształtem. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


Zwraca typ wypełnienia. Tylko do odczytu [FillType](../../com.aspose.slides/filltype).

**Zwraca:**
byte
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Integer getSolidFillColor()
```


Zwraca kolor jednolitego wypełnienia. Tylko do odczytu java.lang.Integer.

**Zwraca:**
java.lang.Integer
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
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```


Określa, czy wypełnienie powinno być obracane razem z kształtem. Tylko do odczytu boolean.

**Zwraca:**
boolean