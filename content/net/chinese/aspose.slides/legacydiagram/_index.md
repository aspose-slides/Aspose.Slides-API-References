---
title: LegacyDiagram
second_title: Aspose.Sildes for .NET API 参考
description: 表示一个传统图表对象。
type: docs
weight: 7670
url: /zh/aspose.slides/legacydiagram/
---
## LegacyDiagram 类

表示一个传统图表对象。

```csharp
public class LegacyDiagram : GraphicalObject, ILegacyDiagram
```

## 属性

| Name | Description |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 返回或设置与形状关联的替代文本。可读/可写 String。 |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 返回或设置与形状关联的替代文本的标题。可读/可写 String。 |
| [AsIGraphicalObject](../../aspose.slides/legacydiagram/asigraphicalobject) { get; } | 允许获取基本 IGraphicalObject 接口。只读 [`IGraphicalObject`](../igraphicalobject)。 |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 属性指定形状在黑白显示模式下的渲染方式。可读/可写 [`BlackWhiteMode`](../blackwhitemode)。 |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 返回形状上的连接点数量。只读 Int32。 |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 返回形状的自定义数据。只读 [`ICustomData`](../icustomdata)。 |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 返回包含应用于形状的像素效果的 EffectFormat 对象。注意：对于某些没有效果属性的形状，可返回 null。只读 [`IEffectFormat`](../ieffectformat)。 |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | 返回包含形状填充格式属性的 FillFormat 对象。注意：对于某些没有填充属性的形状，可返回 null。只读 [`IFillFormat`](../ifillformat)。 |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 返回或设置形状框架的属性。可读/可写 [`IShapeFrame`](../ishapeframe)。 |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | 返回形状的锁定。只读 [`IGraphicalObjectLock`](../igraphicalobjectlock)。 |
| [Height](../../aspose.slides/shape/height) { get; set; } | 获取或设置形状的高度（以点为单位）。可读/可写 Single。 |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 确定形状是否隐藏。可读/可写 Boolean。 |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 返回或设置鼠标单击时定义的超链接。可读/可写 [`IHyperlink`](../ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 返回超链接管理器。只读 [`IHyperlinkManager`](../ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 返回或设置鼠标悬停时定义的超链接。可读/可写 [`IHyperlink`](../ihyperlink)。 |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 获取或设置 “标记为装饰” 选项。可读/可写 Boolean。 |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 确定形状是否已分组。只读 Boolean。 |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 确定形状是否为 TextHolder_PPT。只读 Boolean。 |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 返回包含形状线条格式属性的 LineFormat 对象。注意：对于某些没有线条属性的形状，可返回 null。只读 [`ILineFormat`](../ilineformat)。 |
| [Name](../../aspose.slides/shape/name) { get; set; } | 返回或设置形状的名称。不能为空。如有需要可使用空字符串。可读/可写 String。 |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 返回作用于幻灯片范围的唯一标识符，在形状的生命周期内保持不变，允许 PowerPoint 或互操作代码在文档任何位置可靠地引用该形状。只读 UInt32。另见 [`UniqueId`](../shape/uniqueid)。 |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 如果形状已分组，则返回父 GroupShape 对象；否则返回 null。只读 [`IGroupShape`](../igroupshape)。 |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 返回形状的占位符。如果形状没有占位符，则返回 null。只读 [`IPlaceholder`](../iplaceholder)。 |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 返回幻灯片的父演示文稿。只读 [`IPresentation`](../ipresentation)。 |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 返回或设置原始形状框架的属性。可读/可写 [`IShapeFrame`](../ishapeframe)。 |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 返回或设置指定形状绕 z 轴旋转的度数。正值表示顺时针旋转；负值表示逆时针旋转。可读/可写 Single。 |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | 返回形状的锁定。只读 [`IGraphicalObjectLock`](../igraphicalobjectlock)。（2 个属性） |
| [Slide](../../aspose.slides/shape/slide) { get; } | 返回形状的父幻灯片。只读 [`IBaseSlide`](../ibaseslide)。 |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 返回包含形状 3D 效果属性的 ThreeDFormat 对象。注意：对于某些没有 3D 属性的形状，可返回 null。只读 [`IThreeDFormat`](../ithreedformat)。 |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 返回内部、针对演示文稿范围的标识符，供插件或其他代码使用。由于该值可以被用户或程序重新分配，不应将其视为持久唯一键。只读 UInt32。另见 [`OfficeInteropShapeId`](../shape/officeinteropshapeid)。 |
| [Width](../../aspose.slides/shape/width) { get; set; } | 获取或设置形状的宽度（以点为单位）。可读/可写 Single。 |
| [X](../../aspose.slides/shape/x) { get; set; } | 获取或设置形状左上角的 X 坐标（以点为单位）。可读/可写 Single。 |
| [Y](../../aspose.slides/shape/y) { get; set; } | 获取或设置形状左上角的 Y 坐标（以点为单位）。可读/可写 Single。 |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | 返回形状在 Z 顺序中的位置。Shapes[0] 返回 Z 顺序最靠后的形状，Shapes[Shapes.Count - 1] 返回最前面的形状。只读 Int32。 |

## 方法

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 在不存在占位符时添加新占位符，并将占位符属性设置为指定的占位符。 |
| [ConvertToGroupShape](../../aspose.slides/legacydiagram/converttogroupshape)() | 将传统图表转换为可编辑的组形状。创建的 GroupShape 对象会在相同位置添加到父组形状中。 |
| [ConvertToSmartArt](../../aspose.slides/legacydiagram/converttosmartart)() | 将传统图表转换为可编辑的 SmartArt 对象。创建的 SmartArt 对象会在相同位置添加到父组形状中。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 返回基本占位符形状（从布局和/或母版幻灯片继承的形状）。如果当前形状未继承，则返回 null。 |
| [GetImage](../../aspose.slides/shape/getimage)() | 返回形状缩略图。默认使用 ShapeThumbnailBounds.Shape 形状缩略图边界类型。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 返回形状缩略图。 |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | 获取根据渲染内容计算的形状可视边界。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 定义此形状不是占位符。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | 将形状内容保存为 SVG 文件。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | 将形状内容保存为 SVG 文件。 |

### 另请参见

* 类 [GraphicalObject](../graphicalobject)
* 接口 [ILegacyDiagram](../ilegacydiagram)
* 命名空间 [Aspose.Slides](../../aspose.slides)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->