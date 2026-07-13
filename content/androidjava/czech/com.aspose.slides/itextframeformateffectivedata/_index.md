---
title: ITextFrameFormatEffectiveData
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Neměnný objekt, který obsahuje efektivní vlastnosti formátování textového rámce.
type: docs
url: /cs/com.aspose.slides/itextframeformateffectivedata/
---```
public interface ITextFrameFormatEffectiveData
```

Neměnný objekt, který obsahuje efektivní vlastnosti formátování textového rámce.

--------------------

This interface is used together with the [ITextFrameFormat](../../com.aspose.slides/itextframeformat) interface to return effective formatting values with inheritance applied.
## Metody

| Method | Description |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | Vrací efektivní styl textu. |
| [getMarginLeft()](#getMarginLeft--) | Vrací levý okraj (v bodech) v TextFrame. |
| [getMarginRight()](#getMarginRight--) | Vrací pravý okraj (v bodech) v TextFrame. |
| [getMarginTop()](#getMarginTop--) | Vrací horní okraj (v bodech) v TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Vrací dolní okraj (v bodech) v TextFrame. |
| [getWrapText()](#getWrapText--) | Vrací, zda je text zalamován na okrajích TextFrame. |
| [getAnchoringType()](#getAnchoringType--) | Vrací vertikální kotvení textu v TextFrame. |
| [getCenterText()](#getCenterText--) | Vrací, zda by měl být text horizontálně vycentrován v rámečku. |
| [getTextVerticalType()](#getTextVerticalType--) | Vrací orientaci textu. |
| [getAutofitType()](#getAutofitType--) | Vrací režim automatického přizpůsobení textu. |
| [getColumnCount()](#getColumnCount--) | Určuje počet sloupců textu v ohraničujícím obdélníku. |
| [getColumnSpacing()](#getColumnSpacing--) | Určuje prostor mezi sloupci textu v textové oblasti (v bodech). |
### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyleEffectiveData getTextStyle()
```


Vrací efektivní styl textu. Pouze pro čtení [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).

**Vrací:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata)
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```


Vrací levý okraj (v bodech) v TextFrame. Pouze pro čtení double.

**Vrací:**
double
### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```


Vrací pravý okraj (v bodech) v TextFrame. Pouze pro čtení double.

**Vrací:**
double
### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```


Vrací horní okraj (v bodech) v TextFrame. Pouze pro čtení double.

**Vrací:**
double
### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```


Vrací dolní okraj (v bodech) v TextFrame. Pouze pro čtení double.

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


Vrací vertikální kotvení textu v TextFrame. Pouze pro čtení [TextAnchorType](../../com.aspose.slides/textanchortype).

**Vrací:**
byte
### getCenterText() {#getCenterText--}
```
public abstract boolean getCenterText()
```


Vrací, zda by měl být text horizontálně vycentrován v rámečku. Pouze pro čtení boolean.

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


Určuje prostor mezi sloupci textu v textové oblasti (v bodech). Pouze pro čtení float.

**Vrací:**
float