---
title: IChartTextBlockFormat
second_title: Referencia API de Aspose.Slides para .NET
description: Representa las propiedades de formato para los elementos de texto del gráfico.
type: docs
weight: 1900
url: /es/aspose.slides.charts/icharttextblockformat/
---

## Interfaz IChartTextBlockFormat

Representa las propiedades de formato para los elementos de texto del gráfico.

```csharp
public interface IChartTextBlockFormat
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AnchoringType](../../aspose.slides.charts/icharttextblockformat/anchoringtype) { get; set; } | Devuelve o establece el anclaje de texto vertical en un TextFrame. Lectura/escritura [`TextAnchorType`](../../aspose.slides/textanchortype). |
| [AutofitType](../../aspose.slides.charts/icharttextblockformat/autofittype) { get; set; } | Devuelve o establece el modo de ajuste automático del texto. El cambio de esta propiedad puede influir sólo en estas partes del gráfico: DataLabel y DataLabelFormat (soporte completo en PowerPoint 2013; en PowerPoint 2007 no hay efecto para el renderizado). Lectura/escritura [`TextAutofitType`](../../aspose.slides/textautofittype). |
| [CenterText](../../aspose.slides.charts/icharttextblockformat/centertext) { get; set; } | Si NullableBool.True, el texto debe estar centrado en la caja horizontalmente. Lectura/escritura [`NullableBool`](../../aspose.slides/nullablebool). |
| [MarginBottom](../../aspose.slides.charts/icharttextblockformat/marginbottom) { get; set; } | Devuelve o establece el margen inferior (puntos) en un TextFrame. El cambio de esta propiedad puede influir sólo en estas partes del gráfico: DataLabel y DataLabelFormat (soporte completo en PowerPoint 2013; en PowerPoint 2007 no hay efecto para el renderizado). Lectura/escritura Double. |
| [MarginLeft](../../aspose.slides.charts/icharttextblockformat/marginleft) { get; set; } | Devuelve o establece el margen izquierdo (puntos) en un TextFrame. El cambio de esta propiedad puede influir sólo en estas partes del gráfico: DataLabel y DataLabelFormat (soporte completo en PowerPoint 2013; en PowerPoint 2007 no hay efecto para el renderizado). Lectura/escritura Double. |
| [MarginRight](../../aspose.slides.charts/icharttextblockformat/marginright) { get; set; } | Devuelve o establece el margen derecho (puntos) en un TextFrame. El cambio de esta propiedad puede influir sólo en estas partes del gráfico: DataLabel y DataLabelFormat (soporte completo en PowerPoint 2013; en PowerPoint 2007 no hay efecto para el renderizado). Lectura/escritura Double. |
| [MarginTop](../../aspose.slides.charts/icharttextblockformat/margintop) { get; set; } | Devuelve o establece el margen superior (puntos) en un TextFrame. El cambio de esta propiedad puede influir sólo en estas partes del gráfico: DataLabel y DataLabelFormat (soporte completo en PowerPoint 2013; en PowerPoint 2007 no hay efecto para el renderizado). Lectura/escritura Double. |
| [RotationAngle](../../aspose.slides.charts/icharttextblockformat/rotationangle) { get; set; } | Especifica la rotación personalizada que se aplica al texto dentro de la caja delimitadora. Si no se especifica, se utiliza la rotación de la forma acompañante. Si se especifica, se aplica de forma independiente a la forma. Es decir, la forma puede tener una rotación adicional además de que el texto en sí tenga una rotación aplicada. El valor resultante de la rotación visual del texto se resume a partir de esta propiedad y del tipo vertical predefinido en la propiedad TextVerticalType. Lectura/escritura Single. |
| [TextVerticalType](../../aspose.slides.charts/icharttextblockformat/textverticaltype) { get; set; } | Determina la orientación del texto. El valor resultante de la rotación visual del texto se resume a partir de esta propiedad y del ángulo personalizado en la propiedad RotationAngle. Lectura/escritura [`TextVerticalType`](../../aspose.slides/textverticaltype). |
| [WrapText](../../aspose.slides.charts/icharttextblockformat/wraptext) { get; set; } | **True** si el texto se ajusta a los márgenes de TextFrame. El cambio de esta propiedad puede influir sólo en estas partes del gráfico: DataLabel y DataLabelFormat (soporte completo en PowerPoint 2007/2013). Lectura/escritura [`NullableBool`](../../aspose.slides/nullablebool). |

### Véase también

* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- NO EDITES: generado por xmldocmd para Aspose.Slides.dll -->