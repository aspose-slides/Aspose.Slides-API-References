---
title: ErrorBarsFormat
second_title: Aspose.Slides für Java API Referenz
description: Stellt Fehlerbalken einer Diagrammserie dar.
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

Stellt Fehlerbalken einer Diagrammserie dar. Benutzerdefinierte Werte für ErrorBars befinden sich in IChartDataPointCollection (in der Eigenschaft ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getType()](#getType--) | Liest oder schreibt den Typ der Fehlerbalken. |
| [setType(int value)](#setType-int-) | Liest oder schreibt den Typ der Fehlerbalken. |
| [getValueType()](#getValueType--) | Stellt mögliche Wege zur Bestimmung der Länge der Fehlerbalken dar. |
| [setValueType(int value)](#setValueType-int-) | Stellt mögliche Wege zur Bestimmung der Länge der Fehlerbalken dar. |
| [hasEndCap()](#hasEndCap--) | Gibt an, dass am Fehlerbalken keine Endkappe gezeichnet wird. |
| [setEndCap(boolean value)](#setEndCap-boolean-) | Gibt an, dass am Fehlerbalken keine Endkappe gezeichnet wird. |
| [getValue()](#getValue--) | Liest oder schreibt den Wert, der mit Fixed, Percentage und StandardDeviation zur Bestimmung der Länge der Fehlerbalken verwendet wird. |
| [setValue(float value)](#setValue-float-) | Liest oder schreibt den Wert, der mit Fixed, Percentage und StandardDeviation zur Bestimmung der Länge der Fehlerbalken verwendet wird. |
| [getFormat()](#getFormat--) | Stellt das Format der Fehlerbalken dar. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Stellt das Format der Fehlerbalken dar. |
| [getChart()](#getChart--) | Gibt das übergeordnete Diagramm zurück. |
| [isVisible()](#isVisible--) | Liest oder schreibt die Sichtbarkeit der Fehlerbalken. |
| [setVisible(boolean value)](#setVisible-boolean-) | Liest oder schreibt die Sichtbarkeit der Fehlerbalken. |
| [getSlide()](#getSlide--) | Gibt die übergeordnete Folie eines FillFormat zurück. |
| [getPresentation()](#getPresentation--) | Gibt die übergeordnete Präsentation eines FillFormat zurück. |
### getType() {#getType--}
```
public final int getType()
```

Liest oder schreibt den Typ der Fehlerbalken. Lesen/Schreiben [ErrorBarType](../../com.aspose.slides/errorbartype).

**Rückgabe:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Liest oder schreibt den Typ der Fehlerbalken. Lesen/Schreiben [ErrorBarType](../../com.aspose.slides/errorbartype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getValueType() {#getValueType--}
```
public final int getValueType()
```

Stellt mögliche Wege zur Bestimmung der Länge der Fehlerbalken dar. Im Fall eines benutzerdefinierten Wertetyps geben Sie den Wert über die Eigenschaft ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) des jeweiligen Datenpunkts in der DataPoints-Sammlung der Serie an. Im Fall der Wertetypen Fixed, Percentage oder StandardDeviation verwenden Sie die Eigenschaft Value, um den Wert anzugeben. Lesen/Schreiben [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Rückgabe:**
int
### setValueType(int value) {#setValueType-int-}
```
public final void setValueType(int value)
```

Stellt mögliche Wege zur Bestimmung der Länge der Fehlerbalken dar. Im Fall eines benutzerdefinierten Wertetyps geben Sie den Wert über die Eigenschaft ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) des jeweiligen Datenpunkts in der DataPoints-Sammlung der Serie an. Im Fall der Wertetypen Fixed, Percentage oder StandardDeviation verwenden Sie die Eigenschaft Value, um den Wert anzugeben. Lesen/Schreiben [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### hasEndCap() {#hasEndCap--}
```
public final boolean hasEndCap()
```

Gibt an, dass am Fehlerbalken keine Endkappe gezeichnet wird. Lesen/Schreiben boolean.

**Rückgabe:**
boolean
### setEndCap(boolean value) {#setEndCap-boolean-}
```
public final void setEndCap(boolean value)
```

Gibt an, dass am Fehlerbalken keine Endkappe gezeichnet wird. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getValue() {#getValue--}
```
public final float getValue()
```

Liest oder schreibt den Wert, der mit Fixed, Percentage und StandardDeviation zur Bestimmung der Länge der Fehlerbalken verwendet wird. In allen anderen Fällen wird NaN zurückgegeben. Lesen/Schreiben float.

**Rückgabe:**
float
### setValue(float value) {#setValue-float-}
```
public final void setValue(float value)
```

Liest oder schreibt den Wert, der mit Fixed, Percentage und StandardDeviation zur Bestimmung der Länge der Fehlerbalken verwendet wird. In allen anderen Fällen wird NaN zurückgegeben. Lesen/Schreiben float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Stellt das Format der Fehlerbalken dar. Lesen/Schreiben [IFormat](../../com.aspose.slides/iformat).

**Rückgabe:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

Stellt das Format der Fehlerbalken dar. Lesen/Schreiben [IFormat](../../com.aspose.slides/iformat).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getChart() {#getChart--}
```
public final IChart getChart()
```

Gibt das übergeordnete Diagramm zurück. Nur-Lesen [IChart](../../com.aspose.slides/ichart).

**Rückgabe:**
[IChart](../../com.aspose.slides/ichart)
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

Liest oder schreibt die Sichtbarkeit der Fehlerbalken. Lesen/Schreiben boolean.

**Rückgabe:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```

Liest oder schreibt die Sichtbarkeit der Fehlerbalken. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Gibt die übergeordnete Folie eines FillFormat zurück. Nur-Lesen [BaseSlide](../../com.aspose.slides/baseslide).

**Rückgabe:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Gibt die übergeordnete Präsentation eines FillFormat zurück. Nur-Lesen [IPresentation](../../com.aspose.slides/ipresentation).

**Rückgabe:**
[IPresentation](../../com.aspose.slides/ipresentation)