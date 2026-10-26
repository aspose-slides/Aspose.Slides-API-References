---
title: IChart
second_title: Aspose.Slides Androidra a Java API hivatkozásával
description: Egy grafikus diagramot képvisel egy dián.
type: docs
url: /hu/com.aspose.slides/ichart/
---
**Az összes megvalósított interfész:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface IChart extends IGraphicalObject, IFormattedTextContainer, IOverrideThemeable
```

Egy grafikus diagramot képvisel egy dián.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getPlotVisibleCellsOnly()](#getPlotVisibleCellsOnly--) | Meghatározza, hogy csak a látható cellák legyenek ábrázolva. |
| [setPlotVisibleCellsOnly(boolean value)](#setPlotVisibleCellsOnly-boolean-) | Meghatározza, hogy csak a látható cellák legyenek ábrázolva. |
| [getDisplayBlanksAs()](#getDisplayBlanksAs--) | Visszaadja vagy beállítja a diagramon az üres cellák ábrázolásának módját. |
| [setDisplayBlanksAs(int value)](#setDisplayBlanksAs-int-) | Visszaadja vagy beállítja a diagramon az üres cellák ábrázolásának módját. |
| [getChartData()](#getChartData--) | Visszaad információt a diagramhoz kapcsolódó linkelt vagy beágyazott adatokról. |
| [hasTitle()](#hasTitle--) | Meghatározza, hogy a diagramnak van-e látható címe. |
| [setTitle(boolean value)](#setTitle-boolean-) | Meghatározza, hogy a diagramnak van-e látható címe. |
| [getChartTitle()](#getChartTitle--) | Visszaadja vagy beállítja a diagram címét Csak olvasható [IChartTitle](../../com.aspose.slides/icharttitle). |
| [hasDataTable()](#hasDataTable--) | Meghatározza, hogy a diagramhoz tartozik-e adat táblázat. |
| [setDataTable(boolean value)](#setDataTable-boolean-) | Meghatározza, hogy a diagramhoz tartozik-e adat táblázat. |
| [hasLegend()](#hasLegend--) | Meghatározza, hogy a diagramnak van-e jelmagyarázata. |
| [setLegend(boolean value)](#setLegend-boolean-) | Meghatározza, hogy a diagramnak van-e jelmagyarázata. |
| [getLegend()](#getLegend--) | Visszaadja vagy beállítja a diagram jelmagyarázatát. |
| [getChartDataTable()](#getChartDataTable--) | Visszaadja a diagram adat táblázatát. |
| [getStyle()](#getStyle--) | Visszaadja vagy beállítja a diagram stílusát. |
| [setStyle(int value)](#setStyle-int-) | Visszaadja vagy beállítja a diagram stílusát. |
| [getType()](#getType--) | Visszaadja vagy beállítja a diagram típusát. |
| [setType(int value)](#setType-int-) | Visszaadja vagy beállítja a diagram típusát. |
| [getPlotArea()](#getPlotArea--) | A diagram ábrázolási területét képviseli. |
| [getRotation3D()](#getRotation3D--) | Visszaad egy 3D forgást a diagramra. |
| [getBackWall()](#getBackWall--) | Visszaad egy objektumot, amely lehetővé teszi a 3D diagram hátfalának formátumának módosítását. |
| [getSideWall()](#getSideWall--) | Visszaad egy objektumot, amely lehetővé teszi a 3D diagram oldalfalának formátumának módosítását. |
| [getFloor()](#getFloor--) | Visszaad egy objektumot, amely lehetővé teszi a 3D diagram alaplapjának formátumának módosítását. |
| [getUserShapes()](#getUserShapes--) | Határozza meg a diagram tetején megrajzolt alakzatokat. |
| [getAxes()](#getAxes--) | Hozzáférést biztosít a diagram tengelyeihez. |
| [validateChartLayout()](#validateChartLayout--) | Kiszámítja a diagram elemeinek tényleges értékeit. |
| [getShowDataLabelsOverMaximum()](#getShowDataLabelsOverMaximum--) | Megadja, hogy a diagram maximuma feletti adatcímkék megjelenjenek-e. |
| [setShowDataLabelsOverMaximum(boolean value)](#setShowDataLabelsOverMaximum-boolean-) | Megadja, hogy a diagram maximuma feletti adatcímkék megjelenjenek-e. |
| [hasRoundedCorners()](#hasRoundedCorners--) | Megadja, hogy a diagram területének legyenek lekerekített sarkai. |
| [setRoundedCorners(boolean value)](#setRoundedCorners-boolean-) | Megadja, hogy a diagram területének legyenek lekerekített sarkai. |

### getPlotVisibleCellsOnly() {#getPlotVisibleCellsOnly--}
```
public abstract boolean getPlotVisibleCellsOnly()
```

Megállapítja, hogy csak a látható cellák legyenek ábrázolva. False, ha a látható és a rejtett cellákat is ábrázolni kell. Olvasás/írás boolean.

**Visszatér:**  
boolean

### setPlotVisibleCellsOnly(boolean value) {#setPlotVisibleCellsOnly-boolean-}
```
public abstract void setPlotVisibleCellsOnly(boolean value)
```

Megállapítja, hogy csak a látható cellák legyenek ábrázolva. False, ha a látható és a rejtett cellákat is ábrázolni kell. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getDisplayBlanksAs() {#getDisplayBlanksAs--}
```
public abstract int getDisplayBlanksAs()
```

Visszaadja vagy beállítja a diagramon az üres cellák ábrázolásának módját. Olvasás/írás [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Visszatér:**  
int

### setDisplayBlanksAs(int value) {#setDisplayBlanksAs-int-}
```
public abstract void setDisplayBlanksAs(int value)
```

Visszaadja vagy beállítja a diagramon az üres cellák ábrázolásának módját. Olvasás/írás [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getChartData() {#getChartData--}
```
public abstract IChartData getChartData()
```

Visszaad információt a diagramhoz kapcsolódó linkelt vagy beágyazott adatokról. Csak olvasható [IChartData](../../com.aspose.slides/ichartdata).

**Visszatér:**  
[IChartData](../../com.aspose.slides/ichartdata)

### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

Megállapítja, hogy a diagramnak van-e látható címe. Olvasás/írás boolean.

**Visszatér:**  
boolean

### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

Megállapítja, hogy a diagramnak van-e látható címe. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getChartTitle() {#getChartTitle--}
```
public abstract IChartTitle getChartTitle()
```

Visszaadja vagy beállítja a diagram címét Csak olvasható [IChartTitle](../../com.aspose.slides/icharttitle).

**Visszatér:**  
[IChartTitle](../../com.aspose.slides/icharttitle)

### hasDataTable() {#hasDataTable--}
```
public abstract boolean hasDataTable()
```

Megállapítja, hogy a diagramhoz tartozik-e adat táblázat. Olvasás/írás boolean.

**Visszatér:**  
boolean

### setDataTable(boolean value) {#setDataTable-boolean-}
```
public abstract void setDataTable(boolean value)
```

Megállapítja, hogy a diagramhoz tartozik-e adat táblázat. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### hasLegend() {#hasLegend--}
```
public abstract boolean hasLegend()
```

Megállapítja, hogy a diagramnak van-e jelmagyarázata. Olvasás/írás boolean.

**Visszatér:**  
boolean

### setLegend(boolean value) {#setLegend-boolean-}
```
public abstract void setLegend(boolean value)
```

Megállapítja, hogy a diagramnak van-e jelmagyarázata. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getLegend() {#getLegend--}
```
public abstract ILegend getLegend()
```

Visszaadja vagy beállítja a diagram jelmagyarázatát Csak olvasható [ILegend](../../com.aspose.slides/ilegend).

**Visszatér:**  
[ILegend](../../com.aspose.slides/ilegend)

### getChartDataTable() {#getChartDataTable--}
```
public abstract IDataTable getChartDataTable()
```

Visszaadja a diagram adat táblázatát Csak olvasható [IDataTable](../../com.aspose.slides/idatatable).

**Visszatér:**  
[IDataTable](../../com.aspose.slides/idatatable)

### getStyle() {#getStyle--}
```
public abstract int getStyle()
```

Visszaadja vagy beállítja a diagram stílusát Olvasás/írás [StyleType](../../com.aspose.slides/styletype).

**Visszatér:**  
int

### setStyle(int value) {#setStyle-int-}
```
public abstract void setStyle(int value)
```

Visszaadja vagy beállítja a diagram stílusát Olvasás/írás [StyleType](../../com.aspose.slides/styletype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public abstract int getType()
```

