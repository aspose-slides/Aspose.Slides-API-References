---
title: SmartArt class
second_title: Referencia de API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides.smartart/smartart/
---
## Clase SmartArt

Representa un diagrama SmartArt

**Herencia:**[`SmartArt`](/slides/python-net/es/aspose.slides.smartart/smartart) → [`GraphicalObject`](/slides/python-net/es/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/es/aspose.slides/shape)

El tipo SmartArt expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`is_text_holder`](/slides/python-net/es/aspose.slides.smartart/smartart/is_text_holder/) | Determina si la forma es TextHolder_PPT.<br/>            Solo lectura **bool**. |
| [`placeholder`](/slides/python-net/es/aspose.slides.smartart/smartart/placeholder/) | Devuelve el marcador de posición para una forma. Devuelve None si la forma no tiene marcador de posición.<br/>            Solo lectura [`IPlaceholder`](/slides/python-net/es/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/es/aspose.slides.smartart/smartart/custom_data/) | Devuelve los datos personalizados de la forma.<br/>            Solo lectura [`ICustomData`](/slides/python-net/es/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/es/aspose.slides.smartart/smartart/raw_frame/) | Obtiene o establece las propiedades del marco bruto de la forma.<br/>            Lectura/escritura [`IShapeFrame`](/slides/python-net/es/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/es/aspose.slides.smartart/smartart/frame/) | Obtiene o establece las propiedades del marco de la forma.<br/>            Lectura/escritura [`IShapeFrame`](/slides/python-net/es/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/es/aspose.slides.smartart/smartart/line_format/) | Devuelve el objeto LineFormat que contiene las propiedades de formato de línea para una forma.<br/>            Nota: puede devolver None para ciertos tipos de formas que no tienen propiedades de línea.<br/>            Solo lectura [`ILineFormat`](/slides/python-net/es/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/es/aspose.slides.smartart/smartart/three_d_format/) | Devuelve el objeto ThreeDFormat que contiene las propiedades de efecto 3D para una forma.<br/>            Nota: puede devolver None para ciertos tipos de formas que no tienen propiedades 3D.<br/>            Solo lectura [`IThreeDFormat`](/slides/python-net/es/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/es/aspose.slides.smartart/smartart/effect_format/) | Devuelve el objeto EffectFormat que contiene los efectos de píxel aplicados a una forma.<br/>            Nota: puede devolver None para ciertos tipos de formas que no tienen propiedades de efecto.<br/>            Solo lectura [`IEffectFormat`](/slides/python-net/es/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/es/aspose.slides.smartart/smartart/fill_format/) | Devuelve el objeto FillFormat que contiene las propiedades de formato de relleno para una forma.<br/>            Nota: puede devolver None para ciertos tipos de formas que no tienen propiedades de relleno.<br/>            Solo lectura [`IFillFormat`](/slides/python-net/es/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/es/aspose.slides.smartart/smartart/hyperlink_click/) | Obtiene o establece el hipervínculo definido para hacer clic con el ratón.<br/>            Lectura/escritura [`IHyperlink`](/slides/python-net/es/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/es/aspose.slides.smartart/smartart/hyperlink_mouse_over/) | Obtiene o establece el hipervínculo definido para pasar el ratón por encima.<br/>            Lectura/escritura [`IHyperlink`](/slides/python-net/es/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/es/aspose.slides.smartart/smartart/hyperlink_manager/) | Devuelve el gestor de hipervínculos.<br/>            Solo lectura [`IHyperlinkManager`](/slides/python-net/es/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/es/aspose.slides.smartart/smartart/hidden/) | Determina si la forma está oculta.<br/>            Lectura/escritura **bool**. |
| [`z_order_position`](/slides/python-net/es/aspose.slides.smartart/smartart/z_order_position/) | Devuelve la posición de una forma en el orden z.<br/>            Shapes[0] devuelve la forma al fondo del orden z,<br/>            y Shapes[Shapes.Count - 1] devuelve la forma al frente del orden z.<br/>            Solo lectura **int**. |
| [`connection_site_count`](/slides/python-net/es/aspose.slides.smartart/smartart/connection_site_count/) | Devuelve el número de sitios de conexión en la forma.<br/>            Solo lectura **int**. |
| [`rotation`](/slides/python-net/es/aspose.slides.smartart/smartart/rotation/) | Obtiene o establece el número de grados que la forma especificada está rotada alrededor del eje z. Un valor positivo indica rotación en sentido horario; un valor negativo indica rotación en sentido antihorario.<br/>            Lectura/escritura **float**. |
| [`x`](/slides/python-net/es/aspose.slides.smartart/smartart/x/) | Obtiene o establece la coordenada x de la esquina superior izquierda de la forma, medida en puntos.<br/>            Lectura/escritura **float**. |
| [`y`](/slides/python-net/es/aspose.slides.smartart/smartart/y/) | Obtiene o establece la coordenada y de la esquina superior izquierda de la forma, medida en puntos.<br/>            Lectura/escritura **float**. |
| [`width`](/slides/python-net/es/aspose.slides.smartart/smartart/width/) | Obtiene o establece el ancho de la forma, medido en puntos.<br/>            Lectura/escritura **float**. |
| [`height`](/slides/python-net/es/aspose.slides.smartart/smartart/height/) | Obtiene o establece la altura de la forma, medida en puntos.<br/>            Lectura/escritura **float**. |
| [`black_white_mode`](/slides/python-net/es/aspose.slides.smartart/smartart/black_white_mode/) | La propiedad especifica cómo se renderiza una forma en modo de pantalla en blanco y negro.<br/>            Lectura/escritura [`BlackWhiteMode`](/slides/python-net/es/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/es/aspose.slides.smartart/smartart/unique_id/) | Devuelve un identificador interno, limitado a la presentación, destinado al uso de complementos u otro código.<br/>            Debido a que este valor puede ser reasignado por el usuario o programáticamente, no debe tratarse como una clave única persistente.<br/>            Solo lectura **int**.<br/>            Ver también [`Shape.office_interop_shape_id`](/slides/python-net/es/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/es/aspose.slides.smartart/smartart/office_interop_shape_id/) | Devuelve un identificador único limitado a la diapositiva que permanece constante durante la vida de la forma y permite que PowerPoint o el código interop referencie la forma de manera fiable desde cualquier parte del documento.<br/>            Solo lectura **int**.<br/>            Ver también [`Shape.unique_id`](/slides/python-net/es/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/es/aspose.slides.smartart/smartart/alternative_text/) | Obtiene o establece el texto alternativo asociado a una forma.<br/>            Lectura/escritura **str**. |
| [`alternative_text_title`](/slides/python-net/es/aspose.slides.smartart/smartart/alternative_text_title/) | Obtiene o establece el título del texto alternativo asociado a una forma.<br/>            Lectura/escritura **str**. |
| [`name`](/slides/python-net/es/aspose.slides.smartart/smartart/name/) | Obtiene o establece el nombre de una forma.<br/>            No debe ser None. Use una cadena vacía si es necesario.<br/>            Lectura/escritura **str**. |
| [`is_decorative`](/slides/python-net/es/aspose.slides.smartart/smartart/is_decorative/) | Obtiene o establece la opción 'Marcar como decorativa'<br/>            Lectura/escritura **bool**. |
| [`shape_lock`](/slides/python-net/es/aspose.slides.smartart/smartart/shape_lock/) | Devuelve los bloqueos de la forma.<br/>            Solo lectura [`IGraphicalObjectLock`](/slides/python-net/es/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/es/aspose.slides.smartart/smartart/is_grouped/) | Determina si la forma está agrupada.<br/>            Solo lectura **bool**. |
| [`parent_group`](/slides/python-net/es/aspose.slides.smartart/smartart/parent_group/) | Devuelve el objeto GroupShape padre si la forma está agrupada. De lo contrario devuelve None.<br/>            Solo lectura [`IGroupShape`](/slides/python-net/es/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/es/aspose.slides.smartart/smartart/slide/) | Devuelve la diapositiva padre de una forma.<br/>            Solo lectura [`IBaseSlide`](/slides/python-net/es/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/es/aspose.slides.smartart/smartart/presentation/) | Devuelve la presentación padre de una diapositiva.<br/>            Solo lectura [`IPresentation`](/slides/python-net/es/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/es/aspose.slides.smartart/smartart/graphical_object_lock/) | Devuelve los bloqueos de la forma.<br/>            Solo lectura [`IGraphicalObjectLock`](/slides/python-net/es/aspose.slides/igraphicalobjectlock). |
| [`all_nodes`](/slides/python-net/es/aspose.slides.smartart/smartart/all_nodes/) | Devuelve colecciones de todos los nodos en el objeto SmartArt.<br/>            Solo lectura [`ISmartArtNodeCollection`](/slides/python-net/es/aspose.slides.smartart/ismartartnodecollection). |
| [`nodes`](/slides/python-net/es/aspose.slides.smartart/smartart/nodes/) | Devuelve colecciones de nodos raíz en el objeto SmartArt.<br/>            Solo lectura [`ISmartArtNodeCollection`](/slides/python-net/es/aspose.slides.smartart/ismartartnodecollection). |
| [`layout`](/slides/python-net/es/aspose.slides.smartart/smartart/layout/) | Obtiene o establece el diseño del objeto SmartArt.<br/>            Lectura/escritura [`SmartArtLayoutType`](/slides/python-net/es/aspose.slides.smartart/smartartlayouttype). |
| [`quick_style`](/slides/python-net/es/aspose.slides.smartart/smartart/quick_style/) | Obtiene o establece el estilo rápido del objeto SmartArt.<br/>            Lectura/escritura [`SmartArtQuickStyleType`](/slides/python-net/es/aspose.slides.smartart/smartartquickstyletype). |
| [`color_style`](/slides/python-net/es/aspose.slides.smartart/smartart/color_style/) | Obtiene o establece el estilo de color del objeto SmartArt.<br/>            Lectura/escritura [`SmartArtColorType`](/slides/python-net/es/aspose.slides.smartart/smartartcolortype). |
| [`is_reversed`](/slides/python-net/es/aspose.slides.smartart/smartart/is_reversed/) | Devuelve o establece el estado del diagrama SmartArt respecto a LTR (izquierda a derecha) o RTL (derecha a izquierda), si el diagrama soporta inversión.<br/>            Lectura/escritura **bool**. |

