---
title: OleObjectFrame
second_title: Aspose.Sildes for .NET API 参考
description: 表示幻灯片上的 OLE 对象。
type: docs
weight: 9250
url: /zh/aspose.slides/oleobjectframe/
---
## OleObjectFrame 类

表示幻灯片上的 OLE 对象。

```csharp
public class OleObjectFrame : GraphicalObject, IOleObjectFrame
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 返回或设置与形状关联的替代文本。可读写 String。 |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 返回或设置与形状关联的替代文本的标题。可读写 String。 |
| [AsIGraphicalObject](../../aspose.slides/oleobjectframe/asigraphicalobject) { get; } | 允许获取基础 IGraphicalObject 接口。只读 [`IGraphicalObject`](../igraphicalobject)。 |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 属性指定形状在黑白显示模式下的渲染方式。可读写 [`BlackWhiteMode`](../blackwhitemode)。 |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 返回形状上的连接点数量。只读 Int32。 |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 返回形状的自定义数据。只读 [`ICustomData`](../icustomdata)。 |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 返回包含应用于形状的像素效果的 EffectFormat 对象。注意：对于某些没有效果属性的形状，可能返回 null。只读 [`IEffectFormat`](../ieffectformat)。 |
| [EmbeddedData](../../aspose.slides/oleobjectframe/embeddeddata) { get; } | 获取或设置有关 OLE 嵌入数据的信息。可读写 [`IOleEmbeddedDataInfo`](../ioleembeddeddatainfo)。 |
| [EmbeddedFileLabel](../../aspose.slides/oleobjectframe/embeddedfilelabel) { get; } | 返回嵌入 OLE 对象的文件名 |
| [EmbeddedFileName](../../aspose.slides/oleobjectframe/embeddedfilename) { get; } | 返回嵌入 OLE 对象的路径 |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | 返回包含形状填充格式属性的 FillFormat 对象。注意：对于某些没有填充属性的形状，可能返回 null。只读 [`IFillFormat`](../ifillformat)。 |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 返回或设置形状框架的属性。可读写 [`IShapeFrame`](../ishapeframe)。 |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | 返回形状的锁定状态。只读 [`IGraphicalObjectLock`](../igraphicalobjectlock)。 |
| [Height](../../aspose.slides/shape/height) { get; set; } | 获取或设置形状的高度，单位为点。可读写 Single。 |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 确定形状是否隐藏。可读写 Boolean。 |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 返回或设置鼠标单击时定义的超链接。可读写 [`IHyperlink`](../ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 返回超链接管理器。只读 [`IHyperlinkManager`](../ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 返回或设置鼠标悬停时定义的超链接。可读写 [`IHyperlink`](../ihyperlink)。 |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 获取或设置 “Mark as decorative” 选项 Reed/write Boolean。 |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 确定形状是否已分组。只读 Boolean。 |
| [IsObjectIcon](../../aspose.slides/oleobjectframe/isobjecticon) { get; set; } | 确定对象是否以图标形式可见。可读写 Boolean。 |
| [IsObjectLink](../../aspose.slides/oleobjectframe/isobjectlink) { get; } | 确定对象是否链接到外部文件。只读 Boolean。 |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 确定形状是否为 TextHolder_PPT。只读 Boolean。 |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 返回包含形状线条格式属性的 LineFormat 对象。注意：对于某些没有线条属性的形状，可能返回 null。只读 [`ILineFormat`](../ilineformat)。 |
| [LinkFileName](../../aspose.slides/oleobjectframe/linkfilename) { get; } | 返回已链接文件的完整路径。将使用短文件名。只读 String。 |
| [LinkPathLong](../../aspose.slides/oleobjectframe/linkpathlong) { get; set; } | 返回已链接文件的完整路径。将使用长文件名。可读写 String。 |
| [LinkPathRelative](../../aspose.slides/oleobjectframe/linkpathrelative) { get; } | 如果存在，则返回已链接文件的相对路径；否则返回空字符串。只读 String。 |
| [Name](../../aspose.slides/shape/name) { get; set; } | 返回或设置形状的名称。不能为空。如有需要请使用空字符串。可读写 String。 |
| [ObjectName](../../aspose.slides/oleobjectframe/objectname) { get; set; } | 返回或设置对象的名称。可读写 String。 |
| [ObjectProgId](../../aspose.slides/oleobjectframe/objectprogid) { get; set; } | 返回对象的 ProgID。只读 String。 |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 返回一个在幻灯片范围内唯一的标识符，在形状的整个生命周期内保持不变，允许 PowerPoint 或互操作代码在文档任何位置可靠地引用该形状。只读 UInt32。另请参见 [`UniqueId`](../shape/uniqueid)。 |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 如果形状已分组，则返回父 GroupShape 对象。否则返回 null。只读 [`IGroupShape`](../igroupshape)。 |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 返回形状的占位符。如果形状没有占位符，则返回 null。只读 [`IPlaceholder`](../iplaceholder)。 |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 返回幻灯片的父演示文稿。只读 [`IPresentation`](../ipresentation)。 |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 返回或设置原始形状框架的属性。可读写 [`IShapeFrame`](../ishapeframe)。 |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 返回或设置指定形状绕 z 轴旋转的角度（度数）。正值表示顺时针旋转；负值表示逆时针旋转。可读写 Single。 |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | 返回形状的锁定状态。只读 [`IGraphicalObjectLock`](../igraphicalobjectlock)。（2 个属性） |
| [Slide](../../aspose.slides/shape/slide) { get; } | 返回形状的父幻灯片。只读 [`IBaseSlide`](../ibaseslide)。 |
| [SubstitutePictureFormat](../../aspose.slides/oleobjectframe/substitutepictureformat) { get; } | 返回 OleObject 图像填充属性对象。只读 [`IPictureFillFormat`](../ipicturefillformat)。 |
| [SubstitutePictureTitle](../../aspose.slides/oleobjectframe/substitutepicturetitle) { get; set; } | 返回或设置 OleObject 图标的标题。可读写 String。 |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 返回包含形状 3D 效果属性的 ThreeDFormat 对象。注意：对于某些没有 3D 属性的形状，可能返回 null。只读 [`IThreeDFormat`](../ithreedformat)。 |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 返回供加载项或其他代码使用的内部、针对演示文稿范围的标识符。由于此值可能被用户或程序重新分配，不能视为持久唯一键。只读 UInt32。另请参见 [`OfficeInteropShapeId`](../shape/officeinteropshapeid)。 |
| [UpdateAutomatic](../../aspose.slides/oleobjectframe/updateautomatic) { get; set; } | 确定在打开或打印演示文稿时是否自动更新已链接的嵌入对象。可读写 Boolean。 |
| [Width](../../aspose.slides/shape/width) { get; set; } | 获取或设置形状的宽度，单位为点。可读写 Single。 |
| [X](../../aspose.slides/shape/x) { get; set; } | 获取或设置形状左上角的 x 坐标，单位为点。可读写 Single。 |
| [Y](../../aspose.slides/shape/y) { get; set; } | 获取或设置形状左上角的 y 坐标，单位为点。可读写 Single。 |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | 返回形状在 Z 顺序中的位置。Shapes[0] 返回 Z 顺序最底部的形状，Shapes[Shapes.Count - 1] 返回 Z 顺序最前面的形状。只读 Int32。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 如果不存在，则添加一个新占位符并将占位符属性设置为指定的占位符。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 返回基本占位符形状（当前形状继承自的布局和/或母版幻灯片中的形状）。如果当前形状未被继承，则返回 null。 |
| [GetImage](../../aspose.slides/shape/getimage)() | 返回形状缩略图。默认使用 ShapeThumbnailBounds.Shape 形状缩略图边界类型。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 返回形状缩略图。 |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | 获取根据渲染内容计算的形状可视边界。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 定义此形状不是占位符。 |
| [SetEmbeddedData](../../aspose.slides/oleobjectframe/setembeddeddata)(IOleEmbeddedDataInfo) | 设置 OLE 嵌入数据的信息。此方法更改对象的属性以反映新数据，并将 IsObjectLink 标志设为 false，表示 OLE 对象已嵌入。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | 将形状内容保存为 SVG 文件。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | 将形状内容保存为 SVG 文件。 |

### 示例

以下示例演示如何访问 OLE 对象框架。

```csharp
[C#]
// 将 PPTX 加载到演示对象中
using (Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx"))
{
    // 访问第一张幻灯片
    ISlide sld = pres.Slides[0];
    // 将形状转换为 OleObjectFrame
    OleObjectFrame oleObjectFrame = sld.Shapes[0] as OleObjectFrame;
    // 读取 OLE 对象并写入磁盘
    if (oleObjectFrame != null)
    {
        // 获取嵌入文件数据
        byte[] data = oleObjectFrame.EmbeddedData.EmbeddedFileData;
        // 获取嵌入文件扩展名
        string fileExtention = oleObjectFrame.EmbeddedData.EmbeddedFileExtension;
        // 创建用于保存提取文件的路径
        string extractedPath = "excelFromOLE_out" + fileExtention;
        // 保存提取的数据
        using (FileStream fstr = new FileStream(extractedPath, FileMode.Create, FileAccess.Write))
        {
            fstr.Write(data, 0, data.Length);
        }
    }
}
```

### 另请参见

* 类 [GraphicalObject](../graphicalobject)
* 接口 [IOleObjectFrame](../ioleobjectframe)
* 命名空间 [Aspose.Slides](../../aspose.slides)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->