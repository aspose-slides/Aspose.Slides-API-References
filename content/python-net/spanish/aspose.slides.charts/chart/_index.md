---
title: Chart class
second_title: Referencia de API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides.charts/chart/
---
## Chart clase

Representa un gráfico en una diapositiva.

**Herencia:**[`Chart`](/slides/python-net/es/aspose.slides.charts/chart) → [`GraphicalObject`](/slides/python-net/es/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/es/aspose.slides/shape)

El tipo Chart expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`is_text_holder`](/slides/python-net/es/aspose.slides.charts/chart/is_text_holder/) | Determina si la forma es TextHolder_PPT.<br/>            Solo lectura **bool**. |
| [`placeholder`](/slides/python-net/es/aspose.slides.charts/chart/placeholder/) | Devuelve el marcador de posición para una forma. Devuelve None si la forma no tiene marcador de posición.<br/>            Solo lectura [`IPlaceholder`](/slides/python-net/es/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/es/aspose.slides.charts/chart/custom_data/) | Devuelve los datos personalizados de la forma.<br/>            Solo lectura [`ICustomData`](/slides/python-net/es/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/es/aspose.slides.charts/chart/raw_frame/) | Devuelve o establece las propiedades del marco bruto de la forma.<br/>            Lectura/escritura [`IShapeFrame`](/slides/python-net/es/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/es/aspose.slides.charts/chart/frame/) | Devuelve o establece las propiedades del marco de la forma.<br/>            Lectura/escritura [`IShapeFrame`](/slides/python-net/es/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/es/aspose.slides.charts/chart/line_format/) | Devuelve el objeto LineFormat que contiene las propiedades de formato de línea para una forma.<br/>            Nota: puede devolver None para ciertos tipos de formas que no tienen propiedades de línea.<br/>            Solo lectura [`ILineFormat`](/slides/python-net/es/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/es/aspose.slides.charts/chart/three_d_format/) | Devuelve el objeto ThreeDFormat que contiene las propiedades de efecto 3d para una forma.<br/>            Nota: puede devolver None para ciertos tipos de formas que no tienen propiedades 3d.<br/>            Solo lectura [`IThreeDFormat`](/slides/python-net/es/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/es/aspose.slides.charts/chart/effect_format/) | Devuelve el objeto EffectFormat que contiene los efectos de píxel aplicados a una forma.<br/>            Nota: puede devolver None para ciertos tipos de formas que no tienen propiedades de efecto.<br/>            Solo lectura [`IEffectFormat`](/slides/python-net/es/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/es/aspose.slides.charts/chart/fill_format/) | Devuelve el objeto FillFormat que contiene las propiedades de formato de relleno para una forma.<br/>            Nota: puede devolver None para ciertos tipos de formas que no tienen propiedades de relleno.<br/>            Solo lectura [`IFillFormat`](/slides/python-net/es/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/es/aspose.slides.charts/chart/hyperlink_click/) | Devuelve o establece el hipervínculo definido para clic del ratón.<br/>            Lectura/escritura [`IHyperlink`](/slides/python-net/es/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/es/aspose.slides.charts/chart/hyperlink_mouse_over/) | Devuelve o establece el hipervínculo definido para pasar el ratón por encima.<br/>            Lectura/escritura [`IHyperlink`](/slides/python-net/es/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/es/aspose.slides.charts/chart/hyperlink_manager/) | Devuelve el gestor de hipervínculos.<br/>            Solo lectura [`IHyperlinkManager`](/slides/python-net/es/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/es/aspose.slides.charts/chart/hidden/) | Determina si la forma está oculta.<br/>            Lectura/escritura **bool**. |
| [`z_order_position`](/slides/python-net/es/aspose.slides.charts/chart/z_order_position/) | Devuelve la posición de una forma en el orden z.<br/>            Shapes[0] devuelve la forma al fondo del orden z,<br/>            y Shapes[Shapes.Count - 1] devuelve la forma al frente del orden z.<br/>            Solo lectura **int**. |
| [`connection_site_count`](/slides/python-net/es/aspose.slides.charts/chart/connection_site_count/) | Devuelve el número de puntos de conexión en la forma.<br/>            Solo lectura **int**. |
| [`rotation`](/slides/python-net/es/aspose.slides.charts/chart/rotation/) | Devuelve o establece el número de grados que la forma especificada está rotada alrededor del eje z.<br/>            Un valor positivo indica rotación en el sentido de las agujas del reloj; un valor negativo<br/>            indica rotación en sentido contrario.<br/>            Lectura/escritura **float**. |
| [`x`](/slides/python-net/es/aspose.slides.charts/chart/x/) | Obtiene o establece la coordenada x de la esquina superior izquierda de la forma, medida en puntos.<br/>            Lectura/escritura **float**. |
| [`y`](/slides/python-net/es/aspose.slides.charts/chart/y/) | Obtiene o establece la coordenada y de la esquina superior izquierda de la forma, medida en puntos.<br/>            Lectura/escritura **float**. |
| [`width`](/slides/python-net/es/aspose.slides.charts/chart/width/) | Obtiene o establece el ancho de la forma, medido en puntos.<br/>            Lectura/escritura **float**. |
| [`height`](/slides/python-net/es/aspose.slides.charts/chart/height/) | Obtiene o establece la altura de la forma, medida en puntos.<br/>            Lectura/escritura **float**. |
| [`black_white_mode`](/slides/python-net/es/aspose.slides.charts/chart/black_white_mode/) | La propiedad especifica cómo se renderizará una forma en modo de visualización en blanco y negro..<br/>            Lectura/escritura [`BlackWhiteMode`](/slides/python-net/es/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/es/aspose.slides.charts/chart/unique_id/) | Devuelve un identificador interno con alcance de presentación destinado al uso por complementos u otro código.<br/>            Dado que este valor puede ser reasignado por el usuario o programáticamente, no debe tratarse<br/>            como una clave única persistente.<br/>            Solo lectura **int**.<br/>            Ver también [`Shape.office_interop_shape_id`](/slides/python-net/es/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/es/aspose.slides.charts/chart/office_interop_shape_id/) | Devuelve un identificador único con alcance de diapositiva que permanece constante durante la vida útil de la forma y<br/>            permite que PowerPoint o el código de interop lo referencie de forma fiable desde cualquier parte del documento.<br/>            Solo lectura **int**.<br/>            Ver también [`Shape.unique_id`](/slides/python-net/es/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/es/aspose.slides.charts/chart/alternative_text/) | Devuelve o establece el texto alternativo asociado a una forma.<br/>            Lectura/escritura **str**. |
| [`alternative_text_title`](/slides/python-net/es/aspose.slides.charts/chart/alternative_text_title/) | Devuelve o establece el título del texto alternativo asociado a una forma.<br/>            Lectura/escritura **str**. |
| [`name`](/slides/python-net/es/aspose.slides.charts/chart/name/) | Devuelve o establece el nombre de una forma.<br/>            No debe ser None. Use una cadena vacía si es necesario.<br/>            Lectura/escritura **str**. |
| [`is_decorative`](/slides/python-net/es/aspose.slides.charts/chart/is_decorative/) | Obtiene o establece la opción 'Marcar como decorativo'<br/>            Lectura/escritura **bool**. |
| [`shape_lock`](/slides/python-net/es/aspose.slides.charts/chart/shape_lock/) | Devuelve los bloqueos de la forma.<br/>            Solo lectura [`IGraphicalObjectLock`](/slides/python-net/es/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/es/aspose.slides.charts/chart/is_grouped/) | Determina si la forma está agrupada.<br/>            Solo lectura **bool**. |
| [`parent_group`](/slides/python-net/es/aspose.slides.charts/chart/parent_group/) | Devuelve el objeto GroupShape padre si la forma está agrupada. De lo contrario devuelve None.<br/>            Solo lectura [`IGroupShape`](/slides/python-net/es/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/es/aspose.slides.charts/chart/slide/) | Devuelve la diapositiva padre de una forma.<br/>            Solo lectura [`IBaseSlide`](/slides/python-net/es/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/es/aspose.slides.charts/chart/presentation/) | Devuelve la presentación padre de una diapositiva.<br/>            Solo lectura [`IPresentation`](/slides/python-net/es/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/es/aspose.slides.charts/chart/graphical_object_lock/) | Devuelve los bloqueos de la forma.<br/>            Solo lectura [`IGraphicalObjectLock`](/slides/python-net/es/aspose.slides/igraphicalobjectlock). |
| [`plot_visible_cells_only`](/slides/python-net/es/aspose.slides.charts/chart/plot_visible_cells_only/) | Determina si solo se trazan las celdas visibles. False para trazar tanto celdas visibles como ocultas.<br/>            Lectura/escritura **bool**. |
| [`display_blanks_as`](/slides/python-net/es/aspose.slides.charts/chart/display_blanks_as/) | Devuelve o establece la forma de trazar celdas en blanco en un gráfico.<br/>            Lectura/escritura [`DisplayBlanksAsType`](/slides/python-net/es/aspose.slides.charts/displayblanksastype). |
| [`chart_data`](/slides/python-net/es/aspose.slides.charts/chart/chart_data/) | Devuelve información sobre los datos vinculados o incrustados asociados a un gráfico.<br/>            Solo lectura [`IChartData`](/slides/python-net/es/aspose.slides.charts/ichartdata). |
| [`has_title`](/slides/python-net/es/aspose.slides.charts/chart/has_title/) | Determina si un gráfico tiene título visible.<br/>            Lectura/escritura **bool**. |
| [`chart_title`](/slides/python-net/es/aspose.slides.charts/chart/chart_title/) | Devuelve o establece un título de gráfico.<br/>            Solo lectura [`IChartTitle`](/slides/python-net/es/aspose.slides.charts/icharttitle). |
| [`has_data_table`](/slides/python-net/es/aspose.slides.charts/chart/has_data_table/) | Determina si un gráfico tiene tabla de datos.<br/>            Lectura/escritura **bool**. |
| [`has_legend`](/slides/python-net/es/aspose.slides.charts/chart/has_legend/) | Determina si un gráfico tiene leyenda.<br/>            Lectura/escritura **bool**. |
| [`legend`](/slides/python-net/es/aspose.slides.charts/chart/legend/) | Devuelve o establece una leyenda para un gráfico.<br/>            Solo lectura [`ILegend`](/slides/python-net/es/aspose.slides.charts/ilegend). |
| [`chart_data_table`](/slides/python-net/es/aspose.slides.charts/chart/chart_data_table/) | Devuelve una tabla de datos de un gráfico.<br/>            Solo lectura [`IDataTable`](/slides/python-net/es/aspose.slides.charts/idatatable). |
| [`style`](/slides/python-net/es/aspose.slides.charts/chart/style/) | Devuelve o establece el estilo del gráfico.<br/>            Lectura/escritura [`StyleType`](/slides/python-net/es/aspose.slides.charts/styletype). |
| [`type`](/slides/python-net/es/aspose.slides.charts/chart/type/) | Devuelve o establece el tipo de gráfico.<br/>            Lectura/escritura [`ChartType`](/slides/python-net/es/aspose.slides.charts/charttype). |
| [`plot_area`](/slides/python-net/es/aspose.slides.charts/chart/plot_area/) | Representa el área de trazado de un gráfico.<br/>            Solo lectura [`IChartPlotArea`](/slides/python-net/es/aspose.slides.charts/ichartplotarea). |
| [`rotation_3d`](/slides/python-net/es/aspose.slides.charts/chart/rotation_3d/) | Devuelve una rotación 3D de un gráfico.<br/>            Solo lectura [`IRotation3D`](/slides/python-net/es/aspose.slides.charts/irotation3d). |
| [`back_wall`](/slides/python-net/es/aspose.slides.charts/chart/back_wall/) | Devuelve un objeto que permite cambiar el formato de la pared trasera de un gráfico 3D.<br/>            Solo lectura [`IChartWall`](/slides/python-net/es/aspose.slides.charts/ichartwall). |
| [`side_wall`](/slides/python-net/es/aspose.slides.charts/chart/side_wall/) | Devuelve un objeto que permite cambiar el formato de la pared lateral de un gráfico 3D.<br/>            Solo lectura [`IChartWall`](/slides/python-net/es/aspose.slides.charts/ichartwall). |
| [`floor`](/slides/python-net/es/aspose.slides.charts/chart/floor/) | Devuelve un objeto que permite cambiar el formato del suelo de un gráfico 3D.<br/>            Solo lectura [`IChartWall`](/slides/python-net/es/aspose.slides.charts/ichartwall). |
| [`text_format`](/slides/python-net/es/aspose.slides.charts/chart/text_format/) | Devuelve el formato de texto del gráfico.<br/>            La propiedad no es aplicable a los siguientes tipos: [`ChartType.TREEMAP`](/slides/python-net/es/aspose.slides.charts/charttype/TREEMAP), [`ChartType.SUNBURST`](/slides/python-net/es/aspose.slides.charts/charttype/SUNBURST),<br/>            [`ChartType.WATERFALL`](/slides/python-net/es/aspose.slides.charts/charttype/WATERFALL), [`ChartType.HISTOGRAM`](/slides/python-net/es/aspose.slides.charts/charttype/HISTOGRAM), [`ChartType.FUNNEL`](/slides/python-net/es/aspose.slides.charts/charttype/FUNNEL),[`ChartType.BOX_AND_WHISKER`](/slides/python-net/es/aspose.slides.charts/charttype/BOX_AND_WHISKER).<br/>            Solo lectura [`IChartTextFormat`](/slides/python-net/es/aspose.slides.charts/icharttextformat). |
| [`theme_manager`](/slides/python-net/es/aspose.slides.charts/chart/theme_manager/) | Devuelve el gestor de temas.<br/>            Solo lectura [`IOverrideThemeManager`](/slides/python-net/es/aspose.slides.theme/ioverridethememanager). |
| [`user_shapes`](/slides/python-net/es/aspose.slides.charts/chart/user_shapes/) | Especifica las formas dibujadas encima del gráfico.<br/>            Solo lectura [`IGroupShape`](/slides/python-net/es/aspose.slides/igroupshape). |
| [`axes`](/slides/python-net/es/aspose.slides.charts/chart/axes/) | Proporciona acceso a los ejes del gráfico.<br/>            Solo lectura [`IAxesManager`](/slides/python-net/es/aspose.slides.charts/iaxesmanager). |
| [`show_data_labels_over_maximum`](/slides/python-net/es/aspose.slides.charts/chart/show_data_labels_over_maximum/) | Especifica que se muestren etiquetas de datos por encima del máximo del gráfico.<br/>            Lectura/escritura **bool**. |
| [`has_rounded_corners`](/slides/python-net/es/aspose.slides.charts/chart/has_rounded_corners/) | Especifica que el área del gráfico tenga esquinas redondeadas.<br/>            Lectura/escritura **bool**. |
| [`chart`](/slides/python-net/es/aspose.slides.charts/chart/chart/) |  |

