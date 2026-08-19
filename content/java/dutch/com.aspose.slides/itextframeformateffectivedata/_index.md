---
title: ITextFrameFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Onveranderlijk object dat effectieve tekstkaderopmaak-eigenschappen bevat.
type: docs
url: /nl/com.aspose.slides/itextframeformateffectivedata/
---```
public interface ITextFrameFormatEffectiveData
```

Onveranderlijk object dat effectieve tekstkaderopmaak-eigenschappen bevat.

--------------------

Deze interface wordt samen met de [ITextFrameFormat](../../com.aspose.slides/itextframeformat) interface gebruikt om effectieve opmaakwaarden met overerving toegepast terug te geven.
## Methoden

| Method | Description |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | Retourneert de effectieve tekststijl. |
| [getMarginLeft()](#getMarginLeft--) | Retourneert de linkermarge (punten) in een TextFrame. |
| [getMarginRight()](#getMarginRight--) | Retourneert de rechtermarge (punten) in een TextFrame. |
| [getMarginTop()](#getMarginTop--) | Retourneert de bovemarge (punten) in een TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Retourneert de ondermarge (punten) in een TextFrame. |
| [getWrapText()](#getWrapText--) | Retourneert of tekst wordt afgebroken bij de marges van de TextFrame. |
| [getAnchoringType()](#getAnchoringType--) | Retourneert verticale ankertekst in een TextFrame. |
| [getCenterText()](#getCenterText--) | Retourneert of tekst horizontaal gecentreerd moet worden in de box. |
| [getTextVerticalType()](#getTextVerticalType--) | Retourneert de tekstoriëntatie. |
| [getAutofitType()](#getAutofitType--) | Retourneert de tekst-autofit-modus. |
| [getColumnCount()](#getColumnCount--) | Specificeert het aantal kolommen tekst in de omvattende rechthoek. |
| [getColumnSpacing()](#getColumnSpacing--) | Specificeert de ruimte tussen tekstkolommen in het tekstgebied (in punten). |
### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyleEffectiveData getTextStyle()
```


Retourneert de effectieve tekststijl. Alleen-lezen [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).

**Retourneert:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata)
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```


Retourneert de linkermarge (punten) in een TextFrame. Alleen-lezen double.

**Retourneert:**
double
### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```


Retourneert de rechtermarge (punten) in een TextFrame. Alleen-lezen double.

**Retourneert:**
double
### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```


Retourneert de bovemarge (punten) in een TextFrame. Alleen-lezen double.

**Retourneert:**
double
### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```


Retourneert de ondermarge (punten) in een TextFrame. Alleen-lezen double.

**Retourneert:**
double
### getWrapText() {#getWrapText--}
```
public abstract boolean getWrapText()
```


Retourneert of tekst wordt afgebroken bij de marges van de TextFrame. Alleen-lezen boolean.

**Retourneert:**
boolean
### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```


Retourneert verticale ankertekst in een TextFrame. Alleen-lezen [TextAnchorType](../../com.aspose.slides/textanchortype).

**Retourneert:**
byte
### getCenterText() {#getCenterText--}
```
public abstract boolean getCenterText()
```


Retourneert of tekst horizontaal gecentreerd moet worden in de box. Alleen-lezen boolean.

**Retourneert:**
boolean
### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```


Retourneert de tekstoriëntatie. Alleen-lezen [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Retourneert:**
byte
### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```


Retourneert de tekst-autofit-modus. Alleen-lezen [TextAutofitType](../../com.aspose.slides/textautofittype).

**Retourneert:**
byte
### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```


Specificeert het aantal kolommen tekst in de omvattende rechthoek. Alleen-lezen int.

**Retourneert:**
int
### getColumnSpacing() {#getColumnSpacing--}
```
public abstract float getColumnSpacing()
```


Specificeert de ruimte tussen tekstkolommen in het tekstgebied (in punten). Alleen-lezen float.

**Retourneert:**
float