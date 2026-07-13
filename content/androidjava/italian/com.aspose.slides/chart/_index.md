---
title: Chart
second_title: Riferimento API Java di Aspose.Slides per Android
description: Rappresenta un grafico su una diapositiva.
type: docs
url: /it/com.aspose.slides/chart/
---
**Eredità:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Tutte le interfacce implementate:**
[com.aspose.slides.IChart](../../com.aspose.slides/ichart)
```
public class Chart extends GraphicalObject implements IChart
```

Rappresenta un grafico su una diapositiva.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [validateChartLayout()](#validateChartLayout--) | Calcola i valori effettivi degli elementi del grafico. |
| [getPlotVisibleCellsOnly()](#getPlotVisibleCellsOnly--) | Determina se vengono tracciate solo le celle visibili. |
| [setPlotVisibleCellsOnly(boolean value)](#setPlotVisibleCellsOnly-boolean-) | Determina se vengono tracciate solo le celle visibili. |
| [getDisplayBlanksAs()](#getDisplayBlanksAs--) | Restituisce o imposta il modo di tracciare le celle vuote in un grafico. |
| [setDisplayBlanksAs(int value)](#setDisplayBlanksAs-int-) | Restituisce o imposta il modo di tracciare le celle vuote in un grafico. |
| [getChartData()](#getChartData--) | Restituisce informazioni sui dati collegati o incorporati associati a un grafico. |
| [hasTitle()](#hasTitle--) | Determina se un grafico ha un titolo visibile. |
| [setTitle(boolean value)](#setTitle-boolean-) | Determina se un grafico ha un titolo visibile. |
| [getChartTitle()](#getChartTitle--) | Restituisce o imposta il titolo di un grafico. |
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
| [getTextFormat()](#getTextFormat--) | Restituisce il formato del testo del grafico. |
| [createThemeEffective()](#createThemeEffective--) | Restituisce un tema efficace per questo grafico. |
| [getThemeManager()](#getThemeManager--) | Restituisce il gestore dei temi. |
| [getUserShapes()](#getUserShapes--) | Specifica le forme disegnate sopra il grafico. |
| [getAxes()](#getAxes--) | Fornisce accesso agli assi del grafico. |
| [getShowDataLabelsOverMaximum()](#getShowDataLabelsOverMaximum--) | Specifica che le etichette dei dati sopra il massimo del grafico devono essere mostrate. |
| [setShowDataLabelsOverMaximum(boolean value)](#setShowDataLabelsOverMaximum-boolean-) | Specifica che le etichette dei dati sopra il massimo del grafico devono essere mostrate. |
| [hasRoundedCorners()](#hasRoundedCorners--) | Specifica che l'area del grafico deve avere angoli arrotondati. |
| [setRoundedCorners(boolean value)](#setRoundedCorners-boolean-) | Specifica che l'area del grafico deve avere angoli arrotondati. |
| [getChart()](#getChart--) |  |

### validateChartLayout() {#validateChartLayout--}
```
public final void validateChartLayout()
```

Calcola i valori effettivi degli elementi del grafico. I valori effettivi includono la posizione degli elementi che implementano l'interfaccia IActualLayout (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) e i valori effettivi degli assi (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale)

### getPlotVisibleCellsOnly() {#getPlotVisibleCellsOnly--}
```
public final boolean getPlotVisibleCellsOnly()
```

Determina se vengono tracciate solo le celle visibili. False per tracciare sia le celle visibili che quelle nascoste. Lettura/scrittura boolean.

**Restituisce:**
boolean

### setPlotVisibleCellsOnly(boolean value) {#setPlotVisibleCellsOnly-boolean-}
```
public final void setPlotVisibleCellsOnly(boolean value)
```

Determina se vengono tracciate solo le celle visibili. False per tracciare sia le celle visibili che quelle nascoste. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getDisplayBlanksAs() {#getDisplayBlanksAs--}
```
public final int getDisplayBlanksAs()
```

Restituisce o imposta il modo di tracciare le celle vuote in un grafico. Lettura/scrittura [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Restituisce:**
int

### setDisplayBlanksAs(int value) {#setDisplayBlanksAs-int-}
```
public final void setDisplayBlanksAs(int value)
```

Restituisce o imposta il modo di tracciare le celle vuote in un grafico. Lettura/scrittura [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getChartData() {#getChartData--}
```
public final IChartData getChartData()
```

Restituisce informazioni sui dati collegati o incorporati associati a un grafico. Lettura solo [IChartData](../../com.aspose.slides/ichartdata).

**Restituisce:**
[IChartData](../../com.aspose.slides/ichartdata)

### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```

Determina se un grafico ha un titolo visibile. Lettura/scrittura boolean.

**Restituisce:**
boolean

### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```

Determina se un grafico ha un titolo visibile. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getChartTitle() {#getChartTitle--}
```
public final IChartTitle getChartTitle()
```

Restituisce o imposta il titolo di un grafico. Lettura sola [IChartTitle](../../com.aspose.slides/icharttitle).

**Restituisce:**
[IChartTitle](../../com.aspose.slides/icharttitle)

### hasDataTable() {#hasDataTable--}
```
public final boolean hasDataTable()
```

Determina se un grafico ha una tabella dati. Lettura/scrittura boolean.

**Restituisce:**
boolean

### setDataTable(boolean value) {#setDataTable-boolean-}
```
public final void setDataTable(boolean value)
```

Determina se un grafico ha una tabella dati. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### hasLegend() {#hasLegend--}
```
public final boolean hasLegend()
```

Determina se un grafico ha una legenda. Lettura/scrittura boolean.

**Restituisce:**
boolean

### setLegend(boolean value) {#setLegend-boolean-}
```
public final void setLegend(boolean value)
```

Determina se un grafico ha una legenda. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getLegend() {#getLegend--}
```
public final ILegend getLegend()
```

Restituisce o imposta una legenda per un grafico. Lettura solo [ILegend](../../com.aspose.slides/ilegend).

**Restituisce:**
[ILegend](../../com.aspose.slides/ilegend)

### getChartDataTable() {#getChartDataTable--}
```
public final IDataTable getChartDataTable()
```

Restituisce una tabella dati di un grafico. Lettura sola [IDataTable](../../com.aspose.slides/idatatable).

**Restituisce:**
[IDataTable](../../com.aspose.slides/idatatable)

### getStyle() {#getStyle--}
```
public final int getStyle()
```

Restituisce o imposta lo stile del grafico. Lettura/scrittura [StyleType](../../com.aspose.slides/styletype).

**Restituisce:**
int

### setStyle(int value) {#setStyle-int-}
```
public final void setStyle(int value)
```

Restituisce o imposta lo stile del grafico. Lettura/scrittura [StyleType](../../com.aspose.slides/styletype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public final int getType()
```

Restituisce o imposta il tipo di grafico. Lettura/scrittura [ChartType](../../com.aspose.slides/charttype).

**Restituisce:**
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Restituisce o imposta il tipo di grafico. Lettura/scrittura [ChartType](../../com.aspose.slides/charttype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getPlotArea() {#getPlotArea--}
```
public final IChartPlotArea getPlotArea()
```

Rappresenta l'area di tracciamento di un grafico. Lettura sola [IChartPlotArea](../../com.aspose.slides/ichartplotarea).

**Restituisce:**
[IChartPlotArea](../../com.aspose.slides/ichartplotarea)

### getRotation3D() {#getRotation3D--}
```
public final IRotation3D getRotation3D()
```

Restituisce una rotazione 3D di un grafico. Lettura sola [IRotation3D](../../com.aspose.slides/irotation3d).

**Restituisce:**
[IRotation3D](../../com.aspose.slides/irotation3d)

### getBackWall() {#getBackWall--}
```
public final IChartWall getBackWall()
```

Restituisce un oggetto che consente di modificare il formato della parete posteriore di un grafico 3D. Lettura sola [IChartWall](../../com.aspose.slides/ichartwall).

**Restituisce:**
[IChartWall](../../com.aspose.slides/ichartwall)

### getSideWall() {#getSideWall--}
```
public final IChartWall getSideWall()
```

Restituisce un oggetto che consente di modificare il formato della parete laterale di un grafico 3D. Lettura sola [IChartWall](../../com.aspose.slides/ichartwall).

**Restituisce:**
[IChartWall](../../com.aspose.slides/ichartwall)

### getFloor() {#getFloor--}
```
public final IChartWall getFloor()
```

Restituisce un oggetto che consente di modificare il formato del pavimento di un grafico 3D. Lettura sola [IChartWall](../../com.aspose.slides/ichartwall).

**Restituisce:**
[IChartWall](../../com.aspose.slides/ichartwall)

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Restituisce il formato del testo del grafico. La proprietà non è applicabile per i seguenti tipi: [ChartType.Treemap](../../com.aspose.slides/charttype\#Treemap), [ChartType.Sunburst](../../com.aspose.slides/charttype\#Sunburst), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel),[ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker). Lettura sola [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Restituisce:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

Restituisce un tema efficace per questo grafico.

**Restituisce:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)

### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

Restituisce il gestore dei temi. Lettura sola [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Restituisce:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)

### getUserShapes() {#getUserShapes--}
```
public final IGroupShape getUserShapes()
```

Specificare le forme disegnate sopra il grafico. Lettura sola [IGroupShape](../../com.aspose.slides/igroupshape).

**Restituisce:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### getAxes() {#getAxes--}
```
public final IAxesManager getAxes()
```

Fornisce accesso agli assi del grafico. Lettura sola [IAxesManager](../../com.aspose.slides/iaxesmanager).

**Restituisce:**
[IAxesManager](../../com.aspose.slides/iaxesmanager)

### getShowDataLabelsOverMaximum() {#getShowDataLabelsOverMaximum--}
```
public final boolean getShowDataLabelsOverMaximum()
```

Specificare che le etichette dei dati sopra il massimo del grafico devono essere mostrate. Lettura/scrittura boolean.

**Restituisce:**
boolean

### setShowDataLabelsOverMaximum(boolean value) {#setShowDataLabelsOverMaximum-boolean-}
```
public final void setShowDataLabelsOverMaximum(boolean value)
```

Specificare che le etichette dei dati sopra il massimo del grafico devono essere mostrate. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### hasRoundedCorners() {#hasRoundedCorners--}
```
public final boolean hasRoundedCorners()
```

Specificare che l'area del grafico deve avere angoli arrotondati. Lettura/scrittura boolean.

**Restituisce:**
boolean

### setRoundedCorners(boolean value) {#setRoundedCorners-boolean-}
```
public final void setRoundedCorners(boolean value)
```

Specificare che l'area del grafico deve avere angoli arrotondati. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getChart() {#getChart--}
```
public final IChart getChart()
```

Restituisce il grafico. Lettura sola [IChart](../../com.aspose.slides/ichart).

**Restituisce:**
[IChart](../../com.aspose.slides/ichart)