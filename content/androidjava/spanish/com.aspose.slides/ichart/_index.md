---
title: IChart
second_title: Referencia de API Java de Aspose.Slides para Android
description: Representa un gráfico en una diapositiva.
type: docs
url: /es/com.aspose.slides/ichart/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface IChart extends IGraphicalObject, IFormattedTextContainer, IOverrideThemeable
```

Representa un gráfico en una diapositiva.
## Métodos

| Método | Descripción |
| --- | --- |
| [getPlotVisibleCellsOnly()](#getPlotVisibleCellsOnly--) | Determina si solo se trazan las celdas visibles. |
| [setPlotVisibleCellsOnly(boolean value)](#setPlotVisibleCellsOnly-boolean-) | Determina si solo se trazan las celdas visibles. |
| [getDisplayBlanksAs()](#getDisplayBlanksAs--) | Devuelve o establece la forma de trazar celdas vacías en un gráfico. |
| [setDisplayBlanksAs(int value)](#setDisplayBlanksAs-int-) | Devuelve o establece la forma de trazar celdas vacías en un gráfico. |
| [getChartData()](#getChartData--) | Devuelve información sobre los datos vinculados o incrustados asociados a un gráfico. |
| [hasTitle()](#hasTitle--) | Determina si un gráfico tiene un título visible. |
| [setTitle(boolean value)](#setTitle-boolean-) | Determina si un gráfico tiene un título visible. |
| [getChartTitle()](#getChartTitle--) | Devuelve o establece un título de gráfico Solo lectura [IChartTitle](../../com.aspose.slides/icharttitle). |
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
| [getUserShapes()](#getUserShapes--) | Especifica las formas dibujadas sobre el gráfico. |
| [getAxes()](#getAxes--) | Proporciona acceso a los ejes del gráfico. |
| [validateChartLayout()](#validateChartLayout--) | Calcula los valores reales de los elementos del gráfico. |
| [getShowDataLabelsOverMaximum()](#getShowDataLabelsOverMaximum--) | Especifica si se deben mostrar etiquetas de datos por encima del máximo del gráfico. |
| [setShowDataLabelsOverMaximum(boolean value)](#setShowDataLabelsOverMaximum-boolean-) | Especifica si se deben mostrar etiquetas de datos por encima del máximo del gráfico. |
| [hasRoundedCorners()](#hasRoundedCorners--) | Especifica que el área del gráfico debe tener esquinas redondeadas. |
| [setRoundedCorners(boolean value)](#setRoundedCorners-boolean-) | Especifica que el área del gráfico debe tener esquinas redondeadas. |

### getPlotVisibleCellsOnly() {#getPlotVisibleCellsOnly--}
```
public abstract boolean getPlotVisibleCellsOnly()
```

Determina si solo se trazan las celdas visibles. False para trazar tanto celdas visibles como ocultas. Lectura/escritura boolean.

**Devuelve:**
boolean

### setPlotVisibleCellsOnly(boolean value) {#setPlotVisibleCellsOnly-boolean-}
```
public abstract void setPlotVisibleCellsOnly(boolean value)
```

Determina si solo se trazan las celdas visibles. False para trazar tanto celdas visibles como ocultas. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getDisplayBlanksAs() {#getDisplayBlanksAs--}
```
public abstract int getDisplayBlanksAs()
```

Devuelve o establece la forma de trazar celdas vacías en un gráfico. Lectura/escritura [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Devuelve:**
int

### setDisplayBlanksAs(int value) {#setDisplayBlanksAs-int-}
```
public abstract void setDisplayBlanksAs(int value)
```

Devuelve o establece la forma de trazar celdas vacías en un gráfico. Lectura/escritura [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getChartData() {#getChartData--}
```
public abstract IChartData getChartData()
```

Devuelve información sobre los datos vinculados o incrustados asociados a un gráfico. Solo lectura [IChartData](../../com.aspose.slides/ichartdata).

**Devuelve:**
[IChartData](../../com.aspose.slides/ichartdata)

### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

Determina si un gráfico tiene un título visible. Lectura/escritura boolean.

**Devuelve:**
boolean

### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

Determina si un gráfico tiene un título visible. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getChartTitle() {#getChartTitle--}
```
public abstract IChartTitle getChartTitle()
```

Devuelve o establece un título de gráfico Solo lectura [IChartTitle](../../com.aspose.slides/icharttitle).

**Devuelve:**
[IChartTitle](../../com.aspose.slides/icharttitle)

### hasDataTable() {#hasDataTable--}
```
public abstract boolean hasDataTable()
```

Determina si un gráfico tiene una tabla de datos. Lectura/escritura boolean.

**Devuelve:**
boolean

### setDataTable(boolean value) {#setDataTable-boolean-}
```
public abstract void setDataTable(boolean value)
```

Determina si un gráfico tiene una tabla de datos. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### hasLegend() {#hasLegend--}
```
public abstract boolean hasLegend()
```

Determina si un gráfico tiene una leyenda. Lectura/escritura boolean.

**Devuelve:**
boolean

### setLegend(boolean value) {#setLegend-boolean-}
```
public abstract void setLegend(boolean value)
```

Determina si un gráfico tiene una leyenda. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getLegend() {#getLegend--}
```
public abstract ILegend getLegend()
```

Devuelve o establece una leyenda para un gráfico. Solo lectura [ILegend](../../com.aspose.slides/ilegend).

**Devuelve:**
[ILegend](../../com.aspose.slides/ilegend)

### getChartDataTable() {#getChartDataTable--}
```
public abstract IDataTable getChartDataTable()
```

Devuelve una tabla de datos de un gráfico. Solo lectura [IDataTable](../../com.aspose.slides/idatatable).

**Devuelve:**
[IDataTable](../../com.aspose.slides/idatatable)

### getStyle() {#getStyle--}
```
public abstract int getStyle()
```

Devuelve o establece el estilo del gráfico. Lectura/escritura [StyleType](../../com.aspose.slides/styletype).

**Devuelve:**
int

### setStyle(int value) {#setStyle-int-}
```
public abstract void setStyle(int value)
```

Devuelve o establece el estilo del gráfico. Lectura/escritura [StyleType](../../com.aspose.slides/styletype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public abstract int getType()
```

