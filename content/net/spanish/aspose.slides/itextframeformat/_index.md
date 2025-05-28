---
title: ITextFrameFormat
second_title: Referencia de API de Aspose.Slides para .NET
description: Contiene las propiedades de formato de los TextFrames.
type: docs
weight: 7060
url: /es/aspose.slides/itextframeformat/
---

## Interfaz ITextFrameFormat

Contiene las propiedades de formato del TextFrame.

```csharp
public interface ITextFrameFormat
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AnchoringType](../../aspose.slides/itextframeformat/anchoringtype) { get; set; } | Devuelve o establece el ancla vertical del texto en un TextFrame. Lectura/escritura [`TextAnchorType`](../textanchortype). |
| [AutofitType](../../aspose.slides/itextframeformat/autofittype) { get; set; } | Devuelve o establece el modo de ajuste automático del texto. Lectura/escritura [`TextAutofitType`](../textautofittype). |
| [CenterText](../../aspose.slides/itextframeformat/centertext) { get; set; } | Si NullableBool.True, entonces el texto debe estar centrado en el cuadro horizontalmente. Lectura/escritura [`NullableBool`](../nullablebool). |
| [ColumnCount](../../aspose.slides/itextframeformat/columncount) { get; set; } | Devuelve o establece el número de columnas en el área de texto. Este valor debe ser un número positivo. De lo contrario, se establecerá en cero. El valor 0 significa valor indefinido. Lectura/escritura Int32. |
| [ColumnSpacing](../../aspose.slides/itextframeformat/columnspacing) { get; set; } | Devuelve o establece el espacio entre columnas de texto en el área de texto (en puntos). Esto solo debe aplicarse cuando hay más de 1 columna presente. Este valor debe ser un número positivo. De lo contrario, se establecerá en cero. Lectura/escritura Double. |
| [KeepTextFlat](../../aspose.slides/itextframeformat/keeptextflat) { get; set; } | Devuelve o establece si se mantiene el texto fuera de la escena 3D por completo. Lectura/escritura Boolean. |
| [MarginBottom](../../aspose.slides/itextframeformat/marginbottom) { get; set; } | Devuelve o establece el margen inferior (puntos) en un TextFrame. Lectura/escritura Double. |
| [MarginLeft](../../aspose.slides/itextframeformat/marginleft) { get; set; } | Devuelve o establece el margen izquierdo (puntos) en un TextFrame. Lectura/escritura Double. |
| [MarginRight](../../aspose.slides/itextframeformat/marginright) { get; set; } | Devuelve o establece el margen derecho (puntos) en un TextFrame. Lectura/escritura Double. |
| [MarginTop](../../aspose.slides/itextframeformat/margintop) { get; set; } | Devuelve o establece el margen superior (puntos) en un TextFrame. Lectura/escritura Double. |
| [RotationAngle](../../aspose.slides/itextframeformat/rotationangle) { get; set; } | Especifica la rotación personalizada que se aplica al texto dentro del cuadro delimitador. Si no se especifica, se utiliza la rotación de la forma acompañante. Si se especifica, entonces se aplica independientemente de la forma. Es decir, la forma puede tener una rotación aplicada además de que el texto en sí tenga una rotación aplicada. El valor resultante de la rotación visual del texto se resume a partir de esta propiedad y el tipo vertical predefinido en la propiedad TextVerticalType. Lectura/escritura Single. |
| [TextStyle](../../aspose.slides/itextframeformat/textstyle) { get; } | Devuelve el estilo del texto. Solo lectura [`ITextStyle`](../itextstyle). |
| [TextVerticalType](../../aspose.slides/itextframeformat/textverticaltype) { get; set; } | Determina la orientación del texto. El valor resultante de la rotación visual del texto se resume a partir de esta propiedad y el ángulo personalizado en la propiedad RotationAngle. Lectura/escritura [`TextVerticalType`](../textverticaltype). |
| [ThreeDFormat](../../aspose.slides/itextframeformat/threedformat) { get; } | Devuelve el objeto ThreeDFormat que representa las propiedades del efecto 3D para un texto. Solo lectura [`IThreeDFormat`](../ithreedformat). |
| [Transform](../../aspose.slides/itextframeformat/transform) { get; set; } | Obtiene o establece la forma de ajuste del texto. Lectura/escritura [`TextShapeType`](../textshapetype). |
| [WrapText](../../aspose.slides/itextframeformat/wraptext) { get; set; } | **True** si el texto se ajusta a los márgenes del TextFrame. Lectura/escritura [`NullableBool`](../nullablebool). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetEffective](../../aspose.slides/itextframeformat/geteffective)() | Obtiene los datos de formato del marco de texto efectivos con la herencia aplicada. |

### Véase también

* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->