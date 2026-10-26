---
title: AutoShape class
second_title: Aspose.Slides Python के लिए .NET के माध्यम से API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/autoshape/
---
## AutoShape क्लास

Represents an AutoShape.

**Inheritance:**[`AutoShape`](/slides/python-net/hi/aspose.slides/autoshape) → [`GeometryShape`](/slides/python-net/hi/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/hi/aspose.slides/shape)

The AutoShape type exposes the following members:

## गुण

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/hi/aspose.slides/autoshape/is_text_holder/) | Determines whether the shape is TextHolder_PPT.<br/>            केवल-पढ़ने योग्य **bool**। |
| [`placeholder`](/slides/python-net/hi/aspose.slides/autoshape/placeholder/) | Returns the placeholder for a shape. Returns None if the shape has no placeholder.<br/>            केवल-पढ़ने योग्य [`IPlaceholder`](/slides/python-net/hi/aspose.slides/iplaceholder)। |
| [`custom_data`](/slides/python-net/hi/aspose.slides/autoshape/custom_data/) | Returns the shape's custom data.<br/>            केवल-पढ़ने योग्य [`ICustomData`](/slides/python-net/hi/aspose.slides/icustomdata)। |
| [`raw_frame`](/slides/python-net/hi/aspose.slides/autoshape/raw_frame/) | Returns or sets the raw shape frame's properties.<br/>            पढ़ना/लिखना [`IShapeFrame`](/slides/python-net/hi/aspose.slides/ishapeframe)। |
| [`frame`](/slides/python-net/hi/aspose.slides/autoshape/frame/) | Returns or sets the shape frame's properties.<br/>            पढ़ना/लिखना [`IShapeFrame`](/slides/python-net/hi/aspose.slides/ishapeframe)। |
| [`line_format`](/slides/python-net/hi/aspose.slides/autoshape/line_format/) | Returns the LineFormat object that contains line formatting properties for a shape.<br/>            नोट: कुछ प्रकार की आकृतियों के लिए जो लाइन गुण नहीं रखतीं, None लौटाया जा सकता है।<br/>            केवल-पढ़ने योग्य [`ILineFormat`](/slides/python-net/hi/aspose.slides/ilineformat)। |
| [`three_d_format`](/slides/python-net/hi/aspose.slides/autoshape/three_d_format/) | Returns the ThreeDFormat object that 3d effect properties for a shape.<br/>            नोट: कुछ प्रकार की आकृतियों के लिए जो 3d गुण नहीं रखतीं, None लौटाया जा सकता है।<br/>            केवल-पढ़ने योग्य [`IThreeDFormat`](/slides/python-net/hi/aspose.slides/ithreedformat)। |
| [`effect_format`](/slides/python-net/hi/aspose.slides/autoshape/effect_format/) | Returns the EffectFormat object which contains pixel effects applied to a shape.<br/>            नोट: कुछ प्रकार की आकृतियों के लिए जो इफ़ेक्ट गुण नहीं रखतीं, None लौटाया जा सकता है।<br/>            केवल-पढ़ने योग्य [`IEffectFormat`](/slides/python-net/hi/aspose.slides/ieffectformat)। |
| [`fill_format`](/slides/python-net/hi/aspose.slides/autoshape/fill_format/) | Returns the FillFormat object that contains fill formatting properties for a shape.<br/>            नोट: कुछ प्रकार की आकृतियों के लिए जो फ़िल गुण नहीं रखतीं, None लौटाया जा सकता है।<br/>            केवल-पढ़ने योग्य [`IFillFormat`](/slides/python-net/hi/aspose.slides/ifillformat)। |
| [`hyperlink_click`](/slides/python-net/hi/aspose.slides/autoshape/hyperlink_click/) | Returns or sets the hyperlink defined for mouse click.<br/>            पढ़ना/लिखना [`IHyperlink`](/slides/python-net/hi/aspose.slides/ihyperlink)। |
| [`hyperlink_mouse_over`](/slides/python-net/hi/aspose.slides/autoshape/hyperlink_mouse_over/) | Returns or sets the hyperlink defined for mouse over.<br/>            पढ़ना/लिखना [`IHyperlink`](/slides/python-net/hi/aspose.slides/ihyperlink)। |
| [`hyperlink_manager`](/slides/python-net/hi/aspose.slides/autoshape/hyperlink_manager/) | Returns the hyperlink manager.<br/>            केवल-पढ़ने योग्य [`IHyperlinkManager`](/slides/python-net/hi/aspose.slides/ihyperlinkmanager)। |
| [`hidden`](/slides/python-net/hi/aspose.slides/autoshape/hidden/) | Determines whether the shape is hidden.<br/>            पढ़ना/लिखना **bool**। |
| [`z_order_position`](/slides/python-net/hi/aspose.slides/autoshape/z_order_position/) | Returns the position of a shape in the z-order.<br/>            Shapes[0] z-order के पीछे वाली आकृति लौटाता है,<br/>            और Shapes[Shapes.Count - 1] z-order के सामने वाली आकृति लौटाता है।<br/>            केवल-पढ़ने योग्य **int**। |
| [`connection_site_count`](/slides/python-net/hi/aspose.slides/autoshape/connection_site_count/) | Returns the number of connection sites on the shape.<br/>            केवल-पढ़ने योग्य **int**। |
| [`rotation`](/slides/python-net/hi/aspose.slides/autoshape/rotation/) | Returns or sets the number of degrees the specified shape is rotated around<br/>            the z-axis. A positive value indicates clockwise rotation; a negative value<br/>            indicates counterclockwise rotation.<br/>            पढ़ना/लिखना **float**। |
| [`x`](/slides/python-net/hi/aspose.slides/autoshape/x/) | Gets or sets the x-coordinate of the shape's upper-left corner, measured in points.<br/>            पढ़ना/लिखना **float**। |
| [`y`](/slides/python-net/hi/aspose.slides/autoshape/y/) | Gets or sets the y-coordinate of the shape's upper-left corner, measured in points.<br/>            पढ़ना/लिखना **float**। |
| [`width`](/slides/python-net/hi/aspose.slides/autoshape/width/) | Gets or sets the width of the shape, measured in points.<br/>            पढ़ना/लिखना **float**। |
| [`height`](/slides/python-net/hi/aspose.slides/autoshape/height/) | Gets or sets the height of the shape, measured in points.<br/>            पढ़ना/लिखना **float**। |
| [`black_white_mode`](/slides/python-net/hi/aspose.slides/autoshape/black_white_mode/) | Property specifies how a shape will render in black-and-white display mode..<br/>            पढ़ना/लिखना [`BlackWhiteMode`](/slides/python-net/hi/aspose.slides/blackwhitemode)। |
| [`unique_id`](/slides/python-net/hi/aspose.slides/autoshape/unique_id/) | Returns an internal, presentation-scoped identifier intended for use by add-ins or other code.<br/>            Because this value can be reassigned by the user or programmatically, it must not be treated<br/>            as a persistent unique key.<br/>            केवल-पढ़ने योग्य **int**।<br/>            See also [`Shape.office_interop_shape_id`](/slides/python-net/hi/aspose.slides/shape/office_interop_shape_id)। |
| [`office_interop_shape_id`](/slides/python-net/hi/aspose.slides/autoshape/office_interop_shape_id/) | Returns a slide-scoped unique identifier that remains constant for the lifetime of the shape and<br/>            lets PowerPoint or interop code reliably reference the shape from anywhere in the document.<br/>            केवल-पढ़ने योग्य **int**।<br/>            See also [`Shape.unique_id`](/slides/python-net/hi/aspose.slides/shape/unique_id)। |
| [`alternative_text`](/slides/python-net/hi/aspose.slides/autoshape/alternative_text/) | Returns or sets the alternative text associated with a shape.<br/>            पढ़ना/लिखना **str**। |
| [`alternative_text_title`](/slides/python-net/hi/aspose.slides/autoshape/alternative_text_title/) | Returns or sets the title of alternative text associated with a shape.<br/>            पढ़ना/लिखना **str**। |
| [`name`](/slides/python-net/hi/aspose.slides/autoshape/name/) | Returns or sets the name of a shape.<br/>            Must be not None. Use empty string value if needed.<br/>            पढ़ना/लिखना **str**। |
| [`is_decorative`](/slides/python-net/hi/aspose.slides/autoshape/is_decorative/) | Gets or sets 'Mark as decorative' option<br/>            पढ़ना/लिखना **bool**। |
| [`shape_lock`](/slides/python-net/hi/aspose.slides/autoshape/shape_lock/) | Returns shape's locks.<br/>            केवल-पढ़ने योग्य [`IAutoShapeLock`](/slides/python-net/hi/aspose.slides/iautoshapelock)। |
| [`is_grouped`](/slides/python-net/hi/aspose.slides/autoshape/is_grouped/) | Determines whether the shape is grouped.<br/>            केवल-पढ़ने योग्य **bool**। |
| [`parent_group`](/slides/python-net/hi/aspose.slides/autoshape/parent_group/) | Returns parent GroupShape object if shape is grouped. Otherwise returns None.<br/>            केवल-पढ़ने योग्य [`IGroupShape`](/slides/python-net/hi/aspose.slides/igroupshape)। |
| [`slide`](/slides/python-net/hi/aspose.slides/autoshape/slide/) | Returns the parent slide of a shape.<br/>            केवल-पढ़ने योग्य [`IBaseSlide`](/slides/python-net/hi/aspose.slides/ibaseslide)। |
| [`presentation`](/slides/python-net/hi/aspose.slides/autoshape/presentation/) | Returns the parent presentation of a slide.<br/>            केवल-पढ़ने योग्य [`IPresentation`](/slides/python-net/hi/aspose.slides/ipresentation)। |
| [`shape_style`](/slides/python-net/hi/aspose.slides/autoshape/shape_style/) | Returns shape's style object.<br/>            केवल-पढ़ने योग्य [`IShapeStyle`](/slides/python-net/hi/aspose.slides/ishapestyle)। |
| [`shape_type`](/slides/python-net/hi/aspose.slides/autoshape/shape_type/) | Returns or sets the geometry preset type.<br/>            नोट: मान बदलने पर सभी समायोजन मान उनके डिफ़ॉल्ट मानों पर रीसेट हो जाएंगे।<br/>            पढ़ना/लिखना [`ShapeType`](/slides/python-net/hi/aspose.slides/shapetype)। |
| [`adjustments`](/slides/python-net/hi/aspose.slides/autoshape/adjustments/) | Returns a collection of shape's adjustment values.<br/>            केवल-पढ़ने योग्य [`IAdjustValueCollection`](/slides/python-net/hi/aspose.slides/iadjustvaluecollection)। |
| [`auto_shape_lock`](/slides/python-net/hi/aspose.slides/autoshape/auto_shape_lock/) | Returns autoshape's locks.<br/>            केवल-पढ़ने योग्य [`IAutoShapeLock`](/slides/python-net/hi/aspose.slides/iautoshapelock)। |
| [`text_frame`](/slides/python-net/hi/aspose.slides/autoshape/text_frame/) | Returns TextFrame object for the AutoShape.<br/>            केवल-पढ़ने योग्य [`ITextFrame`](/slides/python-net/hi/aspose.slides/itextframe)। |
| [`use_background_fill`](/slides/python-net/hi/aspose.slides/autoshape/use_background_fill/) | Determines whether this autoshape should be filled with slide's background fill instead of specified by style or fill format.<br/>            पढ़ना/लिखना **bool**। |
| [`is_text_box`](/slides/python-net/hi/aspose.slides/autoshape/is_text_box/) | Specifies if the shape is a text box। |

## मेथड्स

| मेथड | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/hi/aspose.slides/autoshape/get_image/#) | Returns shape thumbnail.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default। |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/hi/aspose.slides/autoshape/get_image/#shapethumbnailbounds-float-float) | Returns shape thumbnail। |
| [`write_as_svg(self, stream)`](/slides/python-net/hi/aspose.slides/autoshape/write_as_svg/#iorawiobase) | Saves content of Shape as SVG file। |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/hi/aspose.slides/autoshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Saves content of Shape as SVG file। |
| [`remove_placeholder(self)`](/slides/python-net/hi/aspose.slides/autoshape/remove_placeholder/#) | Defines that this shape isn't a placeholder। |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/hi/aspose.slides/autoshape/add_placeholder/#iplaceholder) | Adds a new placeholder if there is no and sets placeholder properties to a specified one। |
| [`get_base_placeholder(self)`](/slides/python-net/hi/aspose.slides/autoshape/get_base_placeholder/#) | Returns a basic placeholder shape (shape from the layout and/or master slide that the current shape is inherited from).<br/>            A None is returned if the current shape is not inherited। |
| [`get_visual_bounds(self)`](/slides/python-net/hi/aspose.slides/autoshape/get_visual_bounds/#) | Gets the visual bounds of the shape calculated from its rendered content। |
| [`get_geometry_paths(self)`](/slides/python-net/hi/aspose.slides/autoshape/get_geometry_paths/#) | Returns the copy of path of the geometry shape. Coordinates are relative to the left top corner of the shape। |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/hi/aspose.slides/autoshape/set_geometry_path/#igeometrypath) | Updates shape geometry from [`IGeometryPath`](/slides/python-net/hi/aspose.slides/igeometrypath) object. Coordinates must be relative to the left<br/>             top corner of the shape.<br/>             Changes the type of the shape ([`GeometryShape.shape_type`](/slides/python-net/hi/aspose.slides/geometryshape/shape_type)) to [`ShapeType.CUSTOM`](/slides/python-net/hi/aspose.slides/shapetype/CUSTOM)। |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/hi/aspose.slides/autoshape/set_geometry_paths/#listigeometrypath) | Updates shape geometry from array of [`IGeometryPath`](/slides/python-net/hi/aspose.slides/igeometrypath). Coordinates must be relative to the left<br/>             top corner of the shape.<br/>             Changes the type of the shape ([`GeometryShape.shape_type`](/slides/python-net/hi/aspose.slides/geometryshape/shape_type)) to [`ShapeType.CUSTOM`](/slides/python-net/hi/aspose.slides/shapetype/CUSTOM)। |
| [`create_shape_elements(self)`](/slides/python-net/hi/aspose.slides/autoshape/create_shape_elements/#) | Creates and returns array of shape's elements। |
| [`add_text_frame(self, text)`](/slides/python-net/hi/aspose.slides/autoshape/add_text_frame/#str) | Adds a new TextFrame to a shape.<br/>            If shape already has TextFrame then simply changes its text। |

### देखें भी
* क्लास [`AutoShape`](/slides/python-net/hi/aspose.slides/autoshape)
* क्लास [`GeometryShape`](/slides/python-net/hi/aspose.slides/geometryshape)
* क्लास [`Shape`](/slides/python-net/hi/aspose.slides/shape)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)