---
title: Connector class
second_title: Aspose.Slides para Python mediante la referencia de la API .NET
description: 
type: docs
url: /es/aspose.slides/connector/
---
## Clase Connector

Representa un conector.

**Herencia:**[`Connector`](/slides/python-net/es/aspose.slides/connector) → [`GeometryShape`](/slides/python-net/es/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/es/aspose.slides/shape)

El tipo Connector expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`is_text_holder`](/slides/python-net/es/aspose.slides/connector/is_text_holder/) | Determina si la forma es TextHolder_PPT.<br/>            Solo lectura **bool**. |
| [`placeholder`](/slides/python-net/es/aspose.slides/connector/placeholder/) | Devuelve el marcador de posición de una forma. Devuelve None si la forma no tiene marcador de posición.<br/>            Solo lectura [`IPlaceholder`](/slides/python-net/es/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/es/aspose.slides/connector/custom_data/) | Devuelve los datos personalizados de la forma.<br/>            Solo lectura [`ICustomData`](/slides/python-net/es/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/es/aspose.slides/connector/raw_frame/) | Devuelve o establece las propiedades del marco bruto de la forma.<br/>            Lectura/escritura [`IShapeFrame`](/slides/python-net/es/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/es/aspose.slides/connector/frame/) | Devuelve o establece las propiedades del marco de la forma.<br/>            Lectura/escritura [`IShapeFrame`](/slides/python-net/es/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/es/aspose.slides/connector/line_format/) | Devuelve el objeto LineFormat que contiene las propiedades de formato de línea para una forma.<br/>            Nota: puede devolver None para ciertos tipos de formas que no tienen propiedades de línea.<br/>            Solo lectura [`ILineFormat`](/slides/python-net/es/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/es/aspose.slides/connector/three_d_format/) | Devuelve el objeto ThreeDFormat que contiene las propiedades de efectos 3d para una forma.<br/>            Nota: puede devolver None para ciertos tipos de formas que no tienen propiedades 3d.<br/>            Solo lectura [`IThreeDFormat`](/slides/python-net/es/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/es/aspose.slides/connector/effect_format/) | Devuelve el objeto EffectFormat que contiene los efectos de píxel aplicados a una forma.<br/>            Nota: puede devolver None para ciertos tipos de formas que no tienen propiedades de efecto.<br/>            Solo lectura [`IEffectFormat`](/slides/python-net/es/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/es/aspose.slides/connector/fill_format/) | Devuelve el objeto FillFormat que contiene las propiedades de formato de relleno para una forma.<br/>            Nota: puede devolver None para ciertos tipos de formas que no tienen propiedades de relleno.<br/>            Solo lectura [`IFillFormat`](/slides/python-net/es/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/es/aspose.slides/connector/hyperlink_click/) | Devuelve o establece el hipervínculo definido para clic del ratón.<br/>            Lectura/escritura [`IHyperlink`](/slides/python-net/es/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/es/aspose.slides/connector/hyperlink_mouse_over/) | Devuelve o establece el hipervínculo definido para pasar el ratón por encima.<br/>            Lectura/escritura [`IHyperlink`](/slides/python-net/es/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/es/aspose.slides/connector/hyperlink_manager/) | Devuelve el gestor de hipervínculos.<br/>            Solo lectura [`IHyperlinkManager`](/slides/python-net/es/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/es/aspose.slides/connector/hidden/) | Determina si la forma está oculta.<br/>            Lectura/escritura **bool**. |
| [`z_order_position`](/slides/python-net/es/aspose.slides/connector/z_order_position/) | Devuelve la posición de una forma en el orden z.<br/>            Shapes[0] devuelve la forma al fondo del orden z,<br/>            y Shapes[Shapes.Count - 1] devuelve la forma al frente del orden z.<br/>            Solo lectura **int**. |
| [`connection_site_count`](/slides/python-net/es/aspose.slides/connector/connection_site_count/) | Devuelve el número de puntos de conexión en la forma.<br/>            Solo lectura **int**. |
| [`rotation`](/slides/python-net/es/aspose.slides/connector/rotation/) | Devuelve o establece el número de grados que la forma especificada está rotada alrededor del eje z.<br/>            Un valor positivo indica rotación en sentido horario; un valor negativo indica rotación en sentido antihorario.<br/>            Lectura/escritura **float**. |
| [`x`](/slides/python-net/es/aspose.slides/connector/x/) | Obtiene o establece la coordenada x de la esquina superior izquierda de la forma, medida en puntos.<br/>            Lectura/escritura **float**. |
| [`y`](/slides/python-net/es/aspose.slides/connector/y/) | Obtiene o establece la coordenada y de la esquina superior izquierda de la forma, medida en puntos.<br/>            Lectura/escritura **float**. |
| [`width`](/slides/python-net/es/aspose.slides/connector/width/) | Obtiene o establece el ancho de la forma, medido en puntos.<br/>            Lectura/escritura **float**. |
| [`height`](/slides/python-net/es/aspose.slides/connector/height/) | Obtiene o establece la altura de la forma, medida en puntos.<br/>            Lectura/escritura **float**. |
| [`black_white_mode`](/slides/python-net/es/aspose.slides/connector/black_white_mode/) | La propiedad especifica cómo se representará una forma en modo de pantalla en blanco y negro.<br/>            Lectura/escritura [`BlackWhiteMode`](/slides/python-net/es/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/es/aspose.slides/connector/unique_id/) | Devuelve un identificador interno, con alcance de presentación, destinado a ser usado por complementos u otro código.<br/>            Debido a que este valor puede ser reasignado por el usuario o programáticamente, no debe ser tratado<br/>            como una clave única persistente.<br/>            Solo lectura **int**.<br/>            Ver también [`Shape.office_interop_shape_id`](/slides/python-net/es/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/es/aspose.slides/connector/office_interop_shape_id/) | Devuelve un identificador único con alcance de diapositiva que permanece constante durante la vida útil de la forma y<br/>            permite que PowerPoint o el código interop lo referencie de manera fiable desde cualquier parte del documento.<br/>            Solo lectura **int**.<br/>            Ver también [`Shape.unique_id`](/slides/python-net/es/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/es/aspose.slides/connector/alternative_text/) | Devuelve o establece el texto alternativo asociado a una forma.<br/>            Lectura/escritura **str**. |
| [`alternative_text_title`](/slides/python-net/es/aspose.slides/connector/alternative_text_title/) | Devuelve o establece el título del texto alternativo asociado a una forma.<br/>            Lectura/escritura **str**. |
| [`name`](/slides/python-net/es/aspose.slides/connector/name/) | Devuelve o establece el nombre de una forma.<br/>            No debe ser None. Use una cadena vacía si es necesario.<br/>            Lectura/escritura **str**. |
| [`is_decorative`](/slides/python-net/es/aspose.slides/connector/is_decorative/) | Obtiene o establece la opción 'Marcar como decorativo'<br/>            Lectura/escritura **bool**. |
| [`shape_lock`](/slides/python-net/es/aspose.slides/connector/shape_lock/) | Devuelve los bloqueos de la forma.<br/>            Solo lectura [`IConnectorLock`](/slides/python-net/es/aspose.slides/iconnectorlock). |
| [`is_grouped`](/slides/python-net/es/aspose.slides/connector/is_grouped/) | Determina si la forma está agrupada.<br/>            Solo lectura **bool**. |
| [`parent_group`](/slides/python-net/es/aspose.slides/connector/parent_group/) | Devuelve el objeto GroupShape padre si la forma está agrupada. De lo contrario devuelve None.<br/>            Solo lectura [`IGroupShape`](/slides/python-net/es/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/es/aspose.slides/connector/slide/) | Devuelve la diapositiva padre de una forma.<br/>            Solo lectura [`IBaseSlide`](/slides/python-net/es/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/es/aspose.slides/connector/presentation/) | Devuelve la presentación padre de una diapositiva.<br/>            Solo lectura [`IPresentation`](/slides/python-net/es/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/es/aspose.slides/connector/shape_style/) | Devuelve el objeto de estilo de la forma.<br/>            Solo lectura [`IShapeStyle`](/slides/python-net/es/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/es/aspose.slides/connector/shape_type/) | Devuelve o establece el tipo AutoShape.<br/>            Lectura/escritura [`ShapeType`](/slides/python-net/es/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/es/aspose.slides/connector/adjustments/) | Devuelve una colección de valores de ajuste de la forma.<br/>            Solo lectura [`IAdjustValueCollection`](/slides/python-net/es/aspose.slides/iadjustvaluecollection). |
| [`connector_lock`](/slides/python-net/es/aspose.slides/connector/connector_lock/) | Devuelve los bloqueos del conector.<br/>            Solo lectura [`IConnectorLock`](/slides/python-net/es/aspose.slides/iconnectorlock). |
| [`start_shape_connected_to`](/slides/python-net/es/aspose.slides/connector/start_shape_connected_to/) | Devuelve o establece la forma a la que se debe unir el inicio del conector.<br/>            Lectura/escritura [`IShape`](/slides/python-net/es/aspose.slides/ishape). |
| [`end_shape_connected_to`](/slides/python-net/es/aspose.slides/connector/end_shape_connected_to/) | Devuelve o establece la forma a la que se debe unir el final del conector.<br/>            Lectura/escritura [`IShape`](/slides/python-net/es/aspose.slides/ishape). |
| [`start_shape_connection_site_index`](/slides/python-net/es/aspose.slides/connector/start_shape_connection_site_index/) | Devuelve o establece el índice del punto de conexión para la forma inicial.<br/>            Lectura/escritura **int**. |
| [`end_shape_connection_site_index`](/slides/python-net/es/aspose.slides/connector/end_shape_connection_site_index/) | Devuelve o establece el índice del punto de conexión para la forma final.<br/>            Lectura/escritura **int**. |

