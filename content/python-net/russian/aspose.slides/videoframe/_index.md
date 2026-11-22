---
title: VideoFrame class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/videoframe/
---
## VideoFrame класс

Represents a video clip on a slide.

**Inheritance:**[`VideoFrame`](/slides/python-net/ru/aspose.slides/videoframe) → [`PictureFrame`](/slides/python-net/ru/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/ru/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/ru/aspose.slides/shape)

The VideoFrame type exposes the following members:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ru/aspose.slides/videoframe/is_text_holder/) | Determines whether the shape is TextHolder_PPT.<br/>            Read-only **bool**. |
| [`placeholder`](/slides/python-net/ru/aspose.slides/videoframe/placeholder/) | Returns the placeholder for a shape. Returns None if the shape has no placeholder.<br/>            Read-only [`IPlaceholder`](/slides/python-net/ru/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ru/aspose.slides/videoframe/custom_data/) | Returns the shape's custom data.<br/>            Read-only [`ICustomData`](/slides/python-net/ru/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ru/aspose.slides/videoframe/raw_frame/) | Returns or sets the raw shape frame's properties.<br/>            Read/write [`IShapeFrame`](/slides/python-net/ru/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ru/aspose.slides/videoframe/frame/) | Returns or sets the shape frame's properties.<br/>            Read/write [`IShapeFrame`](/slides/python-net/ru/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ru/aspose.slides/videoframe/line_format/) | Returns the LineFormat object that contains line formatting properties for a shape.<br/>            Note: can return None for certain types of shapes which don't have line properties.<br/>            Read-only [`ILineFormat`](/slides/python-net/ru/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ru/aspose.slides/videoframe/three_d_format/) | Returns the ThreeDFormat object that 3d effect properties for a shape.<br/>            Note: can return None for certain types of shapes which don't have 3d properties.<br/>            Read-only [`IThreeDFormat`](/slides/python-net/ru/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ru/aspose.slides/videoframe/effect_format/) | Returns the EffectFormat object which contains pixel effects applied to a shape.<br/>            Note: can return None for certain types of shapes which don't have effect properties.<br/>            Read-only [`IEffectFormat`](/slides/python-net/ru/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ru/aspose.slides/videoframe/fill_format/) | Returns the FillFormat object that contains fill formatting properties for a shape.<br/>            Note: can return None for certain types of shapes which don't have fill properties.<br/>            Read-only [`IFillFormat`](/slides/python-net/ru/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ru/aspose.slides/videoframe/hyperlink_click/) | Returns or sets the hyperlink defined for mouse click.<br/>            Read/write [`IHyperlink`](/slides/python-net/ru/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ru/aspose.slides/videoframe/hyperlink_mouse_over/) | Returns or sets the hyperlink defined for mouse over.<br/>            Read/write [`IHyperlink`](/slides/python-net/ru/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ru/aspose.slides/videoframe/hyperlink_manager/) | Returns the hyperlink manager.<br/>            Read-only [`IHyperlinkManager`](/slides/python-net/ru/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ru/aspose.slides/videoframe/hidden/) | Determines whether the shape is hidden.<br/>            Read/write **bool**. |
| [`z_order_position`](/slides/python-net/ru/aspose.slides/videoframe/z_order_position/) | Returns the position of a shape in the z-order.<br/>            Shapes[0] returns the shape at the back of the z-order,<br/>            and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order.<br/>            Read-only **int**. |
| [`connection_site_count`](/slides/python-net/ru/aspose.slides/videoframe/connection_site_count/) | Returns the number of connection sites on the shape.<br/>            Read-only **int**. |
| [`rotation`](/slides/python-net/ru/aspose.slides/videoframe/rotation/) | Returns or sets the number of degrees the specified shape is rotated around<br/>            the z-axis. A positive value indicates clockwise rotation; a negative value<br/>            indicates counterclockwise rotation.<br/>            Read/write **float**. |
| [`x`](/slides/python-net/ru/aspose.slides/videoframe/x/) | Gets or sets the x-coordinate of the shape's upper-left corner, measured in points.<br/>            Read/write **float**. |
| [`y`](/slides/python-net/ru/aspose.slides/videoframe/y/) | Gets or sets the y-coordinate of the shape's upper-left corner, measured in points.<br/>            Read/write **float**. |
| [`width`](/slides/python-net/ru/aspose.slides/videoframe/width/) | Gets or sets the width of the shape, measured in points.<br/>            Read/write **float**. |
| [`height`](/slides/python-net/ru/aspose.slides/videoframe/height/) | Gets or sets the height of the shape, measured in points.<br/>            Read/write **float**. |
| [`black_white_mode`](/slides/python-net/ru/aspose.slides/videoframe/black_white_mode/) | Property specifies how a shape will render in black-and-white display mode..<br/>            Read/write [`BlackWhiteMode`](/slides/python-net/ru/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ru/aspose.slides/videoframe/unique_id/) | Returns an internal, presentation-scoped identifier intended for use by add-ins or other code.<br/>            Because this value can be reassigned by the user or programmatically, it must not be treated<br/>            as a persistent unique key.<br/>            Read-only **int**.<br/>            See also [`Shape.office_interop_shape_id`](/slides/python-net/ru/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/ru/aspose.slides/videoframe/office_interop_shape_id/) | Returns a slide-scoped unique identifier that remains constant for the lifetime of the shape and<br/>            lets PowerPoint or interop code reliably reference the shape from anywhere in the document.<br/>            Read-only **int**.<br/>            See also [`Shape.unique_id`](/slides/python-net/ru/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/ru/aspose.slides/videoframe/alternative_text/) | Returns or sets the alternative text associated with a shape.<br/>            Read/write **str**. |
| [`alternative_text_title`](/slides/python-net/ru/aspose.slides/videoframe/alternative_text_title/) | Returns or sets the title of alternative text associated with a shape.<br/>            Read/write **str**. |
| [`name`](/slides/python-net/ru/aspose.slides/videoframe/name/) | Returns or sets the name of a shape.<br/>            Must be not None. Use empty string value if needed.<br/>            Read/write **str**. |
| [`is_decorative`](/slides/python-net/ru/aspose.slides/videoframe/is_decorative/) | Gets or sets 'Mark as decorative' option<br/>            Reed/write **bool**. |
| [`shape_lock`](/slides/python-net/ru/aspose.slides/videoframe/shape_lock/) | Returns shape's locks.<br/>            Read-only [`IPictureFrameLock`](/slides/python-net/ru/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/ru/aspose.slides/videoframe/is_grouped/) | Determines whether the shape is grouped.<br/>            Read-only **bool**. |
| [`parent_group`](/slides/python-net/ru/aspose.slides/videoframe/parent_group/) | Returns parent GroupShape object if shape is grouped. Otherwise returns None.<br/>            Read-only [`IGroupShape`](/slides/python-net/ru/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ru/aspose.slides/videoframe/slide/) | Returns the parent slide of a shape.<br/>            Read-only [`IBaseSlide`](/slides/python-net/ru/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ru/aspose.slides/videoframe/presentation/) | Returns the parent presentation of a slide.<br/>            Read-only [`IPresentation`](/slides/python-net/ru/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/ru/aspose.slides/videoframe/shape_style/) | Returns shape's style object.<br/>            Read-only [`IShapeStyle`](/slides/python-net/ru/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/ru/aspose.slides/videoframe/shape_type/) | Returns or sets the AutoShape type for a PictureFrame.<br/>            There are allowable all items of the set [`ShapeType`](/slides/python-net/ru/aspose.slides/shapetype), <br/>            except all sorts of lines:<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            Read/write [`ShapeType`](/slides/python-net/ru/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/ru/aspose.slides/videoframe/adjustments/) | Returns a collection of shape's adjustment values.<br/>            Read-only [`IAdjustValueCollection`](/slides/python-net/ru/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/ru/aspose.slides/videoframe/picture_frame_lock/) | Returns shape's locks.<br/>            Read-only [`IPictureFrameLock`](/slides/python-net/ru/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/ru/aspose.slides/videoframe/picture_format/) | Returns the PictureFillFormat object for a picture frame.<br/>            Read-only [`IPictureFillFormat`](/slides/python-net/ru/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/ru/aspose.slides/videoframe/relative_scale_height/) | Returns or sets the scale of height(relative to original picture size) of the picture frame. Value 1.0 corresponds to 100%.<br/>            Read/write **float**. |
| [`relative_scale_width`](/slides/python-net/ru/aspose.slides/videoframe/relative_scale_width/) | Returns or sets the scale of width (relative to original picture size) of the picture frame. Value 1.0 corresponds to 100%.<br/>            Read/write **float**. |
| [`is_cameo`](/slides/python-net/ru/aspose.slides/videoframe/is_cameo/) | Determines whether the PictureFrame is Cameo object or not.<br/>            Read only **bool**. |
| [`rewind_video`](/slides/python-net/ru/aspose.slides/videoframe/rewind_video/) | Determines whether a video is automatically rewinded to start<br/>            as soon as the movie has finished playing.<br/>            Read/write **bool**. |
| [`play_loop_mode`](/slides/python-net/ru/aspose.slides/videoframe/play_loop_mode/) | Determines whether a video is looped.<br/>            Read/write **bool**. |
| [`hide_at_showing`](/slides/python-net/ru/aspose.slides/videoframe/hide_at_showing/) | Determines whether a VideoFrame is hidden.<br/>            Read/write **bool**. |
| [`volume`](/slides/python-net/ru/aspose.slides/videoframe/volume/) | Returns or sets the audio volume.<br/>            Read/write [`AudioVolumeMode`](/slides/python-net/ru/aspose.slides/audiovolumemode). |
| [`volume_value`](/slides/python-net/ru/aspose.slides/videoframe/volume_value/) | Returns or sets the exact video volume as a percentage.<br/>             The value is expressed as a percentage from 0 to 100. Use this property<br/>             to read or set volume values that are more precise than the predefined<br/>             levels available through the [`VideoFrame.volume`](/slides/python-net/ru/aspose.slides/videoframe/volume) property.<br/>             Read/write **float**. |
| [`play_mode`](/slides/python-net/ru/aspose.slides/videoframe/play_mode/) | Returns or sets the video play mode.<br/>            Read/write [`VideoPlayModePreset`](/slides/python-net/ru/aspose.slides/videoplaymodepreset). |
| [`full_screen_mode`](/slides/python-net/ru/aspose.slides/videoframe/full_screen_mode/) | Determines whether a video is shown in full screen mode.<br/>            Read/write **bool**. |
| [`link_path_long`](/slides/python-net/ru/aspose.slides/videoframe/link_path_long/) | Returns or sets the name of an video file which is linked to a VideoFrame.<br/>            Read/write **str**. |
| [`embedded_video`](/slides/python-net/ru/aspose.slides/videoframe/embedded_video/) | Returns or sets embedded video object.<br/>            Read/write [`IVideo`](/slides/python-net/ru/aspose.slides/ivideo). |
| [`trim_from_start`](/slides/python-net/ru/aspose.slides/videoframe/trim_from_start/) | Trim start [ms] |
| [`trim_from_end`](/slides/python-net/ru/aspose.slides/videoframe/trim_from_end/) | Trim end [ms] |
| [`caption_tracks`](/slides/python-net/ru/aspose.slides/videoframe/caption_tracks/) | Gets the collection of closed captions associated with the video frame.<br/>             This property is read-only and returns an [`ICaptionsCollection`](/slides/python-net/ru/aspose.slides/icaptionscollection) containing all caption tracks. |

