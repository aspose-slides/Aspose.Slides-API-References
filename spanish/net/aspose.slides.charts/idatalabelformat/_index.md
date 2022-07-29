---
title: IDataLabelFormat
second_title: Referencia de la API de Aspose.Slides para .NET
description: Representa opciones de formato para DataLabel.
type: docs
weight: 1900
url: /es/net/aspose.slides.charts/idatalabelformat/
---
## IDataLabelFormat interface

Representa opciones de formato para DataLabel.

```csharp
public interface IDataLabelFormat : IFormattedTextContainer
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsIFormattedTextContainer](../../aspose.slides.charts/idatalabelformat/asiformattedtextcontainer) { get; } | Permite obtener la interfaz base IFormattedTextContainer. Solo lectura[`IFormattedTextContainer`](../iformattedtextcontainer) . |
| [Format](../../aspose.slides.charts/idatalabelformat/format) { get; } | Representa el formato de la etiqueta de datos. Solo lectura[`IFormat`](../iformat) . |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/idatalabelformat/isnumberformatlinkedtosource) { get; set; } | Lectura/escrituraBoolean . |
| [NumberFormat](../../aspose.slides.charts/idatalabelformat/numberformat) { get; set; } | Representa la cadena de formato para el objeto DataLabels. Lectura/escrituraString . |
| [Position](../../aspose.slides.charts/idatalabelformat/position) { get; set; } | Representa la posición de la etiqueta de datos. Lectura/escritura[`LegendDataLabelPosition`](../legenddatalabelposition) . |
| [Separator](../../aspose.slides.charts/idatalabelformat/separator) { get; set; } | Establece o devuelve una variante que representa el separador utilizado para las etiquetas de datos en un gráfico. Lectura/escrituraString . |
| [ShowBubbleSize](../../aspose.slides.charts/idatalabelformat/showbubblesize) { get; set; } | Representa el comportamiento de visualización del valor del tamaño de la burbuja de la etiqueta de datos de un gráfico especificado. True muestra el valor del tamaño de la burbuja. Falso para ocultar. Lectura/escrituraBoolean . |
| [ShowCategoryName](../../aspose.slides.charts/idatalabelformat/showcategoryname) { get; set; } | Representa el comportamiento de visualización del nombre de categoría de etiqueta de datos de un gráfico especificado. True para mostrar el nombre de categoría para las etiquetas de datos en un gráfico. Falso para ocultar. Lectura/escrituraBoolean . |
| [ShowLabelAsDataCallout](../../aspose.slides.charts/idatalabelformat/showlabelasdatacallout) { get; set; } | Determina que la etiqueta de datos del gráfico especificado se mostrará como llamada de datos o como etiqueta de datos.  Si el padre de este objeto DataLabelFormat es una colección de etiquetas de datos DataLabelCollection, esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowLabelAsDataCallout para las nuevas etiquetas de datos en la colección DataLabelCollection. Establezca esta propiedad con valor también establece este valor en el Propiedad ShowLabelAsDataCallout para todas las etiquetas de datos en la colección DataLabelCollection (es decir, "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" causa que todas las DataLabels[i].ShowLabelAsDataCallout sean iguales a val). |
| [ShowLabelValueFromCell](../../aspose.slides.charts/idatalabelformat/showlabelvaluefromcell) { get; set; } | Representa el comportamiento de visualización del valor de la celda de la etiqueta de datos de un gráfico especificado. True muestra el valor de la celda. Falso para ocultar. Lectura/escrituraBoolean . |
| [ShowLeaderLines](../../aspose.slides.charts/idatalabelformat/showleaderlines) { get; set; } | Representa el comportamiento de visualización de las líneas directrices de la etiqueta de datos de un gráfico especificado. True muestra las líneas guía. Falso para ocultar. Lectura/escrituraBoolean . |
| [ShowLegendKey](../../aspose.slides.charts/idatalabelformat/showlegendkey) { get; set; } | Representa el comportamiento de visualización de la tecla de leyenda de la etiqueta de datos de un gráfico especificado. Verdadero si la clave de la leyenda de la etiqueta de datos está visible. Lectura/escrituraBoolean . |
| [ShowPercentage](../../aspose.slides.charts/idatalabelformat/showpercentage) { get; set; } | Representa el comportamiento de visualización del valor porcentual de la etiqueta de datos de un gráfico especificado. True muestra el valor porcentual. Falso para ocultar. Lectura/escrituraBoolean . |
| [ShowSeriesName](../../aspose.slides.charts/idatalabelformat/showseriesname) { get; set; } | Devuelve o establece un valor booleano para indicar el comportamiento de visualización del nombre de la serie para las etiquetas de datos en un gráfico. True para mostrar el nombre de la serie. Falso para ocultar. Lectura/escrituraBoolean . |
| [ShowValue](../../aspose.slides.charts/idatalabelformat/showvalue) { get; set; } | Representa el comportamiento de visualización del valor porcentual de la etiqueta de datos de un gráfico especificado. True muestra el valor porcentual. Falso para ocultar. Lectura/escrituraBoolean . |

### Ver también

* interface [IFormattedTextContainer](../iformattedtextcontainer)
* espacio de nombres [Aspose.Slides.Charts](../../aspose.slides.charts)
* asamblea [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
