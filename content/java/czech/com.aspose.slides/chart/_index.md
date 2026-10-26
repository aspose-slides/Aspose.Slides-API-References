---
title: Chart
second_title: Aspose.Slides pro Java API Reference
description: Reprezentuje graf na snímku.
type: docs
url: /cs/com.aspose.slides/chart/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Všechny implementované rozhraní:**
[com.aspose.slides.IChart](../../com.aspose.slides/ichart)
```
public class Chart extends GraphicalObject implements IChart
```

Reprezentuje graf na snímku.
## Metody

| Metoda | Popis |
| --- | --- |
| [validateChartLayout()](#validateChartLayout--) | Vypočítá skutečné hodnoty prvků grafu. |
| [getPlotVisibleCellsOnly()](#getPlotVisibleCellsOnly--) | Určuje, zda jsou vykreslovány pouze viditelné buňky. |
| [setPlotVisibleCellsOnly(boolean value)](#setPlotVisibleCellsOnly-boolean-) | Určuje, zda jsou vykreslovány pouze viditelné buňky. |
| [getDisplayBlanksAs()](#getDisplayBlanksAs--) | Vrací nebo nastavuje způsob, jakým jsou vykreslovány prázdné buňky v grafu. |
| [setDisplayBlanksAs(int value)](#setDisplayBlanksAs-int-) | Vrací nebo nastavuje způsob, jakým jsou vykreslovány prázdné buňky v grafu. |
| [getChartData()](#getChartData--) | Vrací informace o propojených nebo vložených datech souvisejících s grafem. |
| [hasTitle()](#hasTitle--) | Určuje, zda má graf viditelný název. |
| [setTitle(boolean value)](#setTitle-boolean-) | Určuje, zda má graf viditelný název. |
| [getChartTitle()](#getChartTitle--) | Vrací nebo nastavuje název grafu. |
| [hasDataTable()](#hasDataTable--) | Určuje, zda má graf datovou tabulku. |
| [setDataTable(boolean value)](#setDataTable-boolean-) | Určuje, zda má graf datovou tabulku. |
| [hasLegend()](#hasLegend--) | Určuje, zda má graf legendu. |
| [setLegend(boolean value)](#setLegend-boolean-) | Určuje, zda má graf legendu. |
| [getLegend()](#getLegend--) | Vrací nebo nastavuje legendu pro graf. |
| [getChartDataTable()](#getChartDataTable--) | Vrací datovou tabulku grafu. |
| [getStyle()](#getStyle--) | Vrací nebo nastavuje styl grafu. |
| [setStyle(int value)](#setStyle-int-) | Vrací nebo nastavuje styl grafu. |
| [getType()](#getType--) | Vrací nebo nastavuje typ grafu. |
| [setType(int value)](#setType-int-) | Vrací nebo nastavuje typ grafu. |
| [getPlotArea()](#getPlotArea--) | Reprezentuje vykreslovací oblast grafu. |
| [getRotation3D()](#getRotation3D--) | Vrací 3D rotaci grafu. |
| [getBackWall()](#getBackWall--) | Vrací objekt, který umožňuje změnit formát zadní stěny 3D grafu. |
| [getSideWall()](#getSideWall--) | Vrací objekt, který umožňuje změnit formát boční stěny 3D grafu. |
| [getFloor()](#getFloor--) | Vrací objekt, který umožňuje změnit formát podlahy 3D grafu. |
| [getTextFormat()](#getTextFormat--) | Vrací textový formát grafu. |
| [createThemeEffective()](#createThemeEffective--) | Vrací efektivní téma pro tento graf. |
| [getThemeManager()](#getThemeManager--) | Vrací správce témat. |
| [getUserShapes()](#getUserShapes--) | Určuje tvary vykreslené nad grafem. |
| [getAxes()](#getAxes--) | Poskytuje přístup k osám grafu. |
| [getShowDataLabelsOverMaximum()](#getShowDataLabelsOverMaximum--) | Určuje, že popisky dat nad maximem grafu se mají zobrazit. |
| [setShowDataLabelsOverMaximum(boolean value)](#setShowDataLabelsOverMaximum-boolean-) | Určuje, že popisky dat nad maximem grafu se mají zobrazit. |
| [hasRoundedCorners()](#hasRoundedCorners--) | Určuje, že oblast grafu má mít zaoblené rohy. |
| [setRoundedCorners(boolean value)](#setRoundedCorners-boolean-) | Určuje, že oblast grafu má mít zaoblené rohy. |
| [getChart()](#getChart--) |  |

### validateChartLayout() {#validateChartLayout--}
```
public final void validateChartLayout()
```

Vypočítá skutečné hodnoty prvků grafu. Skutečné hodnoty zahrnují polohu prvků, které implementují rozhraní IActualLayout (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) a skutečné hodnoty os (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale).

### getPlotVisibleCellsOnly() {#getPlotVisibleCellsOnly--}
```
public final boolean getPlotVisibleCellsOnly()
```

Určuje, zda jsou vykreslovány pouze viditelné buňky. False pro vykreslení jak viditelných, tak skrytých buněk. Čtení/Zápis boolean.

**Vrací:**
boolean
### setPlotVisibleCellsOnly(boolean value) {#setPlotVisibleCellsOnly-boolean-}
```
public final void setPlotVisibleCellsOnly(boolean value)
```

Určuje, zda jsou vykreslovány pouze viditelné buňky. False pro vykreslení jak viditelných, tak skrytých buněk. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getDisplayBlanksAs() {#getDisplayBlanksAs--}
```
public final int getDisplayBlanksAs()
```

Vrací nebo nastavuje způsob, jakým jsou vykreslovány prázdné buňky v grafu. Čtení/Zápis [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Vrací:**
int
### setDisplayBlanksAs(int value) {#setDisplayBlanksAs-int-}
```
public final void setDisplayBlanksAs(int value)
```

Vrací nebo nastavuje způsob, jakým jsou vykreslovány prázdné buňky v grafu. Čtení/Zápis [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getChartData() {#getChartData--}
```
public final IChartData getChartData()
```

Vrací informace o propojených nebo vložených datech souvisejících s grafem. Pouze pro čtení [IChartData](../../com.aspose.slides/ichartdata).

**Vrací:**
[IChartData](../../com.aspose.slides/ichartdata)
### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```

Určuje, zda má graf viditelný název. Čtení/Zápis boolean.

**Vrací:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```

Určuje, zda má graf viditelný název. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getChartTitle() {#getChartTitle--}
```
public final IChartTitle getChartTitle()
```

Vrací nebo nastavuje název grafu. Pouze pro čtení [IChartTitle](../../com.aspose.slides/icharttitle).

**Vrací:**
[IChartTitle](../../com.aspose.slides/icharttitle)
### hasDataTable() {#hasDataTable--}
```
public final boolean hasDataTable()
```

Určuje, zda má graf datovou tabulku. Čtení/Zápis boolean.

**Vrací:**
boolean
### setDataTable(boolean value) {#setDataTable-boolean-}
```
public final void setDataTable(boolean value)
```

Určuje, zda má graf datovou tabulku. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### hasLegend() {#hasLegend--}
```
public final boolean hasLegend()
```

Určuje, zda má graf legendu. Čtení/Zápis boolean.

**Vrací:**
boolean
### setLegend(boolean value) {#setLegend-boolean-}
```
public final void setLegend(boolean value)
```

Určuje, zda má graf legendu. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getLegend() {#getLegend--}
```
public final ILegend getLegend()
```

Vrací nebo nastavuje legendu pro graf. Pouze pro čtení [ILegend](../../com.aspose.slides/ilegend).

**Vrací:**
[ILegend](../../com.aspose.slides/ilegend)
### getChartDataTable() {#getChartDataTable--}
```
public final IDataTable getChartDataTable()
```

Vrací datovou tabulku grafu. Pouze pro čtení [IDataTable](../../com.aspose.slides/idatatable).

**Vrací:**
[IDataTable](../../com.aspose.slides/idatatable)
### getStyle() {#getStyle--}
```
public final int getStyle()
```

Vrací nebo nastavuje styl grafu. Čtení/Zápis [StyleType](../../com.aspose.slides/styletype).

**Vrací:**
int
### setStyle(int value) {#setStyle-int-}
```
public final void setStyle(int value)
```

Vrací nebo nastavuje styl grafu. Čtení/Zápis [StyleType](../../com.aspose.slides/styletype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public final int getType()
```

Vrací nebo nastavuje typ grafu. Čtení/Zápis [ChartType](../../com.aspose.slides/charttype).

**Vrací:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Vrací nebo nastavuje typ grafu. Čtení/Zápis [ChartType](../../com.aspose.slides/charttype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getPlotArea() {#getPlotArea--}
```
public final IChartPlotArea getPlotArea()
```

Reprezentuje vykreslovací oblast grafu. Pouze pro čtení [IChartPlotArea](../../com.aspose.slides/ichartplotarea).

**Vrací:**
[IChartPlotArea](../../com.aspose.slides/ichartplotarea)
### getRotation3D() {#getRotation3D--}
```
public final IRotation3D getRotation3D()
```

Vrací 3D rotaci grafu. Pouze pro čtení [IRotation3D](../../com.aspose.slides/irotation3d).

**Vrací:**
[IRotation3D](../../com.aspose.slides/irotation3d)
### getBackWall() {#getBackWall--}
```
public final IChartWall getBackWall()
```

Vrací objekt, který umožňuje změnit formát zadní stěny 3D grafu. Pouze pro čtení [IChartWall](../../com.aspose.slides/ichartwall).

**Vrací:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getSideWall() {#getSideWall--}
```
public final IChartWall getSideWall()
```

Vrací objekt, který umožňuje změnit formát boční stěny 3D grafu. Pouze pro čtení [IChartWall](../../com.aspose.slides/ichartwall).

**Vrací:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getFloor() {#getFloor--}
```
public final IChartWall getFloor()
```

Vrací objekt, který umožňuje změnit formát podlahy 3D grafu. Pouze pro čtení [IChartWall](../../com.aspose.slides/ichartwall).

**Vrací:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Vrací textový formát grafu. Vlastnost není použita pro následující typy: [ChartType.Treemap](../../com.aspose.slides/charttype\#Treemap), [ChartType.Sunburst](../../com.aspose.slides/charttype\#Sunburst), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel),[ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker). Pouze pro čtení [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Vrací:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

Vrací efektivní téma pro tento graf.

**Vrací:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

Vrací správce témat. Pouze pro čtení [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Vrací:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getUserShapes() {#getUserShapes--}
```
public final IGroupShape getUserShapes()
```

Určuje tvary vykreslené nad grafem. Pouze pro čtení [IGroupShape](../../com.aspose.slides/igroupshape).

**Vrací:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### getAxes() {#getAxes--}
```
public final IAxesManager getAxes()
```

Poskytuje přístup k osám grafu. Pouze pro čtení [IAxesManager](../../com.aspose.slides/iaxesmanager).

**Vrací:**
[IAxesManager](../../com.aspose.slides/iaxesmanager)
### getShowDataLabelsOverMaximum() {#getShowDataLabelsOverMaximum--}
```
public final boolean getShowDataLabelsOverMaximum()
```

Určuje, že popisky dat nad maximem grafu se mají zobrazit. Čtení/Zápis boolean.

**Vrací:**
boolean
### setShowDataLabelsOverMaximum(boolean value) {#setShowDataLabelsOverMaximum-boolean-}
```
public final void setShowDataLabelsOverMaximum(boolean value)
```

Určuje, že popisky dat nad maximem grafu se mají zobrazit. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### hasRoundedCorners() {#hasRoundedCorners--}
```
public final boolean hasRoundedCorners()
```

Určuje, že oblast grafu má mít zaoblené rohy. Čtení/Zápis boolean.

**Vrací:**
boolean
### setRoundedCorners(boolean value) {#setRoundedCorners-boolean-}
```
public final void setRoundedCorners(boolean value)
```

Určuje, že oblast grafu má mít zaoblené rohy. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getChart() {#getChart--}
```
public final IChart getChart()
```

Vrací graf. Pouze pro čtení [IChart](../../com.aspose.slides/ichart).

**Vrací:**
[IChart](../../com.aspose.slides/ichart)