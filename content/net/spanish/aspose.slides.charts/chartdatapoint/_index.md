---
title: ChartDataPoint
second_title: Referencia de la API Aspose.Sildes para .NET
description: Representa un punto de datos de la serie.
type: docs
weight: 1330
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
| [ActualHeight](../../aspose.slides.charts/chartdatapoint/actualheight) { get; } | Especifica la altura real del elemento del gráfico. Llame al método IChart.ValidateChartLayout() antes para obtener los valores reales. Lectura Single. |
| [ActualWidth](../../aspose.slides.charts/chartdatapoint/actualwidth) { get; } | Especifica el ancho real del elemento del gráfico. Llame al método IChart.ValidateChartLayout() antes para obtener los valores reales. Lectura Single. |
| [ActualX](../../aspose.slides.charts/chartdatapoint/actualx) { get; } | Especifica la ubicación x real (izquierda) del elemento del gráfico respecto a la esquina superior izquierda del gráfico. Llame al método IChart.ValidateChartLayout() antes para obtener los valores reales. Lectura Single. |
| [ActualY](../../aspose.slides.charts/chartdatapoint/actualy) { get; } | Especifica la parte superior real del elemento del gráfico respecto a la esquina superior izquierda del gráfico. Llame al método IChart.ValidateChartLayout() antes para obtener los valores reales. Lectura Single. |
| [BubbleSize](../../aspose.slides.charts/chartdatapoint/bubblesize) { get; } | BubbleSize. Solo lectura [`IDoubleChartValue`](../idoublechartvalue). |
| [ColorValue](../../aspose.slides.charts/chartdatapoint/colorvalue) { get; } | Devuelve el valor de color del punto de datos del gráfico. Usado con gráficos de mapa. Solo lectura [`IDoubleChartValue`](../idoublechartvalue). |
| [DataPointLevels](../../aspose.slides.charts/chartdatapoint/datapointlevels) { get; } | Devuelve el contenedor de niveles del punto de datos. Aplicado para series Treeamp y Sunburst. La indexación de niveles del punto de datos es basada en cero. |
| [ErrorBarsCustomValues](../../aspose.slides.charts/chartdatapoint/errorbarscustomvalues) { get; } | Representa los valores de barras de error de la serie en caso de tipo de valor Custom. Solo lectura [`IErrorBarsCustomValues`](../ierrorbarscustomvalues). |
| [Explosion](../../aspose.slides.charts/chartdatapoint/explosion) { get; set; } | Especifica la cantidad que el punto de datos debe desplazarse desde el centro del pastel. Lectura/escritura Int32. |
| [Format](../../aspose.slides.charts/chartdatapoint/format) { get; set; } | Representa las propiedades de formato. Lectura/escritura [`IFormat`](../iformat). |
| [Index](../../aspose.slides.charts/chartdatapoint/index) { get; } |  |
| [InvertIfNegative](../../aspose.slides.charts/chartdatapoint/invertifnegative) { get; set; } | Especifica que el punto de datos invertirá sus colores si el valor es negativo. Lectura/escritura Boolean. |
| [IsBubble3D](../../aspose.slides.charts/chartdatapoint/isbubble3d) { get; set; } | Especifica que a las burbujas se les aplica un efecto 3D. Lectura/escritura Boolean. |
| [Label](../../aspose.slides.charts/chartdatapoint/label) { get; } | Etiqueta. Solo lectura [`IDataLabel`](../idatalabel). |
| [Marker](../../aspose.slides.charts/chartdatapoint/marker) { get; } | Especifica un marcador de datos. Solo lectura [`IMarker`](../imarker). |
| [RelatedLegendEntry](../../aspose.slides.charts/chartdatapoint/relatedlegendentry) { get; } | Propiedades de la entrada de leyenda correspondiente en caso de tipo de gráfico de esta lista: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Solo lectura [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SetAsTotal](../../aspose.slides.charts/chartdatapoint/setastotal) { get; set; } | Establece el punto de datos como total. Aplicado solo para el tipo de serie Waterfall. |
| [SizeValue](../../aspose.slides.charts/chartdatapoint/sizevalue) { get; } | Devuelve el valor de tamaño del punto de datos del gráfico. Usado con gráficos Treemap y Sunburst. Solo lectura [`IDoubleChartValue`](../idoublechartvalue). |
| [Value](../../aspose.slides.charts/chartdatapoint/value) { get; } | Valor. Solo lectura [`IDoubleChartValue`](../idoublechartvalue). |
| [XValue](../../aspose.slides.charts/chartdatapoint/xvalue) { get; } | XValue. Solo lectura [`IStringOrDoubleChartValue`](../istringordoublechartvalue). |
| [YValue](../../aspose.slides.charts/chartdatapoint/yvalue) { get; } | YValue. Solo lectura [`IDoubleChartValue`](../idoublechartvalue). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetAutomaticDataPointColor](../../aspose.slides.charts/chartdatapoint/getautomaticdatapointcolor)() | Devuelve un color automático del punto de datos basado en el índice de serie, el índice del punto de datos, la propiedad ParentSeriesGroup.IsColorVaried y el estilo del gráfico. Este color se usa por defecto si FillType es igual a NotDefined. |
| [Remove](../../aspose.slides.charts/chartdatapoint/remove)() | Elimina DataPoint de la serie del gráfico. |

### Ver también

* interfaz [IChartDataPoint](../ichartdatapoint)
* espacio de nombres [Aspose.Slides.Charts](../../aspose.slides.charts)
* ensamblado [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->