## Métodos

| Método | Descripción |
| :- | :- |
| [`get_image(self)`](/slides/python-net/es/aspose.slides.smartart/smartart/get_image/#) | Devuelve la miniatura de la forma.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type se usa por defecto. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/es/aspose.slides.smartart/smartart/get_image/#shapethumbnailbounds-float-float) | Devuelve la miniatura de la forma. |
| [`write_as_svg(self, stream)`](/slides/python-net/es/aspose.slides.smartart/smartart/write_as_svg/#iorawiobase) | Guarda el contenido de Shape como archivo SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/es/aspose.slides.smartart/smartart/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Guarda el contenido de Shape como archivo SVG. |
| [`remove_placeholder(self)`](/slides/python-net/es/aspose.slides.smartart/smartart/remove_placeholder/#) | Define que esta forma no es un marcador de posición. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/es/aspose.slides.smartart/smartart/add_placeholder/#iplaceholder) | Añade un nuevo marcador de posición si no existe y establece las propiedades del marcador de posición a una especificada. |
| [`get_base_placeholder(self)`](/slides/python-net/es/aspose.slides.smartart/smartart/get_base_placeholder/#) | Devuelve una forma de marcador de posición básica (forma del diseño y/o diapositiva maestra de la que la forma actual hereda).<br/>            Se devuelve None si la forma actual no hereda. |
| [`get_visual_bounds(self)`](/slides/python-net/es/aspose.slides.smartart/smartart/get_visual_bounds/#) | Obtiene los límites visuales de la forma calculados a partir de su contenido renderizado. |


### Ver también
* clase [`GraphicalObject`](/slides/python-net/es/aspose.slides/graphicalobject)
* clase [`Shape`](/slides/python-net/es/aspose.slides/shape)
* clase [`SmartArt`](/slides/python-net/es/aspose.slides.smartart/smartart)
* módulo [`aspose.slides.smartart`](/slides/python-net/es/aspose.slides.smartart)
* biblioteca [`Aspose.Slides`](/slides/python-net)