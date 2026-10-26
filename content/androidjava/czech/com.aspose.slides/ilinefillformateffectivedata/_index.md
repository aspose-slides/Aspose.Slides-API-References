---
title: ILineFillFormatEffectiveData
second_title: Aspose.Slides pro Android prostřednictvím Java API
description: Neměnný objekt, který obsahuje efektivní vlastnosti výplně čáry.
type: docs
url: /cs/com.aspose.slides/ilinefillformateffectivedata/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormatEffectiveData extends IFillParamSource
```

Neměnný objekt, který obsahuje efektivní vlastnosti výplně řádku.

--------------------

Toto rozhraní se používá jako součást [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).
## Metody

| Metoda | Popis |
| --- | --- |
| [getFillType()](#getFillType--) | Vrací typ výplně. |
| [getSolidFillColor()](#getSolidFillColor--) | Vrací barvu pevné výplně. |
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
public abstract Integer getSolidFillColor()
```

Vrací barvu pevné výplně. Pouze pro čtení java.lang.Integer.

**Vrací:**
java.lang.Integer
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