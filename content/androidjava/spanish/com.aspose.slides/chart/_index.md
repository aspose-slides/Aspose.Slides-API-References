---
title: Chart
second_title: Referencia de API Java de Aspose.Slides para Android
description: Representa un gráfico en una diapositiva.
type: docs
url: /es/com.aspose.slides/chart/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Todas las interfaces implementadas:**
[com.aspose.slides.IChart](../../com.aspose.slides/ichart)
```
public class Chart extends GraphicalObject implements IChart
```

Representa un gráfico en una diapositiva.
## Métodos

| Método | Descripción |
| --- | --- |
| [validateChartLayout()](#validateChartLayout--) | Calcula los valores reales de los elementos del gráfico. |
| [getPlotVisibleCellsOnly()](#getPlotVisibleCellsOnly--) | Determina si solo se trazan las celdas visibles. |
| [setPlotVisibleCellsOnly(boolean value)](#setPlotVisibleCellsOnly-boolean-) | Determina si solo se trazan las celdas visibles. |
| [getDisplayBlanksAs()](#getDisplayBlanksAs--) | Devuelve o establece la forma de trazar celdas en blanco en un gráfico. |
| [setDisplayBlanksAs(int value)](#setDisplayBlanksAs-int-) | Devuelve o establece la forma de trazar celdas en blanco en un gráfico. |
| [getChartData()](#getChartData--) | Devuelve información sobre los datos vinculados o incrustados asociados a un gráfico. |
| [hasTitle()](#hasTitle--) | Determina si un gráfico tiene un título visible. |
| [setTitle(boolean value)](#setTitle-boolean-) | Determina si un gráfico tiene un título visible. |
| [getChartTitle()](#getChartTitle--) | Devuelve o establece el título de un gráfico. |
| [hasDataTable()](#hasDataTable--) | Determina si un gráfico tiene una tabla de datos. |
| [setDataTable(boolean value)](#setDataTable-boolean-) | Determina si un gráfico tiene una tabla de datos. |
| [hasLegend()](#hasLegend--) | Determina si un gráfico tiene una leyenda. |
| [setLegend(boolean value)](#setLegend-boolean-) | Determina si un gráfico tiene una leyenda. |
| [getLegend()](#getLegend--) | Devuelve o establece una leyenda para un gráfico. |
| [getChartDataTable()](#getChartDataTable--) | Devuelve una tabla de datos de un gráfico. |
| [getStyle()](#getStyle--) | Devuelve o establece el estilo del gráfico. |
| [setStyle(int value)](#setStyle-int-) | Devuelve o establece el estilo del gráfico. |
| [getType()](#getType--) | Devuelve o establece el tipo de gráfico. |
| [setType(int value)](#setType-int-) | Devuelve o establece el tipo de gráfico. |
| [getPlotArea()](#getPlotArea--) | Representa el área de trazado de un gráfico. |
| [getRotation3D()](#getRotation3D--) | Devuelve una rotación 3D de un gráfico. |
| [getBackWall()](#getBackWall--) | Devuelve un objeto que permite cambiar el formato de la pared trasera de un gráfico 3D. |
| [getSideWall()](#getSideWall--) | Devuelve un objeto que permite cambiar el formato de la pared lateral de un gráfico 3D. |
| [getFloor()](#getFloor--) | Devuelve un objeto que permite cambiar el formato del suelo de un gráfico 3D. |
| [getTextFormat()](#getTextFormat--) | Devuelve el formato de texto del gráfico. |
| [createThemeEffective()](#createThemeEffective--) | Devuelve un tema efectivo para este gráfico. |
| [getThemeManager()](#getThemeManager--) | Devuelve el gestor de temas. |
| [getUserShapes()](#getUserShapes--) | Especifica las formas dibujadas sobre el gráfico. |
| [getAxes()](#getAxes--) | Proporciona acceso a los ejes del gráfico. |
| [getShowDataLabelsOverMaximum()](#getShowDataLabelsOverMaximum--) | Especifica que se deben mostrar etiquetas de datos por encima del máximo del gráfico. |
| [setShowDataLabelsOverMaximum(boolean value)](#setShowDataLabelsOverMaximum-boolean-) | Especifica que se deben mostrar etiquetas de datos por encima del máximo del gráfico. |
| [hasRoundedCorners()](#hasRoundedCorners--) | Especifica que el área del gráfico debe tener esquinas redondeadas. |
| [setRoundedCorners(boolean value)](#setRoundedCorners-boolean-) | Especifica que el área del gráfico debe tener esquinas redondeadas. |
| [getChart()](#getChart--) |  |

### validateChartLayout() {#validateChartLayout--}
```
public final void validateChartLayout()
```

Calcula los valores reales de los elementos del gráfico. Los valores reales incluyen la posición de los elementos que implementan la interfaz IActualLayout (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) y los valores reales de los ejes (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale)

### getPlotVisibleCellsOnly() {#getPlotVisibleCellsOnly--}
```
public final boolean getPlotVisibleCellsOnly()
```

Determina si solo se trazan las celdas visibles. False para trazar tanto celdas visibles como ocultas. Lectura/escritura boolean.

**Devuelve:**
boolean
### setPlotVisibleCellsOnly(boolean value) {#setPlotVisibleCellsOnly-boolean-}
```
public final void setPlotVisibleCellsOnly(boolean value)
```

Determina si solo se trazan las celdas visibles. False para trazar tanto celdas visibles como ocultas. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getDisplayBlanksAs() {#getDisplayBlanksAs--}
```
public final int getDisplayBlanksAs()
```

Devuelve o establece la forma de trazar celdas en blanco en un gráfico. Lectura/escritura [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Devuelve:**
int
### setDisplayBlanksAs(int value) {#setDisplayBlanksAs-int-}
```
public final void setDisplayBlanksAs(int value)
```

Devuelve o establece la forma de trazar celdas en blanco en un gráfico. Lectura/escritura [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getChartData() {#getChartData--}
```
public final IChartData getChartData()
```

Devuelve información sobre los datos vinculados o incrustados asociados a un gráfico. Sólo lectura [IChartData](../../com.aspose.slides/ichartdata).

**Devuelve:**
[IChartData](../../com.aspose.slides/ichartdata)
### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```

Determina si un gráfico tiene un título visible. Lectura/escritura boolean.

**Devuelve:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```

Determina si un gráfico tiene un título visible. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getChartTitle() {#getChartTitle--}
```
public final IChartTitle getChartTitle()
```

Devuelve o establece el título de un gráfico. Sólo lectura [IChartTitle](../../com.aspose.slides/icharttitle).

**Devuelve:**
[IChartTitle](../../com.aspose.slides/icharttitle)
### hasDataTable() {#hasDataTable--}
```
public final boolean hasDataTable()
```

Determina si un gráfico tiene una tabla de datos. Lectura/escritura boolean.

**Devuelve:**
boolean
### setDataTable(boolean value) {#setDataTable-boolean-}
```
public final void setDataTable(boolean value)
```

Determina si un gráfico tiene una tabla de datos. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### hasLegend() {#hasLegend--}
```
public final boolean hasLegend()
```

Determina si un gráfico tiene una leyenda. Lectura/escritura boolean.

**Devuelve:**
boolean
### setLegend(boolean value) {#setLegend-boolean-}
```
public final void setLegend(boolean value)
```

Determina si un gráfico tiene una leyenda. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getLegend() {#getLegend--}
```
public final ILegend getLegend()
```

Devuelve o establece una leyenda para un gráfico. Sólo lectura [ILegend](../../com.aspose.slides/ilegend).

**Devuelve:**
[ILegend](../../com.aspose.slides/ilegend)
### getChartDataTable() {#getChartDataTable--}
```
public final IDataTable getChartDataTable()
```

Devuelve una tabla de datos de un gráfico. Sólo lectura [IDataTable](../../com.aspose.slides/idatatable).

**Devuelve:**
[IDataTable](../../com.aspose.slides/idatatable)
### getStyle() {#getStyle--}
```
public final int getStyle()
```

Devuelve o establece el estilo del gráfico. Lectura/escritura [StyleType](../../com.aspose.slides/styletype).

**Devuelve:**
int
### setStyle(int value) {#setStyle-int-}
```
public final void setStyle(int value)
```

Devuelve o establece el estilo del gráfico. Lectura/escritura [StyleType](../../com.aspose.slides/styletype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public final int getType()
```

Devuelve o establece el tipo de gráfico. Lectura/escritura [ChartType](../../com.aspose.slides/charttype).

**Devuelve:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Devuelve o establece el tipo de gráfico. Lectura/escritura [ChartType](../../com.aspose.slides/charttype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getPlotArea() {#getPlotArea--}
```
public final IChartPlotArea getPlotArea()
```

Representa el área de trazado de un gráfico. Sólo lectura [IChartPlotArea](../../com.aspose.slides/ichartplotarea).

**Devuelve:**
[IChartPlotArea](../../com.aspose.slides/ichartplotarea)
### getRotation3D() {#getRotation3D--}
```
public final IRotation3D getRotation3D()
```

Devuelve una rotación 3D de un gráfico. Sólo lectura [IRotation3D](../../com.aspose.slides/irotation3d).

**Devuelve:**
[IRotation3D](../../com.aspose.slides/irotation3d)
### getBackWall() {#getBackWall--}
```
public final IChartWall getBackWall()
```

Devuelve un objeto que permite cambiar el formato de la pared trasera de un gráfico 3D. Sólo lectura [IChartWall](../../com.aspose.slides/ichartwall).

**Devuelve:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getSideWall() {#getSideWall--}
```
public final IChartWall getSideWall()
```

Devuelve un objeto que permite cambiar el formato de la pared lateral de un gráfico 3D. Sólo lectura [IChartWall](../../com.aspose.slides/ichartwall).

**Devuelve:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getFloor() {#getFloor--}
```
public final IChartWall getFloor()
```

Devuelve un objeto que permite cambiar el formato del suelo de un gráfico 3D. Sólo lectura [IChartWall](../../com.aspose.slides/ichartwall).

**Devuelve:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Devuelve el formato de texto del gráfico. La propiedad no es aplicable a los siguientes tipos: [ChartType.Treemap](../../com.aspose.slides/charttype\#Treemap), [ChartType.Sunburst](../../com.aspose.slides/charttype\#Sunburst), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel),[ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker). Sólo lectura [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Devuelve:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

Devuelve un tema efectivo para este gráfico.

**Devuelve:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

Devuelve el gestor de temas. Sólo lectura [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Devuelve:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getUserShapes() {#getUserShapes--}
```
public final IGroupShape getUserShapes()
```

Especifica las formas dibujadas sobre el gráfico. Sólo lectura [IGroupShape](../../com.aspose.slides/igroupshape).

**Devuelve:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### getAxes() {#getAxes--}
```
public final IAxesManager getAxes()
```

Proporciona acceso a los ejes del gráfico. Sólo lectura [IAxesManager](../../com.aspose.slides/iaxesmanager).

**Devuelve:**
[IAxesManager](../../com.aspose.slides/iaxesmanager)
### getShowDataLabelsOverMaximum() {#getShowDataLabelsOverMaximum--}
```
public final boolean getShowDataLabelsOverMaximum()
```

Especifica que se deben mostrar etiquetas de datos por encima del máximo del gráfico. Lectura/escritura boolean.

**Devuelve:**
boolean
### setShowDataLabelsOverMaximum(boolean value) {#setShowDataLabelsOverMaximum-boolean-}
```
public final void setShowDataLabelsOverMaximum(boolean value)
```

Especifica que se deben mostrar etiquetas de datos por encima del máximo del gráfico. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### hasRoundedCorners() {#hasRoundedCorners--}
```
public final boolean hasRoundedCorners()
```

Especifica que el área del gráfico debe tener esquinas redondeadas. Lectura/escritura boolean.

**Devuelve:**
boolean
### setRoundedCorners(boolean value) {#setRoundedCorners-boolean-}
```
public final void setRoundedCorners(boolean value)
```

Especifica que el área del gráfico debe tener esquinas redondeadas. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getChart() {#getChart--}
```
public final IChart getChart()
```

Devuelve el gráfico. Sólo lectura [IChart](../../com.aspose.slides/ichart).

**Devuelve:**
[IChart](../../com.aspose.slides/ichart)