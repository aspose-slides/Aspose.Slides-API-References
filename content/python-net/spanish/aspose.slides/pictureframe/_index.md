---
title: PictureFrame class
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/pictureframe/
---
## Clase PictureFrame

Representa un marco con una imagen dentro.

**Herencia:**[`PictureFrame`](/slides/python-net/es/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/es/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/es/aspose.slides/shape)

El tipo PictureFrame expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`is_text_holder`](/slides/python-net/es/aspose.slides/pictureframe/is_text_holder/) | Determina si la forma es TextHolder_PPT.<br/>            Solo lectura **bool**. |
| [`placeholder`](/slides/python-net/es/aspose.slides/pictureframe/placeholder/) | Devuelve el marcador de posición para una forma. Devuelve None si la forma no tiene marcador de posición.<br/>            Solo lectura [`IPlaceholder`](/slides/python-net/es/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/es/aspose.slides/pictureframe/custom_data/) | Devuelve los datos personalizados de la forma.<br/>            Solo lectura [`ICustomData`](/slides/python-net/es/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/es/aspose.slides/pictureframe/raw_frame/) | Devuelve o establece las propiedades del marco de la forma sin procesar.<br/>            Lectura/Escritura [`IShapeFrame`](/slides/python-net/es/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/es/aspose.slides/pictureframe/frame/) | Devuelve o establece las propiedades del marco de la forma.<br/>            Lectura/Escritura [`IShapeFrame`](/slides/python-net/es/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/es/aspose.slides/pictureframe/line_format/) | Devuelve el objeto LineFormat que contiene las propiedades de formato de línea para una forma.<br/>            Nota: puede devolver None para ciertos tipos de formas que no tienen propiedades de línea.<br/>            Solo lectura [`ILineFormat`](/slides/python-net/es/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/es/aspose.slides/pictureframe/three_d_format/) | Devuelve el objeto ThreeDFormat que contiene las propiedades de efecto 3D para una forma.<br/>            Nota: puede devolver None para ciertos tipos de formas que no tienen propiedades 3D.<br/>            Solo lectura [`IThreeDFormat`](/slides/python-net/es/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/es/aspose.slides/pictureframe/effect_format/) | Devuelve el objeto EffectFormat que contiene los efectos de píxel aplicados a una forma.<br/>            Nota: puede devolver None para ciertos tipos de formas que no tienen propiedades de efecto.<br/>            Solo lectura [`IEffectFormat`](/slides/python-net/es/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/es/aspose.slides/pictureframe/fill_format/) | Devuelve el objeto FillFormat que contiene las propiedades de formato de relleno para una forma.<br/>            Nota: puede devolver None para ciertos tipos de formas que no tienen propiedades de relleno.<br/>            Solo lectura [`IFillFormat`](/slides/python-net/es/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/es/aspose.slides/pictureframe/hyperlink_click/) | Devuelve o establece el hipervínculo definido para clic del ratón.<br/>            Lectura/Escritura [`IHyperlink`](/slides/python-net/es/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/es/aspose.slides/pictureframe/hyperlink_mouse_over/) | Devuelve o establece el hipervínculo definido para pasar el ratón por encima.<br/>            Lectura/Escritura [`IHyperlink`](/slides/python-net/es/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/es/aspose.slides/pictureframe/hyperlink_manager/) | Devuelve el administrador de hipervínculos.<br/>            Solo lectura [`IHyperlinkManager`](/slides/python-net/es/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/es/aspose.slides/pictureframe/hidden/) | Determina si la forma está oculta.<br/>            Lectura/Escritura **bool**. |
| [`z_order_position`](/slides/python-net/es/aspose.slides/pictureframe/z_order_position/) | Devuelve la posición de una forma en el orden z.<br/>            Shapes[0] devuelve la forma en la parte posterior del orden z,<br/>            y Shapes[Shapes.Count - 1] devuelve la forma en la parte frontal del orden z.<br/>            Solo lectura **int**. |
| [`connection_site_count`](/slides/python-net/es/aspose.slides/pictureframe/connection_site_count/) | Devuelve el número de puntos de conexión en la forma.<br/>            Solo lectura **int**. |
| [`rotation`](/slides/python-net/es/aspose.slides/pictureframe/rotation/) | Devuelve o establece el número de grados que la forma especificada está rotada alrededor<br/>            del eje z. Un valor positivo indica rotación en sentido horario; un valor negativo<br/>            indica rotación en sentido antihorario.<br/>            Lectura/Escritura **float**. |
| [`x`](/slides/python-net/es/aspose.slides/pictureframe/x/) | Obtiene o establece la coordenada x de la esquina superior izquierda de la forma, medida en puntos.<br/>            Lectura/Escritura **float**. |
| [`y`](/slides/python-net/es/aspose.slides/pictureframe/y/) | Obtiene o establece la coordenada y de la esquina superior izquierda de la forma, medida en puntos.<br/>            Lectura/Escritura **float**. |
| [`width`](/slides/python-net/es/aspose.slides/pictureframe/width/) | Obtiene o establece el ancho de la forma, medido en puntos.<br/>            Lectura/Escritura **float**. |
| [`height`](/slides/python-net/es/aspose.slides/pictureframe/height/) | Obtiene o establece la altura de la forma, medida en puntos.<br/>            Lectura/Escritura **float**. |
| [`black_white_mode`](/slides/python-net/es/aspose.slides/pictureframe/black_white_mode/) | La propiedad especifica cómo se renderizará una forma en modo de visualización en blanco y negro.<br/>            Lectura/Escritura [`BlackWhiteMode`](/slides/python-net/es/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/es/aspose.slides/pictureframe/unique_id/) | Devuelve un identificador interno, con alcance de presentación, destinado a ser usado por complementos u otro código.<br/>            Debido a que este valor puede ser reasignado por el usuario o programáticamente, no debe ser tratado<br/>            como una clave única persistente.<br/>            Solo lectura **int**.<br/>            Ver también [`Shape.office_interop_shape_id`](/slides/python-net/es/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/es/aspose.slides/pictureframe/office_interop_shape_id/) | Devuelve un identificador único con alcance de diapositiva que permanece constante durante la vida útil de la forma y<br/>            permite que PowerPoint o el código de interoperabilidad referencien la forma de forma fiable desde cualquier parte del documento.<br/>            Solo lectura **int**.<br/>            Ver también [`Shape.unique_id`](/slides/python-net/es/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/es/aspose.slides/pictureframe/alternative_text/) | Devuelve o establece el texto alternativo asociado a una forma.<br/>            Lectura/Escritura **str**. |
| [`alternative_text_title`](/slides/python-net/es/aspose.slides/pictureframe/alternative_text_title/) | Devuelve o establece el título del texto alternativo asociado a una forma.<br/>            Lectura/Escritura **str**. |
| [`name`](/slides/python-net/es/aspose.slides/pictureframe/name/) | Devuelve o establece el nombre de una forma.<br/>            No debe ser None. Use una cadena vacía si es necesario.<br/>            Lectura/Escritura **str**. |
| [`is_decorative`](/slides/python-net/es/aspose.slides/pictureframe/is_decorative/) | Obtiene o establece la opción 'Marcar como decorativo'<br/>            Lectura/Escritura **bool**. |
| [`shape_lock`](/slides/python-net/es/aspose.slides/pictureframe/shape_lock/) | Devuelve los bloqueos de la forma.<br/>            Solo lectura [`IPictureFrameLock`](/slides/python-net/es/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/es/aspose.slides/pictureframe/is_grouped/) | Determina si la forma está agrupada.<br/>            Solo lectura **bool**. |
| [`parent_group`](/slides/python-net/es/aspose.slides/pictureframe/parent_group/) | Devuelve el objeto GroupShape padre si la forma está agrupada. De lo contrario devuelve None.<br/>            Solo lectura [`IGroupShape`](/slides/python-net/es/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/es/aspose.slides/pictureframe/slide/) | Devuelve la diapositiva padre de una forma.<br/>            Solo lectura [`IBaseSlide`](/slides/python-net/es/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/es/aspose.slides/pictureframe/presentation/) | Devuelve la presentación padre de una diapositiva.<br/>            Solo lectura [`IPresentation`](/slides/python-net/es/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/es/aspose.slides/pictureframe/shape_style/) | Devuelve el objeto de estilo de la forma.<br/>            Solo lectura [`IShapeStyle`](/slides/python-net/es/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/es/aspose.slides/pictureframe/shape_type/) | Devuelve o establece el tipo AutoShape para un PictureFrame.<br/>            Son válidos todos los elementos del conjunto [`ShapeType`](/slides/python-net/es/aspose.slides/shapetype), <br/>            excepto todo tipo de líneas:<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            Lectura/Escritura [`ShapeType`](/slides/python-net/es/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/es/aspose.slides/pictureframe/adjustments/) | Devuelve una colección de valores de ajuste de la forma.<br/>            Solo lectura [`IAdjustValueCollection`](/slides/python-net/es/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/es/aspose.slides/pictureframe/picture_frame_lock/) | Devuelve los bloqueos de la forma.<br/>            Solo lectura [`IPictureFrameLock`](/slides/python-net/es/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/es/aspose.slides/pictureframe/picture_format/) | Devuelve el objeto PictureFillFormat para un marco de imagen.<br/>            Solo lectura [`IPictureFillFormat`](/slides/python-net/es/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/es/aspose.slides/pictureframe/relative_scale_height/) | Devuelve o establece la escala de altura (relativa al tamaño original de la imagen) del marco de imagen. El valor 1.0 corresponde al 100%.<br/>            Lectura/Escritura **float**. |
| [`relative_scale_width`](/slides/python-net/es/aspose.slides/pictureframe/relative_scale_width/) | Devuelve o establece la escala de ancho (relativa al tamaño original de la imagen) del marco de imagen. El valor 1.0 corresponde al 100%.<br/>            Lectura/Escritura **float**. |
| [`is_cameo`](/slides/python-net/es/aspose.slides/pictureframe/is_cameo/) | Determina si el PictureFrame es un objeto Cameo o no.<br/>            Solo lectura **bool**. |

