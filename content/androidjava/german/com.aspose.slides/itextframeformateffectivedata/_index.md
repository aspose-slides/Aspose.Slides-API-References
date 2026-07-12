---
title: ITextFrameFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective text frame formatting properties.
type: docs
url: /de/com.aspose.slides/itextframeformateffectivedata/
---```
public interface ITextFrameFormatEffectiveData
```

Unveränderliches Objekt, das die wirksamen Textfeld-Formatierungseigenschaften enthält.

--------------------

Dieses Interface wird zusammen mit dem [ITextFrameFormat](../../com.aspose.slides/itextframeformat) Interface verwendet, um wirksame Formatierungswerte mit angewandter Vererbung zurückzugeben.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | Gibt den wirksamen Textstil zurück. |
| [getMarginLeft()](#getMarginLeft--) | Gibt den linken Rand (Punkte) in einem TextFrame zurück. |
| [getMarginRight()](#getMarginRight--) | Gibt den rechten Rand (Punkte) in einem TextFrame zurück. |
| [getMarginTop()](#getMarginTop--) | Gibt den oberen Rand (Punkte) in einem TextFrame zurück. |
| [getMarginBottom()](#getMarginBottom--) | Gibt den unteren Rand (Punkte) in einem TextFrame zurück. |
| [getWrapText()](#getWrapText--) | Gibt zurück, ob der Text an den Rändern des TextFrames umbrochen wird. |
| [getAnchoringType()](#getAnchoringType--) | Gibt den vertikalen Ankertext in einem TextFrame zurück. |
| [getCenterText()](#getCenterText--) | Gibt zurück, ob der Text horizontal im Feld zentriert werden soll. |
| [getTextVerticalType()](#getTextVerticalType--) | Gibt die Textausrichtung zurück. |
| [getAutofitType()](#getAutofitType--) | Gibt den Text-Autofit-Modus zurück. |
| [getColumnCount()](#getColumnCount--) | Gibt die Anzahl der Spalten des Textes im Begrenzungsrechteck zurück. |
| [getColumnSpacing()](#getColumnSpacing--) | Gibt den Abstand zwischen Textspalten im Textbereich (in Punkten) zurück. |
### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyleEffectiveData getTextStyle()
```

Gibt den wirksamen Textstil zurück. Nur lesend [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).

**Rückgabe:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata)
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

Gibt den linken Rand (Punkte) in einem TextFrame zurück. Nur lesend double.

**Rückgabe:**
double
### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

Gibt den rechten Rand (Punkte) in einem TextFrame zurück. Nur lesend double.

**Rückgabe:**
double
### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

Gibt den oberen Rand (Punkte) in einem TextFrame zurück. Nur lesend double.

**Rückgabe:**
double
### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

Gibt den unteren Rand (Punkte) in einem TextFrame zurück. Nur lesend double.

**Rückgabe:**
double
### getWrapText() {#getWrapText--}
```
public abstract boolean getWrapText()
```

Gibt zurück, ob der Text an den Rändern des TextFrames umbrochen wird. Nur lesend boolean.

**Rückgabe:**
boolean
### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

Gibt den vertikalen Ankertext in einem TextFrame zurück. Nur lesend [TextAnchorType](../../com.aspose.slides/textanchortype).

**Rückgabe:**
byte
### getCenterText() {#getCenterText--}
```
public abstract boolean getCenterText()
```

Gibt zurück, ob der Text horizontal im Feld zentriert werden soll. Nur lesend boolean.

**Rückgabe:**
boolean
### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

Gibt die Textausrichtung zurück. Nur lesend [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Rückgabe:**
byte
### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

Gibt den Text-Autofit-Modus zurück. Nur lesend [TextAutofitType](../../com.aspose.slides/textautofittype).

**Rückgabe:**
byte
### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```

Gibt die Anzahl der Spalten des Textes im Begrenzungsrechteck zurück. Nur lesend int.

**Rückgabe:**
int
### getColumnSpacing() {#getColumnSpacing--}
```
public abstract float getColumnSpacing()
```

Gibt den Abstand zwischen Textspalten im Textbereich (in Punkten) zurück. Nur lesend float.

**Rückgabe:**
float