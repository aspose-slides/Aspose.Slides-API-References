---
title: OleObjectFrame class
second_title: Aspose.Slides for Python के माध्यम से .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/oleobjectframe/
---
## OleObjectFrame क्लास

Represents an OLE object on a slide.

**विरासत:**[`OleObjectFrame`](/slides/python-net/hi/aspose.slides/oleobjectframe) → [`GraphicalObject`](/slides/python-net/hi/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/hi/aspose.slides/shape)

The OleObjectFrame type exposes the following members:

## गुण

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/hi/aspose.slides/oleobjectframe/is_text_holder/) | Determines whether the shape is TextHolder_PPT.<br/>केवल पढ़ने योग्य **bool**. |
| [`placeholder`](/slides/python-net/hi/aspose.slides/oleobjectframe/placeholder/) | Returns the placeholder for a shape. Returns None if the shape has no placeholder.<br/>केवल पढ़ने योग्य [`IPlaceholder`](/slides/python-net/hi/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/hi/aspose.slides/oleobjectframe/custom_data/) | Returns the shape's custom data.<br/>केवल पढ़ने योग्य [`ICustomData`](/slides/python-net/hi/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/hi/aspose.slides/oleobjectframe/raw_frame/) | Returns or sets the raw shape frame's properties.<br/>पढ़ने/लिखने योग्य [`IShapeFrame`](/slides/python-net/hi/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/hi/aspose.slides/oleobjectframe/frame/) | Returns or sets the shape frame's properties.<br/>पढ़ने/लिखने योग्य [`IShapeFrame`](/slides/python-net/hi/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/hi/aspose.slides/oleobjectframe/line_format/) | Returns the LineFormat object that contains line formatting properties for a shape.<br/>नोट: can return None for certain types of shapes which don't have line properties.<br/>केवल पढ़ने योग्य [`ILineFormat`](/slides/python-net/hi/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/hi/aspose.slides/oleobjectframe/three_d_format/) | Returns the ThreeDFormat object that 3D effect properties for a shape.<br/>नोट: can return None for certain types of shapes which don't have 3d properties.<br/>केवल पढ़ने योग्य [`IThreeDFormat`](/slides/python-net/hi/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/hi/aspose.slides/oleobjectframe/effect_format/) | Returns the EffectFormat object which contains pixel effects applied to a shape.<br/>नोट: can return None for certain types of shapes which don't have effect properties.<br/>केवल पढ़ने योग्य [`IEffectFormat`](/slides/python-net/hi/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/hi/aspose.slides/oleobjectframe/fill_format/) | Returns the FillFormat object that contains fill formatting properties for a shape.<br/>नोट: can return None for certain types of shapes which don't have fill properties.<br/>केवल पढ़ने योग्य [`IFillFormat`](/slides/python-net/hi/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/hi/aspose.slides/oleobjectframe/hyperlink_click/) | Returns or sets the hyperlink defined for mouse click.<br/>पढ़ने/लिखने योग्य [`IHyperlink`](/slides/python-net/hi/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/hi/aspose.slides/oleobjectframe/hyperlink_mouse_over/) | Returns or sets the hyperlink defined for mouse over.<br/>पढ़ने/लिखने योग्य [`IHyperlink`](/slides/python-net/hi/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/hi/aspose.slides/oleobjectframe/hyperlink_manager/) | Returns the hyperlink manager.<br/>केवल पढ़ने योग्य [`IHyperlinkManager`](/slides/python-net/hi/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/hi/aspose.slides/oleobjectframe/hidden/) | Determines whether the shape is hidden.<br/>पढ़ने/लिखने योग्य **bool**. |
| [`z_order_position`](/slides/python-net/hi/aspose.slides/oleobjectframe/z_order_position/) | Returns the position of a shape in the z-order.<br/>Shapes[0] returns the shape at the back of the z-order,<br/>and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order.<br/>केवल पढ़ने योग्य **int**. |
| [`connection_site_count`](/slides/python-net/hi/aspose.slides/oleobjectframe/connection_site_count/) | Returns the number of connection sites on the shape.<br/>केवल पढ़ने योग्य **int**. |
| [`rotation`](/slides/python-net/hi/aspose.slides/oleobjectframe/rotation/) | Returns or sets the number of degrees the specified shape is rotated around<br/>the z-axis. A positive value indicates clockwise rotation; a negative value<br/>indicates counterclockwise rotation.<br/>पढ़ने/लिखने योग्य **float**. |
| [`x`](/slides/python-net/hi/aspose.slides/oleobjectframe/x/) | Gets or sets the x-coordinate of the shape's upper-left corner, measured in points.<br/>पढ़ने/लिखने योग्य **float**. |
| [`y`](/slides/python-net/hi/aspose.slides/oleobjectframe/y/) | Gets or sets the y-coordinate of the shape's upper-left corner, measured in points.<br/>पढ़ने/लिखने योग्य **float**. |
| [`width`](/slides/python-net/hi/aspose.slides/oleobjectframe/width/) | Gets or sets the width of the shape, measured in points.<br/>पढ़ने/लिखने योग्य **float**. |
| [`height`](/slides/python-net/hi/aspose.slides/oleobjectframe/height/) | Gets or sets the height of the shape, measured in points.<br/>पढ़ने/लिखने योग्य **float**. |
| [`black_white_mode`](/slides/python-net/hi/aspose.slides/oleobjectframe/black_white_mode/) | Property specifies how a shape will render in black-and-white display mode..<br/>पढ़ने/लिखने योग्य [`BlackWhiteMode`](/slides/python-net/hi/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/hi/aspose.slides/oleobjectframe/unique_id/) | Returns an internal, presentation-scoped identifier intended for use by add-ins or other code.<br/>Because this value can be reassigned by the user or programmatically, it must not be treated<br/>as a persistent unique key.<br/>केवल पढ़ने योग्य **int**.<br/>See also [`Shape.office_interop_shape_id`](/slides/python-net/hi/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/hi/aspose.slides/oleobjectframe/office_interop_shape_id/) | Returns a slide-scoped unique identifier that remains constant for the lifetime of the shape and<br/>lets PowerPoint or interop code reliably reference the shape from anywhere in the document.<br/>केवल पढ़ने योग्य **int**.<br/>See also [`Shape.unique_id`](/slides/python-net/hi/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/hi/aspose.slides/oleobjectframe/alternative_text/) | Returns or sets the alternative text associated with a shape.<br/>पढ़ने/लिखने योग्य **str**. |
| [`alternative_text_title`](/slides/python-net/hi/aspose.slides/oleobjectframe/alternative_text_title/) | Returns or sets the title of alternative text associated with a shape.<br/>पढ़ने/लिखने योग्य **str**. |
| [`name`](/slides/python-net/hi/aspose.slides/oleobjectframe/name/) | Returns or sets the name of a shape.<br/>Must be not None. Use empty string value if needed.<br/>पढ़ने/लिखने योग्य **str**. |
| [`is_decorative`](/slides/python-net/hi/aspose.slides/oleobjectframe/is_decorative/) | Gets or sets 'Mark as decorative' option<br/>Reed/write **bool**. |
| [`shape_lock`](/slides/python-net/hi/aspose.slides/oleobjectframe/shape_lock/) | Returns shape's locks.<br/>केवल पढ़ने योग्य [`IGraphicalObjectLock`](/slides/python-net/hi/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/hi/aspose.slides/oleobjectframe/is_grouped/) | Determines whether the shape is grouped.<br/>केवल पढ़ने योग्य **bool**. |
| [`parent_group`](/slides/python-net/hi/aspose.slides/oleobjectframe/parent_group/) | Returns parent GroupShape object if shape is grouped. Otherwise returns None.<br/>केवल पढ़ने योग्य [`IGroupShape`](/slides/python-net/hi/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/hi/aspose.slides/oleobjectframe/slide/) | Returns the parent slide of a shape.<br/>केवल पढ़ने योग्य [`IBaseSlide`](/slides/python-net/hi/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/hi/aspose.slides/oleobjectframe/presentation/) | Returns the parent presentation of a slide.<br/>केवल पढ़ने योग्य [`IPresentation`](/slides/python-net/hi/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/hi/aspose.slides/oleobjectframe/graphical_object_lock/) | Returns shape's locks.<br/>केवल पढ़ने योग्य [`IGraphicalObjectLock`](/slides/python-net/hi/aspose.slides/igraphicalobjectlock). |
| [`substitute_picture_format`](/slides/python-net/hi/aspose.slides/oleobjectframe/substitute_picture_format/) | Returns OleObject image fill properties object.<br/>केवल पढ़ने योग्य [`IPictureFillFormat`](/slides/python-net/hi/aspose.slides/ipicturefillformat). |
| [`substitute_picture_title`](/slides/python-net/hi/aspose.slides/oleobjectframe/substitute_picture_title/) | Returns or sets the title for OleObject icon.<br/>पढ़ने/लिखने योग्य **str**. |
| [`object_name`](/slides/python-net/hi/aspose.slides/oleobjectframe/object_name/) | Returns or sets the name of an object.<br/>पढ़ने/लिखने योग्य **str**. |
| [`object_prog_id`](/slides/python-net/hi/aspose.slides/oleobjectframe/object_prog_id/) | Returns the ProgID of an object.<br/>Read only **str**. |
| [`link_file_name`](/slides/python-net/hi/aspose.slides/oleobjectframe/link_file_name/) | Returns the full path to a linked file. Short file name will be used.<br/>केवल पढ़ने योग्य **str**. |
| [`link_path_long`](/slides/python-net/hi/aspose.slides/oleobjectframe/link_path_long/) | Returns the full path to a linked file. Long file name will be used.<br/>पढ़ने/लिखने योग्य **str**. |
| [`link_path_relative`](/slides/python-net/hi/aspose.slides/oleobjectframe/link_path_relative/) | Returns the relative path to a linked file if present, otherwise returns an empty string.<br/>Readonly **str**. |
| [`embedded_file_label`](/slides/python-net/hi/aspose.slides/oleobjectframe/embedded_file_label/) | Returns the file name of embedded OLE object |
| [`embedded_file_name`](/slides/python-net/hi/aspose.slides/oleobjectframe/embedded_file_name/) | Returns the path of embedded OLE object |
| [`embedded_data`](/slides/python-net/hi/aspose.slides/oleobjectframe/embedded_data/) | Gets or sets information about OLE embedded data.<br/>पढ़ने/लिखने योग्य [`IOleEmbeddedDataInfo`](/slides/python-net/hi/aspose.slides/ioleembeddeddatainfo). |
| [`is_object_icon`](/slides/python-net/hi/aspose.slides/oleobjectframe/is_object_icon/) | Determines whether an object is visible as icon.<br/>पढ़ने/लिखने योग्य **bool**. |
| [`is_object_link`](/slides/python-net/hi/aspose.slides/oleobjectframe/is_object_link/) | Determines whether an object is linked to external file.<br/>केवल पढ़ने योग्य **bool**. |
| [`update_automatic`](/slides/python-net/hi/aspose.slides/oleobjectframe/update_automatic/) | Determines if the linked embedded object is automatically updated when the presentation is opened or printed.<br/>पढ़ने/लिखने योग्य **bool**. |

