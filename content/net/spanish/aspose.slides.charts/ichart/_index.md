---
title: IChart
second_title: Referencia de la API de Aspose.Slides para .NET
description: Representa un cuadro gráfico en una diapositiva.
type: docs
weight: 1600
url: /es/aspose.slides.charts/ichart/
---
## IChart interface

Representa un cuadro gráfico en una diapositiva.

```csharp
public interface IChart : IFormattedTextContainer, IGraphicalObject, IOverrideThemeable
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsIFormattedTextContainer](../../aspose.slides.charts/ichart/asiformattedtextcontainer) { get; } | Permite obtener la interfaz base IFormattedTextContainer. Solo lectura[`IFormattedTextContainer`](../iformattedtextcontainer) . |
| [AsIGraphicalObject](../../aspose.slides.charts/ichart/asigraphicalobject) { get; } | Permite obtener la interfaz base IGraphicalObject. Solo lectura[`IGraphicalObject`](../../aspose.slides/igraphicalobject) . |
| [AsIOverrideThemeable](../../aspose.slides.charts/ichart/asioverridethemeable) { get; } | Devuelve la interfaz IOverrideThemeable. Solo lectura[`IOverrideThemeable`](../../aspose.slides.theme/ioverridethemeable) . |
| [Axes](../../aspose.slides.charts/ichart/axes) { get; } | Proporcionar acceso a los ejes del gráfico. Solo lectura[`IAxesManager`](../iaxesmanager) . |
| [BackWall](../../aspose.slides.charts/ichart/backwall) { get; } | Devuelve un objeto que permite cambiar el formato de la pared trasera de un gráfico 3D. Solo lectura[`IChartWall`](../ichartwall) . |
| [ChartData](../../aspose.slides.charts/ichart/chartdata) { get; } | Devuelve información sobre los datos vinculados o incrustados asociados con un gráfico. Solo lectura[`IChartData`](../ichartdata) . |
| [ChartDataTable](../../aspose.slides.charts/ichart/chartdatatable) { get; } | Devuelve una tabla de datos de un gráfico. Solo lectura[`IDataTable`](../idatatable) . |
| [ChartTitle](../../aspose.slides.charts/ichart/charttitle) { get; } | Devuelve o establece un gráfico title Solo lectura[`IChartTitle`](../icharttitle) . |
| [DisplayBlanksAs](../../aspose.slides.charts/ichart/displayblanksas) { get; set; } | Devuelve o establece la forma de trazar celdas en blanco en un gráfico. Lectura/escritura[`DisplayBlanksAsType`](../displayblanksastype) . |
| [Floor](../../aspose.slides.charts/ichart/floor) { get; } | Devuelve un objeto que permite cambiar el formato del piso de un gráfico 3D. Solo lectura[`IChartWall`](../ichartwall) . |
| [HasDataTable](../../aspose.slides.charts/ichart/hasdatatable) { get; set; } | Determina si un gráfico tiene una tabla de datos. Lectura/escrituraBoolean . |
| [HasLegend](../../aspose.slides.charts/ichart/haslegend) { get; set; } | Determina si un gráfico tiene leyenda. Lectura/escrituraBoolean . |
| [HasRoundedCorners](../../aspose.slides.charts/ichart/hasroundedcorners) { get; set; } | Especifica que el área del gráfico tendrá esquinas redondeadas. Lectura/escrituraBoolean . |
| [HasTitle](../../aspose.slides.charts/ichart/hastitle) { get; set; } | Determina si un gráfico tiene un título visible. Lectura/escrituraBoolean . |
| [Legend](../../aspose.slides.charts/ichart/legend) { get; } | Devuelve o establece una leyenda para un gráfico. Solo lectura[`ILegend`](../ilegend) . |
| [PlotArea](../../aspose.slides.charts/ichart/plotarea) { get; } | Representa el área de trazado de un gráfico. Solo lectura[`IChartPlotArea`](../ichartplotarea) . |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/ichart/plotvisiblecellsonly) { get; set; } | Determina si se trazan las únicas celdas visibles. Falso para trazar celdas visibles y ocultas. Lectura/escrituraBoolean . |
| [Rotation3D](../../aspose.slides.charts/ichart/rotation3d) { get; } | Devuelve una rotación 3D de un gráfico. Solo lectura[`IRotation3D`](../irotation3d) . |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/ichart/showdatalabelsovermaximum) { get; set; } | Especifica que se mostrarán etiquetas de datos sobre el máximo del gráfico. Lectura/escrituraBoolean . |
| [SideWall](../../aspose.slides.charts/ichart/sidewall) { get; } | Devuelve un objeto que permite cambiar el formato de la pared lateral de un gráfico 3D. Solo lectura[`IChartWall`](../ichartwall) . |
| [Style](../../aspose.slides.charts/ichart/style) { get; set; } | Devuelve o establece el estilo del gráfico. Lectura/escritura[`StyleType`](../styletype) . |
| [Type](../../aspose.slides.charts/ichart/type) { get; set; } | Devuelve o establece el tipo de gráfico. Lectura/escritura[`ChartType`](../charttype) . |
| [UserShapes](../../aspose.slides.charts/ichart/usershapes) { get; } | Especifique las formas dibujadas en la parte superior del gráfico. Solo lectura[`IGroupShape`](../../aspose.slides/igroupshape) . |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [ValidateChartLayout](../../aspose.slides.charts/ichart/validatechartlayout)() | Calcula los valores reales de los elementos del gráfico. Los valores reales incluyen la posición de los elementos que implementan la interfaz IActualLayout (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) y los valores reales de los ejes (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.Actual MajorUnitScale, IAxis.ActualMinorUnitScale) |

### Ver también

* interface [IFormattedTextContainer](../iformattedtextcontainer)
* interface [IGraphicalObject](../../aspose.slides/igraphicalobject)
* interface [IOverrideThemeable](../../aspose.slides.theme/ioverridethemeable)
* espacio de nombres [Aspose.Slides.Charts](../../aspose.slides.charts)
* asamblea [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
