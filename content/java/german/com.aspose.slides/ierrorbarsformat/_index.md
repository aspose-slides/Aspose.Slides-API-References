---
title: IErrorBarsFormat
second_title: Aspose.Slides für Java API Referenz
description: Stellt Fehlerbalken einer Diagrammserie dar.
type: docs
url: /de/com.aspose.slides/ierrorbarsformat/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IErrorBarsFormat extends IChartComponent
```

Stellt Fehlerbalken einer Diagrammserie dar. Benutzerdefinierte Werte von ErrorBars befinden sich in IChartDataPointCollection (in [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) Eigenschaft).
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getType()](#getType--) | Liest oder legt den Typ der Fehlerbalken fest. |
| [setType(int value)](#setType-int-) | Liest oder legt den Typ der Fehlerbalken fest. |
| [getValueType()](#getValueType--) | Stellt mögliche Wege zur Bestimmung der Länge der Fehlerbalken dar. |
| [setValueType(int value)](#setValueType-int-) | Stellt mögliche Wege zur Bestimmung der Länge der Fehlerbalken dar. |
| [hasEndCap()](#hasEndCap--) | Gibt an, dass auf den Fehlerbalken keine Endkappe gezeichnet wird. |
| [setEndCap(boolean value)](#setEndCap-boolean-) | Gibt an, dass auf den Fehlerbalken keine Endkappe gezeichnet wird. |
| [getValue()](#getValue--) | Liest oder legt den Wert fest, der zusammen mit den Werttypen Fixed, Percentage und StandardDeviation zur Bestimmung der Länge der Fehlerbalken verwendet wird. |
| [setValue(float value)](#setValue-float-) | Liest oder legt den Wert fest, der zusammen mit den Werttypen Fixed, Percentage und StandardDeviation zur Bestimmung der Länge der Fehlerbalken verwendet wird. |
| [getFormat()](#getFormat--) | Stellt das Format der Fehlerbalken dar. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Stellt das Format der Fehlerbalken dar. |
| [isVisible()](#isVisible--) | Liest oder legt die Sichtbarkeit der Fehlerbalken fest. |
| [setVisible(boolean value)](#setVisible-boolean-) | Liest oder legt die Sichtbarkeit der Fehlerbalken fest. |
### getType() {#getType--}
```
public abstract int getType()
```

Liest oder legt den Typ der Fehlerbalken fest. Lesen/Schreiben [ErrorBarType](../../com.aspose.slides/errorbartype).

**Rückgabewert:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Liest oder legt den Typ der Fehlerbalken fest. Lesen/Schreiben [ErrorBarType](../../com.aspose.slides/errorbartype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getValueType() {#getValueType--}
```
public abstract int getValueType()
```

Stellt mögliche Wege zur Bestimmung der Länge der Fehlerbalken dar. Im Fall eines benutzerdefinierten Werttyps verwenden Sie die [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) Eigenschaft des jeweiligen Datenpunkts in DataPoints collection der Serie. Lesen/Schreiben [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Rückgabewert:**
int
### setValueType(int value) {#setValueType-int-}
```
public abstract void setValueType(int value)
```

Stellt mögliche Wege zur Bestimmung der Länge der Fehlerbalken dar. Im Fall eines benutzerdefinierten Werttyps verwenden Sie die [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) Eigenschaft des jeweiligen Datenpunkts in DataPoints collection der Serie. Lesen/Schreiben [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### hasEndCap() {#hasEndCap--}
```
public abstract boolean hasEndCap()
```

Gibt an, dass auf den Fehlerbalken keine Endkappe gezeichnet wird. Lesen/Schreiben boolean.

**Rückgabewert:**
boolean
### setEndCap(boolean value) {#setEndCap-boolean-}
```
public abstract void setEndCap(boolean value)
```

Gibt an, dass auf den Fehlerbalken keine Endkappe gezeichnet wird. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getValue() {#getValue--}
```
public abstract float getValue()
```

Liest oder legt den Wert fest, der zusammen mit den Werttypen Fixed, Percentage und StandardDeviation zur Bestimmung der Länge der Fehlerbalken verwendet wird. Lesen/Schreiben float.

**Rückgabewert:**
float
### setValue(float value) {#setValue-float-}
```
public abstract void setValue(float value)
```

Liest oder legt den Wert fest, der zusammen mit den Werttypen Fixed, Percentage und StandardDeviation zur Bestimmung der Länge der Fehlerbalken verwendet wird. Lesen/Schreiben float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Stellt das Format der Fehlerbalken dar. Lesen/Schreiben [IFormat](../../com.aspose.slides/iformat).

**Rückgabewert:**
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

Liest oder legt die Sichtbarkeit der Fehlerbalken fest. Lesen/Schreiben boolean.

**Rückgabewert:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

Liest oder legt die Sichtbarkeit der Fehlerbalken fest. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |