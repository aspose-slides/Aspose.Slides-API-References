---
title: DataLabelFormat
second_title: Referencia de la API de Aspose.Slides para .NET
description: Representa opciones de formato para DataLabel.
type: docs
weight: 1430
url: /es/aspose.slides.charts/datalabelformat/
---
## DataLabelFormat class

Representa opciones de formato para DataLabel.

```csharp
public class DataLabelFormat : PVIObject, IDataLabelFormat
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Permite obtener la interfaz base IPPresentationComponent. Solo lectura[`IPresentationComponent`](../../aspose.slides/ipresentationcomponent) . |
| [Chart](../../aspose.slides.charts/datalabelformat/chart) { get; } | Devuelve el gráfico. Solo lectura[`IChart`](../ichart) . |
| [Format](../../aspose.slides.charts/datalabelformat/format) { get; } | Representa el formato de la etiqueta de datos. Solo lectura[`IFormat`](../iformat) . |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/datalabelformat/isnumberformatlinkedtosource) { get; set; } | Lectura/escrituraBoolean . |
| [NumberFormat](../../aspose.slides.charts/datalabelformat/numberformat) { get; set; } | Representa la cadena de formato para el objeto DataLabels. Lectura/escrituraString . |
| [Position](../../aspose.slides.charts/datalabelformat/position) { get; set; } | Representa la posición de la etiqueta de datos. Lectura/escritura[`LegendDataLabelPosition`](../legenddatalabelposition) . |
| [Separator](../../aspose.slides.charts/datalabelformat/separator) { get; set; } | Establece o devuelve una variante que representa el separador utilizado para las etiquetas de datos en un gráfico. Lectura/escrituraString . |
| [ShowBubbleSize](../../aspose.slides.charts/datalabelformat/showbubblesize) { get; set; } | Representa el comportamiento de visualización del valor del tamaño de la burbuja de la etiqueta de datos de un gráfico especificado. True muestra el valor del tamaño de la burbuja. Falso para ocultar. Lectura/escrituraBoolean . |
| [ShowCategoryName](../../aspose.slides.charts/datalabelformat/showcategoryname) { get; set; } | Representa el comportamiento de visualización del nombre de categoría de etiqueta de datos de un gráfico especificado. True para mostrar el nombre de categoría para las etiquetas de datos en un gráfico. Falso para ocultar. Lectura/escrituraBoolean . |
| [ShowLabelAsDataCallout](../../aspose.slides.charts/datalabelformat/showlabelasdatacallout) { get; set; } | Determina que la etiqueta de datos del gráfico especificado se mostrará como llamada de datos o como etiqueta de datos.  Si el padre de este objeto DataLabelFormat es una colección de etiquetas de datos DataLabelCollection, esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowLabelAsDataCallout para las nuevas etiquetas de datos en la colección DataLabelCollection. Establezca esta propiedad con valor también establece este valor en el Propiedad ShowLabelAsDataCallout para todas las etiquetas de datos en la colección DataLabelCollection (es decir, "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" causa que todas las DataLabels[i].ShowLabelAsDataCallout sean iguales a val). |
| [ShowLabelValueFromCell](../../aspose.slides.charts/datalabelformat/showlabelvaluefromcell) { get; set; } | Representa el comportamiento de visualización del valor de la celda de la etiqueta de datos de un gráfico especificado. True muestra el valor de la celda. Falso para ocultar. Lectura/escrituraBoolean . |
| [ShowLeaderLines](../../aspose.slides.charts/datalabelformat/showleaderlines) { get; set; } | Representa el comportamiento de visualización de las líneas directrices de la etiqueta de datos de un gráfico especificado. True muestra las líneas guía. Falso para ocultar. Lectura/escrituraBoolean . |
| [ShowLegendKey](../../aspose.slides.charts/datalabelformat/showlegendkey) { get; set; } | Representa el comportamiento de visualización de la tecla de leyenda de la etiqueta de datos de un gráfico especificado. Verdadero si la clave de la leyenda de la etiqueta de datos está visible. Lectura/escrituraBoolean . |
| [ShowPercentage](../../aspose.slides.charts/datalabelformat/showpercentage) { get; set; } | Representa el comportamiento de visualización del valor porcentual de la etiqueta de datos de un gráfico especificado. True muestra el valor porcentual. Falso para ocultar. Lectura/escrituraBoolean . |
| [ShowSeriesName](../../aspose.slides.charts/datalabelformat/showseriesname) { get; set; } | Devuelve o establece un valor booleano para indicar el comportamiento de visualización del nombre de la serie para las etiquetas de datos en un gráfico. True para mostrar el nombre de la serie. Falso para ocultar. Lectura/escrituraBoolean . |
| [ShowValue](../../aspose.slides.charts/datalabelformat/showvalue) { get; set; } | Representa el comportamiento de visualización del valor porcentual de la etiqueta de datos de un gráfico especificado. True muestra el valor porcentual. Falso para ocultar. Lectura/escrituraBoolean . |
| [TextFormat](../../aspose.slides.charts/datalabelformat/textformat) { get; } | Devuelve el formato de texto del gráfico. Solo lectura[`IChartTextFormat`](../icharttextformat) . |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Compara con el objeto especificado. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Devuelve el código hash. |

### Ver también

* class [PVIObject](../../aspose.slides/pviobject)
* interface [IDataLabelFormat](../idatalabelformat)
* espacio de nombres [Aspose.Slides.Charts](../../aspose.slides.charts)
* asamblea [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
