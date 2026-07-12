---
title: IChart
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt ein grafisches Diagramm auf einer Folie dar.
type: docs
url: /de/com.aspose.slides/ichart/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface IChart extends IGraphicalObject, IFormattedTextContainer, IOverrideThemeable
```

Stellt ein grafisches Diagramm auf einer Folie dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPlotVisibleCellsOnly()](#getPlotVisibleCellsOnly--) | Bestimmt, ob nur sichtbare Zellen geplottet werden. |
| [setPlotVisibleCellsOnly(boolean value)](#setPlotVisibleCellsOnly-boolean-) | Bestimmt, ob nur sichtbare Zellen geplottet werden. |
| [getDisplayBlanksAs()](#getDisplayBlanksAs--) | Gibt zurück oder legt fest, wie leere Zellen in einem Diagramm geplottet werden. |
| [setDisplayBlanksAs(int value)](#setDisplayBlanksAs-int-) | Gibt zurück oder legt fest, wie leere Zellen in einem Diagramm geplottet werden. |
| [getChartData()](#getChartData--) | Gibt Informationen über die verknüpften oder eingebetteten Daten eines Diagramms zurück. |
| [hasTitle()](#hasTitle--) | Bestimmt, ob ein Diagramm einen sichtbaren Titel hat. |
| [setTitle(boolean value)](#setTitle-boolean-) | Bestimmt, ob ein Diagramm einen sichtbaren Titel hat. |
| [getChartTitle()](#getChartTitle--) | Gibt einen Diagrammtitel zurück oder legt ihn fest. Nur lesbar [IChartTitle](../../com.aspose.slides/icharttitle). |
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
| [getPlotArea()](#getPlotArea--) | Stellt den Zeichenbereich eines Diagramms dar. |
| [getRotation3D()](#getRotation3D--) | Gibt eine 3D-Drehung eines Diagramms zurück. |
| [getBackWall()](#getBackWall--) | Gibt ein Objekt zurück, das das Format der Rückwand eines 3D-Diagramms ändert. |
| [getSideWall()](#getSideWall--) | Gibt ein Objekt zurück, das das Format der Seitenwand eines 3D-Diagramms ändert. |
| [getFloor()](#getFloor--) | Gibt ein Objekt zurück, das das Format des Bodens eines 3D-Diagramms ändert. |
| [getUserShapes()](#getUserShapes--) | Gibt die Formen an, die oben im Diagramm gezeichnet werden. |
| [getAxes()](#getAxes--) | Stellt Zugriff auf Diagrammachsen bereit. |
| [validateChartLayout()](#validateChartLayout--) | Berechnet die tatsächlichen Werte von Diagrammelementen. |
| [getShowDataLabelsOverMaximum()](#getShowDataLabelsOverMaximum--) | Gibt an, ob Datenbeschriftungen über dem Maximum des Diagramms angezeigt werden sollen. |
| [setShowDataLabelsOverMaximum(boolean value)](#setShowDataLabelsOverMaximum-boolean-) | Gibt an, ob Datenbeschriftungen über dem Maximum des Diagramms angezeigt werden sollen. |
| [hasRoundedCorners()](#hasRoundedCorners--) | Gibt an, dass der Diagrammbereich abgerundete Ecken haben soll. |
| [setRoundedCorners(boolean value)](#setRoundedCorners-boolean-) | Gibt an, dass der Diagrammbereich abgerundete Ecken haben soll. |

### getPlotVisibleCellsOnly() {#getPlotVisibleCellsOnly--}
```
public abstract boolean getPlotVisibleCellsOnly()
```

Bestimmt, ob nur sichtbare Zellen geplottet werden. False, um sowohl sichtbare als auch versteckte Zellen zu plotten. Lesen/Schreiben boolesch.

**Rückgabe:**
boolean

### setPlotVisibleCellsOnly(boolean value) {#setPlotVisibleCellsOnly-boolean-}
```
public abstract void setPlotVisibleCellsOnly(boolean value)
```

Bestimmt, ob nur sichtbare Zellen geplottet werden. False, um sowohl sichtbare als auch versteckte Zellen zu plotten. Lesen/Schreiben boolesch.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getDisplayBlanksAs() {#getDisplayBlanksAs--}
```
public abstract int getDisplayBlanksAs()
```

Gibt zurück oder legt fest, wie leere Zellen in einem Diagramm geplottet werden. Lesen/Schreiben [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Rückgabe:**
int

### setDisplayBlanksAs(int value) {#setDisplayBlanksAs-int-}
```
public abstract void setDisplayBlanksAs(int value)
```

Gibt zurück oder legt fest, wie leere Zellen in einem Diagramm geplottet werden. Lesen/Schreiben [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getChartData() {#getChartData--}
```
public abstract IChartData getChartData()
```

Gibt Informationen über die verknüpften oder eingebetteten Daten eines Diagramms zurück. Nur lesbar [IChartData](../../com.aspose.slides/ichartdata).

**Rückgabe:**
[IChartData](../../com.aspose.slides/ichartdata)

### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

Bestimmt, ob ein Diagramm einen sichtbaren Titel hat. Lesen/Schreiben boolesch.

**Rückgabe:**
boolean

### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

Bestimmt, ob ein Diagramm einen sichtbaren Titel hat. Lesen/Schreiben boolesch.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getChartTitle() {#getChartTitle--}
```
public abstract IChartTitle getChartTitle()
```

Gibt einen Diagrammtitel zurück oder legt ihn fest. Nur lesbar [IChartTitle](../../com.aspose.slides/icharttitle).

**Rückgabe:**
[IChartTitle](../../com.aspose.slides/icharttitle)

### hasDataTable() {#hasDataTable--}
```
public abstract boolean hasDataTable()
```

Bestimmt, ob ein Diagramm eine Datentabelle hat. Lesen/Schreiben boolesch.

**Rückgabe:**
boolean

### setDataTable(boolean value) {#setDataTable-boolean-}
```
public abstract void setDataTable(boolean value)
```

Bestimmt, ob ein Diagramm eine Datentabelle hat. Lesen/Schreiben boolesch.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### hasLegend() {#hasLegend--}
```
public abstract boolean hasLegend()
```

Bestimmt, ob ein Diagramm eine Legende hat. Lesen/Schreiben boolesch.

**Rückgabe:**
boolean

### setLegend(boolean value) {#setLegend-boolean-}
```
public abstract void setLegend(boolean value)
```

Bestimmt, ob ein Diagramm eine Legende hat. Lesen/Schreiben boolesch.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getLegend() {#getLegend--}
```
public abstract ILegend getLegend()
```

Gibt eine Legende für ein Diagramm zurück oder legt sie fest. Nur lesbar [ILegend](../../com.aspose.slides/ilegend).

**Rückgabe:**
[ILegend](../../com.aspose.slides/ilegend)

### getChartDataTable() {#getChartDataTable--}
```
public abstract IDataTable getChartDataTable()
```

Gibt eine Datentabelle eines Diagramms zurück. Nur lesbar [IDataTable](../../com.aspose.slides/idatatable).

**Rückgabe:**
[IDataTable](../../com.aspose.slides/idatatable)

### getStyle() {#getStyle--}
```
public abstract int getStyle()
```

Gibt den Diagrammstil zurück oder legt ihn fest. Lesen/Schreiben [StyleType](../../com.aspose.slides/styletype).

**Rückgabe:**
int

### setStyle(int value) {#setStyle-int-}
```
public abstract void setStyle(int value)
```

Gibt den Diagrammstil zurück oder legt ihn fest. Lesen/Schreiben [StyleType](../../com.aspose.slides/styletype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public abstract int getType()
```

Gibt den Diagrammtyp zurück oder legt ihn fest. Lesen/Schreiben [ChartType](../../com.aspose.slides/charttype).

**Rückgabe:**
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Gibt den Diagrammtyp zurück oder legt ihn fest. Lesen/Schreiben [ChartType](../../com.aspose.slides/charttype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getPlotArea() {#getPlotArea--}
```
public abstract IChartPlotArea getPlotArea()
```

Stellt den Zeichenbereich eines Diagramms dar. Nur lesbar [IChartPlotArea](../../com.aspose.slides/ichartplotarea).

**Rückgabe:**
[IChartPlotArea](../../com.aspose.slides/ichartplotarea)

### getRotation3D() {#getRotation3D--}
```
public abstract IRotation3D getRotation3D()
```

Gibt eine 3D-Drehung eines Diagramms zurück. Nur lesbar [IRotation3D](../../com.aspose.slides/irotation3d).

**Rückgabe:**
[IRotation3D](../../com.aspose.slides/irotation3d)

### getBackWall() {#getBackWall--}
```
public abstract IChartWall getBackWall()
```

Gibt ein Objekt zurück, das das Format der Rückwand eines 3D-Diagramms ändert. Nur lesbar [IChartWall](../../com.aspose.slides/ichartwall).

**Rückgabe:**
[IChartWall](../../com.aspose.slides/ichartwall)

### getSideWall() {#getSideWall--}
```
public abstract IChartWall getSideWall()
```

Gibt ein Objekt zurück, das das Format der Seitenwand eines 3D-Diagramms ändert. Nur lesbar [IChartWall](../../com.aspose.slides/ichartwall).

**Rückgabe:**
[IChartWall](../../com.aspose.slides/ichartwall)

### getFloor() {#getFloor--}
```
public abstract IChartWall getFloor()
```

Gibt ein Objekt zurück, das das Format des Bodens eines 3D-Diagramms ändert. Nur lesbar [IChartWall](../../com.aspose.slides/ichartwall).

**Rückgabe:**
[IChartWall](../../com.aspose.slides/ichartwall)

### getUserShapes() {#getUserShapes--}
```
public abstract IGroupShape getUserShapes()
```

Gibt die Formen an, die oben im Diagramm gezeichnet werden. Nur lesbar [IGroupShape](../../com.aspose.slides/igroupshape).

**Rückgabe:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### getAxes() {#getAxes--}
```
public abstract IAxesManager getAxes()
```

Stellt Zugriff auf Diagrammachsen bereit. Nur lesbar [IAxesManager](../../com.aspose.slides/iaxesmanager).

**Rückgabe:**
[IAxesManager](../../com.aspose.slides/iaxesmanager)

### validateChartLayout() {#validateChartLayout--}
```
public abstract void validateChartLayout()
```

Berechnet die tatsächlichen Werte von Diagrammelementen. Tatsächliche Werte umfassen die Position von Elementen, die IActualLayout implementieren (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) und tatsächliche Achsenwerte (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale)

### getShowDataLabelsOverMaximum() {#getShowDataLabelsOverMaximum--}
```
public abstract boolean getShowDataLabelsOverMaximum()
```

Gibt an, ob Datenbeschriftungen über dem Maximum des Diagramms angezeigt werden sollen. Lesen/Schreiben boolesch.

**Rückgabe:**
boolean

### setShowDataLabelsOverMaximum(boolean value) {#setShowDataLabelsOverMaximum-boolean-}
```
public abstract void setShowDataLabelsOverMaximum(boolean value)
```

Gibt an, ob Datenbeschriftungen über dem Maximum des Diagramms angezeigt werden sollen. Lesen/Schreiben boolesch.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### hasRoundedCorners() {#hasRoundedCorners--}
```
public abstract boolean hasRoundedCorners()
```

Gibt an, dass der Diagrammbereich abgerundete Ecken haben soll. Lesen/Schreiben boolesch.

**Rückgabe:**
boolean

### setRoundedCorners(boolean value) {#setRoundedCorners-boolean-}
```
public abstract void setRoundedCorners(boolean value)
```

Gibt an, dass der Diagrammbereich abgerundete Ecken haben soll. Lesen/Schreiben boolesch.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |