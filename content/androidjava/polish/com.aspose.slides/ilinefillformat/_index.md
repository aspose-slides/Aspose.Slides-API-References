---
title: ILineFillFormat
second_title: Aspose.Slides dla Androida - odniesienie API Java
description: Reprezentuje właściwości wypełniania linii.
type: docs
url: /pl/com.aspose.slides/ilinefillformat/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormat extends IFillParamSource
```

Reprezentuje właściwości wypełniania linii.
## Metody

| Metoda | Opis |
| --- | --- |
| [getFillType()](#getFillType--) | Zwraca lub ustawia typ wypełnienia. |
| [setFillType(byte value)](#setFillType-byte-) | Zwraca lub ustawia typ wypełnienia. |
| [getSolidFillColor()](#getSolidFillColor--) | Zwraca kolor jednolitego wypełnienia. |
| [getGradientFormat()](#getGradientFormat--) | Zwraca format wypełnienia gradientowego. |
| [getPatternFormat()](#getPatternFormat--) | Zwraca format wypełnienia wzorcowego. |
| [getRotateWithShape()](#getRotateWithShape--) | Określa, czy wypełnienie powinno być obracane wraz z kształtem. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Określa, czy wypełnienie powinno być obracane wraz z kształtem. |
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

Zwraca kolor jednolitego wypełnienia. Tylko do odczytu [IColorFormat](../../com.aspose.slides/icolorformat).

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

Zwraca format wypełnienia wzorcowego. Tylko do odczytu [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Zwraca:**  
[IPatternFormat](../../com.aspose.slides/ipatternformat)
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