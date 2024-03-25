---
title: Connector
second_title: Aspose.Sildes for Python via Java API Reference
description: 
type: docs

url: /aspose.slides/connector/
---

## Connector class

  Represents a connector.
 
### addPlaceholder {#addPlaceholder}

| Name | Description |
| --- | --- |
| addPlaceholder([Placeholder](../placeholder)) | Adds a new placeholder if there is no and sets placeholder properties to a specified one. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| placeholderToCopyFrom | [Placeholder](../placeholder) | Placeholder to copy content from. |

 **Result:**
[Placeholder](../placeholder)


---


### createShapeElements {#createShapeElements}

| Name | Description |
| --- | --- |
| createShapeElements() | Creates and returns array of shape's elements. |

 **Result:**
[ShapeElement](../shapeelement)


---


### getAdjustments {#getAdjustments}

| Name | Description |
| --- | --- |
| getAdjustments() | Returns a collection of shape's adjustment values. Read-only IAdjustValueCollection. |

 **Result:**
[AdjustValueCollection](../adjustvaluecollection)


---


### getAlternativeText {#getAlternativeText}

| Name | Description |
| --- | --- |
| getAlternativeText() | Returns or sets the alternative text associated with a shape. Read/write String. |

 **Result:**
String


---


### getAlternativeTextTitle {#getAlternativeTextTitle}

| Name | Description |
| --- | --- |
| getAlternativeTextTitle() | Returns or sets the title of alternative text associated with a shape. Read/write String. |

 **Result:**
String


---


### getBasePlaceholder {#getBasePlaceholder}

| Name | Description |
| --- | --- |
| getBasePlaceholder() | Returns a basic placeholder shape (shape from the layout and/or master slide that the current shape is inherited from). A null is returned if the current shape is not inherited. |

 **Result:**
[Chart](../chart), [PictureFrame](../pictureframe), [Table](../table), [SmartArt](../smartart), [AudioFrame](../audioframe), [Connector](../connector), [SectionZoomFrame](../sectionzoomframe), [SmartArtShape](../smartartshape), [ZoomFrame](../zoomframe), [GeometryShape](../geometryshape), [ZoomObject](../zoomobject), [GraphicalObject](../graphicalobject), [Ink](../ink), [LegacyDiagram](../legacydiagram), [SummaryZoomFrame](../summaryzoomframe), [SummaryZoomSection](../summaryzoomsection), [GroupShape](../groupshape), [VideoFrame](../videoframe), [OleObjectFrame](../oleobjectframe), [AutoShape](../autoshape), [Shape](../shape)


---


### getBlackWhiteMode {#getBlackWhiteMode}

| Name | Description |
| --- | --- |
| getBlackWhiteMode() | Property specifies how a shape will render in black-and-white display mode.. Read/write BlackWhiteMode. |

 **Result:**
byte


---


### getConnectionSiteCount {#getConnectionSiteCount}

| Name | Description |
| --- | --- |
| getConnectionSiteCount() | Returns the number of connection sites on the shape. Read-only int. |

 **Result:**
int


---


### getConnectorLock {#getConnectorLock}

| Name | Description |
| --- | --- |
| getConnectorLock() | Returns connector's locks. Read-only IConnectorLock. |

 **Result:**
[ConnectorLock](../connectorlock)


---


### getCustomData {#getCustomData}

| Name | Description |
| --- | --- |
| getCustomData() | Returns the shape's custom data. Read-only ICustomData. |

 **Result:**
[CustomData](../customdata)


---


### getEffectFormat {#getEffectFormat}

| Name | Description |
| --- | --- |
| getEffectFormat() | Returns the EffectFormat object which contains pixel effects applied to a shape. Note: can return null for certain types of shapes which don't have effect properties. Read-only IEffectFormat. |

 **Result:**
[EffectFormat](../effectformat)


---


### getEndShapeConnectedTo {#getEndShapeConnectedTo}

| Name | Description |
| --- | --- |
| getEndShapeConnectedTo() | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

 **Result:**
[Chart](../chart), [PictureFrame](../pictureframe), [Table](../table), [SmartArt](../smartart), [AudioFrame](../audioframe), [Connector](../connector), [SectionZoomFrame](../sectionzoomframe), [SmartArtShape](../smartartshape), [ZoomFrame](../zoomframe), [GeometryShape](../geometryshape), [ZoomObject](../zoomobject), [GraphicalObject](../graphicalobject), [Ink](../ink), [LegacyDiagram](../legacydiagram), [SummaryZoomFrame](../summaryzoomframe), [SummaryZoomSection](../summaryzoomsection), [GroupShape](../groupshape), [VideoFrame](../videoframe), [OleObjectFrame](../oleobjectframe), [AutoShape](../autoshape), [Shape](../shape)

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### getEndShapeConnectionSiteIndex {#getEndShapeConnectionSiteIndex}

| Name | Description |
| --- | --- |
| getEndShapeConnectionSiteIndex() | Returns or sets the index of connection site for end shape. Read/write long. |

 **Result:**
long

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when value is less than EndShapeConnectedTo.ConnectionSiteCount |


---


### getFillFormat {#getFillFormat}

| Name | Description |
| --- | --- |
| getFillFormat() | Returns the FillFormat object that contains fill formatting properties for a shape. Note: can return null for certain types of shapes which don't have fill properties. Read-only IFillFormat. |

 **Result:**
[FillFormat](../fillformat)


---


### getFrame {#getFrame}

| Name | Description |
| --- | --- |
| getFrame() | Returns or sets the shape frame's properties. Read/write IShapeFrame. Value of each property of the returned IShapeFrame instance is not undefined (is not NaN or NotDefined). Value of each property of the assigned IShapeFrame instance must be not undefined (must be not NaN or NotDefined). You can set undefined values for RawFrame instance properties. |

 **Result:**
[ShapeFrame](../shapeframe)


---


### getGeometryPaths {#getGeometryPaths}

| Name | Description |
| --- | --- |
| getGeometryPaths() | Returns the copy of path of the geometry shape. Coordinates are relative to the left top corner of the shape. |

 **Result:**
[GeometryPath](../geometrypath)


---


### getHeight {#getHeight}

| Name | Description |
| --- | --- |
| getHeight() | Returns or sets the height of the shape. Read/write float. Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties. |

 **Result:**
float


---


### getHidden {#getHidden}

| Name | Description |
| --- | --- |
| getHidden() | Determines whether the shape is hidden. Read/write boolean. |

 **Result:**
boolean


---


### getHyperlinkClick {#getHyperlinkClick}

| Name | Description |
| --- | --- |
| getHyperlinkClick() | Returns or sets the hyperlink defined for mouse click. Read/write IHyperlink. |

 **Result:**
[Hyperlink](../hyperlink)


---


### getHyperlinkManager {#getHyperlinkManager}

| Name | Description |
| --- | --- |
| getHyperlinkManager() | Returns the hyperlink manager. Read-only IHyperlinkManager. |

 **Result:**
[HyperlinkManager](../hyperlinkmanager)


---


### getHyperlinkMouseOver {#getHyperlinkMouseOver}

| Name | Description |
| --- | --- |
| getHyperlinkMouseOver() | Returns or sets the hyperlink defined for mouse over. Read/write IHyperlink. |

 **Result:**
[Hyperlink](../hyperlink)


---


### getLineFormat {#getLineFormat}

| Name | Description |
| --- | --- |
| getLineFormat() | Returns the LineFormat object that contains line formatting properties for a shape. Note: can return null for certain types of shapes which don't have line properties. Read-only ILineFormat. |

 **Result:**
[LineFormat](../lineformat)


---


### getName {#getName}

| Name | Description |
| --- | --- |
| getName() | Returns or sets the name of a shape. Must be not null. Use empty string value if needed. Read/write String. |

 **Result:**
String


---


### getOfficeInteropShapeId {#getOfficeInteropShapeId}

| Name | Description |
| --- | --- |
| getOfficeInteropShapeId() | Gets unique shape identifier in slide scope. Read-only long. See also ( #getUniqueId) for getting unique shape identifier in presentation scope. |

 **Result:**
long


---


### getParentGroup {#getParentGroup}

| Name | Description |
| --- | --- |
| getParentGroup() | Returns parent GroupShape object if shape is grouped. Otherwise returns null. Read-only IGroupShape. Property ( #isGrouped) determines whether the shape is grouped. |

 **Result:**
[GroupShape](../groupshape)


---


### getParent_Immediate {#getParent_Immediate}

| Name | Description |
| --- | --- |
| getParent_Immediate() |  |


---


### getPlaceholder {#getPlaceholder}

| Name | Description |
| --- | --- |
| getPlaceholder() | Returns the placeholder for a shape. Returns null if the shape has no placeholder. Read-only IPlaceholder. |

 **Result:**
[Placeholder](../placeholder)


---


### getPresentation {#getPresentation}

| Name | Description |
| --- | --- |
| getPresentation() | Returns the parent presentation of a slide. Read-only IPresentation. |

 **Result:**
[Presentation](../presentation)


---


### getRawFrame {#getRawFrame}

| Name | Description |
| --- | --- |
| getRawFrame() | Returns or sets the raw shape frame's properties. Read/write IShapeFrame. |

 **Result:**
[ShapeFrame](../shapeframe)


---


### getRotation {#getRotation}

| Name | Description |
| --- | --- |
| getRotation() | Returns or sets the number of degrees the specified shape is rotated around the z-axis. A positive value indicates clockwise rotation; a negative value indicates counterclockwise rotation. Read/write float. Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties. |

 **Result:**
float


---


### getShapeLock {#getShapeLock}

| Name | Description |
| --- | --- |
| getShapeLock() | Returns shape's locks. Read-only IConnectorLock. |

 **Result:**
[ConnectorLock](../connectorlock)


---


### getShapeLock {#getShapeLock}

| Name | Description |
| --- | --- |
| getShapeLock() | Returns shape's locks. Read-only IBaseShapeLock. |

 **Result:**
[GroupShapeLock](../groupshapelock), [GraphicalObjectLock](../graphicalobjectlock), [BaseShapeLock](../baseshapelock), [ConnectorLock](../connectorlock), [AutoShapeLock](../autoshapelock), [PictureFrameLock](../pictureframelock)


---


### getShapeStyle {#getShapeStyle}

| Name | Description |
| --- | --- |
| getShapeStyle() | Returns shape's style object. Read-only IShapeStyle. |

 **Result:**
[ShapeStyle](../shapestyle)


---


### getShapeType {#getShapeType}

| Name | Description |
| --- | --- |
| getShapeType() | Returns or sets the AutoShape type. Read/write ShapeType. |

 **Result:**
int


---


### getShapeType {#getShapeType}

| Name | Description |
| --- | --- |
| getShapeType() | Returns or sets the geometry preset type. Note: on value changing all adjustment values will reset to their default values. Read/write ShapeType. |

 **Result:**
int


---


### getSlide {#getSlide}

| Name | Description |
| --- | --- |
| getSlide() | Returns the parent slide of a shape. Read-only IBaseSlide. |

 **Result:**
[MasterNotesSlide](../masternotesslide), [LayoutSlide](../layoutslide), [BaseSlide](../baseslide), [NotesSlide](../notesslide), [Slide](../slide), [MasterHandoutSlide](../masterhandoutslide), [MasterSlide](../masterslide)


---


### getStartShapeConnectedTo {#getStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| getStartShapeConnectedTo() | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

 **Result:**
[Chart](../chart), [PictureFrame](../pictureframe), [Table](../table), [SmartArt](../smartart), [AudioFrame](../audioframe), [Connector](../connector), [SectionZoomFrame](../sectionzoomframe), [SmartArtShape](../smartartshape), [ZoomFrame](../zoomframe), [GeometryShape](../geometryshape), [ZoomObject](../zoomobject), [GraphicalObject](../graphicalobject), [Ink](../ink), [LegacyDiagram](../legacydiagram), [SummaryZoomFrame](../summaryzoomframe), [SummaryZoomSection](../summaryzoomsection), [GroupShape](../groupshape), [VideoFrame](../videoframe), [OleObjectFrame](../oleobjectframe), [AutoShape](../autoshape), [Shape](../shape)

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### getStartShapeConnectionSiteIndex {#getStartShapeConnectionSiteIndex}

| Name | Description |
| --- | --- |
| getStartShapeConnectionSiteIndex() | Returns or sets the index of connection site for start shape. Read/write long. |

 **Result:**
long

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when value is less than StartShapeConnectedTo.ConnectionSiteCount |


---


### getThreeDFormat {#getThreeDFormat}

| Name | Description |
| --- | --- |
| getThreeDFormat() | Returns the ThreeDFormat object that 3d effect properties for a shape. Note: can return null for certain types of shapes which don't have 3d properties. Read-only IThreeDFormat. |

 **Result:**
[ThreeDFormat](../threedformat)


---


### getThumbnail {#getThumbnail}

| Name | Description |
| --- | --- |
| getThumbnail() | Returns shape thumbnail. ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |

 **Result:**
BufferedImage


---


### getThumbnail {#getThumbnail}

| Name | Description |
| --- | --- |
| getThumbnail(int, float, float) | Returns shape thumbnail. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| bounds | int | Shape thumbnail bounds type. |
| scaleX | float | X scale |
| scaleY | float | Y scale |

 **Result:**
BufferedImage


---


### getUniqueId {#getUniqueId}

| Name | Description |
| --- | --- |
| getUniqueId() | Gets unique shape identifier in presentation scope. Read-only long. See also ( #getOfficeInteropShapeId) for getting unique shape identifier in slide scope. |

 **Result:**
long


---


### getWidth {#getWidth}

| Name | Description |
| --- | --- |
| getWidth() | Returns or sets the width of the shape. Read/write float. Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties. |

 **Result:**
float


---


### getX {#getX}

| Name | Description |
| --- | --- |
| getX() | Returns or sets the x-coordinate of the upper-left corner of the shape. Read/write float. Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties. |

 **Result:**
float


---


### getY {#getY}

| Name | Description |
| --- | --- |
| getY() | Returns or sets the y-coordinate of the upper-left corner of the shape. Read/write float. Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties. |

 **Result:**
float


---


### getZOrderPosition {#getZOrderPosition}

| Name | Description |
| --- | --- |
| getZOrderPosition() | Returns the position of a shape in the z-order. Shapes[0] returns the shape at the back of the z-order, and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order. Read-only int. |

 **Result:**
int


---


### isDecorative {#isDecorative}

| Name | Description |
| --- | --- |
| isDecorative() | Gets or sets 'Mark as decorative' option Reed/write boolean. |

 **Result:**
boolean


---


### isGrouped {#isGrouped}

| Name | Description |
| --- | --- |
| isGrouped() | Determines whether the shape is grouped. Read-only boolean. Property ( #getParentGroup) returns parent GroupShape object if shape is grouped. |

 **Result:**
boolean


---


### isTextHolder {#isTextHolder}

| Name | Description |
| --- | --- |
| isTextHolder() | Determines whether the shape is TextHolder_PPT. Read-only boolean. |

 **Result:**
boolean


---


### removePlaceholder {#removePlaceholder}

| Name | Description |
| --- | --- |
| removePlaceholder() | Defines that this shape isn't a placeholder. |


---


### reroute {#reroute}

| Name | Description |
| --- | --- |
| reroute() | Reroutes connector so that it take the shortest possible path between the shapes it connect. |


---


### setAlternativeText {#setAlternativeText}

| Name | Description |
| --- | --- |
| setAlternativeText(String) | Returns or sets the alternative text associated with a shape. Read/write String. |


---


### setAlternativeTextTitle {#setAlternativeTextTitle}

| Name | Description |
| --- | --- |
| setAlternativeTextTitle(String) | Returns or sets the title of alternative text associated with a shape. Read/write String. |


---


### setBlackWhiteMode {#setBlackWhiteMode}

| Name | Description |
| --- | --- |
| setBlackWhiteMode(byte) | Property specifies how a shape will render in black-and-white display mode.. Read/write BlackWhiteMode. |


---


### setDecorative {#setDecorative}

| Name | Description |
| --- | --- |
| setDecorative(boolean) | Gets or sets 'Mark as decorative' option Reed/write boolean. |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Name | Description |
| --- | --- |
| setEndShapeConnectedTo([Chart](../chart)) | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Name | Description |
| --- | --- |
| setEndShapeConnectedTo([PictureFrame](../pictureframe)) | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Name | Description |
| --- | --- |
| setEndShapeConnectedTo([Table](../table)) | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Name | Description |
| --- | --- |
| setEndShapeConnectedTo([SmartArt](../smartart)) | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Name | Description |
| --- | --- |
| setEndShapeConnectedTo([AudioFrame](../audioframe)) | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Name | Description |
| --- | --- |
| setEndShapeConnectedTo([Connector](../connector)) | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Name | Description |
| --- | --- |
| setEndShapeConnectedTo([SectionZoomFrame](../sectionzoomframe)) | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Name | Description |
| --- | --- |
| setEndShapeConnectedTo([SmartArtShape](../smartartshape)) | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Name | Description |
| --- | --- |
| setEndShapeConnectedTo([ZoomFrame](../zoomframe)) | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Name | Description |
| --- | --- |
| setEndShapeConnectedTo([ZoomObject](../zoomobject)) | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Name | Description |
| --- | --- |
| setEndShapeConnectedTo([GraphicalObject](../graphicalobject)) | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Name | Description |
| --- | --- |
| setEndShapeConnectedTo([Ink](../ink)) | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Name | Description |
| --- | --- |
| setEndShapeConnectedTo([LegacyDiagram](../legacydiagram)) | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Name | Description |
| --- | --- |
| setEndShapeConnectedTo([SummaryZoomFrame](../summaryzoomframe)) | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Name | Description |
| --- | --- |
| setEndShapeConnectedTo([SummaryZoomSection](../summaryzoomsection)) | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Name | Description |
| --- | --- |
| setEndShapeConnectedTo([GroupShape](../groupshape)) | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Name | Description |
| --- | --- |
| setEndShapeConnectedTo([VideoFrame](../videoframe)) | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Name | Description |
| --- | --- |
| setEndShapeConnectedTo([OleObjectFrame](../oleobjectframe)) | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Name | Description |
| --- | --- |
| setEndShapeConnectedTo([AutoShape](../autoshape)) | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Name | Description |
| --- | --- |
| setEndShapeConnectedTo([Shape](../shape)) | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setEndShapeConnectionSiteIndex {#setEndShapeConnectionSiteIndex}

| Name | Description |
| --- | --- |
| setEndShapeConnectionSiteIndex(long) | Returns or sets the index of connection site for end shape. Read/write long. |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when value is less than EndShapeConnectedTo.ConnectionSiteCount |


---


### setFrame {#setFrame}

| Name | Description |
| --- | --- |
| setFrame([ShapeFrame](../shapeframe)) | Returns or sets the shape frame's properties. Read/write IShapeFrame. Value of each property of the returned IShapeFrame instance is not undefined (is not NaN or NotDefined). Value of each property of the assigned IShapeFrame instance must be not undefined (must be not NaN or NotDefined). You can set undefined values for RawFrame instance properties. |


---


### setGeometryPath {#setGeometryPath}

| Name | Description |
| --- | --- |
| setGeometryPath([GeometryPath](../geometrypath)) | Updates shape geometry from IGeometryPath object. Coordinates must be relative to the left top corner of the shape. Changes the type of the shape (ShapeType( #getShapeType/ #setShapeType(int))) to ShapeType#Custom. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| geometryPath | [GeometryPath](../geometrypath) | Geometry path |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Empty path found |


---


### setGeometryPaths {#setGeometryPaths}

| Name | Description |
| --- | --- |
| setGeometryPaths(com.aspose.slides.IGeometryPath[]) | Updates shape geometry from array of IGeometryPath. Coordinates must be relative to the left top corner of the shape. Changes the type of the shape (ShapeType( #getShapeType/ #setShapeType(int))) to ShapeType#Custom. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| geometryPaths | com.aspose.slides.IGeometryPath[] | Array geometry paths |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Empty path |


---


### setHeight {#setHeight}

| Name | Description |
| --- | --- |
| setHeight(float) | Returns or sets the height of the shape. Read/write float. Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties. |


---


### setHidden {#setHidden}

| Name | Description |
| --- | --- |
| setHidden(boolean) | Determines whether the shape is hidden. Read/write boolean. |


---


### setHyperlinkClick {#setHyperlinkClick}

| Name | Description |
| --- | --- |
| setHyperlinkClick([Hyperlink](../hyperlink)) | Returns or sets the hyperlink defined for mouse click. Read/write IHyperlink. |


---


### setHyperlinkMouseOver {#setHyperlinkMouseOver}

| Name | Description |
| --- | --- |
| setHyperlinkMouseOver([Hyperlink](../hyperlink)) | Returns or sets the hyperlink defined for mouse over. Read/write IHyperlink. |


---


### setName {#setName}

| Name | Description |
| --- | --- |
| setName(String) | Returns or sets the name of a shape. Must be not null. Use empty string value if needed. Read/write String. |


---


### setRawFrame {#setRawFrame}

| Name | Description |
| --- | --- |
| setRawFrame([ShapeFrame](../shapeframe)) | Returns or sets the raw shape frame's properties. Read/write IShapeFrame. |


---


### setRotation {#setRotation}

| Name | Description |
| --- | --- |
| setRotation(float) | Returns or sets the number of degrees the specified shape is rotated around the z-axis. A positive value indicates clockwise rotation; a negative value indicates counterclockwise rotation. Read/write float. Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties. |


---


### setShapeType {#setShapeType}

| Name | Description |
| --- | --- |
| setShapeType(int) | Returns or sets the AutoShape type. Read/write ShapeType. |


---


### setShapeType {#setShapeType}

| Name | Description |
| --- | --- |
| setShapeType(int) | Returns or sets the geometry preset type. Note: on value changing all adjustment values will reset to their default values. Read/write ShapeType. |


---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo([Chart](../chart)) | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo([PictureFrame](../pictureframe)) | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo([Table](../table)) | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo([SmartArt](../smartart)) | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo([AudioFrame](../audioframe)) | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo([Connector](../connector)) | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo([SectionZoomFrame](../sectionzoomframe)) | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo([SmartArtShape](../smartartshape)) | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo([ZoomFrame](../zoomframe)) | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo([ZoomObject](../zoomobject)) | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo([GraphicalObject](../graphicalobject)) | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo([Ink](../ink)) | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo([LegacyDiagram](../legacydiagram)) | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo([SummaryZoomFrame](../summaryzoomframe)) | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo([SummaryZoomSection](../summaryzoomsection)) | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo([GroupShape](../groupshape)) | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo([VideoFrame](../videoframe)) | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo([OleObjectFrame](../oleobjectframe)) | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo([AutoShape](../autoshape)) | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo([Shape](../shape)) | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setStartShapeConnectionSiteIndex {#setStartShapeConnectionSiteIndex}

| Name | Description |
| --- | --- |
| setStartShapeConnectionSiteIndex(long) | Returns or sets the index of connection site for start shape. Read/write long. |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when value is less than StartShapeConnectedTo.ConnectionSiteCount |


---


### setWidth {#setWidth}

| Name | Description |
| --- | --- |
| setWidth(float) | Returns or sets the width of the shape. Read/write float. Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties. |


---


### setX {#setX}

| Name | Description |
| --- | --- |
| setX(float) | Returns or sets the x-coordinate of the upper-left corner of the shape. Read/write float. Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties. |


---


### setY {#setY}

| Name | Description |
| --- | --- |
| setY(float) | Returns or sets the y-coordinate of the upper-left corner of the shape. Read/write float. Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties. |


---


### writeAsSvgToBytes  {#writeAsSvgToBytes }

| Name | Description |
| --- | --- |
| writeAsSvgToBytes () | Saves content of Shape as SVG file. |

 **Result:**
Bytes[]


---


### writeAsSvgToBytes  {#writeAsSvgToBytes }

| Name | Description |
| --- | --- |
| writeAsSvgToBytes ([SVGOptions](../svgoptions)) | Saves content of Shape as SVG file. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| svgOptions | [SVGOptions](../svgoptions) | SVG generation options |

 **Result:**
Bytes[]


---


