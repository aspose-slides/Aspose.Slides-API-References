---
title: IFillFormatEffectiveData
second_title: Aspose.Slides pro Java API Reference
description: Neměnný objekt, který obsahuje efektivní vlastnosti formátování výplně.
type: docs
url: /cs/com.aspose.slides/ifillformateffectivedata/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormatEffectiveData extends IFillParamSource
```

Neměnný objekt, který obsahuje efektivní vlastnosti formátování výplně.

--------------------

Toto rozhraní se používá spolu s rozhraním [IFillFormat](../../com.aspose.slides/ifillformat) k vrácení efektivních hodnot formátování s použitou dědičností.
## Metody

| Metoda | Popis |
| --- | --- |
| [getFillType()](#getFillType--) | Vrací typ výplně. |
| [getSolidFillColor()](#getSolidFillColor--) | Vrací barvu výplně. |
| [getSolidFillSchemeColor()](#getSolidFillSchemeColor--) | Získává barvu výplně definovanou barevným schématem. |
| [getGradientFormat()](#getGradientFormat--) | Vrací formát gradientové výplně. |
| [getPatternFormat()](#getPatternFormat--) | Vrací formát vzorové výplně. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Vrací formát obrázkové výplně. |
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

Vrací barvu výplně. Pouze pro čtení java.awt.Color.

**Vrací:**
java.awt.Color
### getSolidFillSchemeColor() {#getSolidFillSchemeColor--}
```
public abstract int getSolidFillSchemeColor()
```

Získává barvu výplně definovanou barevným schématem. Hodnota [SchemeColor.NotDefined](../../com.aspose.slides/schemecolor\#NotDefined) označuje, že SolidFillColor (\#getSolidFillColor.getSolidFillColor) není barva schématu. Pouze pro čtení [SchemeColor](../../com.aspose.slides/schemecolor).

**Vrací:**
int
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
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormatEffectiveData getPictureFillFormat()
```

Vrací formát obrázkové výplně. Pouze pro čtení [IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata).

**Vrací:**
[IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```

Určuje, zda má být výplň otáčena spolu s tvarem. Pouze pro čtení boolean.

**Vrací:**
boolean