## मेथड्स

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/hi/aspose.slides/oleobjectframe/get_image/#) | Returns shape thumbnail.<br/>ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/hi/aspose.slides/oleobjectframe/get_image/#shapethumbnailbounds-float-float) | Returns shape thumbnail. |
| [`write_as_svg(self, stream)`](/slides/python-net/hi/aspose.slides/oleobjectframe/write_as_svg/#iorawiobase) | Saves content of Shape as SVG file. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/hi/aspose.slides/oleobjectframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Saves content of Shape as SVG file. |
| [`remove_placeholder(self)`](/slides/python-net/hi/aspose.slides/oleobjectframe/remove_placeholder/#) | Defines that this shape isn't a placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/hi/aspose.slides/oleobjectframe/add_placeholder/#iplaceholder) | Adds a new placeholder if there is no and sets placeholder properties to a specified one. |
| [`get_base_placeholder(self)`](/slides/python-net/hi/aspose.slides/oleobjectframe/get_base_placeholder/#) | Returns a basic placeholder shape (shape from the layout and/or master slide that the current shape is inherited from).<br/>A None is returned if the current shape is not inherited. |
| [`get_visual_bounds(self)`](/slides/python-net/hi/aspose.slides/oleobjectframe/get_visual_bounds/#) | Gets the visual bounds of the shape calculated from its rendered content. |
| [`set_embedded_data(self, embedded_data)`](/slides/python-net/hi/aspose.slides/oleobjectframe/set_embedded_data/#ioleembeddeddatainfo) | Sets information about OLE embedded data.<br/><br/>This method changes the properties of the object to reflect the new data and <br/>sets the IsObjectLink flag to false, indicating that the OLE object is embedded. |

### देखें
* क्लास [`GraphicalObject`](/slides/python-net/hi/aspose.slides/graphicalobject)
* क्लास [`OleObjectFrame`](/slides/python-net/hi/aspose.slides/oleobjectframe)
* क्लास [`Shape`](/slides/python-net/hi/aspose.slides/shape)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)