## Métodos

| Método | Descripción |
| :- | :- |
| [`get_image(self)`](/slides/python-net/es/aspose.slides/pictureframe/get_image/#) | Devuelve la miniatura de la forma.<br/>            Se usa por defecto el tipo de límites de miniatura ShapeThumbnailBounds.Shape. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/es/aspose.slides/pictureframe/get_image/#shapethumbnailbounds-float-float) | Devuelve la miniatura de la forma. |
| [`write_as_svg(self, stream)`](/slides/python-net/es/aspose.slides/pictureframe/write_as_svg/#iorawiobase) | Guarda el contenido de la Forma como archivo SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/es/aspose.slides/pictureframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Guarda el contenido de la Forma como archivo SVG. |
| [`remove_placeholder(self)`](/slides/python-net/es/aspose.slides/pictureframe/remove_placeholder/#) | Define que esta forma no es un marcador de posición. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/es/aspose.slides/pictureframe/add_placeholder/#iplaceholder) | Añade un nuevo marcador de posición si no existe y establece las propiedades del marcador de posición a una especificada. |
| [`get_base_placeholder(self)`](/slides/python-net/es/aspose.slides/pictureframe/get_base_placeholder/#) | Devuelve una forma básica de marcador de posición (forma del diseño y/o diapositiva maestra de la que la forma actual hereda).<br/>            Se devuelve None si la forma actual no hereda. |
| [`get_visual_bounds(self)`](/slides/python-net/es/aspose.slides/pictureframe/get_visual_bounds/#) | Obtiene los límites visuales de la forma calculados a partir de su contenido renderizado. |
| [`get_geometry_paths(self)`](/slides/python-net/es/aspose.slides/pictureframe/get_geometry_paths/#) | Devuelve una copia de la ruta de la forma geométrica. Las coordenadas son relativas a la esquina superior izquierda de la forma. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/es/aspose.slides/pictureframe/set_geometry_path/#igeometrypath) | Actualiza la geometría de la forma a partir del objeto [`IGeometryPath`](/slides/python-net/es/aspose.slides/igeometrypath). Las coordenadas deben ser relativas a la esquina superior izquierda de la forma.<br/>             Cambia el tipo de la forma ([`GeometryShape.shape_type`](/slides/python-net/es/aspose.slides/geometryshape/shape_type)) a [`ShapeType.CUSTOM`](/slides/python-net/es/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/es/aspose.slides/pictureframe/set_geometry_paths/#listigeometrypath) | Actualiza la geometría de la forma a partir de una matriz de [`IGeometryPath`](/slides/python-net/es/aspose.slides/igeometrypath). Las coordenadas deben ser relativas a la esquina superior izquierda de la forma.<br/>             Cambia el tipo de la forma ([`GeometryShape.shape_type`](/slides/python-net/es/aspose.slides/geometryshape/shape_type)) a [`ShapeType.CUSTOM`](/slides/python-net/es/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/es/aspose.slides/pictureframe/create_shape_elements/#) | Crea y devuelve una matriz de los elementos de la forma. |

### Ver también
* clase [`GeometryShape`](/slides/python-net/es/aspose.slides/geometryshape)
* clase [`PictureFrame`](/slides/python-net/es/aspose.slides/pictureframe)
* clase [`Shape`](/slides/python-net/es/aspose.slides/shape)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)