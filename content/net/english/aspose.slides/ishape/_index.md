---
title: IShape
second_title: Aspose.Sildes for .NET API Reference
description: Represents a shape on a slide.
type: docs
weight: 6790
url: /aspose.slides/ishape/
---

## IShape interface

Represents a shape on a slide.

```csharp
public interface IShape : IHyperlinkContainer, ISlideComponent
```

## Properties

| Name | Description |
| --- | --- |
| [AlternativeText](../../aspose.slides/ishape/alternativetext) { get; set; } | Returns or sets the alternative text associated with a shape. Read/write String. |
| [AlternativeTextTitle](../../aspose.slides/ishape/alternativetexttitle) { get; set; } | Returns or sets the title of alternative text associated with a shape. Read/write String. |
| [AsIHyperlinkContainer](../../aspose.slides/ishape/asihyperlinkcontainer) { get; } | Allows to get base IHyperlinkContainer interface. Read-only [`IHyperlinkContainer`](../ihyperlinkcontainer). |
| [AsISlideComponent](../../aspose.slides/ishape/asislidecomponent) { get; } | Allows to get base ISlideComponent interface. Read-only [`ISlideComponent`](../islidecomponent). |
| [BlackWhiteMode](../../aspose.slides/ishape/blackwhitemode) { get; set; } | Property specifies how a shape will render in black-and-white display mode.. Read/write [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/ishape/connectionsitecount) { get; } | Returns the number of connection sites on the shape. Read-only Int32. |
| [CustomData](../../aspose.slides/ishape/customdata) { get; } | Returns the shape's custom data. Read-only [`ICustomData`](../icustomdata). |
| [EffectFormat](../../aspose.slides/ishape/effectformat) { get; } | Returns the EffectFormat object which contains pixel effects applied to a shape. Read-only [`IEffectFormat`](../ieffectformat). |
| [FillFormat](../../aspose.slides/ishape/fillformat) { get; } | Returns the FillFormat object that contains fill formatting properties for a shape. Read-only [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/ishape/frame) { get; set; } | Returns or sets the shape frame's properties. Read/write [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/ishape/height) { get; set; } | Gets or sets the height of the shape, measured in points. Read/write Single. |
| [Hidden](../../aspose.slides/ishape/hidden) { get; set; } | Determines whether the shape is hidden. Read/write Boolean. |
| [IsDecorative](../../aspose.slides/ishape/isdecorative) { get; set; } | Gets or sets 'Mark as decorative' option Reed/write Boolean. |
| [IsGrouped](../../aspose.slides/ishape/isgrouped) { get; } | Determines whether the shape is grouped. Read-only Boolean. |
| [IsTextHolder](../../aspose.slides/ishape/istextholder) { get; } | Determines whether the shape is TextHolder. Read-only Boolean. |
| [LineFormat](../../aspose.slides/ishape/lineformat) { get; } | Returns the LineFormat object that contains line formatting properties for a shape. Read-only [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/ishape/name) { get; set; } | Returns or sets the name of a shape. Read/write String. |
| [OfficeInteropShapeId](../../aspose.slides/ishape/officeinteropshapeid) { get; } | Returns a slide-scoped unique identifier that remains constant for the lifetime of the shape and lets PowerPoint or interop code reliably reference the shape from anywhere in the document. Read-only UInt32. See also [`UniqueId`](./uniqueid). |
| [ParentGroup](../../aspose.slides/ishape/parentgroup) { get; } | Returns parent GroupShape object if shape is grouped. Otherwise returns null. Read-only [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/ishape/placeholder) { get; } | Returns the placeholder for a shape. Read-only [`IPlaceholder`](../iplaceholder). |
| [RawFrame](../../aspose.slides/ishape/rawframe) { get; set; } | Returns or sets the raw shape frame's properties. Read/write [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/ishape/rotation) { get; set; } | Returns or sets the number of degrees the specified shape is rotated around the z-axis. A positive value indicates clockwise rotation; a negative value indicates counterclockwise rotation. Read/write Single. |
| [ShapeLock](../../aspose.slides/ishape/shapelock) { get; } | Returns shape's locks. Read-only [`IBaseShapeLock`](../ibaseshapelock). |
| [ThreeDFormat](../../aspose.slides/ishape/threedformat) { get; } | Returns the ThreeDFormat object that contains line formatting properties for a shape. Read-only [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/ishape/uniqueid) { get; } | Returns an internal, presentation-scoped identifier intended for use by add-ins or other code. Because this value can be reassigned by the user or programmatically, it must not be treated as a persistent unique key. Read-only UInt32. See also [`OfficeInteropShapeId`](./officeinteropshapeid). |
| [Width](../../aspose.slides/ishape/width) { get; set; } | Gets or sets the width of the shape, measured in points. Read/write Single. |
| [X](../../aspose.slides/ishape/x) { get; set; } | Gets or sets the x-coordinate of the shape's upper-left corner, measured in points. Read/write Single. |
| [Y](../../aspose.slides/ishape/y) { get; set; } | Gets or sets the y-coordinate of the shape's upper-left corner, measured in points. Read/write Single. |
| [ZOrderPosition](../../aspose.slides/ishape/zorderposition) { get; } | Returns the position of a shape in the z-order. Shapes[0] returns the shape at the back of the z-order, and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order. Read-only Int32. |

## Methods

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/ishape/addplaceholder)(IPlaceholder) | Adds a new placeholder if there is no and sets placeholder properties to a specified one. |
| [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder)() | Returns a basic placeholder shape (shape from the layout and/or master slide that the current shape is inherited from). A null is returned if the current shape is not inherited. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage)() | Returns shape thumbnail. ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | Returns shape thumbnail. |
| [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder)() | Defines that this shape isn't a placeholder. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg)(Stream) | Saves content of Shape as SVG file. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Saves content of Shape as SVG file. |

### See Also

* interface [IHyperlinkContainer](../ihyperlinkcontainer)
* interface [ISlideComponent](../islidecomponent)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
