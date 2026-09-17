---
title: SummaryZoomSection class
second_title: Aspose.Slides para Python vía .NET Referencia de API
description: 
type: docs
url: /es/aspose.slides/summaryzoomsection/
---
## SummaryZoomSection clase

Representa un objeto Summary Zoom Section en un marco Summary Zoom.

**Herencia:**[`SummaryZoomSection`](/slides/python-net/es/aspose.slides/summaryzoomsection) → [`SectionZoomFrame`](/slides/python-net/es/aspose.slides/sectionzoomframe) → [`ZoomObject`](/slides/python-net/es/aspose.slides/zoomobject) → [`GraphicalObject`](/slides/python-net/es/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/es/aspose.slides/shape)

El tipo SummaryZoomSection expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`is_text_holder`](/slides/python-net/es/aspose.slides/summaryzoomsection/is_text_holder/) | Determina si la forma es TextHolder_PPT.<br/>            Solo lectura **bool**. |
| [`placeholder`](/slides/python-net/es/aspose.slides/summaryzoomsection/placeholder/) | Devuelve el marcador de posición para una forma. Devuelve None si la forma no tiene marcador de posición.<br/>            Solo lectura [`IPlaceholder`](/slides/python-net/es/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/es/aspose.slides/summaryzoomsection/custom_data/) | Devuelve los datos personalizados de la forma.<br/>            Solo lectura [`ICustomData`](/slides/python-net/es/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/es/aspose.slides/summaryzoomsection/raw_frame/) | Obtiene o establece las propiedades del marco de forma sin procesar.<br/>            Lectura/escritura [`IShapeFrame`](/slides/python-net/es/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/es/aspose.slides/summaryzoomsection/frame/) | Obtiene o establece las propiedades del marco de forma.<br/>            Lectura/escritura [`IShapeFrame`](/slides/python-net/es/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/es/aspose.slides/summaryzoomsection/line_format/) | Devuelve el objeto LineFormat que contiene las propiedades de formato de línea para una forma.<br/>            Nota: puede devolver None para ciertos tipos de formas que no tienen propiedades de línea.<br/>            Solo lectura [`ILineFormat`](/slides/python-net/es/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/es/aspose.slides/summaryzoomsection/three_d_format/) | Devuelve el objeto ThreeDFormat que contiene las propiedades de efecto 3d para una forma.<br/>            Nota: puede devolver None para ciertos tipos de formas que no tienen propiedades 3d.<br/>            Solo lectura [`IThreeDFormat`](/slides/python-net/es/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/es/aspose.slides/summaryzoomsection/effect_format/) | Devuelve el objeto EffectFormat que contiene los efectos de píxel aplicados a una forma.<br/>            Nota: puede devolver None para ciertos tipos de formas que no tienen propiedades de efecto.<br/>            Solo lectura [`IEffectFormat`](/slides/python-net/es/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/es/aspose.slides/summaryzoomsection/fill_format/) | Devuelve el objeto FillFormat que contiene las propiedades de formato de relleno para una forma.<br/>            Nota: puede devolver None para ciertos tipos de formas que no tienen propiedades de relleno.<br/>            Solo lectura [`IFillFormat`](/slides/python-net/es/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/es/aspose.slides/summaryzoomsection/hyperlink_click/) | Obtiene o establece el hipervínculo definido para hacer clic con el ratón.<br/>            Lectura/escritura [`IHyperlink`](/slides/python-net/es/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/es/aspose.slides/summaryzoomsection/hyperlink_mouse_over/) | Obtiene o establece el hipervínculo definido para pasar el ratón por encima.<br/>            Lectura/escritura [`IHyperlink`](/slides/python-net/es/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/es/aspose.slides/summaryzoomsection/hyperlink_manager/) | Devuelve el gestor de hipervínculos.<br/>            Solo lectura [`IHyperlinkManager`](/slides/python-net/es/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/es/aspose.slides/summaryzoomsection/hidden/) | Determina si la forma está oculta.<br/>            Lectura/escritura **bool**. |
| [`z_order_position`](/slides/python-net/es/aspose.slides/summaryzoomsection/z_order_position/) | Devuelve la posición de una forma en el orden Z.<br/>            Shapes[0] devuelve la forma al fondo del orden Z,<br/>            y Shapes[Shapes.Count - 1] devuelve la forma al frente del orden Z.<br/>            Solo lectura **int**. |
| [`connection_site_count`](/slides/python-net/es/aspose.slides/summaryzoomsection/connection_site_count/) | Devuelve el número de puntos de conexión en la forma.<br/>            Solo lectura **int**. |
| [`rotation`](/slides/python-net/es/aspose.slides/summaryzoomsection/rotation/) | Obtiene o establece el número de grados que la forma especificada se rota alrededor del eje Z. Un valor positivo indica rotación en sentido horario; un valor negativo indica rotación en sentido antihorario.<br/>            Lectura/escritura **float**. |
| [`x`](/slides/python-net/es/aspose.slides/summaryzoomsection/x/) | Obtiene o establece la coordenada X de la esquina superior izquierda de la forma, medida en puntos.<br/>            Lectura/escritura **float**. |
| [`y`](/slides/python-net/es/aspose.slides/summaryzoomsection/y/) | Obtiene o establece la coordenada Y de la esquina superior izquierda de la forma, medida en puntos.<br/>            Lectura/escritura **float**. |
| [`width`](/slides/python-net/es/aspose.slides/summaryzoomsection/width/) | Obtiene o establece el ancho de la forma, medido en puntos.<br/>            Lectura/escritura **float**. |
| [`height`](/slides/python-net/es/aspose.slides/summaryzoomsection/height/) | Obtiene o establece la altura de la forma, medida en puntos.<br/>            Lectura/escritura **float**. |
| [`black_white_mode`](/slides/python-net/es/aspose.slides/summaryzoomsection/black_white_mode/) | La propiedad especifica cómo se renderizará una forma en modo de visualización en blanco y negro.<br/>            Lectura/escritura [`BlackWhiteMode`](/slides/python-net/es/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/es/aspose.slides/summaryzoomsection/unique_id/) | Devuelve un identificador interno de presentación destinado a ser usado por complementos u otro código.<br/>            Debido a que este valor puede ser reasignado por el usuario o programáticamente, no debe tratarse como una clave única persistente.<br/>            Solo lectura **int**.<br/>            Ver también [`Shape.office_interop_shape_id`](/slides/python-net/es/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/es/aspose.slides/summaryzoomsection/office_interop_shape_id/) | Devuelve un identificador único de diapositiva que permanece constante durante la vida de la forma y permite que PowerPoint o código de interop referencie de forma fiable la forma desde cualquier parte del documento.<br/>            Solo lectura **int**.<br/>            Ver también [`Shape.unique_id`](/slides/python-net/es/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/es/aspose.slides/summaryzoomsection/alternative_text/) | Obtiene o establece el texto alternativo asociado a una forma.<br/>            Lectura/escritura **str**. |
| [`alternative_text_title`](/slides/python-net/es/aspose.slides/summaryzoomsection/alternative_text_title/) | Obtiene o establece el título del texto alternativo asociado a una forma.<br/>            Lectura/escritura **str**. |
| [`name`](/slides/python-net/es/aspose.slides/summaryzoomsection/name/) | Obtiene o establece el nombre de una forma.<br/>            No debe ser None. Utilice una cadena vacía si es necesario.<br/>            Lectura/escritura **str**. |
| [`is_decorative`](/slides/python-net/es/aspose.slides/summaryzoomsection/is_decorative/) | Obtiene o establece la opción 'Marcar como decorativo'<br/>            Lectura/escritura **bool**. |
| [`shape_lock`](/slides/python-net/es/aspose.slides/summaryzoomsection/shape_lock/) | Devuelve los bloqueos de la forma.<br/>            Solo lectura [`IGraphicalObjectLock`](/slides/python-net/es/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/es/aspose.slides/summaryzoomsection/is_grouped/) | Determina si la forma está agrupada.<br/>            Solo lectura **bool**. |
| [`parent_group`](/slides/python-net/es/aspose.slides/summaryzoomsection/parent_group/) | Devuelve el objeto GroupShape padre si la forma está agrupada. De lo contrario devuelve None.<br/>            Solo lectura [`IGroupShape`](/slides/python-net/es/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/es/aspose.slides/summaryzoomsection/slide/) | Devuelve la diapositiva padre de una forma.<br/>            Solo lectura [`IBaseSlide`](/slides/python-net/es/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/es/aspose.slides/summaryzoomsection/presentation/) | Devuelve la presentación padre de una diapositiva.<br/>            Solo lectura [`IPresentation`](/slides/python-net/es/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/es/aspose.slides/summaryzoomsection/graphical_object_lock/) | Devuelve los bloqueos de la forma.<br/>            Solo lectura [`IGraphicalObjectLock`](/slides/python-net/es/aspose.slides/igraphicalobjectlock). |
| [`image_type`](/slides/python-net/es/aspose.slides/summaryzoomsection/image_type/) | Obtiene o establece el tipo de imagen de un objeto zoom.<br/>            Lectura/escritura [`ZoomImageType`](/slides/python-net/es/aspose.slides/zoomimagetype).<br/>            Valor predeterminado: Preview |
| [`return_to_parent`](/slides/python-net/es/aspose.slides/summaryzoomsection/return_to_parent/) | Obtiene o establece el comportamiento de navegación en la presentación de diapositivas.<br/>            Lectura/escritura **bool**.<br/>            Valor predeterminado: false |
| [`show_background`](/slides/python-net/es/aspose.slides/summaryzoomsection/show_background/) | Obtiene o establece el valor que especifica si el Zoom usará el fondo de la diapositiva de destino.<br/>            Lectura/escritura **bool**.<br/>            Valor predeterminado: true |
| [`zoom_image`](/slides/python-net/es/aspose.slides/summaryzoomsection/zoom_image/) | Obtiene o establece la imagen para el objeto zoom.<br/>            Lectura/escritura [`IPPImage`](/slides/python-net/es/aspose.slides/ippimage). |
| [`transition_duration`](/slides/python-net/es/aspose.slides/summaryzoomsection/transition_duration/) | Obtiene o establece la duración de la transición entre Zoom y la diapositiva.<br/>            Lectura/escritura **float**.<br/>            Valor predeterminado: 1.0f |
| [`target_section`](/slides/python-net/es/aspose.slides/summaryzoomsection/target_section/) | Obtiene o establece el objeto sección al que el objeto Section Zoom enlaza.<br/>            Lectura/escritura [`ISection`](/slides/python-net/es/aspose.slides/isection). |
| [`title`](/slides/python-net/es/aspose.slides/summaryzoomsection/title/) | Devuelve el título de texto del objeto Summary Zoom Section. |
| [`description`](/slides/python-net/es/aspose.slides/summaryzoomsection/description/) | Devuelve la descripción de texto del objeto Summary Zoom Section. |

