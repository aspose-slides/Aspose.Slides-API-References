---
title: OleObjectFrame class
second_title: Referencia de API de Aspose.Slides para Python mediante .NET
description: 
type: docs
url: /es/aspose.slides/oleobjectframe/
---
## OleObjectFrame clase

Representa un objeto OLE en una diapositiva.

**Herencia:**[`OleObjectFrame`](/slides/python-net/es/aspose.slides/oleobjectframe) → [`GraphicalObject`](/slides/python-net/es/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/es/aspose.slides/shape)

El tipo OleObjectFrame expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`is_text_holder`](/slides/python-net/es/aspose.slides/oleobjectframe/is_text_holder/) | Determina si la forma es TextHolder_PPT.<br/>            Solo lectura **bool**. |
| [`placeholder`](/slides/python-net/es/aspose.slides/oleobjectframe/placeholder/) | Devuelve el marcador de posición para una forma. Devuelve None si la forma no tiene marcador de posición.<br/>            Solo lectura [`IPlaceholder`](/slides/python-net/es/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/es/aspose.slides/oleobjectframe/custom_data/) | Devuelve los datos personalizados de la forma.<br/>            Solo lectura [`ICustomData`](/slides/python-net/es/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/es/aspose.slides/oleobjectframe/raw_frame/) | Devuelve o establece las propiedades del marco sin procesar de la forma.<br/>            Lectura/escritura [`IShapeFrame`](/slides/python-net/es/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/es/aspose.slides/oleobjectframe/frame/) | Devuelve o establece las propiedades del marco de la forma.<br/>            Lectura/escritura [`IShapeFrame`](/slides/python-net/es/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/es/aspose.slides/oleobjectframe/line_format/) | Devuelve el objeto LineFormat que contiene las propiedades de formato de línea para una forma.<br/>            Nota: puede devolver None para ciertos tipos de formas que no tienen propiedades de línea.<br/>            Solo lectura [`ILineFormat`](/slides/python-net/es/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/es/aspose.slides/oleobjectframe/three_d_format/) | Devuelve el objeto ThreeDFormat que contiene las propiedades de efectos 3D para una forma.<br/>            Nota: puede devolver None para ciertos tipos de formas que no tienen propiedades 3D.<br/>            Solo lectura [`IThreeDFormat`](/slides/python-net/es/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/es/aspose.slides/oleobjectframe/effect_format/) | Devuelve el objeto EffectFormat que contiene los efectos de píxel aplicados a una forma.<br/>            Nota: puede devolver None para ciertos tipos de formas que no tienen propiedades de efecto.<br/>            Solo lectura [`IEffectFormat`](/slides/python-net/es/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/es/aspose.slides/oleobjectframe/fill_format/) | Devuelve el objeto FillFormat que contiene las propiedades de formato de relleno para una forma.<br/>            Nota: puede devolver None para ciertos tipos de formas que no tienen propiedades de relleno.<br/>            Solo lectura [`IFillFormat`](/slides/python-net/es/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/es/aspose.slides/oleobjectframe/hyperlink_click/) | Devuelve o establece el hipervínculo definido para clic del ratón.<br/>            Lectura/escritura [`IHyperlink`](/slides/python-net/es/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/es/aspose.slides/oleobjectframe/hyperlink_mouse_over/) | Devuelve o establece el hipervínculo definido para pasar el ratón por encima.<br/>            Lectura/escritura [`IHyperlink`](/slides/python-net/es/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/es/aspose.slides/oleobjectframe/hyperlink_manager/) | Devuelve el gestor de hipervínculos.<br/>            Solo lectura [`IHyperlinkManager`](/slides/python-net/es/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/es/aspose.slides/oleobjectframe/hidden/) | Determina si la forma está oculta.<br/>            Lectura/escritura **bool**. |
| [`z_order_position`](/slides/python-net/es/aspose.slides/oleobjectframe/z_order_position/) | Devuelve la posición de una forma en el orden Z.<br/>            Shapes[0] devuelve la forma al fondo del orden Z,<br/>            y Shapes[Shapes.Count - 1] devuelve la forma al frente del orden Z.<br/>            Solo lectura **int**. |
| [`connection_site_count`](/slides/python-net/es/aspose.slides/oleobjectframe/connection_site_count/) | Devuelve el número de puntos de conexión en la forma.<br/>            Solo lectura **int**. |
| [`rotation`](/slides/python-net/es/aspose.slides/oleobjectframe/rotation/) | Devuelve o establece el número de grados que la forma especificada está rotada alrededor del eje z.<br/>            Un valor positivo indica rotación en sentido horario; un valor negativo<br/>            indica rotación en sentido antihorario.<br/>            Lectura/escritura **float**. |
| [`x`](/slides/python-net/es/aspose.slides/oleobjectframe/x/) | Obtiene o establece la coordenada x de la esquina superior izquierda de la forma, medida en puntos.<br/>            Lectura/escritura **float**. |
| [`y`](/slides/python-net/es/aspose.slides/oleobjectframe/y/) | Obtiene o establece la coordenada y de la esquina superior izquierda de la forma, medida en puntos.<br/>            Lectura/escritura **float**. |
| [`width`](/slides/python-net/es/aspose.slides/oleobjectframe/width/) | Obtiene o establece el ancho de la forma, medido en puntos.<br/>            Lectura/escritura **float**. |
| [`height`](/slides/python-net/es/aspose.slides/oleobjectframe/height/) | Obtiene o establece la altura de la forma, medida en puntos.<br/>            Lectura/escritura **float**. |
| [`black_white_mode`](/slides/python-net/es/aspose.slides/oleobjectframe/black_white_mode/) | La propiedad especifica cómo se renderizará una forma en modo de visualización en blanco y negro..<br/>            Lectura/escritura [`BlackWhiteMode`](/slides/python-net/es/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/es/aspose.slides/oleobjectframe/unique_id/) | Devuelve un identificador interno, con alcance de presentación, destinado al uso por complementos u otro código.<br/>            Debido a que este valor puede ser reasignado por el usuario o programáticamente, no debe ser tratado<br/>            como una clave única persistente.<br/>            Solo lectura **int**.<br/>            Ver también [`Shape.office_interop_shape_id`](/slides/python-net/es/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/es/aspose.slides/oleobjectframe/office_interop_shape_id/) | Devuelve un identificador único con alcance de diapositiva que permanece constante durante la vida útil de la forma y<br/>            permite que PowerPoint o código de interop lo referencie de forma fiable desde cualquier parte del documento.<br/>            Solo lectura **int**.<br/>            Ver también [`Shape.unique_id`](/slides/python-net/es/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/es/aspose.slides/oleobjectframe/alternative_text/) | Devuelve o establece el texto alternativo asociado a una forma.<br/>            Lectura/escritura **str**. |
| [`alternative_text_title`](/slides/python-net/es/aspose.slides/oleobjectframe/alternative_text_title/) | Devuelve o establece el título del texto alternativo asociado a una forma.<br/>            Lectura/escritura **str**. |
| [`name`](/slides/python-net/es/aspose.slides/oleobjectframe/name/) | Devuelve o establece el nombre de una forma.<br/>            No debe ser None. Use una cadena vacía si es necesario.<br/>            Lectura/escritura **str**. |
| [`is_decorative`](/slides/python-net/es/aspose.slides/oleobjectframe/is_decorative/) | Obtiene o establece la opción 'Marcar como decorativo'<br/>            Lectura/escritura **bool**. |
| [`shape_lock`](/slides/python-net/es/aspose.slides/oleobjectframe/shape_lock/) | Devuelve los bloqueos de la forma.<br/>            Solo lectura [`IGraphicalObjectLock`](/slides/python-net/es/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/es/aspose.slides/oleobjectframe/is_grouped/) | Determina si la forma está agrupada.<br/>            Solo lectura **bool**. |
| [`parent_group`](/slides/python-net/es/aspose.slides/oleobjectframe/parent_group/) | Devuelve el objeto GroupShape padre si la forma está agrupada. De lo contrario devuelve None.<br/>            Solo lectura [`IGroupShape`](/slides/python-net/es/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/es/aspose.slides/oleobjectframe/slide/) | Devuelve la diapositiva padre de una forma.<br/>            Solo lectura [`IBaseSlide`](/slides/python-net/es/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/es/aspose.slides/oleobjectframe/presentation/) | Devuelve la presentación padre de una diapositiva.<br/>            Solo lectura [`IPresentation`](/slides/python-net/es/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/es/aspose.slides/oleobjectframe/graphical_object_lock/) | Devuelve los bloqueos de la forma.<br/>            Solo lectura [`IGraphicalObjectLock`](/slides/python-net/es/aspose.slides/igraphicalobjectlock). |
| [`substitute_picture_format`](/slides/python-net/es/aspose.slides/oleobjectframe/substitute_picture_format/) | Devuelve el objeto de propiedades de relleno de imagen OleObject.<br/>            Solo lectura [`IPictureFillFormat`](/slides/python-net/es/aspose.slides/ipicturefillformat). |
| [`substitute_picture_title`](/slides/python-net/es/aspose.slides/oleobjectframe/substitute_picture_title/) | Devuelve o establece el título del ícono OleObject.<br/>            Lectura/escritura **str**. |
| [`object_name`](/slides/python-net/es/aspose.slides/oleobjectframe/object_name/) | Devuelve o establece el nombre de un objeto.<br/>            Lectura/escritura **str**. |
| [`object_prog_id`](/slides/python-net/es/aspose.slides/oleobjectframe/object_prog_id/) | Devuelve el ProgID de un objeto.<br/>            Solo lectura **str**. |
| [`link_file_name`](/slides/python-net/es/aspose.slides/oleobjectframe/link_file_name/) | Devuelve la ruta completa a un archivo vinculado. Se usará el nombre corto del archivo.<br/>            Solo lectura **str**. |
| [`link_path_long`](/slides/python-net/es/aspose.slides/oleobjectframe/link_path_long/) | Devuelve la ruta completa a un archivo vinculado. Se usará el nombre largo del archivo.<br/>            Lectura/escritura **str**. |
| [`link_path_relative`](/slides/python-net/es/aspose.slides/oleobjectframe/link_path_relative/) | Devuelve la ruta relativa a un archivo vinculado si está presente, de lo contrario devuelve una cadena vacía.<br/>             Solo lectura **str**. |
| [`embedded_file_label`](/slides/python-net/es/aspose.slides/oleobjectframe/embedded_file_label/) | Devuelve el nombre de archivo del objeto OLE incrustado |
| [`embedded_file_name`](/slides/python-net/es/aspose.slides/oleobjectframe/embedded_file_name/) | Devuelve la ruta del objeto OLE incrustado |
| [`embedded_data`](/slides/python-net/es/aspose.slides/oleobjectframe/embedded_data/) | Obtiene o establece información sobre los datos OLE incrustados.<br/>            Lectura/escritura [`IOleEmbeddedDataInfo`](/slides/python-net/es/aspose.slides/ioleembeddeddatainfo). |
| [`is_object_icon`](/slides/python-net/es/aspose.slides/oleobjectframe/is_object_icon/) | Determina si un objeto es visible como ícono.<br/>            Lectura/escritura **bool**. |
| [`is_object_link`](/slides/python-net/es/aspose.slides/oleobjectframe/is_object_link/) | Determina si un objeto está vinculado a un archivo externo.<br/>            Solo lectura **bool**. |
| [`update_automatic`](/slides/python-net/es/aspose.slides/oleobjectframe/update_automatic/) | Determina si el objeto incrustado vinculado se actualiza automáticamente cuando la presentación se abre o se imprime.<br/>            Lectura/escritura **bool**. |

