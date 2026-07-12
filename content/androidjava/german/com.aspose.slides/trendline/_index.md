---
title: Trendline
second_title: Aspose.Slides für Android über Java API-Referenz
description: Klasse repräsentiert Trendlinie einer Diagrammserie
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

Klasse repräsentiert Trendlinie einer Diagrammserie
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getTrendlineName()](#getTrendlineName--) | Liest oder setzt den Namen der Trendlinie. |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | Liest oder setzt den Namen der Trendlinie. |
| [getTrendlineType()](#getTrendlineType--) | Liest oder setzt den Typ der Trendlinie. |
| [setTrendlineType(int value)](#setTrendlineType-int-) | Liest oder setzt den Typ der Trendlinie. |
| [getFormat()](#getFormat--) | Stellt das Format der Trendlinie dar. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Stellt das Format der Trendlinie dar. |
| [getBackward()](#getBackward--) | Gibt die Anzahl der Kategorien (oder Einheiten in einem Streudiagramm) an, die die Trendlinie vor den Daten der trended Serie erstreckt. |
| [setBackward(double value)](#setBackward-double-) | Gibt die Anzahl der Kategorien (oder Einheiten in einem Streudiagramm) an, die die Trendlinie vor den Daten der trended Serie erstreckt. |
| [getForward()](#getForward--) | Gibt die Anzahl der Kategorien (oder Einheiten in einem Streudiagramm) an, die die Trendlinie nach den Daten der trended Serie erstreckt. |
| [setForward(double value)](#setForward-double-) | Gibt die Anzahl der Kategorien (oder Einheiten in einem Streudiagramm) an, die die Trendlinie nach den Daten der trended Serie erstreckt. |
| [getIntercept()](#getIntercept--) | Gibt den Wert an, an dem die Trendlinie die y-Achse schneidet. |
| [setIntercept(double value)](#setIntercept-double-) | Gibt den Wert an, an dem die Trendlinie die y-Achse schneidet. |
| [getDisplayEquation()](#getDisplayEquation--) | Gibt an, dass die Gleichung der Trendlinie im Diagramm angezeigt wird (im selben Beschriftungsfeld wie der Rsquaredvalue). |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | Gibt an, dass die Gleichung der Trendlinie im Diagramm angezeigt wird (im selben Beschriftungsfeld wie der Rsquaredvalue). |
| [getOrder()](#getOrder--) | Gibt die Ordnung der polynomialen Trendlinie an. |
| [setOrder(byte value)](#setOrder-byte-) | Gibt die Ordnung der polynomialen Trendlinie an. |
| [getPeriod()](#getPeriod--) | Gibt den Zeitraum der Trendlinie für eine gleitende Durchschnittstrendlinie an. |
| [setPeriod(byte value)](#setPeriod-byte-) | Gibt den Zeitraum der Trendlinie für eine gleitende Durchschnittstrendlinie an. |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | Gibt an, dass der R-Quadrat-Wert der Trendlinie im Diagramm angezeigt wird (im selben Beschriftungsfeld wie die Gleichung). |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | Gibt an, dass der R-Quadrat-Wert der Trendlinie im Diagramm angezeigt wird (im selben Beschriftungsfeld wie die Gleichung). |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Stellt den Legendeneintrag zu dieser Trendlinie dar. Nur lesbar [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Initialisiert TextFrameForOverriding mit dem Text im Parameter „text“. |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Kann einen reich formatierten Text enthalten. |
| [getTextFormat()](#getTextFormat--) | Gibt das Textformat zurück. |
| [getChart()](#getChart--) | Gibt das übergeordnete Diagramm zurück. |
| [getSlide()](#getSlide--) | Gibt die übergeordnete Folie eines FillFormat zurück. |
| [getPresentation()](#getPresentation--) | Gibt die übergeordnete Präsentation eines FillFormat zurück. |
### getTrendlineName() {#getTrendlineName--}
```
public final String getTrendlineName()
```

Liest oder setzt den Namen der Trendlinie. Lese-/Schreibzugriff String.

**Rückgabewert:**
java.lang.String
### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public final void setTrendlineName(String value)
```

Liest oder setzt den Namen der Trendlinie. Lese-/Schreibzugriff String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getTrendlineType() {#getTrendlineType--}
```
public final int getTrendlineType()
```

Liest oder setzt den Typ der Trendlinie. Lese-/Schreibzugriff [TrendlineType](../../com.aspose.slides/trendlinetype).

**Rückgabewert:**
int
### setTrendlineType(int value) {#setTrendlineType-int-}
```
public final void setTrendlineType(int value)
```

Liest oder setzt den Typ der Trendlinie. Lese-/Schreibzugriff [TrendlineType](../../com.aspose.slides/trendlinetype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Stellt das Format der Trendlinie dar. Lese-/Schreibzugriff [IFormat](../../com.aspose.slides/iformat).

**Rückgabewert:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

Stellt das Format der Trendlinie dar. Lese-/Schreibzugriff [IFormat](../../com.aspose.slides/iformat).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getBackward() {#getBackward--}
```
public final double getBackward()
```

Gibt die Anzahl der Kategorien (oder Einheiten in einem Streudiagramm) an, die die Trendlinie vor den Daten der trended Serie erstreckt. Bei Streu- und Nicht-Streu-Diagrammen muss der Wert ein nicht-negativer Wert sein. Lese-/Schreibzugriff double.

**Rückgabewert:**
double
### setBackward(double value) {#setBackward-double-}
```
public final void setBackward(double value)
```

Gibt die Anzahl der Kategorien (oder Einheiten in einem Streudiagramm) an, die die Trendlinie vor den Daten der trended Serie erstreckt. Bei Streu- und Nicht-Streu-Diagrammen muss der Wert ein nicht-negativer Wert sein. Lese-/Schreibzugriff double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |
### getForward() {#getForward--}
```
public final double getForward()
```

Gibt die Anzahl der Kategorien (oder Einheiten in einem Streudiagramm) an, die die Trendlinie nach den Daten der trended Serie erstreckt. Bei Streu- und Nicht-Streu-Diagrammen muss der Wert ein nicht-negativer Wert sein. Lese-/Schreibzugriff double.

**Rückgabewert:**
double
### setForward(double value) {#setForward-double-}
```
public final void setForward(double value)
```

Gibt die Anzahl der Kategorien (oder Einheiten in einem Streudiagramm) an, die die Trendlinie nach den Daten der trended Serie erstreckt. Bei Streu- und Nicht-Streu-Diagrammen muss der Wert ein nicht-negativer Wert sein. Lese-/Schreibzugriff double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |
### getIntercept() {#getIntercept--}
```
public final double getIntercept()
```

Gibt den Wert an, an dem die Trendlinie die y-Achse schneidet. Diese Eigenschaft wird nur unterstützt, wenn der Trendlinientyp exp, linear oder poly ist. Lese-/Schreibzugriff double.

**Rückgabewert:**
double
### setIntercept(double value) {#setIntercept-double-}
```
public final void setIntercept(double value)
```

Gibt den Wert an, an dem die Trendlinie die y-Achse schneidet. Diese Eigenschaft wird nur unterstützt, wenn der Trendlinientyp exp, linear oder poly ist. Lese-/Schreibzugriff double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |
### getDisplayEquation() {#getDisplayEquation--}
```
public final boolean getDisplayEquation()
```

Gibt an, dass die Gleichung der Trendlinie im Diagramm angezeigt wird (im selben Beschriftungsfeld wie der Rsquaredvalue). Lese-/Schreibzugriff boolean.

**Rückgabewert:**
boolean
### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public final void setDisplayEquation(boolean value)
```

Gibt an, dass die Gleichung der Trendlinie im Diagramm angezeigt wird (im selben Beschriftungsfeld wie der Rsquaredvalue). Lese-/Schreibzugriff boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getOrder() {#getOrder--}
```
public final byte getOrder()
```

Gibt die Ordnung der polynomialen Trendlinie an. Sie wird für andere Trendlinientypen ignoriert. Der Wert muss zwischen 2 und 6 liegen. Lese-/Schreibzugriff byte.

**Rückgabewert:**
byte
### setOrder(byte value) {#setOrder-byte-}
```
public final void setOrder(byte value)
```

Gibt die Ordnung der polynomialen Trendlinie an. Sie wird für andere Trendlinientypen ignoriert. Der Wert muss zwischen 2 und 6 liegen. Lese-/Schreibzugriff byte.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |
### getPeriod() {#getPeriod--}
```
public final byte getPeriod()
```

Gibt den Zeitraum der Trendlinie für eine gleitende Durchschnittstrendlinie an. Sie wird für andere Trendlinientypen ignoriert. Der Wert muss zwischen 2 und 255 liegen. Lese-/Schreibzugriff byte.

**Rückgabewert:**
byte
### setPeriod(byte value) {#setPeriod-byte-}
```
public final void setPeriod(byte value)
```

Gibt den Zeitraum der Trendlinie für eine gleitende Durchschnittstrendlinie an. Sie wird für andere Trendlinientypen ignoriert. Der Wert muss zwischen 2 und 255 liegen. Lese-/Schreibzugriff byte.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |
### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public final boolean getDisplayRSquaredValue()
```

Gibt an, dass der R-Quadrat-Wert der Trendlinie im Diagramm angezeigt wird (im selben Beschriftungsfeld wie die Gleichung). Lese-/Schreibzugriff boolean.

**Rückgabewert:**
boolean
### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public final void setDisplayRSquaredValue(boolean value)
```

Gibt an, dass der R-Quadrat-Wert der Trendlinie im Diagramm angezeigt wird (im selben Beschriftungsfeld wie die Gleichung). Lese-/Schreibzugriff boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

Stellt den Legendeneintrag zu dieser Trendlinie dar. Nur lesbar [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Rückgabewert:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

Initialisiert TextFrameForOverriding mit dem Text im Parameter „text“. Wenn TextFrameForOverriding bereits initialisiert ist, wird sein Text einfach geändert.

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

Kann einen reich formatierten Text enthalten. Wenn diese Eigenschaft nicht null ist, überschreibt dieser formatierte Text den automatisch generierten Text des Datenbeschriftungsfeldes. Der automatisch generierte Text des Datenbeschriftungsfeldes ist der Text, der von den Eigenschaften ShowSeriesName, ShowValue, … verwaltet wird und mit der TextFormatManager.TextFormat-Eigenschaft formatiert ist. Nur lesbar [ITextFrame](../../com.aspose.slides/itextframe).

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