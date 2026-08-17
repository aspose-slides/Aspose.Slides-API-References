---
title: Trendline
second_title: Aspose.Slides für Java API Referenz
description: Klasse repräsentiert die Trendlinie einer Diagrammserie
type: docs
url: /de/com.aspose.slides/trendline/
---
**Vererbung:**
java.lang.Object, com.aspose.slides.DomObject

**Alle implementierten Schnittstellen:**
[com.aspose.slides.ITrendline](../../com.aspose.slides/itrendline)
```
public class Trendline extends DomObject<TrendlineCollection> implements ITrendline
```

Klasse repräsentiert die Trendlinie einer Diagrammserie
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getTrendlineName()](#getTrendlineName--) | Ruft den Namen der Trendlinie ab oder legt ihn fest. |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | Ruft den Namen der Trendlinie ab oder legt ihn fest. |
| [getTrendlineType()](#getTrendlineType--) | Ruft den Typ der Trendlinie ab oder legt ihn fest. |
| [setTrendlineType(int value)](#setTrendlineType-int-) | Ruft den Typ der Trendlinie ab oder legt ihn fest. |
| [getFormat()](#getFormat--) | Stellt das Format der Trendlinie dar. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Stellt das Format der Trendlinie dar. |
| [getBackward()](#getBackward--) | Gibt die Anzahl der Kategorien (oder Einheiten in einem Streudiagramm) an, die die Trendlinie vor den Daten der trenden Serie erstreckt. |
| [setBackward(double value)](#setBackward-double-) | Gibt die Anzahl der Kategorien (oder Einheiten in einem Streudiagramm) an, die die Trendlinie vor den Daten der trenden Serie erstreckt. |
| [getForward()](#getForward--) | Gibt die Anzahl der Kategorien (oder Einheiten in einem Streudiagramm) an, die die Trendlinie nach den Daten der trenden Serie erstreckt. |
| [setForward(double value)](#setForward-double-) | Gibt die Anzahl der Kategorien (oder Einheiten in einem Streudiagramm) an, die die Trendlinie nach den Daten der trenden Serie erstreckt. |
| [getIntercept()](#getIntercept--) | Gibt den Wert an, an dem die Trendlinie die y-Achse schneidet. |
| [setIntercept(double value)](#setIntercept-double-) | Gibt den Wert an, an dem die Trendlinie die y-Achse schneidet. |
| [getDisplayEquation()](#getDisplayEquation--) | Gibt an, dass die Gleichung der Trendlinie im Diagramm angezeigt wird (im selben Beschriftungsfeld wie Rsquaredvalue). |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | Gibt an, dass die Gleichung der Trendlinie im Diagramm angezeigt wird (im selben Beschriftungsfeld wie Rsquaredvalue). |
| [getOrder()](#getOrder--) | Gibt die Ordnung der polynomialen Trendlinie an. |
| [setOrder(byte value)](#setOrder-byte-) | Gibt die Ordnung der polynomialen Trendlinie an. |
| [getPeriod()](#getPeriod--) | Gibt die Periode der Trendlinie für eine gleitende Durchschnittstrendlinie an. |
| [setPeriod(byte value)](#setPeriod-byte-) | Gibt die Periode der Trendlinie für eine gleitende Durchschnittstrendlinie an. |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | Gibt an, dass der R-squared-Wert der Trendlinie im Diagramm angezeigt wird (im selben Beschriftungsfeld wie die Gleichung). |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | Gibt an, dass der R-squared-Wert der Trendlinie im Diagramm angezeigt wird (im selben Beschriftungsfeld wie die Gleichung). |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Stellt den Legendeneintrag zu dieser Trendlinie dar Nur lesbar [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Initialisiert TextFrameForOverriding mit dem Text im Parameter "text". |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Kann einen reich formatierten Text enthalten. |
| [getTextFormat()](#getTextFormat--) | Gibt das Textformat zurück. |
| [getChart()](#getChart--) | Gibt das übergeordnete Diagramm zurück. |
| [getSlide()](#getSlide--) | Gibt die übergeordnete Folie eines FillFormat zurück. |
| [getPresentation()](#getPresentation--) | Gibt die übergeordnete Präsentation eines FillFormat zurück. |
### getTrendlineName() {#getTrendlineName--}
```
public final String getTrendlineName()
```

Ruft den Namen der Trendlinie ab oder legt ihn fest. Lesen/Schreiben String.

**Rückgabewert:**
java.lang.String
### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public final void setTrendlineName(String value)
```

Ruft den Namen der Trendlinie ab oder legt ihn fest. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getTrendlineType() {#getTrendlineType--}
```
public final int getTrendlineType()
```

Ruft den Typ der Trendlinie ab oder legt ihn fest. Lesen/Schreiben [TrendlineType](../../com.aspose.slides/trendlinetype).

**Rückgabewert:**
int
### setTrendlineType(int value) {#setTrendlineType-int-}
```
public final void setTrendlineType(int value)
```

Ruft den Typ der Trendlinie ab oder legt ihn fest. Lesen/Schreiben [TrendlineType](../../com.aspose.slides/trendlinetype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Stellt das Format der Trendlinie dar. Lesen/Schreiben [IFormat](../../com.aspose.slides/iformat).

**Rückgabewert:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

Stellt das Format der Trendlinie dar. Lesen/Schreiben [IFormat](../../com.aspose.slides/iformat).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getBackward() {#getBackward--}
```
public final double getBackward()
```

Gibt die Anzahl der Kategorien (oder Einheiten in einem Streudiagramm) an, die die Trendlinie vor den Daten der trenden Serie erstreckt. Auf Streu- und Nicht-Streu-Diagrammen darf der Wert jeder nichtnegative Wert sein. Lesen/Schreiben double.

**Rückgabewert:**
double
### setBackward(double value) {#setBackward-double-}
```
public final void setBackward(double value)
```

Gibt die Anzahl der Kategorien (oder Einheiten in einem Streudiagramm) an, die die Trendlinie vor den Daten der trenden Serie erstreckt. Auf Streu- und Nicht-Streu-Diagrammen darf der Wert jeder nichtnegative Wert sein. Lesen/Schreiben double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |
### getForward() {#getForward--}
```
public final double getForward()
```

Gibt die Anzahl der Kategorien (oder Einheiten in einem Streudiagramm) an, die die Trendlinie nach den Daten der trenden Serie erstreckt. Auf Streu- und Nicht-Streu-Diagrammen darf der Wert jeder nichtnegative Wert sein. Lesen/Schreiben double.

**Rückgabewert:**
double
### setForward(double value) {#setForward-double-}
```
public final void setForward(double value)
```

Gibt die Anzahl der Kategorien (oder Einheiten in einem Streudiagramm) an, die die Trendlinie nach den Daten der trenden Serie erstreckt. Auf Streu- und Nicht-Streu-Diagrammen darf der Wert jeder nichtnegative Wert sein. Lesen/Schreiben double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |
### getIntercept() {#getIntercept--}
```
public final double getIntercept()
```

Gibt den Wert an, an dem die Trendlinie die y-Achse schneidet. Diese Eigenschaft wird nur unterstützt, wenn der Trendlinientyp exp, linear oder poly ist. Lesen/Schreiben double.

**Rückgabewert:**
double
### setIntercept(double value) {#setIntercept-double-}
```
public final void setIntercept(double value)
```

Gibt den Wert an, an dem die Trendlinie die y-Achse schneidet. Diese Eigenschaft wird nur unterstützt, wenn der Trendlinientyp exp, linear oder poly ist. Lesen/Schreiben double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |
### getDisplayEquation() {#getDisplayEquation--}
```
public final boolean getDisplayEquation()
```

Gibt an, dass die Gleichung der Trendlinie im Diagramm angezeigt wird (im selben Beschriftungsfeld wie Rsquaredvalue). Lesen/Schreiben boolean.

**Rückgabewert:**
boolean
### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public final void setDisplayEquation(boolean value)
```

Gibt an, dass die Gleichung der Trendlinie im Diagramm angezeigt wird (im selben Beschriftungsfeld wie Rsquaredvalue). Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getOrder() {#getOrder--}
```
public final byte getOrder()
```

Gibt die Ordnung der polynomialen Trendlinie an. Sie wird für andere Trendlinientypen ignoriert. Der Wert muss zwischen 2 und 6 liegen. Lesen/Schreiben byte.

**Rückgabewert:**
byte
### setOrder(byte value) {#setOrder-byte-}
```
public final void setOrder(byte value)
```

Gibt die Ordnung der polynomialen Trendlinie an. Sie wird für andere Trendlinientypen ignoriert. Der Wert muss zwischen 2 und 6 liegen. Lesen/Schreiben byte.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |
### getPeriod() {#getPeriod--}
```
public final byte getPeriod()
```

Gibt die Periode der Trendlinie für eine gleitende Durchschnittstrendlinie an. Sie wird für andere Trendlinientypen ignoriert. Der Wert muss zwischen 2 und 255 liegen. Lesen/Schreiben byte.

**Rückgabewert:**
byte
### setPeriod(byte value) {#setPeriod-byte-}
```
public final void setPeriod(byte value)
```

Gibt die Periode der Trendlinie für eine gleitende Durchschnittstrendlinie an. Sie wird für andere Trendlinientypen ignoriert. Der Wert muss zwischen 2 und 255 liegen. Lesen/Schreiben byte.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |
### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public final boolean getDisplayRSquaredValue()
```

Gibt an, dass der R-squared-Wert der Trendlinie im Diagramm angezeigt wird (im selben Beschriftungsfeld wie die Gleichung). Lesen/Schreiben boolean.

**Rückgabewert:**
boolean
### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public final void setDisplayRSquaredValue(boolean value)
```

Gibt an, dass der R-squared-Wert der Trendlinie im Diagramm angezeigt wird (im selben Beschriftungsfeld wie die Gleichung). Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

Stellt den Legendeneintrag zu dieser Trendlinie dar Nur lesbar [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Rückgabewert:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

Initialisiert TextFrameForOverriding mit dem Text im Parameter "text". Wenn TextFrameForOverriding bereits initialisiert ist, wird einfach dessen Text geändert.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Text für ein neues TextFrameForOverriding. |

**Rückgabewert:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

Kann einen reich formatierten Text enthalten. Wenn diese Eigenschaft nicht null ist, überschreibt dieser formatierte Text den automatisch generierten Text des Datenbeschriftungs-Labels. Der automatisch generierte Text bedeutet Text, der von den Eigenschaften ShowSeriesName, ShowValue, … verwaltet wird und mit der Eigenschaft TextFormatManager.TextFormat formatiert ist. Nur lesbar [ITextFrame](../../com.aspose.slides/itextframe).

**Rückgabewert:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Gibt das Textformat zurück. Nur lesbar [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Rückgabewert:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getChart() {#getChart--}
```
public final IChart getChart()
```

Gibt das übergeordnete Diagramm zurück. Nur lesbar [IChart](../../com.aspose.slides/ichart).

**Rückgabewert:**
[IChart](../../com.aspose.slides/ichart)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Gibt die übergeordnete Folie eines FillFormat zurück. Nur lesbar [BaseSlide](../../com.aspose.slides/baseslide).

**Rückgabewert:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Gibt die übergeordnete Präsentation eines FillFormat zurück. Nur lesbar [IPresentation](../../com.aspose.slides/ipresentation).

**Rückgabewert:**
[IPresentation](../../com.aspose.slides/ipresentation)