---
title: ITextFrameFormat class
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/itextframeformat/
---
## ITextFrameFormat clase

Contiene las propiedades de formato del TextFrame.

El tipo ITextFrameFormat expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`text_style`](/slides/python-net/es/aspose.slides/itextframeformat/text_style/) | Devuelve el estilo del texto.<br/>            Solo lectura [`ITextStyle`](/slides/python-net/es/aspose.slides/itextstyle). |
| [`margin_left`](/slides/python-net/es/aspose.slides/itextframeformat/margin_left/) | Devuelve o establece el margen izquierdo (puntos) en un TextFrame.<br/>            Lectura/escritura **float**. |
| [`margin_right`](/slides/python-net/es/aspose.slides/itextframeformat/margin_right/) | Devuelve o establece el margen derecho (puntos) en un TextFrame.<br/>            Lectura/escritura **float**. |
| [`margin_top`](/slides/python-net/es/aspose.slides/itextframeformat/margin_top/) | Devuelve o establece el margen superior (puntos) en un TextFrame.<br/>            Lectura/escritura **float**. |
| [`margin_bottom`](/slides/python-net/es/aspose.slides/itextframeformat/margin_bottom/) | Devuelve o establece el margen inferior (puntos) en un TextFrame.<br/>            Lectura/escritura **float**. |
| [`wrap_text`](/slides/python-net/es/aspose.slides/itextframeformat/wrap_text/) | **True**  si el texto se ajusta a los márgenes del TextFrame.<br/>            Lectura/escritura [`NullableBool`](/slides/python-net/es/aspose.slides/nullablebool). |
| [`anchoring_type`](/slides/python-net/es/aspose.slides/itextframeformat/anchoring_type/) | Devuelve o establece el ancla vertical del texto en un TextFrame.<br/>            Lectura/escritura [`TextAnchorType`](/slides/python-net/es/aspose.slides/textanchortype). |
| [`center_text`](/slides/python-net/es/aspose.slides/itextframeformat/center_text/) | Si NullableBool.True, el texto debe centrarse horizontalmente en el cuadro.<br/>            Lectura/escritura [`NullableBool`](/slides/python-net/es/aspose.slides/nullablebool). |
| [`text_vertical_type`](/slides/python-net/es/aspose.slides/itextframeformat/text_vertical_type/) | Determina la orientación del texto.<br/>            El valor resultante de rotación visual del texto resumido a partir de esta propiedad y el ángulo personalizado<br/>            en la propiedad RotationAngle.<br/>            Lectura/escritura [`TextVerticalType`](/slides/python-net/es/aspose.slides/textverticaltype). |
| [`autofit_type`](/slides/python-net/es/aspose.slides/itextframeformat/autofit_type/) | Devuelve o establece el modo de ajuste automático del texto.<br/>            Lectura/escritura [`TextAutofitType`](/slides/python-net/es/aspose.slides/textautofittype). |
| [`column_count`](/slides/python-net/es/aspose.slides/itextframeformat/column_count/) | Devuelve o establece el número de columnas en el área de texto.<br/>            Este valor debe ser un número positivo. De lo contrario, el valor se establecerá en cero.<br/>            Valor 0 significa valor indefinido.<br/>            Lectura/escritura **int**. |
| [`column_spacing`](/slides/python-net/es/aspose.slides/itextframeformat/column_spacing/) | Devuelve o establece el espacio entre columnas de texto en el área de texto (en puntos). Esto solo debe aplicarse <br/>            cuando hay más de 1 columna presente.<br/>            Este valor debe ser un número positivo. De lo contrario, el valor se establecerá en cero.<br/>            Lectura/escritura **float**. |
| [`three_d_format`](/slides/python-net/es/aspose.slides/itextframeformat/three_d_format/) | Devuelve el objeto ThreeDFormat que representa las propiedades de efecto 3D para un texto.<br/>            Solo lectura [`IThreeDFormat`](/slides/python-net/es/aspose.slides/ithreedformat). |
| [`keep_text_flat`](/slides/python-net/es/aspose.slides/itextframeformat/keep_text_flat/) | Devuelve o establece mantener el texto fuera de la escena 3D completamente.<br/>            Lectura/escritura **bool**. |
| [`rotation_angle`](/slides/python-net/es/aspose.slides/itextframeformat/rotation_angle/) | Especifica la rotación personalizada que se aplica al texto dentro del cuadro delimitador. Si no<br/>            se especifica, se usa la rotación de la forma acompañante. Si se especifica, entonces esto se<br/>            aplica independientemente de la forma. Es decir, la forma puede tener una rotación aplicada en<br/>            adición a la rotación del propio texto.<br/>            El valor resultante de rotación visual del texto resumido a partir de esta propiedad y el tipo<br/>            vertical predefinido en la propiedad TextVerticalType.<br/>            Lectura/escritura **float**. |
| [`transform`](/slides/python-net/es/aspose.slides/itextframeformat/transform/) | Obtiene o establece la forma de ajuste de texto.<br/>            Lectura/escritura [`TextShapeType`](/slides/python-net/es/aspose.slides/textshapetype). |

## Métodos

| Método | Descripción |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/es/aspose.slides/itextframeformat/get_effective/#) | Obtiene los datos de formato del marco de texto efectivos con la herencia aplicada. |

### Ver también
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)