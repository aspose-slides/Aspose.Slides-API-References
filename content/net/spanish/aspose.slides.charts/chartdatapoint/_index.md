---
title: ChartDataPoint
second_title: Aspose.Sildes para la referencia de API de .NET
description: Representa un punto de datos de la serie.
type: docs
weight: 1340
url: /es/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint clase

Representa un punto de datos de la serie.

```csharp
public class ChartDataPoint : IChartDataPoint
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ActualHeight](../../aspose.slides.charts/chartdatapoint/actualheight) { get; } | Especifica la altura real del elemento del gráfico. Llame al método IChart.ValidateChartLayout() antes para obtener los valores reales. Leer Single. |
| [ActualWidth](../../aspose.slides.charts/chartdatapoint/actualwidth) { get; } | Especifica el ancho real del elemento del gráfico. Llame al método IChart.ValidateChartLayout() antes para obtener los valores reales. Leer Single. |
| [ActualX](../../aspose.slides.charts/chartdatapoint/actualx) { get; } | Especifica la ubicación x real (izquierda) del elemento del gráfico relativa a la esquina superior izquierda del gráfico. Llame al método IChart.ValidateChartLayout() antes para obtener los valores reales. Leer Single. |
| [ActualY](../../aspose.slides.charts/chartdatapoint/actualy) { get; } | Especifica la parte superior real del elemento del gráfico relativa a la esquina superior izquierda del gráfico. Llame al método IChart.ValidateChartLayout() antes para obtener los valores reales. Leer Single. |
| [BubbleSize](../../aspose.slides.charts/chartdatapoint/bubblesize) { get; } | BubbleSize. Solo lectura [`IDoubleChartValue`](../idoublechartvalue). |
| [CachedBubbleSize](../../aspose.slides.charts/chartdatapoint/cachedbubblesize) { get; } | Obtiene el tamaño de burbuja almacenado en caché de un punto de datos del gráfico. Solo lectura [`ICachedChartValue`](../icachedchartvalue). |
| [CachedValue](../../aspose.slides.charts/chartdatapoint/cachedvalue) { get; } | Obtiene el valor almacenado en caché de un punto de datos del gráfico. Solo lectura [`ICachedChartValue`](../icachedchartvalue). |
| [CachedXValue](../../aspose.slides.charts/chartdatapoint/cachedxvalue) { get; } | Obtiene el valor X almacenado en caché de un punto de datos del gráfico. Solo lectura [`ICachedChartValue`](../icachedchartvalue). |
| [CachedYValue](../../aspose.slides.charts/chartdatapoint/cachedyvalue) { get; } | Obtiene el valor Y almacenado en caché de un punto de datos del gráfico. Solo lectura [`ICachedChartValue`](../icachedchartvalue). |
| [ColorValue](../../aspose.slides.charts/chartdatapoint/colorvalue) { get; } | Devuelve el valor de color del punto de datos del gráfico. Usado con gráficos de mapa. Solo lectura [`IDoubleChartValue`](../idoublechartvalue). |
| [DataPointLevels](../../aspose.slides.charts/chartdatapoint/datapointlevels) { get; } | Devuelve el contenedor de los niveles del punto de datos. Aplicado a series Treeamp y Sunburst. La indexación de los niveles del punto de datos comienza en cero. |
| [ErrorBarsCustomValues](../../aspose.slides.charts/chartdatapoint/errorbarscustomvalues) { get; } | Representa los valores de barras de error de la serie en caso de tipo de valor Custom. Solo lectura [`IErrorBarsCustomValues`](../ierrorbarscustomvalues). |
| [Explosion](../../aspose.slides.charts/chartdatapoint/explosion) { get; set; } | Especifica la cantidad que el punto de datos debe desplazarse del centro del pastel. Lectura/escritura Int32. |
| [Format](../../aspose.slides.charts/chartdatapoint/format) { get; set; } | Representa las propiedades de formato. Lectura/escritura [`IFormat`](../iformat). |
| [Index](../../aspose.slides.charts/chartdatapoint/index) { get; } |  |
| [InvertIfNegative](../../aspose.slides.charts/chartdatapoint/invertifnegative) { get; set; } | Especifica que el punto de datos debe invertir sus colores si el valor es negativo. Lectura/escritura Boolean. |
| [IsBubble3D](../../aspose.slides.charts/chartdatapoint/isbubble3d) { get; set; } | Especifica que las burbujas tienen aplicado un efecto 3-D. Lectura/escritura Boolean. |
| [Label](../../aspose.slides.charts/chartdatapoint/label) { get; } | Label. Solo lectura [`IDataLabel`](../idatalabel). |
| [Marker](../../aspose.slides.charts/chartdatapoint/marker) { get; } | Especifica un marcador de datos. Solo lectura [`IMarker`](../imarker). |
| [RelatedLegendEntry](../../aspose.slides.charts/chartdatapoint/relatedlegendentry) { get; } | Propiedades de la entrada de leyenda correspondiente en caso de que el tipo de gráfico sea de esta lista: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Solo lectura [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SetAsTotal](../../aspose.slides.charts/chartdatapoint/setastotal) { get; set; } | Establece el punto de datos como total. Aplicado solo al tipo de serie Waterfall. |
| [SizeValue](../../aspose.slides.charts/chartdatapoint/sizevalue) { get; } | Devuelve el valor de tamaño del punto de datos del gráfico. Usado con gráficos Treemap y Sunburst. Solo lectura [`IDoubleChartValue`](../idoublechartvalue). |
| [Value](../../aspose.slides.charts/chartdatapoint/value) { get; } | Value. Solo lectura [`IDoubleChartValue`](../idoublechartvalue). |
| [XValue](../../aspose.slides.charts/chartdatapoint/xvalue) { get; } | XValue. Solo lectura [`IStringOrDoubleChartValue`](../istringordoublechartvalue). |
| [YValue](../../aspose.slides.charts/chartdatapoint/yvalue) { get; } | YValue. Solo lectura [`IDoubleChartValue`](../idoublechartvalue). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetAutomaticDataPointColor](../../aspose.slides.charts/chartdatapoint/getautomaticdatapointcolor)() | Devuelve un color automático del punto de datos basado en el índice de la serie, el índice del punto de datos, la propiedad ParentSeriesGroup.IsColorVaried y el estilo del gráfico. Este color se usa por defecto si FillType es igual a NotDefined. |
| [Remove](../../aspose.slides.charts/chartdatapoint/remove)() | Elimina DataPoint de la serie del gráfico. |

### Ver también

* interfaz [IChartDataPoint](../ichartdatapoint)
* espacio de nombres [Aspose.Slides.Charts](../../aspose.slides.charts)
* ensamblado [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->