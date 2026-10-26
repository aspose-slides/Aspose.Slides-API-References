---
title: IChart
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een grafisch diagram op een dia voor.
type: docs
url: /nl/com.aspose.slides/ichart/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface IChart extends IGraphicalObject, IFormattedTextContainer, IOverrideThemeable
```

Stelt een grafisch diagram op een dia voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getPlotVisibleCellsOnly()](#getPlotVisibleCellsOnly--) | Bepaalt of alleen de zichtbare cellen worden geplot. |
| [setPlotVisibleCellsOnly(boolean value)](#setPlotVisibleCellsOnly-boolean-) | Bepaalt of alleen de zichtbare cellen worden geplot. |
| [getDisplayBlanksAs()](#getDisplayBlanksAs--) | Geeft de manier terug of stelt deze in om lege cellen in een diagram te plotten. |
| [setDisplayBlanksAs(int value)](#setDisplayBlanksAs-int-) | Geeft de manier terug of stelt deze in om lege cellen in een diagram te plotten. |
| [getChartData()](#getChartData--) | Geeft informatie terug over de gekoppelde of ingesloten gegevens die bij een diagram horen. |
| [hasTitle()](#hasTitle--) | Bepaalt of een diagram een zichtbare titel heeft. |
| [setTitle(boolean value)](#setTitle-boolean-) | Bepaalt of een diagram een zichtbare titel heeft. |
| [getChartTitle()](#getChartTitle--) | Geeft een diagramtitel terug of stelt deze in Alleen-lezen [IChartTitle](../../com.aspose.slides/icharttitle). |
| [hasDataTable()](#hasDataTable--) | Bepaalt of een diagram een gegevenstabel heeft. |
| [setDataTable(boolean value)](#setDataTable-boolean-) | Bepaalt of een diagram een gegevenstabel heeft. |
| [hasLegend()](#hasLegend--) | Bepaalt of een diagram een legenda heeft. |
| [setLegend(boolean value)](#setLegend-boolean-) | Bepaalt of een diagram een legenda heeft. |
| [getLegend()](#getLegend--) | Geeft een legenda voor een diagram terug of stelt deze in. |
| [getChartDataTable()](#getChartDataTable--) | Geeft een gegevenstabel van een diagram terug. |
| [getStyle()](#getStyle--) | Geeft de diagramstijl terug of stelt deze in. |
| [setStyle(int value)](#setStyle-int-) | Geeft de diagramstijl terug of stelt deze in. |
| [getType()](#getType--) | Geeft het diagramtype terug of stelt dit in. |
| [setType(int value)](#setType-int-) | Geeft het diagramtype terug of stelt dit in. |
| [getPlotArea()](#getPlotArea--) | Stelt het plotgebied van een diagram voor. |
| [getRotation3D()](#getRotation3D--) | Geeft een 3D-rotatie van een diagram terug. |
| [getBackWall()](#getBackWall--) | Geeft een object terug dat het formaat van de achterwand van een 3D-diagram kan wijzigen. |
| [getSideWall()](#getSideWall--) | Geeft een object terug dat het formaat van de zijwand van een 3D-diagram kan wijzigen. |
| [getFloor()](#getFloor--) | Geeft een object terug dat het formaat van de vloer van een 3D-diagram kan wijzigen. |
| [getUserShapes()](#getUserShapes--) | Geef de vormen op die bovenop het diagram worden getekend. |
| [getAxes()](#getAxes--) | Biedt toegang tot diagramassen. |
| [validateChartLayout()](#validateChartLayout--) | Berekent werkelijke waarden van diagramonderdelen. |
| [getShowDataLabelsOverMaximum()](#getShowDataLabelsOverMaximum--) | Specificeert dat gegevenslabels boven het maximum van het diagram worden getoond. |
| [setShowDataLabelsOverMaximum(boolean value)](#setShowDataLabelsOverMaximum-boolean-) | Specificeert dat gegevenslabels boven het maximum van het diagram worden getoond. |
| [hasRoundedCorners()](#hasRoundedCorners--) | Specificeert dat het diagramgebied afgeronde hoeken moet hebben. |
| [setRoundedCorners(boolean value)](#setRoundedCorners-boolean-) | Specificeert dat het diagramgebied afgeronde hoeken moet hebben. |

### getPlotVisibleCellsOnly() {#getPlotVisibleCellsOnly--}
```
public abstract boolean getPlotVisibleCellsOnly()
```

Bepaalt of alleen de zichtbare cellen worden geplot. False om zowel zichtbare als verborgen cellen te plotten. Lezen/schrijven boolean.

**Retour:**
boolean

### setPlotVisibleCellsOnly(boolean value) {#setPlotVisibleCellsOnly-boolean-}
```
public abstract void setPlotVisibleCellsOnly(boolean value)
```

Bepaalt of alleen de zichtbare cellen worden geplot. False om zowel zichtbare als verborgen cellen te plotten. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDisplayBlanksAs() {#getDisplayBlanksAs--}
```
public abstract int getDisplayBlanksAs()
```

Geeft de manier terug of stelt deze in om lege cellen in een diagram te plotten. Lezen/schrijven [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Retour:**
int

### setDisplayBlanksAs(int value) {#setDisplayBlanksAs-int-}
```
public abstract void setDisplayBlanksAs(int value)
```

Geeft de manier terug of stelt deze in om lege cellen in een diagram te plotten. Lezen/schrijven [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getChartData() {#getChartData--}
```
public abstract IChartData getChartData()
```

Geeft informatie terug over de gekoppelde of ingesloten gegevens die bij een diagram horen. Alleen-lezen [IChartData](../../com.aspose.slides/ichartdata).

**Retour:**
[IChartData](../../com.aspose.slides/ichartdata)

### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

Bepaalt of een diagram een zichtbare titel heeft. Lezen/schrijven boolean.

**Retour:**
boolean

### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

Bepaalt of een diagram een zichtbare titel heeft. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getChartTitle() {#getChartTitle--}
```
public abstract IChartTitle getChartTitle()
```

Geeft een diagramtitel terug of stelt deze in Alleen-lezen [IChartTitle](../../com.aspose.slides/icharttitle).

**Retour:**
[IChartTitle](../../com.aspose.slides/icharttitle)

### hasDataTable() {#hasDataTable--}
```
public abstract boolean hasDataTable()
```

Bepaalt of een diagram een gegevenstabel heeft. Lezen/schrijven boolean.

**Retour:**
boolean

### setDataTable(boolean value) {#setDataTable-boolean-}
```
public abstract void setDataTable(boolean value)
```

Bepaalt of een diagram een gegevenstabel heeft. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### hasLegend() {#hasLegend--}
```
public abstract boolean hasLegend()
```

Bepaalt of een diagram een legenda heeft. Lezen/schrijven boolean.

**Retour:**
boolean

### setLegend(boolean value) {#setLegend-boolean-}
```
public abstract void setLegend(boolean value)
```

Bepaalt of een diagram een legenda heeft. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLegend() {#getLegend--}
```
public abstract ILegend getLegend()
```

Geeft een legenda voor een diagram terug of stelt deze in Alleen-lezen [ILegend](../../com.aspose.slides/ilegend).

**Retour:**
[ILegend](../../com.aspose.slides/ilegend)

### getChartDataTable() {#getChartDataTable--}
```
public abstract IDataTable getChartDataTable()
```

Geeft een gegevenstabel van een diagram terug Alleen-lezen [IDataTable](../../com.aspose.slides/idatatable).

**Retour:**
[IDataTable](../../com.aspose.slides/idatatable)

### getStyle() {#getStyle--}
```
public abstract int getStyle()
```

Geeft de diagramstijl terug of stelt deze in Lezen/schrijven [StyleType](../../com.aspose.slides/styletype).

**Retour:**
int

### setStyle(int value) {#setStyle-int-}
```
public abstract void setStyle(int value)
```

Geeft de diagramstijl terug of stelt deze in Lezen/schrijven [StyleType](../../com.aspose.slides/styletype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public abstract int getType()
```

Geeft het diagramtype terug of stelt dit in Lezen/schrijven [ChartType](../../com.aspose.slides/charttype).

**Retour:**
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Geeft het diagramtype terug of stelt dit in Lezen/schrijven [ChartType](../../com.aspose.slides/charttype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPlotArea() {#getPlotArea--}
```
public abstract IChartPlotArea getPlotArea()
```

Stelt het plotgebied van een diagram voor Alleen-lezen [IChartPlotArea](../../com.aspose.slides/ichartplotarea).

**Retour:**
[IChartPlotArea](../../com.aspose.slides/ichartplotarea)

### getRotation3D() {#getRotation3D--}
```
public abstract IRotation3D getRotation3D()
```

Geeft een 3D-rotatie van een diagram terug Alleen-lezen [IRotation3D](../../com.aspose.slides/irotation3d).

**Retour:**
[IRotation3D](../../com.aspose.slides/irotation3d)

### getBackWall() {#getBackWall--}
```
public abstract IChartWall getBackWall()
```

Geeft een object terug dat het formaat van de achterwand van een 3D-diagram kan wijzigen Alleen-lezen [IChartWall](../../com.aspose.slides/ichartwall).

**Retour:**
[IChartWall](../../com.aspose.slides/ichartwall)

### getSideWall() {#getSideWall--}
```
public abstract IChartWall getSideWall()
```

Geeft een object terug dat het formaat van de zijwand van een 3D-diagram kan wijzigen Alleen-lezen [IChartWall](../../com.aspose.slides/ichartwall).

**Retour:**
[IChartWall](../../com.aspose.slides/ichartwall)

### getFloor() {#getFloor--}
```
public abstract IChartWall getFloor()
```

Geeft een object terug dat het formaat van de vloer van een 3D-diagram kan wijzigen Alleen-lezen [IChartWall](../../com.aspose.slides/ichartwall).

**Retour:**
[IChartWall](../../com.aspose.slides/ichartwall)

### getUserShapes() {#getUserShapes--}
```
public abstract IGroupShape getUserShapes()
```

Geef de vormen op die bovenop het diagram worden getekend Alleen-lezen [IGroupShape](../../com.aspose.slides/igroupshape).

**Retour:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### getAxes() {#getAxes--}
```
public abstract IAxesManager getAxes()
```

Biedt toegang tot diagramassen Alleen-lezen [IAxesManager](../../com.aspose.slides/iaxesmanager).

**Retour:**
[IAxesManager](../../com.aspose.slides/iaxesmanager)

### validateChartLayout() {#validateChartLayout--}
```
public abstract void validateChartLayout()
```

Berekent werkelijke waarden van diagramonderdelen. Werkelijke waarden omvatten positie van elementen die de IActualLayout-interface implementeren (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) en werkelijke as-waarden (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale)

### getShowDataLabelsOverMaximum() {#getShowDataLabelsOverMaximum--}
```
public abstract boolean getShowDataLabelsOverMaximum()
```

Specificeert dat gegevenslabels boven het maximum van het diagram worden getoond. Lezen/schrijven boolean.

**Retour:**
boolean

### setShowDataLabelsOverMaximum(boolean value) {#setShowDataLabelsOverMaximum-boolean-}
```
public abstract void setShowDataLabelsOverMaximum(boolean value)
```

Specificeert dat gegevenslabels boven het maximum van het diagram worden getoond. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### hasRoundedCorners() {#hasRoundedCorners--}
```
public abstract boolean hasRoundedCorners()
```

Specificeert dat het diagramgebied afgeronde hoeken moet hebben. Lezen/schrijven boolean.

**Retour:**
boolean

### setRoundedCorners(boolean value) {#setRoundedCorners-boolean-}
```
public abstract void setRoundedCorners(boolean value)
```

Specificeert dat het diagramgebied afgeronde hoeken moet hebben. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |