---
title: AutoShape
second_title: Aspose.Slides for .NET API 参考
description: 表示自选图形
type: docs
weight: 800
url: /zh/aspose.slides/autoshape/
---
## AutoShape class

表示自选图形。

```csharp
public class AutoShape : GeometryShape, IAutoShape
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | 返回形状调整值的集合。 只读[`IAdjustValueCollection`](../iadjustvaluecollection)。 |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 返回或设置与形状关联的替代文本。 读/写String。 |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 返回或设置与形状关联的替代文本的标题。 读/写String。 |
| [AutoShapeLock](../../aspose.slides/autoshape/autoshapelock) { get; } | 返回 autoshape 的锁。 只读[`IAutoShapeLock`](../iautoshapelock)。 |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 属性指定形状在黑白显示模式下的渲染方式。 读/写[`BlackWhiteMode`](../blackwhitemode)。 |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 返回形状上的连接点数。 只读Int32。 |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 返回形状的自定义数据。 只读[`ICustomData`](../icustomdata)。 |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 返回包含应用于形状的像素效果的 EffectFormat 对象。 注意:对于不具有效果属性的某些类型的形状，可以返回 null。 只读[`IEffectFormat`](../ieffectformat)。 |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | 返回包含形状填充格式属性的 FillFormat 对象。 注意:对于某些没有填充属性的形状，可以返回 null。 只读[`IFillFormat`](../ifillformat)。 |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 返回或设置形状框架的属性。 读/写[`IShapeFrame`](../ishapeframe)。 |
| [Height](../../aspose.slides/shape/height) { get; set; } | 返回或设置形状的高度。 读/写Single。 |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 确定形状是否隐藏。 读/写Boolean。 |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 返回或设置为鼠标单击定义的超链接。 读/写[`IHyperlink`](../ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 返回超链接管理器。 只读[`IHyperlinkManager`](../ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 返回或设置为鼠标悬停定义的超链接。 读/写[`IHyperlink`](../ihyperlink)。 |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 确定形状是否被分组。 只读Boolean。 |
| [IsTextBox](../../aspose.slides/autoshape/istextbox) { get; } | 指定形状是否为文本框。 |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 判断形状是否为TextHolder_PPT。 只读Boolean。 |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 返回包含形状的行格式属性的 LineFormat 对象。 注意:对于某些没有线条属性的形状类型，可以返回 null。 只读[`ILineFormat`](../ilineformat)。 |
| [Name](../../aspose.slides/shape/name) { get; set; } | 返回或设置形状的名称。 不能为空。如果需要，使用空字符串值。 读/写String。 |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 获取幻灯片范围内的唯一形状标识符。 只读UInt32。 另请参见[`UniqueId`](../shape/uniqueid)以获取表示范围内的唯一形状标识符。 |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 如果形状被分组，则返回父 GroupShape 对象。否则返回 null。 只读[`IGroupShape`](../igroupshape)。 |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 返回形状的占位符。如果形状没有占位符，则返回 null。 只读[`IPlaceholder`](../iplaceholder)。 |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 返回幻灯片的父演示文稿。 只读[`IPresentation`](../ipresentation)。 |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 返回或设置原始形状框架的属性。 读/写[`IShapeFrame`](../ishapeframe)。 |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 返回或设置指定形状围绕 z 轴 旋转的度数。正值表示顺时针旋转；负值 表示逆时针旋转。 读/写Single。 |
| [ShapeLock](../../aspose.slides/autoshape/shapelock) { get; } | 返回形状的锁。 只读[`IAutoShapeLock`](../iautoshapelock)。 (2 properties) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | 返回形状的样式对象。 只读[`IShapeStyle`](../ishapestyle)。 |
| virtual [ShapeType](../../aspose.slides/geometryshape/shapetype) { get; set; } | 返回或设置几何预设类型。 注意:在更改值时，所有调整值都将重置为其默认值。 读/写[`ShapeType`](../shapetype)。 |
| [Slide](../../aspose.slides/shape/slide) { get; } | 返回形状的父幻灯片。 只读[`IBaseSlide`](../ibaseslide)。 |
| [TextFrame](../../aspose.slides/autoshape/textframe) { get; } | 返回自选图形的 TextFrame 对象。 只读[`ITextFrame`](../itextframe)。 |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 返回对形状产生 3d 效果的 ThreeDFormat 对象。 注意:对于没有 3d 属性的某些类型的形状，可以返回 null。 只读[`IThreeDFormat`](../ithreedformat)。 |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 获取表示范围内的唯一形状标识符。 只读UInt32。 另请参见[`OfficeInteropShapeId`](../shape/officeinteropshapeid)以获取幻灯片范围内的唯一形状标识符。 |
| [UseBackgroundFill](../../aspose.slides/autoshape/usebackgroundfill) { get; set; } | 确定此自选图形是否应使用幻灯片的背景填充而不是由样式或填充格式指定。 读/写Boolean。 |
| [Width](../../aspose.slides/shape/width) { get; set; } | 返回或设置形状的宽度。 读/写Single。 |
| [X](../../aspose.slides/shape/x) { get; set; } | 返回或设置形状左上角的 x 坐标。 读/写Single。 |
| [Y](../../aspose.slides/shape/y) { get; set; } | 返回或设置形状左上角的 y 坐标。 读/写Single。 |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | 返回形状在 z 顺序中的位置。 Shapes[0] 返回 z 顺序后面的形状， 和 Shapes[Shapes.Count - 1] 返回 z 顺序前面的形状. 只读Int32。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 如果没有，则添加新的占位符并将占位符属性设置为指定的占位符。 |
| virtual [AddTextFrame](../../aspose.slides/autoshape/addtextframe)(string) | 将新的 TextFrame 添加到形状。 如果形状已经有 TextFrame 则只需更改其文本。 |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | 创建并返回形状元素的数组。 |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | 返回几何形状路径的副本。 坐标相对于形状的左上角。 |
| [GetThumbnail](../../aspose.slides/shape/getthumbnail)() | 返回形状缩略图。 ShapeThumbnailBounds.Shape 形状缩略图边界类型默认使用。 |
| [GetThumbnail](../../aspose.slides/shape/getthumbnail)(ShapeThumbnailBounds, float, float) | 返回形状缩略图。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 定义此形状不是占位符。 |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | 从[`IGeometryPath`](../igeometrypath)对象更新形状几何。坐标必须相对于形状的左 上角。 将形状的类型（[`ShapeType`](../geometryshape/shapetype)）更改为Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | 从[`IGeometryPath`](../igeometrypath)数组更新形状几何。坐标必须相对于形状的左 上角。 将形状的类型（[`ShapeType`](../geometryshape/shapetype)）更改为Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | 将 Shape 的内容保存为 SVG 文件。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | 将 Shape 的内容保存为 SVG 文件。 |

### 也可以看看

* class [GeometryShape](../geometryshape)
* interface [IAutoShape](../iautoshape)
* 命名空间 [Aspose.Slides](../../aspose.slides)
* 部件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
