---
title: AudioFrame
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/audioframe/
---


AudioFrame class

Represents an audio clip on a slide.

**Inheritance:**[`AudioFrame`](/slides/python-net/aspose.slides/audioframe) → [`PictureFrame`](/slides/python-net/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/aspose.slides/shape)

The AudioFrame type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [is_text_holder](/slides/python-net/aspose.slides/audioframe/is_text_holder/) | Determines whether the shape is TextHolder_PPT.<br/>            Read-only :py:class:`bool`. |
| [placeholder](/slides/python-net/aspose.slides/audioframe/placeholder/) | Returns the placeholder for a shape. Returns null if the shape has no placeholder.<br/>            Read-only :py:class:`aspose.slides.IPlaceholder`. |
| [custom_data](/slides/python-net/aspose.slides/audioframe/custom_data/) | Returns the shape's custom data.<br/>            Read-only :py:class:`aspose.slides.ICustomData`. |
| [raw_frame](/slides/python-net/aspose.slides/audioframe/raw_frame/) | Returns or sets the raw shape frame's properties.<br/>            Read/write :py:class:`aspose.slides.IShapeFrame`. |
| [frame](/slides/python-net/aspose.slides/audioframe/frame/) | Returns or sets the shape frame's properties.<br/>            Read/write :py:class:`aspose.slides.IShapeFrame`. |
| [line_format](/slides/python-net/aspose.slides/audioframe/line_format/) | Returns the LineFormat object that contains line formatting properties for a shape.<br/>            Note: can return null for certain types of shapes which don't have line properties.<br/>            Read-only :py:class:`aspose.slides.ILineFormat`. |
| [three_d_format](/slides/python-net/aspose.slides/audioframe/three_d_format/) | Returns the ThreeDFormat object that 3d effect properties for a shape.<br/>            Note: can return null for certain types of shapes which don't have 3d properties.<br/>            Read-only :py:class:`aspose.slides.IThreeDFormat`. |
| [effect_format](/slides/python-net/aspose.slides/audioframe/effect_format/) | Returns the EffectFormat object which contains pixel effects applied to a shape.<br/>            Note: can return null for certain types of shapes which don't have effect properties.<br/>            Read-only :py:class:`aspose.slides.IEffectFormat`. |
| [fill_format](/slides/python-net/aspose.slides/audioframe/fill_format/) | Returns the FillFormat object that contains fill formatting properties for a shape.<br/>            Note: can return null for certain types of shapes which don't have fill properties.<br/>            Read-only :py:class:`aspose.slides.IFillFormat`. |
| [hyperlink_click](/slides/python-net/aspose.slides/audioframe/hyperlink_click/) | Returns or sets the hyperlink defined for mouse click.<br/>            Read/write :py:class:`aspose.slides.IHyperlink`. |
| [hyperlink_mouse_over](/slides/python-net/aspose.slides/audioframe/hyperlink_mouse_over/) | Returns or sets the hyperlink defined for mouse over.<br/>            Read/write :py:class:`aspose.slides.IHyperlink`. |
| [hyperlink_manager](/slides/python-net/aspose.slides/audioframe/hyperlink_manager/) | Returns the hyperlink manager.<br/>            Read-only :py:class:`aspose.slides.IHyperlinkManager`. |
| [hidden](/slides/python-net/aspose.slides/audioframe/hidden/) | Determines whether the shape is hidden.<br/>            Read/write :py:class:`bool`. |
| [z_order_position](/slides/python-net/aspose.slides/audioframe/z_order_position/) | Returns the position of a shape in the z-order.<br/>            Shapes[0] returns the shape at the back of the z-order,<br/>            and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order.<br/>            Read-only :py:class:`int`. |
| [connection_site_count](/slides/python-net/aspose.slides/audioframe/connection_site_count/) | Returns the number of connection sites on the shape.<br/>            Read-only :py:class:`int`. |
| [rotation](/slides/python-net/aspose.slides/audioframe/rotation/) | Returns or sets the number of degrees the specified shape is rotated around<br/>            the z-axis. A positive value indicates clockwise rotation; a negative value<br/>            indicates counterclockwise rotation.<br/>            Read/write :py:class:`float`. |
| [x](/slides/python-net/aspose.slides/audioframe/x/) | Returns or sets the x-coordinate of the upper-left corner of the shape.<br/>            Read/write :py:class:`float`. |
| [y](/slides/python-net/aspose.slides/audioframe/y/) | Returns or sets the y-coordinate of the upper-left corner of the shape.<br/>            Read/write :py:class:`float`. |
| [width](/slides/python-net/aspose.slides/audioframe/width/) | Returns or sets the width of the shape.<br/>            Read/write :py:class:`float`. |
| [height](/slides/python-net/aspose.slides/audioframe/height/) | Returns or sets the height of the shape.<br/>            Read/write :py:class:`float`. |
| [black_white_mode](/slides/python-net/aspose.slides/audioframe/black_white_mode/) | Property specifies how a shape will render in black-and-white display mode..<br/>            Read/write :py:enum:`aspose.slides.BlackWhiteMode`. |
| [unique_id](/slides/python-net/aspose.slides/audioframe/unique_id/) | Gets unique shape identifier in presentation scope.<br/>            Read-only :py:class:`int`.<br/>            See also :py:attr:`aspose.slides.Shape.office_interop_shape_id` for getting unique shape identifier in slide scope. |
| [office_interop_shape_id](/slides/python-net/aspose.slides/audioframe/office_interop_shape_id/) | Gets unique shape identifier in slide scope.<br/>            Read-only :py:class:`int`.<br/>            See also :py:attr:`aspose.slides.Shape.unique_id` for getting unique shape identifier in presentation scope. |
| [alternative_text](/slides/python-net/aspose.slides/audioframe/alternative_text/) | Returns or sets the alternative text associated with a shape.<br/>            Read/write :py:class:`System.String`. |
| [alternative_text_title](/slides/python-net/aspose.slides/audioframe/alternative_text_title/) | Returns or sets the title of alternative text associated with a shape.<br/>            Read/write :py:class:`System.String`. |
| [name](/slides/python-net/aspose.slides/audioframe/name/) | Returns or sets the name of a shape.<br/>            Must be not null. Use empty string value if needed.<br/>            Read/write :py:class:`System.String`. |
| [is_decorative](/slides/python-net/aspose.slides/audioframe/is_decorative/) | Gets or sets 'Mark as decorative' option<br/>            Reed/write :py:class:`bool`. |
| [shape_lock](/slides/python-net/aspose.slides/audioframe/shape_lock/) | Returns shape's locks.<br/>            Read-only :py:class:`aspose.slides.IPictureFrameLock`. |
| [is_grouped](/slides/python-net/aspose.slides/audioframe/is_grouped/) | Determines whether the shape is grouped.<br/>            Read-only :py:class:`bool`. |
| [parent_group](/slides/python-net/aspose.slides/audioframe/parent_group/) | Returns parent GroupShape object if shape is grouped. Otherwise returns null.<br/>            Read-only :py:class:`aspose.slides.IGroupShape`. |
| [slide](/slides/python-net/aspose.slides/audioframe/slide/) | Returns the parent slide of a shape.<br/>            Read-only :py:class:`aspose.slides.IBaseSlide`. |
| [presentation](/slides/python-net/aspose.slides/audioframe/presentation/) | Returns the parent presentation of a slide.<br/>            Read-only :py:class:`aspose.slides.IPresentation`. |
| [shape_style](/slides/python-net/aspose.slides/audioframe/shape_style/) | Returns shape's style object.<br/>            Read-only :py:class:`aspose.slides.IShapeStyle`. |
| [shape_type](/slides/python-net/aspose.slides/audioframe/shape_type/) | Returns or sets the AutoShape type for a PictureFrame.<br/>            There are allowable all items of the set :py:enum:`aspose.slides.ShapeType`, <br/>            except all sorts of lines:<br/><br/>    ShapeType.Line,<br/><br/>    ShapeType.StraightConnector1,<br/><br/>    ShapeType.BentConnector2,<br/><br/>    ShapeType.BentConnector3,<br/><br/>    ShapeType.BentConnector4,<br/><br/>    ShapeType.BentConnector5,<br/><br/>    ShapeType.CurvedConnector2,<br/><br/>    ShapeType.CurvedConnector3,<br/><br/>    ShapeType.CurvedConnector4,<br/><br/>    ShapeType.CurvedConnector5.<br/><br/>            Read/write :py:enum:`aspose.slides.ShapeType`. |
| [adjustments](/slides/python-net/aspose.slides/audioframe/adjustments/) | Returns a collection of shape's adjustment values.<br/>            Read-only :py:class:`aspose.slides.IAdjustValueCollection`. |
| [picture_frame_lock](/slides/python-net/aspose.slides/audioframe/picture_frame_lock/) | Returns shape's locks.<br/>            Read-only :py:class:`aspose.slides.IPictureFrameLock`. |
| [picture_format](/slides/python-net/aspose.slides/audioframe/picture_format/) | Returns the PictureFillFormat object for a picture frame.<br/>            Read-only :py:class:`aspose.slides.IPictureFillFormat`. |
| [relative_scale_height](/slides/python-net/aspose.slides/audioframe/relative_scale_height/) | Returns or sets the scale of height(relative to original picture size) of the picture frame. Value 1.0 corresponds to 100%.<br/>            Read/write :py:class:`float`. |
| [relative_scale_width](/slides/python-net/aspose.slides/audioframe/relative_scale_width/) | Returns or sets the scale of width (relative to original picture size) of the picture frame. Value 1.0 corresponds to 100%.<br/>            Read/write :py:class:`float`. |
| [audio_cd_start_track](/slides/python-net/aspose.slides/audioframe/audio_cd_start_track/) | Returns or sets a start track index.<br/>            Read/write :py:class:`int`. |
| [audio_cd_start_track_time](/slides/python-net/aspose.slides/audioframe/audio_cd_start_track_time/) | Returns or sets a start track time.<br/>            Read/write :py:class:`int`. |
| [audio_cd_end_track](/slides/python-net/aspose.slides/audioframe/audio_cd_end_track/) | Returns or sets a last track index<br/>            Read/write :py:class:`int`. |
| [audio_cd_end_track_time](/slides/python-net/aspose.slides/audioframe/audio_cd_end_track_time/) | Returns or sets a last track time.<br/>            Read/write :py:class:`int`. |
| [volume](/slides/python-net/aspose.slides/audioframe/volume/) | Returns or sets the audio volume.<br/>            Read/write :py:enum:`aspose.slides.AudioVolumeMode`. |
| [play_mode](/slides/python-net/aspose.slides/audioframe/play_mode/) | Returns or sets the audio play mode.<br/>            Read/write :py:enum:`aspose.slides.AudioPlayModePreset`. |
| [hide_at_showing](/slides/python-net/aspose.slides/audioframe/hide_at_showing/) | Determines whether an AudioFrame is hidden.<br/>            Read/write :py:class:`bool`. |
| [play_loop_mode](/slides/python-net/aspose.slides/audioframe/play_loop_mode/) | Determines whether an audio is looped.<br/>            Read/write :py:class:`bool`. |
| [play_across_slides](/slides/python-net/aspose.slides/audioframe/play_across_slides/) | Determines whether audio is playing across the slides.<br/>             Read/write :py:class:`bool`. |
| [rewind_audio](/slides/python-net/aspose.slides/audioframe/rewind_audio/) | Determines whether audio is automatically rewinded to start after playing. <br/>             Read/write :py:class:`bool`. |
| [embedded](/slides/python-net/aspose.slides/audioframe/embedded/) | Determines whether a sound is embedded to a presentation.<br/>            Read-only :py:class:`bool`. |
| [link_path_long](/slides/python-net/aspose.slides/audioframe/link_path_long/) | Returns or sets the name of an audio file which is linked to an AudioFrame.<br/>            Read/write :py:class:`System.String`. |
| [embedded_audio](/slides/python-net/aspose.slides/audioframe/embedded_audio/) | Returns or sets embedded audio object.<br/>            Read/write :py:class:`aspose.slides.IAudio`. |
| [as_i_hyperlink_container](/slides/python-net/aspose.slides/audioframe/as_i_hyperlink_container/) |  |
| [as_i_slide_component](/slides/python-net/aspose.slides/audioframe/as_i_slide_component/) |  |
| [as_i_presentation_component](/slides/python-net/aspose.slides/audioframe/as_i_presentation_component/) |  |
| [as_i_shape](/slides/python-net/aspose.slides/audioframe/as_i_shape/) |  |
| [as_i_geometry_shape](/slides/python-net/aspose.slides/audioframe/as_i_geometry_shape/) |  |
| [as_i_picture_frame](/slides/python-net/aspose.slides/audioframe/as_i_picture_frame/) |  |

