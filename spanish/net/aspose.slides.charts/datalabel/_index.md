---
title: DataLabel
second_title: Referencia de la API de Aspose.Slides para .NET
description: Representa una serie de etiquetas.
type: docs
weight: 1410
url: /es/net/aspose.slides.charts/datalabel/
---
## DataLabel class

Representa una serie de etiquetas.

```csharp
public class DataLabel : IDataLabel
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [DataLabel](datalabel)(IChartDataPoint) | Crea una nueva instancia de la clase DataLabel. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ActualHeight](../../aspose.slides.charts/datalabel/actualheight) { get; } | Especifica la altura real del elemento del gráfico. Llame al método IChart.ValidateChartLayout() antes para obtener los valores reales. LeerSingle . |
| [ActualWidth](../../aspose.slides.charts/datalabel/actualwidth) { get; } | Especifica el ancho real del elemento del gráfico. Llame al método IChart.ValidateChartLayout() antes para obtener los valores reales. LeerSingle . |
| [ActualX](../../aspose.slides.charts/datalabel/actualx) { get; } | Especifica la ubicación x real (izquierda) del elemento del gráfico en relación con la esquina superior izquierda del gráfico. Llame al método IChart.ValidateChartLayout() antes para obtener los valores reales. LeerSingle . |
| [ActualY](../../aspose.slides.charts/datalabel/actualy) { get; } | Especifica la parte superior real del elemento del gráfico en relación con la esquina superior izquierda del gráfico. Llame al método IChart.ValidateChartLayout() antes para obtener los valores reales. LeerSingle . |
| [Bottom](../../aspose.slides.charts/datalabel/bottom) { get; } | Inferior. Solo lecturaSingle . |
| [Chart](../../aspose.slides.charts/datalabel/chart) { get; } | Devuelve el gráfico principal. Solo lectura[`IChart`](../ichart) . |
| [DataLabelFormat](../../aspose.slides.charts/datalabel/datalabelformat) { get; } | Devuelve el formato de la etiqueta de datos. Solo lectura[`IDataLabelFormat`](../idatalabelformat) . |
| [Height](../../aspose.slides.charts/datalabel/height) { get; set; } | Devuelve o establece la altura de un título como una fracción de la altura del gráfico. Lectura/escrituraSingle . |
| [IsVisible](../../aspose.slides.charts/datalabel/isvisible) { get; } | Falso significa que la etiqueta de datos no está visible (por lo que todos los indicadores Mostrar* (ShowValue, ...) son falsos). Solo lecturaBoolean . |
| [Right](../../aspose.slides.charts/datalabel/right) { get; } | Derecha. Solo lecturaSingle . |
| [TextFormat](../../aspose.slides.charts/datalabel/textformat) { get; } | Devuelve formato de texto. Solo lectura[`IChartTextFormat`](../icharttextformat) . |
| [TextFrameForOverriding](../../aspose.slides.charts/datalabel/textframeforoverriding) { get; } | Puede contener un texto con formato enriquecido. Si esta propiedad no es nula, este valor de texto con formato anula el texto generado automáticamente de la etiqueta de datos. El texto generado automáticamente de la etiqueta de datos significa texto administrado por ShowSeriesName, ShowValue, ... propiedades y está formateado con TextFormatManager .Propiedad TextFormat. Solo lectura[`ITextFrame`](../../aspose.slides/itextframe) . |
| [ValueFromCell](../../aspose.slides.charts/datalabel/valuefromcell) { get; set; } | Obtiene o establece la celda de datos del libro. Se aplica si la propiedad IDataLabelFormat.ShowLabelValueFromCell es igual a true. |
| [Width](../../aspose.slides.charts/datalabel/width) { get; set; } | Devuelve o establece el ancho de un título como una fracción del ancho del gráfico. Lectura/escrituraSingle . |
| [X](../../aspose.slides.charts/datalabel/x) { get; set; } | Devuelve o establece la coordenada x de un título como una fracción del ancho del gráfico. Lectura/escrituraSingle . |
| [Y](../../aspose.slides.charts/datalabel/y) { get; set; } | Devuelve o establece la coordenada y de un título como una fracción de la altura del gráfico. Lectura/escrituraSingle . |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddTextFrameForOverriding](../../aspose.slides.charts/datalabel/addtextframeforoverriding)(string) | Inicialice TextFrameForOverriding con el texto en el parámetro "text". Si TextFrameForOverriding ya está inicializado, simplemente cambia su texto. |
| [GetActualLabelText](../../aspose.slides.charts/datalabel/getactuallabeltext)() | Devuelve el texto de la etiqueta real según la configuración de DataLabelFormat o TextFrameForOverriding.Text value. |
| [Hide](../../aspose.slides.charts/datalabel/hide)() | Oculte la etiqueta de datos configurando todos los indicadores Mostrar* (ShowValue, ...) en estado falso. IsVisible será falso después de esto. |

### Ver también

* interface [IDataLabel](../idatalabel)
* espacio de nombres [Aspose.Slides.Charts](../../aspose.slides.charts)
* asamblea [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->