---
title: VideoFrame class
second_title: Referencia de API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides/videoframe/
---
## VideoFrame clase

Representa un clip de vídeo en una diapositiva.

**Herencia:**[`VideoFrame`](/slides/python-net/es/aspose.slides/videoframe) → [`PictureFrame`](/slides/python-net/es/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/es/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/es/aspose.slides/shape)

El tipo VideoFrame expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`is_text_holder`](/slides/python-net/es/aspose.slides/videoframe/is_text_holder/) | Determina si la forma es TextHolder_PPT.<br/>            Solo lectura **bool**. |
| [`placeholder`](/slides/python-net/es/aspose.slides/videoframe/placeholder/) | Devuelve el marcador de posición de una forma. Devuelve None si la forma no tiene marcador de posición.<br/>            Solo lectura [`IPlaceholder`](/slides/python-net/es/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/es/aspose.slides/videoframe/custom_data/) | Devuelve los datos personalizados de la forma.<br/>            Solo lectura [`ICustomData`](/slides/python-net/es/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/es/aspose.slides/videoframe/raw_frame/) | Devuelve o establece las propiedades del marco de forma sin procesar.<br/>            Lectura/escritura [`IShapeFrame`](/slides/python-net/es/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/es/aspose.slides/videoframe/frame/) | Devuelve o establece las propiedades del marco de forma.<br/>            Lectura/escritura [`IShapeFrame`](/slides/python-net/es/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/es/aspose.slides/videoframe/line_format/) | Devuelve el objeto LineFormat que contiene las propiedades de formato de línea para una forma.<br/>            Nota: puede devolver None para ciertos tipos de formas que no tienen propiedades de línea.<br/>            Solo lectura [`ILineFormat`](/slides/python-net/es/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/es/aspose.slides/videoframe/three_d_format/) | Devuelve el objeto ThreeDFormat que contiene las propiedades de efecto 3D para una forma.<br/>            Nota: puede devolver None para ciertos tipos de formas que no tienen propiedades 3D.<br/>            Solo lectura [`IThreeDFormat`](/slides/python-net/es/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/es/aspose.slides/videoframe/effect_format/) | Devuelve el objeto EffectFormat que contiene los efectos de píxel aplicados a una forma.<br/>            Nota: puede devolver None para ciertos tipos de formas que no tienen propiedades de efecto.<br/>            Solo lectura [`IEffectFormat`](/slides/python-net/es/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/es/aspose.slides/videoframe/fill_format/) | Devuelve el objeto FillFormat que contiene las propiedades de formato de relleno para una forma.<br/>            Nota: puede devolver None para ciertos tipos de formas que no tienen propiedades de relleno.<br/>            Solo lectura [`IFillFormat`](/slides/python-net/es/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/es/aspose.slides/videoframe/hyperlink_click/) | Devuelve o establece el hipervínculo definido para el clic del ratón.<br/>            Lectura/escritura [`IHyperlink`](/slides/python-net/es/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/es/aspose.slides/videoframe/hyperlink_mouse_over/) | Devuelve o establece el hipervínculo definido para pasar el ratón por encima.<br/>            Lectura/escritura [`IHyperlink`](/slides/python-net/es/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/es/aspose.slides/videoframe/hyperlink_manager/) | Devuelve el gestor de hipervínculos.<br/>            Solo lectura [`IHyperlinkManager`](/slides/python-net/es/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/es/aspose.slides/videoframe/hidden/) | Determina si la forma está oculta.<br/>            Lectura/escritura **bool**. |
| [`z_order_position`](/slides/python-net/es/aspose.slides/videoframe/z_order_position/) | Devuelve la posición de una forma en el orden z.<br/>            Shapes[0] devuelve la forma que está al fondo del orden z,<br/>            y Shapes[Shapes.Count - 1] devuelve la forma que está al frente del orden z.<br/>            Solo lectura **int**. |
| [`connection_site_count`](/slides/python-net/es/aspose.slides/videoframe/connection_site_count/) | Devuelve el número de puntos de conexión en la forma.<br/>            Solo lectura **int**. |
| [`rotation`](/slides/python-net/es/aspose.slides/videoframe/rotation/) | Devuelve o establece el número de grados que la forma especificada está rotada alrededor del eje z.<br/>            Un valor positivo indica rotación en sentido horario; un valor negativo indica rotación en sentido antihorario.<br/>            Lectura/escritura **float**. |
| [`x`](/slides/python-net/es/aspose.slides/videoframe/x/) | Obtiene o establece la coordenada x de la esquina superior izquierda de la forma, medida en puntos.<br/>            Lectura/escritura **float**. |
| [`y`](/slides/python-net/es/aspose.slides/videoframe/y/) | Obtiene o establece la coordenada y de la esquina superior izquierda de la forma, medida en puntos.<br/>            Lectura/escritura **float**. |
| [`width`](/slides/python-net/es/aspose.slides/videoframe/width/) | Obtiene o establece el ancho de la forma, medido en puntos.<br/>            Lectura/escritura **float**. |
| [`height`](/slides/python-net/es/aspose.slides/videoframe/height/) | Obtiene o establece la altura de la forma, medida en puntos.<br/>            Lectura/escritura **float**. |
| [`black_white_mode`](/slides/python-net/es/aspose.slides/videoframe/black_white_mode/) | La propiedad especifica cómo se renderizará una forma en modo de visualización en blanco y negro..<br/>            Lectura/escritura [`BlackWhiteMode`](/slides/python-net/es/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/es/aspose.slides/videoframe/unique_id/) | Devuelve un identificador interno de ámbito de presentación destinado al uso por complementos u otro código.<br/>            Debido a que este valor puede ser reasignado por el usuario o programáticamente, no debe ser tratado<br/>            como una clave única persistente.<br/>            Solo lectura **int**.<br/>            Ver también [`Shape.office_interop_shape_id`](/slides/python-net/es/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/es/aspose.slides/videoframe/office_interop_shape_id/) | Devuelve un identificador único de ámbito de diapositiva que permanece constante durante la vida útil de la forma y<br/>            permite que PowerPoint o el código de interoperabilidad referencien la forma de forma fiable desde cualquier parte del documento.<br/>            Solo lectura **int**.<br/>            Ver también [`Shape.unique_id`](/slides/python-net/es/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/es/aspose.slides/videoframe/alternative_text/) | Devuelve o establece el texto alternativo asociado a una forma.<br/>            Lectura/escritura **str**. |
| [`alternative_text_title`](/slides/python-net/es/aspose.slides/videoframe/alternative_text_title/) | Devuelve o establece el título del texto alternativo asociado a una forma.<br/>            Lectura/escritura **str**. |
| [`name`](/slides/python-net/es/aspose.slides/videoframe/name/) | Devuelve o establece el nombre de una forma.<br/>            No debe ser None. Use una cadena vacía si es necesario.<br/>            Lectura/escritura **str**. |
| [`is_decorative`](/slides/python-net/es/aspose.slides/videoframe/is_decorative/) | Obtiene o establece la opción 'Marcar como decorativo'<br/>            Lectura/escritura **bool**. |
| [`shape_lock`](/slides/python-net/es/aspose.slides/videoframe/shape_lock/) | Devuelve los bloqueos de la forma.<br/>            Solo lectura [`IPictureFrameLock`](/slides/python-net/es/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/es/aspose.slides/videoframe/is_grouped/) | Determina si la forma está agrupada.<br/>            Solo lectura **bool**. |
| [`parent_group`](/slides/python-net/es/aspose.slides/videoframe/parent_group/) | Devuelve el objeto GroupShape padre si la forma está agrupada. De lo contrario devuelve None.<br/>            Solo lectura [`IGroupShape`](/slides/python-net/es/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/es/aspose.slides/videoframe/slide/) | Devuelve la diapositiva padre de una forma.<br/>            Solo lectura [`IBaseSlide`](/slides/python-net/es/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/es/aspose.slides/videoframe/presentation/) | Devuelve la presentación padre de una diapositiva.<br/>            Solo lectura [`IPresentation`](/slides/python-net/es/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/es/aspose.slides/videoframe/shape_style/) | Devuelve el objeto de estilo de la forma.<br/>            Solo lectura [`IShapeStyle`](/slides/python-net/es/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/es/aspose.slides/videoframe/shape_type/) | Devuelve o establece el tipo AutoShape para un PictureFrame.<br/>            Todos los elementos del conjunto [`ShapeType`](/slides/python-net/es/aspose.slides/shapetype) son permitidos,<br/>            excepto los tipos de línea:<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            Lectura/escritura [`ShapeType`](/slides/python-net/es/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/es/aspose.slides/videoframe/adjustments/) | Devuelve una colección de valores de ajuste de la forma.<br/>            Solo lectura [`IAdjustValueCollection`](/slides/python-net/es/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/es/aspose.slides/videoframe/picture_frame_lock/) | Devuelve los bloqueos de la forma.<br/>            Solo lectura [`IPictureFrameLock`](/slides/python-net/es/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/es/aspose.slides/videoframe/picture_format/) | Devuelve el objeto PictureFillFormat para un marco de imagen.<br/>            Solo lectura [`IPictureFillFormat`](/slides/python-net/es/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/es/aspose.slides/videoframe/relative_scale_height/) | Devuelve o establece la escala de altura (relativa al tamaño original de la imagen) del marco de imagen. El valor 1.0 corresponde al 100%.<br/>            Lectura/escritura **float**. |
| [`relative_scale_width`](/slides/python-net/es/aspose.slides/videoframe/relative_scale_width/) | Devuelve o establece la escala de anchura (relativa al tamaño original de la imagen) del marco de imagen. El valor 1.0 corresponde al 100%.<br/>            Lectura/escritura **float**. |
| [`is_cameo`](/slides/python-net/es/aspose.slides/videoframe/is_cameo/) | Determina si el PictureFrame es un objeto Cameo o no.<br/>            Solo lectura **bool**. |
| [`rewind_video`](/slides/python-net/es/aspose.slides/videoframe/rewind_video/) | Determina si un video se rebobina automáticamente al inicio<br/>            tan pronto como la película ha terminado de reproducirse.<br/>            Lectura/escritura **bool**. |
| [`play_loop_mode`](/slides/python-net/es/aspose.slides/videoframe/play_loop_mode/) | Determina si un video se reproduce en bucle.<br/>            Lectura/escritura **bool**. |
| [`hide_at_showing`](/slides/python-net/es/aspose.slides/videoframe/hide_at_showing/) | Determina si un VideoFrame está oculto.<br/>            Lectura/escritura **bool**. |
| [`volume`](/slides/python-net/es/aspose.slides/videoframe/volume/) | Devuelve o establece el volumen de audio.<br/>            Lectura/escritura [`AudioVolumeMode`](/slides/python-net/es/aspose.slides/audiovolumemode). |
| [`play_mode`](/slides/python-net/es/aspose.slides/videoframe/play_mode/) | Devuelve o establece el modo de reproducción del video.<br/>            Lectura/escritura [`VideoPlayModePreset`](/slides/python-net/es/aspose.slides/videoplaymodepreset). |
| [`full_screen_mode`](/slides/python-net/es/aspose.slides/videoframe/full_screen_mode/) | Determina si un video se muestra en modo pantalla completa.<br/>            Lectura/escritura **bool**. |
| [`link_path_long`](/slides/python-net/es/aspose.slides/videoframe/link_path_long/) | Devuelve o establece el nombre de un archivo de video que está vinculado a un VideoFrame.<br/>            Lectura/escritura **str**. |
| [`embedded_video`](/slides/python-net/es/aspose.slides/videoframe/embedded_video/) | Devuelve o establece el objeto de video incrustado.<br/>            Lectura/escritura [`IVideo`](/slides/python-net/es/aspose.slides/ivideo). |
| [`trim_from_start`](/slides/python-net/es/aspose.slides/videoframe/trim_from_start/) | Inicio de recorte [ms] |
| [`trim_from_end`](/slides/python-net/es/aspose.slides/videoframe/trim_from_end/) | Fin de recorte [ms] |
| [`caption_tracks`](/slides/python-net/es/aspose.slides/videoframe/caption_tracks/) | Obtiene la colección de subtítulos cerrados asociados al marco de video.<br/>            Esta propiedad es solo lectura y devuelve un [`ICaptionsCollection`](/slides/python-net/es/aspose.slides/icaptionscollection) que contiene todas las pistas de subtítulos. |

