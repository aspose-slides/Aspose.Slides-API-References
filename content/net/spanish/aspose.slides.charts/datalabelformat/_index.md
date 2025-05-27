---
title: DataLabelFormat
second_title: Referencia de API de Aspose.Slides para .NET
description: Representa las opciones de formato para DataLabel.
type: docs
weight: 1490
url: /es/aspose.slides.charts/datalabelformat/
---

## Clase DataLabelFormat

Representa las opciones de formato para DataLabel.

```csharp
public sealed class DataLabelFormat : PVIObject, IDataLabelFormat
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Permite obtener la interfaz base IPresentationComponent. Solo lectura [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [Chart](../../aspose.slides.charts/datalabelformat/chart) { get; } | Devuelve el gráfico. Solo lectura [`IChart`](../ichart). |
| [Format](../../aspose.slides.charts/datalabelformat/format) { get; } | Representa el formato de la etiqueta de datos. Solo lectura [`IFormat`](../iformat). |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/datalabelformat/isnumberformatlinkedtosource) { get; set; } | Boolean de lectura/escritura. |
| [NumberFormat](../../aspose.slides.charts/datalabelformat/numberformat) { get; set; } | Representa la cadena de formato para el objeto DataLabels. Cadena de lectura/escritura. |
| [Position](../../aspose.slides.charts/datalabelformat/position) { get; set; } | Representa la posición de la etiqueta de datos. Lectura/escritura [`LegendDataLabelPosition`](../legenddatalabelposition). |
| [Separator](../../aspose.slides.charts/datalabelformat/separator) { get; set; } | Establece o devuelve un Variant que representa el separador utilizado para las etiquetas de datos en un gráfico. Cadena de lectura/escritura. |
| [ShowBubbleSize](../../aspose.slides.charts/datalabelformat/showbubblesize) { get; set; } | Representa un comportamiento de visualización del valor del tamaño de burbuja de la etiqueta de datos de un gráfico especificado. Verdadero muestra el valor del tamaño de burbuja. Falso para ocultar. Boolean de lectura/escritura. |
| [ShowCategoryName](../../aspose.slides.charts/datalabelformat/showcategoryname) { get; set; } | Representa un comportamiento de visualización del nombre de categoría de la etiqueta de datos de un gráfico especificado. Verdadero para mostrar el nombre de categoría de las etiquetas de datos en un gráfico. Falso para ocultar. Boolean de lectura/escritura. |
| [ShowLabelAsDataCallout](../../aspose.slides.charts/datalabelformat/showlabelasdatacallout) { get; set; } | Determina si la etiqueta de datos de un gráfico especificado se mostrará como un llamado de datos o como una etiqueta de datos.  Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowLabelAsDataCallout para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también establece este valor en la propiedad ShowLabelAsDataCallout para todas las etiquetas de datos en la colección DataLabelCollection (es decir, "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" causa que todas DataLabels[i].ShowLabelAsDataCallout sea igual a val). |
| [ShowLabelValueFromCell](../../aspose.slides.charts/datalabelformat/showlabelvaluefromcell) { get; set; } | Representa un comportamiento de visualización del valor de la celda de la etiqueta de datos de un gráfico especificado. Verdadero muestra el valor de la celda. Falso para ocultar. Boolean de lectura/escritura. |
| [ShowLeaderLines](../../aspose.slides.charts/datalabelformat/showleaderlines) { get; set; } | Representa un comportamiento de visualización de las líneas de líder de la etiqueta de datos de un gráfico especificado. Verdadero muestra las líneas de líder. Falso para ocultar. Boolean de lectura/escritura. |
| [ShowLegendKey](../../aspose.slides.charts/datalabelformat/showlegendkey) { get; set; } | Representa un comportamiento de visualización de la clave de leyenda de la etiqueta de datos de un gráfico especificado. Verdadero si la clave de leyenda de la etiqueta de datos es visible. Boolean de lectura/escritura. |
| [ShowPercentage](../../aspose.slides.charts/datalabelformat/showpercentage) { get; set; } | Representa un comportamiento de visualización del valor porcentual de la etiqueta de datos de un gráfico especificado. Verdadero muestra el valor porcentual. Falso para ocultar. Boolean de lectura/escritura. |
| [ShowSeriesName](../../aspose.slides.charts/datalabelformat/showseriesname) { get; set; } | Devuelve o establece un Boolean para indicar el comportamiento de visualización del nombre de la serie para las etiquetas de datos en un gráfico. Verdadero para mostrar el nombre de la serie. Falso para ocultar. Boolean de lectura/escritura. |
| [ShowValue](../../aspose.slides.charts/datalabelformat/showvalue) { get; set; } | Representa un comportamiento de visualización del valor porcentual de la etiqueta de datos de un gráfico especificado. Verdadero muestra el valor porcentual. Falso para ocultar. Boolean de lectura/escritura. |
| [TextFormat](../../aspose.slides.charts/datalabelformat/textformat) { get; } | Devuelve el formato de texto del gráfico. Solo lectura [`IChartTextFormat`](../icharttextformat). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Compara con el objeto especificado. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Devuelve el código hash. |

### Ver También

* clase [PVIObject](../../aspose.slides/pviobject)
* interfaz [IDataLabelFormat](../idatalabelformat)
* espacio de nombres [Aspose.Slides.Charts](../../aspose.slides.charts)
* ensamblaje [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->