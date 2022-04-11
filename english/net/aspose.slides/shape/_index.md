---
title: Shape
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 9300
url: /net/aspose.slides/shape/
---
## Shape class

Represents a shape on a slide.

```csharp
public class Shape : IShape
```

## Public Members

| Name | Description |
| --- | --- |
| [AlternativeText](alternativetext) { get; set; } | Returns or sets the alternative text associated with a shape. Read/write String. |
| [AlternativeTextTitle](alternativetexttitle) { get; set; } | Returns or sets the title of alternative text associated with a shape. Read/write String. |
| [BlackWhiteMode](blackwhitemode) { get; set; } | Property specifies how a shape will render in black-and-white display mode.. Read/write [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](connectionsitecount) { get; } | Returns the number of connection sites on the shape. Read-only Int32. |
| [CustomData](customdata) { get; } | Returns the shape's custom data. Read-only [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](effectformat) { get; } | Returns the EffectFormat object which contains pixel effects applied to a shape. Note: can return null for certain types of shapes which don't have effect properties. Read-only [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](fillformat) { get; } | Returns the FillFormat object that contains fill formatting properties for a shape. Note: can return null for certain types of shapes which don't have fill properties. Read-only [`IFillFormat`](../ifillformat). |
| [Frame](frame) { get; set; } | Returns or sets the shape frame's properties. Read/write [`IShapeFrame`](../ishapeframe). |
| [Height](height) { get; set; } | Returns or sets the height of the shape. Read/write Single. |
| [Hidden](hidden) { get; set; } | Determines whether the shape is hidden. Read/write Boolean. |
| [HyperlinkClick](hyperlinkclick) { get; set; } | Returns or sets the hyperlink defined for mouse click. Read/write [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](hyperlinkmanager) { get; } | Returns the hyperlink manager. Read-only [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](hyperlinkmouseover) { get; set; } | Returns or sets the hyperlink defined for mouse over. Read/write [`IHyperlink`](../ihyperlink). |
| [IsGrouped](isgrouped) { get; } | Determines whether the shape is grouped. Read-only Boolean. |
| [IsTextHolder](istextholder) { get; } | Determines whether the shape is TextHolder_PPT. Read-only Boolean. |
| virtual [LineFormat](lineformat) { get; } | Returns the LineFormat object that contains line formatting properties for a shape. Note: can return null for certain types of shapes which don't have line properties. Read-only [`ILineFormat`](../ilineformat). |
| [Name](name) { get; set; } | Returns or sets the name of a shape. Must be not null. Use empty string value if needed. Read/write String. |
| [OfficeInteropShapeId](officeinteropshapeid) { get; } | Gets unique shape identifier in slide scope. Read-only UInt32. See also [`UniqueId`](./uniqueid) for getting unique shape identifier in presentation scope. |
| [ParentGroup](parentgroup) { get; } | Returns parent GroupShape object if shape is grouped. Otherwise returns null. Read-only [`IGroupShape`](../igroupshape). |
| [Placeholder](placeholder) { get; } | Returns the placeholder for a shape. Returns null if the shape has no placeholder. Read-only [`IPlaceholder`](../iplaceholder). |
| [Presentation](presentation) { get; } | Returns the parent presentation of a slide. Read-only [`IPresentation`](../ipresentation). |
| [RawFrame](rawframe) { get; set; } | Returns or sets the raw shape frame's properties. Read/write [`IShapeFrame`](../ishapeframe). |
| [Rotation](rotation) { get; set; } | Returns or sets the number of degrees the specified shape is rotated around the z-axis. A positive value indicates clockwise rotation; a negative value indicates counterclockwise rotation. Read/write Single. |
| [ShapeLock](shapelock) { get; } | Returns shape's locks. Read-only [`IBaseShapeLock`](../ibaseshapelock). |
| [Slide](slide) { get; } | Returns the parent slide of a shape. Read-only [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](threedformat) { get; } | Returns the ThreeDFormat object that 3d effect properties for a shape. Note: can return null for certain types of shapes which don't have 3d properties. Read-only [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](uniqueid) { get; } | Gets unique shape identifier in presentation scope. Read-only UInt32. See also [`OfficeInteropShapeId`](./officeinteropshapeid) for getting unique shape identifier in slide scope. |
| [Width](width) { get; set; } | Returns or sets the width of the shape. Read/write Single. |
| [X](x) { get; set; } | Returns or sets the x-coordinate of the upper-left corner of the shape. Read/write Single. |
| [Y](y) { get; set; } | Returns or sets the y-coordinate of the upper-left corner of the shape. Read/write Single. |
| virtual [ZOrderPosition](zorderposition) { get; } | Returns the position of a shape in the z-order. Shapes[0] returns the shape at the back of the z-order, and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order. Read-only Int32. |
| [AddPlaceholder](addplaceholder)(…) | Adds a new placeholder if there is no and sets placeholder properties to a specified one. |
| [GetThumbnail](getthumbnail)() | Returns shape thumbnail. ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [GetThumbnail](getthumbnail)(…) | Returns shape thumbnail. |
| [RemovePlaceholder](removeplaceholder)() | Defines that this shape isn't a placeholder. |
| [WriteAsSvg](writeassvg)(…) | Saves content of Shape as SVG file. (2 methods) |

### See Also

* interface [IShape](../ishape)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
