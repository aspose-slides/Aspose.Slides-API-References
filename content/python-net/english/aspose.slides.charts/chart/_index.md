---
title: Chart
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.charts/chart/
---


Chart class

Represents an graphic chart on a slide.

**Inheritance:**[`Chart`](/slides/python-net/aspose.slides.charts/chart)

The Chart type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [is_text_holder](/slides/python-net/aspose.slides.charts/chart/is_text_holder/) | Determines whether the shape is TextHolder_PPT.<br/>            Read-only :py:class:`bool`. |
| [placeholder](/slides/python-net/aspose.slides.charts/chart/placeholder/) | Returns the placeholder for a shape. Returns null if the shape has no placeholder.<br/>            Read-only :py:class:`aspose.slides.IPlaceholder`. |
| [custom_data](/slides/python-net/aspose.slides.charts/chart/custom_data/) | Returns the shape's custom data.<br/>            Read-only :py:class:`aspose.slides.ICustomData`. |
| [raw_frame](/slides/python-net/aspose.slides.charts/chart/raw_frame/) | Returns or sets the raw shape frame's properties.<br/>            Read/write :py:class:`aspose.slides.IShapeFrame`. |
| [frame](/slides/python-net/aspose.slides.charts/chart/frame/) | Returns or sets the shape frame's properties.<br/>            Read/write :py:class:`aspose.slides.IShapeFrame`. |
| [line_format](/slides/python-net/aspose.slides.charts/chart/line_format/) | Returns the LineFormat object that contains line formatting properties for a shape.<br/>            Note: can return null for certain types of shapes which don't have line properties.<br/>            Read-only :py:class:`aspose.slides.ILineFormat`. |
| [three_d_format](/slides/python-net/aspose.slides.charts/chart/three_d_format/) | Returns the ThreeDFormat object that 3d effect properties for a shape.<br/>            Note: can return null for certain types of shapes which don't have 3d properties.<br/>            Read-only :py:class:`aspose.slides.IThreeDFormat`. |
| [effect_format](/slides/python-net/aspose.slides.charts/chart/effect_format/) | Returns the EffectFormat object which contains pixel effects applied to a shape.<br/>            Note: can return null for certain types of shapes which don't have effect properties.<br/>            Read-only :py:class:`aspose.slides.IEffectFormat`. |
| [fill_format](/slides/python-net/aspose.slides.charts/chart/fill_format/) | Returns the FillFormat object that contains fill formatting properties for a shape.<br/>            Note: can return null for certain types of shapes which don't have fill properties.<br/>            Read-only :py:class:`aspose.slides.IFillFormat`. |
| [hyperlink_click](/slides/python-net/aspose.slides.charts/chart/hyperlink_click/) | Returns or sets the hyperlink defined for mouse click.<br/>            Read/write :py:class:`aspose.slides.IHyperlink`. |
| [hyperlink_mouse_over](/slides/python-net/aspose.slides.charts/chart/hyperlink_mouse_over/) | Returns or sets the hyperlink defined for mouse over.<br/>            Read/write :py:class:`aspose.slides.IHyperlink`. |
| [hyperlink_manager](/slides/python-net/aspose.slides.charts/chart/hyperlink_manager/) | Returns the hyperlink manager.<br/>            Read-only :py:class:`aspose.slides.IHyperlinkManager`. |
| [hidden](/slides/python-net/aspose.slides.charts/chart/hidden/) | Determines whether the shape is hidden.<br/>            Read/write :py:class:`bool`. |
| [z_order_position](/slides/python-net/aspose.slides.charts/chart/z_order_position/) | Returns the position of a shape in the z-order.<br/>            Shapes[0] returns the shape at the back of the z-order,<br/>            and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order.<br/>            Read-only :py:class:`int`. |
| [connection_site_count](/slides/python-net/aspose.slides.charts/chart/connection_site_count/) | Returns the number of connection sites on the shape.<br/>            Read-only :py:class:`int`. |
| [rotation](/slides/python-net/aspose.slides.charts/chart/rotation/) | Returns or sets the number of degrees the specified shape is rotated around<br/>            the z-axis. A positive value indicates clockwise rotation; a negative value<br/>            indicates counterclockwise rotation.<br/>            Read/write :py:class:`float`. |
| [x](/slides/python-net/aspose.slides.charts/chart/x/) | Returns or sets the x-coordinate of the upper-left corner of the shape.<br/>            Read/write :py:class:`float`. |
| [y](/slides/python-net/aspose.slides.charts/chart/y/) | Returns or sets the y-coordinate of the upper-left corner of the shape.<br/>            Read/write :py:class:`float`. |
| [width](/slides/python-net/aspose.slides.charts/chart/width/) | Returns or sets the width of the shape.<br/>            Read/write :py:class:`float`. |
| [height](/slides/python-net/aspose.slides.charts/chart/height/) | Returns or sets the height of the shape.<br/>            Read/write :py:class:`float`. |
| [black_white_mode](/slides/python-net/aspose.slides.charts/chart/black_white_mode/) | Property specifies how a shape will render in black-and-white display mode..<br/>            Read/write :py:enum:`aspose.slides.BlackWhiteMode`. |
| [unique_id](/slides/python-net/aspose.slides.charts/chart/unique_id/) | Gets unique shape identifier in presentation scope.<br/>            Read-only :py:class:`int`.<br/>            See also :py:attr:`aspose.slides.Shape.office_interop_shape_id` for getting unique shape identifier in slide scope. |
| [office_interop_shape_id](/slides/python-net/aspose.slides.charts/chart/office_interop_shape_id/) | Gets unique shape identifier in slide scope.<br/>            Read-only :py:class:`int`.<br/>            See also :py:attr:`aspose.slides.Shape.unique_id` for getting unique shape identifier in presentation scope. |
| [alternative_text](/slides/python-net/aspose.slides.charts/chart/alternative_text/) | Returns or sets the alternative text associated with a shape.<br/>            Read/write :py:class:`System.String`. |
| [alternative_text_title](/slides/python-net/aspose.slides.charts/chart/alternative_text_title/) | Returns or sets the title of alternative text associated with a shape.<br/>            Read/write :py:class:`System.String`. |
| [name](/slides/python-net/aspose.slides.charts/chart/name/) | Returns or sets the name of a shape.<br/>            Must be not null. Use empty string value if needed.<br/>            Read/write :py:class:`System.String`. |
| [is_decorative](/slides/python-net/aspose.slides.charts/chart/is_decorative/) | Gets or sets 'Mark as decorative' option<br/>            Reed/write :py:class:`bool`. |
| [shape_lock](/slides/python-net/aspose.slides.charts/chart/shape_lock/) | Returns shape's locks.<br/>            Read-only :py:class:`aspose.slides.IGraphicalObjectLock`. |
| [is_grouped](/slides/python-net/aspose.slides.charts/chart/is_grouped/) | Determines whether the shape is grouped.<br/>            Read-only :py:class:`bool`. |
| [parent_group](/slides/python-net/aspose.slides.charts/chart/parent_group/) | Returns parent GroupShape object if shape is grouped. Otherwise returns null.<br/>            Read-only :py:class:`aspose.slides.IGroupShape`. |
| [slide](/slides/python-net/aspose.slides.charts/chart/slide/) | Returns the parent slide of a shape.<br/>            Read-only :py:class:`aspose.slides.IBaseSlide`. |
| [presentation](/slides/python-net/aspose.slides.charts/chart/presentation/) | Returns the parent presentation of a slide.<br/>            Read-only :py:class:`aspose.slides.IPresentation`. |
| [graphical_object_lock](/slides/python-net/aspose.slides.charts/chart/graphical_object_lock/) | Returns shape's locks.<br/>            Read-only :py:class:`aspose.slides.IGraphicalObjectLock`. |
| [plot_visible_cells_only](/slides/python-net/aspose.slides.charts/chart/plot_visible_cells_only/) | Determines whether the only visible cells are plotted. False to plot both visible and hidden cells.<br/>            Read/write :py:class:`bool`. |
| [display_blanks_as](/slides/python-net/aspose.slides.charts/chart/display_blanks_as/) | Returns or sets the way to plot blank cells on a chart.<br/>            Read/write :py:enum:`aspose.slides.charts.DisplayBlanksAsType`. |
| [chart_data](/slides/python-net/aspose.slides.charts/chart/chart_data/) | Returns information about the linked or embedded data associated with a chart.<br/>            Read-only :py:class:`aspose.slides.charts.IChartData`. |
| [has_title](/slides/python-net/aspose.slides.charts/chart/has_title/) | Determines whether a chart has a visible title.<br/>            Read/write :py:class:`bool`. |
| [chart_title](/slides/python-net/aspose.slides.charts/chart/chart_title/) | Returns or sets a chart title.<br/>            Read-only :py:class:`aspose.slides.charts.IChartTitle`. |
| [has_data_table](/slides/python-net/aspose.slides.charts/chart/has_data_table/) | Determines whether a chart has a data table.<br/>            Read/write :py:class:`bool`. |
| [has_legend](/slides/python-net/aspose.slides.charts/chart/has_legend/) | Determines whether a chart has a legend.<br/>            Read/write :py:class:`bool`. |
| [legend](/slides/python-net/aspose.slides.charts/chart/legend/) | Returns or sets a legend for a chart.<br/>            Read-only :py:class:`aspose.slides.charts.ILegend`. |
| [chart_data_table](/slides/python-net/aspose.slides.charts/chart/chart_data_table/) | Returns a data table of a chart.<br/>            Read-only :py:class:`aspose.slides.charts.IDataTable`. |
| [style](/slides/python-net/aspose.slides.charts/chart/style/) | Returns or sets the chart style.<br/>            Read/write :py:enum:`aspose.slides.charts.StyleType`. |
| [type](/slides/python-net/aspose.slides.charts/chart/type/) | Returns or sets the chart type.<br/>            Read/write :py:enum:`aspose.slides.charts.ChartType`. |
| [plot_area](/slides/python-net/aspose.slides.charts/chart/plot_area/) | Represents the plot area of a chart.<br/>            Read-only :py:class:`aspose.slides.charts.IChartPlotArea`. |
| [rotation_3d](/slides/python-net/aspose.slides.charts/chart/rotation_3d/) | Returns a 3D rotation of a chart.<br/>            Read-only :py:class:`aspose.slides.charts.IRotation3D`. |
| [back_wall](/slides/python-net/aspose.slides.charts/chart/back_wall/) | Returns an object which allows to change format of the back wall of a 3D chart.<br/>            Read-only :py:class:`aspose.slides.charts.IChartWall`. |
| [side_wall](/slides/python-net/aspose.slides.charts/chart/side_wall/) | Returns an object which allows to change format of the side wall of a 3D chart.<br/>            Read-only :py:class:`aspose.slides.charts.IChartWall`. |
| [floor](/slides/python-net/aspose.slides.charts/chart/floor/) | Returns an object which allows to change format of the floor of a 3D chart.<br/>            Read-only :py:class:`aspose.slides.charts.IChartWall`. |
| [text_format](/slides/python-net/aspose.slides.charts/chart/text_format/) | Returns chart text format.<br/>            The property is not applicable for the following types: :py:attr:`aspose.slides.charts.ChartType.TREEMAP`, :py:attr:`aspose.slides.charts.ChartType.SUNBURST`,<br/>            :py:attr:`aspose.slides.charts.ChartType.WATERFALL`, :py:attr:`aspose.slides.charts.ChartType.HISTOGRAM`, :py:attr:`aspose.slides.charts.ChartType.FUNNEL`,:py:attr:`aspose.slides.charts.ChartType.BOX_AND_WHISKER`.<br/>            Read-only :py:class:`aspose.slides.charts.IChartTextFormat`. |
| [theme_manager](/slides/python-net/aspose.slides.charts/chart/theme_manager/) | Returns theme manager.<br/>            Read-only :py:class:`aspose.slides.theme.IOverrideThemeManager`. |
| [user_shapes](/slides/python-net/aspose.slides.charts/chart/user_shapes/) | Specify the shapes drawn on top of the chart.<br/>            Read-only :py:class:`aspose.slides.IGroupShape`. |
| [axes](/slides/python-net/aspose.slides.charts/chart/axes/) | Provide access to chart axes.<br/>            Read-only :py:class:`aspose.slides.charts.IAxesManager`. |
| [show_data_labels_over_maximum](/slides/python-net/aspose.slides.charts/chart/show_data_labels_over_maximum/) | Specifies data labels over the maximum of the chart shall be shown.<br/>            Read/write :py:class:`bool`. |
| [has_rounded_corners](/slides/python-net/aspose.slides.charts/chart/has_rounded_corners/) | Specifies the chart area shall have rounded corners.<br/>            Read/write :py:class:`bool`. |
| [as_i_formatted_text_container](/slides/python-net/aspose.slides.charts/chart/as_i_formatted_text_container/) | Allows to get base IFormattedTextContainer interface.<br/>            Read-only :py:class:`aspose.slides.charts.IFormattedTextContainer`. |
| [as_i_themeable](/slides/python-net/aspose.slides.charts/chart/as_i_themeable/) | Allows to get base IThemeable interface.<br/>            Read-only :py:class:`aspose.slides.theme.IThemeable`. |
| [as_i_hyperlink_container](/slides/python-net/aspose.slides.charts/chart/as_i_hyperlink_container/) |  |
| [as_i_presentation_component](/slides/python-net/aspose.slides.charts/chart/as_i_presentation_component/) |  |
| [as_i_shape](/slides/python-net/aspose.slides.charts/chart/as_i_shape/) |  |
| [as_i_graphical_object](/slides/python-net/aspose.slides.charts/chart/as_i_graphical_object/) |  |
| [as_i_override_themeable](/slides/python-net/aspose.slides.charts/chart/as_i_override_themeable/) |  |
| [as_i_chart_component](/slides/python-net/aspose.slides.charts/chart/as_i_chart_component/) |  |
| [chart](/slides/python-net/aspose.slides.charts/chart/chart/) |  |

