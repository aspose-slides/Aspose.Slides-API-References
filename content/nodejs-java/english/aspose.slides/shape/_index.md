---
title: Shape
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/shape/
---

## Shape class

  Represents a shape on a slide.
 
| [addPlaceholder] ([Placeholder]) Adds a new placeholder if there is no and sets placeholder properties to a specified one. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| placeholderToCopyFrom | [Placeholder] | Placeholder to copy content from. |

### Result
[Placeholder]


---


| [getAlternativeText] () Returns or sets the alternative text associated with a shape. Read/write String. |

### Result
String


---


| [getAlternativeTextTitle] () Returns or sets the title of alternative text associated with a shape. Read/write String. |

### Result
String


---


| [getBasePlaceholder] () Returns a basic placeholder shape (shape from the layout and/or master slide that the current shape is inherited from). A null is returned if the current shape is not inherited. |

### Result
[LegacyDiagram], [Connector], [GraphicalObject], [Shape], [Ink], [GroupShape], [SmartArtShape], [SummaryZoomSection], [ZoomObject], [SmartArt], [VideoFrame], [PictureFrame], [ZoomFrame], [AutoShape], [GeometryShape], [OleObjectFrame], [SectionZoomFrame], [AudioFrame], [Chart], [Table], [SummaryZoomFrame]


---


| [getBlackWhiteMode] () Property specifies how a shape will render in black-and-white display mode.. Read/write BlackWhiteMode. |

### Result
byte


---


| [getConnectionSiteCount] () Returns the number of connection sites on the shape. Read-only int. |

### Result
int


---


| [getCustomData] () Returns the shape's custom data. Read-only ICustomData. |

### Result
[CustomData]


---


| [getEffectFormat] () Returns the EffectFormat object which contains pixel effects applied to a shape. Note: can return null for certain types of shapes which don't have effect properties. Read-only IEffectFormat. |

### Result
[EffectFormat]


---


| [getFillFormat] () Returns the FillFormat object that contains fill formatting properties for a shape. Note: can return null for certain types of shapes which don't have fill properties. Read-only IFillFormat. |

### Result
[FillFormat]


---


| [getFrame] () Returns or sets the shape frame's properties. Read/write IShapeFrame. Value of each property of the returned IShapeFrame instance is not undefined (is not NaN or NotDefined). Value of each property of the assigned IShapeFrame instance must be not undefined (must be not NaN or NotDefined). You can set undefined values for RawFrame instance properties. |

### Result
[ShapeFrame]


---


| [getHeight] () Returns or sets the height of the shape. Read/write float. Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties. |

### Result
float


---


| [getHidden] () Determines whether the shape is hidden. Read/write boolean. |

### Result
boolean


---


| [getHyperlinkClick] () Returns or sets the hyperlink defined for mouse click. Read/write IHyperlink. |

### Result
[Hyperlink]


---


| [getHyperlinkManager] () Returns the hyperlink manager. Read-only IHyperlinkManager. |

### Result
[HyperlinkManager]


---


| [getHyperlinkMouseOver] () Returns or sets the hyperlink defined for mouse over. Read/write IHyperlink. |

### Result
[Hyperlink]


---


| [getLineFormat] () Returns the LineFormat object that contains line formatting properties for a shape. Note: can return null for certain types of shapes which don't have line properties. Read-only ILineFormat. |

### Result
[LineFormat]


---


| [getName] () Returns or sets the name of a shape. Must be not null. Use empty string value if needed. Read/write String. |

### Result
String


---


| [getOfficeInteropShapeId] () Gets unique shape identifier in slide scope. Read-only long. See also ( #getUniqueId) for getting unique shape identifier in presentation scope. |

### Result
long


---


| [getParentGroup] () Returns parent GroupShape object if shape is grouped. Otherwise returns null. Read-only IGroupShape. Property ( #isGrouped) determines whether the shape is grouped. |

### Result
[GroupShape]


---


| [getPlaceholder] () Returns the placeholder for a shape. Returns null if the shape has no placeholder. Read-only IPlaceholder. |

### Result
[Placeholder]


---


| [getPresentation] () Returns the parent presentation of a slide. Read-only IPresentation. |

### Result
[Presentation]


---


| [getRawFrame] () Returns or sets the raw shape frame's properties. Read/write IShapeFrame. |

### Result
[ShapeFrame]


---


| [getRotation] () Returns or sets the number of degrees the specified shape is rotated around the z-axis. A positive value indicates clockwise rotation; a negative value indicates counterclockwise rotation. Read/write float. Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties. |

### Result
float


---


| [getShapeLock] () Returns shape's locks. Read-only IBaseShapeLock. |

### Result
[GraphicalObjectLock], [PictureFrameLock], [BaseShapeLock], [GroupShapeLock], [AutoShapeLock], [ConnectorLock]


---


| [getSlide] () Returns the parent slide of a shape. Read-only IBaseSlide. |

### Result
[MasterNotesSlide], [MasterHandoutSlide], [BaseSlide], [NotesSlide], [LayoutSlide], [Slide], [MasterSlide]


---


| [getThreeDFormat] () Returns the ThreeDFormat object that 3d effect properties for a shape. Note: can return null for certain types of shapes which don't have 3d properties. Read-only IThreeDFormat. |

### Result
[ThreeDFormat]


---


| [getThumbnail] () Returns shape thumbnail. ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |

### Result
BufferedImage


---


| [getThumbnail] ([int], [float], [float]) Returns shape thumbnail. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| bounds | [int] | Shape thumbnail bounds type. |
| scaleX | [float] | X scale |
| scaleY | [float] | Y scale |

### Result
BufferedImage


---


| [getUniqueId] () Gets unique shape identifier in presentation scope. Read-only long. See also ( #getOfficeInteropShapeId) for getting unique shape identifier in slide scope. |

### Result
long


---


| [getWidth] () Returns or sets the width of the shape. Read/write float. Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties. |

### Result
float


---


| [getX] () Returns or sets the x-coordinate of the upper-left corner of the shape. Read/write float. Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties. |

### Result
float


---


| [getY] () Returns or sets the y-coordinate of the upper-left corner of the shape. Read/write float. Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties. |

### Result
float


---


| [getZOrderPosition] () Returns the position of a shape in the z-order. Shapes[0] returns the shape at the back of the z-order, and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order. Read-only int. |

### Result
int


---


| [isGrouped] () Determines whether the shape is grouped. Read-only boolean. Property ( #getParentGroup) returns parent GroupShape object if shape is grouped. |

### Result
boolean


---


| [isTextHolder] () Determines whether the shape is TextHolder_PPT. Read-only boolean. |

### Result
boolean


---


| [removePlaceholder] () Defines that this shape isn't a placeholder. |


---


| [setAlternativeText] ([String]) Returns or sets the alternative text associated with a shape. Read/write String. |


---


| [setAlternativeTextTitle] ([String]) Returns or sets the title of alternative text associated with a shape. Read/write String. |


---


| [setBlackWhiteMode] ([byte]) Property specifies how a shape will render in black-and-white display mode.. Read/write BlackWhiteMode. |


---


| [setFrame] ([ShapeFrame]) Returns or sets the shape frame's properties. Read/write IShapeFrame. Value of each property of the returned IShapeFrame instance is not undefined (is not NaN or NotDefined). Value of each property of the assigned IShapeFrame instance must be not undefined (must be not NaN or NotDefined). You can set undefined values for RawFrame instance properties. |


---


| [setHeight] ([float]) Returns or sets the height of the shape. Read/write float. Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties. |


---


| [setHidden] ([boolean]) Determines whether the shape is hidden. Read/write boolean. |


---


| [setHyperlinkClick] ([Hyperlink]) Returns or sets the hyperlink defined for mouse click. Read/write IHyperlink. |


---


| [setHyperlinkMouseOver] ([Hyperlink]) Returns or sets the hyperlink defined for mouse over. Read/write IHyperlink. |


---


| [setName] ([String]) Returns or sets the name of a shape. Must be not null. Use empty string value if needed. Read/write String. |


---


| [setRawFrame] ([ShapeFrame]) Returns or sets the raw shape frame's properties. Read/write IShapeFrame. |


---


| [setRotation] ([float]) Returns or sets the number of degrees the specified shape is rotated around the z-axis. A positive value indicates clockwise rotation; a negative value indicates counterclockwise rotation. Read/write float. Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties. |


---


| [setWidth] ([float]) Returns or sets the width of the shape. Read/write float. Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties. |


---


| [setX] ([float]) Returns or sets the x-coordinate of the upper-left corner of the shape. Read/write float. Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties. |


---


| [setY] ([float]) Returns or sets the y-coordinate of the upper-left corner of the shape. Read/write float. Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties. |


---


| [writeAsSvgToStream ] (Shape, [WriteStream]) Saves content of Shape as SVG file. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| shape | Shape  | link to self |
| stream | [WriteStream] | Target stream |


---


| [writeAsSvgToStream ] (Shape, [WriteStream], [SVGOptions]) Saves content of Shape as SVG file. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| shape | Shape  | link to self |
| stream | [WriteStream] | Target stream |
| svgOptions | [SVGOptions] | SVG generation options |


---