## Métodos

| Método | Descripción |
| :- | :- |
| [`get_image(self)`](/slides/python-net/es/aspose.slides/connector/get_image/#) | Devuelve la miniatura de la forma.<br/>            Se usa por defecto el tipo ShapeThumbnailBounds.Shape de los límites de la miniatura de la forma. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/es/aspose.slides/connector/get_image/#shapethumbnailbounds-float-float) | Devuelve la miniatura de la forma. |
| [`write_as_svg(self, stream)`](/slides/python-net/es/aspose.slides/connector/write_as_svg/#iorawiobase) | Guarda el contenido de Shape como archivo SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/es/aspose.slides/connector/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Guarda el contenido de Shape como archivo SVG. |
| [`remove_placeholder(self)`](/slides/python-net/es/aspose.slides/connector/remove_placeholder/#) | Define que esta forma no es un marcador de posición. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/es/aspose.slides/connector/add_placeholder/#iplaceholder) | Agrega un nuevo marcador de posición si no existe y establece las propiedades del marcador de posición a una especificada. |
| [`get_base_placeholder(self)`](/slides/python-net/es/aspose.slides/connector/get_base_placeholder/#) | Devuelve una forma básica de marcador de posición (forma del diseño y/o diapositiva maestra de la que se hereda la forma actual).<br/>            Se devuelve None si la forma actual no es heredada. |
| [`get_visual_bounds(self)`](/slides/python-net/es/aspose.slides/connector/get_visual_bounds/#) | Obtiene los límites visuales de la forma calculados a partir de su contenido renderizado. |
| [`get_geometry_paths(self)`](/slides/python-net/es/aspose.slides/connector/get_geometry_paths/#) | Devuelve una copia de la ruta de la forma geométrica. Las coordenadas son relativas a la esquina superior izquierda de la forma. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/es/aspose.slides/connector/set_geometry_path/#igeometrypath) | Actualiza la geometría de la forma a partir del objeto [`IGeometryPath`](/slides/python-net/es/aspose.slides/igeometrypath). Las coordenadas deben ser relativas a la esquina superior izquierda de la forma.<br/>             Cambia el tipo de la forma ([`GeometryShape.shape_type`](/slides/python-net/es/aspose.slides/geometryshape/shape_type)) a [`ShapeType.CUSTOM`](/slides/python-net/es/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/es/aspose.slides/connector/set_geometry_paths/#listigeometrypath) | Actualiza la geometría de la forma a partir de una matriz de [`IGeometryPath`](/slides/python-net/es/aspose.slides/igeometrypath). Las coordenadas deben ser relativas a la esquina superior izquierda de la forma.<br/>             Cambia el tipo de la forma ([`GeometryShape.shape_type`](/slides/python-net/es/aspose.slides/geometryshape/shape_type)) a [`ShapeType.CUSTOM`](/slides/python-net/es/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/es/aspose.slides/connector/create_shape_elements/#) | Crea y devuelve una matriz de los elementos de la forma. |
| [`reroute(self)`](/slides/python-net/es/aspose.slides/connector/reroute/#) | Redirige el conector de modo que tome la ruta más corta posible entre las formas que conecta. |

### Ver también
* clase [`Connector`](/slides/python-net/es/aspose.slides/connector)
* clase [`GeometryShape`](/slides/python-net/es/aspose.slides/geometryshape)
* clase [`Shape`](/slides/python-net/es/aspose.slides/shape)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)