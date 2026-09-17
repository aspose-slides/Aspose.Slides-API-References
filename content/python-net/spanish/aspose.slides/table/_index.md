---
title: Table class
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/table/
---
## Clase Table

Representa una tabla en una diapositiva.

**Herencia:**[`Table`](/slides/python-net/es/aspose.slides/table) → [`GraphicalObject`](/slides/python-net/es/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/es/aspose.slides/shape)

El tipo Table expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`is_text_holder`](/slides/python-net/es/aspose.slides/table/is_text_holder/) | Determina si la forma es TextHolder_PPT.<br/>            Solo lectura **bool**. |
| [`placeholder`](/slides/python-net/es/aspose.slides/table/placeholder/) | Devuelve el marcador de posición de una forma. Devuelve None si la forma no tiene marcador de posición.<br/>            Solo lectura [`IPlaceholder`](/slides/python-net/es/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/es/aspose.slides/table/custom_data/) | Devuelve los datos personalizados de la forma.<br/>            Solo lectura [`ICustomData`](/slides/python-net/es/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/es/aspose.slides/table/raw_frame/) | Devuelve o establece las propiedades del marco bruto de la forma.<br/>            Lectura/escritura [`IShapeFrame`](/slides/python-net/es/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/es/aspose.slides/table/frame/) | Devuelve o establece las propiedades del marco de la forma.<br/>            Lectura/escritura [`IShapeFrame`](/slides/python-net/es/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/es/aspose.slides/table/line_format/) | Devuelve el objeto LineFormat que contiene las propiedades de formato de línea para una forma.<br/>            Nota: puede devolver None para ciertos tipos de formas que no tienen propiedades de línea.<br/>            Solo lectura [`ILineFormat`](/slides/python-net/es/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/es/aspose.slides/table/three_d_format/) | Devuelve el objeto ThreeDFormat que contiene las propiedades de efecto 3D para una forma.<br/>            Nota: puede devolver None para ciertos tipos de formas que no tienen propiedades 3D.<br/>            Solo lectura [`IThreeDFormat`](/slides/python-net/es/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/es/aspose.slides/table/effect_format/) | Devuelve el objeto EffectFormat que contiene los efectos de píxel aplicados a una forma.<br/>            Nota: puede devolver None para ciertos tipos de formas que no tienen propiedades de efecto.<br/>            Solo lectura [`IEffectFormat`](/slides/python-net/es/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/es/aspose.slides/table/fill_format/) | Devuelve un objeto TableFormat.FillFormat que contiene el formato de relleno para la Table.<br/>            Solo lectura [`IFillFormat`](/slides/python-net/es/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/es/aspose.slides/table/hyperlink_click/) | Devuelve o establece el hipervínculo definido para clic del ratón.<br/>            Lectura/escritura [`IHyperlink`](/slides/python-net/es/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/es/aspose.slides/table/hyperlink_mouse_over/) | Devuelve o establece el hipervínculo definido para pasar el ratón.<br/>            Lectura/escritura [`IHyperlink`](/slides/python-net/es/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/es/aspose.slides/table/hyperlink_manager/) | Devuelve el administrador de hipervínculos.<br/>            Solo lectura [`IHyperlinkManager`](/slides/python-net/es/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/es/aspose.slides/table/hidden/) | Determina si la forma está oculta.<br/>            Lectura/escritura **bool**. |
| [`z_order_position`](/slides/python-net/es/aspose.slides/table/z_order_position/) | Devuelve la posición de una forma en el orden z.<br/>            Shapes[0] devuelve la forma al fondo del orden z,<br/>            y Shapes[Shapes.Count - 1] devuelve la forma al frente del orden z.<br/>            Solo lectura **int**. |
| [`connection_site_count`](/slides/python-net/es/aspose.slides/table/connection_site_count/) | Devuelve el número de puntos de conexión en la forma.<br/>            Solo lectura **int**. |
| [`rotation`](/slides/python-net/es/aspose.slides/table/rotation/) | Devuelve o establece el número de grados que la forma especificada está rotada alrededor<br/>            del eje z. Un valor positivo indica rotación en sentido horario; un valor negativo<br/>            indica rotación en sentido antihorario.<br/>            Lectura/escritura **float**. |
| [`x`](/slides/python-net/es/aspose.slides/table/x/) | Obtiene o establece la coordenada x de la esquina superior izquierda de la forma, medida en puntos.<br/>            Lectura/escritura **float**. |
| [`y`](/slides/python-net/es/aspose.slides/table/y/) | Obtiene o establece la coordenada y de la esquina superior izquierda de la forma, medida en puntos.<br/>            Lectura/escritura **float**. |
| [`width`](/slides/python-net/es/aspose.slides/table/width/) | Obtiene o establece el ancho de la forma, medido en puntos.<br/>            Lectura/escritura **float**. |
| [`height`](/slides/python-net/es/aspose.slides/table/height/) | Obtiene o establece la altura de la forma, medida en puntos.<br/>            Lectura/escritura **float**. |
| [`black_white_mode`](/slides/python-net/es/aspose.slides/table/black_white_mode/) | Propiedad que especifica cómo se renderizará una forma en modo de visualización en blanco y negro.<br/>            Lectura/escritura [`BlackWhiteMode`](/slides/python-net/es/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/es/aspose.slides/table/unique_id/) | Devuelve un identificador interno, de alcance de la presentación, destinado para uso por complementos u otro código.<br/>            Debido a que este valor puede ser reasignado por el usuario o programáticamente, no debe ser tratado<br/>            como una clave única persistente.<br/>            Solo lectura **int**.<br/>            Ver también [`Shape.office_interop_shape_id`](/slides/python-net/es/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/es/aspose.slides/table/office_interop_shape_id/) | Devuelve un identificador único de alcance de diapositiva que permanece constante durante la vida útil de la forma y<br/>            permite que PowerPoint o código de interop referencia la forma de manera fiable desde cualquier parte del documento.<br/>            Solo lectura **int**.<br/>            Ver también [`Shape.unique_id`](/slides/python-net/es/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/es/aspose.slides/table/alternative_text/) | Devuelve o establece el texto alternativo asociado a una forma.<br/>            Lectura/escritura **str**. |
| [`alternative_text_title`](/slides/python-net/es/aspose.slides/table/alternative_text_title/) | Devuelve o establece el título del texto alternativo asociado a una forma.<br/>            Lectura/escritura **str**. |
| [`name`](/slides/python-net/es/aspose.slides/table/name/) | Devuelve o establece el nombre de una forma.<br/>            No debe ser None. Use una cadena vacía si es necesario.<br/>            Lectura/escritura **str**. |
| [`is_decorative`](/slides/python-net/es/aspose.slides/table/is_decorative/) | Obtiene o establece la opción 'Marcar como decorativo'<br/>            Lectura/escritura **bool**. |
| [`shape_lock`](/slides/python-net/es/aspose.slides/table/shape_lock/) | Devuelve los bloqueos de la forma.<br/>            Solo lectura [`IGraphicalObjectLock`](/slides/python-net/es/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/es/aspose.slides/table/is_grouped/) | Determina si la forma está agrupada.<br/>            Solo lectura **bool**. |
| [`parent_group`](/slides/python-net/es/aspose.slides/table/parent_group/) | Devuelve el objeto GroupShape padre si la forma está agrupada. De lo contrario devuelve None.<br/>            Solo lectura [`IGroupShape`](/slides/python-net/es/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/es/aspose.slides/table/slide/) | Devuelve la diapositiva padre de una forma.<br/>            Solo lectura [`IBaseSlide`](/slides/python-net/es/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/es/aspose.slides/table/presentation/) | Devuelve la presentación padre de una diapositiva.<br/>            Solo lectura [`IPresentation`](/slides/python-net/es/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/es/aspose.slides/table/graphical_object_lock/) | Devuelve los bloqueos de la forma.<br/>            Solo lectura [`IGraphicalObjectLock`](/slides/python-net/es/aspose.slides/igraphicalobjectlock). |
| [`rows`](/slides/python-net/es/aspose.slides/table/rows/) | Devuelve la colección de filas.<br/>            Solo lectura [`IRowCollection`](/slides/python-net/es/aspose.slides/irowcollection). |
| [`columns`](/slides/python-net/es/aspose.slides/table/columns/) | Devuelve la colección de columnas.<br/>            Solo lectura [`IColumnCollection`](/slides/python-net/es/aspose.slides/icolumncollection). |
| [`table_format`](/slides/python-net/es/aspose.slides/table/table_format/) | Devuelve el objeto TableFormat que contiene las propiedades de formato para esta tabla.<br/>            Solo lectura [`ITableFormat`](/slides/python-net/es/aspose.slides/itableformat). |
| [`style_preset`](/slides/python-net/es/aspose.slides/table/style_preset/) | Obtiene o establece el estilo de tabla incorporado.<br/>            Lectura/escritura [`TableStylePreset`](/slides/python-net/es/aspose.slides/tablestylepreset). |
| [`right_to_left`](/slides/python-net/es/aspose.slides/table/right_to_left/) | Determina si la tabla tiene orden de lectura de derecha a izquierda.<br/>            Lectura-escritura **bool**. |
| [`first_row`](/slides/python-net/es/aspose.slides/table/first_row/) | Determina si la primera fila de una tabla debe dibujarse con un formato especial.<br/>            Lectura/escritura **bool**. |
| [`first_col`](/slides/python-net/es/aspose.slides/table/first_col/) | Determina si la primera columna de una tabla debe dibujarse con un formato especial.<br/>            Lectura/escritura **bool**. |
| [`last_row`](/slides/python-net/es/aspose.slides/table/last_row/) | Determina si la última fila de una tabla debe dibujarse con un formato especial.<br/>            Lectura/escritura **bool**. |
| [`last_col`](/slides/python-net/es/aspose.slides/table/last_col/) | Determina si la última columna de una tabla debe dibujarse con un formato especial.<br/>            Lectura/escritura **bool**. |
| [`horizontal_banding`](/slides/python-net/es/aspose.slides/table/horizontal_banding/) | Determina si las filas pares deben dibujarse con un formato diferente.<br/>            Lectura/escritura **bool**. |
| [`vertical_banding`](/slides/python-net/es/aspose.slides/table/vertical_banding/) | Determina si las columnas pares deben dibujarse con un formato diferente.<br/>            Lectura/escritura **bool**. |

