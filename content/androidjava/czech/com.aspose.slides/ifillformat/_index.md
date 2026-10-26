---
title: IFillFormat
second_title: Aspose.Slides pro Android přes Java API Reference
description: Představuje možnosti formátování výplně.
type: docs
url: /cs/com.aspose.slides/ifillformat/
---
**All Implemented Interfaces:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormat extends IFillParamSource
```

Představuje možnosti formátování výplně.
## Metody

| Method | Description |
| --- | --- |
| [getFillType()](#getFillType--) | Vrací nebo nastavuje typ výplně. |
| [setFillType(byte value)](#setFillType-byte-) | Vrací nebo nastavuje typ výplně. |
| [getSolidFillColor()](#getSolidFillColor--) | Vrací barvu výplně. |
| [getGradientFormat()](#getGradientFormat--) | Vrací formát gradientové výplně. |
| [getPatternFormat()](#getPatternFormat--) | Vrací formát vzorové výplně. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Vrací formát obrázkové výplně. |
| [getRotateWithShape()](#getRotateWithShape--) | Určuje, zda má být výplň otáčena s tvarem. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Určuje, zda má být výplň otáčena s tvarem. |
| [getEffective()](#getEffective--) | Získá účinná data formátování výplně s aplikovaným děděním. |
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
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract IColorFormat getSolidFillColor()
```

Vrací barvu výplně. Pouze pro čtení [IColorFormat](../../com.aspose.slides/icolorformat).

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
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormat getPictureFillFormat()
```

Vrací formát obrázkové výplně. Pouze pro čtení [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Vrací:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract byte getRotateWithShape()
```

Určuje, zda má být výplň otáčena s tvarem. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public abstract void setRotateWithShape(byte value)
```

Určuje, zda má být výplň otáčena s tvarem. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getEffective() {#getEffective--}
```
public abstract IFillFormatEffectiveData getEffective()
```

Získá účinná data formátování výplně s aplikovaným děděním.

**Vrací:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) - a [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).