---
title: ChartDataPoint
second_title: Referencia de la API de Aspose.Slides para .NET
description: Representa el punto de datos de la serie.
type: docs
weight: 1190
url: /es/net/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint class

Representa el punto de datos de la serie.

```csharp
public class ChartDataPoint : IChartDataPoint
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ActualHeight](../../aspose.slides.charts/chartdatapoint/actualheight) { get; } | Especifica la altura real del elemento del gráfico. Llame al método IChart.ValidateChartLayout() antes para obtener los valores reales. LeerSingle . |
| [ActualWidth](../../aspose.slides.charts/chartdatapoint/actualwidth) { get; } | Especifica el ancho real del elemento del gráfico. Llame al método IChart.ValidateChartLayout() antes para obtener los valores reales. LeerSingle . |
| [ActualX](../../aspose.slides.charts/chartdatapoint/actualx) { get; } | Especifica la ubicación x real (izquierda) del elemento del gráfico en relación con la esquina superior izquierda del gráfico. Llame al método IChart.ValidateChartLayout() antes para obtener los valores reales. LeerSingle . |
| [ActualY](../../aspose.slides.charts/chartdatapoint/actualy) { get; } | Especifica la parte superior real del elemento del gráfico en relación con la esquina superior izquierda del gráfico. Llame al método IChart.ValidateChartLayout() antes para obtener los valores reales. LeerSingle . |
| [BubbleSize](../../aspose.slides.charts/chartdatapoint/bubblesize) { get; } | BubbleSize. Solo lectura[`IDoubleChartValue`](../idoublechartvalue) . |
| [ColorValue](../../aspose.slides.charts/chartdatapoint/colorvalue) { get; } | Devuelve el valor de color del punto de datos del gráfico. Se utiliza con gráficos de mapa. Solo lectura[`IDoubleChartValue`](../idoublechartvalue) . |
| [DataPointLevels](../../aspose.slides.charts/chartdatapoint/datapointlevels) { get; } | Devuelve un contenedor de niveles de puntos de datos. Aplicado para las series Treeamp y Sunburst. La indexación de los niveles de puntos de datos se basa en cero. |
| [ErrorBarsCustomValues](../../aspose.slides.charts/chartdatapoint/errorbarscustomvalues) { get; } | Representa valores de barras de error de serie en caso de tipo de valor personalizado. Solo lectura[`IErrorBarsCustomValues`](../ierrorbarscustomvalues) . |
| [Explosion](../../aspose.slides.charts/chartdatapoint/explosion) { get; set; } | Especifica la cantidad que se moverá el punto de datos desde el centro del gráfico circular. Lectura/escrituraInt32 . |
| [Format](../../aspose.slides.charts/chartdatapoint/format) { get; set; } | Representa las propiedades de formato. Lectura/escritura[`IFormat`](../iformat) . |
| [InvertIfNegative](../../aspose.slides.charts/chartdatapoint/invertifnegative) { get; set; } | Especifica que el punto de datos invertirá sus colores si el valor es negativo. Lectura/escrituraBoolean . |
| [IsBubble3D](../../aspose.slides.charts/chartdatapoint/isbubble3d) { get; set; } | Especifica que las burbujas tienen aplicado un efecto 3-D. Lectura/escrituraBoolean . |
| [Label](../../aspose.slides.charts/chartdatapoint/label) { get; } | Etiqueta. Solo lectura[`IDataLabel`](../idatalabel) . |
| [Marker](../../aspose.slides.charts/chartdatapoint/marker) { get; } | Especifica un marcador de datos. Solo lectura[`IMarker`](../imarker) . |
| [RelatedLegendEntry](../../aspose.slides.charts/chartdatapoint/relatedlegendentry) { get; } | Propiedades de la entrada de leyenda correspondiente en caso de tipo de gráfico de esta lista: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Solo lectura[`ILegendEntryProperties`](../ilegendentryproperties) . |
| [SetAsTotal](../../aspose.slides.charts/chartdatapoint/setastotal) { get; set; } | Establece el punto de datos como total. Aplicado solo para el tipo de serie Waterfall. |
| [SizeValue](../../aspose.slides.charts/chartdatapoint/sizevalue) { get; } | Devuelve el valor de tamaño del punto de datos del gráfico. Se utiliza con gráficos Treemap y Sunburst. Solo lectura[`IDoubleChartValue`](../idoublechartvalue) . |
| [Value](../../aspose.slides.charts/chartdatapoint/value) { get; } | Valor. Solo lectura[`IDoubleChartValue`](../idoublechartvalue) . |
| [XValue](../../aspose.slides.charts/chartdatapoint/xvalue) { get; } | XValor. Solo lectura[`IStringOrDoubleChartValue`](../istringordoublechartvalue) . |
| [YValue](../../aspose.slides.charts/chartdatapoint/yvalue) { get; } | YValue. Solo lectura[`IDoubleChartValue`](../idoublechartvalue) . |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetAutomaticDataPointColor](../../aspose.slides.charts/chartdatapoint/getautomaticdatapointcolor)() | Devuelve un color automático del punto de datos basado en el índice de la serie, el índice del punto de datos, la propiedad ParentSeriesGroup.IsColorVaried y el estilo del gráfico. Este color se usa de forma predeterminada si FillType es igual a NotDefined. |
| [Remove](../../aspose.slides.charts/chartdatapoint/remove)() | Elimina DataPoint de la serie de gráficos. |

### Ver también

* interface [IChartDataPoint](../ichartdatapoint)
* espacio de nombres [Aspose.Slides.Charts](../../aspose.slides.charts)
* asamblea [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
