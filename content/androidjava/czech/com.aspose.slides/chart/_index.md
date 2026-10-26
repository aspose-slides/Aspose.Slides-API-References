---
title: Chart
second_title: Aspose.Slides pro Android přes Java API Reference
description: Reprezentuje grafický diagram na snímku.
type: docs
url: /cs/com.aspose.slides/chart/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Všechna implementovaná rozhraní:**
[com.aspose.slides.IChart](../../com.aspose.slides/ichart)
```
public class Chart extends GraphicalObject implements IChart
```

Representuje grafický diagram na snímku.
## Metody

| Metoda | Popis |
| --- | --- |
| [validateChartLayout()](#validateChartLayout--) | Vypočítá skutečné hodnoty prvků diagramu. |
| [getPlotVisibleCellsOnly()](#getPlotVisibleCellsOnly--) | Určuje, zda jsou vykresleny pouze viditelné buňky. |
| [setPlotVisibleCellsOnly(boolean value)](#setPlotVisibleCellsOnly-boolean-) | Určuje, zda jsou vykresleny pouze viditelné buňky. |
| [getDisplayBlanksAs()](#getDisplayBlanksAs--) | Vrací nebo nastavuje způsob vykreslení prázdných buněk v diagramu. |
| [setDisplayBlanksAs(int value)](#setDisplayBlanksAs-int-) | Vrací nebo nastavuje způsob vykreslení prázdných buněk v diagramu. |
| [getChartData()](#getChartData--) | Vrací informace o propojených nebo vložených datech asociovaných s diagramem. |
| [hasTitle()](#hasTitle--) | Určuje, zda má diagram viditelný název. |
| [setTitle(boolean value)](#setTitle-boolean-) | Určuje, zda má diagram viditelný název. |
| [getChartTitle()](#getChartTitle--) | Vrací nebo nastavuje název diagramu. |
| [hasDataTable()](#hasDataTable--) | Určuje, zda má diagram datovou tabulku. |
| [setDataTable(boolean value)](#setDataTable-boolean-) | Určuje, zda má diagram datovou tabulku. |
| [hasLegend()](#hasLegend--) | Určuje, zda má diagram legendu. |
| [setLegend(boolean value)](#setLegend-boolean-) | Určuje, zda má diagram legendu. |
| [getLegend()](#getLegend--) | Vrací nebo nastavuje legendu pro diagram. |
| [getChartDataTable()](#getChartDataTable--) | Vrací datovou tabulku diagramu. |
| [getStyle()](#getStyle--) | Vrací nebo nastavuje styl diagramu. |
| [setStyle(int value)](#setStyle-int-) | Vrací nebo nastavuje styl diagramu. |
| [getType()](#getType--) | Vrací nebo nastavuje typ diagramu. |
| [setType(int value)](#setType-int-) | Vrací nebo nastavuje typ diagramu. |
| [getPlotArea()](#getPlotArea--) | Representuje oblast vykreslování diagramu. |
| [getRotation3D()](#getRotation3D--) | Vrací 3D rotaci diagramu. |
| [getBackWall()](#getBackWall--) | Vrací objekt, který umožňuje změnit formát zadní stěny 3D diagramu. |
| [getSideWall()](#getSideWall--) | Vrací objekt, který umožňuje změnit formát boční stěny 3D diagramu. |
| [getFloor()](#getFloor--) | Vrací objekt, který umožňuje změnit formát podlahy 3D diagramu. |
| [getTextFormat()](#getTextFormat--) | Vrací formát textu diagramu. |
| [createThemeEffective()](#createThemeEffective--) | Vrací efektivní motiv pro tento diagram. |
| [getThemeManager()](#getThemeManager--) | Vrací správce motivů. |
| [getUserShapes()](#getUserShapes--) | Určuje tvary kreslené nad diagramem. |
| [getAxes()](#getAxes--) | Poskytuje přístup k osám diagramu. |
| [getShowDataLabelsOverMaximum()](#getShowDataLabelsOverMaximum--) | Určuje, že popisky dat nad maximem diagramu budou zobrazeny. |
| [setShowDataLabelsOverMaximum(boolean value)](#setShowDataLabelsOverMaximum-boolean-) | Určuje, že popisky dat nad maximem diagramu budou zobrazeny. |
| [hasRoundedCorners()](#hasRoundedCorners--) | Určuje, že oblast diagramu bude mít zaoblené rohy. |
| [setRoundedCorners(boolean value)](#setRoundedCorners-boolean-) | Určuje, že oblast diagramu bude mít zaoblené rohy. |
| [getChart()](#getChart--) |  |

### validateChartLayout() {#validateChartLayout--}
```
public final void validateChartLayout()
```

Vypočítá skutečné hodnoty prvků diagramu. Skutečné hodnoty zahrnují pozice prvků, které implementují rozhraní IActualLayout (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) a skutečné hodnoty os (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale).

### getPlotVisibleCellsOnly() {#getPlotVisibleCellsOnly--}
```
public final boolean getPlotVisibleCellsOnly()
```

Určuje, zda jsou vykresleny pouze viditelné buňky. False pro vykreslení jak viditelných, tak skrytých buněk. Čtení/Zápis boolean.

**Vrací:**
boolean
### setPlotVisibleCellsOnly(boolean value) {#setPlotVisibleCellsOnly-boolean-}
```
public final void setPlotVisibleCellsOnly(boolean value)
```

Určuje, zda jsou vykresleny pouze viditelné buňky. False pro vykreslení jak viditelných, tak skrytých buněk. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getDisplayBlanksAs() {#getDisplayBlanksAs--}
```
public final int getDisplayBlanksAs()
```

Vrací nebo nastavuje způsob vykreslení prázdných buněk v diagramu. Čtení/Zápis [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Vrací:**
int
### setDisplayBlanksAs(int value) {#setDisplayBlanksAs-int-}
```
public final void setDisplayBlanksAs(int value)
```

Vrací nebo nastavuje způsob vykreslení prázdných buněk v diagramu. Čtení/Zápis [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getChartData() {#getChartData--}
```
public final IChartData getChartData()
```

Vrací informace o propojených nebo vložených datech asociovaných s diagramem. Pouze pro čtení [IChartData](../../com.aspose.slides/ichartdata).

**Vrací:**
[IChartData](../../com.aspose.slides/ichartdata)
### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```

Určuje, zda má diagram viditelný název. Čtení/Zápis boolean.

**Vrací:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```

Určuje, zda má diagram viditelný název. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getChartTitle() {#getChartTitle--}
```
public final IChartTitle getChartTitle()
```

Vrací nebo nastavuje název diagramu. Pouze pro čtení [IChartTitle](../../com.aspose.slides/icharttitle).

**Vrací:**
[IChartTitle](../../com.aspose.slides/icharttitle)
### hasDataTable() {#hasDataTable--}
```
public final boolean hasDataTable()
```

Určuje, zda má diagram datovou tabulku. Čtení/Zápis boolean.

**Vrací:**
boolean
### setDataTable(boolean value) {#setDataTable-boolean-}
```
public final void setDataTable(boolean value)
```

Určuje, zda má diagram datovou tabulku. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### hasLegend() {#hasLegend--}
```
public final boolean hasLegend()
```

Určuje, zda má diagram legendu. Čtení/Zápis boolean.

**Vrací:**
boolean
### setLegend(boolean value) {#setLegend-boolean-}
```
public final void setLegend(boolean value)
```

Určuje, zda má diagram legendu. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getLegend() {#getLegend--}
```
public final ILegend getLegend()
```

Vrací nebo nastavuje legendu pro diagram. Pouze pro čtení [ILegend](../../com.aspose.slides/ilegend).

**Vrací:**
[ILegend](../../com.aspose.slides/ilegend)
### getChartDataTable() {#getChartDataTable--}
```
public final IDataTable getChartDataTable()
```

Vrací datovou tabulku diagramu. Pouze pro čtení [IDataTable](../../com.aspose.slides/idatatable).

**Vrací:**
[IDataTable](../../com.aspose.slides/idatatable)
### getStyle() {#getStyle--}
```
public final int getStyle()
```

Vrací nebo nastavuje styl diagramu. Čtení/Zápis [StyleType](../../com.aspose.slides/styletype).

**Vrací:**
int
### setStyle(int value) {#setStyle-int-}
```
public final void setStyle(int value)
```

Vrací nebo nastavuje styl diagramu. Čtení/Zápis [StyleType](../../com.aspose.slides/styletype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public final int getType()
```

Vrací nebo nastavuje typ diagramu. Čtení/Zápis [ChartType](../../com.aspose.slides/charttype).

**Vrací:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Vrací nebo nastavuje typ diagramu. Čtení/Zápis [ChartType](../../com.aspose.slides/charttype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getPlotArea() {#getPlotArea--}
```
public final IChartPlotArea getPlotArea()
```

Representuje oblast vykreslování diagramu. Pouze pro čtení [IChartPlotArea](../../com.aspose.slides/ichartplotarea).

**Vrací:**
[IChartPlotArea](../../com.aspose.slides/ichartplotarea)
### getRotation3D() {#getRotation3D--}
```
public final IRotation3D getRotation3D()
```

Vrací 3D rotaci diagramu. Pouze pro čtení [IRotation3D](../../com.aspose.slides/irotation3d).

**Vrací:**
[IRotation3D](../../com.aspose.slides/irotation3d)
### getBackWall() {#getBackWall--}
```
public final IChartWall getBackWall()
```

Vrací objekt, který umožňuje změnit formát zadní stěny 3D diagramu. Pouze pro čtení [IChartWall](../../com.aspose.slides/ichartwall).

**Vrací:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getSideWall() {#getSideWall--}
```
public final IChartWall getSideWall()
```

Vrací objekt, který umožňuje změnit formát boční stěny 3D diagramu. Pouze pro čtení [IChartWall](../../com.aspose.slides/ichartwall).

**Vrací:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getFloor() {#getFloor--}
```
public final IChartWall getFloor()
```

Vrací objekt, který umožňuje změnit formát podlahy 3D diagramu. Pouze pro čtení [IChartWall](../../com.aspose.slides/ichartwall).

**Vrací:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Vrací formát textu diagramu. Vlastnost není použitelna pro následující typy: [ChartType.Treemap](../../com.aspose.slides/charttype\#Treemap), [ChartType.Sunburst](../../com.aspose.slides/charttype\#Sunburst), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel),[ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker). Pouze pro čtení [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Vrací:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

Vrací efektivní motiv pro tento diagram.

**Vrací:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

Vrací správce motivů. Pouze pro čtení [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Vrací:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getUserShapes() {#getUserShapes--}
```
public final IGroupShape getUserShapes()
```

Určuje tvary kreslené nad diagramem. Pouze pro čtení [IGroupShape](../../com.aspose.slides/igroupshape).

**Vrací:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### getAxes() {#getAxes--}
```
public final IAxesManager getAxes()
```

Poskytuje přístup k osám diagramu. Pouze pro čtení [IAxesManager](../../com.aspose.slides/iaxesmanager).

**Vrací:**
[IAxesManager](../../com.aspose.slides/iaxesmanager)
### getShowDataLabelsOverMaximum() {#getShowDataLabelsOverMaximum--}
```
public final boolean getShowDataLabelsOverMaximum()
```

Určuje, že popisky dat nad maximem diagramu budou zobrazeny. Čtení/Zápis boolean.

**Vrací:**
boolean
### setShowDataLabelsOverMaximum(boolean value) {#setShowDataLabelsOverMaximum-boolean-}
```
public final void setShowDataLabelsOverMaximum(boolean value)
```

Určuje, že popisky dat nad maximem diagramu budou zobrazeny. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### hasRoundedCorners() {#hasRoundedCorners--}
```
public final boolean hasRoundedCorners()
```

Určuje, že oblast diagramu bude mít zaoblené rohy. Čtení/Zápis boolean.

**Vrací:**
boolean
### setRoundedCorners(boolean value) {#setRoundedCorners-boolean-}
```
public final void setRoundedCorners(boolean value)
```

Určuje, že oblast diagramu bude mít zaoblené rohy. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getChart() {#getChart--}
```
public final IChart getChart()
```

Vrací diagram. Pouze pro čtení [IChart](../../com.aspose.slides/ichart).

**Vrací:**
[IChart](../../com.aspose.slides/ichart)