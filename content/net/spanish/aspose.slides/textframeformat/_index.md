---
title: TextFrameFormat
second_title: Referencia de la API de Aspose.Slides para .NET
description: Contiene las propiedades formatTextFrameFormatting de TextFrame.
type: docs
weight: 10150
url: /es/aspose.slides/textframeformat/
---
## TextFrameFormat class

Contiene las propiedades formatTextFrameFormatting de TextFrame.

```csharp
public class TextFrameFormat : PVIObject, IChartTextBlockFormat, ITextFrameFormat
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [TextFrameFormat](textframeformat)() | Inicializa una nueva instancia de[`TextFrameFormat`](../textframeformat) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AnchoringType](../../aspose.slides/textframeformat/anchoringtype) { get; set; } | Devuelve o establece texto ancla vertical en un TextFrameEx. Lectura/escritura[`TextAnchorType`](../textanchortype) . |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Permite obtener la interfaz base IPPresentationComponent. Solo lectura[`IPresentationComponent`](../ipresentationcomponent) . |
| [AutofitType](../../aspose.slides/textframeformat/autofittype) { get; set; } | Devuelve o establece el modo de ajuste automático del texto. Lectura/escritura[`TextAutofitType`](../textautofittype) . |
| [CenterText](../../aspose.slides/textframeformat/centertext) { get; set; } | Si NullableBool.True, el texto debe estar centrado en el cuadro horizontalmente. Lectura/escritura[`NullableBool`](../nullablebool) . |
| [ColumnCount](../../aspose.slides/textframeformat/columncount) { get; set; } | Devuelve o establece el número de columnas en el área de texto. Este valor debe ser un número positivo. De lo contrario, el valor se establecerá en cero. Valor 0 significa valor indefinido. Lectura/escrituraInt32 . |
| [ColumnSpacing](../../aspose.slides/textframeformat/columnspacing) { get; set; } | Devuelve o establece el espacio entre columnas de texto en el área de texto (en puntos). Esto solo debería aplicarse cuando hay más de 1 columna presente. Este valor debe ser un número positivo. De lo contrario, el valor se establecerá en cero. Lectura/escrituraDouble . |
| [KeepTextFlat](../../aspose.slides/textframeformat/keeptextflat) { get; set; } | Obtiene o establece mantener el texto plano incluso si se aplicó un efecto de Rotación 3-D. Lectura/escrituraBoolean . |
| [MarginBottom](../../aspose.slides/textframeformat/marginbottom) { get; set; } | Devuelve o establece el margen inferior (puntos) en un TextFrame. Lectura/escrituraDouble . |
| [MarginLeft](../../aspose.slides/textframeformat/marginleft) { get; set; } | Devuelve o establece el margen izquierdo (puntos) en un TextFrame. Lectura/escrituraDouble . |
| [MarginRight](../../aspose.slides/textframeformat/marginright) { get; set; } | Devuelve o establece el margen derecho (puntos) en un TextFrame. Lectura/escrituraDouble . |
| [MarginTop](../../aspose.slides/textframeformat/margintop) { get; set; } | Devuelve o establece el margen superior (puntos) en un TextFrame. Lectura/escrituraDouble . |
| [RotationAngle](../../aspose.slides/textframeformat/rotationangle) { get; set; } | Especifica la rotación personalizada que se aplica al texto dentro del cuadro delimitador. Si no se especifica , se usa la rotación de la forma adjunta. Si se especifica, se aplica independientemente de la forma. Es decir, a la forma se le puede aplicar una rotación en además del propio texto al que se le ha aplicado una rotación. El valor resultante de la rotación de texto visual se resume a partir de esta propiedad y el tipo vertical predefinido en la propiedad TextVerticalType. Lectura/escrituraSingle . |
| [TextVerticalType](../../aspose.slides/textframeformat/textverticaltype) { get; set; } | Determina la orientación del texto. El valor resultante de la rotación del texto visual resumido a partir de esta propiedad y el ángulo personalizado en la propiedad RotationAngle. Lectura/escritura[`TextVerticalType`](../textverticaltype) . |
| [ThreeDFormat](../../aspose.slides/textframeformat/threedformat) { get; } | Devuelve el objeto ThreeDFormat que representa las propiedades del efecto 3D de un texto. Solo lectura[`IThreeDFormat`](../ithreedformat) . |
| [Transform](../../aspose.slides/textframeformat/transform) { get; set; } | Obtiene o establece la forma de ajuste del texto. Lectura/escritura[`TextShapeType`](../textshapetype) . |
| [WrapText](../../aspose.slides/textframeformat/wraptext) { get; set; } | **Verdadero** si el texto se ajusta a los márgenes de TextFrame. Lectura/escritura[`NullableBool`](../nullablebool) . |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Compara con el objeto especificado. |
| [GetEffective](../../aspose.slides/textframeformat/geteffective)() | Obtiene datos de formato de marco de texto efectivo con la herencia aplicada. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Devuelve el código hash. |

### Ver también

* class [PVIObject](../pviobject)
* interface [IChartTextBlockFormat](../../aspose.slides.charts/icharttextblockformat)
* interface [ITextFrameFormat](../itextframeformat)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* asamblea [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