## Métodos

| Método | Descripción |
| :- | :- |
| [`get_image(self)`](/slides/python-net/es/aspose.slides/oleobjectframe/get_image/#) | Devuelve la miniatura de la forma.<br/>            Se utiliza por defecto el tipo ShapeThumbnailBounds.Shape para los límites de la miniatura de la forma. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/es/aspose.slides/oleobjectframe/get_image/#shapethumbnailbounds-float-float) | Devuelve la miniatura de la forma. |
| [`write_as_svg(self, stream)`](/slides/python-net/es/aspose.slides/oleobjectframe/write_as_svg/#iorawiobase) | Guarda el contenido de la Forma como archivo SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/es/aspose.slides/oleobjectframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Guarda el contenido de la Forma como archivo SVG. |
| [`remove_placeholder(self)`](/slides/python-net/es/aspose.slides/oleobjectframe/remove_placeholder/#) | Define que esta forma no es un marcador de posición. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/es/aspose.slides/oleobjectframe/add_placeholder/#iplaceholder) | Agrega un nuevo marcador de posición si no existe y establece las propiedades del marcador en una especificada. |
| [`get_base_placeholder(self)`](/slides/python-net/es/aspose.slides/oleobjectframe/get_base_placeholder/#) | Devuelve una forma de marcador de posición básica (forma del diseño y/o diapositiva maestra de la cual la forma actual hereda).<br/>            Se devuelve None si la forma actual no está heredada. |
| [`get_visual_bounds(self)`](/slides/python-net/es/aspose.slides/oleobjectframe/get_visual_bounds/#) | Obtiene los límites visuales de la forma calculados a partir de su contenido renderizado. |
| [`set_embedded_data(self, embedded_data)`](/slides/python-net/es/aspose.slides/oleobjectframe/set_embedded_data/#ioleembeddeddatainfo) | Establece información sobre los datos OLE incrustados.<br/>            <br/>            Este método cambia las propiedades del objeto para reflejar los nuevos datos y <br/>            establece la bandera IsObjectLink a false, indicando que el objeto OLE está incrustado. |

### Ver también
* clase [`GraphicalObject`](/slides/python-net/es/aspose.slides/graphicalobject)
* clase [`OleObjectFrame`](/slides/python-net/es/aspose.slides/oleobjectframe)
* clase [`Shape`](/slides/python-net/es/aspose.slides/shape)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)