## Методы

| Метод | Описание |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ru/aspose.slides/videoframe/get_image/#) | Returns shape thumbnail.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ru/aspose.slides/videoframe/get_image/#shapethumbnailbounds-float-float) | Returns shape thumbnail. |
| [`write_as_svg(self, stream)`](/slides/python-net/ru/aspose.slides/videoframe/write_as_svg/#iorawiobase) | Saves content of Shape as SVG file. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ru/aspose.slides/videoframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Saves content of Shape as SVG file. |
| [`remove_placeholder(self)`](/slides/python-net/ru/aspose.slides/videoframe/remove_placeholder/#) | Defines that this shape isn't a placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ru/aspose.slides/videoframe/add_placeholder/#iplaceholder) | Adds a new placeholder if there is no and sets placeholder properties to a specified one. |
| [`get_base_placeholder(self)`](/slides/python-net/ru/aspose.slides/videoframe/get_base_placeholder/#) | Returns a basic placeholder shape (shape from the layout and/or master slide that the current shape is inherited from).<br/>            A None is returned if the current shape is not inherited. |
| [`get_visual_bounds(self)`](/slides/python-net/ru/aspose.slides/videoframe/get_visual_bounds/#) | Gets the visual bounds of the shape calculated from its rendered content. |
| [`get_geometry_paths(self)`](/slides/python-net/ru/aspose.slides/videoframe/get_geometry_paths/#) | Returns the copy of path of the geometry shape. Coordinates are relative to the left top corner of the shape. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/ru/aspose.slides/videoframe/set_geometry_path/#igeometrypath) | Updates shape geometry from [`IGeometryPath`](/slides/python-net/ru/aspose.slides/igeometrypath) object. Coordinates must be relative to the left<br/>             top corner of the shape.<br/>             Changes the type of the shape ([`GeometryShape.shape_type`](/slides/python-net/ru/aspose.slides/geometryshape/shape_type)) to [`ShapeType.CUSTOM`](/slides/python-net/ru/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/ru/aspose.slides/videoframe/set_geometry_paths/#listigeometrypath) | Updates shape geometry from array of [`IGeometryPath`](/slides/python-net/ru/aspose.slides/igeometrypath). Coordinates must be relative to the left<br/>             top corner of the shape.<br/>             Changes the type of the shape ([`GeometryShape.shape_type`](/slides/python-net/ru/aspose.slides/geometryshape/shape_type)) to [`ShapeType.CUSTOM`](/slides/python-net/ru/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/ru/aspose.slides/videoframe/create_shape_elements/#) | Creates and returns array of shape's elements. |

### См. также
* класс [`GeometryShape`](/slides/python-net/ru/aspose.slides/geometryshape)
* класс [`PictureFrame`](/slides/python-net/ru/aspose.slides/pictureframe)
* класс [`Shape`](/slides/python-net/ru/aspose.slides/shape)
* класс [`VideoFrame`](/slides/python-net/ru/aspose.slides/videoframe)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)