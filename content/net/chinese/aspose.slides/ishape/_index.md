---  
title: IShape
second_title: Aspose.Sildes for .NET API Reference  
description: 表示幻灯片上的形状。
type: docs
weight: 6730  
url: /zh/aspose.slides/ishape/
---  

## IShape interface  

表示幻灯片上的形状。  

```csharp  
public interface IShape : IHyperlinkContainer, ISlideComponent  
```  

## Properties  

| Name | Description |  
| --- | --- |  
| [AlternativeText](../../aspose.slides/ishape/alternativetext) { get; set; } | 返回或设置与形状相关的替代文本。可读写字符串。 |  
| [AlternativeTextTitle](../../aspose.slides/ishape/alternativetexttitle) { get; set; } | 返回或设置与形状相关的替代文本标题。可读写字符串。 |  
| [AsIHyperlinkContainer](../../aspose.slides/ishape/asihyperlinkcontainer) { get; } | 允许获取基本的 IHyperlinkContainer 接口。只读 [`IHyperlinkContainer`](../ihyperlinkcontainer)。 |  
| [AsISlideComponent](../../aspose.slides/ishape/asislidecomponent) { get; } | 允许获取基本的 ISlideComponent 接口。只读 [`ISlideComponent`](../islidecomponent)。 |  
| [BlackWhiteMode](../../aspose.slides/ishape/blackwhitemode) { get; set; } | 属性指定形状在黑白显示模式下的渲染方式。可读写 [`BlackWhiteMode`](../blackwhitemode)。 |  
| [ConnectionSiteCount](../../aspose.slides/ishape/connectionsitecount) { get; } | 返回形状上的连接点数量。只读 Int32。 |  
| [CustomData](../../aspose.slides/ishape/customdata) { get; } | 返回形状的自定义数据。只读 [`ICustomData`](../icustomdata)。 |  
| [EffectFormat](../../aspose.slides/ishape/effectformat) { get; } | 返回包含应用于形状的像素效果的 EffectFormat 对象。只读 [`IEffectFormat`](../ieffectformat)。 |  
| [FillFormat](../../aspose.slides/ishape/fillformat) { get; } | 返回包含形状填充格式属性的 FillFormat 对象。只读 [`IFillFormat`](../ifillformat)。 |  
| [Frame](../../aspose.slides/ishape/frame) { get; set; } | 返回或设置形状框架的属性。可读写 [`IShapeFrame`](../ishapeframe)。 |  
| [Height](../../aspose.slides/ishape/height) { get; set; } | 返回或设置形状的高度。可读写单精度浮点数。 |  
| [Hidden](../../aspose.slides/ishape/hidden) { get; set; } | 确定形状是否隐藏。可读写布尔值。 |  
| [IsDecorative](../../aspose.slides/ishape/isdecorative) { get; set; } | 获取或设置“标记为装饰”的选项。可读写布尔值。 |  
| [IsGrouped](../../aspose.slides/ishape/isgrouped) { get; } | 确定形状是否分组。只读布尔值。 |  
| [IsTextHolder](../../aspose.slides/ishape/istextholder) { get; } | 确定形状是否为文本框。只读布尔值。 |  
| [LineFormat](../../aspose.slides/ishape/lineformat) { get; } | 返回包含形状线条格式属性的 LineFormat 对象。只读 [`ILineFormat`](../ilineformat)。 |  
| [Name](../../aspose.slides/ishape/name) { get; set; } | 返回或设置形状的名称。可读写字符串。 |  
| [OfficeInteropShapeId](../../aspose.slides/ishape/officeinteropshapeid) { get; } | 获取幻灯片范围内的唯一形状标识符。只读 UInt32。有关在演示范围获取唯一形状标识符，请参见 [`UniqueId`](./uniqueid)。 |  
| [ParentGroup](../../aspose.slides/ishape/parentgroup) { get; } | 如果形状是分组的，则返回父 GroupShape 对象。否则返回 null。只读 [`IGroupShape`](../igroupshape)。 |  
| [Placeholder](../../aspose.slides/ishape/placeholder) { get; } | 返回形状的占位符。只读 [`IPlaceholder`](../iplaceholder)。 |  
| [RawFrame](../../aspose.slides/ishape/rawframe) { get; set; } | 返回或设置原始形状框架的属性。可读写 [`IShapeFrame`](../ishapeframe)。 |  
| [Rotation](../../aspose.slides/ishape/rotation) { get; set; } | 返回或设置指定形状围绕 z 轴旋转的度数。正值表示顺时针旋转；负值表示逆时针旋转。可读写单精度浮点数。 |  
| [ShapeLock](../../aspose.slides/ishape/shapelock) { get; } | 返回形状的锁定。只读 [`IBaseShapeLock`](../ibaseshapelock)。 |  
| [ThreeDFormat](../../aspose.slides/ishape/threedformat) { get; } | 返回包含形状线条格式属性的 ThreeDFormat 对象。只读 [`IThreeDFormat`](../ithreedformat)。 |  
| [UniqueId](../../aspose.slides/ishape/uniqueid) { get; } | 获取演示范围内的唯一形状标识符。只读 UInt32。有关在幻灯片范围获取唯一形状标识符，请参见 [`OfficeInteropShapeId`](./officeinteropshapeid)。 |  
| [Width](../../aspose.slides/ishape/width) { get; set; } | 返回或设置形状的宽度。可读写单精度浮点数。 |  
| [X](../../aspose.slides/ishape/x) { get; set; } | 返回或设置形状左上角的 x 坐标。可读写单精度浮点数。 |  
| [Y](../../aspose.slides/ishape/y) { get; set; } | 返回或设置形状左上角的 y 坐标。可读写单精度浮点数。 |  
| [ZOrderPosition](../../aspose.slides/ishape/zorderposition) { get; } | 返回形状在 z 顺序中的位置。Shapes[0] 返回 z 顺序最底部的形状，Shapes[Shapes.Count - 1] 返回 z 顺序最顶部的形状。只读 Int32。 |  

## Methods  

| Name | Description |  
| --- | --- |  
| [AddPlaceholder](../../aspose.slides/ishape/addplaceholder)(IPlaceholder) | 如果没有则添加新的占位符，并将占位符属性设置为指定的属性。 |  
| [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder)() | 返回基本占位符形状（从布局和/或母版幻灯片继承的当前形状的形状）。如果当前形状未继承，则返回 null。 |  
| [GetImage](../../aspose.slides/ishape/getimage#getimage)() | 返回形状缩略图。默认使用 ShapeThumbnailBounds.Shape 形状缩略图边界类型。 |  
| [GetImage](../../aspose.slides/ishape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | 返回形状缩略图。 |  
| [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder)() | 定义该形状不是占位符。 |  
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg)(Stream) | 将形状的内容保存为 SVG 文件。 |  
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | 将形状的内容保存为 SVG 文件。 |  

### See Also  

* interface [IHyperlinkContainer](../ihyperlinkcontainer)  
* interface [ISlideComponent](../islidecomponent)  
* namespace [Aspose.Slides](../../aspose.slides)  
* assembly [Aspose.Slides](../../)  

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->  