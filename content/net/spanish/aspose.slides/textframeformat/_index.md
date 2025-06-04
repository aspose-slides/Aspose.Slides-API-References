---
title: TextFrameFormat
second_title: Referencia de API de Aspose.Slides para .NET
description: Contiene las propiedades de formato de TextFrames.
type: docs
weight: 10650
url: /es/aspose.slides/textframeformat/
---

## Clase TextFrameFormat

Contiene las propiedades de formato de TextFrame.

```csharp
public sealed class TextFrameFormat : PVIObject, IChartTextBlockFormat, ITextFrameFormat
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [TextFrameFormat](textframeformat)() | Inicializa una nueva instancia de la clase [`TextFrameFormat`](../textframeformat). |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AnchoringType](../../aspose.slides/textframeformat/anchoringtype) { get; set; } | Devuelve o establece el anclaje vertical del texto en un TextFrame. Lectura/escritura [`TextAnchorType`](../textanchortype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Permite obtener la interfaz base IPresentationComponent. Solo lectura [`IPresentationComponent`](../ipresentationcomponent). |
| [AutofitType](../../aspose.slides/textframeformat/autofittype) { get; set; } | Devuelve o establece el modo de ajuste automático del texto. Lectura/escritura [`TextAutofitType`](../textautofittype). |
| [CenterText](../../aspose.slides/textframeformat/centertext) { get; set; } | Si NullableBool.True, entonces el texto debe estar centrado en la caja horizontalmente. Lectura/escritura [`NullableBool`](../nullablebool). |
| [ColumnCount](../../aspose.slides/textframeformat/columncount) { get; set; } | Devuelve o establece el número de columnas en el área de texto. Este valor debe ser un número positivo. De lo contrario, el valor se establecerá en cero. El valor 0 significa valor no definido. Lectura/escritura Int32. |
| [ColumnSpacing](../../aspose.slides/textframeformat/columnspacing) { get; set; } | Devuelve o establece el espacio entre las columnas de texto en el área de texto (en puntos). Esto solo debe aplicarse cuando haya más de 1 columna presente. Este valor debe ser un número positivo. De lo contrario, el valor se establecerá en cero. Lectura/escritura Double. |
| [KeepTextFlat](../../aspose.slides/textframeformat/keeptextflat) { get; set; } | Obtiene o establece mantener el texto plano incluso si se aplicó un efecto de rotación 3-D. Lectura/escritura Boolean. |
| [MarginBottom](../../aspose.slides/textframeformat/marginbottom) { get; set; } | Devuelve o establece el margen inferior (puntos) en un TextFrame. Lectura/escritura Double. |
| [MarginLeft](../../aspose.slides/textframeformat/marginleft) { get; set; } | Devuelve o establece el margen izquierdo (puntos) en un TextFrame. Lectura/escritura Double. |
| [MarginRight](../../aspose.slides/textframeformat/marginright) { get; set; } | Devuelve o establece el margen derecho (puntos) en un TextFrame. Lectura/escritura Double. |
| [MarginTop](../../aspose.slides/textframeformat/margintop) { get; set; } | Devuelve o establece el margen superior (puntos) en un TextFrame. Lectura/escritura Double. |
| [RotationAngle](../../aspose.slides/textframeformat/rotationangle) { get; set; } | Especifica la rotación personalizada que se está aplicando al texto dentro de la caja delimitadora. Si no se especifica, se usa la rotación de la forma acompañante. Si se especifica, se aplica de manera independiente de la forma. Es decir, la forma puede tener una rotación aplicada además de que el texto en sí tenga una rotación aplicada. El valor resultante de la rotación visual del texto se resume desde esta propiedad y el tipo vertical predefinido en la propiedad TextVerticalType. Lectura/escritura Single. |
| [TextVerticalType](../../aspose.slides/textframeformat/textverticaltype) { get; set; } | Determina la orientación del texto. El valor resultante de la rotación visual del texto se resume desde esta propiedad y el ángulo personalizado en la propiedad RotationAngle. Lectura/escritura [`TextVerticalType`](../textverticaltype). |
| [ThreeDFormat](../../aspose.slides/textframeformat/threedformat) { get; } | Devuelve el objeto ThreeDFormat que representa las propiedades del efecto 3D para un texto. Solo lectura [`IThreeDFormat`](../ithreedformat). |
| [Transform](../../aspose.slides/textframeformat/transform) { get; set; } | Obtiene o establece la forma de ajuste de texto. Lectura/escritura [`TextShapeType`](../textshapetype). |
| [WrapText](../../aspose.slides/textframeformat/wraptext) { get; set; } | **True** si el texto se ajusta a los márgenes de TextFrame. Lectura/escritura [`NullableBool`](../nullablebool). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Compara con el objeto especificado. |
| [GetEffective](../../aspose.slides/textframeformat/geteffective)() | Obtiene los datos de formato de marco de texto efectivos con la herencia aplicada. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Devuelve el código hash. |

### Vea También

* clase [PVIObject](../pviobject)
* interfaz [IChartTextBlockFormat](../../aspose.slides.charts/icharttextblockformat)
* interfaz [ITextFrameFormat](../itextframeformat)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblado [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->