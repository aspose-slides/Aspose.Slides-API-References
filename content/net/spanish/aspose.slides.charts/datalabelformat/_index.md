---
title: DataLabelFormat
second_title: Aspose.Sildes for .NET API Reference
description: Representa las opciones de formato para DataLabel.
type: docs
weight: 1490
url: /es/aspose.slides.charts/datalabelformat/
---

## DataLabelFormat class

Representa las opciones de formato para DataLabel.

```csharp
public sealed class DataLabelFormat : PVIObject, IDataLabelFormat
```

## Properties

| Nombre | Descripción |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Permite obtener la interfaz base IPresentationComponent. Solo lectura [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [Chart](../../aspose.slides.charts/datalabelformat/chart) { get; } | Devuelve el gráfico. Solo lectura [`IChart`](../ichart). |
| [Format](../../aspose.slides.charts/datalabelformat/format) { get; } | Representa el formato de la etiqueta de datos. Solo lectura [`IFormat`](../iformat). |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/datalabelformat/isnumberformatlinkedtosource) { get; set; } | Boolean de lectura/escritura. |
| [NumberFormat](../../aspose.slides.charts/datalabelformat/numberformat) { get; set; } | Representa la cadena de formato para el objeto DataLabels. Lectura/escritura String. |
| [Position](../../aspose.slides.charts/datalabelformat/position) { get; set; } | Representa la posición de la etiqueta de datos. Lectura/escritura [`LegendDataLabelPosition`](../legenddatalabelposition). |
| [Separator](../../aspose.slides.charts/datalabelformat/separator) { get; set; } | Establece o devuelve un Variant que representa el separador utilizado para las etiquetas de datos en un gráfico. Lectura/escritura String. |
| [ShowBubbleSize](../../aspose.slides.charts/datalabelformat/showbubblesize) { get; set; } | Representa el comportamiento de visualización del valor del tamaño de burbuja de la etiqueta de datos de un gráfico específico. Verdadero muestra el valor del tamaño de la burbuja. Falso para ocultar. Lectura/escritura Boolean. |
| [ShowCategoryName](../../aspose.slides.charts/datalabelformat/showcategoryname) { get; set; } | Representa el comportamiento de visualización del nombre de categoría de la etiqueta de datos de un gráfico específico. Verdadero para mostrar el nombre de categoría para las etiquetas de datos en un gráfico. Falso para ocultar. Lectura/escritura Boolean. |
| [ShowLabelAsDataCallout](../../aspose.slides.charts/datalabelformat/showlabelasdatacallout) { get; set; } | Determina si la etiqueta de datos del gráfico especificado se mostrará como un llamado de datos o como una etiqueta de datos. Si el padre de este objeto DataLabelFormat es una colección de etiquetas de datos DataLabelCollection, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowLabelAsDataCallout para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con valor también establece este valor en la propiedad ShowLabelAsDataCallout para todas las etiquetas de datos en la colección DataLabelCollection (es decir, "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" causa que todas las DataLabels[i].ShowLabelAsDataCallout sean iguales a val). |
| [ShowLabelValueFromCell](../../aspose.slides.charts/datalabelformat/showlabelvaluefromcell) { get; set; } | Representa el comportamiento de visualización del valor de la celda de la etiqueta de datos de un gráfico específico. Verdadero muestra el valor de la celda. Falso para ocultar. Lectura/escritura Boolean. |
| [ShowLeaderLines](../../aspose.slides.charts/datalabelformat/showleaderlines) { get; set; } | Representa el comportamiento de visualización de las líneas de líder de la etiqueta de datos de un gráfico específico. Verdadero muestra las líneas de líder. Falso para ocultar. Lectura/escritura Boolean. |
| [ShowLegendKey](../../aspose.slides.charts/datalabelformat/showlegendkey) { get; set; } | Representa el comportamiento de visualización de la clave de leyenda de la etiqueta de datos de un gráfico específico. Verdadero si la clave de leyenda de la etiqueta de datos es visible. Lectura/escritura Boolean. |
| [ShowPercentage](../../aspose.slides.charts/datalabelformat/showpercentage) { get; set; } | Representa el comportamiento de visualización del valor porcentual de la etiqueta de datos de un gráfico específico. Verdadero muestra el valor porcentual. Falso para ocultar. Lectura/escritura Boolean. |
| [ShowSeriesName](../../aspose.slides.charts/datalabelformat/showseriesname) { get; set; } | Devuelve o establece un Boolean para indicar el comportamiento de visualización del nombre de la serie para las etiquetas de datos en un gráfico. Verdadero para mostrar el nombre de la serie. Falso para ocultar. Lectura/escritura Boolean. |
| [ShowValue](../../aspose.slides.charts/datalabelformat/showvalue) { get; set; } | Representa el comportamiento de visualización del valor de la etiqueta de datos de un gráfico específico. Verdadero muestra el valor. Falso para ocultar. Lectura/escritura Boolean. |
| [TextFormat](../../aspose.slides.charts/datalabelformat/textformat) { get; } | Devuelve el formato de texto del gráfico. Solo lectura [`IChartTextFormat`](../icharttextformat). |

## Methods

| Nombre | Descripción |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Compara con el objeto especificado. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Devuelve el código hash. |

### See Also

* class [PVIObject](../../aspose.slides/pviobject)
* interface [IDataLabelFormat](../idatalabelformat)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->