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
| [is_text_holder](/slides/python-net/aspose.slides.charts/chart/is_text_holder/) | Determines whether the shape is TextHolder_PPT.<br/>            Read-only <br/>.NET type System.Boolean<br/>. |
| [placeholder](/slides/python-net/aspose.slides.charts/chart/placeholder/) | Returns the placeholder for a shape. Returns null if the shape has no placeholder.<br/>            Read-only <br/>[`IPlaceholder`](/slides/python-net/aspose.slides/iplaceholder)<br/>. |
| [custom_data](/slides/python-net/aspose.slides.charts/chart/custom_data/) | Returns the shape's custom data.<br/>            Read-only <br/>[`ICustomData`](/slides/python-net/aspose.slides/icustomdata)<br/>. |
| [raw_frame](/slides/python-net/aspose.slides.charts/chart/raw_frame/) | Returns or sets the raw shape frame's properties.<br/>            Read/write <br/>[`IShapeFrame`](/slides/python-net/aspose.slides/ishapeframe)<br/>. |
| [frame](/slides/python-net/aspose.slides.charts/chart/frame/) | Returns or sets the shape frame's properties.<br/>            Read/write <br/>[`IShapeFrame`](/slides/python-net/aspose.slides/ishapeframe)<br/>. |
| [line_format](/slides/python-net/aspose.slides.charts/chart/line_format/) | Returns the LineFormat object that contains line formatting properties for a shape.<br/>            Note: can return null for certain types of shapes which don't have line properties.<br/>            Read-only <br/>[`ILineFormat`](/slides/python-net/aspose.slides/ilineformat)<br/>. |
| [three_d_format](/slides/python-net/aspose.slides.charts/chart/three_d_format/) | Returns the ThreeDFormat object that 3d effect properties for a shape.<br/>            Note: can return null for certain types of shapes which don't have 3d properties.<br/>            Read-only <br/>[`IThreeDFormat`](/slides/python-net/aspose.slides/ithreedformat)<br/>. |
| [effect_format](/slides/python-net/aspose.slides.charts/chart/effect_format/) | Returns the EffectFormat object which contains pixel effects applied to a shape.<br/>            Note: can return null for certain types of shapes which don't have effect properties.<br/>            Read-only <br/>[`IEffectFormat`](/slides/python-net/aspose.slides/ieffectformat)<br/>. |
| [fill_format](/slides/python-net/aspose.slides.charts/chart/fill_format/) | Returns the FillFormat object that contains fill formatting properties for a shape.<br/>            Note: can return null for certain types of shapes which don't have fill properties.<br/>            Read-only <br/>[`IFillFormat`](/slides/python-net/aspose.slides/ifillformat)<br/>. |
| [hyperlink_click](/slides/python-net/aspose.slides.charts/chart/hyperlink_click/) | Returns or sets the hyperlink defined for mouse click.<br/>            Read/write <br/>[`IHyperlink`](/slides/python-net/aspose.slides/ihyperlink)<br/>. |
| [hyperlink_mouse_over](/slides/python-net/aspose.slides.charts/chart/hyperlink_mouse_over/) | Returns or sets the hyperlink defined for mouse over.<br/>            Read/write <br/>[`IHyperlink`](/slides/python-net/aspose.slides/ihyperlink)<br/>. |
| [hyperlink_manager](/slides/python-net/aspose.slides.charts/chart/hyperlink_manager/) | Returns the hyperlink manager.<br/>            Read-only <br/>[`IHyperlinkManager`](/slides/python-net/aspose.slides/ihyperlinkmanager)<br/>. |
| [hidden](/slides/python-net/aspose.slides.charts/chart/hidden/) | Determines whether the shape is hidden.<br/>            Read/write <br/>.NET type System.Boolean<br/>. |
| [z_order_position](/slides/python-net/aspose.slides.charts/chart/z_order_position/) | Returns the position of a shape in the z-order.<br/>            Shapes[0] returns the shape at the back of the z-order,<br/>            and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order.<br/>            Read-only <br/>.NET type System.Int32<br/>. |
| [connection_site_count](/slides/python-net/aspose.slides.charts/chart/connection_site_count/) | Returns the number of connection sites on the shape.<br/>            Read-only <br/>.NET type System.Int32<br/>. |
| [rotation](/slides/python-net/aspose.slides.charts/chart/rotation/) | Returns or sets the number of degrees the specified shape is rotated around<br/>            the z-axis. A positive value indicates clockwise rotation; a negative value<br/>            indicates counterclockwise rotation.<br/>            Read/write <br/>.NET type System.Single<br/>. |
| [x](/slides/python-net/aspose.slides.charts/chart/x/) | Returns or sets the x-coordinate of the upper-left corner of the shape.<br/>            Read/write <br/>.NET type System.Single<br/>. |
| [y](/slides/python-net/aspose.slides.charts/chart/y/) | Returns or sets the y-coordinate of the upper-left corner of the shape.<br/>            Read/write <br/>.NET type System.Single<br/>. |
| [width](/slides/python-net/aspose.slides.charts/chart/width/) | Returns or sets the width of the shape.<br/>            Read/write <br/>.NET type System.Single<br/>. |
| [height](/slides/python-net/aspose.slides.charts/chart/height/) | Returns or sets the height of the shape.<br/>            Read/write <br/>.NET type System.Single<br/>. |
| [black_white_mode](/slides/python-net/aspose.slides.charts/chart/black_white_mode/) | Property specifies how a shape will render in black-and-white display mode..<br/>            Read/write <br/>[`BlackWhiteMode`](/slides/python-net/aspose.slides/blackwhitemode)<br/>. |
| [unique_id](/slides/python-net/aspose.slides.charts/chart/unique_id/) | Gets unique shape identifier in presentation scope.<br/>            Read-only <br/>.NET type System.UInt32<br/>.<br/>            See also <br/>[`Shape.office_interop_shape_id`](/slides/python-net/aspose.slides/shape#office_interop_shape_id)<br/> for getting unique shape identifier in slide scope. |
| [office_interop_shape_id](/slides/python-net/aspose.slides.charts/chart/office_interop_shape_id/) | Gets unique shape identifier in slide scope.<br/>            Read-only <br/>.NET type System.UInt32<br/>.<br/>            See also <br/>[`Shape.unique_id`](/slides/python-net/aspose.slides/shape#unique_id)<br/> for getting unique shape identifier in presentation scope. |
| [alternative_text](/slides/python-net/aspose.slides.charts/chart/alternative_text/) | Returns or sets the alternative text associated with a shape.<br/>            Read/write <br/>.NET type System.String<br/>. |
| [alternative_text_title](/slides/python-net/aspose.slides.charts/chart/alternative_text_title/) | Returns or sets the title of alternative text associated with a shape.<br/>            Read/write <br/>.NET type System.String<br/>. |
| [name](/slides/python-net/aspose.slides.charts/chart/name/) | Returns or sets the name of a shape.<br/>            Must be not null. Use empty string value if needed.<br/>            Read/write <br/>.NET type System.String<br/>. |
| [is_decorative](/slides/python-net/aspose.slides.charts/chart/is_decorative/) | Gets or sets 'Mark as decorative' option<br/>            Reed/write <br/>.NET type System.Boolean<br/>. |
| [shape_lock](/slides/python-net/aspose.slides.charts/chart/shape_lock/) | Returns shape's locks.<br/>            Read-only <br/>[`IGraphicalObjectLock`](/slides/python-net/aspose.slides/igraphicalobjectlock)<br/>. |
| [is_grouped](/slides/python-net/aspose.slides.charts/chart/is_grouped/) | Determines whether the shape is grouped.<br/>            Read-only <br/>.NET type System.Boolean<br/>. |
| [parent_group](/slides/python-net/aspose.slides.charts/chart/parent_group/) | Returns parent GroupShape object if shape is grouped. Otherwise returns null.<br/>            Read-only <br/>[`IGroupShape`](/slides/python-net/aspose.slides/igroupshape)<br/>. |
| [slide](/slides/python-net/aspose.slides.charts/chart/slide/) | Returns the parent slide of a shape.<br/>            Read-only <br/>[`IBaseSlide`](/slides/python-net/aspose.slides/ibaseslide)<br/>. |
| [presentation](/slides/python-net/aspose.slides.charts/chart/presentation/) | Returns the parent presentation of a slide.<br/>            Read-only <br/>[`IPresentation`](/slides/python-net/aspose.slides/ipresentation)<br/>. |
| [graphical_object_lock](/slides/python-net/aspose.slides.charts/chart/graphical_object_lock/) | Returns shape's locks.<br/>            Read-only <br/>[`IGraphicalObjectLock`](/slides/python-net/aspose.slides/igraphicalobjectlock)<br/>. |
| [plot_visible_cells_only](/slides/python-net/aspose.slides.charts/chart/plot_visible_cells_only/) | Determines whether the only visible cells are plotted. False to plot both visible and hidden cells.<br/>            Read/write <br/>.NET type System.Boolean<br/>. |
| [display_blanks_as](/slides/python-net/aspose.slides.charts/chart/display_blanks_as/) | Returns or sets the way to plot blank cells on a chart.<br/>            Read/write <br/>[`DisplayBlanksAsType`](/slides/python-net/aspose.slides.charts/displayblanksastype)<br/>. |
| [chart_data](/slides/python-net/aspose.slides.charts/chart/chart_data/) | Returns information about the linked or embedded data associated with a chart.<br/>            Read-only <br/>[`IChartData`](/slides/python-net/aspose.slides.charts/ichartdata)<br/>. |
| [has_title](/slides/python-net/aspose.slides.charts/chart/has_title/) | Determines whether a chart has a visible title.<br/>            Read/write <br/>.NET type System.Boolean<br/>. |
| [chart_title](/slides/python-net/aspose.slides.charts/chart/chart_title/) | Returns or sets a chart title.<br/>            Read-only <br/>[`IChartTitle`](/slides/python-net/aspose.slides.charts/icharttitle)<br/>. |
| [has_data_table](/slides/python-net/aspose.slides.charts/chart/has_data_table/) | Determines whether a chart has a data table.<br/>            Read/write <br/>.NET type System.Boolean<br/>. |
| [has_legend](/slides/python-net/aspose.slides.charts/chart/has_legend/) | Determines whether a chart has a legend.<br/>            Read/write <br/>.NET type System.Boolean<br/>. |
| [legend](/slides/python-net/aspose.slides.charts/chart/legend/) | Returns or sets a legend for a chart.<br/>            Read-only <br/>[`ILegend`](/slides/python-net/aspose.slides.charts/ilegend)<br/>. |
| [chart_data_table](/slides/python-net/aspose.slides.charts/chart/chart_data_table/) | Returns a data table of a chart.<br/>            Read-only <br/>[`IDataTable`](/slides/python-net/aspose.slides.charts/idatatable)<br/>. |
| [style](/slides/python-net/aspose.slides.charts/chart/style/) | Returns or sets the chart style.<br/>            Read/write <br/>[`StyleType`](/slides/python-net/aspose.slides.charts/styletype)<br/>. |
| [type](/slides/python-net/aspose.slides.charts/chart/type/) | Returns or sets the chart type.<br/>            Read/write <br/>[`ChartType`](/slides/python-net/aspose.slides.charts/charttype)<br/>. |
| [plot_area](/slides/python-net/aspose.slides.charts/chart/plot_area/) | Represents the plot area of a chart.<br/>            Read-only <br/>[`IChartPlotArea`](/slides/python-net/aspose.slides.charts/ichartplotarea)<br/>. |
| [rotation_3d](/slides/python-net/aspose.slides.charts/chart/rotation_3d/) | Returns a 3D rotation of a chart.<br/>            Read-only <br/>[`IRotation3D`](/slides/python-net/aspose.slides.charts/irotation3d)<br/>. |
| [back_wall](/slides/python-net/aspose.slides.charts/chart/back_wall/) | Returns an object which allows to change format of the back wall of a 3D chart.<br/>            Read-only <br/>[`IChartWall`](/slides/python-net/aspose.slides.charts/ichartwall)<br/>. |
| [side_wall](/slides/python-net/aspose.slides.charts/chart/side_wall/) | Returns an object which allows to change format of the side wall of a 3D chart.<br/>            Read-only <br/>[`IChartWall`](/slides/python-net/aspose.slides.charts/ichartwall)<br/>. |
| [floor](/slides/python-net/aspose.slides.charts/chart/floor/) | Returns an object which allows to change format of the floor of a 3D chart.<br/>            Read-only <br/>[`IChartWall`](/slides/python-net/aspose.slides.charts/ichartwall)<br/>. |
| [text_format](/slides/python-net/aspose.slides.charts/chart/text_format/) | Returns chart text format.<br/>            The property is not applicable for the following types: <br/>[`ChartType.TREEMAP`](/slides/python-net/aspose.slides.charts/charttype#TREEMAP)<br/>, <br/>[`ChartType.SUNBURST`](/slides/python-net/aspose.slides.charts/charttype#SUNBURST)<br/>,<br/>            <br/>[`ChartType.WATERFALL`](/slides/python-net/aspose.slides.charts/charttype#WATERFALL)<br/>, <br/>[`ChartType.HISTOGRAM`](/slides/python-net/aspose.slides.charts/charttype#HISTOGRAM)<br/>, <br/>[`ChartType.FUNNEL`](/slides/python-net/aspose.slides.charts/charttype#FUNNEL)<br/>,<br/>[`ChartType.BOX_AND_WHISKER`](/slides/python-net/aspose.slides.charts/charttype#BOX_AND_WHISKER)<br/>.<br/>            Read-only <br/>[`IChartTextFormat`](/slides/python-net/aspose.slides.charts/icharttextformat)<br/>. |
| [theme_manager](/slides/python-net/aspose.slides.charts/chart/theme_manager/) | Returns theme manager.<br/>            Read-only <br/>[`IOverrideThemeManager`](/slides/python-net/aspose.slides.theme/ioverridethememanager)<br/>. |
| [user_shapes](/slides/python-net/aspose.slides.charts/chart/user_shapes/) | Specify the shapes drawn on top of the chart.<br/>            Read-only <br/>[`IGroupShape`](/slides/python-net/aspose.slides/igroupshape)<br/>. |
| [axes](/slides/python-net/aspose.slides.charts/chart/axes/) | Provide access to chart axes.<br/>            Read-only <br/>[`IAxesManager`](/slides/python-net/aspose.slides.charts/iaxesmanager)<br/>. |
| [show_data_labels_over_maximum](/slides/python-net/aspose.slides.charts/chart/show_data_labels_over_maximum/) | Specifies data labels over the maximum of the chart shall be shown.<br/>            Read/write <br/>.NET type System.Boolean<br/>. |
| [has_rounded_corners](/slides/python-net/aspose.slides.charts/chart/has_rounded_corners/) | Specifies the chart area shall have rounded corners.<br/>            Read/write <br/>.NET type System.Boolean<br/>. |
| [as_i_formatted_text_container](/slides/python-net/aspose.slides.charts/chart/as_i_formatted_text_container/) | Allows to get base IFormattedTextContainer interface.<br/>            Read-only <br/>[`IFormattedTextContainer`](/slides/python-net/aspose.slides.charts/iformattedtextcontainer)<br/>. |
| [as_i_themeable](/slides/python-net/aspose.slides.charts/chart/as_i_themeable/) | Allows to get base IThemeable interface.<br/>            Read-only <br/>[`IThemeable`](/slides/python-net/aspose.slides.theme/ithemeable)<br/>. |
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
| [get_base_placeholder](/slides/python-net/aspose.slides.charts/chart/chart/#/) | Returns a basic placeholder shape (shape from the layout and/or master slide that the current shape is inherited from).<br/>            <br/>A null is returned if the current shape is not inherited. |
| [validate_chart_layout](/slides/python-net/aspose.slides.charts/chart/chart/#/) | Calculates actual values of chart elements. The actual values include position of elements that implement IActualLayout interface <br/>            (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight)<br/>            and actual axes values (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, <br/>            IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) |
| [create_theme_effective](/slides/python-net/aspose.slides.charts/chart/chart/#/) | Returns an effective theme for this chart. |

