---
title: ILineFormatEffectiveData
second_title: Aspose.Slides für Android über die Java API Referenz
description: Unveränderliches Objekt, das effektive Zeilenformatierungseigenschaften enthält.
type: docs
url: /de/com.aspose.slides/ilineformateffectivedata/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource)
```
public interface ILineFormatEffectiveData extends ILineParamSource
```

Unveränderliches Objekt, das effektive Zeilenformatierungseigenschaften enthält.

--------------------

Dieses Interface wird zusammen mit dem [ILineFormat](../../com.aspose.slides/ilineformat) Schnittstelle verwendet, um effektive Formatierungswerte mit angewandter Vererbung zurückzugeben.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Gibt das Füllformat einer Zeile zurück. |
| [getSketchFormat()](#getSketchFormat--) | Gibt das Skizzenformat einer Zeile zurück. |
| [getWidth()](#getWidth--) | Gibt die Breite einer Zeile zurück. |
| [getDashStyle()](#getDashStyle--) | Gibt den Strichstil der Zeile zurück. |
| [getCustomDashPattern()](#getCustomDashPattern--) | Gibt das benutzerdefinierte Strichmuster zurück. |
| [getCapStyle()](#getCapStyle--) | Gibt den Endenstil der Zeile zurück. |
| [getStyle()](#getStyle--) | Gibt den Zeilenstil zurück. |
| [getAlignment()](#getAlignment--) | Gibt die Ausrichtung der Zeile zurück. |
| [getJoinStyle()](#getJoinStyle--) | Gibt den Verbindungsstil der Zeilen zurück. |
| [getMiterLimit()](#getMiterLimit--) | Gibt das Miter-Limit einer Zeile zurück. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | Gibt den Pfeilspitzenstil am Anfang einer Zeile zurück. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | Gibt den Pfeilspitzenstil am Ende einer Zeile zurück. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | Gibt die Pfeilspitzenbreite am Anfang einer Zeile zurück. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | Gibt die Pfeilspitzenbreite am Ende einer Zeile zurück. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | Gibt die Pfeilspitzenlänge am Anfang einer Zeile zurück. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | Gibt die Pfeilspitzenlänge am Ende einer Zeile zurück. |
| [equals(ILineFormatEffectiveData lf)](#equals-com.aspose.slides.ILineFormatEffectiveData-) | Bestimmt, ob die beiden ILineFormatEffectiveData-Instanzen gleich sind. |
### getFillFormat() {#getFillFormat--}
```
public abstract ILineFillFormatEffectiveData getFillFormat()
```

Gibt das Füllformat einer Zeile zurück. Nur lesbar [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).

**Rückgabe:**
[ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata)
### getSketchFormat() {#getSketchFormat--}
```
public abstract ISketchFormatEffectiveData getSketchFormat()
```

Gibt das Skizzenformat einer Zeile zurück. Nur lesbar [ISketchFormatEffectiveData](../../com.aspose.slides/isketchformateffectivedata).

**Rückgabe:**
[ISketchFormatEffectiveData](../../com.aspose.slides/isketchformateffectivedata)
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

Gibt die Breite einer Zeile zurück. Nur lesbar double.

**Rückgabe:**
double
### getDashStyle() {#getDashStyle--}
```
public abstract byte getDashStyle()
```

Gibt den Strichstil der Zeile zurück. Nur lesbar [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Rückgabe:**
byte
### getCustomDashPattern() {#getCustomDashPattern--}
```
public abstract float[] getCustomDashPattern()
```

Gibt das benutzerdefinierte Strichmuster zurück. Nur lesbar float[].

**Rückgabe:**
float[]
### getCapStyle() {#getCapStyle--}
```
public abstract byte getCapStyle()
```

Gibt den Endenstil der Zeile zurück. Nur lesbar [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Rückgabe:**
byte
### getStyle() {#getStyle--}
```
public abstract byte getStyle()
```

Gibt den Zeilenstil zurück. Nur lesbar [LineStyle](../../com.aspose.slides/linestyle).

**Rückgabe:**
byte
### getAlignment() {#getAlignment--}
```
public abstract byte getAlignment()
```

Gibt die Ausrichtung der Zeile zurück. Nur lesbar [LineAlignment](../../com.aspose.slides/linealignment).

**Rückgabe:**
byte
### getJoinStyle() {#getJoinStyle--}
```
public abstract byte getJoinStyle()
```

Gibt den Verbindungsstil der Zeilen zurück. Nur lesbar [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Rückgabe:**
byte
### getMiterLimit() {#getMiterLimit--}
```
public abstract float getMiterLimit()
```

Gibt das Miter-Limit einer Zeile zurück. Nur lesbar float.

**Rückgabe:**
float
### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public abstract byte getBeginArrowheadStyle()
```

Gibt den Pfeilspitzenstil am Anfang einer Zeile zurück. Nur lesbar [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Rückgabe:**
byte
### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```

Gibt den Pfeilspitzenstil am Ende einer Zeile zurück. Nur lesbar [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Rückgabe:**
byte
### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```

Gibt die Pfeilspitzenbreite am Anfang einer Zeile zurück. Nur lesbar [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Rückgabe:**
byte
### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```

Gibt die Pfeilspitzenbreite am Ende einer Zeile zurück. Nur lesbar [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Rückgabe:**
byte
### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```

Gibt die Pfeilspitzenlänge am Anfang einer Zeile zurück. Nur lesbar [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Rückgabe:**
byte
### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```

Gibt die Pfeilspitzenlänge am Ende einer Zeile zurück. Nur lesbar [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Rückgabe:**
byte
### equals(ILineFormatEffectiveData lf) {#equals-com.aspose.slides.ILineFormatEffectiveData-}
```
public abstract boolean equals(ILineFormatEffectiveData lf)
```

Bestimmt, ob die beiden ILineFormatEffectiveData-Instanzen gleich sind.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| lf | [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) | Die ILineFormatEffectiveData zum Vergleich mit der aktuellen ILineFormatEffectiveData. |

**Rückgabe:**
boolean - **true**, wenn die angegebene ILineFormatEffectiveData gleich der aktuellen ILineFormatEffectiveData ist; andernfalls **false**.