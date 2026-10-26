---
title: Chart
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar ett grafiskt diagram på en bild.
type: docs
url: /sv/com.aspose.slides/chart/
---
**Arv:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IChart](../../com.aspose.slides/ichart)
```
public class Chart extends GraphicalObject implements IChart
```

Representerar ett grafiskt diagram på en bild.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [validateChartLayout()](#validateChartLayout--) | Beräknar faktiska värden för diagrammets element. |
| [getPlotVisibleCellsOnly()](#getPlotVisibleCellsOnly--) | Avgör om endast synliga celler plottas. |
| [setPlotVisibleCellsOnly(boolean value)](#setPlotVisibleCellsOnly-boolean-) | Avgör om endast synliga celler plottas. |
| [getDisplayBlanksAs()](#getDisplayBlanksAs--) | Returnerar eller anger hur tomma celler plottas i ett diagram. |
| [setDisplayBlanksAs(int value)](#setDisplayBlanksAs-int-) | Returnerar eller anger hur tomma celler plottas i ett diagram. |
| [getChartData()](#getChartData--) | Returnerar information om de länkade eller inbäddade data som är associerade med ett diagram. |
| [hasTitle()](#hasTitle--) | Avgör om ett diagram har en synlig titel. |
| [setTitle(boolean value)](#setTitle-boolean-) | Avgör om ett diagram har en synlig titel. |
| [getChartTitle()](#getChartTitle--) | Returnerar eller anger en diagramtitel. |
| [hasDataTable()](#hasDataTable--) | Avgör om ett diagram har en datatabell. |
| [setDataTable(boolean value)](#setDataTable-boolean-) | Avgör om ett diagram har en datatabell. |
| [hasLegend()](#hasLegend--) | Avgör om ett diagram har en förklaring. |
| [setLegend(boolean value)](#setLegend-boolean-) | Avgör om ett diagram har en förklaring. |
| [getLegend()](#getLegend--) | Returnerar eller anger en förklaring för ett diagram. |
| [getChartDataTable()](#getChartDataTable--) | Returnerar en datatabell för ett diagram. |
| [getStyle()](#getStyle--) | Returnerar eller anger diagramstilen. |
| [setStyle(int value)](#setStyle-int-) | Returnerar eller anger diagramstilen. |
| [getType()](#getType--) | Returnerar eller anger diagramtypen. |
| [setType(int value)](#setType-int-) | Returnerar eller anger diagramtypen. |
| [getPlotArea()](#getPlotArea--) | Representerar diagrammets plotområde. |
| [getRotation3D()](#getRotation3D--) | Returnerar en 3D-rotation av ett diagram. |
| [getBackWall()](#getBackWall--) | Returnerar ett objekt som möjliggör att ändra formatet på bakväggen i ett 3D-diagram. |
| [getSideWall()](#getSideWall--) | Returnerar ett objekt som möjliggör att ändra formatet på sidoväggen i ett 3D-diagram. |
| [getFloor()](#getFloor--) | Returnerar ett objekt som möjliggör att ändra formatet på golvet i ett 3D-diagram. |
| [getTextFormat()](#getTextFormat--) | Returnerar diagrammets textformat. |
| [createThemeEffective()](#createThemeEffective--) | Returnerar ett effektivt tema för detta diagram. |
| [getThemeManager()](#getThemeManager--) | Returnerar temahanterare. |
| [getUserShapes()](#getUserShapes--) | Ange formerna som ritas ovanpå diagrammet. |
| [getAxes()](#getAxes--) | Tillhandahåller åtkomst till diagramaxlar. |
| [getShowDataLabelsOverMaximum()](#getShowDataLabelsOverMaximum--) | Anger att datalabels över diagrammets maximum ska visas. |
| [setShowDataLabelsOverMaximum(boolean value)](#setShowDataLabelsOverMaximum-boolean-) | Anger att datalabels över diagrammets maximum ska visas. |
| [hasRoundedCorners()](#hasRoundedCorners--) | Anger att diagramområdet ska ha avrundade hörn. |
| [setRoundedCorners(boolean value)](#setRoundedCorners-boolean-) | Anger att diagramområdet ska ha avrundade hörn. |
| [getChart()](#getChart--) |  |

### validateChartLayout() {#validateChartLayout--}
```
public final void validateChartLayout()
```

Beräknar faktiska värden för diagrammets element. De faktiska värdena inkluderar positionen för element som implementerar IActualLayout-gränssnittet (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) och faktiska axelvärden (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale).

### getPlotVisibleCellsOnly() {#getPlotVisibleCellsOnly--}
```
public final boolean getPlotVisibleCellsOnly()
```

Avgör om endast synliga celler plottas. False för att plotta både synliga och dolda celler. Läs/skriv boolesk.

**Returnerar:**
boolean
### setPlotVisibleCellsOnly(boolean value) {#setPlotVisibleCellsOnly-boolean-}
```
public final void setPlotVisibleCellsOnly(boolean value)
```

Avgör om endast synliga celler plottas. False för att plotta både synliga och dolda celler. Läs/skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getDisplayBlanksAs() {#getDisplayBlanksAs--}
```
public final int getDisplayBlanksAs()
```

Returnerar eller anger hur tomma celler plottas i ett diagram. Läs/skriv [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Returnerar:**
int
### setDisplayBlanksAs(int value) {#setDisplayBlanksAs-int-}
```
public final void setDisplayBlanksAs(int value)
```

Returnerar eller anger hur tomma celler plottas i ett diagram. Läs/skriv [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getChartData() {#getChartData--}
```
public final IChartData getChartData()
```

Returnerar information om de länkade eller inbäddade data som är associerade med ett diagram. Endast läs [IChartData](../../com.aspose.slides/ichartdata).

**Returnerar:**
[IChartData](../../com.aspose.slides/ichartdata)
### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```

Avgör om ett diagram har en synlig titel. Läs/skriv boolesk.

**Returnerar:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```

Avgör om ett diagram har en synlig titel. Läs/skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getChartTitle() {#getChartTitle--}
```
public final IChartTitle getChartTitle()
```

Returnerar eller anger en diagramtitel. Endast läs [IChartTitle](../../com.aspose.slides/icharttitle).

**Returnerar:**
[IChartTitle](../../com.aspose.slides/icharttitle)
### hasDataTable() {#hasDataTable--}
```
public final boolean hasDataTable()
```

Avgör om ett diagram har en datatabell. Läs/skriv boolesk.

**Returnerar:**
boolean
### setDataTable(boolean value) {#setDataTable-boolean-}
```
public final void setDataTable(boolean value)
```

Avgör om ett diagram har en datatabell. Läs/skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### hasLegend() {#hasLegend--}
```
public final boolean hasLegend()
```

Avgör om ett diagram har en förklaring. Läs/skriv boolesk.

**Returnerar:**
boolean
### setLegend(boolean value) {#setLegend-boolean-}
```
public final void setLegend(boolean value)
```

Avgör om ett diagram har en förklaring. Läs/skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getLegend() {#getLegend--}
```
public final ILegend getLegend()
```

Returnerar eller anger en förklaring för ett diagram. Endast läs [ILegend](../../com.aspose.slides/ilegend).

**Returnerar:**
[ILegend](../../com.aspose.slides/ilegend)
### getChartDataTable() {#getChartDataTable--}
```
public final IDataTable getChartDataTable()
```

Returnerar en datatabell för ett diagram. Endast läs [IDataTable](../../com.aspose.slides/idatatable).

**Returnerar:**
[IDataTable](../../com.aspose.slides/idatatable)
### getStyle() {#getStyle--}
```
public final int getStyle()
```

Returnerar eller anger diagramstilen. Läs/skriv [StyleType](../../com.aspose.slides/styletype).

**Returnerar:**
int
### setStyle(int value) {#setStyle-int-}
```
public final void setStyle(int value)
```

Returnerar eller anger diagramstilen. Läs/skriv [StyleType](../../com.aspose.slides/styletype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public final int getType()
```

Returnerar eller anger diagramtypen. Läs/skriv [ChartType](../../com.aspose.slides/charttype).

**Returnerar:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Returnerar eller anger diagramtypen. Läs/skriv [ChartType](../../com.aspose.slides/charttype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getPlotArea() {#getPlotArea--}
```
public final IChartPlotArea getPlotArea()
```

Representerar diagrammets plotområde. Endast läs [IChartPlotArea](../../com.aspose.slides/ichartplotarea).

**Returnerar:**
[IChartPlotArea](../../com.aspose.slides/ichartplotarea)
### getRotation3D() {#getRotation3D--}
```
public final IRotation3D getRotation3D()
```

Returnerar en 3D-rotation av ett diagram. Endast läs [IRotation3D](../../com.aspose.slides/irotation3d).

**Returnerar:**
[IRotation3D](../../com.aspose.slides/irotation3d)
### getBackWall() {#getBackWall--}
```
public final IChartWall getBackWall()
```

Returnerar ett objekt som möjliggör att ändra formatet på bakväggen i ett 3D-diagram. Endast läs [IChartWall](../../com.aspose.slides/ichartwall).

**Returnerar:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getSideWall() {#getSideWall--}
```
public final IChartWall getSideWall()
```

Returnerar ett objekt som möjliggör att ändra formatet på sidoväggen i ett 3D-diagram. Endast läs [IChartWall](../../com.aspose.slides/ichartwall).

**Returnerar:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getFloor() {#getFloor--}
```
public final IChartWall getFloor()
```

Returnerar ett objekt som möjliggör att ändra formatet på golvet i ett 3D-diagram. Endast läs [IChartWall](../../com.aspose.slides/ichartwall).

**Returnerar:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Returnerar diagrammets textformat. Egenskapen är inte tillämplig för följande typer: [ChartType.Treemap](../../com.aspose.slides/charttype\#Treemap), [ChartType.Sunburst](../../com.aspose.slides/charttype\#Sunburst), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel),[ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker). Endast läs [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Returnerar:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

Returnerar ett effektivt tema för detta diagram.

**Returnerar:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

Returnerar temahanterare. Endast läs [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Returnerar:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getUserShapes() {#getUserShapes--}
```
public final IGroupShape getUserShapes()
```

Ange formerna som ritas ovanpå diagrammet. Endast läs [IGroupShape](../../com.aspose.slides/igroupshape).

**Returnerar:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### getAxes() {#getAxes--}
```
public final IAxesManager getAxes()
```

Tillhandahåller åtkomst till diagramaxlar. Endast läs [IAxesManager](../../com.aspose.slides/iaxesmanager).

**Returnerar:**
[IAxesManager](../../com.aspose.slides/iaxesmanager)
### getShowDataLabelsOverMaximum() {#getShowDataLabelsOverMaximum--}
```
public final boolean getShowDataLabelsOverMaximum()
```

Anger att datalabels över diagrammets maximum ska visas. Läs/skriv boolesk.

**Returnerar:**
boolean
### setShowDataLabelsOverMaximum(boolean value) {#setShowDataLabelsOverMaximum-boolean-}
```
public final void setShowDataLabelsOverMaximum(boolean value)
```

Anger att datalabels över diagrammets maximum ska visas. Läs/skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### hasRoundedCorners() {#hasRoundedCorners--}
```
public final boolean hasRoundedCorners()
```

Anger att diagramområdet ska ha avrundade hörn. Läs/skriv boolesk.

**Returnerar:**
boolean
### setRoundedCorners(boolean value) {#setRoundedCorners-boolean-}
```
public final void setRoundedCorners(boolean value)
```

Anger att diagramområdet ska ha avrundade hörn. Läs/skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getChart() {#getChart--}
```
public final IChart getChart()
```

Returnerar diagrammet. Endast läs [IChart](../../com.aspose.slides/ichart).

**Returnerar:**
[IChart](../../com.aspose.slides/ichart)