## Métodos

| Método | Descripción |
| :- | :- |
| [`get_image(self)`](/slides/python-net/es/aspose.slides/videoframe/get_image/#) | Devuelve la miniatura de la forma.<br/>            Se usa por defecto el tipo ShapeThumbnailBounds.Shape para los límites de la miniatura. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/es/aspose.slides/videoframe/get_image/#shapethumbnailbounds-float-float) | Devuelve la miniatura de la forma. |
| [`write_as_svg(self, stream)`](/slides/python-net/es/aspose.slides/videoframe/write_as_svg/#iorawiobase) | Guarda el contenido de la forma como archivo SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/es/aspose.slides/videoframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Guarda el contenido de la forma como archivo SVG. |
| [`remove_placeholder(self)`](/slides/python-net/es/aspose.slides/videoframe/remove_placeholder/#) | Define que esta forma no es un marcador de posición. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/es/aspose.slides/videoframe/add_placeholder/#iplaceholder) | Añade un nuevo marcador de posición si no existe y establece las propiedades del marcador de posición a una especificada. |
| [`get_base_placeholder(self)`](/slides/python-net/es/aspose.slides/videoframe/get_base_placeholder/#) | Devuelve una forma de marcador de posición básica (forma del diseño y/o diapositiva maestra de la que la forma actual hereda).<br/>            Se devuelve None si la forma actual no hereda. |
| [`get_visual_bounds(self)`](/slides/python-net/es/aspose.slides/videoframe/get_visual_bounds/#) | Obtiene los límites visuales de la forma calculados a partir de su contenido renderizado. |
| [`get_geometry_paths(self)`](/slides/python-net/es/aspose.slides/videoframe/get_geometry_paths/#) | Devuelve una copia de la ruta de la forma geométrica. Las coordenadas son relativas a la esquina superior izquierda de la forma. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/es/aspose.slides/videoframe/set_geometry_path/#igeometrypath) | Actualiza la geometría de la forma a partir del objeto [`IGeometryPath`](/slides/python-net/es/aspose.slides/igeometrypath). Las coordenadas deben ser relativas a la esquina superior izquierda de la forma.<br/>            Cambia el tipo de la forma ([`GeometryShape.shape_type`](/slides/python-net/es/aspose.slides/geometryshape/shape_type)) a [`ShapeType.CUSTOM`](/slides/python-net/es/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/es/aspose.slides/videoframe/set_geometry_paths/#listigeometrypath) | Actualiza la geometría de la forma a partir de una matriz de [`IGeometryPath`](/slides/python-net/es/aspose.slides/igeometrypath). Las coordenadas deben ser relativas a la esquina superior izquierda de la forma.<br/>            Cambia el tipo de la forma ([`GeometryShape.shape_type`](/slides/python-net/es/aspose.slides/geometryshape/shape_type)) a [`ShapeType.CUSTOM`](/slides/python-net/es/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/es/aspose.slides/videoframe/create_shape_elements/#) | Crea y devuelve una matriz de los elementos de la forma. |

### Ver también
* clase [`GeometryShape`](/slides/python-net/es/aspose.slides/geometryshape)
* clase [`PictureFrame`](/slides/python-net/es/aspose.slides/pictureframe)
* clase [`Shape`](/slides/python-net/es/aspose.slides/shape)
* clase [`VideoFrame`](/slides/python-net/es/aspose.slides/videoframe)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)