---
title: Chart
second_title: Aspose.Slides für Android über Java API-Referenz
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
| [validateChartLayout()](#validateChartLayout--) | Berechnet die tatsächlichen Werte der Diagrammelemente. |
| [getPlotVisibleCellsOnly()](#getPlotVisibleCellsOnly--) | Bestimmt, ob nur sichtbare Zellen geplottet werden. |
| [setPlotVisibleCellsOnly(boolean value)](#setPlotVisibleCellsOnly-boolean-) | Bestimmt, ob nur sichtbare Zellen geplottet werden. |
| [getDisplayBlanksAs()](#getDisplayBlanksAs--) | Gibt zurück oder setzt die Art, leere Zellen in einem Diagramm zu plotten. |
| [setDisplayBlanksAs(int value)](#setDisplayBlanksAs-int-) | Gibt zurück oder setzt die Art, leere Zellen in einem Diagramm zu plotten. |
| [getChartData()](#getChartData--) | Gibt Informationen über die verknüpften oder eingebetteten Daten, die einem Diagramm zugeordnet sind, zurück. |
| [hasTitle()](#hasTitle--) | Bestimmt, ob ein Diagramm einen sichtbaren Titel hat. |
| [setTitle(boolean value)](#setTitle-boolean-) | Bestimmt, ob ein Diagramm einen sichtbaren Titel hat. |
| [getChartTitle()](#getChartTitle--) | Gibt den Diagrammtitel zurück oder setzt ihn. |
| [hasDataTable()](#hasDataTable--) | Bestimmt, ob ein Diagramm eine Datentabelle hat. |
| [setDataTable(boolean value)](#setDataTable-boolean-) | Bestimmt, ob ein Diagramm eine Datentabelle hat. |
| [hasLegend()](#hasLegend--) | Bestimmt, ob ein Diagramm eine Legende hat. |
| [setLegend(boolean value)](#setLegend-boolean-) | Bestimmt, ob ein Diagramm eine Legende hat. |
| [getLegend()](#getLegend--) | Gibt eine Legende für ein Diagramm zurück oder setzt sie. |
| [getChartDataTable()](#getChartDataTable--) | Gibt eine Datentabelle eines Diagramms zurück. |
| [getStyle()](#getStyle--) | Gibt den Diagrammstil zurück oder setzt ihn. |
| [setStyle(int value)](#setStyle-int-) | Gibt den Diagrammstil zurück oder setzt ihn. |
| [getType()](#getType--) | Gibt den Diagrammtyp zurück oder setzt ihn. |
| [setType(int value)](#setType-int-) | Gibt den Diagrammtyp zurück oder setzt ihn. |
| [getPlotArea()](#getPlotArea--) | Stellt den Plotbereich eines Diagramms dar. |
| [getRotation3D()](#getRotation3D--) | Gibt eine 3D-Rotation eines Diagramms zurück. |
| [getBackWall()](#getBackWall--) | Gibt ein Objekt zurück, das das Ändern des Formats der hinteren Wand eines 3D-Diagramms ermöglicht. |
| [getSideWall()](#getSideWall--) | Gibt ein Objekt zurück, das das Ändern des Formats der Seitenwand eines 3D-Diagramms ermöglicht. |
| [getFloor()](#getFloor--) | Gibt ein Objekt zurück, das das Ändern des Formats des Bodens eines 3D-Diagramms ermöglicht. |
| [getTextFormat()](#getTextFormat--) | Gibt das Textformat des Diagramms zurück. |
| [createThemeEffective()](#createThemeEffective--) | Gibt ein wirksames Thema für dieses Diagramm zurück. |
| [getThemeManager()](#getThemeManager--) | Gibt den Themen-Manager zurück. |
| [getUserShapes()](#getUserShapes--) | Gibt die Formen an, die über dem Diagramm gezeichnet werden. |
| [getAxes()](#getAxes--) | Stellt Zugriff auf die Diagrammachsen bereit. |
| [getShowDataLabelsOverMaximum()](#getShowDataLabelsOverMaximum--) | Gibt an, dass Datenbeschriftungen über dem Maximum des Diagramms angezeigt werden sollen. |
| [setShowDataLabelsOverMaximum(boolean value)](#setShowDataLabelsOverMaximum-boolean-) | Gibt an, dass Datenbeschriftungen über dem Maximum des Diagramms angezeigt werden sollen. |
| [hasRoundedCorners()](#hasRoundedCorners--) | Gibt an, dass der Diagrammbereich abgerundete Ecken haben soll. |
| [setRoundedCorners(boolean value)](#setRoundedCorners-boolean-) | Gibt an, dass der Diagrammbereich abgerundete Ecken haben soll. |
| [getChart()](#getChart--) |  |

### validateChartLayout() {#validateChartLayout--}
```
public final void validateChartLayout()
```

Berechnet die tatsächlichen Werte der Diagrammelemente. Die tatsächlichen Werte umfassen die Position von Elementen, die das IActualLayout-Interface implementieren (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) und die tatsächlichen Achsenwerte (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale)

### getPlotVisibleCellsOnly() {#getPlotVisibleCellsOnly--}
```
public final boolean getPlotVisibleCellsOnly()
```

Bestimmt, ob nur sichtbare Zellen geplottet werden. False, um sowohl sichtbare als auch ausgeblendete Zellen zu plotten. Lesen/Schreiben boolean.

**Gibt zurück:**
boolean
### setPlotVisibleCellsOnly(boolean value) {#setPlotVisibleCellsOnly-boolean-}
```
public final void setPlotVisibleCellsOnly(boolean value)
```

Bestimmt, ob nur sichtbare Zellen geplottet werden. False, um sowohl sichtbare als auch ausgeblendete Zellen zu plotten. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getDisplayBlanksAs() {#getDisplayBlanksAs--}
```
public final int getDisplayBlanksAs()
```

Gibt zurück oder setzt die Art, leere Zellen in einem Diagramm zu plotten. Lesen/Schreiben [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Gibt zurück:**
int
### setDisplayBlanksAs(int value) {#setDisplayBlanksAs-int-}
```
public final void setDisplayBlanksAs(int value)
```

Gibt zurück oder setzt die Art, leere Zellen in einem Diagramm zu plotten. Lesen/Schreiben [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getChartData() {#getChartData--}
```
public final IChartData getChartData()
```

Gibt Informationen über die verknüpften oder eingebetteten Daten, die einem Diagramm zugeordnet sind, zurück. Nur Lesen [IChartData](../../com.aspose.slides/ichartdata).

**Gibt zurück:**
[IChartData](../../com.aspose.slides/ichartdata)
### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```

Bestimmt, ob ein Diagramm einen sichtbaren Titel hat. Lesen/Schreiben boolean.

**Gibt zurück:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```

Bestimmt, ob ein Diagramm einen sichtbaren Titel hat. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getChartTitle() {#getChartTitle--}
```
public final IChartTitle getChartTitle()
```

Gibt den Diagrammtitel zurück oder setzt ihn. Nur Lesen [IChartTitle](../../com.aspose.slides/icharttitle).

**Gibt zurück:**
[IChartTitle](../../com.aspose.slides/icharttitle)
### hasDataTable() {#hasDataTable--}
```
public final boolean hasDataTable()
```

Bestimmt, ob ein Diagramm eine Datentabelle hat. Lesen/Schreiben boolean.

**Gibt zurück:**
boolean
### setDataTable(boolean value) {#setDataTable-boolean-}
```
public final void setDataTable(boolean value)
```

Bestimmt, ob ein Diagramm eine Datentabelle hat. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### hasLegend() {#hasLegend--}
```
public final boolean hasLegend()
```

Bestimmt, ob ein Diagramm eine Legende hat. Lesen/Schreiben boolean.

**Gibt zurück:**
boolean
### setLegend(boolean value) {#setLegend-boolean-}
```
public final void setLegend(boolean value)
```

Bestimmt, ob ein Diagramm eine Legende hat. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getLegend() {#getLegend--}
```
public final ILegend getLegend()
```

Gibt eine Legende für ein Diagramm zurück oder setzt sie. Nur Lesen [ILegend](../../com.aspose.slides/ilegend).

**Gibt zurück:**
[ILegend](../../com.aspose.slides/ilegend)
### getChartDataTable() {#getChartDataTable--}
```
public final IDataTable getChartDataTable()
```

Gibt eine Datentabelle eines Diagramms zurück. Nur Lesen [IDataTable](../../com.aspose.slides/idatatable).

**Gibt zurück:**
[IDataTable](../../com.aspose.slides/idatatable)
### getStyle() {#getStyle--}
```
public final int getStyle()
```

Gibt den Diagrammstil zurück oder setzt ihn. Lesen/Schreiben [StyleType](../../com.aspose.slides/styletype).

**Gibt zurück:**
int
### setStyle(int value) {#setStyle-int-}
```
public final void setStyle(int value)
```

Gibt den Diagrammstil zurück oder setzt ihn. Lesen/Schreiben [StyleType](../../com.aspose.slides/styletype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public final int getType()
```

Gibt den Diagrammtyp zurück oder setzt ihn. Lesen/Schreiben [ChartType](../../com.aspose.slides/charttype).

**Gibt zurück:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Gibt den Diagrammtyp zurück oder setzt ihn. Lesen/Schreiben [ChartType](../../com.aspose.slides/charttype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getPlotArea() {#getPlotArea--}
```
public final IChartPlotArea getPlotArea()
```

Stellt den Plotbereich eines Diagramms dar. Nur Lesen [IChartPlotArea](../../com.aspose.slides/ichartplotarea).

**Gibt zurück:**
[IChartPlotArea](../../com.aspose.slides/ichartplotarea)
### getRotation3D() {#getRotation3D--}
```
public final IRotation3D getRotation3D()
```

Gibt eine 3D-Rotation eines Diagramms zurück. Nur Lesen [IRotation3D](../../com.aspose.slides/irotation3d).

**Gibt zurück:**
[IRotation3D](../../com.aspose.slides/irotation3d)
### getBackWall() {#getBackWall--}
```
public final IChartWall getBackWall()
```

Gibt ein Objekt zurück, das das Ändern des Formats der hinteren Wand eines 3D-Diagramms ermöglicht. Nur Lesen [IChartWall](../../com.aspose.slides/ichartwall).

**Gibt zurück:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getSideWall() {#getSideWall--}
```
public final IChartWall getSideWall()
```

Gibt ein Objekt zurück, das das Ändern des Formats der Seitenwand eines 3D-Diagramms ermöglicht. Nur Lesen [IChartWall](../../com.aspose.slides/ichartwall).

**Gibt zurück:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getFloor() {#getFloor--}
```
public final IChartWall getFloor()
```

Gibt ein Objekt zurück, das das Ändern des Formats des Bodens eines 3D-Diagramms ermöglicht. Nur Lesen [IChartWall](../../com.aspose.slides/ichartwall).

**Gibt zurück:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Gibt das Textformat des Diagramms zurück. Die Eigenschaft ist für die folgenden Typen nicht anwendbar: [ChartType.Treemap](../../com.aspose.slides/charttype\#Treemap), [ChartType.Sunburst](../../com.aspose.slides/charttype\#Sunburst), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel),[ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker). Nur Lesen [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Gibt zurück:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

Gibt ein wirksames Thema für dieses Diagramm zurück.

**Gibt zurück:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

Gibt den Themen-Manager zurück. Nur Lesen [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Gibt zurück:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getUserShapes() {#getUserShapes--}
```
public final IGroupShape getUserShapes()
```

Gibt die Formen an, die über dem Diagramm gezeichnet werden. Nur Lesen [IGroupShape](../../com.aspose.slides/igroupshape).

**Gibt zurück:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### getAxes() {#getAxes--}
```
public final IAxesManager getAxes()
```

Stellt Zugriff auf die Diagrammachsen bereit. Nur Lesen [IAxesManager](../../com.aspose.slides/iaxesmanager).

**Gibt zurück:**
[IAxesManager](../../com.aspose.slides/iaxesmanager)
### getShowDataLabelsOverMaximum() {#getShowDataLabelsOverMaximum--}
```
public final boolean getShowDataLabelsOverMaximum()
```

Gibt an, dass Datenbeschriftungen über dem Maximum des Diagramms angezeigt werden sollen. Lesen/Schreiben boolean.

**Gibt zurück:**
boolean
### setShowDataLabelsOverMaximum(boolean value) {#setShowDataLabelsOverMaximum-boolean-}
```
public final void setShowDataLabelsOverMaximum(boolean value)
```

Gibt an, dass Datenbeschriftungen über dem Maximum des Diagramms angezeigt werden sollen. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### hasRoundedCorners() {#hasRoundedCorners--}
```
public final boolean hasRoundedCorners()
```

Gibt an, dass der Diagrammbereich abgerundete Ecken haben soll. Lesen/Schreiben boolean.

**Gibt zurück:**
boolean
### setRoundedCorners(boolean value) {#setRoundedCorners-boolean-}
```
public final void setRoundedCorners(boolean value)
```

Gibt an, dass der Diagrammbereich abgerundete Ecken haben soll. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getChart() {#getChart--}
```
public final IChart getChart()
```

Gibt das Diagramm zurück. Nur Lesen [IChart](../../com.aspose.slides/ichart).

**Gibt zurück:**
[IChart](../../com.aspose.slides/ichart)