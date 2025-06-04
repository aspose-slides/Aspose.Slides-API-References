---
title: IDataLabelFormat
second_title: Aspose.Sildes para .NET API Reference
description: Representa opciones de formato para DataLabel.
type: docs
weight: 1960
url: /es/aspose.slides.charts/idatalabelformat/
---

## Interfaz IDataLabelFormat

Representa opciones de formato para DataLabel.

```csharp
public interface IDataLabelFormat : IFormattedTextContainer
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsIFormattedTextContainer](../../aspose.slides.charts/idatalabelformat/asiformattedtextcontainer) { get; } | Permite obtener la interfaz base IFormattedTextContainer. Solo lectura [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [Format](../../aspose.slides.charts/idatalabelformat/format) { get; } | Representa el formato de la etiqueta de datos. Solo lectura [`IFormat`](../iformat). |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/idatalabelformat/isnumberformatlinkedtosource) { get; set; } | Boolean de lectura/escritura. |
| [NumberFormat](../../aspose.slides.charts/idatalabelformat/numberformat) { get; set; } | Representa la cadena de formato para el objeto DataLabels. Cadena de lectura/escritura. |
| [Position](../../aspose.slides.charts/idatalabelformat/position) { get; set; } | Representa la posición de la etiqueta de datos. Lectura/escritura [`LegendDataLabelPosition`](../legenddatalabelposition). |
| [Separator](../../aspose.slides.charts/idatalabelformat/separator) { get; set; } | Establece o devuelve un Variant que representa el separador utilizado para las etiquetas de datos en un gráfico. Cadena de lectura/escritura. |
| [ShowBubbleSize](../../aspose.slides.charts/idatalabelformat/showbubblesize) { get; set; } | Representa el comportamiento de visualización del valor del tamaño de burbuja de la etiqueta de datos de un gráfico especificado. Verdadero muestra el valor del tamaño de burbuja. Falso para ocultar. Boolean de lectura/escritura. |
| [ShowCategoryName](../../aspose.slides.charts/idatalabelformat/showcategoryname) { get; set; } | Representa el comportamiento de visualización del nombre de categoría de la etiqueta de datos de un gráfico especificado. Verdadero para mostrar el nombre de categoría de las etiquetas de datos en un gráfico. Falso para ocultar. Boolean de lectura/escritura. |
| [ShowLabelAsDataCallout](../../aspose.slides.charts/idatalabelformat/showlabelasdatacallout) { get; set; } | Determina si la etiqueta de datos especificada de un gráfico se mostrará como una llamada de datos o como una etiqueta de datos. Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowLabelAsDataCallout para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también establece este valor en la propiedad ShowLabelAsDataCallout para todas las etiquetas de datos en la colección DataLabelCollection (es decir, "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" causará que todas las DataLabels[i].ShowLabelAsDataCallout sean iguales a val). |
| [ShowLabelValueFromCell](../../aspose.slides.charts/idatalabelformat/showlabelvaluefromcell) { get; set; } | Representa el comportamiento de visualización del valor de la celda de la etiqueta de datos de un gráfico especificado. Verdadero muestra el valor de la celda. Falso para ocultar. Boolean de lectura/escritura. |
| [ShowLeaderLines](../../aspose.slides.charts/idatalabelformat/showleaderlines) { get; set; } | Representa el comportamiento de visualización de las líneas líderes de la etiqueta de datos de un gráfico especificado. Verdadero muestra las líneas líderes. Falso para ocultar. Boolean de lectura/escritura. |
| [ShowLegendKey](../../aspose.slides.charts/idatalabelformat/showlegendkey) { get; set; } | Representa el comportamiento de visualización de la clave de leyenda de la etiqueta de datos de un gráfico especificado. Verdadero si la clave de leyenda de la etiqueta de datos es visible. Boolean de lectura/escritura. |
| [ShowPercentage](../../aspose.slides.charts/idatalabelformat/showpercentage) { get; set; } | Representa el comportamiento de visualización del valor porcentual de la etiqueta de datos de un gráfico especificado. Verdadero muestra el valor porcentual. Falso para ocultar. Boolean de lectura/escritura. |
| [ShowSeriesName](../../aspose.slides.charts/idatalabelformat/showseriesname) { get; set; } | Devuelve o establece un Boolean para indicar el comportamiento de visualización del nombre de la serie para las etiquetas de datos en un gráfico. Verdadero para mostrar el nombre de la serie. Falso para ocultar. Boolean de lectura/escritura. |
| [ShowValue](../../aspose.slides.charts/idatalabelformat/showvalue) { get; set; } | Representa el comportamiento de visualización del valor de la etiqueta de datos de un gráfico especificado. Verdadero muestra el valor porcentual. Falso para ocultar. Boolean de lectura/escritura. |

### Vea También

* interfaz [IFormattedTextContainer](../iformattedtextcontainer)
* espacio de nombres [Aspose.Slides.Charts](../../aspose.slides.charts)
* ensamblaje [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->