---
title: ITextFrameFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective text frame formatting properties.
type: docs
url: /pl/com.aspose.slides/itextframeformateffectivedata/
---```
public interface ITextFrameFormatEffectiveData
```

Niezmienny obiekt, który zawiera efektywne właściwości formatowania ramki tekstowej.

--------------------

Ten interfejs jest używany razem z interfejsem [ITextFrameFormat](../../com.aspose.slides/itextframeformat), aby zwrócić efektywne wartości formatowania z zastosowanym dziedziczeniem.
## Metody

| Metoda | Opis |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | Zwraca efektywny styl tekstu. |
| [getMarginLeft()](#getMarginLeft--) | Zwraca lewy margines (punkty) w TextFrame. |
| [getMarginRight()](#getMarginRight--) | Zwraca prawy margines (punkty) w TextFrame. |
| [getMarginTop()](#getMarginTop--) | Zwraca górny margines (punkty) w TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Zwraca dolny margines (punkty) w TextFrame. |
| [getWrapText()](#getWrapText--) | Zwraca informację, czy tekst jest zawijany przy marginesach TextFrame. |
| [getAnchoringType()](#getAnchoringType--) | Zwraca pionowy punkt kotwiczenia tekstu w TextFrame. |
| [getCenterText()](#getCenterText--) | Zwraca informację, czy tekst powinien być wyśrodkowany w poziomie w ramce. |
| [getTextVerticalType()](#getTextVerticalType--) | Zwraca orientację tekstu. |
| [getAutofitType()](#getAutofitType--) | Zwraca tryb automatycznego dopasowania tekstu. |
| [getColumnCount()](#getColumnCount--) | Określa liczbę kolumn tekstu w prostokącie ograniczającym. |
| [getColumnSpacing()](#getColumnSpacing--) | Określa odstęp między kolumnami tekstu w obszarze tekstowym (w punktach). |
### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyleEffectiveData getTextStyle()
```


Zwraca efektywny styl tekstu. Tylko do odczytu [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).

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


Zwraca informację, czy tekst jest zawijany przy marginesach TextFrame. Tylko do odczytu boolean.

**Zwraca:**
boolean
### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```


Zwraca pionowy punkt kotwiczenia tekstu w TextFrame. Tylko do odczytu [TextAnchorType](../../com.aspose.slides/textanchortype).

**Zwraca:**
byte
### getCenterText() {#getCenterText--}
```
public abstract boolean getCenterText()
```


Zwraca informację, czy tekst powinien być wyśrodkowany w poziomie w ramce. Tylko do odczytu boolean.

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