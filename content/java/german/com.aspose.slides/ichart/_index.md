---
title: IChart
second_title: Aspose.Slides für Java API-Referenz
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
| [getDisplayBlanksAs()](#getDisplayBlanksAs--) | Gibt zurück oder legt die Art fest, leere Zellen in einem Diagramm zu plotten. |
| [setDisplayBlanksAs(int value)](#setDisplayBlanksAs-int-) | Gibt zurück oder legt die Art fest, leere Zellen in einem Diagramm zu plotten. |
| [getChartData()](#getChartData--) | Gibt Informationen über die verknüpften oder eingebetteten Daten eines Diagramms zurück. |
| [hasTitle()](#hasTitle--) | Bestimmt, ob ein Diagramm einen sichtbaren Titel hat. |
| [setTitle(boolean value)](#setTitle-boolean-) | Bestimmt, ob ein Diagramm einen sichtbaren Titel hat. |
| [getChartTitle()](#getChartTitle--) | Gibt zurück oder legt einen Diagrammtitel fest Nur lesen [IChartTitle](../../com.aspose.slides/icharttitle). |
| [hasDataTable()](#hasDataTable--) | Bestimmt, ob ein Diagramm eine Datentabelle hat. |
| [setDataTable(boolean value)](#setDataTable-boolean-) | Bestimmt, ob ein Diagramm eine Datentabelle hat. |
| [hasLegend()](#hasLegend--) | Bestimmt, ob ein Diagramm eine Legende hat. |
| [setLegend(boolean value)](#setLegend-boolean-) | Bestimmt, ob ein Diagramm eine Legende hat. |
| [getLegend()](#getLegend--) | Gibt zurück oder legt eine Legende für ein Diagramm fest. |
| [getChartDataTable()](#getChartDataTable--) | Gibt eine Datentabelle eines Diagramms zurück. |
| [getStyle()](#getStyle--) | Gibt zurück oder legt den Diagrammstil fest. |
| [setStyle(int value)](#setStyle-int-) | Gibt zurück oder legt den Diagrammstil fest. |
| [getType()](#getType--) | Gibt zurück oder legt den Diagrammtyp fest. |
| [setType(int value)](#setType-int-) | Gibt zurück oder legt den Diagrammtyp fest. |
| [getPlotArea()](#getPlotArea--) | Stellt den Zeichenbereich eines Diagramms dar. |
| [getRotation3D()](#getRotation3D--) | Gibt eine 3D-Drehung eines Diagramms zurück. |
| [getBackWall()](#getBackWall--) | Gibt ein Objekt zurück, das die Formatierung der Rückwand eines 3D-Diagramms ändern lässt. |
| [getSideWall()](#getSideWall--) | Gibt ein Objekt zurück, das die Formatierung der Seitenwand eines 3D-Diagramms ändern lässt. |
| [getFloor()](#getFloor--) | Gibt ein Objekt zurück, das die Formatierung des Bodens eines 3D-Diagramms ändern lässt. |
| [getUserShapes()](#getUserShapes--) | Gibt die Formen an, die über dem Diagramm gezeichnet werden. |
| [getAxes()](#getAxes--) | Stellt Zugriff auf Diagrammachsen bereit. |
| [validateChartLayout()](#validateChartLayout--) | Berechnet tatsächliche Werte von Diagrammelementen. |
| [getShowDataLabelsOverMaximum()](#getShowDataLabelsOverMaximum--) | Gibt an, dass Datenbeschriftungen über dem Maximum des Diagramms angezeigt werden sollen. |
| [setShowDataLabelsOverMaximum(boolean value)](#setShowDataLabelsOverMaximum-boolean-) | Gibt an, dass Datenbeschriftungen über dem Maximum des Diagramms angezeigt werden sollen. |
| [hasRoundedCorners()](#hasRoundedCorners--) | Gibt an, dass der Diagrammbereich abgerundete Ecken haben soll. |
| [setRoundedCorners(boolean value)](#setRoundedCorners-boolean-) | Gibt an, dass der Diagrammbereich abgerundete Ecken haben soll. |

### getPlotVisibleCellsOnly() {#getPlotVisibleCellsOnly--}
```
public abstract boolean getPlotVisibleCellsOnly()
```

Bestimmt, ob nur sichtbare Zellen geplottet werden. False, um sowohl sichtbare als auch versteckte Zellen zu plotten. Lese/Schreiben boolean.

**Rückgabe:**
boolean

### setPlotVisibleCellsOnly(boolean value) {#setPlotVisibleCellsOnly-boolean-}
```
public abstract void setPlotVisibleCellsOnly(boolean value)
```

Bestimmt, ob nur sichtbare Zellen geplottet werden. False, um sowohl sichtbare als auch versteckte Zellen zu plotten. Lese/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getDisplayBlanksAs() {#getDisplayBlanksAs--}
```
public abstract int getDisplayBlanksAs()
```

Gibt zurück oder legt die Art fest, leere Zellen in einem Diagramm zu plotten. Lese/Schreiben [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Rückgabe:**
int

### setDisplayBlanksAs(int value) {#setDisplayBlanksAs-int-}
```
public abstract void setDisplayBlanksAs(int value)
```

Gibt zurück oder legt die Art fest, leere Zellen in einem Diagramm zu plotten. Lese/Schreiben [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getChartData() {#getChartData--}
```
public abstract IChartData getChartData()
```

Gibt Informationen über die verknüpften oder eingebetteten Daten eines Diagramms zurück. Nur lesen [IChartData](../../com.aspose.slides/ichartdata).

**Rückgabe:**
[IChartData](../../com.aspose.slides/ichartdata)

### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

Bestimmt, ob ein Diagramm einen sichtbaren Titel hat. Lese/Schreiben boolean.

**Rückgabe:**
boolean

### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

Bestimmt, ob ein Diagramm einen sichtbaren Titel hat. Lese/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getChartTitle() {#getChartTitle--}
```
public abstract IChartTitle getChartTitle()
```

Gibt zurück oder legt einen Diagrammtitel fest Nur lesen [IChartTitle](../../com.aspose.slides/icharttitle).

**Rückgabe:**
[IChartTitle](../../com.aspose.slides/icharttitle)

### hasDataTable() {#hasDataTable--}
```
public abstract boolean hasDataTable()
```

Bestimmt, ob ein Diagramm eine Datentabelle hat. Lese/Schreiben boolean.

**Rückgabe:**
boolean

### setDataTable(boolean value) {#setDataTable-boolean-}
```
public abstract void setDataTable(boolean value)
```

Bestimmt, ob ein Diagramm eine Datentabelle hat. Lese/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### hasLegend() {#hasLegend--}
```
public abstract boolean hasLegend()
```

Bestimmt, ob ein Diagramm eine Legende hat. Lese/Schreiben boolean.

**Rückgabe:**
boolean

### setLegend(boolean value) {#setLegend-boolean-}
```
public abstract void setLegend(boolean value)
```

Bestimmt, ob ein Diagramm eine Legende hat. Lese/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getLegend() {#getLegend--}
```
public abstract ILegend getLegend()
```

Gibt zurück oder legt eine Legende für ein Diagramm fest. Nur lesen [ILegend](../../com.aspose.slides/ilegend).

**Rückgabe:**
[ILegend](../../com.aspose.slides/ilegend)

### getChartDataTable() {#getChartDataTable--}
```
public abstract IDataTable getChartDataTable()
```

Gibt eine Datentabelle eines Diagramms zurück. Nur lesen [IDataTable](../../com.aspose.slides/idatatable).

**Rückgabe:**
[IDataTable](../../com.aspose.slides/idatatable)

### getStyle() {#getStyle--}
```
public abstract int getStyle()
```

Gibt zurück oder legt den Diagrammstil fest. Lese/Schreiben [StyleType](../../com.aspose.slides/styletype).

**Rückgabe:**
int

### setStyle(int value) {#setStyle-int-}
```
public abstract void setStyle(int value)
```

Gibt zurück oder legt den Diagrammstil fest. Lese/Schreiben [StyleType](../../com.aspose.slides/styletype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public abstract int getType()
```

Gibt zurück oder legt den Diagrammtyp fest. Lese/Schreiben [ChartType](../../com.aspose.slides/charttype).

**Rückgabe:**
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Gibt zurück oder legt den Diagrammtyp fest. Lese/Schreiben [ChartType](../../com.aspose.slides/charttype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getPlotArea() {#getPlotArea--}
```
public abstract IChartPlotArea getPlotArea()
```

Stellt den Zeichenbereich eines Diagramms dar. Nur lesen [IChartPlotArea](../../com.aspose.slides/ichartplotarea).

**Rückgabe:**
[IChartPlotArea](../../com.aspose.slides/ichartplotarea)

### getRotation3D() {#getRotation3D--}
```
public abstract IRotation3D getRotation3D()
```

Gibt eine 3D-Drehung eines Diagramms zurück. Nur lesen [IRotation3D](../../com.aspose.slides/irotation3d).

**Rückgabe:**
[IRotation3D](../../com.aspose.slides/irotation3d)

### getBackWall() {#getBackWall--}
```
public abstract IChartWall getBackWall()
```

Gibt ein Objekt zurück, das die Formatierung der Rückwand eines 3D-Diagramms ändern lässt. Nur lesen [IChartWall](../../com.aspose.slides/ichartwall).

**Rückgabe:**
[IChartWall](../../com.aspose.slides/ichartwall)

### getSideWall() {#getSideWall--}
```
public abstract IChartWall getSideWall()
```

Gibt ein Objekt zurück, das die Formatierung der Seitenwand eines 3D-Diagramms ändern lässt. Nur lesen [IChartWall](../../com.aspose.slides/ichartwall).

**Rückgabe:**
[IChartWall](../../com.aspose.slides/ichartwall)

### getFloor() {#getFloor--}
```
public abstract IChartWall getFloor()
```

Gibt ein Objekt zurück, das die Formatierung des Bodens eines 3D-Diagramms ändern lässt. Nur lesen [IChartWall](../../com.aspose.slides/ichartwall).

**Rückgabe:**
[IChartWall](../../com.aspose.slides/ichartwall)

### getUserShapes() {#getUserShapes--}
```
public abstract IGroupShape getUserShapes()
```

Gibt die über dem Diagramm gezeichneten Formen an. Nur lesen [IGroupShape](../../com.aspose.slides/igroupshape).

**Rückgabe:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### getAxes() {#getAxes--}
```
public abstract IAxesManager getAxes()
```

Stellt Zugriff auf Diagrammachsen bereit. Nur lesen [IAxesManager](../../com.aspose.slides/iaxesmanager).

**Rückgabe:**
[IAxesManager](../../com.aspose.slides/iaxesmanager)

### validateChartLayout() {#validateChartLayout--}
```
public abstract void validateChartLayout()
```

Berechnet tatsächliche Werte von Diagrammelementen. Tatsächliche Werte umfassen die Position von Elementen, die das IActualLayout-Interface implementieren (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) und tatsächliche Achsenwerte (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale).

### getShowDataLabelsOverMaximum() {#getShowDataLabelsOverMaximum--}
```
public abstract boolean getShowDataLabelsOverMaximum()
```

Gibt an, dass Datenbeschriftungen über dem Maximum des Diagramms angezeigt werden sollen. Lese/Schreiben boolean.

**Rückgabe:**
boolean

### setShowDataLabelsOverMaximum(boolean value) {#setShowDataLabelsOverMaximum-boolean-}
```
public abstract void setShowDataLabelsOverMaximum(boolean value)
```

Gibt an, dass Datenbeschriftungen über dem Maximum des Diagramms angezeigt werden sollen. Lese/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### hasRoundedCorners() {#hasRoundedCorners--}
```
public abstract boolean hasRoundedCorners()
```

Gibt an, dass der Diagrammbereich abgerundete Ecken haben soll. Lese/Schreiben boolean.

**Rückgabe:**
boolean

### setRoundedCorners(boolean value) {#setRoundedCorners-boolean-}
```
public abstract void setRoundedCorners(boolean value)
```

Gibt an, dass der Diagrammbereich abgerundete Ecken haben soll. Lese/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |