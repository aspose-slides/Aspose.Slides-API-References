---
title: Chart
second_title: Aspose.Slides für Java API Referenz
description: Stellt ein grafisches Diagramm auf einer Folie dar.
type: docs
url: /de/com.aspose.slides/chart/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IChart](../../com.aspose.slides/ichart)
```
public class Chart extends GraphicalObject implements IChart
```

Stellt ein grafisches Diagramm auf einer Folie dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [validateChartLayout()](#validateChartLayout--) | Berechnet die tatsächlichen Werte von Diagrammelementen. |
| [getPlotVisibleCellsOnly()](#getPlotVisibleCellsOnly--) | Bestimmt, ob nur die sichtbaren Zellen geplottet werden. |
| [setPlotVisibleCellsOnly(boolean value)](#setPlotVisibleCellsOnly-boolean-) | Bestimmt, ob nur die sichtbaren Zellen geplottet werden. |
| [getDisplayBlanksAs()](#getDisplayBlanksAs--) | Gibt die Art zurück oder legt sie fest, wie leere Zellen in einem Diagramm geplottet werden. |
| [setDisplayBlanksAs(int value)](#setDisplayBlanksAs-int-) | Gibt die Art zurück oder legt sie fest, wie leere Zellen in einem Diagramm geplottet werden. |
| [getChartData()](#getChartData--) | Gibt Informationen über die verknüpften oder eingebetteten Daten zurück, die mit einem Diagramm verbunden sind. |
| [hasTitle()](#hasTitle--) | Bestimmt, ob ein Diagramm einen sichtbaren Titel hat. |
| [setTitle(boolean value)](#setTitle-boolean-) | Bestimmt, ob ein Diagramm einen sichtbaren Titel hat. |
| [getChartTitle()](#getChartTitle--) | Gibt einen Diagrammtitel zurück oder legt ihn fest. |
| [hasDataTable()](#hasDataTable--) | Bestimmt, ob ein Diagramm eine Datentabelle hat. |
| [setDataTable(boolean value)](#setDataTable-boolean-) | Bestimmt, ob ein Diagramm eine Datentabelle hat. |
| [hasLegend()](#hasLegend--) | Bestimmt, ob ein Diagramm eine Legende hat. |
| [setLegend(boolean value)](#setLegend-boolean-) | Bestimmt, ob ein Diagramm eine Legende hat. |
| [getLegend()](#getLegend--) | Gibt eine Legende für ein Diagramm zurück oder legt sie fest. |
| [getChartDataTable()](#getChartDataTable--) | Gibt eine Datentabelle eines Diagramms zurück. |
| [getStyle()](#getStyle--) | Gibt den Diagrammstil zurück oder legt ihn fest. |
| [setStyle(int value)](#setStyle-int-) | Gibt den Diagrammstil zurück oder legt ihn fest. |
| [getType()](#getType--) | Gibt den Diagrammtyp zurück oder legt ihn fest. |
| [setType(int value)](#setType-int-) | Gibt den Diagrammtyp zurück oder legt ihn fest. |
| [getPlotArea()](#getPlotArea--) | Stellt den Plotbereich eines Diagramms dar. |
| [getRotation3D()](#getRotation3D--) | Gibt eine 3D-Drehung eines Diagramms zurück. |
| [getBackWall()](#getBackWall--) | Gibt ein Objekt zurück, das das Format der Rückwand eines 3D-Diagramms ändern lässt. |
| [getSideWall()](#getSideWall--) | Gibt ein Objekt zurück, das das Format der Seitenwand eines 3D-Diagramms ändern lässt. |
| [getFloor()](#getFloor--) | Gibt ein Objekt zurück, das das Format des Bodens eines 3D-Diagramms ändern lässt. |
| [getTextFormat()](#getTextFormat--) | Gibt das Textformat des Diagramms zurück. |
| [createThemeEffective()](#createThemeEffective--) | Gibt ein effektives Theme für dieses Diagramm zurück. |
| [getThemeManager()](#getThemeManager--) | Gibt den Theme-Manager zurück. |
| [getUserShapes()](#getUserShapes--) | Gibt die Formen an, die über dem Diagramm gezeichnet werden. |
| [getAxes()](#getAxes--) | Stellt Zugriff auf Diagrammachsen bereit. |
| [getShowDataLabelsOverMaximum()](#getShowDataLabelsOverMaximum--) | Gibt an, dass Datenbeschriftungen über dem Maximum des Diagramms angezeigt werden sollen. |
| [setShowDataLabelsOverMaximum(boolean value)](#setShowDataLabelsOverMaximum-boolean-) | Gibt an, dass Datenbeschriftungen über dem Maximum des Diagramms angezeigt werden sollen. |
| [hasRoundedCorners()](#hasRoundedCorners--) | Gibt an, dass der Diagrammbereich abgerundete Ecken haben soll. |
| [setRoundedCorners(boolean value)](#setRoundedCorners-boolean-) | Gibt an, dass der Diagrammbereich abgerundete Ecken haben soll. |
| [getChart()](#getChart--) |  |
### validateChartLayout() {#validateChartLayout--}
```
public final void validateChartLayout()
```


Berechnet die tatsächlichen Werte von Diagrammelementen. Die tatsächlichen Werte umfassen die Position von Elementen, die das IActualLayout-Interface implementieren (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) und die tatsächlichen Achsenwerte (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale)

### getPlotVisibleCellsOnly() {#getPlotVisibleCellsOnly--}
```
public final boolean getPlotVisibleCellsOnly()
```


Bestimmt, ob nur die sichtbaren Zellen geplottet werden. False, um sowohl sichtbare als auch versteckte Zellen zu plotten. Lesen/Schreiben boolesch.

**Rückgabe:**
boolean
### setPlotVisibleCellsOnly(boolean value) {#setPlotVisibleCellsOnly-boolean-}
```
public final void setPlotVisibleCellsOnly(boolean value)
```


Bestimmt, ob nur die sichtbaren Zellen geplottet werden. False, um sowohl sichtbare als auch versteckte Zellen zu plotten. Lesen/Schreiben boolesch.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getDisplayBlanksAs() {#getDisplayBlanksAs--}
```
public final int getDisplayBlanksAs()
```


Gibt die Art zurück oder legt sie fest, wie leere Zellen in einem Diagramm geplottet werden. Lesen/Schreiben [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Rückgabe:**
int
### setDisplayBlanksAs(int value) {#setDisplayBlanksAs-int-}
```
public final void setDisplayBlanksAs(int value)
```


Gibt die Art zurück oder legt sie fest, wie leere Zellen in einem Diagramm geplottet werden. Lesen/Schreiben [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getChartData() {#getChartData--}
```
public final IChartData getChartData()
```


Gibt Informationen über die verknüpften oder eingebetteten Daten zurück, die mit einem Diagramm verbunden sind. Nur lesen [IChartData](../../com.aspose.slides/ichartdata).

**Rückgabe:**
[IChartData](../../com.aspose.slides/ichartdata)
### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```


Bestimmt, ob ein Diagramm einen sichtbaren Titel hat. Lesen/Schreiben boolesch.

**Rückgabe:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```


Bestimmt, ob ein Diagramm einen sichtbaren Titel hat. Lesen/Schreiben boolesch.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getChartTitle() {#getChartTitle--}
```
public final IChartTitle getChartTitle()
```


Gibt einen Diagrammtitel zurück oder legt ihn fest. Nur lesen [IChartTitle](../../com.aspose.slides/icharttitle).

**Rückgabe:**
[IChartTitle](../../com.aspose.slides/icharttitle)
### hasDataTable() {#hasDataTable--}
```
public final boolean hasDataTable()
```


Bestimmt, ob ein Diagramm eine Datentabelle hat. Lesen/Schreiben boolesch.

**Rückgabe:**
boolean
### setDataTable(boolean value) {#setDataTable-boolean-}
```
public final void setDataTable(boolean value)
```


Bestimmt, ob ein Diagramm eine Datentabelle hat. Lesen/Schreiben boolesch.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### hasLegend() {#hasLegend--}
```
public final boolean hasLegend()
```


Bestimmt, ob ein Diagramm eine Legende hat. Lesen/Schreiben boolesch.

**Rückgabe:**
boolean
### setLegend(boolean value) {#setLegend-boolean-}
```
public final void setLegend(boolean value)
```


Bestimmt, ob ein Diagramm eine Legende hat. Lesen/Schreiben boolesch.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getLegend() {#getLegend--}
```
public final ILegend getLegend()
```


Gibt eine Legende für ein Diagramm zurück oder legt sie fest. Nur lesen [ILegend](../../com.aspose.slides/ilegend).

**Rückgabe:**
[ILegend](../../com.aspose.slides/ilegend)
### getChartDataTable() {#getChartDataTable--}
```
public final IDataTable getChartDataTable()
```


Gibt eine Datentabelle eines Diagramms zurück. Nur lesen [IDataTable](../../com.aspose.slides/idatatable).

**Rückgabe:**
[IDataTable](../../com.aspose.slides/idatatable)
### getStyle() {#getStyle--}
```
public final int getStyle()
```


Gibt den Diagrammstil zurück oder legt ihn fest. Lesen/Schreiben [StyleType](../../com.aspose.slides/styletype).

**Rückgabe:**
int
### setStyle(int value) {#setStyle-int-}
```
public final void setStyle(int value)
```


Gibt den Diagrammstil zurück oder legt ihn fest. Lesen/Schreiben [StyleType](../../com.aspose.slides/styletype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public final int getType()
```


Gibt den Diagrammtyp zurück oder legt ihn fest. Lesen/Schreiben [ChartType](../../com.aspose.slides/charttype).

**Rückgabe:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


Gibt den Diagrammtyp zurück oder legt ihn fest. Lesen/Schreiben [ChartType](../../com.aspose.slides/charttype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getPlotArea() {#getPlotArea--}
```
public final IChartPlotArea getPlotArea()
```


Stellt den Plotbereich eines Diagramms dar. Nur lesen [IChartPlotArea](../../com.aspose.slides/ichartplotarea).

**Rückgabe:**
[IChartPlotArea](../../com.aspose.slides/ichartplotarea)
### getRotation3D() {#getRotation3D--}
```
public final IRotation3D getRotation3D()
```


Gibt eine 3D-Drehung eines Diagramms zurück. Nur lesen [IRotation3D](../../com.aspose.slides/irotation3d).

**Rückgabe:**
[IRotation3D](../../com.aspose.slides/irotation3d)
### getBackWall() {#getBackWall--}
```
public final IChartWall getBackWall()
```


Gibt ein Objekt zurück, das das Format der Rückwand eines 3D-Diagramms ändern lässt. Nur lesen [IChartWall](../../com.aspose.slides/ichartwall).

**Rückgabe:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getSideWall() {#getSideWall--}
```
public final IChartWall getSideWall()
```


Gibt ein Objekt zurück, das das Format der Seitenwand eines 3D-Diagramms ändern lässt. Nur lesen [IChartWall](../../com.aspose.slides/ichartwall).

**Rückgabe:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getFloor() {#getFloor--}
```
public final IChartWall getFloor()
```


Gibt ein Objekt zurück, das das Format des Bodens eines 3D-Diagramms ändern lässt. Nur lesen [IChartWall](../../com.aspose.slides/ichartwall).

**Rückgabe:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```


Gibt das Textformat des Diagramms zurück. Die Eigenschaft ist für die folgenden Typen nicht anwendbar: [ChartType.Treemap](../../com.aspose.slides/charttype\#Treemap), [ChartType.Sunburst](../../com.aspose.slides/charttype\#Sunburst), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel),[ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker). Nur lesen [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Rückgabe:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```


Gibt ein effektives Theme für dieses Diagramm zurück.

**Rückgabe:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```


Gibt den Theme-Manager zurück. Nur lesen [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Rückgabe:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getUserShapes() {#getUserShapes--}
```
public final IGroupShape getUserShapes()
```


Gibt die Formen an, die über dem Diagramm gezeichnet werden. Nur lesen [IGroupShape](../../com.aspose.slides/igroupshape).

**Rückgabe:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### getAxes() {#getAxes--}
```
public final IAxesManager getAxes()
```


Stellt Zugriff auf Diagrammachsen bereit. Nur lesen [IAxesManager](../../com.aspose.slides/iaxesmanager).

**Rückgabe:**
[IAxesManager](../../com.aspose.slides/iaxesmanager)
### getShowDataLabelsOverMaximum() {#getShowDataLabelsOverMaximum--}
```
public final boolean getShowDataLabelsOverMaximum()
```


Gibt an, dass Datenbeschriftungen über dem Maximum des Diagramms angezeigt werden sollen. Lesen/Schreiben boolesch.

**Rückgabe:**
boolean
### setShowDataLabelsOverMaximum(boolean value) {#setShowDataLabelsOverMaximum-boolean-}
```
public final void setShowDataLabelsOverMaximum(boolean value)
```


Gibt an, dass Datenbeschriftungen über dem Maximum des Diagramms angezeigt werden sollen. Lesen/Schreiben boolesch.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### hasRoundedCorners() {#hasRoundedCorners--}
```
public final boolean hasRoundedCorners()
```


Gibt an, dass der Diagrammbereich abgerundete Ecken haben soll. Lesen/Schreiben boolesch.

**Rückgabe:**
boolean
### setRoundedCorners(boolean value) {#setRoundedCorners-boolean-}
```
public final void setRoundedCorners(boolean value)
```


Gibt an, dass der Diagrammbereich abgerundete Ecken haben soll. Lesen/Schreiben boolesch.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getChart() {#getChart--}
```
public final IChart getChart()
```


Gibt das Diagramm zurück. Nur lesen [IChart](../../com.aspose.slides/ichart).

**Rückgabe:**
[IChart](../../com.aspose.slides/ichart)