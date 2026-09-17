---
title: ZoomFrame class
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/zoomframe/
---
## ZoomFrame clase

Representa un objeto Slide Zoom en una diapositiva.

**Herencia:**[`ZoomFrame`](/slides/python-net/es/aspose.slides/zoomframe) → [`ZoomObject`](/slides/python-net/es/aspose.slides/zoomobject) → [`GraphicalObject`](/slides/python-net/es/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/es/aspose.slides/shape)

El tipo ZoomFrame expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`is_text_holder`](/slides/python-net/es/aspose.slides/zoomframe/is_text_holder/) | Determina si la forma es TextHolder_PPT.<br/>            Solo lectura **bool**. |
| [`placeholder`](/slides/python-net/es/aspose.slides/zoomframe/placeholder/) | Devuelve el marcador de posición para una forma. Devuelve None si la forma no tiene marcador de posición.<br/>            Solo lectura [`IPlaceholder`](/slides/python-net/es/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/es/aspose.slides/zoomframe/custom_data/) | Devuelve los datos personalizados de la forma.<br/>            Solo lectura [`ICustomData`](/slides/python-net/es/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/es/aspose.slides/zoomframe/raw_frame/) | Devuelve o establece las propiedades del marco de forma sin procesar.<br/>            Lectura/escritura [`IShapeFrame`](/slides/python-net/es/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/es/aspose.slides/zoomframe/frame/) | Devuelve o establece las propiedades del marco de forma.<br/>            Lectura/escritura [`IShapeFrame`](/slides/python-net/es/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/es/aspose.slides/zoomframe/line_format/) | Devuelve el objeto LineFormat que contiene las propiedades de formato de línea para una forma.<br/>            Nota: puede devolver None para ciertos tipos de formas que no tienen propiedades de línea.<br/>            Solo lectura [`ILineFormat`](/slides/python-net/es/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/es/aspose.slides/zoomframe/three_d_format/) | Devuelve el objeto ThreeDFormat que contiene las propiedades de efecto 3D para una forma.<br/>            Nota: puede devolver None para ciertos tipos de formas que no tienen propiedades 3D.<br/>            Solo lectura [`IThreeDFormat`](/slides/python-net/es/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/es/aspose.slides/zoomframe/effect_format/) | Devuelve el objeto EffectFormat que contiene los efectos de píxel aplicados a una forma.<br/>            Nota: puede devolver None para ciertos tipos de formas que no tienen propiedades de efecto.<br/>            Solo lectura [`IEffectFormat`](/slides/python-net/es/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/es/aspose.slides/zoomframe/fill_format/) | Devuelve el objeto FillFormat que contiene las propiedades de formato de relleno para una forma.<br/>            Nota: puede devolver None para ciertos tipos de formas que no tienen propiedades de relleno.<br/>            Solo lectura [`IFillFormat`](/slides/python-net/es/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/es/aspose.slides/zoomframe/hyperlink_click/) | Devuelve o establece el hipervínculo definido para el clic del ratón.<br/>            Lectura/escritura [`IHyperlink`](/slides/python-net/es/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/es/aspose.slides/zoomframe/hyperlink_mouse_over/) | Devuelve o establece el hipervínculo definido para pasar el ratón por encima.<br/>            Lectura/escritura [`IHyperlink`](/slides/python-net/es/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/es/aspose.slides/zoomframe/hyperlink_manager/) | Devuelve el administrador de hipervínculos.<br/>            Solo lectura [`IHyperlinkManager`](/slides/python-net/es/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/es/aspose.slides/zoomframe/hidden/) | Determina si la forma está oculta.<br/>            Lectura/escritura **bool**. |
| [`z_order_position`](/slides/python-net/es/aspose.slides/zoomframe/z_order_position/) | Devuelve la posición de una forma en el orden Z.<br/>            Shapes[0] devuelve la forma al fondo del orden Z,<br/>            y Shapes[Shapes.Count - 1] devuelve la forma al frente del orden Z.<br/>            Solo lectura **int**. |
| [`connection_site_count`](/slides/python-net/es/aspose.slides/zoomframe/connection_site_count/) | Devuelve el número de puntos de conexión en la forma.<br/>            Solo lectura **int**. |
| [`rotation`](/slides/python-net/es/aspose.slides/zoomframe/rotation/) | Devuelve o establece el número de grados que la forma especificada está rotada alrededor del eje Z. Un valor positivo indica rotación en sentido horario; un valor negativo indica rotación en sentido antihorario.<br/>            Lectura/escritura **float**. |
| [`x`](/slides/python-net/es/aspose.slides/zoomframe/x/) | Obtiene o establece la coordenada X de la esquina superior izquierda de la forma, medida en puntos.<br/>            Lectura/escritura **float**. |
| [`y`](/slides/python-net/es/aspose.slides/zoomframe/y/) | Obtiene o establece la coordenada Y de la esquina superior izquierda de la forma, medida en puntos.<br/>            Lectura/escritura **float**. |
| [`width`](/slides/python-net/es/aspose.slides/zoomframe/width/) | Obtiene o establece el ancho de la forma, medido en puntos.<br/>            Lectura/escritura **float**. |
| [`height`](/slides/python-net/es/aspose.slides/zoomframe/height/) | Obtiene o establece la altura de la forma, medida en puntos.<br/>            Lectura/escritura **float**. |
| [`black_white_mode`](/slides/python-net/es/aspose.slides/zoomframe/black_white_mode/) | Propiedad que especifica cómo se renderiza una forma en modo de visualización en blanco y negro.<br/>            Lectura/escritura [`BlackWhiteMode`](/slides/python-net/es/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/es/aspose.slides/zoomframe/unique_id/) | Devuelve un identificador interno, limitado a la presentación, destinado a ser usado por complementos u otro código.<br/>            Debido a que este valor puede ser reasignado por el usuario o programáticamente, no debe tratarse como una clave única persistente.<br/>            Solo lectura **int**.<br/>            Véase también [`Shape.office_interop_shape_id`](/slides/python-net/es/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/es/aspose.slides/zoomframe/office_interop_shape_id/) | Devuelve un identificador único limitado a la diapositiva que permanece constante durante la vida útil de la forma y permite que PowerPoint o el código de interop la referencien de forma fiable desde cualquier parte del documento.<br/>            Solo lectura **int**.<br/>            Véase también [`Shape.unique_id`](/slides/python-net/es/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/es/aspose.slides/zoomframe/alternative_text/) | Devuelve o establece el texto alternativo asociado a una forma.<br/>            Lectura/escritura **str**. |
| [`alternative_text_title`](/slides/python-net/es/aspose.slides/zoomframe/alternative_text_title/) | Devuelve o establece el título del texto alternativo asociado a una forma.<br/>            Lectura/escritura **str**. |
| [`name`](/slides/python-net/es/aspose.slides/zoomframe/name/) | Devuelve o establece el nombre de una forma.<br/>            No debe ser None. Use una cadena vacía si es necesario.<br/>            Lectura/escritura **str**. |
| [`is_decorative`](/slides/python-net/es/aspose.slides/zoomframe/is_decorative/) | Obtiene o establece la opción 'Marcar como decorativo'<br/>            Lectura/escritura **bool**. |
| [`shape_lock`](/slides/python-net/es/aspose.slides/zoomframe/shape_lock/) | Devuelve los bloqueos de la forma.<br/>            Solo lectura [`IGraphicalObjectLock`](/slides/python-net/es/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/es/aspose.slides/zoomframe/is_grouped/) | Determina si la forma está agrupada.<br/>            Solo lectura **bool**. |
| [`parent_group`](/slides/python-net/es/aspose.slides/zoomframe/parent_group/) | Devuelve el objeto GroupShape padre si la forma está agrupada. De lo contrario devuelve None.<br/>            Solo lectura [`IGroupShape`](/slides/python-net/es/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/es/aspose.slides/zoomframe/slide/) | Devuelve la diapositiva padre de una forma.<br/>            Solo lectura [`IBaseSlide`](/slides/python-net/es/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/es/aspose.slides/zoomframe/presentation/) | Devuelve la presentación padre de una diapositiva.<br/>            Solo lectura [`IPresentation`](/slides/python-net/es/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/es/aspose.slides/zoomframe/graphical_object_lock/) | Devuelve los bloqueos de la forma.<br/>            Solo lectura [`IGraphicalObjectLock`](/slides/python-net/es/aspose.slides/igraphicalobjectlock). |
| [`image_type`](/slides/python-net/es/aspose.slides/zoomframe/image_type/) | Obtiene o establece el tipo de imagen de un objeto zoom.<br/>            Lectura/escritura [`ZoomImageType`](/slides/python-net/es/aspose.slides/zoomimagetype).<br/>            Valor predeterminado: Preview |
| [`return_to_parent`](/slides/python-net/es/aspose.slides/zoomframe/return_to_parent/) | Obtiene o establece el comportamiento de navegación en la presentación.<br/>            Lectura/escritura **bool**.<br/>            Valor predeterminado: false |
| [`show_background`](/slides/python-net/es/aspose.slides/zoomframe/show_background/) | Obtiene o establece el valor que especifica si el Zoom usará el fondo de la diapositiva de destino.<br/>            Lectura/escritura **bool**.<br/>            Valor predeterminado: true |
| [`zoom_image`](/slides/python-net/es/aspose.slides/zoomframe/zoom_image/) | Obtiene o establece la imagen para el objeto zoom.<br/>            Lectura/escritura [`IPPImage`](/slides/python-net/es/aspose.slides/ippimage). |
| [`transition_duration`](/slides/python-net/es/aspose.slides/zoomframe/transition_duration/) | Obtiene o establece la duración de la transición entre Zoom y la diapositiva.<br/>            Lectura/escritura **float**.<br/>            Valor predeterminado: 1.0f |
| [`target_slide`](/slides/python-net/es/aspose.slides/zoomframe/target_slide/) | Obtiene o establece el objeto diapositiva al que el objeto Slide Zoom enlaza.<br/>            Lectura/escritura [`ISlide`](/slides/python-net/es/aspose.slides/islide). |

