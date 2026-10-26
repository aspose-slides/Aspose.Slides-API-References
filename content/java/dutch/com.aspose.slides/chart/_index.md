---
title: Chart
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een grafische chart voor op een dia.
type: docs
url: /nl/com.aspose.slides/chart/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IChart](../../com.aspose.slides/ichart)
```
public class Chart extends GraphicalObject implements IChart
```

Stelt een grafische chart voor op een dia.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [validateChartLayout()](#validateChartLayout--) | Bereken de actuele waarden van chart-elementen. |
| [getPlotVisibleCellsOnly()](#getPlotVisibleCellsOnly--) | Bepaalt of alleen de zichtbare cellen worden geplot. |
| [setPlotVisibleCellsOnly(boolean value)](#setPlotVisibleCellsOnly-boolean-) | Bepaalt of alleen de zichtbare cellen worden geplot. |
| [getDisplayBlanksAs()](#getDisplayBlanksAs--) | Retourneert of stelt de manier in waarop lege cellen worden geplot op een chart. |
| [setDisplayBlanksAs(int value)](#setDisplayBlanksAs-int-) | Retourneert of stelt de manier in waarop lege cellen worden geplot op een chart. |
| [getChartData()](#getChartData--) | Retourneert informatie over de gekoppelde of ingesloten gegevens die aan een chart zijn gekoppeld. |
| [hasTitle()](#hasTitle--) | Bepaalt of een chart een zichtbare titel heeft. |
| [setTitle(boolean value)](#setTitle-boolean-) | Bepaalt of een chart een zichtbare titel heeft. |
| [getChartTitle()](#getChartTitle--) | Retourneert of stelt een chart-titel in. |
| [hasDataTable()](#hasDataTable--) | Bepaalt of een chart een gegevens-tabel heeft. |
| [setDataTable(boolean value)](#setDataTable-boolean-) | Bepaalt of een chart een gegevens-tabel heeft. |
| [hasLegend()](#hasLegend--) | Bepaalt of een chart een legenda heeft. |
| [setLegend(boolean value)](#setLegend-boolean-) | Bepaalt of een chart een legenda heeft. |
| [getLegend()](#getLegend--) | Retourneert of stelt een legenda voor een chart in. |
| [getChartDataTable()](#getChartDataTable--) | Retourneert een gegevens-tabel van een chart. |
| [getStyle()](#getStyle--) | Retourneert of stelt de chart-stijl in. |
| [setStyle(int value)](#setStyle-int-) | Retourneert of stelt de chart-stijl in. |
| [getType()](#getType--) | Retourneert of stelt het chart-type in. |
| [setType(int value)](#setType-int-) | Retourneert of stelt het chart-type in. |
| [getPlotArea()](#getPlotArea--) | Stelt het plotgebied van een chart voor. |
| [getRotation3D()](#getRotation3D--) | Retourneert een 3D-rotatie van een chart. |
| [getBackWall()](#getBackWall--) | Retourneert een object waarmee het formaat van de achterwand van een 3D-chart kan worden gewijzigd. |
| [getSideWall()](#getSideWall--) | Retourneert een object waarmee het formaat van de zijwand van een 3D-chart kan worden gewijzigd. |
| [getFloor()](#getFloor--) | Retourneert een object waarmee het formaat van de vloer van een 3D-chart kan worden gewijzigd. |
| [getTextFormat()](#getTextFormat--) | Retourneert het tekstformaat van de chart. |
| [createThemeEffective()](#createThemeEffective--) | Retourneert een effectief thema voor deze chart. |
| [getThemeManager()](#getThemeManager--) | Retourneert themabeheerder. |
| [getUserShapes()](#getUserShapes--) | Specificeer de vormen die boven op de chart getekend worden. |
| [getAxes()](#getAxes--) | Geef toegang tot de assen van de chart. |
| [getShowDataLabelsOverMaximum()](#getShowDataLabelsOverMaximum--) | Specificeert of datalabels boven het maximum van de chart moeten worden weergegeven. |
| [setShowDataLabelsOverMaximum(boolean value)](#setShowDataLabelsOverMaximum-boolean-) | Specificeert of datalabels boven het maximum van de chart moeten worden weergegeven. |
| [hasRoundedCorners()](#hasRoundedCorners--) | Specificeert dat het chart-gebied afgeronde hoeken moet hebben. |
| [setRoundedCorners(boolean value)](#setRoundedCorners-boolean-) | Specificeert dat het chart-gebied afgeronde hoeken moet hebben. |
| [getChart()](#getChart--) |  |
### validateChartLayout() {#validateChartLayout--}
```
public final void validateChartLayout()
```


Bereken de actuele waarden van chart-elementen. De actuele waarden omvatten de positie van elementen die de IActualLayout-interface implementeren (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) en de actuele aswaarden (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale).

### getPlotVisibleCellsOnly() {#getPlotVisibleCellsOnly--}
```
public final boolean getPlotVisibleCellsOnly()
```


Bepaalt of alleen de zichtbare cellen worden geplot. False om zowel zichtbare als verborgen cellen te plotten. Lezen/schrijven boolean.

**Retour:**
boolean
### setPlotVisibleCellsOnly(boolean value) {#setPlotVisibleCellsOnly-boolean-}
```
public final void setPlotVisibleCellsOnly(boolean value)
```


Bepaalt of alleen de zichtbare cellen worden geplot. False om zowel zichtbare als verborgen cellen te plotten. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getDisplayBlanksAs() {#getDisplayBlanksAs--}
```
public final int getDisplayBlanksAs()
```


Retourneert of stelt de manier in waarop lege cellen worden geplot op een chart. Lezen/schrijven [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Retour:**
int
### setDisplayBlanksAs(int value) {#setDisplayBlanksAs-int-}
```
public final void setDisplayBlanksAs(int value)
```


Retourneert of stelt de manier in waarop lege cellen worden geplot op een chart. Lezen/schrijven [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getChartData() {#getChartData--}
```
public final IChartData getChartData()
```


Retourneert informatie over de gekoppelde of ingesloten gegevens die aan een chart zijn gekoppeld. Alleen lezen [IChartData](../../com.aspose.slides/ichartdata).

**Retour:**
[IChartData](../../com.aspose.slides/ichartdata)
### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```


Bepaalt of een chart een zichtbare titel heeft. Lezen/schrijven boolean.

**Retour:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```


Bepaalt of een chart een zichtbare titel heeft. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getChartTitle() {#getChartTitle--}
```
public final IChartTitle getChartTitle()
```


Retourneert of stelt een chart-titel in. Alleen lezen [IChartTitle](../../com.aspose.slides/icharttitle).

**Retour:**
[IChartTitle](../../com.aspose.slides/icharttitle)
### hasDataTable() {#hasDataTable--}
```
public final boolean hasDataTable()
```


Bepaalt of een chart een gegevens-tabel heeft. Lezen/schrijven boolean.

**Retour:**
boolean
### setDataTable(boolean value) {#setDataTable-boolean-}
```
public final void setDataTable(boolean value)
```


Bepaalt of een chart een gegevens-tabel heeft. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### hasLegend() {#hasLegend--}
```
public final boolean hasLegend()
```


Bepaalt of een chart een legenda heeft. Lezen/schrijven boolean.

**Retour:**
boolean
### setLegend(boolean value) {#setLegend-boolean-}
```
public final void setLegend(boolean value)
```


Bepaalt of een chart een legenda heeft. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getLegend() {#getLegend--}
```
public final ILegend getLegend()
```


Retourneert of stelt een legenda voor een chart in. Alleen lezen [ILegend](../../com.aspose.slides/ilegend).

**Retour:**
[ILegend](../../com.aspose.slides/ilegend)
### getChartDataTable() {#getChartDataTable--}
```
public final IDataTable getChartDataTable()
```


Retourneert een gegevens-tabel van een chart. Alleen lezen [IDataTable](../../com.aspose.slides/idatatable).

**Retour:**
[IDataTable](../../com.aspose.slides/idatatable)
### getStyle() {#getStyle--}
```
public final int getStyle()
```


Retourneert of stelt de chart-stijl in. Lezen/schrijven [StyleType](../../com.aspose.slides/styletype).

**Retour:**
int
### setStyle(int value) {#setStyle-int-}
```
public final void setStyle(int value)
```


Retourneert of stelt de chart-stijl in. Lezen/schrijven [StyleType](../../com.aspose.slides/styletype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public final int getType()
```


Retourneert of stelt het chart-type in. Lezen/schrijven [ChartType](../../com.aspose.slides/charttype).

**Retour:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


Retourneert of stelt het chart-type in. Lezen/schrijven [ChartType](../../com.aspose.slides/charttype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getPlotArea() {#getPlotArea--}
```
public final IChartPlotArea getPlotArea()
```


Stelt het plotgebied van een chart voor. Alleen lezen [IChartPlotArea](../../com.aspose.slides/ichartplotarea).

**Retour:**
[IChartPlotArea](../../com.aspose.slides/ichartplotarea)
### getRotation3D() {#getRotation3D--}
```
public final IRotation3D getRotation3D()
```


Retourneert een 3D-rotatie van een chart. Alleen lezen [IRotation3D](../../com.aspose.slides/irotation3d).

**Retour:**
[IRotation3D](../../com.aspose.slides/irotation3d)
### getBackWall() {#getBackWall--}
```
public final IChartWall getBackWall()
```


Retourneert een object waarmee het formaat van de achterwand van een 3D-chart kan worden gewijzigd. Alleen lezen [IChartWall](../../com.aspose.slides/ichartwall).

**Retour:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getSideWall() {#getSideWall--}
```
public final IChartWall getSideWall()
```


Retourneert een object waarmee het formaat van de zijwand van een 3D-chart kan worden gewijzigd. Alleen lezen [IChartWall](../../com.aspose.slides/ichartwall).

**Retour:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getFloor() {#getFloor--}
```
public final IChartWall getFloor()
```


Retourneert een object waarmee het formaat van de vloer van een 3D-chart kan worden gewijzigd. Alleen lezen [IChartWall](../../com.aspose.slides/ichartwall).

**Retour:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```


Retourneert chart-tekstformaat. De eigenschap is niet toepasbaar voor de volgende types: [ChartType.Treemap](../../com.aspose.slides/charttype\#Treemap), [ChartType.Sunburst](../../com.aspose.slides/charttype\#Sunburst), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel),[ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker). Alleen lezen [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Retour:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```


Retourneert een effectief thema voor deze chart.

**Retour:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```


Retourneert themabeheerder. Alleen lezen [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Retour:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getUserShapes() {#getUserShapes--}
```
public final IGroupShape getUserShapes()
```


Specificeer de vormen die boven op de chart getekend worden. Alleen lezen [IGroupShape](../../com.aspose.slides/igroupshape).

**Retour:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### getAxes() {#getAxes--}
```
public final IAxesManager getAxes()
```


Geef toegang tot de assen van de chart. Alleen lezen [IAxesManager](../../com.aspose.slides/iaxesmanager).

**Retour:**
[IAxesManager](../../com.aspose.slides/iaxesmanager)
### getShowDataLabelsOverMaximum() {#getShowDataLabelsOverMaximum--}
```
public final boolean getShowDataLabelsOverMaximum()
```


Specificeert of datalabels boven het maximum van de chart moeten worden weergegeven. Lezen/schrijven boolean.

**Retour:**
boolean
### setShowDataLabelsOverMaximum(boolean value) {#setShowDataLabelsOverMaximum-boolean-}
```
public final void setShowDataLabelsOverMaximum(boolean value)
```


Specificeert of datalabels boven het maximum van de chart moeten worden weergegeven. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### hasRoundedCorners() {#hasRoundedCorners--}
```
public final boolean hasRoundedCorners()
```


Specificeert dat het chart-gebied afgeronde hoeken moet hebben. Lezen/schrijven boolean.

**Retour:**
boolean
### setRoundedCorners(boolean value) {#setRoundedCorners-boolean-}
```
public final void setRoundedCorners(boolean value)
```


Specificeert dat het chart-gebied afgeronde hoeken moet hebben. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getChart() {#getChart--}
```
public final IChart getChart()
```


Retourneert de chart. Alleen lezen [IChart](../../com.aspose.slides/ichart).

**Retour:**
[IChart](../../com.aspose.slides/ichart)