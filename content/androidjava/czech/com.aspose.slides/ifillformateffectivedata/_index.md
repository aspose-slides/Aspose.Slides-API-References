---
title: IFillFormatEffectiveData
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Neměnný objekt, který obsahuje efektivní vlastnosti formátování výplně.
type: docs
url: /cs/com.aspose.slides/ifillformateffectivedata/
---
**Všechna implementovaná rozhraní:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormatEffectiveData extends IFillParamSource
```

Neměnný objekt, který obsahuje efektivní vlastnosti formátování výplně.

--------------------

Toto rozhraní se používá spolu s rozhraním [IFillFormat](../../com.aspose.slides/ifillformat) k vrácení efektivních hodnot formátování s použitím dědičnosti.
## Metody

| Metoda | Popis |
| --- | --- |
| [getFillType()](#getFillType--) | Returns the type of filling. |
| [getSolidFillColor()](#getSolidFillColor--) | Returns the fill color. |
| [getSolidFillSchemeColor()](#getSolidFillSchemeColor--) | Gets the fill color defined by a color scheme. |
| [getGradientFormat()](#getGradientFormat--) | Returns the gradient fill format. |
| [getPatternFormat()](#getPatternFormat--) | Returns the pattern fill format. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Returns the picture fill format. |
| [getRotateWithShape()](#getRotateWithShape--) | Determines whether the fill should be rotated with shape. |
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


Vrací barvu výplně. Pouze pro čtení java.lang.Integer.

**Vrací:**
java.lang.Integer
### getSolidFillSchemeColor() {#getSolidFillSchemeColor--}
```
public abstract int getSolidFillSchemeColor()
```


Získává barvu výplně definovanou barevným schématem. Hodnota [SchemeColor.NotDefined](../../com.aspose.slides/schemecolor\#NotDefined) naznačuje, že SolidFillColor (\#getSolidFillColor.getSolidFillColor) není barva ze schématu. Pouze pro čtení [SchemeColor](../../com.aspose.slides/schemecolor).

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


Určuje, zda má být výplň otočena spolu s tvarem. Pouze pro čtení boolean.

**Vrací:**
boolean