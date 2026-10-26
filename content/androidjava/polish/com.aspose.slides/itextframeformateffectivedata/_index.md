---
title: ITextFrameFormatEffectiveData
second_title: Aspose.Slides dla Androida poprzez Java API Reference
description: Niezmienny obiekt zawierający skuteczne właściwości formatowania ramki tekstowej.
type: docs
url: /pl/com.aspose.slides/itextframeformateffectivedata/
---```
public interface ITextFrameFormatEffectiveData
```

Niezmienny obiekt zawierający skuteczne właściwości formatowania ramki tekstowej.

--------------------

Ten interfejs jest używany razem z interfejsem [ITextFrameFormat](../../com.aspose.slides/itextframeformat) w celu zwrócenia skutecznych wartości formatowania z zastosowanym dziedziczeniem.
## Metody

| Metoda | Opis |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | Returns effective text's style. |
| [getMarginLeft()](#getMarginLeft--) | Returns the left margin (points) in a TextFrame. |
| [getMarginRight()](#getMarginRight--) | Returns the right margin (points) in a TextFrame. |
| [getMarginTop()](#getMarginTop--) | Returns the top margin (points) in a TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Returns the bottom margin (points) in a TextFrame. |
| [getWrapText()](#getWrapText--) | Returns if text is wrapped at TextFrame's margins. |
| [getAnchoringType()](#getAnchoringType--) | Returns vertical anchor text in a TextFrame. |
| [getCenterText()](#getCenterText--) | Returns if text should be centered in box horizontally. |
| [getTextVerticalType()](#getTextVerticalType--) | Returns text orientation. |
| [getAutofitType()](#getAutofitType--) | Returns text autofit mode. |
| [getColumnCount()](#getColumnCount--) | Specifies the number of columns of text in the bounding rectangle. |
| [getColumnSpacing()](#getColumnSpacing--) | Specifies the space between text columns in the text area (in points). |
### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyleEffectiveData getTextStyle()
```


Zwraca skuteczny styl tekstu. Tylko do odczytu [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).

**Zwraca:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata)
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```


Zwraca lewy margines (punkty) w TextFrame. Tylko do odczytu double.

**Zwraca:**
double
### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```


Zwraca prawy margines (punkty) w TextFrame. Tylko do odczytu double.

**Zwraca:**
double
### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```


Zwraca górny margines (punkty) w TextFrame. Tylko do odczytu double.

**Zwraca:**
double
### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```


Zwraca dolny margines (punkty) w TextFrame. Tylko do odczytu double.

**Zwraca:**
double
### getWrapText() {#getWrapText--}
```
public abstract boolean getWrapText()
```


Zwraca, czy tekst jest zawijany przy marginesach TextFrame. Tylko do odczytu boolean.

**Zwraca:**
boolean
### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```


Zwraca pionowy anchor tekstu w TextFrame. Tylko do odczytu [TextAnchorType](../../com.aspose.slides/textanchortype).

**Zwraca:**
byte
### getCenterText() {#getCenterText--}
```
public abstract boolean getCenterText()
```


Zwraca, czy tekst powinien być wyśrodkowany w ramce w poziomie. Tylko do odczytu boolean.

**Zwraca:**
boolean
### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```


Zwraca orientację tekstu. Tylko do odczytu [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Zwraca:**
byte
### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```


Zwraca tryb automatycznego dopasowania tekstu. Tylko do odczytu [TextAutofitType](../../com.aspose.slides/textautofittype).

**Zwraca:**
byte
### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```


Określa liczbę kolumn tekstu w prostokącie ograniczającym. Tylko do odczytu int.

**Zwraca:**
int
### getColumnSpacing() {#getColumnSpacing--}
```
public abstract float getColumnSpacing()
```


Określa odstęp między kolumnami tekstu w obszarze tekstowym (w punktach). Tylko do odczytu float.

**Zwraca:**
float