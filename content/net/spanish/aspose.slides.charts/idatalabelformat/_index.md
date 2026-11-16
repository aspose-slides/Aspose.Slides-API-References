---
title: IDataLabelFormat
second_title: Referencia de API de Aspose.Sildes para .NET
description: Representa las opciones de formato para DataLabel.
type: docs
weight: 2060
url: /es/aspose.slides.charts/idatalabelformat/
---
## IDataLabelFormat interfaz

Representa las opciones de formato para DataLabel.

```csharp
public interface IDataLabelFormat : IFormattedTextContainer
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsIFormattedTextContainer](../../aspose.slides.charts/idatalabelformat/asiformattedtextcontainer) { get; } | Permite obtener la interfaz base IFormattedTextContainer. Solo lectura [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [Format](../../aspose.slides.charts/idatalabelformat/format) { get; } | Representa el formato de la etiqueta de datos. Solo lectura [`IFormat`](../iformat). |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/idatalabelformat/isnumberformatlinkedtosource) { get; set; } | Boolean de lectura/escritura. |
| [NumberFormat](../../aspose.slides.charts/idatalabelformat/numberformat) { get; set; } | Representa la cadena de formato para el objeto DataLabels. String de lectura/escritura. |
| [Position](../../aspose.slides.charts/idatalabelformat/position) { get; set; } | Representa la posición de la etiqueta de datos. [`LegendDataLabelPosition`](../legenddatalabelposition) de lectura/escritura. |
| [Separator](../../aspose.slides.charts/idatalabelformat/separator) { get; set; } | Establece o devuelve un Variant que representa el separador usado para las etiquetas de datos en un gráfico. String de lectura/escritura. |
| [ShowBubbleSize](../../aspose.slides.charts/idatalabelformat/showbubblesize) { get; set; } | Representa el comportamiento de visualización del valor del tamaño de burbuja de la etiqueta de datos de un gráfico especificado. True muestra el valor del tamaño de burbuja. False lo oculta. Boolean de lectura/escritura. |
| [ShowCategoryName](../../aspose.slides.charts/idatalabelformat/showcategoryname) { get; set; } | Representa el comportamiento de visualización del nombre de categoría de la etiqueta de datos de un gráfico especificado. True muestra el nombre de categoría para las etiquetas de datos en un gráfico. False lo oculta. Boolean de lectura/escritura. |
| [ShowLabelAsDataCallout](../../aspose.slides.charts/idatalabelformat/showlabelasdatacallout) { get; set; } | Determina si la etiqueta de datos de un gráfico especificado se mostrará como llamada de datos o como etiqueta de datos. Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowLabelAsDataCallout para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también asigna este valor a la propiedad ShowLabelAsDataCallout para todas las etiquetas de datos en la colección DataLabelCollection (p.ej. "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" hace que todos DataLabels[i].ShowLabelAsDataCallout sean iguales a val). |
| [ShowLabelValueFromCell](../../aspose.slides.charts/idatalabelformat/showlabelvaluefromcell) { get; set; } | Representa el comportamiento de visualización del valor de celda de la etiqueta de datos de un gráfico especificado. True muestra el valor de la celda. False lo oculta. Boolean de lectura/escritura. |
| [ShowLeaderLines](../../aspose.slides.charts/idatalabelformat/showleaderlines) { get; set; } | Representa el comportamiento de visualización de las líneas guía de la etiqueta de datos de un gráfico especificado. True muestra las líneas guía. False las oculta. Boolean de lectura/escritura. |
| [ShowLegendKey](../../aspose.slides.charts/idatalabelformat/showlegendkey) { get; set; } | Representa el comportamiento de visualización de la clave de leyenda de la etiqueta de datos de un gráfico especificado. True si la clave de leyenda de la etiqueta de datos es visible. Boolean de lectura/escritura. |
| [ShowPercentage](../../aspose.slides.charts/idatalabelformat/showpercentage) { get; set; } | Representa el comportamiento de visualización del valor de porcentaje de la etiqueta de datos de un gráfico especificado. True muestra el valor de porcentaje. False lo oculta. Boolean de lectura/escritura. |
| [ShowSeriesName](../../aspose.slides.charts/idatalabelformat/showseriesname) { get; set; } | Devuelve o establece un Boolean que indica el comportamiento de visualización del nombre de serie para las etiquetas de datos en un gráfico. True muestra el nombre de serie. False lo oculta. Boolean de lectura/escritura. |
| [ShowValue](../../aspose.slides.charts/idatalabelformat/showvalue) { get; set; } | Representa el comportamiento de visualización del valor de porcentaje de la etiqueta de datos de un gráfico especificado. True muestra el valor de porcentaje. False lo oculta. Boolean de lectura/escritura. |

### Ver también

* interfaz [IFormattedTextContainer](../iformattedtextcontainer)
* espacio de nombres [Aspose.Slides.Charts](../../aspose.slides.charts)
* ensamblado [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->