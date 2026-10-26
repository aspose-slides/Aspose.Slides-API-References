---
title: IErrorBarsFormat
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt Fehlerbalken von Diagrammserien dar.
type: docs
url: /de/com.aspose.slides/ierrorbarsformat/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IErrorBarsFormat extends IChartComponent
```

Stellt Fehlerbalken einer Diagrammreihe dar. Benutzerdefinierte ErrorBars-Werte befinden sich in IChartDataPointCollection (in [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) Eigenschaft).

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getType()](#getType--) | Liest oder setzt den Typ der Fehlerbalken. |
| [setType(int value)](#setType-int-) | Liest oder setzt den Typ der Fehlerbalken. |
| [getValueType()](#getValueType--) | Stellt mögliche Wege zur Bestimmung der Länge der Fehlerbalken dar. |
| [setValueType(int value)](#setValueType-int-) | Stellt mögliche Wege zur Bestimmung der Länge der Fehlerbalken dar. |
| [hasEndCap()](#hasEndCap--) | Gibt an, dass an den Fehlerbalken keine Endkappe gezeichnet wird. |
| [setEndCap(boolean value)](#setEndCap-boolean-) | Gibt an, dass an den Fehlerbalken keine Endkappe gezeichnet wird. |
| [getValue()](#getValue--) | Liest oder setzt den Wert, der zusammen mit den Werttypen Fixed, Percentage und StandardDeviation zur Bestimmung der Länge der Fehlerbalken verwendet wird. |
| [setValue(float value)](#setValue-float-) | Liest oder setzt den Wert, der zusammen mit den Werttypen Fixed, Percentage und StandardDeviation zur Bestimmung der Länge der Fehlerbalken verwendet wird. |
| [getFormat()](#getFormat--) | Stellt das Format der Fehlerbalken dar. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Stellt das Format der Fehlerbalken dar. |
| [isVisible()](#isVisible--) | Liest oder setzt die Sichtbarkeit der Fehlerbalken. |
| [setVisible(boolean value)](#setVisible-boolean-) | Liest oder setzt die Sichtbarkeit der Fehlerbalken. |
### getType() {#getType--}
```
public abstract int getType()
```

Liest oder setzt den Typ der Fehlerbalken. Lesen/Schreiben [ErrorBarType](../../com.aspose.slides/errorbartype).

**Rückgabe:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Liest oder setzt den Typ der Fehlerbalken. Lesen/Schreiben [ErrorBarType](../../com.aspose.slides/errorbartype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getValueType() {#getValueType--}
```
public abstract int getValueType()
```

Stellt mögliche Wege zur Bestimmung der Länge der Fehlerbalken dar. Im Fall eines benutzerdefinierten Werttyps wird zum Festlegen des Werts die [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)-Eigenschaft des jeweiligen Datenpunkts in der DataPoints-Sammlung der Reihe verwendet. Lesen/Schreiben [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Rückgabe:**
int
### setValueType(int value) {#setValueType-int-}
```
public abstract void setValueType(int value)
```

Stellt mögliche Wege zur Bestimmung der Länge der Fehlerbalken dar. Im Fall eines benutzerdefinierten Werttyps wird zum Festlegen des Werts die [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)-Eigenschaft des jeweiligen Datenpunkts in der DataPoints-Sammlung der Reihe verwendet. Lesen/Schreiben [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### hasEndCap() {#hasEndCap--}
```
public abstract boolean hasEndCap()
```

Gibt an, dass an den Fehlerbalken keine Endkappe gezeichnet wird. Lesen/Schreiben boolean.

**Rückgabe:**
boolean
### setEndCap(boolean value) {#setEndCap-boolean-}
```
public abstract void setEndCap(boolean value)
```

Gibt an, dass an den Fehlerbalken keine Endkappe gezeichnet wird. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getValue() {#getValue--}
```
public abstract float getValue()
```

Liest oder setzt den Wert, der zusammen mit den Werttypen Fixed, Percentage und StandardDeviation zur Bestimmung der Länge der Fehlerbalken verwendet wird. Lesen/Schreiben float.

**Rückgabe:**
float
### setValue(float value) {#setValue-float-}
```
public abstract void setValue(float value)
```

Liest oder setzt den Wert, der zusammen mit den Werttypen Fixed, Percentage und StandardDeviation zur Bestimmung der Länge der Fehlerbalken verwendet wird. Lesen/Schreiben float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Stellt das Format der Fehlerbalken dar. Lesen/Schreiben [IFormat](../../com.aspose.slides/iformat).

**Rückgabe:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

Stellt das Format der Fehlerbalken dar. Lesen/Schreiben [IFormat](../../com.aspose.slides/iformat).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

Liest oder setzt die Sichtbarkeit der Fehlerbalken. Lesen/Schreiben boolean.

**Rückgabe:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

Liest oder setzt die Sichtbarkeit der Fehlerbalken. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |