---
title: Chart
second_title: Aspose.Slides voor Android via Java API-referentie
description: Vertegenwoordigt een grafisch diagram op een dia.
type: docs
url: /nl/com.aspose.slides/chart/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**All Implemented Interfaces:**
[com.aspose.slides.IChart](../../com.aspose.slides/ichart)
```
public class Chart extends GraphicalObject implements IChart
```

Represents an graphic chart on a slide.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [validateChartLayout()](#validateChartLayout--) | Berekent de werkelijke waarden van diagramonderdelen. |
| [getPlotVisibleCellsOnly()](#getPlotVisibleCellsOnly--) | Bepaalt of alleen de zichtbare cellen worden geplot. |
| [setPlotVisibleCellsOnly(boolean value)](#setPlotVisibleCellsOnly-boolean-) | Bepaalt of alleen de zichtbare cellen worden geplot. |
| [getDisplayBlanksAs()](#getDisplayBlanksAs--) | Geeft de manier terug of stelt de manier in om lege cellen in een diagram te plotten. |
| [setDisplayBlanksAs(int value)](#setDisplayBlanksAs-int-) | Geeft de manier terug of stelt de manier in om lege cellen in een diagram te plotten. |
| [getChartData()](#getChartData--) | Geeft informatie over de gekoppelde of ingebedde gegevens die met een diagram zijn geassocieerd. |
| [hasTitle()](#hasTitle--) | Bepaalt of een diagram een zichtbare titel heeft. |
| [setTitle(boolean value)](#setTitle-boolean-) | Bepaalt of een diagram een zichtbare titel heeft. |
| [getChartTitle()](#getChartTitle--) | Geeft een diagramtitel terug of stelt deze in. |
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
| [getBackWall()](#getBackWall--) | Geeft een object terug waarmee het formaat van de achterwand van een 3D-diagram kan worden aangepast. |
| [getSideWall()](#getSideWall--) | Geeft een object terug waarmee het formaat van de zijwand van een 3D-diagram kan worden aangepast. |
| [getFloor()](#getFloor--) | Geeft een object terug waarmee het formaat van de vloer van een 3D-diagram kan worden aangepast. |
| [getTextFormat()](#getTextFormat--) | Geeft het tekstformaat van het diagram terug. |
| [createThemeEffective()](#createThemeEffective--) | Geeft een effectief thema voor dit diagram terug. |
| [getThemeManager()](#getThemeManager--) | Geeft themabeheerder terug. |
| [getUserShapes()](#getUserShapes--) | Specificeer de vormen die boven het diagram worden getekend. |
| [getAxes()](#getAxes--) | Biedt toegang tot diagramassen. |
| [getShowDataLabelsOverMaximum()](#getShowDataLabelsOverMaximum--) | Specificeert dat gegevenslabels boven het maximum van het diagram getoond moeten worden. |
| [setShowDataLabelsOverMaximum(boolean value)](#setShowDataLabelsOverMaximum-boolean-) | Specificeert dat gegevenslabels boven het maximum van het diagram getoond moeten worden. |
| [hasRoundedCorners()](#hasRoundedCorners--) | Specificeert dat het diagramgebied afgeronde hoeken moet hebben. |
| [setRoundedCorners(boolean value)](#setRoundedCorners-boolean-) | Specificeert dat het diagramgebied afgeronde hoeken moet hebben. |
| [getChart()](#getChart--) |  |

### validateChartLayout() {#validateChartLayout--}
```
public final void validateChartLayout()
```

Berekent de werkelijke waarden van diagramonderdelen. De werkelijke waarden omvatten de positie van elementen die de IActualLayout-interface implementeren (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) en de werkelijke aswaarden (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale).

### getPlotVisibleCellsOnly() {#getPlotVisibleCellsOnly--}
```
public final boolean getPlotVisibleCellsOnly()
```

Bepaalt of alleen de zichtbare cellen worden geplot. False om zowel zichtbare als verborgen cellen te plotten. **Lezen/Schrijven** boolean.

**Retour:**
boolean
### setPlotVisibleCellsOnly(boolean value) {#setPlotVisibleCellsOnly-boolean-}
```
public final void setPlotVisibleCellsOnly(boolean value)
```

Bepaalt of alleen de zichtbare cellen worden geplot. False om zowel zichtbare als verborgen cellen te plotten. **Lezen/Schrijven** boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getDisplayBlanksAs() {#getDisplayBlanksAs--}
```
public final int getDisplayBlanksAs()
```

Geeft de manier terug of stelt de manier in om lege cellen in een diagram te plotten. **Lezen/Schrijven** [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Retour:**
int
### setDisplayBlanksAs(int value) {#setDisplayBlanksAs-int-}
```
public final void setDisplayBlanksAs(int value)
```

Geeft de manier terug of stelt de manier in om lege cellen in een diagram te plotten. **Lezen/Schrijven** [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getChartData() {#getChartData--}
```
public final IChartData getChartData()
```

Geeft informatie terug over de gekoppelde of ingebedde gegevens die aan een diagram zijn gekoppeld. **Alleen-lezen** [IChartData](../../com.aspose.slides/ichartdata).

**Retour:**
[IChartData](../../com.aspose.slides/ichartdata)
### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```

Bepaalt of een diagram een zichtbare titel heeft. **Lezen/Schrijven** boolean.

**Retour:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```

Bepaalt of een diagram een zichtbare titel heeft. **Lezen/Schrijven** boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getChartTitle() {#getChartTitle--}
```
public final IChartTitle getChartTitle()
```

Geeft een diagramtitel terug of stelt deze in. **Alleen-lezen** [IChartTitle](../../com.aspose.slides/icharttitle).

**Retour:**
[IChartTitle](../../com.aspose.slides/icharttitle)
### hasDataTable() {#hasDataTable--}
```
public final boolean hasDataTable()
```

Bepaalt of een diagram een gegevenstabel heeft. **Lezen/Schrijven** boolean.

**Retour:**
boolean
### setDataTable(boolean value) {#setDataTable-boolean-}
```
public final void setDataTable(boolean value)
```

Bepaalt of een diagram een gegevenstabel heeft. **Lezen/Schrijven** boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### hasLegend() {#hasLegend--}
```
public final boolean hasLegend()
```

Bepaalt of een diagram een legenda heeft. **Lezen/Schrijven** boolean.

**Retour:**
boolean
### setLegend(boolean value) {#setLegend-boolean-}
```
public final void setLegend(boolean value)
```

Bepaalt of een diagram een legenda heeft. **Lezen/Schrijven** boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getLegend() {#getLegend--}
```
public final ILegend getLegend()
```

Geeft een legenda voor een diagram terug of stelt deze in. **Alleen-lezen** [ILegend](../../com.aspose.slides/ilegend).

**Retour:**
[ILegend](../../com.aspose.slides/ilegend)
### getChartDataTable() {#getChartDataTable--}
```
public final IDataTable getChartDataTable()
```

Geeft een gegevenstabel van een diagram terug. **Alleen-lezen** [IDataTable](../../com.aspose.slides/idatatable).

**Retour:**
[IDataTable](../../com.aspose.slides/idatatable)
### getStyle() {#getStyle--}
```
public final int getStyle()
```

Geeft de diagramstijl terug of stelt deze in. **Lezen/Schrijven** [StyleType](../../com.aspose.slides/styletype).

**Retour:**
int
### setStyle(int value) {#setStyle-int-}
```
public final void setStyle(int value)
```

Geeft de diagramstijl terug of stelt deze in. **Lezen/Schrijven** [StyleType](../../com.aspose.slides/styletype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public final int getType()
```

Geeft het diagramtype terug of stelt dit in. **Lezen/Schrijven** [ChartType](../../com.aspose.slides/charttype).

**Retour:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Geeft het diagramtype terug of stelt dit in. **Lezen/Schrijven** [ChartType](../../com.aspose.slides/charttype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getPlotArea() {#getPlotArea--}
```
public final IChartPlotArea getPlotArea()
```

Stelt het plotgebied van een diagram voor. **Alleen-lezen** [IChartPlotArea](../../com.aspose.slides/ichartplotarea).

**Retour:**
[IChartPlotArea](../../com.aspose.slides/ichartplotarea)
### getRotation3D() {#getRotation3D--}
```
public final IRotation3D getRotation3D()
```

Geeft een 3D-rotatie van een diagram terug. **Alleen-lezen** [IRotation3D](../../com.aspose.slides/irotation3d).

**Retour:**
[IRotation3D](../../com.aspose.slides/irotation3d)
### getBackWall() {#getBackWall--}
```
public final IChartWall getBackWall()
```

Geeft een object terug waarmee het formaat van de achterwand van een 3D-diagram kan worden aangepast. **Alleen-lezen** [IChartWall](../../com.aspose.slides/ichartwall).

**Retour:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getSideWall() {#getSideWall--}
```
public final IChartWall getSideWall()
```

Geeft een object terug waarmee het formaat van de zijwand van een 3D-diagram kan worden aangepast. **Alleen-lezen** [IChartWall](../../com.aspose.slides/ichartwall).

**Retour:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getFloor() {#getFloor--}
```
public final IChartWall getFloor()
```

Geeft een object terug waarmee het formaat van de vloer van een 3D-diagram kan worden aangepast. **Alleen-lezen** [IChartWall](../../com.aspose.slides/ichartwall).

**Retour:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Geeft het tekstformaat van het diagram terug. De eigenschap is niet van toepassing op de volgende typen: [ChartType.Treemap](../../com.aspose.slides/charttype\#Treemap), [ChartType.Sunburst](../../com.aspose.slides/charttype\#Sunburst), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel),[ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker). **Alleen-lezen** [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Retour:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

Geeft een effectief thema voor dit diagram terug.

**Retour:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

Geeft themabeheerder terug. **Alleen-lezen** [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Retour:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getUserShapes() {#getUserShapes--}
```
public final IGroupShape getUserShapes()
```

Specificeer de vormen die boven het diagram worden getekend. **Alleen-lezen** [IGroupShape](../../com.aspose.slides/igroupshape).

**Retour:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### getAxes() {#getAxes--}
```
public final IAxesManager getAxes()
```

Biedt toegang tot diagramassen. **Alleen-lezen** [IAxesManager](../../com.aspose.slides/iaxesmanager).

**Retour:**
[IAxesManager](../../com.aspose.slides/iaxesmanager)
### getShowDataLabelsOverMaximum() {#getShowDataLabelsOverMaximum--}
```
public final boolean getShowDataLabelsOverMaximum()
```

Specificeert dat gegevenslabels boven het maximum van het diagram getoond moeten worden. **Lezen/Schrijven** boolean.

**Retour:**
boolean
### setShowDataLabelsOverMaximum(boolean value) {#setShowDataLabelsOverMaximum-boolean-}
```
public final void setShowDataLabelsOverMaximum(boolean value)
```

Specificeert dat gegevenslabels boven het maximum van het diagram getoond moeten worden. **Lezen/Schrijven** boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### hasRoundedCorners() {#hasRoundedCorners--}
```
public final boolean hasRoundedCorners()
```

Specificeert dat het diagramgebied afgeronde hoeken moet hebben. **Lezen/Schrijven** boolean.

**Retour:**
boolean
### setRoundedCorners(boolean value) {#setRoundedCorners-boolean-}
```
public final void setRoundedCorners(boolean value)
```

Specificeert dat het diagramgebied afgeronde hoeken moet hebben. **Lezen/Schrijven** boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getChart() {#getChart--}
```
public final IChart getChart()
```

Geeft het diagram terug. **Alleen-lezen** [IChart](../../com.aspose.slides/ichart).

**Retour:**
[IChart](../../com.aspose.slides/ichart)