Visszaadja vagy beállítja a diagram típusát Olvasás/írás [ChartType](../../com.aspose.slides/charttype).

**Visszatér:**  
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Visszaadja vagy beállítja a diagram típusát Olvasás/írás [ChartType](../../com.aspose.slides/charttype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getPlotArea() {#getPlotArea--}
```
public abstract IChartPlotArea getPlotArea()
```

A diagram ábrázolási területét képviseli. Csak olvasható [IChartPlotArea](../../com.aspose.slides/ichartplotarea).

**Visszatér:**  
[IChartPlotArea](../../com.aspose.slides/ichartplotarea)

### getRotation3D() {#getRotation3D--}
```
public abstract IRotation3D getRotation3D()
```

Visszaad egy 3D forgást a diagramra. Csak olvasható [IRotation3D](../../com.aspose.slides/irotation3d).

**Visszatér:**  
[IRotation3D](../../com.aspose.slides/irotation3d)

### getBackWall() {#getBackWall--}
```
public abstract IChartWall getBackWall()
```

Visszaad egy objektumot, amely lehetővé teszi a 3D diagram hátfalának formátumának módosítását. Csak olvasható [IChartWall](../../com.aspose.slides/ichartwall).

**Visszatér:**  
[IChartWall](../../com.aspose.slides/ichartwall)

### getSideWall() {#getSideWall--}
```
public abstract IChartWall getSideWall()
```

Visszaad egy objektumot, amely lehetővé teszi a 3D diagram oldalfalának formátumának módosítását. Csak olvasható [IChartWall](../../com.aspose.slides/ichartwall).

**Visszatér:**  
[IChartWall](../../com.aspose.slides/ichartwall)

### getFloor() {#getFloor--}
```
public abstract IChartWall getFloor()
```

Visszaad egy objektumot, amely lehetővé teszi a 3D diagram alaplapjának formátumának módosítását. Csak olvasható [IChartWall](../../com.aspose.slides/ichartwall).

**Visszatér:**  
[IChartWall](../../com.aspose.slides/ichartwall)

### getUserShapes() {#getUserShapes--}
```
public abstract IGroupShape getUserShapes()
```

Határozza meg a diagram tetején megrajzolt alakzatokat. Csak olvasható [IGroupShape](../../com.aspose.slides/igroupshape).

**Visszatér:**  
[IGroupShape](../../com.aspose.slides/igroupshape)

### getAxes() {#getAxes--}
```
public abstract IAxesManager getAxes()
```

Hozzáférést biztosít a diagram tengelyeihez. Csak olvasható [IAxesManager](../../com.aspose.slides/iaxesmanager).

**Visszatér:**  
[IAxesManager](../../com.aspose.slides/iaxesmanager)

### validateChartLayout() {#validateChartLayout--}
```
public abstract void validateChartLayout()
```

Kiszámítja a diagram elemeinek tényleges értékeit. A tényleges értékek tartalmazzák azoknak az elemeknek a pozícióját, amelyek az IActualLayout interfészt valósítják meg (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) és a tényleges tengelyértékeket (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale).

### getShowDataLabelsOverMaximum() {#getShowDataLabelsOverMaximum--}
```
public abstract boolean getShowDataLabelsOverMaximum()
```

Megadja, hogy a diagram maximuma feletti adatcímkék megjelenjenek-e. Olvasás/írás boolean.

**Visszatér:**  
boolean

### setShowDataLabelsOverMaximum(boolean value) {#setShowDataLabelsOverMaximum-boolean-}
```
public abstract void setShowDataLabelsOverMaximum(boolean value)
```

Megadja, hogy a diagram maximuma feletti adatcímkék megjelenjenek-e. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### hasRoundedCorners() {#hasRoundedCorners--}
```
public abstract boolean hasRoundedCorners()
```

Megadja, hogy a diagram területének legyenek lekerekített sarkai. Olvasás/írás boolean.

**Visszatér:**  
boolean

### setRoundedCorners(boolean value) {#setRoundedCorners-boolean-}
```
public abstract void setRoundedCorners(boolean value)
```

Megadja, hogy a diagram területének legyenek lekerekített sarkai. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |