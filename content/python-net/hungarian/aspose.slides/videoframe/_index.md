---
title: VideoFrame class
second_title: Aspose.Slides a Pythonhoz .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/videoframe/
---
## VideoFrame osztály

Represents a video clip on a slide.

**Inheritance:**[`VideoFrame`](/slides/python-net/hu/aspose.slides/videoframe) → [`PictureFrame`](/slides/python-net/hu/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/hu/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/hu/aspose.slides/shape)

The VideoFrame type exposes the following members:

## Tulajdonságok

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/hu/aspose.slides/videoframe/is_text_holder/) | Determines whether the shape is TextHolder_PPT.<br/>            Csak olvasható **bool**. |
| [`placeholder`](/slides/python-net/hu/aspose.slides/videoframe/placeholder/) | Returns the placeholder for a shape. Returns None if the shape has no placeholder.<br/>            Csak olvasható [`IPlaceholder`](/slides/python-net/hu/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/hu/aspose.slides/videoframe/custom_data/) | Returns the shape's custom data.<br/>            Csak olvasható [`ICustomData`](/slides/python-net/hu/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/hu/aspose.slides/videoframe/raw_frame/) | Returns or sets the raw shape frame's properties.<br/>            Olvasás/írás [`IShapeFrame`](/slides/python-net/hu/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/hu/aspose.slides/videoframe/frame/) | Returns or sets the shape frame's properties.<br/>            Olvasás/írás [`IShapeFrame`](/slides/python-net/hu/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/hu/aspose.slides/videoframe/line_format/) | Returns the LineFormat object that contains line formatting properties for a shape.<br/>            Note: can return None for certain types of shapes which don't have line properties.<br/>            Csak olvasható [`ILineFormat`](/slides/python-net/hu/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/hu/aspose.slides/videoframe/three_d_format/) | Returns the ThreeDFormat object that 3d effect properties for a shape.<br/>            Note: can return None for certain types of shapes which don't have 3d properties.<br/>            Csak olvasható [`IThreeDFormat`](/slides/python-net/hu/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/hu/aspose.slides/videoframe/effect_format/) | Returns the EffectFormat object which contains pixel effects applied to a shape.<br/>            Note: can return None for certain types of shapes which don't have effect properties.<br/>            Csak olvasható [`IEffectFormat`](/slides/python-net/hu/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/hu/aspose.slides/videoframe/fill_format/) | Returns the FillFormat object that contains fill formatting properties for a shape.<br/>            Note: can return None for certain types of shapes which don't have fill properties.<br/>            Csak olvasható [`IFillFormat`](/slides/python-net/hu/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/hu/aspose.slides/videoframe/hyperlink_click/) | Returns or sets the hyperlink defined for mouse click.<br/>            Olvasás/írás [`IHyperlink`](/slides/python-net/hu/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/hu/aspose.slides/videoframe/hyperlink_mouse_over/) | Returns or sets the hyperlink defined for mouse over.<br/>            Olvasás/írás [`IHyperlink`](/slides/python-net/hu/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/hu/aspose.slides/videoframe/hyperlink_manager/) | Returns the hyperlink manager.<br/>            Csak olvasható [`IHyperlinkManager`](/slides/python-net/hu/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/hu/aspose.slides/videoframe/hidden/) | Determines whether the shape is hidden.<br/>            Olvasás/írás **bool**. |
| [`z_order_position`](/slides/python-net/hu/aspose.slides/videoframe/z_order_position/) | Returns the position of a shape in the z-order.<br/>            Shapes[0] returns the shape at the back of the z-order,<br/>            and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order.<br/>            Csak olvasható **int**. |
| [`connection_site_count`](/slides/python-net/hu/aspose.slides/videoframe/connection_site_count/) | Returns the number of connection sites on the shape.<br/>            Csak olvasható **int**. |
| [`rotation`](/slides/python-net/hu/aspose.slides/videoframe/rotation/) | Returns or sets the number of degrees the specified shape is rotated around<br/>            the z-axis. A positive value indicates clockwise rotation; a negative value<br/>            indicates counterclockwise rotation.<br/>            Olvasás/írás **float**. |
| [`x`](/slides/python-net/hu/aspose.slides/videoframe/x/) | Gets or sets the x-coordinate of the shape's upper-left corner, measured in points.<br/>            Olvasás/írás **float**. |
| [`y`](/slides/python-net/hu/aspose.slides/videoframe/y/) | Gets or sets the y-coordinate of the shape's upper-left corner, measured in points.<br/>            Olvasás/írás **float**. |
| [`width`](/slides/python-net/hu/aspose.slides/videoframe/width/) | Gets or sets the width of the shape, measured in points.<br/>            Olvasás/írás **float**. |
| [`height`](/slides/python-net/hu/aspose.slides/videoframe/height/) | Gets or sets the height of the shape, measured in points.<br/>            Olvasás/írás **float**. |
| [`black_white_mode`](/slides/python-net/hu/aspose.slides/videoframe/black_white_mode/) | Property specifies how a shape will render in black-and-white display mode..<br/>            Olvasás/írás [`BlackWhiteMode`](/slides/python-net/hu/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/hu/aspose.slides/videoframe/unique_id/) | Returns an internal, presentation-scoped identifier intended for use by add-ins or other code.<br/>            Because this value can be reassigned by the user or programmatically, it must not be treated<br/>            as a persistent unique key.<br/>            Csak olvasható **int**.<br/>            Lásd még [`Shape.office_interop_shape_id`](/slides/python-net/hu/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/hu/aspose.slides/videoframe/office_interop_shape_id/) | Returns a slide-scoped unique identifier that remains constant for the lifetime of the shape and<br/>            lets PowerPoint or interop code reliably reference the shape from anywhere in the document.<br/>            Csak olvasható **int**.<br/>            Lásd még [`Shape.unique_id`](/slides/python-net/hu/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/hu/aspose.slides/videoframe/alternative_text/) | Returns or sets the alternative text associated with a shape.<br/>            Olvasás/írás **str**. |
| [`alternative_text_title`](/slides/python-net/hu/aspose.slides/videoframe/alternative_text_title/) | Returns or sets the title of alternative text associated with a shape.<br/>            Olvasás/írás **str**. |
| [`name`](/slides/python-net/hu/aspose.slides/videoframe/name/) | Returns or sets the name of a shape.<br/>            Must be not None. Use empty string value if needed.<br/>            Olvasás/írás **str**. |
| [`is_decorative`](/slides/python-net/hu/aspose.slides/videoframe/is_decorative/) | Gets or sets 'Mark as decorative' option<br/>            Olvasás/írás **bool**. |
| [`shape_lock`](/slides/python-net/hu/aspose.slides/videoframe/shape_lock/) | Returns shape's locks.<br/>            Csak olvasható [`IPictureFrameLock`](/slides/python-net/hu/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/hu/aspose.slides/videoframe/is_grouped/) | Determines whether the shape is grouped.<br/>            Csak olvasható **bool**. |
| [`parent_group`](/slides/python-net/hu/aspose.slides/videoframe/parent_group/) | Returns parent GroupShape object if shape is grouped. Otherwise returns None.<br/>            Csak olvasható [`IGroupShape`](/slides/python-net/hu/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/hu/aspose.slides/videoframe/slide/) | Returns the parent slide of a shape.<br/>            Csak olvasható [`IBaseSlide`](/slides/python-net/hu/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/hu/aspose.slides/videoframe/presentation/) | Returns the parent presentation of a slide.<br/>            Csak olvasható [`IPresentation`](/slides/python-net/hu/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/hu/aspose.slides/videoframe/shape_style/) | Returns shape's style object.<br/>            Csak olvasható [`IShapeStyle`](/slides/python-net/hu/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/hu/aspose.slides/videoframe/shape_type/) | Returns or sets the AutoShape type for a PictureFrame.<br/>            There are allowable all items of the set [`ShapeType`](/slides/python-net/hu/aspose.slides/shapetype), <br/>            except all sorts of lines:<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            Olvasás/írás [`ShapeType`](/slides/python-net/hu/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/hu/aspose.slides/videoframe/adjustments/) | Returns a collection of shape's adjustment values.<br/>            Csak olvasható [`IAdjustValueCollection`](/slides/python-net/hu/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/hu/aspose.slides/videoframe/picture_frame_lock/) | Returns shape's locks.<br/>            Csak olvasható [`IPictureFrameLock`](/slides/python-net/hu/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/hu/aspose.slides/videoframe/picture_format/) | Returns the PictureFillFormat object for a picture frame.<br/>            Csak olvasható [`IPictureFillFormat`](/slides/python-net/hu/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/hu/aspose.slides/videoframe/relative_scale_height/) | Returns or sets the scale of height(relative to original picture size) of the picture frame. Value 1.0 corresponds to 100%.<br/>            Olvasás/írás **float**. |
| [`relative_scale_width`](/slides/python-net/hu/aspose.slides/videoframe/relative_scale_width/) | Returns or sets the scale of width (relative to original picture size) of the picture frame. Value 1.0 corresponds to 100%.<br/>            Olvasás/írás **float**. |
| [`is_cameo`](/slides/python-net/hu/aspose.slides/videoframe/is_cameo/) | Determines whether the PictureFrame is Cameo object or not.<br/>            Csak olvasható **bool**. |
| [`rewind_video`](/slides/python-net/hu/aspose.slides/videoframe/rewind_video/) | Determines whether a video is automatically rewinded to start<br/>            as soon as the movie has finished playing.<br/>            Olvasás/írás **bool**. |
| [`play_loop_mode`](/slides/python-net/hu/aspose.slides/videoframe/play_loop_mode/) | Determines whether a video is looped.<br/>            Olvasás/írás **bool**. |
| [`hide_at_showing`](/slides/python-net/hu/aspose.slides/videoframe/hide_at_showing/) | Determines whether a VideoFrame is hidden.<br/>            Olvasás/írás **bool**. |
| [`volume`](/slides/python-net/hu/aspose.slides/videoframe/volume/) | Returns or sets the audio volume.<br/>            Olvasás/írás [`AudioVolumeMode`](/slides/python-net/hu/aspose.slides/audiovolumemode). |
| [`volume_value`](/slides/python-net/hu/aspose.slides/videoframe/volume_value/) | Returns or sets the exact video volume as a percentage.<br/>             The value is expressed as a percentage from 0 to 100. Use this property<br/>             to read or set volume values that are more precise than the predefined<br/>             levels available through the [`VideoFrame.volume`](/slides/python-net/hu/aspose.slides/videoframe/volume) property.<br/>             Olvasás/írás **float**. |
| [`play_mode`](/slides/python-net/hu/aspose.slides/videoframe/play_mode/) | Returns or sets the video play mode.<br/>            Olvasás/írás [`VideoPlayModePreset`](/slides/python-net/hu/aspose.slides/videoplaymodepreset). |
| [`full_screen_mode`](/slides/python-net/hu/aspose.slides/videoframe/full_screen_mode/) | Determines whether a video is shown in full screen mode.<br/>            Olvasás/írás **bool**. |
| [`link_path_long`](/slides/python-net/hu/aspose.slides/videoframe/link_path_long/) | Returns or sets the name of an video file which is linked to a VideoFrame.<br/>            Olvasás/írás **str**. |
| [`embedded_video`](/slides/python-net/hu/aspose.slides/videoframe/embedded_video/) | Returns or sets embedded video object.<br/>            Olvasás/írás [`IVideo`](/slides/python-net/hu/aspose.slides/ivideo). |
| [`trim_from_start`](/slides/python-net/hu/aspose.slides/videoframe/trim_from_start/) | Vágás kezdete [ms] |
| [`trim_from_end`](/slides/python-net/hu/aspose.slides/videoframe/trim_from_end/) | Vágás vége [ms] |
| [`caption_tracks`](/slides/python-net/hu/aspose.slides/videoframe/caption_tracks/) | Gets the collection of closed captions associated with the video frame.<br/>             This property is read-only and returns an [`ICaptionsCollection`](/slides/python-net/hu/aspose.slides/icaptionscollection) containing all caption tracks. |

