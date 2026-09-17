---
title: AudioFrame class
second_title: Referencia de la API de Aspose.Slides para Python mediante .NET
description: 
type: docs
url: /es/aspose.slides/audioframe/
---
## AudioFrame clase

Representa un clip de audio en una diapositiva.

**Inheritance:**[`AudioFrame`](/slides/python-net/es/aspose.slides/audioframe) → [`PictureFrame`](/slides/python-net/es/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/es/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/es/aspose.slides/shape)

El tipo AudioFrame expone los siguientes miembros:

## Propiedades

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/es/aspose.slides/audioframe/is_text_holder/) | Determina si la forma es TextHolder_PPT.<br/>            Solo lectura **bool**. |
| [`placeholder`](/slides/python-net/es/aspose.slides/audioframe/placeholder/) | Devuelve el marcador de posición de una forma. Devuelve None si la forma no tiene marcador de posición.<br/>            Solo lectura [`IPlaceholder`](/slides/python-net/es/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/es/aspose.slides/audioframe/custom_data/) | Devuelve los datos personalizados de la forma.<br/>            Solo lectura [`ICustomData`](/slides/python-net/es/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/es/aspose.slides/audioframe/raw_frame/) | Devuelve o establece las propiedades sin procesar del marco de la forma.<br/>            Lectura/escritura [`IShapeFrame`](/slides/python-net/es/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/es/aspose.slides/audioframe/frame/) | Devuelve o establece las propiedades del marco de la forma.<br/>            Lectura/escritura [`IShapeFrame`](/slides/python-net/es/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/es/aspose.slides/audioframe/line_format/) | Devuelve el objeto LineFormat que contiene las propiedades de formato de línea para una forma.<br/>            Nota: puede devolver None para ciertos tipos de formas que no tienen propiedades de línea.<br/>            Solo lectura [`ILineFormat`](/slides/python-net/es/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/es/aspose.slides/audioframe/three_d_format/) | Devuelve el objeto ThreeDFormat que contiene las propiedades de efecto 3D para una forma.<br/>            Nota: puede devolver None para ciertos tipos de formas que no tienen propiedades 3D.<br/>            Solo lectura [`IThreeDFormat`](/slides/python-net/es/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/es/aspose.slides/audioframe/effect_format/) | Devuelve el objeto EffectFormat que contiene los efectos de píxel aplicados a una forma.<br/>            Nota: puede devolver None para ciertos tipos de formas que no tienen propiedades de efecto.<br/>            Solo lectura [`IEffectFormat`](/slides/python-net/es/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/es/aspose.slides/audioframe/fill_format/) | Devuelve el objeto FillFormat que contiene las propiedades de formato de relleno para una forma.<br/>            Nota: puede devolver None para ciertos tipos de formas que no tienen propiedades de relleno.<br/>            Solo lectura [`IFillFormat`](/slides/python-net/es/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/es/aspose.slides/audioframe/hyperlink_click/) | Devuelve o establece el hipervínculo definido para clic del ratón.<br/>            Lectura/escritura [`IHyperlink`](/slides/python-net/es/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/es/aspose.slides/audioframe/hyperlink_mouse_over/) | Devuelve o establece el hipervínculo definido para pasar el ratón por encima.<br/>            Lectura/escritura [`IHyperlink`](/slides/python-net/es/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/es/aspose.slides/audioframe/hyperlink_manager/) | Devuelve el gestor de hipervínculos.<br/>            Solo lectura [`IHyperlinkManager`](/slides/python-net/es/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/es/aspose.slides/audioframe/hidden/) | Determina si la forma está oculta.<br/>            Lectura/escritura **bool**. |
| [`z_order_position`](/slides/python-net/es/aspose.slides/audioframe/z_order_position/) | Devuelve la posición de una forma en el orden z.<br/>            Shapes[0] devuelve la forma que está al fondo del orden z,<br/>            y Shapes[Shapes.Count - 1] devuelve la forma que está al frente del orden z.<br/>            Solo lectura **int**. |
| [`connection_site_count`](/slides/python-net/es/aspose.slides/audioframe/connection_site_count/) | Devuelve el número de puntos de conexión en la forma.<br/>            Solo lectura **int**. |
| [`rotation`](/slides/python-net/es/aspose.slides/audioframe/rotation/) | Devuelve o establece el número de grados que la forma especificada está rotada alrededor del eje z.<br/>            Un valor positivo indica rotación en sentido horario; un valor negativo indica rotación en sentido antihorario.<br/>            Lectura/escritura **float**. |
| [`x`](/slides/python-net/es/aspose.slides/audioframe/x/) | Obtiene o establece la coordenada x de la esquina superior-izquierda de la forma, medida en puntos.<br/>            Lectura/escritura **float**. |
| [`y`](/slides/python-net/es/aspose.slides/audioframe/y/) | Obtiene o establece la coordenada y de la esquina superior-izquierda de la forma, medida en puntos.<br/>            Lectura/escritura **float**. |
| [`width`](/slides/python-net/es/aspose.slides/audioframe/width/) | Obtiene o establece el ancho de la forma, medido en puntos.<br/>            Lectura/escritura **float**. |
| [`height`](/slides/python-net/es/aspose.slides/audioframe/height/) | Obtiene o establece la altura de la forma, medida en puntos.<br/>            Lectura/escritura **float**. |
| [`black_white_mode`](/slides/python-net/es/aspose.slides/audioframe/black_white_mode/) | La propiedad especifica cómo se representará una forma en modo de visualización en blanco y negro.<br/>            Lectura/escritura [`BlackWhiteMode`](/slides/python-net/es/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/es/aspose.slides/audioframe/unique_id/) | Devuelve un identificador interno, con alcance a la presentación, destinado al uso de complementos u otro código.<br/>            Debido a que este valor puede ser reasignado por el usuario o programáticamente, no debe tratarse<br/>            como una clave única persistente.<br/>            Solo lectura **int**.<br/>            Ver también [`Shape.office_interop_shape_id`](/slides/python-net/es/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/es/aspose.slides/audioframe/office_interop_shape_id/) | Devuelve un identificador único con alcance a la diapositiva que permanece constante durante la vida útil de la forma y<br/>            permite que PowerPoint o el código de interop la referencie de forma fiable desde cualquier parte del documento.<br/>            Solo lectura **int**.<br/>            Ver también [`Shape.unique_id`](/slides/python-net/es/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/es/aspose.slides/audioframe/alternative_text/) | Devuelve o establece el texto alternativo asociado a una forma.<br/>            Lectura/escritura **str**. |
| [`alternative_text_title`](/slides/python-net/es/aspose.slides/audioframe/alternative_text_title/) | Devuelve o establece el título del texto alternativo asociado a una forma.<br/>            Lectura/escritura **str**. |
| [`name`](/slides/python-net/es/aspose.slides/audioframe/name/) | Devuelve o establece el nombre de una forma.<br/>            No debe ser None. Use una cadena vacía si es necesario.<br/>            Lectura/escritura **str**. |
| [`is_decorative`](/slides/python-net/es/aspose.slides/audioframe/is_decorative/) | Obtiene o establece la opción 'Marcar como decorativo'<br/>            Lectura/escritura **bool**. |
| [`shape_lock`](/slides/python-net/es/aspose.slides/audioframe/shape_lock/) | Devuelve los bloqueos de la forma.<br/>            Solo lectura [`IPictureFrameLock`](/slides/python-net/es/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/es/aspose.slides/audioframe/is_grouped/) | Determina si la forma está agrupada.<br/>            Solo lectura **bool**. |
| [`parent_group`](/slides/python-net/es/aspose.slides/audioframe/parent_group/) | Devuelve el objeto GroupShape padre si la forma está agrupada. De lo contrario devuelve None.<br/>            Solo lectura [`IGroupShape`](/slides/python-net/es/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/es/aspose.slides/audioframe/slide/) | Devuelve la diapositiva padre de una forma.<br/>            Solo lectura [`IBaseSlide`](/slides/python-net/es/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/es/aspose.slides/audioframe/presentation/) | Devuelve la presentación padre de una diapositiva.<br/>            Solo lectura [`IPresentation`](/slides/python-net/es/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/es/aspose.slides/audioframe/shape_style/) | Devuelve el objeto de estilo de la forma.<br/>            Solo lectura [`IShapeStyle`](/slides/python-net/es/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/es/aspose.slides/audioframe/shape_type/) | Devuelve o establece el tipo AutoShape para un PictureFrame.<br/>            Todos los elementos del conjunto [`ShapeType`](/slides/python-net/es/aspose.slides/shapetype) son válidos, <br/>            excepto los siguientes tipos de línea:<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            Lectura/escritura [`ShapeType`](/slides/python-net/es/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/es/aspose.slides/audioframe/adjustments/) | Devuelve una colección de valores de ajuste de la forma.<br/>            Solo lectura [`IAdjustValueCollection`](/slides/python-net/es/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/es/aspose.slides/audioframe/picture_frame_lock/) | Devuelve los bloqueos de la forma.<br/>            Solo lectura [`IPictureFrameLock`](/slides/python-net/es/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/es/aspose.slides/audioframe/picture_format/) | Devuelve el objeto PictureFillFormat para un marco de imagen.<br/>            Solo lectura [`IPictureFillFormat`](/slides/python-net/es/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/es/aspose.slides/audioframe/relative_scale_height/) | Devuelve o establece la escala de altura (relativa al tamaño original de la imagen) del marco de imagen. Un valor de 1.0 corresponde al 100%.<br/>            Lectura/escritura **float**. |
| [`relative_scale_width`](/slides/python-net/es/aspose.slides/audioframe/relative_scale_width/) | Devuelve o establece la escala de ancho (relativa al tamaño original de la imagen) del marco de imagen. Un valor de 1.0 corresponde al 100%.<br/>            Lectura/escritura **float**. |
| [`is_cameo`](/slides/python-net/es/aspose.slides/audioframe/is_cameo/) | Determina si el PictureFrame es un objeto Cameo o no.<br/>            Solo lectura **bool**. |
| [`audio_cd_start_track`](/slides/python-net/es/aspose.slides/audioframe/audio_cd_start_track/) | Devuelve o establece un índice de pista inicial.<br/>            Lectura/escritura **int**. |
| [`audio_cd_start_track_time`](/slides/python-net/es/aspose.slides/audioframe/audio_cd_start_track_time/) | Devuelve o establece un tiempo de pista inicial.<br/>            Lectura/escritura **int**. |
| [`audio_cd_end_track`](/slides/python-net/es/aspose.slides/audioframe/audio_cd_end_track/) | Devuelve o establece un índice de pista final<br/>            Lectura/escritura **int**. |
| [`audio_cd_end_track_time`](/slides/python-net/es/aspose.slides/audioframe/audio_cd_end_track_time/) | Devuelve o establece un tiempo de pista final.<br/>            Lectura/escritura **int**. |
| [`volume`](/slides/python-net/es/aspose.slides/audioframe/volume/) | Devuelve o establece el volumen del audio.<br/>            Lectura/escritura [`AudioVolumeMode`](/slides/python-net/es/aspose.slides/audiovolumemode). |
| [`play_mode`](/slides/python-net/es/aspose.slides/audioframe/play_mode/) | Devuelve o establece el modo de reproducción del audio.<br/>            Lectura/escritura [`AudioPlayModePreset`](/slides/python-net/es/aspose.slides/audioplaymodepreset). |
| [`hide_at_showing`](/slides/python-net/es/aspose.slides/audioframe/hide_at_showing/) | Determina si un AudioFrame está oculto.<br/>            Lectura/escritura **bool**. |
| [`play_loop_mode`](/slides/python-net/es/aspose.slides/audioframe/play_loop_mode/) | Determina si un audio está en bucle.<br/>            Lectura/escritura **bool**. |
| [`play_across_slides`](/slides/python-net/es/aspose.slides/audioframe/play_across_slides/) | Determina si el audio se reproduce a través de las diapositivas.<br/>            Lectura/escritura **bool**. |
| [`rewind_audio`](/slides/python-net/es/aspose.slides/audioframe/rewind_audio/) | Determina si el audio se rebobina automáticamente al inicio después de reproducirse.<br/>            Lectura/escritura **bool**. |
| [`embedded`](/slides/python-net/es/aspose.slides/audioframe/embedded/) | Determina si un sonido está incrustado en una presentación.<br/>            Solo lectura **bool**. |
| [`link_path_long`](/slides/python-net/es/aspose.slides/audioframe/link_path_long/) | Devuelve o establece el nombre de un archivo de audio que está enlazado a un AudioFrame.<br/>            Lectura/escritura **str**. |
| [`embedded_audio`](/slides/python-net/es/aspose.slides/audioframe/embedded_audio/) | Devuelve o establece el objeto de audio incrustado.<br/>            Lectura/escritura [`IAudio`](/slides/python-net/es/aspose.slides/iaudio). |
| [`fade_in_duration`](/slides/python-net/es/aspose.slides/audioframe/fade_in_duration/) | Especifica la duración del fundido de entrada inicial del medio en milisegundos.<br/>            Lectura/escritura **float**. |
| [`fade_out_duration`](/slides/python-net/es/aspose.slides/audioframe/fade_out_duration/) | Especifica la duración del fundido de salida final del medio en milisegundos.<br/>            Lectura/escritura **float**. |
| [`volume_value`](/slides/python-net/es/aspose.slides/audioframe/volume_value/) | Devuelve o establece el volumen del audio en porcentajes.<br/>            Lectura/escritura **float**. |
| [`trim_from_start`](/slides/python-net/es/aspose.slides/audioframe/trim_from_start/) | Especifica la duración a eliminar del inicio del medio durante la reproducción, en milisegundos.<br/>            Lectura/escritura **float**. |
| [`trim_from_end`](/slides/python-net/es/aspose.slides/audioframe/trim_from_end/) | Especifica la duración a eliminar del final del medio durante la reproducción, en milisegundos.<br/>            Lectura/escritura **float**. |
| [`caption_tracks`](/slides/python-net/es/aspose.slides/audioframe/caption_tracks/) | Obtiene la colección de subtítulos cerrados asociados al marco de audio.<br/>            Esta propiedad es solo lectura y devuelve un [`ICaptionsCollection`](/slides/python-net/es/aspose.slides/icaptionscollection) que contiene todas las pistas de subtítulos. |

## Métodos

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/es/aspose.slides/audioframe/get_image/#) | Devuelve la miniatura de la forma.<br/>            Se usa por defecto el tipo ShapeThumbnailBounds.Shape para los límites de la miniatura. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/es/aspose.slides/audioframe/get_image/#shapethumbnailbounds-float-float) | Devuelve la miniatura de la forma. |
| [`write_as_svg(self, stream)`](/slides/python-net/es/aspose.slides/audioframe/write_as_svg/#iorawiobase) | Guarda el contenido de la Forma como archivo SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/es/aspose.slides/audioframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Guarda el contenido de la Forma como archivo SVG. |
| [`remove_placeholder(self)`](/slides/python-net/es/aspose.slides/audioframe/remove_placeholder/#) | Define que esta forma no es un marcador de posición. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/es/aspose.slides/audioframe/add_placeholder/#iplaceholder) | Añade un nuevo marcador de posición si no existe y establece las propiedades del marcador de posición a una especificada. |
| [`get_base_placeholder(self)`](/slides/python-net/es/aspose.slides/audioframe/get_base_placeholder/#) | Devuelve una forma de marcador de posición básica (forma del diseño y/o diapositiva maestra de la que la forma actual hereda).<br/>            Se devuelve None si la forma actual no hereda. |
| [`get_visual_bounds(self)`](/slides/python-net/es/aspose.slides/audioframe/get_visual_bounds/#) | Obtiene los límites visuales de la forma calculados a partir de su contenido renderizado. |
| [`get_geometry_paths(self)`](/slides/python-net/es/aspose.slides/audioframe/get_geometry_paths/#) | Devuelve una copia de la ruta de la forma geométrica. Las coordenadas son relativas a la esquina superior izquierda de la forma. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/es/aspose.slides/audioframe/set_geometry_path/#igeometrypath) | Actualiza la geometría de la forma a partir del objeto [`IGeometryPath`](/slides/python-net/es/aspose.slides/igeometrypath). Las coordenadas deben ser relativas a la esquina superior izquierda de la forma.<br/>            Cambia el tipo de la forma ([`GeometryShape.shape_type`](/slides/python-net/es/aspose.slides/geometryshape/shape_type)) a [`ShapeType.CUSTOM`](/slides/python-net/es/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/es/aspose.slides/audioframe/set_geometry_paths/#listigeometrypath) | Actualiza la geometría de la forma a partir de una matriz de [`IGeometryPath`](/slides/python-net/es/aspose.slides/igeometrypath). Las coordenadas deben ser relativas a la esquina superior izquierda de la forma.<br/>            Cambia el tipo de la forma ([`GeometryShape.shape_type`](/slides/python-net/es/aspose.slides/geometryshape/shape_type)) a [`ShapeType.CUSTOM`](/slides/python-net/es/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/es/aspose.slides/audioframe/create_shape_elements/#) | Crea y devuelve una matriz de los elementos de la forma. |

### Ver también
* clase [`AudioFrame`](/slides/python-net/es/aspose.slides/audioframe)
* clase [`GeometryShape`](/slides/python-net/es/aspose.slides/geometryshape)
* clase [`PictureFrame`](/slides/python-net/es/aspose.slides/pictureframe)
* clase [`Shape`](/slides/python-net/es/aspose.slides/shape)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)