## Métodos

| Método | Descripción |
| :- | :- |
| [`get_image(self)`](/slides/python-net/es/aspose.slides/table/get_image/#) | Devuelve la miniatura de la forma.<br/>            Se usa por defecto el tipo ShapeThumbnailBounds.Shape para los límites de la miniatura de la forma. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/es/aspose.slides/table/get_image/#shapethumbnailbounds-float-float) | Devuelve la miniatura de la forma. |
| [`write_as_svg(self, stream)`](/slides/python-net/es/aspose.slides/table/write_as_svg/#iorawiobase) | Guarda el contenido de la Shape como archivo SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/es/aspose.slides/table/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Guarda el contenido de la Shape como archivo SVG. |
| [`set_text_format(self, source)`](/slides/python-net/es/aspose.slides/table/set_text_format/#iportionformat) | Establece las propiedades de formato de porción definidas a todas las porciones de celdas de la tabla. |
| [`set_text_format(self, source)`](/slides/python-net/es/aspose.slides/table/set_text_format/#iparagraphformat) | Establece las propiedades de formato de párrafo definidas a todos los párrafos de celdas de la tabla. |
| [`set_text_format(self, source)`](/slides/python-net/es/aspose.slides/table/set_text_format/#itextframeformat) | Establece las propiedades de formato de marco de texto definidas a todos los marcos de texto de celdas de la tabla. |
| [`remove_placeholder(self)`](/slides/python-net/es/aspose.slides/table/remove_placeholder/#) | Define que esta forma no es un marcador de posición. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/es/aspose.slides/table/add_placeholder/#iplaceholder) | Añade un nuevo marcador de posición si no existe y establece sus propiedades a uno especificado. |
| [`get_base_placeholder(self)`](/slides/python-net/es/aspose.slides/table/get_base_placeholder/#) | Devuelve una forma de marcador de posición básica (forma del diseño y/o diapositiva maestra de la que la forma actual hereda).<br/>            Se devuelve None si la forma actual no hereda. |
| [`get_visual_bounds(self)`](/slides/python-net/es/aspose.slides/table/get_visual_bounds/#) | Obtiene los límites visuales de la forma calculados a partir de su contenido renderizado. |
| [`merge_cells(self, cell1, cell2, allow_splitting)`](/slides/python-net/es/aspose.slides/table/merge_cells/#icell-icell-bool) | Fusiona celdas vecinas. |

### Ver también
* clase [`GraphicalObject`](/slides/python-net/es/aspose.slides/graphicalobject)
* clase [`Shape`](/slides/python-net/es/aspose.slides/shape)
* clase [`Table`](/slides/python-net/es/aspose.slides/table)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)