---
title: IFillFormat
second_title: Aspose.Slides dla Androida - odniesienie API Java
description: Reprezentuje opcje formatowania wypełnienia.
type: docs
url: /pl/com.aspose.slides/ifillformat/
---
**Wszystkie implementowane interfejsy:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormat extends IFillParamSource
```

Reprezentuje opcje formatowania wypełnienia.
## Metody

| Metoda | Opis |
| --- | --- |
| [getFillType()](#getFillType--) | Zwraca lub ustawia typ wypełnienia. |
| [setFillType(byte value)](#setFillType-byte-) | Zwraca lub ustawia typ wypełnienia. |
| [getSolidFillColor()](#getSolidFillColor--) | Zwraca kolor wypełnienia. |
| [getGradientFormat()](#getGradientFormat--) | Zwraca format wypełnienia gradientowego. |
| [getPatternFormat()](#getPatternFormat--) | Zwraca format wypełnienia wzoru. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Zwraca format wypełnienia obrazu. |
| [getRotateWithShape()](#getRotateWithShape--) | Określa, czy wypełnienie powinno być obracane wraz z kształtem. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Określa, czy wypełnienie powinno być obracane wraz z kształtem. |
| [getEffective()](#getEffective--) | Pobiera skuteczne dane formatowania wypełnienia z zastosowanym dziedziczeniem. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


Zwraca lub ustawia typ wypełnienia. Odczyt/zapis [FillType](../../com.aspose.slides/filltype).

**Zwraca:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public abstract void setFillType(byte value)
```


Zwraca lub ustawia typ wypełnienia. Odczyt/zapis [FillType](../../com.aspose.slides/filltype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getSolidFillColor() {#getSolidFillColor--}
```
public abstract IColorFormat getSolidFillColor()
```


Zwraca kolor wypełnienia. Tylko do odczytu [IColorFormat](../../com.aspose.slides/icolorformat).

**Zwraca:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormat getGradientFormat()
```


Zwraca format wypełnienia gradientowego. Tylko do odczytu [IGradientFormat](../../com.aspose.slides/igradientformat).

**Zwraca:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormat getPatternFormat()
```


Zwraca format wypełnienia wzoru. Tylko do odczytu [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Zwraca:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormat getPictureFillFormat()
```


Zwraca format wypełnienia obrazu. Tylko do odczytu [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Zwraca:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract byte getRotateWithShape()
```


Określa, czy wypełnienie powinno być obracane wraz z kształtem. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Zwraca:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public abstract void setRotateWithShape(byte value)
```


Określa, czy wypełnienie powinno być obracane wraz z kształtem. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getEffective() {#getEffective--}
```
public abstract IFillFormatEffectiveData getEffective()
```


Pobiera skuteczne dane formatowania wypełnienia z zastosowanym dziedziczeniem.

**Zwraca:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) - [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).