---
title: Chart
second_title: Aspose.Slides Androidhoz Java API hivatkozás
description: Egy grafikus diagramot ábrázol egy dián.
type: docs
url: /hu/com.aspose.slides/chart/
---
**Öröklődés:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Minden megvalósított interfész:**  
[com.aspose.slides.IChart](../../com.aspose.slides/ichart)  
```
public class Chart extends GraphicalObject implements IChart
```

Egy diagramot ábrázol egy dián.

## Módszerek

| Módszer | Leírás |
| --- | --- |
| [validateChartLayout()](#validateChartLayout--) | A diagram elemeinek tényleges értékeit számítja ki. |
| [getPlotVisibleCellsOnly()](#getPlotVisibleCellsOnly--) | Meghatározza, hogy csak a látható cellák legyenek ábrázolva. |
| [setPlotVisibleCellsOnly(boolean value)](#setPlotVisibleCellsOnly-boolean-) | Meghatározza, hogy csak a látható cellák legyenek ábrázolva. |
| [getDisplayBlanksAs()](#getDisplayBlanksAs--) | Visszaadja vagy beállítja a diagram üres celláinak megjelenítésének módját. |
| [setDisplayBlanksAs(int value)](#setDisplayBlanksAs-int-) | Visszaadja vagy beállítja a diagram üres celláinak megjelenítésének módját. |
| [getChartData()](#getChartData--) | Visszaadja egy diagramhoz kapcsolódó csatolt vagy beágyazott adatok információit. |
| [hasTitle()](#hasTitle--) | Meghatározza, hogy a diagramnak van-e látható címe. |
| [setTitle(boolean value)](#setTitle-boolean-) | Meghatározza, hogy a diagramnak van-e látható címe. |
| [getChartTitle()](#getChartTitle--) | Visszaadja vagy beállítja a diagram címét. |
| [hasDataTable()](#hasDataTable--) | Meghatározza, hogy a diagramnak van-e adat táblája. |
| [setDataTable(boolean value)](#setDataTable-boolean-) | Meghatározza, hogy a diagramnak van-e adat táblája. |
| [hasLegend()](#hasLegend--) | Meghatározza, hogy a diagramnak van-e jelmagyarázata. |
| [setLegend(boolean value)](#setLegend-boolean-) | Meghatározza, hogy a diagramnak van-e jelmagyarázata. |
| [getLegend()](#getLegend--) | Visszaadja vagy beállítja a diagram jelmagyarázatát. |
| [getChartDataTable()](#getChartDataTable--) | Visszaadja a diagram adat tábláját. |
| [getStyle()](#getStyle--) | Visszaadja vagy beállítja a diagram stílusát. |
| [setStyle(int value)](#setStyle-int-) | Visszaadja vagy beállítja a diagram stílusát. |
| [getType()](#getType--) | Visszaadja vagy beállítja a diagram típusát. |
| [setType(int value)](#setType-int-) | Visszaadja vagy beállítja a diagram típusát. |
| [getPlotArea()](#getPlotArea--) | A diagram ábrázoló területét reprezentálja. |
| [getRotation3D()](#getRotation3D--) | Visszaadja egy diagram 3D forgását. |
| [getBackWall()](#getBackWall--) | Visszaad egy objektumot, amely lehetővé teszi a 3D diagram hátfalának formátumának módosítását. |
| [getSideWall()](#getSideWall--) | Visszaad egy objektumot, amely lehetővé teszi a 3D diagram oldalfalának formátumának módosítását. |
| [getFloor()](#getFloor--) | Visszaad egy objektumot, amely lehetővé teszi a 3D diagram padlójának formátumának módosítását. |
| [getTextFormat()](#getTextFormat--) | Visszaadja a diagram szövegformátumát. |
| [createThemeEffective()](#createThemeEffective--) | Visszaad egy hatékony témát ehhez a diagramhoz. |
| [getThemeManager()](#getThemeManager--) | Visszaadja a téma kezelőt. |
| [getUserShapes()](#getUserShapes--) | Meghatározza a diagram tetején rajzolt alakzatokat. |
| [getAxes()](#getAxes--) | Hozzáférést biztosít a diagram tengelyeihez. |
| [getShowDataLabelsOverMaximum()](#getShowDataLabelsOverMaximum--) | Meghatározza, hogy a diagram maximuma feletti adatcímkék megjelenjenek-e. |
| [setShowDataLabelsOverMaximum(boolean value)](#setShowDataLabelsOverMaximum-boolean-) | Meghatározza, hogy a diagram maximuma feletti adatcímkék megjelenjenek-e. |
| [hasRoundedCorners()](#hasRoundedCorners--) | Meghatározza, hogy a diagram területének legyenek lekerekített sarkai. |
| [setRoundedCorners(boolean value)](#setRoundedCorners-boolean-) | Meghatározza, hogy a diagram területének legyenek lekerekített sarkai. |
| [getChart()](#getChart--) |  |

### validateChartLayout() {#validateChartLayout--}
```
public final void validateChartLayout()
```

A diagram elemeinek tényleges értékeit számítja ki. A tényleges értékek tartalmazzák a IActualLayout interfészt megvalósító elemek pozícióját (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) és a tengelyek tényleges értékeit (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale).

### getPlotVisibleCellsOnly() {#getPlotVisibleCellsOnly--}
```
public final boolean getPlotVisibleCellsOnly()
```

Meghatározza, hogy csak a látható cellák legyenek ábrázolva. False esetén a látható és a rejtett cellák egyaránt ábrázolásra kerülnek. Olvasás/írás boolean.

**Visszatér:**
boolean

### setPlotVisibleCellsOnly(boolean value) {#setPlotVisibleCellsOnly-boolean-}
```
public final void setPlotVisibleCellsOnly(boolean value)
```

Meghatározza, hogy csak a látható cellák legyenek ábrázolva. False esetén a látható és a rejtett cellák egyaránt ábrázolásra kerülnek. Olvasás/írás boolean.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDisplayBlanksAs() {#getDisplayBlanksAs--}
```
public final int getDisplayBlanksAs()
```

Visszaadja vagy beállítja a diagram üres celláinak megjelenítésének módját. Olvasás/írás [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Visszatér:**
int

### setDisplayBlanksAs(int value) {#setDisplayBlanksAs-int-}
```
public final void setDisplayBlanksAs(int value)
```

Visszaadja vagy beállítja a diagram üres celláinak megjelenítésének módját. Olvasás/írás [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getChartData() {#getChartData--}
```
public final IChartData getChartData()
```

Visszaadja egy diagramhoz kapcsolódó csatolt vagy beágyazott adatok információit. Olvasás csak [IChartData](../../com.aspose.slides/ichartdata).

**Visszatér:**
[IChartData](../../com.aspose.slides/ichartdata)

### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```

Meghatározza, hogy a diagramnak van-e látható címe. Olvasás/írás boolean.

**Visszatér:**
boolean

### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```

Meghatározza, hogy a diagramnak van-e látható címe. Olvasás/írás boolean.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getChartTitle() {#getChartTitle--}
```
public final IChartTitle getChartTitle()
```

Visszaadja vagy beállítja a diagram címét. Olvasás csak [IChartTitle](../../com.aspose.slides/icharttitle).

**Visszatér:**
[IChartTitle](../../com.aspose.slides/icharttitle)

### hasDataTable() {#hasDataTable--}
```
public final boolean hasDataTable()
```

Meghatározza, hogy a diagramnak van-e adat táblája. Olvasás/írás boolean.

**Visszatér:**
boolean

### setDataTable(boolean value) {#setDataTable-boolean-}
```
public final void setDataTable(boolean value)
```

Meghatározza, hogy a diagramnak van-e adat táblája. Olvasás/írás boolean.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### hasLegend() {#hasLegend--}
```
public final boolean hasLegend()
```

Meghatározza, hogy a diagramnak van-e jelmagyarázata. Olvasás/írás boolean.

**Visszatér:**
boolean

### setLegend(boolean value) {#setLegend-boolean-}
```
public final void setLegend(boolean value)
```

Meghatározza, hogy a diagramnak van-e jelmagyarázata. Olvasás/írás boolean.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLegend() {#getLegend--}
```
public final ILegend getLegend()
```

Visszaadja vagy beállítja a diagram jelmagyarázatát. Olvasás csak [ILegend](../../com.aspose.slides/ilegend).

**Visszatér:**
[ILegend](../../com.aspose.slides/ilegend)

### getChartDataTable() {#getChartDataTable--}
```
public final IDataTable getChartDataTable()
```

Visszaadja a diagram adat tábláját. Olvasás csak [IDataTable](../../com.aspose.slides/idatatable).

**Visszatér:**
[IDataTable](../../com.aspose.slides/idatatable)

### getStyle() {#getStyle--}
```
public final int getStyle()
```

Visszaadja vagy beállítja a diagram stílusát. Olvasás/írás [StyleType](../../com.aspose.slides/styletype).

**Visszatér:**
int

### setStyle(int value) {#setStyle-int-}
```
public final void setStyle(int value)
```

Visszaadja vagy beállítja a diagram stílusát. Olvasás/írás [StyleType](../../com.aspose.slides/styletype).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public final int getType()
```

Visszaadja vagy beállítja a diagram típusát. Olvasás/írás [ChartType](../../com.aspose.slides/charttype).

**Visszatér:**
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Visszaadja vagy beállítja a diagram típusát. Olvasás/írás [ChartType](../../com.aspose.slides/charttype).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPlotArea() {#getPlotArea--}
```
public final IChartPlotArea getPlotArea()
```

A diagram ábrázoló területét reprezentálja. Olvasás csak [IChartPlotArea](../../com.aspose.slides/ichartplotarea).

**Visszatér:**
[IChartPlotArea](../../com.aspose.slides/ichartplotarea)

### getRotation3D() {#getRotation3D--}
```
public final IRotation3D getRotation3D()
```

Visszaad egy 3D forgást a diagramhoz. Olvasás csak [IRotation3D](../../com.aspose.slides/irotation3d).

**Visszatér:**
[IRotation3D](../../com.aspose.slides/irotation3d)

### getBackWall() {#getBackWall--}
```
public final IChartWall getBackWall()
```

Visszaad egy objektumot, amely lehetővé teszi a 3D diagram hátfalának formátumának módosítását. Olvasás csak [IChartWall](../../com.aspose.slides/ichartwall).

**Visszatér:**
[IChartWall](../../com.aspose.slides/ichartwall)

### getSideWall() {#getSideWall--}
```
public final IChartWall getSideWall()
```

Visszaad egy objektumot, amely lehetővé teszi a 3D diagram oldalfalának formátumának módosítását. Olvasás csak [IChartWall](../../com.aspose.slides/ichartwall).

**Visszatér:**
[IChartWall](../../com.aspose.slides/ichartwall)

### getFloor() {#getFloor--}
```
public final IChartWall getFloor()
```

Visszaad egy objektumot, amely lehetővé teszi a 3D diagram padlójának formátumának módosítását. Olvasás csak [IChartWall](../../com.aspose.slides/ichartwall).

**Visszatér:**
[IChartWall](../../com.aspose.slides/ichartwall)

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Visszaadja a diagram szövegformátumát. A tulajdonság a következő típusoknál nem alkalmazható: [ChartType.Treemap](../../com.aspose.slides/charttype\#Treemap), [ChartType.Sunburst](../../com.aspose.slides/charttype\#Sunburst), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel),[ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker). Olvasás csak [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Visszatér:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

Visszaad egy hatékony témát ehhez a diagramhoz.

**Visszatér:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)

### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

Visszaadja a téma kezelőt. Olvasás csak [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Visszatér:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)

### getUserShapes() {#getUserShapes--}
```
public final IGroupShape getUserShapes()
```

Meghatározza a diagram tetején rajzolt alakzatokat. Olvasás csak [IGroupShape](../../com.aspose.slides/igroupshape).

**Visszatér:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### getAxes() {#getAxes--}
```
public final IAxesManager getAxes()
```

Hozzáférést biztosít a diagram tengelyeihez. Olvasás csak [IAxesManager](../../com.aspose.slides/iaxesmanager).

**Visszatér:**
[IAxesManager](../../com.aspose.slides/iaxesmanager)

### getShowDataLabelsOverMaximum() {#getShowDataLabelsOverMaximum--}
```
public final boolean getShowDataLabelsOverMaximum()
```

Meghatározza, hogy a diagram maximuma feletti adatcímkék megjelenjenek-e. Olvasás/írás boolean.

**Visszatér:**
boolean

### setShowDataLabelsOverMaximum(boolean value) {#setShowDataLabelsOverMaximum-boolean-}
```
public final void setShowDataLabelsOverMaximum(boolean value)
```

Meghatározza, hogy a diagram maximuma feletti adatcímkék megjelenjenek-e. Olvasás/írás boolean.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### hasRoundedCorners() {#hasRoundedCorners--}
```
public final boolean hasRoundedCorners()
```

Meghatározza, hogy a diagram területének legyenek lekerekített sarkai. Olvasás/írás boolean.

**Visszatér:**
boolean

### setRoundedCorners(boolean value) {#setRoundedCorners-boolean-}
```
public final void setRoundedCorners(boolean value)
```

Meghatározza, hogy a diagram területének legyenek lekerekített sarkai. Olvasás/írás boolean.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getChart() {#getChart--}
```
public final IChart getChart()
```

Visszaadja a diagramot. Olvasás csak [IChart](../../com.aspose.slides/ichart).

**Visszatér:**
[IChart](../../com.aspose.slides/ichart)