## Métodos

| Método | Descripción |
| :- | :- |
| [`get_image(self)`](/slides/python-net/es/aspose.slides.charts/chart/get_image/#) | Devuelve la miniatura de la forma.<br/>            Se utiliza por defecto el tipo ShapeThumbnailBounds.Shape para los límites de la miniatura de la forma. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/es/aspose.slides.charts/chart/get_image/#shapethumbnailbounds-float-float) | Devuelve la miniatura de la forma. |
| [`write_as_svg(self, stream)`](/slides/python-net/es/aspose.slides.charts/chart/write_as_svg/#iorawiobase) | Guarda el contenido de Shape como archivo SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/es/aspose.slides.charts/chart/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Guarda el contenido de Shape como archivo SVG. |
| [`remove_placeholder(self)`](/slides/python-net/es/aspose.slides.charts/chart/remove_placeholder/#) | Define que esta forma no es un marcador de posición. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/es/aspose.slides.charts/chart/add_placeholder/#iplaceholder) | Añade un nuevo marcador de posición si no existe y establece sus propiedades a las especificadas. |
| [`get_base_placeholder(self)`](/slides/python-net/es/aspose.slides.charts/chart/get_base_placeholder/#) | Devuelve una forma de marcador de posición básica (forma del diseño y/o diapositiva maestra de la que la forma actual hereda).<br/>            Se devuelve None si la forma actual no hereda. |
| [`get_visual_bounds(self)`](/slides/python-net/es/aspose.slides.charts/chart/get_visual_bounds/#) | Obtiene los límites visuales de la forma calculados a partir de su contenido renderizado. |
| [`validate_chart_layout(self)`](/slides/python-net/es/aspose.slides.charts/chart/validate_chart_layout/#) | Calcula los valores reales de los elementos del gráfico. Los valores reales incluyen la posición de los elementos que implementan la interfaz IActualLayout <br/>            (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight)<br/>            y los valores reales de los ejes (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, <br/>            IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale). |
| [`create_theme_effective(self)`](/slides/python-net/es/aspose.slides.charts/chart/create_theme_effective/#) | Devuelve un tema efectivo para este gráfico. |

### Ver también
* clase [`Chart`](/slides/python-net/es/aspose.slides.charts/chart)
* clase [`GraphicalObject`](/slides/python-net/es/aspose.slides/graphicalobject)
* clase [`Shape`](/slides/python-net/es/aspose.slides/shape)
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)