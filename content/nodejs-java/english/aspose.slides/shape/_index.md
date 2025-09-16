---
title: Shape
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/shape/
---

## Shape class

  Represents a shape on a slide.
 
### addPlaceholder {#addPlaceholder}

| Name | Description |
| --- | --- |
| addPlaceholder ([Placeholder](../placeholder)) | Adds a new placeholder if there is no and sets placeholder properties to a specified one. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| placeholderToCopyFrom | [Placeholder](../placeholder) | Placeholder to copy content from. |

 **Returns:**
[Placeholder](../placeholder)


---


### getAlternativeText {#getAlternativeText}

| Name | Description |
| --- | --- |
| getAlternativeText () | Returns or sets the alternative text associated with a shape. Read/write String. |

 **Returns:**
String


---


### getAlternativeTextTitle {#getAlternativeTextTitle}

| Name | Description |
| --- | --- |
| getAlternativeTextTitle () | Returns or sets the title of alternative text associated with a shape. Read/write String. |

 **Returns:**
String


---


### getBasePlaceholder {#getBasePlaceholder}

| Name | Description |
| --- | --- |
| getBasePlaceholder () | Returns a basic placeholder shape (shape from the layout and/or master slide that the current shape is inherited from). A null is returned if the current shape is not inherited. |

 **Returns:**
[Ink](../ink), [SmartArtShape](../smartartshape), [VideoFrame](../videoframe), [AutoShape](../autoshape), [SectionZoomFrame](../sectionzoomframe), [SmartArt](../smartart), [InkActions](../inkactions), [AudioFrame](../audioframe), [Connector](../connector), [OleObjectFrame](../oleobjectframe), [Chart](../chart), [GraphicalObject](../graphicalobject), [GroupShape](../groupshape), [SummaryZoomSection](../summaryzoomsection), [LegacyDiagram](../legacydiagram), [SummaryZoomFrame](../summaryzoomframe), [ZoomFrame](../zoomframe), [Table](../table), [Shape](../shape), [GeometryShape](../geometryshape), [ZoomObject](../zoomobject), [PictureFrame](../pictureframe)


---


### getBlackWhiteMode {#getBlackWhiteMode}

| Name | Description |
| --- | --- |
| getBlackWhiteMode () | Property specifies how a shape will render in black-and-white display mode.. Read/write BlackWhiteMode. |

 **Returns:**
byte


---


### getConnectionSiteCount {#getConnectionSiteCount}

| Name | Description |
| --- | --- |
| getConnectionSiteCount () | Returns the number of connection sites on the shape. Read-only int. |

 **Returns:**
int


---


### getCustomData {#getCustomData}

| Name | Description |
| --- | --- |
| getCustomData () | Returns the shape's custom data. Read-only ICustomData. |

 **Returns:**
[CustomData](../customdata)


---


### getEffectFormat {#getEffectFormat}

| Name | Description |
| --- | --- |
| getEffectFormat () | Returns the EffectFormat object which contains pixel effects applied to a shape. Note: can return null for certain types of shapes which don't have effect properties. Read-only IEffectFormat. |

 **Returns:**
[EffectFormat](../effectformat)


---


### getFillFormat {#getFillFormat}

| Name | Description |
| --- | --- |
| getFillFormat () | Returns the FillFormat object that contains fill formatting properties for a shape. Note: can return null for certain types of shapes which don't have fill properties. Read-only IFillFormat. |

 **Returns:**
[FillFormat](../fillformat)


---


### getFrame {#getFrame}

| Name | Description |
| --- | --- |
| getFrame () | Returns or sets the shape frame's properties. Read/write IShapeFrame. Value of each property of the returned IShapeFrame instance is not undefined (is not NaN or NotDefined). Value of each property of the assigned IShapeFrame instance must be not undefined (must be not NaN or NotDefined). You can set undefined values for RawFrame instance properties. |

 **Returns:**
[ShapeFrame](../shapeframe)


---


### getHeight {#getHeight}

| Name | Description |
| --- | --- |
| getHeight () | Gets or sets the height of the shape, measured in points. Read/write float. The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance. |

 **Returns:**
float


---


### getHidden {#getHidden}

| Name | Description |
| --- | --- |
| getHidden () | Determines whether the shape is hidden. Read/write boolean. |

 **Returns:**
boolean


---


### getHyperlinkClick {#getHyperlinkClick}

| Name | Description |
| --- | --- |
| getHyperlinkClick () | Returns or sets the hyperlink defined for mouse click. Read/write IHyperlink. |

 **Returns:**
[Hyperlink](../hyperlink)


---


### getHyperlinkManager {#getHyperlinkManager}

| Name | Description |
| --- | --- |
| getHyperlinkManager () | Returns the hyperlink manager. Read-only IHyperlinkManager. |

 **Returns:**
[HyperlinkManager](../hyperlinkmanager)


---


### getHyperlinkMouseOver {#getHyperlinkMouseOver}

| Name | Description |
| --- | --- |
| getHyperlinkMouseOver () | Returns or sets the hyperlink defined for mouse over. Read/write IHyperlink. |

 **Returns:**
[Hyperlink](../hyperlink)


---


### getImage {#getImage}

| Name | Description |
| --- | --- |
| getImage () | Returns shape thumbnail. ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |

 **Returns:**
SlidesImage


---


### getImage {#getImage}

| Name | Description |
| --- | --- |
| getImage (int, float, float) | Returns shape thumbnail. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| bounds | int | Shape thumbnail bounds type. |
| scaleX | float | X scale |
| scaleY | float | Y scale |

 **Returns:**
SlidesImage


---


### getLineFormat {#getLineFormat}

| Name | Description |
| --- | --- |
| getLineFormat () | Returns the LineFormat object that contains line formatting properties for a shape. Note: can return null for certain types of shapes which don't have line properties. Read-only ILineFormat. |

 **Returns:**
[LineFormat](../lineformat)


---


### getName {#getName}

| Name | Description |
| --- | --- |
| getName () | Returns or sets the name of a shape. Must be not null. Use empty string value if needed. Read/write String. |

 **Returns:**
String


---


### getOfficeInteropShapeId {#getOfficeInteropShapeId}

| Name | Description |
| --- | --- |
| getOfficeInteropShapeId () | Returns a slide-scoped unique identifier that remains constant for the lifetime of the shape and lets PowerPoint or interop code reliably reference the shape from anywhere in the document. Read-only long. See also #getUniqueId. |

 **Returns:**
long


---


### getParentGroup {#getParentGroup}

| Name | Description |
| --- | --- |
| getParentGroup () | Returns parent GroupShape object if shape is grouped. Otherwise returns null. Read-only IGroupShape. Property #isGrouped determines whether the shape is grouped. |

 **Returns:**
[GroupShape](../groupshape)


---


### getPlaceholder {#getPlaceholder}

| Name | Description |
| --- | --- |
| getPlaceholder () | Returns the placeholder for a shape. Returns null if the shape has no placeholder. Read-only IPlaceholder. |

 **Returns:**
[Placeholder](../placeholder)


---


### getPresentation {#getPresentation}

| Name | Description |
| --- | --- |
| getPresentation () | Returns the parent presentation of a slide. Read-only IPresentation. |

 **Returns:**
[Presentation](../presentation)


---


### getRawFrame {#getRawFrame}

| Name | Description |
| --- | --- |
| getRawFrame () | Returns or sets the raw shape frame's properties. Read/write IShapeFrame. |

 **Returns:**
[ShapeFrame](../shapeframe)


---


### getRotation {#getRotation}

| Name | Description |
| --- | --- |
| getRotation () | Returns or sets the number of degrees the specified shape is rotated around the z-axis. A positive value indicates clockwise rotation; a negative value indicates counterclockwise rotation. Read/write float. Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties. |

 **Returns:**
float


---


### getShapeLock {#getShapeLock}

| Name | Description |
| --- | --- |
| getShapeLock () | Returns shape's locks. Read-only IBaseShapeLock. |

 **Returns:**
[GraphicalObjectLock](../graphicalobjectlock), [AutoShapeLock](../autoshapelock), [GroupShapeLock](../groupshapelock), [PictureFrameLock](../pictureframelock), [ConnectorLock](../connectorlock), [BaseShapeLock](../baseshapelock)


---


### getSlide {#getSlide}

| Name | Description |
| --- | --- |
| getSlide () | Returns the parent slide of a shape. Read-only IBaseSlide. |

 **Returns:**
[NotesSlide](../notesslide), [MasterNotesSlide](../masternotesslide), [LayoutSlide](../layoutslide), [BaseSlide](../baseslide), [Slide](../slide), [MasterSlide](../masterslide), [MasterHandoutSlide](../masterhandoutslide)


---


### getThreeDFormat {#getThreeDFormat}

| Name | Description |
| --- | --- |
| getThreeDFormat () | Returns the ThreeDFormat object that 3d effect properties for a shape. Note: can return null for certain types of shapes which don't have 3d properties. Read-only IThreeDFormat. |

 **Returns:**
[ThreeDFormat](../threedformat)


---


### getThumbnail {#getThumbnail}

| Name | Description |
| --- | --- |
| getThumbnail () | Returns shape thumbnail. ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |

 **Returns:**
BufferedImage


---


### getThumbnail {#getThumbnail}

| Name | Description |
| --- | --- |
| getThumbnail (int, float, float) | Returns shape thumbnail. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| bounds | int | Shape thumbnail bounds type. |
| scaleX | float | X scale |
| scaleY | float | Y scale |

 **Returns:**
BufferedImage


---


### getUniqueId {#getUniqueId}

| Name | Description |
| --- | --- |
| getUniqueId () | Returns an internal, presentation-scoped identifier intended for use by add-ins or other code. Because this value can be reassigned by the user or programmatically, it must not be treated as a persistent unique key. Read-only long. See also #getOfficeInteropShapeId. |

 **Returns:**
long


---


### getWidth {#getWidth}

| Name | Description |
| --- | --- |
| getWidth () | Gets or sets the width of the shape, measured in points. Read/write float. The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance. |

 **Returns:**
float


---


### getX {#getX}

| Name | Description |
| --- | --- |
| getX () | Gets or sets the x-coordinate of the shape's upper-left corner, measured in points. Read/write float. The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance. |

 **Returns:**
float


---


### getY {#getY}

| Name | Description |
| --- | --- |
| getY () | Gets or sets the y-coordinate of the shape's upper-left corner, measured in points. Read/write float. The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance. |

 **Returns:**
float


---


### getZOrderPosition {#getZOrderPosition}

| Name | Description |
| --- | --- |
| getZOrderPosition () | Returns the position of a shape in the z-order. Shapes[0] returns the shape at the back of the z-order, and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order. Read-only int. |

 **Returns:**
int


---


### isDecorative {#isDecorative}

| Name | Description |
| --- | --- |
| isDecorative () | Gets or sets 'Mark as decorative' option Reed/write boolean. |

 **Returns:**
boolean


---


### isGrouped {#isGrouped}

| Name | Description |
| --- | --- |
| isGrouped () | Determines whether the shape is grouped. Read-only boolean. Property #getParentGroup returns parent GroupShape object if shape is grouped. |

 **Returns:**
boolean


---


### isTextHolder {#isTextHolder}

| Name | Description |
| --- | --- |
| isTextHolder () | Determines whether the shape is TextHolder_PPT. Read-only boolean. |

 **Returns:**
boolean


---


### removePlaceholder {#removePlaceholder}

| Name | Description |
| --- | --- |
| removePlaceholder () | Defines that this shape isn't a placeholder. |


---


### setAlternativeText {#setAlternativeText}

| Name | Description |
| --- | --- |
| setAlternativeText (String) | Returns or sets the alternative text associated with a shape. Read/write String. |


---


### setAlternativeTextTitle {#setAlternativeTextTitle}

| Name | Description |
| --- | --- |
| setAlternativeTextTitle (String) | Returns or sets the title of alternative text associated with a shape. Read/write String. |


---


### setBlackWhiteMode {#setBlackWhiteMode}

| Name | Description |
| --- | --- |
| setBlackWhiteMode (byte) | Property specifies how a shape will render in black-and-white display mode.. Read/write BlackWhiteMode. |


---


### setDecorative {#setDecorative}

| Name | Description |
| --- | --- |
| setDecorative (boolean) | Gets or sets 'Mark as decorative' option Reed/write boolean. |


---


### setFrame {#setFrame}

| Name | Description |
| --- | --- |
| setFrame ([ShapeFrame](../shapeframe)) | Returns or sets the shape frame's properties. Read/write IShapeFrame. Value of each property of the returned IShapeFrame instance is not undefined (is not NaN or NotDefined). Value of each property of the assigned IShapeFrame instance must be not undefined (must be not NaN or NotDefined). You can set undefined values for RawFrame instance properties. |


---


### setHeight {#setHeight}

| Name | Description |
| --- | --- |
| setHeight (float) | Gets or sets the height of the shape, measured in points. Read/write float. The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance. |


---


### setHidden {#setHidden}

| Name | Description |
| --- | --- |
| setHidden (boolean) | Determines whether the shape is hidden. Read/write boolean. |


---


### setHyperlinkClick {#setHyperlinkClick}

| Name | Description |
| --- | --- |
| setHyperlinkClick ([Hyperlink](../hyperlink)) | Returns or sets the hyperlink defined for mouse click. Read/write IHyperlink. |


---


### setHyperlinkMouseOver {#setHyperlinkMouseOver}

| Name | Description |
| --- | --- |
| setHyperlinkMouseOver ([Hyperlink](../hyperlink)) | Returns or sets the hyperlink defined for mouse over. Read/write IHyperlink. |


---


### setName {#setName}

| Name | Description |
| --- | --- |
| setName (String) | Returns or sets the name of a shape. Must be not null. Use empty string value if needed. Read/write String. |


---


### setRawFrame {#setRawFrame}

| Name | Description |
| --- | --- |
| setRawFrame ([ShapeFrame](../shapeframe)) | Returns or sets the raw shape frame's properties. Read/write IShapeFrame. |


---


### setRotation {#setRotation}

| Name | Description |
| --- | --- |
| setRotation (float) | Returns or sets the number of degrees the specified shape is rotated around the z-axis. A positive value indicates clockwise rotation; a negative value indicates counterclockwise rotation. Read/write float. Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties. |


---


### setWidth {#setWidth}

| Name | Description |
| --- | --- |
| setWidth (float) | Gets or sets the width of the shape, measured in points. Read/write float. The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance. |


---


### setX {#setX}

| Name | Description |
| --- | --- |
| setX (float) | Gets or sets the x-coordinate of the shape's upper-left corner, measured in points. Read/write float. The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance. |


---


### setY {#setY}

| Name | Description |
| --- | --- |
| setY (float) | Gets or sets the y-coordinate of the shape's upper-left corner, measured in points. Read/write float. The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance. |


---


### writeAsSvgToStream  {#writeAsSvgToStream }

| Name | Description |
| --- | --- |
| writeAsSvgToStream  (Shape, WriteStream) | Saves content of Shape as SVG file. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | Shape  | link to self |
| stream | WriteStream | Target stream |


---


### writeAsSvgToStream  {#writeAsSvgToStream }

| Name | Description |
| --- | --- |
| writeAsSvgToStream  (Shape, WriteStream, [SVGOptions](../svgoptions)) | Saves content of Shape as SVG file. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shape | Shape  | link to self |
| stream | WriteStream | Target stream |
| svgOptions | [SVGOptions](../svgoptions) | SVG generation options |


---


