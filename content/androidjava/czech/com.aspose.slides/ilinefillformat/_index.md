---
title: ILineFillFormat
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Reprezentuje vlastnosti pro vyplňování čar.
type: docs
url: /cs/com.aspose.slides/ilinefillformat/
---
**Všechna implementovaná rozhraní:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormat extends IFillParamSource
```

Representuje vlastnosti pro vyplňování čar.
## Metody

| Metoda | Popis |
| --- | --- |
| [getFillType()](#getFillType--) | Vrací nebo nastavuje typ výplně. |
| [setFillType(byte value)](#setFillType-byte-) | Vrací nebo nastavuje typ výplně. |
| [getSolidFillColor()](#getSolidFillColor--) | Vrací barvu plné výplně. |
| [getGradientFormat()](#getGradientFormat--) | Vrací formát gradientové výplně. |
| [getPatternFormat()](#getPatternFormat--) | Vrací formát vzorové výplně. |
| [getRotateWithShape()](#getRotateWithShape--) | Určuje, zda má být výplň otáčena spolu s tvarem. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Určuje, zda má být výplň otáčena spolu s tvarem. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


Vrací nebo nastavuje typ výplně. Číst/Zapisovat [FillType](../../com.aspose.slides/filltype).

**Vrací:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public abstract void setFillType(byte value)
```


Vrací nebo nastavuje typ výplně. Číst/Zapisovat [FillType](../../com.aspose.slides/filltype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getSolidFillColor() {#getSolidFillColor--}
```
public abstract IColorFormat getSolidFillColor()
```


Vrací barvu plné výplně. Pouze pro čtení [IColorFormat](../../com.aspose.slides/icolorformat).

**Vrací:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormat getGradientFormat()
```


Vrací formát gradientové výplně. Pouze pro čtení [IGradientFormat](../../com.aspose.slides/igradientformat).

**Vrací:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormat getPatternFormat()
```


Vrací formát vzorové výplně. Pouze pro čtení [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Vrací:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract byte getRotateWithShape()
```


Určuje, zda má být výplň otáčena spolu s tvarem. Číst/Zapisovat [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public abstract void setRotateWithShape(byte value)
```


Určuje, zda má být výplň otáčena spolu s tvarem. Číst/Zapisovat [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |