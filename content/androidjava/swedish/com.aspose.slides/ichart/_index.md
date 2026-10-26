---
title: IChart
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar ett grafiskt diagram på en bild.
type: docs
url: /sv/com.aspose.slides/ichart/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface IChart extends IGraphicalObject, IFormattedTextContainer, IOverrideThemeable
```

Representerar ett grafiskt diagram på en bild.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getPlotVisibleCellsOnly()](#getPlotVisibleCellsOnly--) | Determines whether the only visible cells are plotted. |
| [setPlotVisibleCellsOnly(boolean value)](#setPlotVisibleCellsOnly-boolean-) | Determines whether the only visible cells are plotted. |
| [getDisplayBlanksAs()](#getDisplayBlanksAs--) | Returns or sets the way to plot blank cells on a chart. |
| [setDisplayBlanksAs(int value)](#setDisplayBlanksAs-int-) | Returns or sets the way to plot blank cells on a chart. |
| [getChartData()](#getChartData--) | Returns information about the linked or embedded data associated with a chart. |
| [hasTitle()](#hasTitle--) | Determines whether a chart has a visible title. |
| [setTitle(boolean value)](#setTitle-boolean-) | Determines whether a chart has a visible title. |
| [getChartTitle()](#getChartTitle--) | Returns or sets a chart title Read-only [IChartTitle](../../com.aspose.slides/icharttitle). |
| [hasDataTable()](#hasDataTable--) | Determines whether a chart has a data table. |
| [setDataTable(boolean value)](#setDataTable-boolean-) | Determines whether a chart has a data table. |
| [hasLegend()](#hasLegend--) | Determines whether a chart has a legend. |
| [setLegend(boolean value)](#setLegend-boolean-) | Determines whether a chart has a legend. |
| [getLegend()](#getLegend--) | Returns or sets a legend for a chart. |
| [getChartDataTable()](#getChartDataTable--) | Returns a data table of a chart. |
| [getStyle()](#getStyle--) | Returns or sets the chart style. |
| [setStyle(int value)](#setStyle-int-) | Returns or sets the chart style. |
| [getType()](#getType--) | Returns or sets the chart type. |
| [setType(int value)](#setType-int-) | Returns or sets the chart type. |
| [getPlotArea()](#getPlotArea--) | Represents the plot area of a chart. |
| [getRotation3D()](#getRotation3D--) | Returns a 3D rotation of a chart. |
| [getBackWall()](#getBackWall--) | Returns an object which allows to change format of the back wall of a 3D chart. |
| [getSideWall()](#getSideWall--) | Returns an object which allows to change format of the side wall of a 3D chart. |
| [getFloor()](#getFloor--) | Returns an object which allows to change format of the floor of a 3D chart. |
| [getUserShapes()](#getUserShapes--) | Specify the shapes drawn on top of the chart. |
| [getAxes()](#getAxes--) | Provide access to chart axes. |
| [validateChartLayout()](#validateChartLayout--) | Calculates actual values of chart elements. |
| [getShowDataLabelsOverMaximum()](#getShowDataLabelsOverMaximum--) | Specifies data labels over the maximum of the chart shall be shown. |
| [setShowDataLabelsOverMaximum(boolean value)](#setShowDataLabelsOverMaximum-boolean-) | Specifies data labels over the maximum of the chart shall be shown. |
| [hasRoundedCorners()](#hasRoundedCorners--) | Specifies the chart area shall have rounded corners. |
| [setRoundedCorners(boolean value)](#setRoundedCorners-boolean-) | Specifies the chart area shall have rounded corners. |
### getPlotVisibleCellsOnly() {#getPlotVisibleCellsOnly--}
```
public abstract boolean getPlotVisibleCellsOnly()
```

Bestämmer om endast synliga celler plottas. Falskt för att plotta både synliga och dolda celler. Läs/skriv boolesk.

**Returnerar:**
boolean
### setPlotVisibleCellsOnly(boolean value) {#setPlotVisibleCellsOnly-boolean-}
```
public abstract void setPlotVisibleCellsOnly(boolean value)
```

Bestämmer om endast synliga celler plottas. Falskt för att plotta både synliga och dolda celler. Läs/skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getDisplayBlanksAs() {#getDisplayBlanksAs--}
```
public abstract int getDisplayBlanksAs()
```

Returnerar eller anger hur tomma celler ska plottas i ett diagram. Läs/skriv [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Returnerar:**
int
### setDisplayBlanksAs(int value) {#setDisplayBlanksAs-int-}
```
public abstract void setDisplayBlanksAs(int value)
```

Returnerar eller anger hur tomma celler ska plottas i ett diagram. Läs/skriv [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getChartData() {#getChartData--}
```
public abstract IChartData getChartData()
```

Returnerar information om den länkade eller inbäddade data som är associerad med ett diagram. Endast läsning [IChartData](../../com.aspose.slides/ichartdata).

**Returnerar:**
[IChartData](../../com.aspose.slides/ichartdata)
### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

Bestämmer om ett diagram har en synlig titel. Läs/skriv boolesk.

**Returnerar:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

Bestämmer om ett diagram har en synlig titel. Läs/skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getChartTitle() {#getChartTitle--}
```
public abstract IChartTitle getChartTitle()
```

Returnerar eller anger en diagramtitel. Endast läsning [IChartTitle](../../com.aspose.slides/icharttitle).

**Returnerar:**
[IChartTitle](../../com.aspose.slides/icharttitle)
### hasDataTable() {#hasDataTable--}
```
public abstract boolean hasDataTable()
```

Bestämmer om ett diagram har en datatabell. Läs/skriv boolesk.

**Returnerar:**
boolean
### setDataTable(boolean value) {#setDataTable-boolean-}
```
public abstract void setDataTable(boolean value)
```

Bestämmer om ett diagram har en datatabell. Läs/skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### hasLegend() {#hasLegend--}
```
public abstract boolean hasLegend()
```

Bestämmer om ett diagram har en legend. Läs/skriv boolesk.

**Returnerar:**
boolean
### setLegend(boolean value) {#setLegend-boolean-}
```
public abstract void setLegend(boolean value)
```

Bestämmer om ett diagram har en legend. Läs/skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getLegend() {#getLegend--}
```
public abstract ILegend getLegend()
```

Returnerar eller anger en legend för ett diagram. Endast läsning [ILegend](../../com.aspose.slides/ilegend).

**Returnerar:**
[ILegend](../../com.aspose.slides/ilegend)
### getChartDataTable() {#getChartDataTable--}
```
public abstract IDataTable getChartDataTable()
```

Returnerar en datatabell för ett diagram. Endast läsning [IDataTable](../../com.aspose.slides/idatatable).

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

Representerar plot-området för ett diagram. Endast läsning [IChartPlotArea](../../com.aspose.slides/ichartplotarea).

**Returnerar:**
[IChartPlotArea](../../com.aspose.slides/ichartplotarea)
### getRotation3D() {#getRotation3D--}
```
public abstract IRotation3D getRotation3D()
```

Returnerar en 3D-rotation av ett diagram. Endast läsning [IRotation3D](../../com.aspose.slides/irotation3d).

**Returnerar:**
[IRotation3D](../../com.aspose.slides/irotation3d)
### getBackWall() {#getBackWall--}
```
public abstract IChartWall getBackWall()
```

Returnerar ett objekt som möjliggör ändring av formatet för bakväggen i ett 3D-diagram. Endast läsning [IChartWall](../../com.aspose.slides/ichartwall).

**Returnerar:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getSideWall() {#getSideWall--}
```
public abstract IChartWall getSideWall()
```

Returnerar ett objekt som möjliggör ändring av formatet för sidoväggen i ett 3D-diagram. Endast läsning [IChartWall](../../com.aspose.slides/ichartwall).

**Returnerar:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getFloor() {#getFloor--}
```
public abstract IChartWall getFloor()
```

Returnerar ett objekt som möjliggör ändring av formatet för golvet i ett 3D-diagram. Endast läsning [IChartWall](../../com.aspose.slides/ichartwall).

**Returnerar:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getUserShapes() {#getUserShapes--}
```
public abstract IGroupShape getUserShapes()
```

Specificera formerna som ritas ovanpå diagrammet. Endast läsning [IGroupShape](../../com.aspose.slides/igroupshape).

**Returnerar:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### getAxes() {#getAxes--}
```
public abstract IAxesManager getAxes()
```

Tillhandahåller åtkomst till diagramaxlar. Endast läsning [IAxesManager](../../com.aspose.slides/iaxesmanager).

**Returnerar:**
[IAxesManager](../../com.aspose.slides/iaxesmanager)
### validateChartLayout() {#validateChartLayout--}
```
public abstract void validateChartLayout()
```

Beräknar faktiska värden för diagramelement. Faktiska värden inkluderar positionen för element som implementerar IActualLayout-gränssnittet (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) och faktiska axelvärden (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale)
### getShowDataLabelsOverMaximum() {#getShowDataLabelsOverMaximum--}
```
public abstract boolean getShowDataLabelsOverMaximum()
```

Anger att datalabels över diagrammets maximum ska visas. Läs/skriv boolesk.

**Returnerar:**
boolean
### setShowDataLabelsOverMaximum(boolean value) {#setShowDataLabelsOverMaximum-boolean-}
```
public abstract void setShowDataLabelsOverMaximum(boolean value)
```

Anger att datalabels över diagrammets maximum ska visas. Läs/skriv boolesk.

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