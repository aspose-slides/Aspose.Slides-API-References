---
title: IChartData
second_title: Referencia de la API de Aspose.Slides para .NET
description: Representa los datos utilizados para el trazado de un gráfico.
type: docs
weight: 1660
url: /es/net/aspose.slides.charts/ichartdata/
---
## IChartData interface

Representa los datos utilizados para el trazado de un gráfico.

```csharp
public interface IChartData
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Categories](../../aspose.slides.charts/ichartdata/categories) { get; } | Obtiene las categorías primarias (o las categorías primaria y secundaria si[`UseSecondaryCategories`](./usesecondarycategories) propiedad es falsa). Solo lectura[`IChartCategoryCollection`](../ichartcategorycollection) . |
| [ChartDataWorkbook](../../aspose.slides.charts/ichartdata/chartdataworkbook) { get; } | Obtiene la fábrica de celdas para crear celdas utilizadas para series o categorías de gráficos. Solo lectura[`IChartDataWorkbook`](../ichartdataworkbook) . |
| [DataSourceType](../../aspose.slides.charts/ichartdata/datasourcetype) { get; } | Representa la fuente de datos del gráfico |
| [ExternalWorkbookPath](../../aspose.slides.charts/ichartdata/externalworkbookpath) { get; } | Representa la ruta del libro de trabajo externo si la fuente de datos es externa, nulo de lo contrario |
| [SecondaryCategories](../../aspose.slides.charts/ichartdata/secondarycategories) { get; } | Obtiene las categorías secundarias si[`UseSecondaryCategories`](./usesecondarycategories) la propiedad es verdadera. Solo lectura[`IChartCategoryCollection`](../ichartcategorycollection) . |
| [Series](../../aspose.slides.charts/ichartdata/series) { get; } | Obtiene la serie. Solo lectura[`IChartSeriesCollection`](../ichartseriescollection) . |
| [SeriesGroups](../../aspose.slides.charts/ichartdata/seriesgroups) { get; } | Obtiene los grupos de series. Solo lectura[`IChartSeriesGroupCollection`](../ichartseriesgroupcollection) . |
| [UseSecondaryCategories](../../aspose.slides.charts/ichartdata/usesecondarycategories) { get; set; } | Si es falso entonces[`SecondaryCategories`](./secondarycategories) propiedad devuelve nulo y datos en[`Categories`](./categories) propiedad se usa tanto para la serie primaria como para la secundaria. Si es verdadero, entonces los datos en[`SecondaryCategories`](./secondarycategories) propiedad se utiliza para series secundarias y datos en[`Categories`](./categories)la propiedad se usa para la serie primaria. Lectura/escrituraBoolean . |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetRange](../../aspose.slides.charts/ichartdata/getrange)() | Obtiene el rango de datos del gráfico. |
| [ReadWorkbookStream](../../aspose.slides.charts/ichartdata/readworkbookstream)() | Escribe el libro de Excel contenido internamente en un flujo en memoria. |
| [SetExternalWorkbook](../../aspose.slides.charts/ichartdata/setexternalworkbook#setexternalworkbook)(string) | Establece un libro de trabajo externo como fuente de datos para el gráfico. Los datos del gráfico se actualizarán desde el libro de trabajo de destino. |
| [SetExternalWorkbook](../../aspose.slides.charts/ichartdata/setexternalworkbook#setexternalworkbook_1)(string, bool) | Establece un libro de trabajo externo como fuente de datos para el gráfico. |
| [SetRange](../../aspose.slides.charts/ichartdata/setrange)(string) | Establecer el rango de datos del gráfico. Las series y categorías se actualizarán en función del nuevo rango de datos. Si la cantidad de series en el rango de datos es mayor que el recuento de series en los datos del gráfico, se agregarán al final series adicionales con el mismo tipo como última serie en la colección actual de la colección |
| [SwitchRowColumn](../../aspose.slides.charts/ichartdata/switchrowcolumn)() | Intercambie los datos sobre el eje. Los datos que se grafican en el eje X se moverán al eje Y y viceversa. |
| [WriteWorkbookStream](../../aspose.slides.charts/ichartdata/writeworkbookstream)(MemoryStream) | Inicializa el libro de Excel contenido internamente con el valor especificado por el usuario. |

### Ver también

* espacio de nombres [Aspose.Slides.Charts](../../aspose.slides.charts)
* asamblea [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->