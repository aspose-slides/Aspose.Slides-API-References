---
title: GroupShape
second_title: Aspose.Sildes .NET API 参考
description: 表示幻灯片上一组形状。
type: docs
weight: 5090
url: /zh/aspose.slides/groupshape/
---
## GroupShape 类

表示幻灯片上一组形状。

```csharp
public class GroupShape : Shape, IGroupShape
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 返回或设置与形状关联的替代文本。可读/可写 String。 |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 返回或设置与形状关联的替代文本的标题。可读/可写 String。 |
| [AsIShape](../../aspose.slides/groupshape/asishape) { get; } | 允许获取基础 IShape 接口。只读 [`IShape`](../ishape)。 |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 属性指定形状在黑白显示模式下的渲染方式。可读/可写 [`BlackWhiteMode`](../blackwhitemode)。 |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 返回形状上的连接点数量。只读 Int32。 |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 返回形状的自定义数据。只读 [`ICustomData`](../icustomdata)。 |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 返回包含像素效果的 EffectFormat 对象。注意：对于某些没有效果属性的形状类型可能返回 null。只读 [`IEffectFormat`](../ieffectformat)。 |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | 返回包含填充格式属性的 FillFormat 对象。注意：对于某些没有填充属性的形状类型可能返回 null。只读 [`IFillFormat`](../ifillformat)。 |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 返回或设置形状框架的属性。可读/可写 [`IShapeFrame`](../ishapeframe)。 |
| [GroupShapeLock](../../aspose.slides/groupshape/groupshapelock) { get; } | 返回形状的锁定状态。只读 [`IGroupShapeLock`](../igroupshapelock)。 |
| [Height](../../aspose.slides/shape/height) { get; set; } | 获取或设置形状的高度，单位为磅。可读/可写 Single。 |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 确定形状是否隐藏。可读/可写 Boolean。 |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 返回或设置鼠标单击时定义的超链接。可读/可写 [`IHyperlink`](../ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 返回超链接管理器。只读 [`IHyperlinkManager`](../ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 返回或设置鼠标悬停时定义的超链接。可读/可写 [`IHyperlink`](../ihyperlink)。 |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 获取或设置“标记为装饰性”选项。可读/可写 Boolean。 |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 确定形状是否已分组。只读 Boolean。 |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 确定形状是否为 TextHolder_PPT。只读 Boolean。 |
| override [LineFormat](../../aspose.slides/groupshape/lineformat) { get; } | 返回包含线条格式属性的 LineFormat 对象。注意：对于 GroupShape 对象返回 null，因为它们没有线条属性。只读 [`ILineFormat`](../ilineformat)。 |
| [Name](../../aspose.slides/shape/name) { get; set; } | 返回或设置形状的名称。不能为空。需要时使用空字符串。可读/可写 String。 |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 返回在幻灯片范围内唯一且在形状生命周期内保持不变的标识符，可用于在文档任意位置可靠引用形状。只读 UInt32。另请参阅 [`UniqueId`](../shape/uniqueid)。 |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 如果形状已分组，返回父 GroupShape 对象；否则返回 null。只读 [`IGroupShape`](../igroupshape)。 |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 返回形状的占位符。如果形状没有占位符则返回 null。只读 [`IPlaceholder`](../iplaceholder)。 |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 返回幻灯片的父演示文稿。只读 [`IPresentation`](../ipresentation)。 |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 返回或设置原始形状框架的属性。可读/可写 [`IShapeFrame`](../ishapeframe)。 |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 返回或设置指定形状围绕 Z 轴旋转的角度（度）。正值表示顺时针旋转，负值表示逆时针旋转。可读/可写 Single。 |
| [ShapeLock](../../aspose.slides/groupshape/shapelock) { get; } | 返回形状的锁定状态。只读 [`IGroupShapeLock`](../igroupshapelock)。（2 个属性） |
| [Shapes](../../aspose.slides/groupshape/shapes) { get; } | 返回组内形状的集合。只读 [`IShapeCollection`](../ishapecollection)。 |
| [Slide](../../aspose.slides/shape/slide) { get; } | 返回形状所在的父幻灯片。只读 [`IBaseSlide`](../ibaseslide)。 |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 返回包含 3D 效果属性的 ThreeDFormat 对象。注意：对于某些没有 3D 属性的形状类型可能返回 null。只读 [`IThreeDFormat`](../ithreedformat)。 |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 返回供加载项或其他代码使用的内部演示文稿范围标识符。由于该值可能被用户或程序重新分配，不能视为持久唯一键。只读 UInt32。另请参阅 [`OfficeInteropShapeId`](../shape/officeinteropshapeid)。 |
| [Width](../../aspose.slides/shape/width) { get; set; } | 获取或设置形状的宽度，单位为磅。可读/可写 Single。 |
| [X](../../aspose.slides/shape/x) { get; set; } | 获取或设置形状左上角的 X 坐标，单位为磅。可读/可写 Single。 |
| [Y](../../aspose.slides/shape/y) { get; set; } | 获取或设置形状左上角的 Y 坐标，单位为磅。可读/可写 Single。 |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | 返回形状在 Z 顺序中的位置。Shapes[0] 返回位于 Z 顺序最底层的形状，Shapes[Shapes.Count - 1] 返回位于最前面的形状。只读 Int32。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 如果不存在占位符，则添加新占位符并将占位符属性设置为指定的占位符。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 返回基本占位符形状（布局或母版幻灯片中当前形状继承的形状）。如果当前形状未继承，则返回 null。 |
| [GetImage](../../aspose.slides/shape/getimage)() | 返回形状缩略图。默认使用 ShapeThumbnailBounds.Shape 形状缩略图边界类型。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 返回形状缩略图。 |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | 获取基于已渲染内容计算得到的形状视觉边界。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 定义此形状不是占位符。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | 将形状内容另存为 SVG 文件。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | 将形状内容另存为 SVG 文件。 |

### 另见

* 类 [Shape](../shape)
* 接口 [IGroupShape](../igroupshape)
* 命名空间 [Aspose.Slides](../../aspose.slides)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->