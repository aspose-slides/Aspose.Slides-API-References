---
title: SmartArt
second_title: Aspose.Sildes for .NET API Reference
description: Represents a SmartArt diagram
type: docs
weight: 9900
url: /net/aspose.slides.smartart/smartart/
---
## SmartArt class

Represents a SmartArt diagram

```csharp
public class SmartArt : GraphicalObject, ISmartArt
```

## Properties

| Name | Description |
| --- | --- |
| [AllNodes](../../aspose.slides.smartart/smartart/allnodes) { get; } | Returns collections of all nodes in the SmartArt object. Read-only [`ISmartArtNodeCollection`](../ismartartnodecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Returns or sets the alternative text associated with a shape. Read/write String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Returns or sets the title of alternative text associated with a shape. Read/write String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Property specifies how a shape will render in black-and-white display mode.. Read/write [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ColorStyle](../../aspose.slides.smartart/smartart/colorstyle) { get; set; } | Returns or sets color style of SmartArt object. Read/write [`SmartArtColorType`](../smartartcolortype). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Returns the number of connection sites on the shape. Read-only Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Returns the shape's custom data. Read-only [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Returns the EffectFormat object which contains pixel effects applied to a shape. Note: can return null for certain types of shapes which don't have effect properties. Read-only [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Returns the FillFormat object that contains fill formatting properties for a shape. Note: can return null for certain types of shapes which don't have fill properties. Read-only [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Returns or sets the shape frame's properties. Read/write [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Returns shape's locks. Read-only [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Returns or sets the height of the shape. Read/write Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Determines whether the shape is hidden. Read/write Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Returns or sets the hyperlink defined for mouse click. Read/write [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Returns the hyperlink manager. Read-only [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Returns or sets the hyperlink defined for mouse over. Read/write [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Determines whether the shape is grouped. Read-only Boolean. |
| [IsReversed](../../aspose.slides.smartart/smartart/isreversed) { get; set; } | Return or set the state of the SmartArt diagram with regard to (left-to-right) LTR or (right-to-left) RTL, if the diagram supports reversal. Read/write Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Determines whether the shape is TextHolder_PPT. Read-only Boolean. |
| [Layout](../../aspose.slides.smartart/smartart/layout) { get; set; } | Returns or sets layout of the SmartArt object. Read/write [`SmartArtLayoutType`](../smartartlayouttype). |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Returns the LineFormat object that contains line formatting properties for a shape. Note: can return null for certain types of shapes which don't have line properties. Read-only [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Returns or sets the name of a shape. Must be not null. Use empty string value if needed. Read/write String. |
| [Nodes](../../aspose.slides.smartart/smartart/nodes) { get; } | Returns collections of root nodes in SmartArt object. Read-only [`ISmartArtNodeCollection`](../ismartartnodecollection). |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Gets unique shape identifier in slide scope. Read-only UInt32. See also [`UniqueId`](../../aspose.slides/shape/uniqueid) for getting unique shape identifier in presentation scope. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Returns parent GroupShape object if shape is grouped. Otherwise returns null. Read-only [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Returns the placeholder for a shape. Returns null if the shape has no placeholder. Read-only [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Returns the parent presentation of a slide. Read-only [`IPresentation`](../../aspose.slides/ipresentation). |
| [QuickStyle](../../aspose.slides.smartart/smartart/quickstyle) { get; set; } | Returns or sets quick style of SmartArt object. Read/write [`SmartArtQuickStyleType`](../smartartquickstyletype). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Returns or sets the raw shape frame's properties. Read/write [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Returns or sets the number of degrees the specified shape is rotated around the z-axis. A positive value indicates clockwise rotation; a negative value indicates counterclockwise rotation. Read/write Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Returns shape's locks. Read-only [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 properties) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Returns the parent slide of a shape. Read-only [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Returns the ThreeDFormat object that 3d effect properties for a shape. Note: can return null for certain types of shapes which don't have 3d properties. Read-only [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Gets unique shape identifier in presentation scope. Read-only UInt32. See also [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid) for getting unique shape identifier in slide scope. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Returns or sets the width of the shape. Read/write Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Returns or sets the x-coordinate of the upper-left corner of the shape. Read/write Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Returns or sets the y-coordinate of the upper-left corner of the shape. Read/write Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Returns the position of a shape in the z-order. Shapes[0] returns the shape at the back of the z-order, and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order. Read-only Int32. |

## Methods

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Adds a new placeholder if there is no and sets placeholder properties to a specified one. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Returns a basic placeholder shape (shape from the layout and/or master slide that the current shape is inherited from). A null is returned if the current shape is not inherited. |
| [GetThumbnail](../../aspose.slides/shape/getthumbnail)() | Returns shape thumbnail. ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [GetThumbnail](../../aspose.slides/shape/getthumbnail)(ShapeThumbnailBounds, float, float) | Returns shape thumbnail. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Defines that this shape isn't a placeholder. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Saves content of Shape as SVG file. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Saves content of Shape as SVG file. |

### See Also

* class [GraphicalObject](../../aspose.slides/graphicalobject)
* interface [ISmartArt](../ismartart)
* namespace [Aspose.Slides.SmartArt](../../aspose.slides.smartart)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
