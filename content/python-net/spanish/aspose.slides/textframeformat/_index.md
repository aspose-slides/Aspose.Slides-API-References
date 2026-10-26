---
title: TextFrameFormat class
second_title: Referencia de API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides/textframeformat/
---
## TextFrameFormat clase

Contiene las propiedades formatTextFrameFormatting del TextFrame.

**Herencia:**[`TextFrameFormat`](/slides/python-net/es/aspose.slides/textframeformat) → [`PVIObject`](/slides/python-net/es/aspose.slides/pviobject)

El tipo TextFrameFormat expone los siguientes miembros:

## Constructores

| Constructor | Descripción |
| :- | :- |
| [`__init__(self)`](/slides/python-net/es/aspose.slides/textframeformat/__init__/#) | Inicializa una nueva instancia de la clase [`TextFrameFormat`](/slides/python-net/es/aspose.slides/textframeformat). |

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`three_d_format`](/slides/python-net/es/aspose.slides/textframeformat/three_d_format/) | Devuelve el objeto ThreeDFormat que representa las propiedades de efecto 3d para un texto.<br/>            Solo lectura [`IThreeDFormat`](/slides/python-net/es/aspose.slides/ithreedformat). |
| [`margin_left`](/slides/python-net/es/aspose.slides/textframeformat/margin_left/) | Devuelve o establece el margen izquierdo (puntos) en un TextFrame.<br/>            Lectura/escritura **float**. |
| [`margin_right`](/slides/python-net/es/aspose.slides/textframeformat/margin_right/) | Devuelve o establece el margen derecho (puntos) en un TextFrame.<br/>            Lectura/escritura **float**. |
| [`margin_top`](/slides/python-net/es/aspose.slides/textframeformat/margin_top/) | Devuelve o establece el margen superior (puntos) en un TextFrame.<br/>            Lectura/escritura **float**. |
| [`margin_bottom`](/slides/python-net/es/aspose.slides/textframeformat/margin_bottom/) | Devuelve o establece el margen inferior (puntos) en un TextFrame.<br/>            Lectura/escritura **float**. |
| [`wrap_text`](/slides/python-net/es/aspose.slides/textframeformat/wrap_text/) | **True** si el texto se ajusta a los márgenes del TextFrame.<br/>            Lectura/escritura [`NullableBool`](/slides/python-net/es/aspose.slides/nullablebool). |
| [`anchoring_type`](/slides/python-net/es/aspose.slides/textframeformat/anchoring_type/) | Devuelve o establece el anclaje vertical del texto en un TextFrame.<br/>            Lectura/escritura [`TextAnchorType`](/slides/python-net/es/aspose.slides/textanchortype). |
| [`center_text`](/slides/python-net/es/aspose.slides/textframeformat/center_text/) | Si NullableBool.True entonces el texto debe centrarse horizontalmente en el cuadro.<br/>            Lectura/escritura [`NullableBool`](/slides/python-net/es/aspose.slides/nullablebool). |
| [`text_vertical_type`](/slides/python-net/es/aspose.slides/textframeformat/text_vertical_type/) | Determina la orientación del texto.<br/>            El valor resultante de la rotación visual del texto resumido a partir de esta propiedad y el ángulo personalizado<br/>            en la propiedad RotationAngle.<br/>            Lectura/escritura [`TextVerticalType`](/slides/python-net/es/aspose.slides/textverticaltype). |
| [`autofit_type`](/slides/python-net/es/aspose.slides/textframeformat/autofit_type/) | Devuelve o establece el modo de ajuste automático del texto.<br/>            Lectura/escritura [`TextAutofitType`](/slides/python-net/es/aspose.slides/textautofittype). |
| [`column_count`](/slides/python-net/es/aspose.slides/textframeformat/column_count/) | Devuelve o establece el número de columnas en el área de texto.<br/>            Este valor debe ser un número positivo. De lo contrario, el valor se establecerá en cero.<br/>            El valor 0 significa valor indefinido.<br/>            Lectura/escritura **int**. |
| [`column_spacing`](/slides/python-net/es/aspose.slides/textframeformat/column_spacing/) | Devuelve o establece el espacio entre columnas de texto en el área de texto (en puntos). Esto solo debe aplicarse <br/>            cuando hay más de 1 columna presente.<br/>            Este valor debe ser un número positivo. De lo contrario, el valor se establecerá en cero.<br/>            Lectura/escritura **float**. |
| [`rotation_angle`](/slides/python-net/es/aspose.slides/textframeformat/rotation_angle/) | Especifica la rotación personalizada que se aplica al texto dentro del cuadro delimitador. Si no<br/>            se especifica, se usa la rotación de la forma adjunta. Si se especifica, entonces esto se<br/>            aplica independientemente de la forma. Es decir, la forma puede tener una rotación aplicada<br/>            además de que el propio texto tenga una rotación aplicada a él.<br/>            El valor resultante de la rotación visual del texto resumido a partir de esta propiedad y el tipo<br/>            vertical predefinido en la propiedad TextVerticalType.<br/>            Lectura/escritura **float**. |
| [`transform`](/slides/python-net/es/aspose.slides/textframeformat/transform/) | Obtiene o establece la forma de ajuste del texto.<br/>            Lectura/escritura [`TextShapeType`](/slides/python-net/es/aspose.slides/textshapetype). |
| [`keep_text_flat`](/slides/python-net/es/aspose.slides/textframeformat/keep_text_flat/) | Obtiene o establece mantener el texto plano incluso si se aplicó un efecto de Rotación 3-D.<br/>            Lectura/escritura **bool**. |
| [`slide`](/slides/python-net/es/aspose.slides/textframeformat/slide/) |  |
| [`presentation`](/slides/python-net/es/aspose.slides/textframeformat/presentation/) |  |
| [`text_style`](/slides/python-net/es/aspose.slides/textframeformat/text_style/) |  |

## Métodos

| Método | Descripción |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/es/aspose.slides/textframeformat/get_effective/#) | Obtiene los datos de formato de marco de texto efectivos con la herencia aplicada. |

### Ver también
* clase [`PVIObject`](/slides/python-net/es/aspose.slides/pviobject)
* clase [`TextFrameFormat`](/slides/python-net/es/aspose.slides/textframeformat)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)