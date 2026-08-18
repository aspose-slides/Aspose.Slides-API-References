---
title: ErrorBarsCustomValues
second_title: Aspose.Slides für Java API-Referenz
description: Gibt die Werte der Fehlerbalken an.
type: docs
url: /de/com.aspose.slides/errorbarscustomvalues/
---
**Vererbung:**
java.lang.Object, com.aspose.slides.DomObject

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)
```
public class ErrorBarsCustomValues extends DomObject<ChartDataPoint> implements IErrorBarsCustomValues
```

Gibt die Werte der Error bars an. Sie darf nur verwendet werden, wenn der Error bars value type Custom ist.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getXMinus()](#getXMinus--) | Gibt den Wert des Fehlerbalkens in negativer Richtung an. |
| [getYMinus()](#getYMinus--) | Gibt den Wert des Fehlerbalkens in negativer Richtung an. |
| [getXPlus()](#getXPlus--) | Gibt den Wert des Fehlerbalkens in positiver Richtung an. |
| [getYPlus()](#getYPlus--) | Gibt den Wert des Fehlerbalkens in positiver Richtung an. |
### getXMinus() {#getXMinus--}
```
public final IDoubleChartValue getXMinus()
```


Gibt den Fehlerbalkenwert in negativer Richtung an. Verfügbar, wenn der Error bars value type Custom ist und ErrorBarsXFormat erlaubt ist. In allen anderen Fällen gibt diese Eigenschaft null zurück. Nur lesbar [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Rückgabe:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getYMinus() {#getYMinus--}
```
public final IDoubleChartValue getYMinus()
```


Gibt den Fehlerbalkenwert in negativer Richtung an. Verfügbar, wenn der Error bars value type Custom ist und ErrorBarsYFormat erlaubt ist. In allen anderen Fällen gibt diese Eigenschaft null zurück. Nur lesbar [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Rückgabe:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getXPlus() {#getXPlus--}
```
public final IDoubleChartValue getXPlus()
```


Gibt den Fehlerbalkenwert in positiver Richtung an. Verfügbar, wenn der Error bars value type Custom ist und ErrorBarsXFormat erlaubt ist. In allen anderen Fällen gibt diese Eigenschaft null zurück. Nur lesbar [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Rückgabe:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getYPlus() {#getYPlus--}
```
public final IDoubleChartValue getYPlus()
```


Gibt den Fehlerbalkenwert in positiver Richtung an. Verfügbar, wenn der Error bars value type Custom ist und ErrorBarsYFormat erlaubt ist. In allen anderen Fällen gibt diese Eigenschaft null zurück. Nur lesbar [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Rückgabe:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)