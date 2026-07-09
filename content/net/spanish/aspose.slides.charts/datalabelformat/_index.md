---
title: DataLabelFormat
second_title: Referencia de API de Aspose.Sildes para .NET
description: Representa opciones de formato para DataLabel.
type: docs
weight: 1570
url: /es/aspose.slides.charts/datalabelformat/
---
## DataLabelFormat clase

Representa opciones de formato para DataLabel.

```csharp
public sealed class DataLabelFormat : PVIObject, IDataLabelFormat
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Permite obtener la interfaz base IPresentationComponent. Solo lectura [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [Chart](../../aspose.slides.charts/datalabelformat/chart) { get; } | Devuelve el gráfico. Solo lectura [`IChart`](../ichart). |
| [Format](../../aspose.slides.charts/datalabelformat/format) { get; } | Representa el formato de la etiqueta de datos. Solo lectura [`IFormat`](../iformat). |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/datalabelformat/isnumberformatlinkedtosource) { get; set; } | Booleano de lectura/escritura. |
| [NumberFormat](../../aspose.slides.charts/datalabelformat/numberformat) { get; set; } | Representa la cadena de formato para el objeto DataLabels. String de lectura/escritura. |
| [Position](../../aspose.slides.charts/datalabelformat/position) { get; set; } | Representa la posición de la etiqueta de datos. Lectura/escritura [`LegendDataLabelPosition`](../legenddatalabelposition). |
| [Separator](../../aspose.slides.charts/datalabelformat/separator) { get; set; } | Establece o devuelve un Variant que representa el separador utilizado para las etiquetas de datos en un gráfico. String de lectura/escritura. |
| [ShowBubbleSize](../../aspose.slides.charts/datalabelformat/showbubblesize) { get; set; } | Representa el comportamiento de visualización del valor del tamaño de la burbuja de la etiqueta de datos de un gráfico especificado. True muestra el valor del tamaño de la burbuja. False lo oculta. Booleano de lectura/escritura. |
| [ShowCategoryName](../../aspose.slides.charts/datalabelformat/showcategoryname) { get; set; } | Representa el comportamiento de visualización del nombre de categoría de la etiqueta de datos de un gráfico especificado. True muestra el nombre de la categoría. False lo oculta. Booleano de lectura/escritura. |
| [ShowLabelAsDataCallout](../../aspose.slides.charts/datalabelformat/showlabelasdatacallout) { get; set; } | Determina si la etiqueta de datos del gráfico especificado se mostrará como llamada de datos o como etiqueta de datos. Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowLabelAsDataCallout para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también establece este valor a la propiedad ShowLabelAsDataCallout para todas las etiquetas de datos en la colección DataLabelCollection (es decir, "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" hace que todas DataLabels[i].ShowLabelAsDataCallout sea igual a val). |
| [ShowLabelValueFromCell](../../aspose.slides.charts/datalabelformat/showlabelvaluefromcell) { get; set; } | Representa el comportamiento de visualización del valor de celda de la etiqueta de datos de un gráfico especificado. True muestra el valor de la celda. False lo oculta. Booleano de lectura/escritura. |
| [ShowLeaderLines](../../aspose.slides.charts/datalabelformat/showleaderlines) { get; set; } | Representa el comportamiento de visualización de las líneas guía de la etiqueta de datos de un gráfico especificado. True muestra las líneas guía. False las oculta. Booleano de lectura/escritura. |
| [ShowLegendKey](../../aspose.slides.charts/datalabelformat/showlegendkey) { get; set; } | Representa el comportamiento de visualización de la clave de leyenda de la etiqueta de datos de un gráfico especificado. True si la clave de leyenda es visible. Booleano de lectura/escritura. |
| [ShowPercentage](../../aspose.slides.charts/datalabelformat/showpercentage) { get; set; } | Representa el comportamiento de visualización del valor porcentaje de la etiqueta de datos de un gráfico especificado. True muestra el valor porcentaje. False lo oculta. Booleano de lectura/escritura. |
| [ShowSeriesName](../../aspose.slides.charts/datalabelformat/showseriesname) { get; set; } | Devuelve o establece un Boolean para indicar el comportamiento de visualización del nombre de serie para las etiquetas de datos en un gráfico. True muestra el nombre de la serie. False lo oculta. Booleano de lectura/escritura. |
| [ShowValue](../../aspose.slides.charts/datalabelformat/showvalue) { get; set; } | Representa el comportamiento de visualización del valor porcentaje de la etiqueta de datos de un gráfico especificado. True muestra el valor porcentaje. False lo oculta. Booleano de lectura/escritura. |
| [TextFormat](../../aspose.slides.charts/datalabelformat/textformat) { get; } | Devuelve el formato de texto del gráfico. Solo lectura [`IChartTextFormat`](../icharttextformat). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Compara con el objeto especificado. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Devuelve el código hash. |

### Ver también

* clase [PVIObject](../../aspose.slides/pviobject)
* interfaz [IDataLabelFormat](../idatalabelformat)
* espacio de nombres [Aspose.Slides.Charts](../../aspose.slides.charts)
* ensamblado [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->