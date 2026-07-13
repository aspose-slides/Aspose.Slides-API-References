---
title: IChart
second_title: Aspose.Slides pro Android prostřednictvím reference Java API
description: Representuje grafický diagram na snímku.
type: docs
url: /cs/com.aspose.slides/ichart/
---
**All Implemented Interfaces:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface IChart extends IGraphicalObject, IFormattedTextContainer, IOverrideThemeable
```

Representuje grafický diagram na snímku.
## Metody

| Metoda | Popis |
| --- | --- |
| [getPlotVisibleCellsOnly()](#getPlotVisibleCellsOnly--) | Určuje, zda jsou vykresleny pouze viditelné buňky. |
| [setPlotVisibleCellsOnly(boolean value)](#setPlotVisibleCellsOnly-boolean-) | Určuje, zda jsou vykresleny pouze viditelné buňky. |
| [getDisplayBlanksAs()](#getDisplayBlanksAs--) | Vrací nebo nastavuje způsob, jak vykreslit prázdné buňky v diagramu. |
| [setDisplayBlanksAs(int value)](#setDisplayBlanksAs-int-) | Vrací nebo nastavuje způsob, jak vykreslit prázdné buňky v diagramu. |
| [getChartData()](#getChartData--) | Vrací informace o propojených nebo vložených datech souvisejících s diagramem. |
| [hasTitle()](#hasTitle--) | Určuje, zda má diagram viditelný název. |
| [setTitle(boolean value)](#setTitle-boolean-) | Určuje, zda má diagram viditelný název. |
| [getChartTitle()](#getChartTitle--) | Vrací nebo nastavuje název diagramu jen pro čtení [IChartTitle](../../com.aspose.slides/icharttitle). |
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
| [getUserShapes()](#getUserShapes--) | Určuje tvary kreslené nad diagramem. |
| [getAxes()](#getAxes--) | Poskytuje přístup k osám diagramu. |
| [validateChartLayout()](#validateChartLayout--) | Vypočítává skutečné hodnoty prvků diagramu. |
| [getShowDataLabelsOverMaximum()](#getShowDataLabelsOverMaximum--) | Určuje, že popisky dat nad maximem diagramu mají být zobrazeny. |
| [setShowDataLabelsOverMaximum(boolean value)](#setShowDataLabelsOverMaximum-boolean-) | Určuje, že popisky dat nad maximem diagramu mají být zobrazeny. |
| [hasRoundedCorners()](#hasRoundedCorners--) | Určuje, že oblast diagramu má mít zaoblené rohy. |
| [setRoundedCorners(boolean value)](#setRoundedCorners-boolean-) | Určuje, že oblast diagramu má mít zaoblené rohy. |
### getPlotVisibleCellsOnly() {#getPlotVisibleCellsOnly--}
```
public abstract boolean getPlotVisibleCellsOnly()
```

Určuje, zda jsou vykresleny pouze viditelné buňky. False to plot both visible and hidden cells. Číst/Zapisovat boolean.

**Vrací:**
boolean
### setPlotVisibleCellsOnly(boolean value) {#setPlotVisibleCellsOnly-boolean-}
```
public abstract void setPlotVisibleCellsOnly(boolean value)
```

Určuje, zda jsou vykresleny pouze viditelné buňky. False to plot both visible and hidden cells. Číst/Zapisovat boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getDisplayBlanksAs() {#getDisplayBlanksAs--}
```
public abstract int getDisplayBlanksAs()
```

Vrací nebo nastavuje způsob, jak vykreslit prázdné buňky v diagramu. Číst/Zapisovat [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Vrací:**
int
### setDisplayBlanksAs(int value) {#setDisplayBlanksAs-int-}
```
public abstract void setDisplayBlanksAs(int value)
```

Vrací nebo nastavuje způsob, jak vykreslit prázdné buňky v diagramu. Číst/Zapisovat [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getChartData() {#getChartData--}
```
public abstract IChartData getChartData()
```

Vrací informace o propojených nebo vložených datech souvisejících s diagramem. Jen pro čtení [IChartData](../../com.aspose.slides/ichartdata).

**Vrací:**
[IChartData](../../com.aspose.slides/ichartdata)
### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

Určuje, zda má diagram viditelný název. Číst/Zapisovat boolean.

**Vrací:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

Určuje, zda má diagram viditelný název. Číst/Zapisovat boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getChartTitle() {#getChartTitle--}
```
public abstract IChartTitle getChartTitle()
```

Vrací nebo nastavuje název diagramu jen pro čtení [IChartTitle](../../com.aspose.slides/icharttitle).

**Vrací:**
[IChartTitle](../../com.aspose.slides/icharttitle)
### hasDataTable() {#hasDataTable--}
```
public abstract boolean hasDataTable()
```

Určuje, zda má diagram datovou tabulku. Číst/Zapisovat boolean.

**Vrací:**
boolean
### setDataTable(boolean value) {#setDataTable-boolean-}
```
public abstract void setDataTable(boolean value)
```

Určuje, zda má diagram datovou tabulku. Číst/Zapisovat boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### hasLegend() {#hasLegend--}
```
public abstract boolean hasLegend()
```

Určuje, zda má diagram legendu. Číst/Zapisovat boolean.

**Vrací:**
boolean
### setLegend(boolean value) {#setLegend-boolean-}
```
public abstract void setLegend(boolean value)
```

Určuje, zda má diagram legendu. Číst/Zapisovat boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getLegend() {#getLegend--}
```
public abstract ILegend getLegend()
```

Vrací nebo nastavuje legendu pro diagram. Jen pro čtení [ILegend](../../com.aspose.slides/ilegend).

**Vrací:**
[ILegend](../../com.aspose.slides/ilegend)
### getChartDataTable() {#getChartDataTable--}
```
public abstract IDataTable getChartDataTable()
```

Vrací datovou tabulku diagramu. Jen pro čtení [IDataTable](../../com.aspose.slides/idatatable).

**Vrací:**
[IDataTable](../../com.aspose.slides/idatatable)
### getStyle() {#getStyle--}
```
public abstract int getStyle()
```

Vrací nebo nastavuje styl diagramu. Číst/Zapisovat [StyleType](../../com.aspose.slides/styletype).

**Vrací:**
int
### setStyle(int value) {#setStyle-int-}
```
public abstract void setStyle(int value)
```

Vrací nebo nastavuje styl diagramu. Číst/Zapisovat [StyleType](../../com.aspose.slides/styletype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public abstract int getType()
```

Vrací nebo nastavuje typ diagramu. Číst/Zapisovat [ChartType](../../com.aspose.slides/charttype).

**Vrací:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Vrací nebo nastavuje typ diagramu. Číst/Zapisovat [ChartType](../../com.aspose.slides/charttype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getPlotArea() {#getPlotArea--}
```
public abstract IChartPlotArea getPlotArea()
```

Representuje oblast vykreslování diagramu. Jen pro čtení [IChartPlotArea](../../com.aspose.slides/ichartplotarea).

**Vrací:**
[IChartPlotArea](../../com.aspose.slides/ichartplotarea)
### getRotation3D() {#getRotation3D--}
```
public abstract IRotation3D getRotation3D()
```

Vrací 3D rotaci diagramu. Jen pro čtení [IRotation3D](../../com.aspose.slides/irotation3d).

**Vrací:**
[IRotation3D](../../com.aspose.slides/irotation3d)
### getBackWall() {#getBackWall--}
```
public abstract IChartWall getBackWall()
```

Vrací objekt, který umožňuje změnit formát zadní stěny 3D diagramu. Jen pro čtení [IChartWall](../../com.aspose.slides/ichartwall).

**Vrací:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getSideWall() {#getSideWall--}
```
public abstract IChartWall getSideWall()
```

Vrací objekt, který umožňuje změnit formát boční stěny 3D diagramu. Jen pro čtení [IChartWall](../../com.aspose.slides/ichartwall).

**Vrací:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getFloor() {#getFloor--}
```
public abstract IChartWall getFloor()
```

Vrací objekt, který umožňuje změnit formát podlahy 3D diagramu. Jen pro čtení [IChartWall](../../com.aspose.slides/ichartwall).

**Vrací:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getUserShapes() {#getUserShapes--}
```
public abstract IGroupShape getUserShapes()
```

Určuje tvary kreslené nad diagramem. Jen pro čtení [IGroupShape](../../com.aspose.slides/igroupshape).

**Vrací:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### getAxes() {#getAxes--}
```
public abstract IAxesManager getAxes()
```

Poskytuje přístup k osám diagramu. Jen pro čtení [IAxesManager](../../com.aspose.slides/iaxesmanager).

**Vrací:**
[IAxesManager](../../com.aspose.slides/iaxesmanager)
### validateChartLayout() {#validateChartLayout--}
```
public abstract void validateChartLayout()
```

Vypočítává skutečné hodnoty prvků diagramu. Skutečné hodnoty zahrnují pozice prvků, které implementují rozhraní IActualLayout (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) a skutečné hodnoty os (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale)

### getShowDataLabelsOverMaximum() {#getShowDataLabelsOverMaximum--}
```
public abstract boolean getShowDataLabelsOverMaximum()
```

Určuje, že popisky dat nad maximem diagramu mají být zobrazeny. Číst/Zapisovat boolean.

**Vrací:**
boolean
### setShowDataLabelsOverMaximum(boolean value) {#setShowDataLabelsOverMaximum-boolean-}
```
public abstract void setShowDataLabelsOverMaximum(boolean value)
```

Určuje, že popisky dat nad maximem diagramu mají být zobrazeny. Číst/Zapisovat boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### hasRoundedCorners() {#hasRoundedCorners--}
```
public abstract boolean hasRoundedCorners()
```

Určuje, že oblast diagramu má mít zaoblené rohy. Číst/Zapisovat boolean.

**Vrací:**
boolean
### setRoundedCorners(boolean value) {#setRoundedCorners-boolean-}
```
public abstract void setRoundedCorners(boolean value)
```

Určuje, že oblast diagramu má mít zaoblené rohy. Číst/Zapisovat boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |