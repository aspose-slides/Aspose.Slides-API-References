---
title: LineFillFormat
second_title: Aspose.Slides dla Androida poprzez Odwołanie do API Java
description: Reprezentuje właściwości wypełniania linii.
type: docs
url: /pl/com.aspose.slides/linefillformat/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ILineFillFormat](../../com.aspose.slides/ilinefillformat)
```
public final class LineFillFormat extends PVIObject implements ILineFillFormat
```

Reprezentuje właściwości wypełniania linii.
## Metody

| Metoda | Opis |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillType()](#getFillType--) | Zwraca lub ustawia typ wypełnienia. |
| [setFillType(byte value)](#setFillType-byte-) | Zwraca lub ustawia typ wypełnienia. |
| [getRotateWithShape()](#getRotateWithShape--) | Określa, czy wypełnienie powinno być obracane razem z kształtem. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Określa, czy wypełnienie powinno być obracane razem z kształtem. |
| [getSolidFillColor()](#getSolidFillColor--) | Zwraca kolor jednolitego wypełnienia. |
| [getGradientFormat()](#getGradientFormat--) | Zwraca format wypełnienia gradientowego. |
| [getPatternFormat()](#getPatternFormat--) | Zwraca format wypełnienia wzorem. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Wersja. Tylko do odczytu long.

**Zwraca:**
long
### getFillType() {#getFillType--}
```
public final byte getFillType()
```

Zwraca lub ustawia typ wypełnienia. Odczyt/zapis [FillType](../../com.aspose.slides/filltype).

**Zwraca:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public final void setFillType(byte value)
```

Zwraca lub ustawia typ wypełnienia. Odczyt/zapis [FillType](../../com.aspose.slides/filltype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |
### getRotateWithShape() {#getRotateWithShape--}
```
public final byte getRotateWithShape()
```

Określa, czy wypełnienie powinno być obracane razem z kształtem. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Zwraca:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public final void setRotateWithShape(byte value)
```

Określa, czy wypełnienie powinno być obracane razem z kształtem. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |
### getSolidFillColor() {#getSolidFillColor--}
```
public final IColorFormat getSolidFillColor()
```

Zwraca kolor jednolitego wypełnienia. Tylko do odczytu [IColorFormat](../../com.aspose.slides/icolorformat).

**Zwraca:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public final IGradientFormat getGradientFormat()
```

Zwraca format wypełnienia gradientowego. Tylko do odczytu [IGradientFormat](../../com.aspose.slides/igradientformat).

**Zwraca:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public final IPatternFormat getPatternFormat()
```

Zwraca format wypełnienia wzorem. Tylko do odczytu [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Zwraca:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)