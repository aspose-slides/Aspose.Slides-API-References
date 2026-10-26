---
title: ITextFrameFormatEffectiveData
second_title: Aspose.Slides für die Java-API-Referenz
description: Unveränderliches Objekt, das effektive Textrahmen-Formatierungseigenschaften enthält.
type: docs
url: /de/com.aspose.slides/itextframeformateffectivedata/
---```
public interface ITextFrameFormatEffectiveData
```

Unveränderliches Objekt, das effektive Textrahmen-Formatierungseigenschaften enthält.

--------------------

Dieses Interface wird zusammen mit dem [ITextFrameFormat](../../com.aspose.slides/itextframeformat) Interface verwendet, um effektive Formatierungswerte mit angewandter Vererbung zurückzugeben.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | Gibt den effektiven Textstil zurück. |
| [getMarginLeft()](#getMarginLeft--) | Gibt den linken Rand (Punkte) in einem TextFrame zurück. |
| [getMarginRight()](#getMarginRight--) | Gibt den rechten Rand (Punkte) in einem TextFrame zurück. |
| [getMarginTop()](#getMarginTop--) | Gibt den oberen Rand (Punkte) in einem TextFrame zurück. |
| [getMarginBottom()](#getMarginBottom--) | Gibt den unteren Rand (Punkte) in einem TextFrame zurück. |
| [getWrapText()](#getWrapText--) | Gibt zurück, ob Text an den Rändern des TextFrames umbrochen wird. |
| [getAnchoringType()](#getAnchoringType--) | Gibt den vertikalen Ankertext in einem TextFrame zurück. |
| [getCenterText()](#getCenterText--) | Gibt zurück, ob Text horizontal in der Box zentriert werden soll. |
| [getTextVerticalType()](#getTextVerticalType--) | Gibt die Textausrichtung zurück. |
| [getAutofitType()](#getAutofitType--) | Gibt den Text-Autofit-Modus zurück. |
| [getColumnCount()](#getColumnCount--) | Gibt die Anzahl der Textspalten im Begrenzungsrechteck an. |
| [getColumnSpacing()](#getColumnSpacing--) | Gibt den Abstand zwischen Textspalten im Textbereich (in Punkten) an. |
### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyleEffectiveData getTextStyle()
```


Gibt den effektiven Textstil zurück. Nur lesbar [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).

**Rückgabe:**  
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata)
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```


Gibt den linken Rand (Punkte) in einem TextFrame zurück. Nur lesbar double.

**Rückgabe:**  
double
### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```


Gibt den rechten Rand (Punkte) in einem TextFrame zurück. Nur lesbar double.

**Rückgabe:**  
double
### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```


Gibt den oberen Rand (Punkte) in einem TextFrame zurück. Nur lesbar double.

**Rückgabe:**  
double
### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```


Gibt den unteren Rand (Punkte) in einem TextFrame zurück. Nur lesbar double.

**Rückgabe:**  
double
### getWrapText() {#getWrapText--}
```
public abstract boolean getWrapText()
```


Gibt zurück, ob Text an den Rändern des TextFrames umbrochen wird. Nur lesbar boolean.

**Rückgabe:**  
boolean
### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```


Gibt den vertikalen Ankertext in einem TextFrame zurück. Nur lesbar [TextAnchorType](../../com.aspose.slides/textanchortype).

**Rückgabe:**  
byte
### getCenterText() {#getCenterText--}
```
public abstract boolean getCenterText()
```


Gibt zurück, ob Text horizontal in der Box zentriert werden soll. Nur lesbar boolean.

**Rückgabe:**  
boolean
### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```


Gibt die Textausrichtung zurück. Nur lesbar [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Rückgabe:**  
byte
### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```


Gibt den Text-Autofit-Modus zurück. Nur lesbar [TextAutofitType](../../com.aspose.slides/textautofittype).

**Rückgabe:**  
byte
### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```


Gibt die Anzahl der Textspalten im Begrenzungsrechteck an. Nur lesbar int.

**Rückgabe:**  
int
### getColumnSpacing() {#getColumnSpacing--}
```
public abstract float getColumnSpacing()
```


Gibt den Abstand zwischen Textspalten im Textbereich (in Punkten) an. Nur lesbar float.

**Rückgabe:**  
float