## Métodos

| Método | Descripción |
| :- | :- |
| [`get_image(self)`](/slides/python-net/es/aspose.slides/summaryzoomsection/get_image/#) | Devuelve la miniatura de la forma.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type se usa por defecto. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/es/aspose.slides/summaryzoomsection/get_image/#shapethumbnailbounds-float-float) | Devuelve la miniatura de la forma. |
| [`write_as_svg(self, stream)`](/slides/python-net/es/aspose.slides/summaryzoomsection/write_as_svg/#iorawiobase) | Guarda el contenido de la forma como archivo SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/es/aspose.slides/summaryzoomsection/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Guarda el contenido de la forma como archivo SVG. |
| [`remove_placeholder(self)`](/slides/python-net/es/aspose.slides/summaryzoomsection/remove_placeholder/#) | Define que esta forma no es un marcador de posición. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/es/aspose.slides/summaryzoomsection/add_placeholder/#iplaceholder) | Añade un nuevo marcador de posición si no hay ninguno y establece las propiedades del marcador de posición a uno especificado. |
| [`get_base_placeholder(self)`](/slides/python-net/es/aspose.slides/summaryzoomsection/get_base_placeholder/#) | Devuelve una forma de marcador de posición básica (forma del diseño y/o diapositiva maestra de la cual la forma actual se hereda).<br/>            Se devuelve None si la forma actual no está heredada. |
| [`get_visual_bounds(self)`](/slides/python-net/es/aspose.slides/summaryzoomsection/get_visual_bounds/#) | Obtiene los límites visuales de la forma calculados a partir de su contenido renderizado. |

### Ver también
* clase [`GraphicalObject`](/slides/python-net/es/aspose.slides/graphicalobject)
* clase [`SectionZoomFrame`](/slides/python-net/es/aspose.slides/sectionzoomframe)
* clase [`Shape`](/slides/python-net/es/aspose.slides/shape)
* clase [`SummaryZoomSection`](/slides/python-net/es/aspose.slides/summaryzoomsection)
* clase [`ZoomObject`](/slides/python-net/es/aspose.slides/zoomobject)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)