---
title: ILineFillFormatEffectiveData
second_title: Aspose.Slides pro Java – referenční příručka API
description: Neměnný objekt, který obsahuje účinné vlastnosti vyplňování řádků.
type: docs
url: /cs/com.aspose.slides/ilinefillformateffectivedata/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormatEffectiveData extends IFillParamSource
```

Neměnný objekt, který obsahuje účinné vlastnosti vyplňování řádků.

--------------------

Toto rozhraní se používá jako součást [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).
## Metody

| Metoda | Popis |
| --- | --- |
| [getFillType()](#getFillType--) | Vrací typ výplně. |
| [getSolidFillColor()](#getSolidFillColor--) | Vrací barvu plné výplně. |
| [getGradientFormat()](#getGradientFormat--) | Vrací formát gradientové výplně. |
| [getPatternFormat()](#getPatternFormat--) | Vrací formát vzorové výplně. |
| [getRotateWithShape()](#getRotateWithShape--) | Určuje, zda má být výplň otáčena spolu s tvarem. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


Vrací typ výplně. Pouze pro čtení [FillType](../../com.aspose.slides/filltype).

**Vrací:**
byte
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Color getSolidFillColor()
```


Vrací barvu plné výplně. Pouze pro čtení java.awt.Color.

**Vrací:**
java.awt.Color
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```


Vrací formát gradientové výplně. Pouze pro čtení [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata).

**Vrací:**
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```


Vrací formát vzorové výplně. Pouze pro čtení [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata).

**Vrací:**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```


Určuje, zda má být výplň otáčena spolu s tvarem. Pouze pro čtení boolean.

**Vrací:**
boolean