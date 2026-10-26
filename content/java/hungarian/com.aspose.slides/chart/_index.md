---
title: Chart
second_title: Aspose.Slides Java API hivatkozás
description: Egy grafikus diagramot jelenít meg a dián.
type: docs
url: /hu/com.aspose.slides/chart/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Minden megvalósított interfész:**
[com.aspose.slides.IChart](../../com.aspose.slides/ichart)
```
public class Chart extends GraphicalObject implements IChart
```

Egy grafikus diagramot jelenít meg a dián.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [validateChartLayout()](#validateChartLayout--) | A diagram elemeinek tényleges értékeit számolja ki. |
| [getPlotVisibleCellsOnly()](#getPlotVisibleCellsOnly--) | Megállapítja, hogy csak a látható cellákat ábrázolják-e. |
| [setPlotVisibleCellsOnly(boolean value)](#setPlotVisibleCellsOnly-boolean-) | Megállapítja, hogy csak a látható cellákat ábrázolják-e. |
| [getDisplayBlanksAs()](#getDisplayBlanksAs--) | Visszaadja vagy beállítja, hogyan ábrázolják az üres cellákat a diagramon. |
| [setDisplayBlanksAs(int value)](#setDisplayBlanksAs-int-) | Visszaadja vagy beállítja, hogyan ábrázolják az üres cellákat a diagramon. |
| [getChartData()](#getChartData--) | Információt ad vissza a diagramhoz kapcsolt vagy beágyazott adatokkal kapcsolatban. |
| [hasTitle()](#hasTitle--) | Megállapítja, hogy a diagramnak van-e látható címe. |
| [setTitle(boolean value)](#setTitle-boolean-) | Megállapítja, hogy a diagramnak van-e látható címe. |
| [getChartTitle()](#getChartTitle--) | Visszaadja vagy beállítja a diagram címét. |
| [hasDataTable()](#hasDataTable--) | Megállapítja, hogy a diagramnak van-e adat táblázata. |
| [setDataTable(boolean value)](#setDataTable-boolean-) | Megállapítja, hogy a diagramnak van-e adat táblázata. |
| [hasLegend()](#hasLegend--) | Megállapítja, hogy a diagramnak van-e jelmagyarázata. |
| [setLegend(boolean value)](#setLegend-boolean-) | Megállapítja, hogy a diagramnak van-e jelmagyarázata. |
| [getLegend()](#getLegend--) | Visszaadja vagy beállítja a diagram jelmagyarázatát. |
| [getChartDataTable()](#getChartDataTable--) | Visszaad egy adat táblázatot a diagramhoz. |
| [getStyle()](#getStyle--) | Visszaadja vagy beállítja a diagram stílusát. |
| [setStyle(int value)](#setStyle-int-) | Visszaadja vagy beállítja a diagram stílusát. |
| [getType()](#getType--) | Visszaadja vagy beállítja a diagram típusát. |
| [setType(int value)](#setType-int-) | Visszaadja vagy beállítja a diagram típusát. |
| [getPlotArea()](#getPlotArea--) | A diagram ábrázolási területét jelenti. |
| [getRotation3D()](#getRotation3D--) | Visszaad egy 3D forgást a diagramról. |
| [getBackWall()](#getBackWall--) | Visszaad egy objektumot, amely lehetővé teszi a 3D diagram hátsó falának formátumának módosítását. |
| [getSideWall()](#getSideWall--) | Visszaad egy objektumot, amely lehetővé teszi a 3D diagram oldalfalának formátumának módosítását. |
| [getFloor()](#getFloor--) | Visszaad egy objektumot, amely lehetővé teszi a 3D diagram padlójának formátumának módosítását. |
| [getTextFormat()](#getTextFormat--) | Visszaadja a diagram szövegformátumát. |
| [createThemeEffective()](#createThemeEffective--) | Visszaad egy hatékony témát ehhez a diagramhoz. |
| [getThemeManager()](#getThemeManager--) | Visszaadja a témakezelőt. |
| [getUserShapes()](#getUserShapes--) | A diagram tetején megrajzolt alakzatokat adja meg. |
| [getAxes()](#getAxes--) | Hozzáférést biztosít a diagram tengelyeihez. |
| [getShowDataLabelsOverMaximum()](#getShowDataLabelsOverMaximum--) | Megadja, hogy a diagram maximuma feletti adatcímkék megjelenjenek-e. |
| [setShowDataLabelsOverMaximum(boolean value)](#setShowDataLabelsOverMaximum-boolean-) | Megadja, hogy a diagram maximuma feletti adatcímkék megjelenjenek-e. |
| [hasRoundedCorners()](#hasRoundedCorners--) | Megadja, hogy a diagram területe legyen lekerekített sarkokkal. |
| [setRoundedCorners(boolean value)](#setRoundedCorners-boolean-) | Megadja, hogy a diagram területe legyen lekerekített sarkokkal. |
| [getChart()](#getChart--) |  |
### validateChartLayout() {#validateChartLayout--}
```
public final void validateChartLayout()
```

A diagram elemeinek tényleges értékeit számolja ki. A tényleges értékek tartalmazzák azoknak az elemeknek a pozícióját, amelyek az IActualLayout interfészt valósítják meg (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight), valamint a tengelyek tényleges értékeit (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale).

### getPlotVisibleCellsOnly() {#getPlotVisibleCellsOnly--}
```
public final boolean getPlotVisibleCellsOnly()
```

Megállapítja, hogy csak a látható cellákat ábrázolják-e. False esetén a látható és rejtett cellák egyaránt ábrázolásra kerülnek. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setPlotVisibleCellsOnly(boolean value) {#setPlotVisibleCellsOnly-boolean-}
```
public final void setPlotVisibleCellsOnly(boolean value)
```

Megállapítja, hogy csak a látható cellákat ábrázolják-e. False esetén a látható és rejtett cellák egyaránt ábrázolásra kerülnek. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getDisplayBlanksAs() {#getDisplayBlanksAs--}
```
public final int getDisplayBlanksAs()
```

Visszaadja vagy beállítja, hogyan ábrázolják az üres cellákat a diagramon. Olvasás/írás [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Visszatérési érték:**
int
### setDisplayBlanksAs(int value) {#setDisplayBlanksAs-int-}
```
public final void setDisplayBlanksAs(int value)
```

Visszaadja vagy beállítja, hogyan ábrázolják az üres cellákat a diagramon. Olvasás/írás [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getChartData() {#getChartData--}
```
public final IChartData getChartData()
```

Információt ad vissza a diagramhoz kapcsolt vagy beágyazott adatokkal kapcsolatban. Csak olvasható [IChartData](../../com.aspose.slides/ichartdata).

**Visszatérési érték:**
[IChartData](../../com.aspose.slides/ichartdata)
### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```

Megállapítja, hogy a diagramnak van-e látható címe. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```

Megállapítja, hogy a diagramnak van-e látható címe. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getChartTitle() {#getChartTitle--}
```
public final IChartTitle getChartTitle()
```

Visszaadja vagy beállítja a diagram címét. Csak olvasható [IChartTitle](../../com.aspose.slides/icharttitle).

**Visszatérési érték:**
[IChartTitle](../../com.aspose.slides/icharttitle)
### hasDataTable() {#hasDataTable--}
```
public final boolean hasDataTable()
```

Megállapítja, hogy a diagramnak van-e adat táblázata. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setDataTable(boolean value) {#setDataTable-boolean-}
```
public final void setDataTable(boolean value)
```

Megállapítja, hogy a diagramnak van-e adat táblázata. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### hasLegend() {#hasLegend--}
```
public final boolean hasLegend()
```

Megállapítja, hogy a diagramnak van-e jelmagyarázata. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setLegend(boolean value) {#setLegend-boolean-}
```
public final void setLegend(boolean value)
```

Megállapítja, hogy a diagramnak van-e jelmagyarázata. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getLegend() {#getLegend--}
```
public final ILegend getLegend()
```

Visszaadja vagy beállítja a diagram jelmagyarázatát. Csak olvasható [ILegend](../../com.aspose.slides/ilegend).

**Visszatérési érték:**
[ILegend](../../com.aspose.slides/ilegend)
### getChartDataTable() {#getChartDataTable--}
```
public final IDataTable getChartDataTable()
```

Visszaad egy adat táblázatot a diagramhoz. Csak olvasható [IDataTable](../../com.aspose.slides/idatatable).

**Visszatérési érték:**
[IDataTable](../../com.aspose.slides/idatatable)
### getStyle() {#getStyle--}
```
public final int getStyle()
```

Visszaadja vagy beállítja a diagram stílusát. Olvasás/írás [StyleType](../../com.aspose.slides/styletype).

**Visszatérési érték:**
int
### setStyle(int value) {#setStyle-int-}
```
public final void setStyle(int value)
```

Visszaadja vagy beállítja a diagram stílusát. Olvasás/írás [StyleType](../../com.aspose.slides/styletype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public final int getType()
```

Visszaadja vagy beállítja a diagram típusát. Olvasás/írás [ChartType](../../com.aspose.slides/charttype).

**Visszatérési érték:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Visszaadja vagy beállítja a diagram típusát. Olvasás/írás [ChartType](../../com.aspose.slides/charttype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getPlotArea() {#getPlotArea--}
```
public final IChartPlotArea getPlotArea()
```

A diagram ábrázolási területét jelenti. Csak olvasható [IChartPlotArea](../../com.aspose.slides/ichartplotarea).

**Visszatérési érték:**
[IChartPlotArea](../../com.aspose.slides/ichartplotarea)
### getRotation3D() {#getRotation3D--}
```
public final IRotation3D getRotation3D()
```

Visszaad egy 3D forgást a diagramról. Csak olvasható [IRotation3D](../../com.aspose.slides/irotation3d).

**Visszatérési érték:**
[IRotation3D](../../com.aspose.slides/irotation3d)
### getBackWall() {#getBackWall--}
```
public final IChartWall getBackWall()
```

Visszaad egy objektumot, amely lehetővé teszi a 3D diagram hátsó falának formátumának módosítását. Csak olvasható [IChartWall](../../com.aspose.slides/ichartwall).

**Visszatérési érték:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getSideWall() {#getSideWall--}
```
public final IChartWall getSideWall()
```

Visszaad egy objektumot, amely lehetővé teszi a 3D diagram oldalfalának formátumának módosítását. Csak olvasható [IChartWall](../../com.aspose.slides/ichartwall).

**Visszatérési érték:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getFloor() {#getFloor--}
```
public final IChartWall getFloor()
```

Visszaad egy objektumot, amely lehetővé teszi a 3D diagram padlójának formátumának módosítását. Csak olvasható [IChartWall](../../com.aspose.slides/ichartwall).

**Visszatérési érték:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Visszaadja a diagram szövegformátumát. A tulajdonság a következő típusokra nem alkalmazható: [ChartType.Treemap](../../com.aspose.slides/charttype\#Treemap), [ChartType.Sunburst](../../com.aspose.slides/charttype\#Sunburst), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel),[ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker). Csak olvasható [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Visszatérési érték:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

Visszaad egy hatékony témát ehhez a diagramhoz.

**Visszatérési érték:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

Visszaadja a témakezelőt. Csak olvasható [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Visszatérési érték:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getUserShapes() {#getUserShapes--}
```
public final IGroupShape getUserShapes()
```

A diagram tetején megrajzolt alakzatokat adja meg. Csak olvasható [IGroupShape](../../com.aspose.slides/igroupshape).

**Visszatérési érték:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### getAxes() {#getAxes--}
```
public final IAxesManager getAxes()
```

Hozzáférést biztosít a diagram tengelyeihez. Csak olvasható [IAxesManager](../../com.aspose.slides/iaxesmanager).

**Visszatérési érték:**
[IAxesManager](../../com.aspose.slides/iaxesmanager)
### getShowDataLabelsOverMaximum() {#getShowDataLabelsOverMaximum--}
```
public final boolean getShowDataLabelsOverMaximum()
```

Megadja, hogy a diagram maximuma feletti adatcímkék megjelenjenek-e. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setShowDataLabelsOverMaximum(boolean value) {#setShowDataLabelsOverMaximum-boolean-}
```
public final void setShowDataLabelsOverMaximum(boolean value)
```

Megadja, hogy a diagram maximuma feletti adatcímkék megjelenjenek-e. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### hasRoundedCorners() {#hasRoundedCorners--}
```
public final boolean hasRoundedCorners()
```

Megadja, hogy a diagram területe legyen lekerekített sarkokkal. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setRoundedCorners(boolean value) {#setRoundedCorners-boolean-}
```
public final void setRoundedCorners(boolean value)
```

Megadja, hogy a diagram területe legyen lekerekített sarkokkal. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getChart() {#getChart--}
```
public final IChart getChart()
```

Visszaadja a diagramot. Csak olvasható [IChart](../../com.aspose.slides/ichart).

**Visszatérési érték:**
[IChart](../../com.aspose.slides/ichart)