Devuelve o establece el tipo de gráfico. Lectura/escritura [ChartType](../../com.aspose.slides/charttype).

**Devuelve:**
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Devuelve o establece el tipo de gráfico. Lectura/escritura [ChartType](../../com.aspose.slides/charttype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getPlotArea() {#getPlotArea--}
```
public abstract IChartPlotArea getPlotArea()
```

Representa el área de trazado de un gráfico. Solo lectura [IChartPlotArea](../../com.aspose.slides/ichartplotarea).

**Devuelve:**
[IChartPlotArea](../../com.aspose.slides/ichartplotarea)

### getRotation3D() {#getRotation3D--}
```
public abstract IRotation3D getRotation3D()
```

Devuelve una rotación 3D de un gráfico. Solo lectura [IRotation3D](../../com.aspose.slides/irotation3d).

**Devuelve:**
[IRotation3D](../../com.aspose.slides/irotation3d)

### getBackWall() {#getBackWall--}
```
public abstract IChartWall getBackWall()
```

Devuelve un objeto que permite cambiar el formato de la pared trasera de un gráfico 3D. Solo lectura [IChartWall](../../com.aspose.slides/ichartwall).

**Devuelve:**
[IChartWall](../../com.aspose.slides/ichartwall)

### getSideWall() {#getSideWall--}
```
public abstract IChartWall getSideWall()
```

Devuelve un objeto que permite cambiar el formato de la pared lateral de un gráfico 3D. Solo lectura [IChartWall](../../com.aspose.slides/ichartwall).

**Devuelve:**
[IChartWall](../../com.aspose.slides/ichartwall)

### getFloor() {#getFloor--}
```
public abstract IChartWall getFloor()
```

Devuelve un objeto que permite cambiar el formato del suelo de un gráfico 3D. Solo lectura [IChartWall](../../com.aspose.slides/ichartwall).

**Devuelve:**
[IChartWall](../../com.aspose.slides/ichartwall)

### getUserShapes() {#getUserShapes--}
```
public abstract IGroupShape getUserShapes()
```

Especifica las formas dibujadas sobre el gráfico. Solo lectura [IGroupShape](../../com.aspose.slides/igroupshape).

**Devuelve:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### getAxes() {#getAxes--}
```
public abstract IAxesManager getAxes()
```

Proporciona acceso a los ejes del gráfico. Solo lectura [IAxesManager](../../com.aspose.slides/iaxesmanager).

**Devuelve:**
[IAxesManager](../../com.aspose.slides/iaxesmanager)

### validateChartLayout() {#validateChartLayout--}
```
public abstract void validateChartLayout()
```

Calcula los valores reales de los elementos del gráfico. Los valores reales incluyen la posición de los elementos que implementan la interfaz IActualLayout (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) y los valores reales de los ejes (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale)

### getShowDataLabelsOverMaximum() {#getShowDataLabelsOverMaximum--}
```
public abstract boolean getShowDataLabelsOverMaximum()
```

Especifica si se deben mostrar etiquetas de datos por encima del máximo del gráfico. Lectura/escritura boolean.

**Devuelve:**
boolean

### setShowDataLabelsOverMaximum(boolean value) {#setShowDataLabelsOverMaximum-boolean-}
```
public abstract void setShowDataLabelsOverMaximum(boolean value)
```

Especifica si se deben mostrar etiquetas de datos por encima del máximo del gráfico. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### hasRoundedCorners() {#hasRoundedCorners--}
```
public abstract boolean hasRoundedCorners()
```

Especifica si el área del gráfico debe tener esquinas redondeadas. Lectura/escritura boolean.

**Devuelve:**
boolean

### setRoundedCorners(boolean value) {#setRoundedCorners-boolean-}
```
public abstract void setRoundedCorners(boolean value)
```

Especifica si el área del gráfico debe tener esquinas redondeadas. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |