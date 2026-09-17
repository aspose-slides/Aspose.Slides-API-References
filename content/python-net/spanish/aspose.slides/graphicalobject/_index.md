---
title: GraphicalObject class
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/graphicalobject/
---
## GraphicalObject clase

Representa un objeto gráfico abstracto.

**Herencia:**[`GraphicalObject`](/slides/python-net/es/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/es/aspose.slides/shape)

El tipo GraphicalObject expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`is_text_holder`](/slides/python-net/es/aspose.slides/graphicalobject/is_text_holder/) | Determina si la forma es TextHolder_PPT.<br/>            Solo lectura **bool**. |
| [`placeholder`](/slides/python-net/es/aspose.slides/graphicalobject/placeholder/) | Devuelve el marcador de posición de una forma. Devuelve None si la forma no tiene marcador de posición.<br/>            Solo lectura [`IPlaceholder`](/slides/python-net/es/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/es/aspose.slides/graphicalobject/custom_data/) | Devuelve los datos personalizados de la forma.<br/>            Solo lectura [`ICustomData`](/slides/python-net/es/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/es/aspose.slides/graphicalobject/raw_frame/) | Devuelve o establece las propiedades del marco bruto de la forma.<br/>            Lectura/escritura [`IShapeFrame`](/slides/python-net/es/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/es/aspose.slides/graphicalobject/frame/) | Devuelve o establece las propiedades del marco de la forma.<br/>            Lectura/escritura [`IShapeFrame`](/slides/python-net/es/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/es/aspose.slides/graphicalobject/line_format/) | Devuelve el objeto LineFormat que contiene propiedades de formato de línea para una forma.<br/>            Nota: puede devolver None para ciertos tipos de formas que no tienen propiedades de línea.<br/>            Solo lectura [`ILineFormat`](/slides/python-net/es/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/es/aspose.slides/graphicalobject/three_d_format/) | Devuelve el objeto ThreeDFormat que contiene propiedades de efecto 3d para una forma.<br/>            Nota: puede devolver None para ciertos tipos de formas que no tienen propiedades 3d.<br/>            Solo lectura [`IThreeDFormat`](/slides/python-net/es/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/es/aspose.slides/graphicalobject/effect_format/) | Devuelve el objeto EffectFormat que contiene efectos de píxel aplicados a una forma.<br/>            Nota: puede devolver None para ciertos tipos de formas que no tienen propiedades de efecto.<br/>            Solo lectura [`IEffectFormat`](/slides/python-net/es/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/es/aspose.slides/graphicalobject/fill_format/) | Devuelve el objeto FillFormat que contiene propiedades de formato de relleno para una forma.<br/>            Nota: puede devolver None para ciertos tipos de formas que no tienen propiedades de relleno.<br/>            Solo lectura [`IFillFormat`](/slides/python-net/es/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/es/aspose.slides/graphicalobject/hyperlink_click/) | Devuelve o establece el hipervínculo definido para clic del ratón.<br/>            Lectura/escritura [`IHyperlink`](/slides/python-net/es/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/es/aspose.slides/graphicalobject/hyperlink_mouse_over/) | Devuelve o establece el hipervínculo definido para pasar el ratón por encima.<br/>            Lectura/escritura [`IHyperlink`](/slides/python-net/es/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/es/aspose.slides/graphicalobject/hyperlink_manager/) | Devuelve el administrador de hipervínculos.<br/>            Solo lectura [`IHyperlinkManager`](/slides/python-net/es/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/es/aspose.slides/graphicalobject/hidden/) | Determina si la forma está oculta.<br/>            Lectura/escritura **bool**. |
| [`z_order_position`](/slides/python-net/es/aspose.slides/graphicalobject/z_order_position/) | Devuelve la posición de una forma en el orden z.<br/>            Shapes[0] devuelve la forma en la parte trasera del orden z,<br/>            y Shapes[Shapes.Count - 1] devuelve la forma en la parte delantera del orden z.<br/>            Solo lectura **int**. |
| [`connection_site_count`](/slides/python-net/es/aspose.slides/graphicalobject/connection_site_count/) | Devuelve el número de puntos de conexión en la forma.<br/>            Solo lectura **int**. |
| [`rotation`](/slides/python-net/es/aspose.slides/graphicalobject/rotation/) | Devuelve o establece el número de grados que la forma especificada está girada alrededor del eje z.<br/>            Un valor positivo indica rotación en sentido horario; un valor negativo indica rotación en sentido antihorario.<br/>            Lectura/escritura **float**. |
| [`x`](/slides/python-net/es/aspose.slides/graphicalobject/x/) | Obtiene o establece la coordenada x de la esquina superior izquierda de la forma, medida en puntos.<br/>            Lectura/escritura **float**. |
| [`y`](/slides/python-net/es/aspose.slides/graphicalobject/y/) | Obtiene o establece la coordenada y de la esquina superior izquierda de la forma, medida en puntos.<br/>            Lectura/escritura **float**. |
| [`width`](/slides/python-net/es/aspose.slides/graphicalobject/width/) | Obtiene o establece el ancho de la forma, medido en puntos.<br/>            Lectura/escritura **float**. |
| [`height`](/slides/python-net/es/aspose.slides/graphicalobject/height/) | Obtiene o establece la altura de la forma, medida en puntos.<br/>            Lectura/escritura **float**. |
| [`black_white_mode`](/slides/python-net/es/aspose.slides/graphicalobject/black_white_mode/) | La propiedad especifica cómo se representará una forma en modo de pantalla en blanco y negro.<br/>            Lectura/escritura [`BlackWhiteMode`](/slides/python-net/es/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/es/aspose.slides/graphicalobject/unique_id/) | Devuelve un identificador interno, con alcance a la presentación, destinado al uso por complementos u otro código.<br/>            Dado que este valor puede ser reasignado por el usuario o programáticamente, no debe ser tratado<br/>            como una clave única persistente.<br/>            Solo lectura **int**.<br/>            Ver también [`Shape.office_interop_shape_id`](/slides/python-net/es/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/es/aspose.slides/graphicalobject/office_interop_shape_id/) | Devuelve un identificador único con alcance a la diapositiva que permanece constante durante la vida útil de la forma y<br/>            permite que PowerPoint o el código de interop lo haga referencia de manera fiable desde cualquier parte del documento.<br/>            Solo lectura **int**.<br/>            Ver también [`Shape.unique_id`](/slides/python-net/es/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/es/aspose.slides/graphicalobject/alternative_text/) | Devuelve o establece el texto alternativo asociado a una forma.<br/>            Lectura/escritura **str**. |
| [`alternative_text_title`](/slides/python-net/es/aspose.slides/graphicalobject/alternative_text_title/) | Devuelve o establece el título del texto alternativo asociado a una forma.<br/>            Lectura/escritura **str**. |
| [`name`](/slides/python-net/es/aspose.slides/graphicalobject/name/) | Devuelve o establece el nombre de una forma.<br/>            No debe ser None. Use un valor de cadena vacía si es necesario.<br/>            Lectura/escritura **str**. |
| [`is_decorative`](/slides/python-net/es/aspose.slides/graphicalobject/is_decorative/) | Obtiene o establece la opción 'Marcar como decorativo'<br/>            Lectura/escritura **bool**. |
| [`shape_lock`](/slides/python-net/es/aspose.slides/graphicalobject/shape_lock/) | Devuelve los bloqueos de la forma.<br/>            Solo lectura [`IGraphicalObjectLock`](/slides/python-net/es/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/es/aspose.slides/graphicalobject/is_grouped/) | Determina si la forma está agrupada.<br/>            Solo lectura **bool**. |
| [`parent_group`](/slides/python-net/es/aspose.slides/graphicalobject/parent_group/) | Devuelve el objeto GroupShape padre si la forma está agrupada. De lo contrario devuelve None.<br/>            Solo lectura [`IGroupShape`](/slides/python-net/es/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/es/aspose.slides/graphicalobject/slide/) | Devuelve la diapositiva padre de una forma.<br/>            Solo lectura [`IBaseSlide`](/slides/python-net/es/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/es/aspose.slides/graphicalobject/presentation/) | Devuelve la presentación padre de una diapositiva.<br/>            Solo lectura [`IPresentation`](/slides/python-net/es/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/es/aspose.slides/graphicalobject/graphical_object_lock/) | Devuelve los bloqueos de la forma.<br/>            Solo lectura [`IGraphicalObjectLock`](/slides/python-net/es/aspose.slides/igraphicalobjectlock). |

## Métodos

| Método | Descripción |
| :- | :- |
| [`get_image(self)`](/slides/python-net/es/aspose.slides/graphicalobject/get_image/#) | Devuelve la miniatura de la forma.<br/>            Se usa por defecto el tipo ShapeThumbnailBounds.Shape para los límites de la miniatura de la forma. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/es/aspose.slides/graphicalobject/get_image/#shapethumbnailbounds-float-float) | Devuelve la miniatura de la forma. |
| [`write_as_svg(self, stream)`](/slides/python-net/es/aspose.slides/graphicalobject/write_as_svg/#iorawiobase) | Guarda el contenido de Shape como archivo SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/es/aspose.slides/graphicalobject/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Guarda el contenido de Shape como archivo SVG. |
| [`remove_placeholder(self)`](/slides/python-net/es/aspose.slides/graphicalobject/remove_placeholder/#) | Define que esta forma no es un marcador de posición. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/es/aspose.slides/graphicalobject/add_placeholder/#iplaceholder) | Agrega un nuevo marcador de posición si no hay ninguno y establece las propiedades del marcador en uno especificado. |
| [`get_base_placeholder(self)`](/slides/python-net/es/aspose.slides/graphicalobject/get_base_placeholder/#) | Devuelve una forma de marcador de posición básica (forma del diseño y/o diapositiva maestra de la que hereda la forma actual).<br/>            Se devuelve None si la forma actual no hereda. |
| [`get_visual_bounds(self)`](/slides/python-net/es/aspose.slides/graphicalobject/get_visual_bounds/#) | Obtiene los límites visuales de la forma calculados a partir de su contenido renderizado. |

### Ver también
* clase [`GraphicalObject`](/slides/python-net/es/aspose.slides/graphicalobject)
* clase [`Shape`](/slides/python-net/es/aspose.slides/shape)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)