---
title: ZoomObject
second_title: Aspose.Sildes for .NET API Reference
description: 代表幻灯片中的缩放对象。
type: docs
weight: 11560
url: /zh/aspose.slides/zoomobject/
---

## ZoomObject class

代表幻灯片中的缩放对象。

```csharp
public class ZoomObject : GraphicalObject, IZoomObject
```

## Properties

| Name | Description |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 返回或设置与形状相关的替代文本。可读/可写字符串。 |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 返回或设置与形状相关的替代文本标题。可读/可写字符串。 |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 属性指定形状在黑白显示模式下的渲染方式。可读/可写 [`BlackWhiteMode`](../blackwhitemode)。 |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 返回形状上的连接站点数量。只读Int32。 |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 返回形状的自定义数据。只读 [`ICustomData`](../icustomdata)。 |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 返回包含应用于形状的像素效果的EffectFormat对象。注意：对于某些类型的没有效果属性的形状可以返回null。只读 [`IEffectFormat`](../ieffectformat)。 |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | 返回包含形状填充格式属性的FillFormat对象。注意：对于某些类型的没有填充属性的形状可以返回null。只读 [`IFillFormat`](../ifillformat)。 |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 返回或设置形状框架的属性。可读/可写 [`IShapeFrame`](../ishapeframe)。 |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | 返回形状的锁定。只读 [`IGraphicalObjectLock`](../igraphicalobjectlock)。 |
| [Height](../../aspose.slides/shape/height) { get; set; } | 返回或设置形状的高度。可读/可写单精度浮点数。 |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 决定形状是否隐藏。可读/可写布尔值。 |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 返回或设置为鼠标点击定义的超链接。可读/可写 [`IHyperlink`](../ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 返回超链接管理器。只读 [`IHyperlinkManager`](../ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 返回或设置为鼠标悬停定义的超链接。可读/可写 [`IHyperlink`](../ihyperlink)。 |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | 获取或设置缩放对象的图像类型。可读/可写 [`ZoomImageType`](../zoomimagetype)。默认值：预览 |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 获取或设置“标记为装饰’’选项。可读/可写布尔值。 |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 确定形状是否分组。只读布尔值。 |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 确定形状是否为TextHolder_PPT。只读布尔值。 |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 返回包含形状线条格式属性的LineFormat对象。注意：对于某些类型的没有线条属性的形状可以返回null。只读 [`ILineFormat`](../ilineformat)。 |
| [Name](../../aspose.slides/shape/name) { get; set; } | 返回或设置形状的名称。必须不为null。如果需要，请使用空字符串值。可读/可写字符串。 |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 获取在幻灯片范围内的唯一形状标识符。只读UInt32。有关在演示文稿范围内获取唯一形状标识符，另见 [`UniqueId`](../shape/uniqueid)。 |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 如果形状是分组的，返回父GroupShape对象。否则返回null。只读 [`IGroupShape`](../igroupshape)。 |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 返回形状的占位符。如果形状没有占位符，则返回null。只读 [`IPlaceholder`](../iplaceholder)。 |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 返回幻灯片的父演示文稿。只读 [`IPresentation`](../ipresentation)。 |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 返回或设置原始形状框架的属性。可读/可写 [`IShapeFrame`](../ishapeframe)。 |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | 获取或设置幻灯片放映中的导航行为。可读/可写布尔值。默认值：false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 返回或设置指定形状围绕z轴旋转的度数。正值表示顺时针旋转；负值表示逆时针旋转。可读/可写单精度浮点数。 |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | 返回形状的锁定。只读 [`IGraphicalObjectLock`](../igraphicalobjectlock)。 (2个属性) |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | 获取或设置一个值，该值指示缩放是否使用目标幻灯片的背景。可读/可写布尔值。默认值：true |
| [Slide](../../aspose.slides/shape/slide) { get; } | 返回形状的父幻灯片。只读 [`IBaseSlide`](../ibaseslide)。 |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 返回包含形状的3D效果属性的ThreeDFormat对象。注意：对于某些类型的没有3D属性的形状可以返回null。只读 [`IThreeDFormat`](../ithreedformat)。 |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | 获取或设置缩放与幻灯片之间的过渡持续时间。可读/可写单精度浮点数。默认值：1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 获取在演示文稿范围内的唯一形状标识符。只读UInt32。有关在幻灯片范围内获取唯一形状标识符，另见 [`OfficeInteropShapeId`](../shape/officeinteropshapeid)。 |
| [Width](../../aspose.slides/shape/width) { get; set; } | 返回或设置形状的宽度。可读/可写单精度浮点数。 |
| [X](../../aspose.slides/shape/x) { get; set; } | 返回或设置形状左上角的x坐标。可读/可写单精度浮点数。 |
| [Y](../../aspose.slides/shape/y) { get; set; } | 返回或设置形状左上角的y坐标。可读/可写单精度浮点数。 |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | 获取或设置缩放对象的图像。可读/可写 [`IPPImage`](../ippimage)。 |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | 返回形状在z顺序中的位置。Shapes[0] 返回z顺序底部的形状，Shapes[Shapes.Count - 1] 返回z顺序顶部的形状。只读Int32。 |

## Methods

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 如果没有占位符，则添加一个新的占位符，并将占位符属性设置为指定的属性。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 返回基本占位符形状（当前形状所继承的来自布局和/或母版幻灯片的形状）。如果当前形状未继承，则返回null。 |
| [GetImage](../../aspose.slides/shape/getimage)() | 返回形状缩略图。默认情况下使用ShapeThumbnailBounds.Shape形状缩略图边界类型。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 返回形状缩略图。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 定义该形状不是占位符。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | 将形状的内容保存为SVG文件。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | 将形状的内容保存为SVG文件。 |

### See Also

* class [GraphicalObject](../graphicalobject)
* interface [IZoomObject](../izoomobject)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)