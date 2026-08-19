---
title: IFillFormat
second_title: Aspose.Slides pro Java – referenční příručka API
description: Reprezentuje možnosti formátování výplně.
type: docs
url: /cs/com.aspose.slides/ifillformat/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormat extends IFillParamSource
```

Reprezentuje možnosti formátování výplně.
## Metody

| Metoda | Popis |
| --- | --- |
| [getFillType()](#getFillType--) | Vrací nebo nastavuje typ výplně. |
| [setFillType(byte value)](#setFillType-byte-) | Vrací nebo nastavuje typ výplně. |
| [getSolidFillColor()](#getSolidFillColor--) | Vrací barvu výplně. |
| [getGradientFormat()](#getGradientFormat--) | Vrací formát gradientní výplně. |
| [getPatternFormat()](#getPatternFormat--) | Vrací formát vzorové výplně. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Vrací formát obrázkové výplně. |
| [getRotateWithShape()](#getRotateWithShape--) | Určuje, zda by měla být výplň otáčena s tvarem. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Určuje, zda by měla být výplň otáčena s tvarem. |
| [getEffective()](#getEffective--) | Získá efektivní data formátování výplně s aplikovaným děděním. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```

Vrací nebo nastavuje typ výplně. Čtení/zápis [FillType](../../com.aspose.slides/filltype).

**Vrací:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public abstract void setFillType(byte value)
```

Vrací nebo nastavuje typ výplně. Čtení/zápis [FillType](../../com.aspose.slides/filltype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract IColorFormat getSolidFillColor()
```

Vrací barvu výplně. Pouze ke čtení [IColorFormat](../../com.aspose.slides/icolorformat).

**Vrací:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormat getGradientFormat()
```

Vrací formát gradientní výplně. Pouze ke čtení [IGradientFormat](../../com.aspose.slides/igradientformat).

**Vrací:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormat getPatternFormat()
```

Vrací formát vzorové výplně. Pouze ke čtení [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Vrací:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormat getPictureFillFormat()
```

Vrací formát obrázkové výplně. Pouze ke čtení [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Vrací:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract byte getRotateWithShape()
```

Určuje, zda by měla být výplň otáčena s tvarem. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public abstract void setRotateWithShape(byte value)
```

Určuje, zda by měla být výplň otáčena s tvarem. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |
### getEffective() {#getEffective--}
```
public abstract IFillFormatEffectiveData getEffective()
```

Získá efektivní data formátování výplně s aplikovaným děděním.

**Vrací:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) - A [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).