## Metódusok

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/hu/aspose.slides/videoframe/get_image/#) | Returns shape thumbnail.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/hu/aspose.slides/videoframe/get_image/#shapethumbnailbounds-float-float) | Returns shape thumbnail. |
| [`write_as_svg(self, stream)`](/slides/python-net/hu/aspose.slides/videoframe/write_as_svg/#iorawiobase) | Saves content of Shape as SVG file. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/hu/aspose.slides/videoframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Saves content of Shape as SVG file. |
| [`remove_placeholder(self)`](/slides/python-net/hu/aspose.slides/videoframe/remove_placeholder/#) | Defines that this shape isn't a placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/hu/aspose.slides/videoframe/add_placeholder/#iplaceholder) | Adds a new placeholder if there is no and sets placeholder properties to a specified one. |
| [`get_base_placeholder(self)`](/slides/python-net/hu/aspose.slides/videoframe/get_base_placeholder/#) | Returns a basic placeholder shape (shape from the layout and/or master slide that the current shape is inherited from).<br/>            A None is returned if the current shape is not inherited. |
| [`get_visual_bounds(self)`](/slides/python-net/hu/aspose.slides/videoframe/get_visual_bounds/#) | Gets the visual bounds of the shape calculated from its rendered content. |
| [`get_geometry_paths(self)`](/slides/python-net/hu/aspose.slides/videoframe/get_geometry_paths/#) | Returns the copy of path of the geometry shape. Coordinates are relative to the left top corner of the shape. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/hu/aspose.slides/videoframe/set_geometry_path/#igeometrypath) | Updates shape geometry from [`IGeometryPath`](/slides/python-net/hu/aspose.slides/igeometrypath) object. Coordinates must be relative to the left<br/>             top corner of the shape.<br/>             Changes the type of the shape ([`GeometryShape.shape_type`](/slides/python-net/hu/aspose.slides/geometryshape/shape_type)) to [`ShapeType.CUSTOM`](/slides/python-net/hu/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/hu/aspose.slides/videoframe/set_geometry_paths/#listigeometrypath) | Updates shape geometry from array of [`IGeometryPath`](/slides/python-net/hu/aspose.slides/igeometrypath). Coordinates must be relative to the left<br/>             top corner of the shape.<br/>             Changes the type of the shape ([`GeometryShape.shape_type`](/slides/python-net/hu/aspose.slides/geometryshape/shape_type)) to [`ShapeType.CUSTOM`](/slides/python-net/hu/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/hu/aspose.slides/videoframe/create_shape_elements/#) | Creates and returns array of shape's elements. |

### Lásd még
* osztály [`GeometryShape`](/slides/python-net/hu/aspose.slides/geometryshape)
* osztály [`PictureFrame`](/slides/python-net/hu/aspose.slides/pictureframe)
* osztály [`Shape`](/slides/python-net/hu/aspose.slides/shape)
* osztály [`VideoFrame`](/slides/python-net/hu/aspose.slides/videoframe)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)