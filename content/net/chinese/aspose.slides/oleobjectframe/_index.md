---
title: OleObjectFrame
second_title: Aspose.Sildes for .NET API Reference
description: 表示幻灯片上的OLE对象。
type: docs
weight: 8960
url: /zh/aspose.slides/oleobjectframe/
---

## OleObjectFrame class

表示幻灯片上的OLE对象。

```csharp
public class OleObjectFrame : GraphicalObject, IOleObjectFrame
```

## Properties

| Name | Description |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 返回或设置与形状相关的替代文本。可读写字符串。 |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 返回或设置与形状相关的替代文本标题。可读写字符串。 |
| [AsIGraphicalObject](../../aspose.slides/oleobjectframe/asigraphicalobject) { get; } | 允许获取基接口IGraphicalObject。只读 [`IGraphicalObject`](../igraphicalobject)。 |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 属性指定形状在黑白显示模式下的渲染方式。可读写 [`BlackWhiteMode`](../blackwhitemode)。 |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 返回形状上的连接点数量。只读整数。 |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 返回形状的自定义数据。只读 [`ICustomData`](../icustomdata)。 |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 返回包含应用于形状的像素效果的EffectFormat对象。注意：对于某些没有效果属性的形状可以返回null。只读 [`IEffectFormat`](../ieffectformat)。 |
| [EmbeddedData](../../aspose.slides/oleobjectframe/embeddeddata) { get; } | 获取或设置有关OLE嵌入数据的信息。可读写 [`IOleEmbeddedDataInfo`](../ioleembeddeddatainfo)。 |
| [EmbeddedFileLabel](../../aspose.slides/oleobjectframe/embeddedfilelabel) { get; } | 返回嵌入OLE对象的文件名 |
| [EmbeddedFileName](../../aspose.slides/oleobjectframe/embeddedfilename) { get; } | 返回嵌入OLE对象的路径 |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | 返回包含形状填充格式属性的FillFormat对象。注意：对于某些没有填充属性的形状可以返回null。只读 [`IFillFormat`](../ifillformat)。 |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 返回或设置形状框架的属性。可读写 [`IShapeFrame`](../ishapeframe)。 |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | 返回形状的锁定状态。只读 [`IGraphicalObjectLock`](../igraphicalobjectlock)。 |
| [Height](../../aspose.slides/shape/height) { get; set; } | 返回或设置形状的高度。可读写单精度浮点数。 |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 确定形状是否隐藏。可读写布尔值。 |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 返回或设置为鼠标点击定义的超链接。可读写 [`IHyperlink`](../ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 返回超链接管理器。只读 [`IHyperlinkManager`](../ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 返回或设置为鼠标经过定义的超链接。可读写 [`IHyperlink`](../ihyperlink)。 |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 获取或设置“标记为装饰性”选项 可读写布尔值。 |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 确定形状是否分组。只读布尔值。 |
| [IsObjectIcon](../../aspose.slides/oleobjectframe/isobjecticon) { get; set; } | 确定对象是否作为图标可见。可读写布尔值。 |
| [IsObjectLink](../../aspose.slides/oleobjectframe/isobjectlink) { get; } | 确定对象是否链接到外部文件。只读布尔值。 |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 确定形状是否为文本占位符。只读布尔值。 |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 返回包含形状线条格式属性的LineFormat对象。注意：对于某些没有线条属性的形状可以返回null。只读 [`ILineFormat`](../ilineformat)。 |
| [LinkFileName](../../aspose.slides/oleobjectframe/linkfilename) { get; } | 返回链接文件的完整路径。将使用短文件名。只读字符串。 |
| [LinkPathLong](../../aspose.slides/oleobjectframe/linkpathlong) { get; set; } | 返回链接文件的完整路径。将使用长文件名。可读写字符串。 |
| [LinkPathRelative](../../aspose.slides/oleobjectframe/linkpathrelative) { get; } | 返回相对路径到链接文件（如果存在），否则返回空字符串。只读字符串。 |
| [Name](../../aspose.slides/shape/name) { get; set; } | 返回或设置形状的名称。必须不为null。如有必要，使用空字符串值。可读写字符串。 |
| [ObjectName](../../aspose.slides/oleobjectframe/objectname) { get; set; } | 返回或设置对象的名称。可读写字符串。 |
| [ObjectProgId](../../aspose.slides/oleobjectframe/objectprogid) { get; set; } | 返回对象的ProgID。只读字符串。 |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 获取在幻灯片范围内唯一的形状标识符。只读UInt32。另见 [`UniqueId`](../shape/uniqueid) 获取在演示范围内唯一的形状标识符。 |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 如果形状被分组，返回父GroupShape对象。否则返回null。只读 [`IGroupShape`](../igroupshape)。 |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 返回形状的占位符。如果形状没有占位符则返回null。只读 [`IPlaceholder`](../iplaceholder)。 |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 返回幻灯片的父演示文稿。只读 [`IPresentation`](../ipresentation)。 |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 返回或设置原始形状框架的属性。可读写 [`IShapeFrame`](../ishapeframe)。 |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 返回或设置指定形状围绕z轴旋转的度数。正值表示顺时针旋转；负值表示逆时针旋转。可读写单精度浮点数。 |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | 返回形状的锁定状态。只读 [`IGraphicalObjectLock`](../igraphicalobjectlock)。 (2个属性) |
| [Slide](../../aspose.slides/shape/slide) { get; } | 返回形状的父幻灯片。只读 [`IBaseSlide`](../ibaseslide)。 |
| [SubstitutePictureFormat](../../aspose.slides/oleobjectframe/substitutepictureformat) { get; } | 返回OleObject图像填充属性对象。只读 [`IPictureFillFormat`](../ipicturefillformat)。 |
| [SubstitutePictureTitle](../../aspose.slides/oleobjectframe/substitutepicturetitle) { get; set; } | 返回或设置OleObject图标的标题。可读写字符串。 |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 返回包含形状3D效果属性的ThreeDFormat对象。注意：对于某些没有3D属性的形状可以返回null。只读 [`IThreeDFormat`](../ithreedformat)。 |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 获取在演示范围内唯一的形状标识符。只读UInt32。另见 [`OfficeInteropShapeId`](../shape/officeinteropshapeid) 获取在幻灯片范围内唯一的形状标识符。 |
| [UpdateAutomatic](../../aspose.slides/oleobjectframe/updateautomatic) { get; set; } | 确定当打开或打印演示文稿时，链接的嵌入对象是否自动更新。可读写布尔值。 |
| [Width](../../aspose.slides/shape/width) { get; set; } | 返回或设置形状的宽度。可读写单精度浮点数。 |
| [X](../../aspose.slides/shape/x) { get; set; } | 返回或设置形状左上角的x坐标。可读写单精度浮点数。 |
| [Y](../../aspose.slides/shape/y) { get; set; } | 返回或设置形状左上角的y坐标。可读写单精度浮点数。 |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | 返回形状在z-order中的位置。Shapes[0]返回z-order最背后的形状，Shapes[Shapes.Count - 1]返回z-order最前面的形状。只读整数。 |

## Methods

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 如果没有占位符，则添加一个新占位符，并将占位符属性设置为指定属性。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 返回基本占位符形状（当前形状所继承的布局和/或母版幻灯片中的形状）。如果当前形状没有继承，则返回null。 |
| [GetImage](../../aspose.slides/shape/getimage)() | 返回形状缩略图。默认情况下使用ShapeThumbnailBounds.Shape形状缩略图边界类型。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 返回形状缩略图。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 定义该形状不是占位符。 |
| [SetEmbeddedData](../../aspose.slides/oleobjectframe/setembeddeddata)(IOleEmbeddedDataInfo) | 设置有关OLE嵌入数据的信息。该方法更改对象的属性以反映新数据，并将IsObjectLink标志设置为false，表示OLE对象是嵌入的。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | 将形状内容保存为SVG文件。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | 将形状内容保存为SVG文件。 |

### Examples

以下示例演示如何访问OLE对象框架。

```csharp
[C#]
// Loads the PPTX to a presentation object
using (Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx"))
{
    // Accesses the first slide
    ISlide sld = pres.Slides[0];
    // Casts the shape to OleObjectFrame
    OleObjectFrame oleObjectFrame = sld.Shapes[0] as OleObjectFrame;
    // Reads the OLE Object and writes it to disk
    if (oleObjectFrame != null)
    {
        // Gets embedded file data
        byte[] data = oleObjectFrame.EmbeddedData.EmbeddedFileData;
        // Gets embedded file extention
        string fileExtention = oleObjectFrame.EmbeddedData.EmbeddedFileExtension;
        // Creates a path to save the extracted file
        string extractedPath = "excelFromOLE_out" + fileExtention;
        // Saves extracted data
        using (FileStream fstr = new FileStream(extractedPath, FileMode.Create, FileAccess.Write))
        {
            fstr.Write(data, 0, data.Length);
        }
    }
}
```

### See Also

* class [GraphicalObject](../graphicalobject)
* interface [IOleObjectFrame](../ioleobjectframe)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->