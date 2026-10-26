---
title: IChart
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta un grafico su una diapositiva.
type: docs
url: /it/com.aspose.slides/ichart/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface IChart extends IGraphicalObject, IFormattedTextContainer, IOverrideThemeable
```

Rappresenta un grafico su una diapositiva.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getPlotVisibleCellsOnly()](#getPlotVisibleCellsOnly--) | Determina se vengono tracciate solo le celle visibili. |
| [setPlotVisibleCellsOnly(boolean value)](#setPlotVisibleCellsOnly-boolean-) | Determina se vengono tracciate solo le celle visibili. |
| [getDisplayBlanksAs()](#getDisplayBlanksAs--) | Restituisce o imposta il modo in cui vengono tracciate le celle vuote su un grafico. |
| [setDisplayBlanksAs(int value)](#setDisplayBlanksAs-int-) | Restituisce o imposta il modo in cui vengono tracciate le celle vuote su un grafico. |
| [getChartData()](#getChartData--) | Restituisce informazioni sui dati collegati o incorporati associati a un grafico. |
| [hasTitle()](#hasTitle--) | Determina se un grafico ha un titolo visibile. |
| [setTitle(boolean value)](#setTitle-boolean-) | Determina se un grafico ha un titolo visibile. |
| [getChartTitle()](#getChartTitle--) | Restituisce o imposta un titolo del grafico Solo lettura [IChartTitle](../../com.aspose.slides/icharttitle). |
| [hasDataTable()](#hasDataTable--) | Determina se un grafico ha una tabella dati. |
| [setDataTable(boolean value)](#setDataTable-boolean-) | Determina se un grafico ha una tabella dati. |
| [hasLegend()](#hasLegend--) | Determina se un grafico ha una legenda. |
| [setLegend(boolean value)](#setLegend-boolean-) | Determina se un grafico ha una legenda. |
| [getLegend()](#getLegend--) | Restituisce o imposta una legenda per un grafico. |
| [getChartDataTable()](#getChartDataTable--) | Restituisce una tabella dati di un grafico. |
| [getStyle()](#getStyle--) | Restituisce o imposta lo stile del grafico. |
| [setStyle(int value)](#setStyle-int-) | Restituisce o imposta lo stile del grafico. |
| [getType()](#getType--) | Restituisce o imposta il tipo di grafico. |
| [setType(int value)](#setType-int-) | Restituisce o imposta il tipo di grafico. |
| [getPlotArea()](#getPlotArea--) | Rappresenta l'area di tracciamento di un grafico. |
| [getRotation3D()](#getRotation3D--) | Restituisce una rotazione 3D di un grafico. |
| [getBackWall()](#getBackWall--) | Restituisce un oggetto che consente di modificare il formato della parete posteriore di un grafico 3D. |
| [getSideWall()](#getSideWall--) | Restituisce un oggetto che consente di modificare il formato della parete laterale di un grafico 3D. |
| [getFloor()](#getFloor--) | Restituisce un oggetto che consente di modificare il formato del pavimento di un grafico 3D. |
| [getUserShapes()](#getUserShapes--) | Specifica le forme disegnate sopra il grafico. |
| [getAxes()](#getAxes--) | Fornisce l'accesso agli assi del grafico. |
| [validateChartLayout()](#validateChartLayout--) | Calcola i valori effettivi degli elementi del grafico. |
| [getShowDataLabelsOverMaximum()](#getShowDataLabelsOverMaximum--) | Specifica che le etichette dati oltre il valore massimo del grafico devono essere mostrate. |
| [setShowDataLabelsOverMaximum(boolean value)](#setShowDataLabelsOverMaximum-boolean-) | Specifica che le etichette dati oltre il valore massimo del grafico devono essere mostrate. |
| [hasRoundedCorners()](#hasRoundedCorners--) | Specifica che l'area del grafico deve avere angoli arrotondati. |
| [setRoundedCorners(boolean value)](#setRoundedCorners-boolean-) | Specifica che l'area del grafico deve avere angoli arrotondati. |
### getPlotVisibleCellsOnly() {#getPlotVisibleCellsOnly--}
```
public abstract boolean getPlotVisibleCellsOnly()
```

Determina se vengono tracciate solo le celle visibili. False per tracciare sia le celle visibili sia quelle nascoste. boolean a lettura/scrittura.

**Restituisce:**
boolean
### setPlotVisibleCellsOnly(boolean value) {#setPlotVisibleCellsOnly-boolean-}
```
public abstract void setPlotVisibleCellsOnly(boolean value)
```

Determina se vengono tracciate solo le celle visibili. False per tracciare sia le celle visibili sia quelle nascoste. boolean a lettura/scrittura.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getDisplayBlanksAs() {#getDisplayBlanksAs--}
```
public abstract int getDisplayBlanksAs()
```

Restituisce o imposta il modo in cui vengono tracciate le celle vuote su un grafico. a lettura/scrittura [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Restituisce:**
int
### setDisplayBlanksAs(int value) {#setDisplayBlanksAs-int-}
```
public abstract void setDisplayBlanksAs(int value)
```

Restituisce o imposta il modo in cui vengono tracciate le celle vuote su un grafico. a lettura/scrittura [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getChartData() {#getChartData--}
```
public abstract IChartData getChartData()
```

Restituisce informazioni sui dati collegati o incorporati associati a un grafico. Solo lettura [IChartData](../../com.aspose.slides/ichartdata).

**Restituisce:**
[IChartData](../../com.aspose.slides/ichartdata)
### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

Determina se un grafico ha un titolo visibile. boolean a lettura/scrittura.

**Restituisce:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

Determina se un grafico ha un titolo visibile. boolean a lettura/scrittura.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getChartTitle() {#getChartTitle--}
```
public abstract IChartTitle getChartTitle()
```

Restituisce o imposta un titolo del grafico Solo lettura [IChartTitle](../../com.aspose.slides/icharttitle).

**Restituisce:**
[IChartTitle](../../com.aspose.slides/icharttitle)
### hasDataTable() {#hasDataTable--}
```
public abstract boolean hasDataTable()
```

Determina se un grafico ha una tabella dati. boolean a lettura/scrittura.

**Restituisce:**
boolean
### setDataTable(boolean value) {#setDataTable-boolean-}
```
public abstract void setDataTable(boolean value)
```

Determina se un grafico ha una tabella dati. boolean a lettura/scrittura.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### hasLegend() {#hasLegend--}
```
public abstract boolean hasLegend()
```

Determina se un grafico ha una legenda. boolean a lettura/scrittura.

**Restituisce:**
boolean
### setLegend(boolean value) {#setLegend-boolean-}
```
public abstract void setLegend(boolean value)
```

Determina se un grafico ha una legenda. boolean a lettura/scrittura.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getLegend() {#getLegend--}
```
public abstract ILegend getLegend()
```

Restituisce o imposta una legenda per un grafico. Solo lettura [ILegend](../../com.aspose.slides/ilegend).

**Restituisce:**
[ILegend](../../com.aspose.slides/ilegend)
### getChartDataTable() {#getChartDataTable--}
```
public abstract IDataTable getChartDataTable()
```

Restituisce una tabella dati di un grafico. Solo lettura [IDataTable](../../com.aspose.slides/idatatable).

**Restituisce:**
[IDataTable](../../com.aspose.slides/idatatable)
### getStyle() {#getStyle--}
```
public abstract int getStyle()
```

Restituisce o imposta lo stile del grafico. a lettura/scrittura [StyleType](../../com.aspose.slides/styletype).

**Restituisce:**
int
### setStyle(int value) {#setStyle-int-}
```
public abstract void setStyle(int value)
```

Restituisce o imposta lo stile del grafico. a lettura/scrittura [StyleType](../../com.aspose.slides/styletype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getType() {#getType--}
```
public abstract int getType()
```

Restituisce o imposta il tipo di grafico. a lettura/scrittura [ChartType](../../com.aspose.slides/charttype).

**Restituisce:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Restituisce o imposta il tipo di grafico. a lettura/scrittura [ChartType](../../com.aspose.slides/charttype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getPlotArea() {#getPlotArea--}
```
public abstract IChartPlotArea getPlotArea()
```

Rappresenta l'area di tracciamento di un grafico. Solo lettura [IChartPlotArea](../../com.aspose.slides/ichartplotarea).

**Restituisce:**
[IChartPlotArea](../../com.aspose.slides/ichartplotarea)
### getRotation3D() {#getRotation3D--}
```
public abstract IRotation3D getRotation3D()
```

Restituisce una rotazione 3D di un grafico. Solo lettura [IRotation3D](../../com.aspose.slides/irotation3d).

**Restituisce:**
[IRotation3D](../../com.aspose.slides/irotation3d)
### getBackWall() {#getBackWall--}
```
public abstract IChartWall getBackWall()
```

Restituisce un oggetto che consente di modificare il formato della parete posteriore di un grafico 3D. Solo lettura [IChartWall](../../com.aspose.slides/ichartwall).

**Restituisce:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getSideWall() {#getSideWall--}
```
public abstract IChartWall getSideWall()
```

Restituisce un oggetto che consente di modificare il formato della parete laterale di un grafico 3D. Solo lettura [IChartWall](../../com.aspose.slides/ichartwall).

**Restituisce:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getFloor() {#getFloor--}
```
public abstract IChartWall getFloor()
```

Restituisce un oggetto che consente di modificare il formato del pavimento di un grafico 3D. Solo lettura [IChartWall](../../com.aspose.slides/ichartwall).

**Restituisce:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getUserShapes() {#getUserShapes--}
```
public abstract IGroupShape getUserShapes()
```

Specifica le forme disegnate sopra il grafico. Solo lettura [IGroupShape](../../com.aspose.slides/igroupshape).

**Restituisce:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### getAxes() {#getAxes--}
```
public abstract IAxesManager getAxes()
```

Fornisce l'accesso agli assi del grafico. Solo lettura [IAxesManager](../../com.aspose.slides/iaxesmanager).

**Restituisce:**
[IAxesManager](../../com.aspose.slides/iaxesmanager)
### validateChartLayout() {#validateChartLayout--}
```
public abstract void validateChartLayout()
```

Calcola i valori effettivi degli elementi del grafico. I valori effettivi includono la posizione degli elementi che implementano l'interfaccia IActualLayout (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) e i valori effettivi degli assi (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale)
### getShowDataLabelsOverMaximum() {#getShowDataLabelsOverMaximum--}
```
public abstract boolean getShowDataLabelsOverMaximum()
```

Specifica che le etichette dati oltre il valore massimo del grafico devono essere mostrate. boolean a lettura/scrittura.

**Restituisce:**
boolean
### setShowDataLabelsOverMaximum(boolean value) {#setShowDataLabelsOverMaximum-boolean-}
```
public abstract void setShowDataLabelsOverMaximum(boolean value)
```

Specifica che le etichette dati oltre il valore massimo del grafico devono essere mostrate. boolean a lettura/scrittura.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### hasRoundedCorners() {#hasRoundedCorners--}
```
public abstract boolean hasRoundedCorners()
```

Specifica che l'area del grafico deve avere angoli arrotondati. boolean a lettura/scrittura.

**Restituisce:**
boolean
### setRoundedCorners(boolean value) {#setRoundedCorners-boolean-}
```
public abstract void setRoundedCorners(boolean value)
```

Specifica che l'area del grafico deve avere angoli arrotondati. boolean a lettura/scrittura.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |