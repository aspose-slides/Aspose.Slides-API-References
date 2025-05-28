---
title: ChartData
second_title: Referencia de la API de Aspose.Slides para .NET
description: Representa datos utilizados para la representación de gráficos.
type: docs
weight: 1230
url: /es/aspose.slides.charts/chartdata/
---

## Clase ChartData

Representa datos utilizados para la representación de gráficos.

```csharp
public class ChartData : DomObject<Chart>, IChartData
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Categories](../../aspose.slides.charts/chartdata/categories) { get; } | Obtiene las categorías primarias (o tanto las categorías primarias como las secundarias si la propiedad [`UseSecondaryCategories`](./usesecondarycategories) es falsa). Solo lectura [`IChartCategoryCollection`](../ichartcategorycollection). |
| [ChartDataWorkbook](../../aspose.slides.charts/chartdata/chartdataworkbook) { get; } | Obtiene la fábrica de celdas para crear celdas utilizadas para series o categorías de gráficos. Solo lectura [`IChartDataWorkbook`](../ichartdataWorkbook). |
| [DataSourceType](../../aspose.slides.charts/chartdata/datasourcetype) { get; } | Representa la ruta del libro de trabajo externo si es una fuente de datos externa, de lo contrario, null |
| [ExternalWorkbookPath](../../aspose.slides.charts/chartdata/externalworkbookpath) { get; } | Representa la fuente de datos del gráfico |
| [SecondaryCategories](../../aspose.slides.charts/chartdata/secondarycategories) { get; } | Obtiene las categorías secundarias si la propiedad [`UseSecondaryCategories`](./usesecondarycategories) es verdadera. Solo lectura [`IChartCategoryCollection`](../ichartcategorycollection). |
| [Series](../../aspose.slides.charts/chartdata/series) { get; } | Obtiene las series. Solo lectura [`IChartSeriesCollection`](../ichartseriescollection). |
| [SeriesGroups](../../aspose.slides.charts/chartdata/seriesgroups) { get; } | Obtiene los grupos de series. Solo lectura [`IChartSeriesGroupCollection`](../ichartseriesgroupcollection). |
| [UseSecondaryCategories](../../aspose.slides.charts/chartdata/usesecondarycategories) { get; set; } | Si es falso, entonces la propiedad [`SecondaryCategories`](./secondarycategories) devuelve null y los datos en la propiedad [`Categories`](./categories) se utilizan tanto para series primarias como secundarias. Si es verdadero, entonces los datos en la propiedad [`SecondaryCategories`](./secondarycategories) se utilizan para las series secundarias y los datos en la propiedad [`Categories`](./categories) se utilizan para las series primarias. Booleano de lectura/escritura. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetRange](../../aspose.slides.charts/chartdata/getrange)() | Obtiene el rango de datos del gráfico. |
| [ReadWorkbookStream](../../aspose.slides.charts/chartdata/readworkbookstream)() | Escribe el libro de trabajo de Excel contenido internamente en un flujo en memoria. |
| [SetExternalWorkbook](../../aspose.slides.charts/chartdata/setexternalworkbook#setexternalworkbook)(string) | Establece el libro de trabajo externo como fuente de datos para el gráfico. Los datos del gráfico se actualizarán desde el libro de trabajo de destino. |
| [SetExternalWorkbook](../../aspose.slides.charts/chartdata/setexternalworkbook#setexternalworkbook_1)(string, bool) | Establece el libro de trabajo externo como fuente de datos para el gráfico. |
| [SetRange](../../aspose.slides.charts/chartdata/setrange)(string) | Establece el rango de datos del gráfico. Las series y categorías se actualizarán en función del nuevo rango de datos. Si la cantidad de series en el rango de datos es mayor que el conteo de series en los datos del gráfico, se agregarán series adicionales del mismo tipo que la última serie en la colección actual al final de la colección. |
| [SwitchRowColumn](../../aspose.slides.charts/chartdata/switchrowcolumn)() | Intercambia los datos sobre el eje. Los datos que se grafican en el eje X se moverán al eje Y y viceversa. |
| [WriteWorkbookStream](../../aspose.slides.charts/chartdata/writeworkbookstream)(MemoryStream) | Inicializa el libro de trabajo de Excel contenido internamente con el valor especificado por el usuario. |

### Véase también

* clase [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)
* clase [Chart](../chart)
* interfaz [IChartData](../ichartdata)
* espacio de nombres [Aspose.Slides.Charts](../../aspose.slides.charts)
* ensamblaje [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->