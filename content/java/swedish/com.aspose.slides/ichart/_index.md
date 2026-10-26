---
title: IChart
second_title: Aspose.Slides för Java API-referens
description: Representerar ett grafiskt diagram på en bild.
type: docs
url: /sv/com.aspose.slides/ichart/
---
**All Implemented Interfaces:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface IChart extends IGraphicalObject, IFormattedTextContainer, IOverrideThemeable
```

Representerar ett grafiskt diagram på en bild.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getPlotVisibleCellsOnly()](#getPlotVisibleCellsOnly--) | Avgör om endast synliga celler plottas. |
| [setPlotVisibleCellsOnly(boolean value)](#setPlotVisibleCellsOnly-boolean-) | Avgör om endast synliga celler plottas. |
| [getDisplayBlanksAs()](#getDisplayBlanksAs--) | Returnerar eller anger sättet att plotta tomma celler i ett diagram. |
| [setDisplayBlanksAs(int value)](#setDisplayBlanksAs-int-) | Returnerar eller anger sättet att plotta tomma celler i ett diagram. |
| [getChartData()](#getChartData--) | Returnerar information om den länkade eller inbäddade data som är kopplad till ett diagram. |
| [hasTitle()](#hasTitle--) | Avgör om ett diagram har en synlig titel. |
| [setTitle(boolean value)](#setTitle-boolean-) | Avgör om ett diagram har en synlig titel. |
| [getChartTitle()](#getChartTitle--) | Returnerar eller anger en diagramtitel Skrivskyddad [IChartTitle](../../com.aspose.slides/icharttitle). |
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
| [getPlotArea()](#getPlotArea--) | Representerar plotområdet för ett diagram. |
| [getRotation3D()](#getRotation3D--) | Returnerar en 3D-rotation av ett diagram. |
| [getBackWall()](#getBackWall--) | Returnerar ett objekt som möjliggör att ändra formatet för bakväggen i ett 3D-diagram. |
| [getSideWall()](#getSideWall--) | Returnerar ett objekt som möjliggör att ändra formatet för sidoväggen i ett 3D-diagram. |
| [getFloor()](#getFloor--) | Returnerar ett objekt som möjliggör att ändra formatet för golvet i ett 3D-diagram. |
| [getUserShapes()](#getUserShapes--) | Specificera formerna som ritas ovanpå diagrammet. |
| [getAxes()](#getAxes--) | Tillhandahåller åtkomst till diagramaxlar. |
| [validateChartLayout()](#validateChartLayout--) | Beräknar faktiska värden för diagrammets element. |
| [getShowDataLabelsOverMaximum()](#getShowDataLabelsOverMaximum--) | Anger att dataetiketter över diagrammets maximum ska visas. |
| [setShowDataLabelsOverMaximum(boolean value)](#setShowDataLabelsOverMaximum-boolean-) | Anger att dataetiketter över diagrammets maximum ska visas. |
| [hasRoundedCorners()](#hasRoundedCorners--) | Anger att diagramområdet ska ha rundade hörn. |
| [setRoundedCorners(boolean value)](#setRoundedCorners-boolean-) | Anger att diagramområdet ska ha rundade hörn. |

### getPlotVisibleCellsOnly() {#getPlotVisibleCellsOnly--}
```
public abstract boolean getPlotVisibleCellsOnly()
```

Avgör om endast synliga celler plottas. False to plot both visible and hidden cells. Läs/skriv boolesk.

**Returnerar:**
boolean

### setPlotVisibleCellsOnly(boolean value) {#setPlotVisibleCellsOnly-boolean-}
```
public abstract void setPlotVisibleCellsOnly(boolean value)
```

Avgör om endast synliga celler plottas. False to plot both visible and hidden cells. Läs/skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getDisplayBlanksAs() {#getDisplayBlanksAs--}
```
public abstract int getDisplayBlanksAs()
```

Returnerar eller anger sättet att plotta tomma celler i ett diagram. Läs/skriv [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Returnerar:**
int

### setDisplayBlanksAs(int value) {#setDisplayBlanksAs-int-}
```
public abstract void setDisplayBlanksAs(int value)
```

Returnerar eller anger sättet att plotta tomma celler i ett diagram. Läs/skriv [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getChartData() {#getChartData--}
```
public abstract IChartData getChartData()
```

Returnerar information om den länkade eller inbäddade data som är kopplad till ett diagram. Skrivskyddad [IChartData](../../com.aspose.slides/ichartdata).

**Returnerar:**
[IChartData](../../com.aspose.slides/ichartdata)

### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

Avgör om ett diagram har en synlig titel. Läs/skriv boolesk.

**Returnerar:**
boolean

### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

Avgör om ett diagram har en synlig titel. Läs/skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getChartTitle() {#getChartTitle--}
```
public abstract IChartTitle getChartTitle()
```

Returnerar eller anger en diagramtitel Skrivskyddad [IChartTitle](../../com.aspose.slides/icharttitle).

**Returnerar:**
[IChartTitle](../../com.aspose.slides/icharttitle)

### hasDataTable() {#hasDataTable--}
```
public abstract boolean hasDataTable()
```

Avgör om ett diagram har en datatabell. Läs/skriv boolesk.

**Returnerar:**
boolean

### setDataTable(boolean value) {#setDataTable-boolean-}
```
public abstract void setDataTable(boolean value)
```

Avgör om ett diagram har en datatabell. Läs/skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### hasLegend() {#hasLegend--}
```
public abstract boolean hasLegend()
```

Avgör om ett diagram har en förklaring. Läs/skriv boolesk.

**Returnerar:**
boolean

### setLegend(boolean value) {#setLegend-boolean-}
```
public abstract void setLegend(boolean value)
```

Avgör om ett diagram har en förklaring. Läs/skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getLegend() {#getLegend--}
```
public abstract ILegend getLegend()
```

Returnerar eller anger en förklaring för ett diagram. Skrivskyddad [ILegend](../../com.aspose.slides/ilegend).

**Returnerar:**
[ILegend](../../com.aspose.slides/ilegend)

### getChartDataTable() {#getChartDataTable--}
```
public abstract IDataTable getChartDataTable()
```

Returnerar en datatabell för ett diagram. Skrivskyddad [IDataTable](../../com.aspose.slides/idatatable).

**Returnerar:**
[IDataTable](../../com.aspose.slides/idatatable)

### getStyle() {#getStyle--}
```
public abstract int getStyle()
```

Returnerar eller anger diagramstilen. Läs/skriv [StyleType](../../com.aspose.slides/styletype).

**Returnerar:**
int

### setStyle(int value) {#setStyle-int-}
```
public abstract void setStyle(int value)
```

Returnerar eller anger diagramstilen. Läs/skriv [StyleType](../../com.aspose.slides/styletype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public abstract int getType()
```

Returnerar eller anger diagramtypen. Läs/skriv [ChartType](../../com.aspose.slides/charttype).

**Returnerar:**
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Returnerar eller anger diagramtypen. Läs/skriv [ChartType](../../com.aspose.slides/charttype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getPlotArea() {#getPlotArea--}
```
public abstract IChartPlotArea getPlotArea()
```

Representerar plotområdet för ett diagram. Skrivskyddad [IChartPlotArea](../../com.aspose.slides/ichartplotarea).

**Returnerar:**
[IChartPlotArea](../../com.aspose.slides/ichartplotarea)

### getRotation3D() {#getRotation3D--}
```
public abstract IRotation3D getRotation3D()
```

Returnerar en 3D-rotation av ett diagram. Skrivskyddad [IRotation3D](../../com.aspose.slides/irotation3d).

**Returnerar:**
[IRotation3D](../../com.aspose.slides/irotation3d)

### getBackWall() {#getBackWall--}
```
public abstract IChartWall getBackWall()
```

Returnerar ett objekt som möjliggör att ändra formatet för bakväggen i ett 3D-diagram. Skrivskyddad [IChartWall](../../com.aspose.slides/ichartwall).

**Returnerar:**
[IChartWall](../../com.aspose.slides/ichartwall)

### getSideWall() {#getSideWall--}
```
public abstract IChartWall getSideWall()
```

Returnerar ett objekt som möjliggör att ändra formatet för sidoväggen i ett 3D-diagram. Skrivskyddad [IChartWall](../../com.aspose.slides/ichartwall).

**Returnerar:**
[IChartWall](../../com.aspose.slides/ichartwall)

### getFloor() {#getFloor--}
```
public abstract IChartWall getFloor()
```

Returnerar ett objekt som möjliggör att ändra formatet för golvet i ett 3D-diagram. Skrivskyddad [IChartWall](../../com.aspose.slides/ichartwall).

**Returnerar:**
[IChartWall](../../com.aspose.slides/ichartwall)

### getUserShapes() {#getUserShapes--}
```
public abstract IGroupShape getUserShapes()
```

Specificera formerna som ritas ovanpå diagrammet. Skrivskyddad [IGroupShape](../../com.aspose.slides/igroupshape).

**Returnerar:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### getAxes() {#getAxes--}
```
public abstract IAxesManager getAxes()
```

Tillhandahåller åtkomst till diagramaxlar. Skrivskyddad [IAxesManager](../../com.aspose.slides/iaxesmanager).

**Returnerar:**
[IAxesManager](../../com.aspose.slides/iaxesmanager)

### validateChartLayout() {#validateChartLayout--}
```
public abstract void validateChartLayout()
```

Beräknar faktiska värden för diagrammets element. Faktiska värden inkluderar position av element som implementerar IActualLayout-gränssnittet (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) och faktiska axelvärden (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale)

### getShowDataLabelsOverMaximum() {#getShowDataLabelsOverMaximum--}
```
public abstract boolean getShowDataLabelsOverMaximum()
```

Anger att dataetiketter över diagrammets maximum ska visas. Läs/skriv boolesk.

**Returnerar:**
boolean

### setShowDataLabelsOverMaximum(boolean value) {#setShowDataLabelsOverMaximum-boolean-}
```
public abstract void setShowDataLabelsOverMaximum(boolean value)
```

Anger att dataetiketter över diagrammets maximum ska visas. Läs/skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### hasRoundedCorners() {#hasRoundedCorners--}
```
public abstract boolean hasRoundedCorners()
```

Anger att diagramområdet ska ha rundade hörn. Läs/skriv boolesk.

**Returnerar:**
boolean

### setRoundedCorners(boolean value) {#setRoundedCorners-boolean-}
```
public abstract void setRoundedCorners(boolean value)
```

Anger att diagramområdet ska ha rundade hörn. Läs/skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |