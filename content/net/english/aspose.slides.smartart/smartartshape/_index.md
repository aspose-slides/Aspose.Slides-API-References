---
title: SmartArtShape
second_title: Aspose.Sildes for .NET API Reference
description: Represents SmartArt shape
type: docs
weight: 10420
url: /aspose.slides.smartart/smartartshape/
---

## SmartArtShape class

Represents SmartArt shape

```csharp
public class SmartArtShape : GeometryShape, ISmartArtShape
```

## Properties

| Name | Description |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Returns a collection of shape's adjustment values. Read-only [`IAdjustValueCollection`](../../aspose.slides/iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Returns or sets the alternative text associated with a shape. Read/write String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Returns or sets the title of alternative text associated with a shape. Read/write String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Property specifies how a shape will render in black-and-white display mode.. Read/write [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Returns the number of connection sites on the shape. Read-only Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Returns the shape's custom data. Read-only [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Returns the EffectFormat object which contains pixel effects applied to a shape. Note: can return null for certain types of shapes which don't have effect properties. Read-only [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Returns the FillFormat object that contains fill formatting properties for a shape. Note: can return null for certain types of shapes which don't have fill properties. Read-only [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Returns or sets the shape frame's properties. Read/write [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Gets or sets the height of the shape, measured in points. Read/write Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Determines whether the shape is hidden. Read/write Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Returns or sets the hyperlink defined for mouse click. Read/write [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Returns the hyperlink manager. Read-only [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Returns or sets the hyperlink defined for mouse over. Read/write [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Gets or sets 'Mark as decorative' option Reed/write Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Determines whether the shape is grouped. Read-only Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Determines whether the shape is TextHolder_PPT. Read-only Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Returns the LineFormat object that contains line formatting properties for a shape. Note: can return null for certain types of shapes which don't have line properties. Read-only [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Returns or sets the name of a shape. Must be not null. Use empty string value if needed. Read/write String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Returns a slide-scoped unique identifier that remains constant for the lifetime of the shape and lets PowerPoint or interop code reliably reference the shape from anywhere in the document. Read-only UInt32. See also [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Returns parent GroupShape object if shape is grouped. Otherwise returns null. Read-only [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Returns the placeholder for a shape. Returns null if the shape has no placeholder. Read-only [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Returns the parent presentation of a slide. Read-only [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Returns or sets the raw shape frame's properties. Read/write [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Returns or sets the number of degrees the specified shape is rotated around the z-axis. A positive value indicates clockwise rotation; a negative value indicates counterclockwise rotation. Read/write Single. |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | Returns shape's locks. Read-only [`IBaseShapeLock`](../../aspose.slides/ibaseshapelock). |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Returns shape's style object. Read-only [`IShapeStyle`](../../aspose.slides/ishapestyle). |
| override [ShapeType](../../aspose.slides.smartart/smartartshape/shapetype) { get; set; } | Returns or sets the geometry preset type. Note: on value changing all adjustment values will reset to their default values. Read/write [`ShapeType`](../../aspose.slides/shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Returns the parent slide of a shape. Read-only [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| [TextFrame](../../aspose.slides.smartart/smartartshape/textframe) { get; } | Returns text of the SmartArt shape. Read-only [`ITextFrame`](../../aspose.slides/itextframe). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Returns the ThreeDFormat object that 3d effect properties for a shape. Note: can return null for certain types of shapes which don't have 3d properties. Read-only [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Returns an internal, presentation-scoped identifier intended for use by add-ins or other code. Because this value can be reassigned by the user or programmatically, it must not be treated as a persistent unique key. Read-only UInt32. See also [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Gets or sets the width of the shape, measured in points. Read/write Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Gets or sets the x-coordinate of the shape's upper-left corner, measured in points. Read/write Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Gets or sets the y-coordinate of the shape's upper-left corner, measured in points. Read/write Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Returns the position of a shape in the z-order. Shapes[0] returns the shape at the back of the z-order, and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order. Read-only Int32. |

## Methods

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Adds a new placeholder if there is no and sets placeholder properties to a specified one. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Creates and returns array of shape's elements. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Returns a basic placeholder shape (shape from the layout and/or master slide that the current shape is inherited from). A null is returned if the current shape is not inherited. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Returns the copy of path of the geometry shape. Coordinates are relative to the left top corner of the shape. |
| [GetImage](../../aspose.slides/shape/getimage)() | Returns shape thumbnail. ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Returns shape thumbnail. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Defines that this shape isn't a placeholder. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Updates shape geometry from [`IGeometryPath`](../../aspose.slides/igeometrypath) object. Coordinates must be relative to the left top corner of the shape. Changes the type of the shape ([`ShapeType`](../../aspose.slides/geometryshape/shapetype)) to Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Updates shape geometry from array of [`IGeometryPath`](../../aspose.slides/igeometrypath). Coordinates must be relative to the left top corner of the shape. Changes the type of the shape ([`ShapeType`](../../aspose.slides/geometryshape/shapetype)) to Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Saves content of Shape as SVG file. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Saves content of Shape as SVG file. |

### See Also

* class [GeometryShape](../../aspose.slides/geometryshape)
* interface [ISmartArtShape](../ismartartshape)
* namespace [Aspose.Slides.SmartArt](../../aspose.slides.smartart)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