## Methods

| Method | Description |
| :- | :- |
| [get_thumbnail](/slides/python-net/aspose.slides.charts/chart/chart/#/) | Returns shape thumbnail.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [get_thumbnail](/slides/python-net/aspose.slides.charts/chart/chart/#ShapeThumbnailBounds-float-float/) |  |
| [write_as_svg](/slides/python-net/aspose.slides.charts/chart/chart/#System.IO.Stream/) | Saves content of Shape as SVG file. |
| [write_as_svg](/slides/python-net/aspose.slides.charts/chart/chart/#System.IO.Stream-aspose.slides.export.ISVGOptions/) | Saves content of Shape as SVG file. |
| [remove_placeholder](/slides/python-net/aspose.slides.charts/chart/chart/#/) | Defines that this shape isn't a placeholder. |
| [add_placeholder](/slides/python-net/aspose.slides.charts/chart/chart/#IPlaceholder/) |  |
| [get_base_placeholder](/slides/python-net/aspose.slides.charts/chart/chart/#/) | Returns a basic placeholder shape (shape from the layout and/or master slide that the current shape is inherited from). |
| [validate_chart_layout](/slides/python-net/aspose.slides.charts/chart/chart/#/) | Calculates actual values of chart elements. The actual values include position of elements that implement IActualLayout interface <br/>            (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight)<br/>            and actual axes values (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, <br/>            IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) |
| [create_theme_effective](/slides/python-net/aspose.slides.charts/chart/chart/#/) | Returns an effective theme for this chart. |

