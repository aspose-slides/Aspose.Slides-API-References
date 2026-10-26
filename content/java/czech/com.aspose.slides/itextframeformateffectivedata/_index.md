---
title: ITextFrameFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Neměnný objekt, který obsahuje efektivní vlastnosti formátování textového rámce.
type: docs
url: /cs/com.aspose.slides/itextframeformateffectivedata/
---```
public interface ITextFrameFormatEffectiveData
```

Neměnný objekt, který obsahuje efektivní vlastnosti formátování textového rámce.

--------------------

Toto rozhraní se používá spolu s rozhraním [ITextFrameFormat](../../com.aspose.slides/itextframeformat) k vrácení efektivních hodnot formátování s aplikovaným děděním.
## Metody

| Metoda | Popis |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | Vrací účinný styl textu. |
| [getMarginLeft()](#getMarginLeft--) | Vrací levý okraj (body) v TextFrame. |
| [getMarginRight()](#getMarginRight--) | Vrací pravý okraj (body) v TextFrame. |
| [getMarginTop()](#getMarginTop--) | Vrací horní okraj (body) v TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Vrací spodní okraj (body) v TextFrame. |
| [getWrapText()](#getWrapText--) | Vrací, zda je text zalamován na okrajích TextFrame. |
| [getAnchoringType()](#getAnchoringType--) | Vrací vertikální kotvu textu v TextFrame. |
| [getCenterText()](#getCenterText--) | Vrací, zda má být text vodorovně vycentrován v boxu. |
| [getTextVerticalType()](#getTextVerticalType--) | Vrací orientaci textu. |
| [getAutofitType()](#getAutofitType--) | Vrací režim automatického přizpůsobení textu. |
| [getColumnCount()](#getColumnCount--) | Určuje počet sloupců textu v ohraničujícím obdélníku. |
| [getColumnSpacing()](#getColumnSpacing--) | Určuje prostor mezi sloupci textu v oblasti textu (v bodech). |
### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyleEffectiveData getTextStyle()
```

Vrací účinný styl textu. Pouze pro čtení [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).

**Vrací:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata)
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

Vrací levý okraj (body) v TextFrame. Pouze pro čtení double.

**Vrací:**
double
### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

Vrací pravý okraj (body) v TextFrame. Pouze pro čtení double.

**Vrací:**
double
### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

Vrací horní okraj (body) v TextFrame. Pouze pro čtení double.

**Vrací:**
double
### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

Vrací spodní okraj (body) v TextFrame. Pouze pro čtení double.

**Vrací:**
double
### getWrapText() {#getWrapText--}
```
public abstract boolean getWrapText()
```

Vrací, zda je text zalamován na okrajích TextFrame. Pouze pro čtení boolean.

**Vrací:**
boolean
### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

Vrací vertikální kotvu textu v TextFrame. Pouze pro čtení [TextAnchorType](../../com.aspose.slides/textanchortype).

**Vrací:**
byte
### getCenterText() {#getCenterText--}
```
public abstract boolean getCenterText()
```

Vrací, zda má být text vodorovně vycentrován v boxu. Pouze pro čtení boolean.

**Vrací:**
boolean
### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

Vrací orientaci textu. Pouze pro čtení [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Vrací:**
byte
### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

Vrací režim automatického přizpůsobení textu. Pouze pro čtení [TextAutofitType](../../com.aspose.slides/textautofittype).

**Vrací:**
byte
### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```

Určuje počet sloupců textu v ohraničujícím obdélníku. Pouze pro čtení int.

**Vrací:**
int
### getColumnSpacing() {#getColumnSpacing--}
```
public abstract float getColumnSpacing()
```

Určuje prostor mezi sloupci textu v oblasti textu (v bodech). Pouze pro čtení float.

**Vrací:**
float