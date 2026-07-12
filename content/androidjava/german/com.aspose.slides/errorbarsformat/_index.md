---
title: ErrorBarsFormat
second_title: Aspose.Slides für Android über Java API Referenz
description: Stellt Error Bars einer Diagrammserie dar.
type: docs
url: /de/com.aspose.slides/errorbarsformat/
---
**Vererbung:**
java.lang.Object, com.aspose.slides.DomObject

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
```
public class ErrorBarsFormat extends DomObject<ChartSeries> implements IErrorBarsFormat
```

Stellt Error Bars einer Diagrammserie dar. ErrorBars benutzerdefinierte Werte befinden sich in IChartDataPointCollection (in ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) Eigenschaft).

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getType()](#getType--) | Liest oder setzt den Typ der Error Bars. |
| [setType(int value)](#setType-int-) | Liest oder setzt den Typ der Error Bars. |
| [getValueType()](#getValueType--) | Gibt mögliche Wege zur Bestimmung der Länge der Error Bars an. |
| [setValueType(int value)](#setValueType-int-) | Gibt mögliche Wege zur Bestimmung der Länge der Error Bars an. |
| [hasEndCap()](#hasEndCap--) | Gibt an, dass eine Endkappe nicht bei den Error Bars gezeichnet wird. |
| [setEndCap(boolean value)](#setEndCap-boolean-) | Gibt an, dass eine Endkappe nicht bei den Error Bars gezeichnet wird. |
| [getValue()](#getValue--) | Liest oder setzt den Wert, der mit den Werttypen Fixed, Percentage und StandardDeviation zur Bestimmung der Länge der Error Bars verwendet wird. |
| [setValue(float value)](#setValue-float-) | Liest oder setzt den Wert, der mit den Werttypen Fixed, Percentage und StandardDeviation zur Bestimmung der Länge der Error Bars verwendet wird. |
| [getFormat()](#getFormat--) | Gibt das Format der Error Bars an. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Gibt das Format der Error Bars an. |
| [getChart()](#getChart--) | Gibt das übergeordnete Chart zurück. |
| [isVisible()](#isVisible--) | Liest oder setzt die Sichtbarkeit der Error Bars. |
| [setVisible(boolean value)](#setVisible-boolean-) | Liest oder setzt die Sichtbarkeit der Error Bars. |
| [getSlide()](#getSlide--) | Gibt die übergeordnete Slide eines FillFormat zurück. |
| [getPresentation()](#getPresentation--) | Gibt die übergeordnete Präsentation eines FillFormat zurück. |
### getType() {#getType--}
```
public final int getType()
```

Liest oder setzt den Typ der Error Bars. Lesen/Schreiben [ErrorBarType](../../com.aspose.slides/errorbartype).

**Rückgabe:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Liest oder setzt den Typ der Error Bars. Lesen/Schreiben [ErrorBarType](../../com.aspose.slides/errorbartype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getValueType() {#getValueType--}
```
public final int getValueType()
```

Gibt mögliche Wege zur Bestimmung der Länge der Error Bars an. Im Fall eines benutzerdefinierten Werttyps verwende die ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) Eigenschaft eines bestimmten Datenpunkts in der DataPoints-Sammlung der Serie, um den Wert anzugeben. Im Fall des Werttyps Fixed, Percentage oder StandardDeviation verwende die Value-Eigenschaft, um den Wert anzugeben. Lesen/Schreiben [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Rückgabe:**
int
### setValueType(int value) {#setValueType-int-}
```
public final void setValueType(int value)
```

Gibt mögliche Wege zur Bestimmung der Länge der Error Bars an. Im Fall eines benutzerdefinierten Werttyps verwende die ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) Eigenschaft eines bestimmten Datenpunkts in der DataPoints-Sammlung der Serie, um den Wert anzugeben. Im Fall des Werttyps Fixed, Percentage oder StandardDeviation verwende die Value-Eigenschaft, um den Wert anzugeben. Lesen/Schreiben [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### hasEndCap() {#hasEndCap--}
```
public final boolean hasEndCap()
```

Gibt an, dass eine Endkappe nicht bei den Error Bars gezeichnet wird. Lesen/Schreiben boolean.

**Rückgabe:**
boolean
### setEndCap(boolean value) {#setEndCap-boolean-}
```
public final void setEndCap(boolean value)
```

Gibt an, dass eine Endkappe nicht bei den Error Bars gezeichnet wird. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getValue() {#getValue--}
```
public final float getValue()
```

Liest oder setzt den Wert, der mit den Werttypen Fixed, Percentage und StandardDeviation zur Bestimmung der Länge der Error Bars verwendet wird. In allen anderen Fällen wird NaN zurückgegeben. Lesen/Schreiben float.

**Rückgabe:**
float
### setValue(float value) {#setValue-float-}
```
public final void setValue(float value)
```

Liest oder setzt den Wert, der mit den Werttypen Fixed, Percentage und StandardDeviation zur Bestimmung der Länge der Error Bars verwendet wird. In allen anderen Fällen wird NaN zurückgegeben. Lesen/Schreiben float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Gibt das Format der Error Bars an. Lesen/Schreiben [IFormat](../../com.aspose.slides/iformat).

**Rückgabe:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

Gibt das Format der Error Bars an. Lesen/Schreiben [IFormat](../../com.aspose.slides/iformat).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getChart() {#getChart--}
```
public final IChart getChart()
```

Gibt das übergeordnete Chart zurück. Nur lesbar [IChart](../../com.aspose.slides/ichart).

**Rückgabe:**
[IChart](../../com.aspose.slides/ichart)
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

Liest oder setzt die Sichtbarkeit der Error Bars. Lesen/Schreiben boolean.

**Rückgabe:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```

Liest oder setzt die Sichtbarkeit der Error Bars. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Gibt die übergeordnete Slide eines FillFormat zurück. Nur lesbar [BaseSlide](../../com.aspose.slides/baseslide).

**Rückgabe:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Gibt die übergeordnete Präsentation eines FillFormat zurück. Nur lesbar [IPresentation](../../com.aspose.slides/ipresentation).

**Rückgabe:**
[IPresentation](../../com.aspose.slides/ipresentation)