## Métodos

| Método | Descripción |
| :- | :- |
| [`get_image(self)`](/slides/python-net/es/aspose.slides/zoomframe/get_image/#) | Devuelve la miniatura de la forma.<br/>            El tipo ShapeThumbnailBounds.Shape se usa por defecto para los límites de la miniatura de la forma. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/es/aspose.slides/zoomframe/get_image/#shapethumbnailbounds-float-float) | Devuelve la miniatura de la forma. |
| [`write_as_svg(self, stream)`](/slides/python-net/es/aspose.slides/zoomframe/write_as_svg/#iorawiobase) | Guarda el contenido de la Forma como archivo SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/es/aspose.slides/zoomframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Guarda el contenido de la Forma como archivo SVG. |
| [`remove_placeholder(self)`](/slides/python-net/es/aspose.slides/zoomframe/remove_placeholder/#) | Define que esta forma no es un marcador de posición. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/es/aspose.slides/zoomframe/add_placeholder/#iplaceholder) | Agrega un nuevo marcador de posición si no existe y establece sus propiedades al especificado. |
| [`get_base_placeholder(self)`](/slides/python-net/es/aspose.slides/zoomframe/get_base_placeholder/#) | Devuelve una forma de marcador de posición básica (forma del diseño y/o diapositiva maestra de la cual la forma actual hereda).<br/>            Se devuelve None si la forma actual no es heredada. |
| [`get_visual_bounds(self)`](/slides/python-net/es/aspose.slides/zoomframe/get_visual_bounds/#) | Obtiene los límites visuales de la forma calculados a partir de su contenido renderizado. |

### Ver también
* clase [`GraphicalObject`](/slides/python-net/es/aspose.slides/graphicalobject)
* clase [`Shape`](/slides/python-net/es/aspose.slides/shape)
* clase [`ZoomFrame`](/slides/python-net/es/aspose.slides/zoomframe)
* clase [`ZoomObject`](/slides/python-net/es/aspose.slides/zoomobject)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)