## Methods

| Method | Description |
| :- | :- |
| [get_thumbnail](/slides/python-net/aspose.slides/audioframe/audioframe/#/) | Returns shape thumbnail.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [get_thumbnail](/slides/python-net/aspose.slides/audioframe/audioframe/#ShapeThumbnailBounds-float-float/) | Returns shape thumbnail. |
| [write_as_svg](/slides/python-net/aspose.slides/audioframe/audioframe/#System.IO.Stream/) | Saves content of Shape as SVG file. |
| [write_as_svg](/slides/python-net/aspose.slides/audioframe/audioframe/#System.IO.Stream-aspose.slides.export.ISVGOptions/) | Saves content of Shape as SVG file. |
| [remove_placeholder](/slides/python-net/aspose.slides/audioframe/audioframe/#/) | Defines that this shape isn't a placeholder. |
| [add_placeholder](/slides/python-net/aspose.slides/audioframe/audioframe/#IPlaceholder/) | Adds a new placeholder if there is no and sets placeholder properties to a specified one. |
| [get_base_placeholder](/slides/python-net/aspose.slides/audioframe/audioframe/#/) | Returns a basic placeholder shape (shape from the layout and/or master slide that the current shape is inherited from). |
| [get_geometry_paths](/slides/python-net/aspose.slides/audioframe/audioframe/#/) | Returns the copy of path of the geometry shape. Coordinates are relative to the left top corner of the shape. |
| [set_geometry_path](/slides/python-net/aspose.slides/audioframe/audioframe/#IGeometryPath/) | Updates shape geometry from :py:class:`aspose.slides.IGeometryPath` object. Coordinates must be relative to the left<br/>             top corner of the shape.<br/>             Changes the type of the shape (:py:attr:`aspose.slides.GeometryShape.shape_type`) to :py:attr:`aspose.slides.ShapeType.CUSTOM`. |
| [set_geometry_paths](/slides/python-net/aspose.slides/audioframe/audioframe/#List[IGeometryPath]/) | Updates shape geometry from array of :py:class:`aspose.slides.IGeometryPath`. Coordinates must be relative to the left<br/>             top corner of the shape.<br/>             Changes the type of the shape (:py:attr:`aspose.slides.GeometryShape.shape_type`) to :py:attr:`aspose.slides.ShapeType.CUSTOM`. |
| [create_shape_elements](/slides/python-net/aspose.slides/audioframe/audioframe/#/) | Creates and returns array of shape's elements. |

