---
title: Presentation
second_title: Aspose.Slides for .NET API 参考
description: 表示 Microsoft PowerPoint 演示文稿
type: docs
weight: 8870
url: /zh/net/aspose.slides/presentation/
---
## Presentation class

表示 Microsoft PowerPoint 演示文稿。

```csharp
public sealed class Presentation : IPresentation
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [Presentation](presentation#constructor)() | 此构造函数从头开始创建新的演示文稿。 创建的演示文稿有一张空幻灯片。 |
| [Presentation](presentation#constructor_1)(LoadOptions) | 此构造函数从头开始创建新的演示文稿。 创建的演示文稿有一张空幻灯片。 |
| [Presentation](presentation#constructor_2)(Stream) | 此构造函数是读取现有演示文稿的主要机制。 |
| [Presentation](presentation#constructor_4)(string) | 此构造函数获取源文件路径， 从中读取演示文稿的内容。 |
| [Presentation](presentation#constructor_3)(Stream, LoadOptions) | 此构造函数是读取现有演示文稿的主要机制。 |
| [Presentation](presentation#constructor_5)(string, LoadOptions) | 此构造函数获取源文件路径， 从中读取演示文稿的内容。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/presentation/allcustomxmlparts) { get; } | 返回演示文稿中的所有自定义数据部分。 只读[`ICustomXmlPart`](../icustomxmlpart)[]. |
| [Audios](../../aspose.slides/presentation/audios) { get; } | 返回演示文稿中所有嵌入音频文件的集合。 只读[`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/presentation/commentauthors) { get; } | 返回评论 autors 的集合。 只读[`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/presentation/currentdatetime) { get; set; } | 返回或设置将替换日期时间字段内容的日期和时间。 默认情况下创建此演示文稿对象的时间。 读/写DateTime. |
| [CustomData](../../aspose.slides/presentation/customdata) { get; } | 返回演示文稿的自定义数据。 只读[`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/presentation/defaulttextstyle) { get; } | 返回形状的默认文本样式。 只读[`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/presentation/digitalsignatures) { get; } | 返回用于签署演示文稿的签名集合。 只读[`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/presentation/documentproperties) { get; } | 返回包含标准和自定义文档属性的 DocumentProperties 对象。 只读[`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/presentation/firstslidenumber) { get; set; } | 表示演示文稿中的第一张幻灯片编号 |
| [FontsManager](../../aspose.slides/presentation/fontsmanager) { get; } | 返回字体管理器。 只读[`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/presentation/headerfootermanager) { get; } | 返回实际的 HeaderFooter 管理器。 只读[`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/presentation/hyperlinkqueries) { get; } | 提供对所有演示幻灯片（不在母版、布局、注释幻灯片中）中包含的所有超链接的轻松访问。 只读[`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/presentation/images) { get; } | 返回演示文稿中所有图像的集合。 只读[`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/presentation/layoutslides) { get; } | 返回演示文稿中定义的所有布局幻灯片的列表。 只读[`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/presentation/masterhandoutslidemanager) { get; } | 返回讲义主经理。 只读[`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/presentation/masternotesslidemanager) { get; } | 返回注释主管理器。 只读[`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/presentation/masters) { get; } | 返回演示文稿中定义的所有母版幻灯片的列表。 只读[`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/presentation/mastertheme) { get; } | 返回主主题。 只读[`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/presentation/notessize) { get; } | 返回笔记幻灯片大小对象。 只读[`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/presentation/protectionmanager) { get; } | 获取此演示文稿的权限管理员。 只读[`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/presentation/sections) { get; } | 返回演示文稿中定义的所有幻灯片部分的列表。 只读[`ISectionCollection`](../isectioncollection). |
| [Slides](../../aspose.slides/presentation/slides) { get; } | 返回演示文稿中定义的所有幻灯片的列表。 只读[`ISlideCollection`](../islidecollection). |
| [SlideSize](../../aspose.slides/presentation/slidesize) { get; } | 返回幻灯片大小对象。 只读[`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/presentation/sourceformat) { get; } | 返回有关从哪个格式加载演示文稿的信息。 只读[`SourceFormat`](../sourceformat). |
| [VbaProject](../../aspose.slides/presentation/vbaproject) { get; set; } | 获取或设置带有演示宏的 VBA 项目。 读/写[`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/presentation/videos) { get; } | 返回演示文稿中所有嵌入视频文件的集合。 只读[`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/presentation/viewproperties) { get; } | 获取演示文稿范围的视图属性。 只读[`IViewProperties`](../iviewproperties). |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [Dispose](../../aspose.slides/presentation/dispose)() | 释放此 Presentation 对象使用的所有资源。 |
| [GetSlideById](../../aspose.slides/presentation/getslidebyid)(uint) | 按 ID 返回幻灯片、MasterSlide 或 LayoutSlide。 |
| [GetThumbnails](../../aspose.slides/presentation/getthumbnails#getthumbnails_6)(IRenderingOptions) | 返回演示文稿所有幻灯片的缩略图位图对象。 |
| [GetThumbnails](../../aspose.slides/presentation/getthumbnails#getthumbnails_7)(IRenderingOptions, int[]) | 返回演示文稿指定幻灯片的缩略图位图对象。 |
| [GetThumbnails](../../aspose.slides/presentation/getthumbnails#getthumbnails_11)(IRenderingOptions, Size) | 为具有指定大小的演示文稿的所有幻灯片返回缩略图位图对象。 |
| [GetThumbnails](../../aspose.slides/presentation/getthumbnails#getthumbnails_10)(IRenderingOptions, float, float) | 为具有自定义缩放的演示文稿的所有幻灯片返回缩略图位图对象。 |
| [GetThumbnails](../../aspose.slides/presentation/getthumbnails#getthumbnails_9)(IRenderingOptions, int[], Size) | 返回具有指定大小的演示文稿的指定幻灯片的缩略图位图对象。 |
| [GetThumbnails](../../aspose.slides/presentation/getthumbnails#getthumbnails_8)(IRenderingOptions, int[], float, float) | 为具有自定义缩放的演示文稿的指定幻灯片返回缩略图位图对象。 |
| [JoinPortionsWithSameFormatting](../../aspose.slides/presentation/joinportionswithsameformatting)() | 在所有幻灯片中以所有可接受的形状在所有段落中以相同的格式运行。 |
| [Print](../../aspose.slides/presentation/print#print)() | 将整个演示文稿打印到默认打印机。 |
| [Print](../../aspose.slides/presentation/print#print_1)(PrinterSettings) | 根据指定的打印机设置打印演示文稿， 使用标准（无用户界面）打印控制器。 |
| [Print](../../aspose.slides/presentation/print#print_3)(string) | 将整个演示文稿打印到指定的打印机， 使用标准（无用户界面）打印控制器。 |
| [Print](../../aspose.slides/presentation/print#print_2)(PrinterSettings, string) | 根据指定的打印机设置打印文档，使用 标准（无用户界面）打印控制器和演示名称。 |
| [Save](../../aspose.slides/presentation/save#save)(IXamlOptions) | 将演示文稿的所有幻灯片保存到一组表示 XAML 标记的文件中。 |
| [Save](../../aspose.slides/presentation/save#save_1)(Stream, SaveFormat) | 以指定格式将演示文稿的所有幻灯片保存到流中。 |
| [Save](../../aspose.slides/presentation/save#save_5)(string, SaveFormat) | 将演示文稿的所有幻灯片保存到指定格式的文件中。 |
| [Save](../../aspose.slides/presentation/save#save_3)(Stream, int[], SaveFormat) | 将演示文稿的指定幻灯片以指定格式保存到流中，并保留页码。 |
| [Save](../../aspose.slides/presentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | 将演示文稿的所有幻灯片以指定格式和附加选项保存到流中。 |
| [Save](../../aspose.slides/presentation/save#save_7)(string, int[], SaveFormat) | 将演示文稿的指定幻灯片保存到具有指定格式并保留页码的文件中。 |
| [Save](../../aspose.slides/presentation/save#save_6)(string, SaveFormat, ISaveOptions) | 将演示文稿的所有幻灯片保存到具有指定格式和附加选项的文件中。 |
| [Save](../../aspose.slides/presentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | 将演示文稿的指定幻灯片以指定格式保存到流中，并保留页码。 |
| [Save](../../aspose.slides/presentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | 将演示文稿的指定幻灯片保存到具有指定格式并保留页码的文件中。 |

### 也可以看看

* interface [IPresentation](../ipresentation)
* 命名空间 [Aspose.Slides](../../aspose.slides)
* 部件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
