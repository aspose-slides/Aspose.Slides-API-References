---
title: Chart class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.charts/chart/
---
## Chart klasse

Represents an graphic chart on a slide.

**Inheritance:**[`Chart`](/slides/python-net/nl/aspose.slides.charts/chart) → [`GraphicalObject`](/slides/python-net/nl/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/nl/aspose.slides/shape)

The Chart type exposes the following members:

## Eigenschappen

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/nl/aspose.slides.charts/chart/is_text_holder/) | Determines whether the shape is TextHolder_PPT.<br/>            Alleen-lezen **bool**. |
| [`placeholder`](/slides/python-net/nl/aspose.slides.charts/chart/placeholder/) | Returns the placeholder for a shape. Returns None if the shape has no placeholder.<br/>            Alleen-lezen [`IPlaceholder`](/slides/python-net/nl/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/nl/aspose.slides.charts/chart/custom_data/) | Returns the shape's custom data.<br/>            Alleen-lezen [`ICustomData`](/slides/python-net/nl/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/nl/aspose.slides.charts/chart/raw_frame/) | Returns or sets the raw shape frame's properties.<br/>            Lezen/Schrijven [`IShapeFrame`](/slides/python-net/nl/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/nl/aspose.slides.charts/chart/frame/) | Returns or sets the shape frame's properties.<br/>            Lezen/Schrijven [`IShapeFrame`](/slides/python-net/nl/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/nl/aspose.slides.charts/chart/line_format/) | Returns the LineFormat object that contains line formatting properties for a shape.<br/>            Note: can return None for certain types of shapes which don't have line properties.<br/>            Alleen-lezen [`ILineFormat`](/slides/python-net/nl/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/nl/aspose.slides.charts/chart/three_d_format/) | Returns the ThreeDFormat object that 3d effect properties for a shape.<br/>            Note: can return None for certain types of shapes which don't have 3d properties.<br/>            Alleen-lezen [`IThreeDFormat`](/slides/python-net/nl/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/nl/aspose.slides.charts/chart/effect_format/) | Returns the EffectFormat object which contains pixel effects applied to a shape.<br/>            Note: can return None for certain types of shapes which don't have effect properties.<br/>            Alleen-lezen [`IEffectFormat`](/slides/python-net/nl/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/nl/aspose.slides.charts/chart/fill_format/) | Returns the FillFormat object that contains fill formatting properties for a shape.<br/>            Note: can return None for certain types of shapes which don't have fill properties.<br/>            Alleen-lezen [`IFillFormat`](/slides/python-net/nl/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/nl/aspose.slides.charts/chart/hyperlink_click/) | Returns or sets the hyperlink defined for mouse click.<br/>            Lezen/Schrijven [`IHyperlink`](/slides/python-net/nl/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/nl/aspose.slides.charts/chart/hyperlink_mouse_over/) | Returns or sets the hyperlink defined for mouse over.<br/>            Lezen/Schrijven [`IHyperlink`](/slides/python-net/nl/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/nl/aspose.slides.charts/chart/hyperlink_manager/) | Returns the hyperlink manager.<br/>            Alleen-lezen [`IHyperlinkManager`](/slides/python-net/nl/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/nl/aspose.slides.charts/chart/hidden/) | Determines whether the shape is hidden.<br/>            Lezen/Schrijven **bool**. |
| [`z_order_position`](/slides/python-net/nl/aspose.slides.charts/chart/z_order_position/) | Returns the position of a shape in the z-order.<br/>            Shapes[0] returns the shape at the back of the z-order,<br/>            and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order.<br/>            Alleen-lezen **int**. |
| [`connection_site_count`](/slides/python-net/nl/aspose.slides.charts/chart/connection_site_count/) | Returns the number of connection sites on the shape.<br/>            Alleen-lezen **int**. |
| [`rotation`](/slides/python-net/nl/aspose.slides.charts/chart/rotation/) | Returns or sets the number of degrees the specified shape is rotated around<br/>            the z-axis. A positive value indicates clockwise rotation; a negative value<br/>            indicates counterclockwise rotation.<br/>            Lezen/Schrijven **float**. |
| [`x`](/slides/python-net/nl/aspose.slides.charts/chart/x/) | Returns or sets the x-coordinate of the shape's upper-left corner, measured in points.<br/>            Lezen/Schrijven **float**. |
| [`y`](/slides/python-net/nl/aspose.slides.charts/chart/y/) | Returns or sets the y-coordinate of the shape's upper-left corner, measured in points.<br/>            Lezen/Schrijven **float**. |
| [`width`](/slides/python-net/nl/aspose.slides.charts/chart/width/) | Returns or sets the width of the shape, measured in points.<br/>            Lezen/Schrijven **float**. |
| [`height`](/slides/python-net/nl/aspose.slides.charts/chart/height/) | Returns or sets the height of the shape, measured in points.<br/>            Lezen/Schrijven **float**. |
| [`black_white_mode`](/slides/python-net/nl/aspose.slides.charts/chart/black_white_mode/) | Property specifies how a shape will render in black-and-white display mode..<br/>            Lezen/Schrijven [`BlackWhiteMode`](/slides/python-net/nl/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/nl/aspose.slides.charts/chart/unique_id/) | Returns an internal, presentation-scoped identifier intended for use by add-ins or other code.<br/>            Because this value can be reassigned by the user or programmatically, it must not be treated<br/>            as a persistent unique key.<br/>            Alleen-lezen **int**.<br/>            See also [`Shape.office_interop_shape_id`](/slides/python-net/nl/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/nl/aspose.slides.charts/chart/office_interop_shape_id/) | Returns a slide-scoped unique identifier that remains constant for the lifetime of the shape and<br/>            lets PowerPoint or interop code reliably reference the shape from anywhere in the document.<br/>            Alleen-lezen **int**.<br/>            See also [`Shape.unique_id`](/slides/python-net/nl/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/nl/aspose.slides.charts/chart/alternative_text/) | Returns or sets the alternative text associated with a shape.<br/>            Lezen/Schrijven **str**. |
| [`alternative_text_title`](/slides/python-net/nl/aspose.slides.charts/chart/alternative_text_title/) | Returns or sets the title of alternative text associated with a shape.<br/>            Lezen/Schrijven **str**. |
| [`name`](/slides/python-net/nl/aspose.slides.charts/chart/name/) | Returns or sets the name of a shape.<br/>            Must be not None. Use empty string value if needed.<br/>            Lezen/Schrijven **str**. |
| [`is_decorative`](/slides/python-net/nl/aspose.slides.charts/chart/is_decorative/) | Gets or sets 'Mark as decorative' option<br/>            Lezen/Schrijven **bool**. |
| [`shape_lock`](/slides/python-net/nl/aspose.slides.charts/chart/shape_lock/) | Returns shape's locks.<br/>            Alleen-lezen [`IGraphicalObjectLock`](/slides/python-net/nl/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/nl/aspose.slides.charts/chart/is_grouped/) | Determines whether the shape is grouped.<br/>            Alleen-lezen **bool**. |
| [`parent_group`](/slides/python-net/nl/aspose.slides.charts/chart/parent_group/) | Returns parent GroupShape object if shape is grouped. Otherwise returns None.<br/>            Alleen-lezen [`IGroupShape`](/slides/python-net/nl/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/nl/aspose.slides.charts/chart/slide/) | Returns the parent slide of a shape.<br/>            Alleen-lezen [`IBaseSlide`](/slides/python-net/nl/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/nl/aspose.slides.charts/chart/presentation/) | Returns the parent presentation of a slide.<br/>            Alleen-lezen [`IPresentation`](/slides/python-net/nl/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/nl/aspose.slides.charts/chart/graphical_object_lock/) | Returns shape's locks.<br/>            Alleen-lezen [`IGraphicalObjectLock`](/slides/python-net/nl/aspose.slides/igraphicalobjectlock). |
| [`plot_visible_cells_only`](/slides/python-net/nl/aspose.slides.charts/chart/plot_visible_cells_only/) | Determines whether the only visible cells are plotted. False to plot both visible and hidden cells.<br/>            Lezen/Schrijven **bool**. |
| [`display_blanks_as`](/slides/python-net/nl/aspose.slides.charts/chart/display_blanks_as/) | Returns or sets the way to plot blank cells on a chart.<br/>            Lezen/Schrijven [`DisplayBlanksAsType`](/slides/python-net/nl/aspose.slides.charts/displayblanksastype). |
| [`chart_data`](/slides/python-net/nl/aspose.slides.charts/chart/chart_data/) | Returns information about the linked or embedded data associated with a chart.<br/>            Alleen-lezen [`IChartData`](/slides/python-net/nl/aspose.slides.charts/ichartdata). |
| [`has_title`](/slides/python-net/nl/aspose.slides.charts/chart/has_title/) | Determines whether a chart has a visible title.<br/>            Lezen/Schrijven **bool**. |
| [`chart_title`](/slides/python-net/nl/aspose.slides.charts/chart/chart_title/) | Returns or sets a chart title.<br/>            Alleen-lezen [`IChartTitle`](/slides/python-net/nl/aspose.slides.charts/icharttitle). |
| [`has_data_table`](/slides/python-net/nl/aspose.slides.charts/chart/has_data_table/) | Determines whether a chart has a data table.<br/>            Lezen/Schrijven **bool**. |
| [`has_legend`](/slides/python-net/nl/aspose.slides.charts/chart/has_legend/) | Determines whether a chart has a legend.<br/>            Lezen/Schrijven **bool**. |
| [`legend`](/slides/python-net/nl/aspose.slides.charts/chart/legend/) | Returns or sets a legend for a chart.<br/>            Alleen-lezen [`ILegend`](/slides/python-net/nl/aspose.slides.charts/ilegend). |
| [`chart_data_table`](/slides/python-net/nl/aspose.slides.charts/chart/chart_data_table/) | Returns a data table of a chart.<br/>            Alleen-lezen [`IDataTable`](/slides/python-net/nl/aspose.slides.charts/idatatable). |
| [`style`](/slides/python-net/nl/aspose.slides.charts/chart/style/) | Returns or sets the chart style.<br/>            Lezen/Schrijven [`StyleType`](/slides/python-net/nl/aspose.slides.charts/styletype). |
| [`type`](/slides/python-net/nl/aspose.slides.charts/chart/type/) | Returns or sets the chart type.<br/>            Lezen/Schrijven [`ChartType`](/slides/python-net/nl/aspose.slides.charts/charttype). |
| [`plot_area`](/slides/python-net/nl/aspose.slides.charts/chart/plot_area/) | Represents the plot area of a chart.<br/>            Alleen-lezen [`IChartPlotArea`](/slides/python-net/nl/aspose.slides.charts/ichartplotarea). |
| [`rotation_3d`](/slides/python-net/nl/aspose.slides.charts/chart/rotation_3d/) | Returns a 3D rotation of a chart.<br/>            Alleen-lezen [`IRotation3D`](/slides/python-net/nl/aspose.slides.charts/irotation3d). |
| [`back_wall`](/slides/python-net/nl/aspose.slides.charts/chart/back_wall/) | Returns an object which allows to change format of the back wall of a 3D chart.<br/>            Alleen-lezen [`IChartWall`](/slides/python-net/nl/aspose.slides.charts/ichartwall). |
| [`side_wall`](/slides/python-net/nl/aspose.slides.charts/chart/side_wall/) | Returns an object which allows to change format of the side wall of a 3D chart.<br/>            Alleen-lezen [`IChartWall`](/slides/python-net/nl/aspose.slides.charts/ichartwall). |
| [`floor`](/slides/python-net/nl/aspose.slides.charts/chart/floor/) | Returns an object which allows to change format of the floor of a 3D chart.<br/>            Alleen-lezen [`IChartWall`](/slides/python-net/nl/aspose.slides.charts/ichartwall). |
| [`text_format`](/slides/python-net/nl/aspose.slides.charts/chart/text_format/) | Returns chart text format.<br/>            The property is not applicable for the following types: [`ChartType.TREEMAP`](/slides/python-net/nl/aspose.slides.charts/charttype/TREEMAP), [`ChartType.SUNBURST`](/slides/python-net/nl/aspose.slides.charts/charttype/SUNBURST),<br/>            [`ChartType.WATERFALL`](/slides/python-net/nl/aspose.slides.charts/charttype/WATERFALL), [`ChartType.HISTOGRAM`](/slides/python-net/nl/aspose.slides.charts/charttype/HISTOGRAM), [`ChartType.FUNNEL`](/slides/python-net/nl/aspose.slides.charts/charttype/FUNNEL),[`ChartType.BOX_AND_WHISKER`](/slides/python-net/nl/aspose.slides.charts/charttype/BOX_AND_WHISKER).<br/>            Alleen-lezen [`IChartTextFormat`](/slides/python-net/nl/aspose.slides.charts/icharttextformat). |
| [`theme_manager`](/slides/python-net/nl/aspose.slides.charts/chart/theme_manager/) | Returns theme manager.<br/>            Alleen-lezen [`IOverrideThemeManager`](/slides/python-net/nl/aspose.slides.theme/ioverridethememanager). |
| [`user_shapes`](/slides/python-net/nl/aspose.slides.charts/chart/user_shapes/) | Specify the shapes drawn on top of the chart.<br/>            Alleen-lezen [`IGroupShape`](/slides/python-net/nl/aspose.slides/igroupshape). |
| [`axes`](/slides/python-net/nl/aspose.slides.charts/chart/axes/) | Provide access to chart axes.<br/>            Alleen-lezen [`IAxesManager`](/slides/python-net/nl/aspose.slides.charts/iaxesmanager). |
| [`show_data_labels_over_maximum`](/slides/python-net/nl/aspose.slides.charts/chart/show_data_labels_over_maximum/) | Specifies data labels over the maximum of the chart shall be shown.<br/>            Lezen/Schrijven **bool**. |
| [`has_rounded_corners`](/slides/python-net/nl/aspose.slides.charts/chart/has_rounded_corners/) | Specifies the chart area shall have rounded corners.<br/>            Lezen/Schrijven **bool**. |
| [`chart`](/slides/python-net/nl/aspose.slides.charts/chart/chart/) |  |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`get_image(self)`](/slides/python-net/nl/aspose.slides.charts/chart/get_image/#) | Returns shape thumbnail.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/nl/aspose.slides.charts/chart/get_image/#shapethumbnailbounds-float-float) | Returns shape thumbnail. |
| [`write_as_svg(self, stream)`](/slides/python-net/nl/aspose.slides.charts/chart/write_as_svg/#iorawiobase) | Saves content of Shape as SVG file. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/nl/aspose.slides.charts/chart/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Saves content of Shape as SVG file. |
| [`remove_placeholder(self)`](/slides/python-net/nl/aspose.slides.charts/chart/remove_placeholder/#) | Defines that this shape isn't a placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/nl/aspose.slides.charts/chart/add_placeholder/#iplaceholder) | Adds a new placeholder if there is no and sets placeholder properties to a specified one. |
| [`get_base_placeholder(self)`](/slides/python-net/nl/aspose.slides.charts/chart/get_base_placeholder/#) | Returns a basic placeholder shape (shape from the layout and/or master slide that the current shape is inherited from).<br/>            A None is returned if the current shape is not inherited. |
| [`get_visual_bounds(self)`](/slides/python-net/nl/aspose.slides.charts/chart/get_visual_bounds/#) | Gets the visual bounds of the shape calculated from its rendered content. |
| [`validate_chart_layout(self)`](/slides/python-net/nl/aspose.slides.charts/chart/validate_chart_layout/#) | Calculates actual values of chart elements. The actual values include position of elements that implement IActualLayout interface <br/>            (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight)<br/>            and actual axes values (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, <br/>            IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) |
| [`create_theme_effective(self)`](/slides/python-net/nl/aspose.slides.charts/chart/create_theme_effective/#) | Returns an effective theme for this chart. |

### Zie ook
* klasse [`Chart`](/slides/python-net/nl/aspose.slides.charts/chart)
* klasse [`GraphicalObject`](/slides/python-net/nl/aspose.slides/graphicalobject)
* klasse [`Shape`](/slides/python-net/nl/aspose.slides/shape)
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)