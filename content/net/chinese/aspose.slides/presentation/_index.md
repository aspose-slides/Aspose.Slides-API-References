---
title: Presentation
second_title: Aspose.Sildes for .NET API 参考
description: 表示一个 Microsoft PowerPoint 演示文稿。
type: docs
weight: 9590
url: /zh/aspose.slides/presentation/
---
## Presentation 类

表示一个 Microsoft PowerPoint 演示文稿。

```csharp
public sealed class Presentation : IPresentation
```

## 构造函数

| 名称 | 说明 |
| --- | --- |
| [Presentation](presentation#constructor)() | 此构造函数从头创建新的演示文稿。创建的演示文稿包含一张空幻灯片。 |
| [Presentation](presentation#constructor_1)(LoadOptions) | 此构造函数从头创建新的演示文稿。创建的演示文稿包含一张空幻灯片。 |
| [Presentation](presentation#constructor_2)(Stream) | 此构造函数是读取现有 Presentation 的主要方式。 |
| [Presentation](presentation#constructor_4)(string) | 此构造函数获取用于读取 Presentation 内容的源文件路径。 |
| [Presentation](presentation#constructor_3)(Stream, LoadOptions) | 此构造函数是读取现有 Presentation 的主要方式。 |
| [Presentation](presentation#constructor_5)(string, LoadOptions) | 此构造函数获取用于读取 Presentation 内容的源文件路径。 |

## 属性

| 名称 | 说明 |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/presentation/allcustomxmlparts) { get; } | 返回演示文稿中的所有自定义数据部件。只读 [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [Audios](../../aspose.slides/presentation/audios) { get; } | 返回演示文稿中所有嵌入式音频文件的集合。只读 [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/presentation/commentauthors) { get; } | 返回评论作者的集合。只读 [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/presentation/currentdatetime) { get; set; } | 返回或设置用于替换 datetime 字段内容的日期和时间。默认是此 Presentation 对象创建的时间。可读写 DateTime. |
| [CustomData](../../aspose.slides/presentation/customdata) { get; } | 返回演示文稿的自定义数据。只读 [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/presentation/defaulttextstyle) { get; } | 返回形状的默认文本样式。只读 [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/presentation/digitalsignatures) { get; } | 返回用于签署演示文稿的签名集合。只读 [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/presentation/documentproperties) { get; } | 返回包含标准和自定义文档属性的 DocumentProperties 对象。只读 [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/presentation/firstslidenumber) { get; set; } | 表示演示文稿中的首页编号 |
| [FontsManager](../../aspose.slides/presentation/fontsmanager) { get; } | 返回字体管理器。只读 [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/presentation/headerfootermanager) { get; } | 返回实际的 HeaderFooter 管理器。只读 [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/presentation/hyperlinkqueries) { get; } | 提供对所有演示文稿幻灯片（不包括母版、布局、备注幻灯片）中包含的超链接的便捷访问。只读 [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/presentation/images) { get; } | 返回演示文稿中所有图像的集合。只读 [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/presentation/layoutslides) { get; } | 返回演示文稿中定义的所有布局幻灯片的列表。只读 [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/presentation/masterhandoutslidemanager) { get; } | 返回讲义母版管理器。只读 [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/presentation/masternotesslidemanager) { get; } | 返回备注母版管理器。只读 [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/presentation/masters) { get; } | 返回演示文稿中定义的所有母版幻灯片的列表。只读 [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/presentation/mastertheme) { get; } | 返回母版主题。只读 [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/presentation/notessize) { get; } | 返回备注幻灯片大小对象。只读 [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/presentation/protectionmanager) { get; } | 获取此演示文稿的权限管理器。只读 [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/presentation/sections) { get; } | 返回演示文稿中定义的所有幻灯片分段的列表。只读 [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/presentation/sensitivitylabels) { get; } | 返回应用于演示文稿文档的敏感度标签集合。只读 [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/presentation/slides) { get; } | 返回演示文稿中定义的所有幻灯片的列表。只读 [`ISlideCollection`](../islidecollection). |
| [SlideShowSettings](../../aspose.slides/presentation/slideshowsettings) { get; } | 返回演示文稿的幻灯片放映设置。 |
| [SlideSize](../../aspose.slides/presentation/slidesize) { get; } | 返回幻灯片大小对象。只读 [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/presentation/sourceformat) { get; } | 返回演示文稿加载的来源格式信息。只读 [`SourceFormat`](../sourceformat). |
| [VbaProject](../../aspose.slides/presentation/vbaproject) { get; set; } | 获取或设置带有演示文稿宏的 VBA 项目。可读写 [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/presentation/videos) { get; } | 返回演示文稿中所有嵌入式视频文件的集合。只读 [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/presentation/viewproperties) { get; } | 获取演示文稿范围的视图属性。只读 [`IViewProperties`](../iviewproperties). |

## 方法

| 名称 | 说明 |
| --- | --- |
| [Dispose](../../aspose.slides/presentation/dispose)() | 释放此 Presentation 对象使用的所有资源。 |
| [GetImages](../../aspose.slides/presentation/getimages#getimages)(IRenderingOptions) | 返回演示文稿所有幻灯片的 Image 对象。 |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_1)(IRenderingOptions, int[]) | 返回指定幻灯片的缩略图 Image 对象。 |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_5)(IRenderingOptions, Size) | 返回所有幻灯片的指定尺寸的缩略图 Image 对象。 |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_4)(IRenderingOptions, float, float) | 返回所有幻灯片的自定义缩放的缩略图 Image 对象。 |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | 返回指定幻灯片的指定尺寸的缩略图 Image 对象。 |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | 返回指定幻灯片的自定义缩放的缩略图 Image 对象。 |
| [GetSlideById](../../aspose.slides/presentation/getslidebyid)(uint) | 根据 Id 返回 Slide、MasterSlide 或 LayoutSlide。 |
| [HighlightRegex](../../aspose.slides/presentation/highlightregex)(Regex, Color, IFindResultCallback) | 使用指定颜色高亮正则表达式的所有匹配项。 |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext)(string, Color) | 使用指定颜色高亮示例文本的所有匹配项。 |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | 使用指定颜色高亮示例文本的所有匹配项。 |
| [JoinPortionsWithSameFormatting](../../aspose.slides/presentation/joinportionswithsameformatting)() | 在所有幻灯片的所有可接受形状中的所有段落中合并具有相同格式的文本运行。 |
| [ReplaceRegex](../../aspose.slides/presentation/replaceregex)(Regex, string, IFindResultCallback) | 使用指定字符串替换正则表达式的所有匹配项。 |
| [ReplaceText](../../aspose.slides/presentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | 将指定文本的所有出现替换为另一个指定文本。 |
| [Save](../../aspose.slides/presentation/save#save)(IXamlOptions) | 将演示文稿的所有幻灯片保存为一组表示 XAML 标记的文件。 |
| [Save](../../aspose.slides/presentation/save#save_1)(Stream, SaveFormat) | 以指定格式将演示文稿的所有幻灯片保存到流中。 |
| [Save](../../aspose.slides/presentation/save#save_5)(string, SaveFormat) | 以指定格式将演示文稿的所有幻灯片保存到文件中。 |
| [Save](../../aspose.slides/presentation/save#save_3)(Stream, int[], SaveFormat) | 以指定格式并保留页码，将演示文稿的指定幻灯片保存到流中。 |
| [Save](../../aspose.slides/presentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | 以指定格式并使用附加选项，将演示文稿的所有幻灯片保存到流中。 |
| [Save](../../aspose.slides/presentation/save#save_7)(string, int[], SaveFormat) | 以指定格式并保留页码，将演示文稿的指定幻灯片保存到文件中。 |
| [Save](../../aspose.slides/presentation/save#save_6)(string, SaveFormat, ISaveOptions) |  |
| [Save](../../aspose.slides/presentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | 以指定格式并保留页码，将演示文稿的指定幻灯片保存到流中。 |
| [Save](../../aspose.slides/presentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | 以指定格式并保留页码，将演示文稿的指定幻灯片保存到文件中。 |

### 示例

以下示例展示如何创建 PowerPoint 演示文稿。

```csharp
[C#]
// 实例化一个表示演示文稿文件的 Presentation 对象
using (Presentation presentation = new Presentation())
{
    // 获取第一张幻灯片
    ISlide slide = presentation.Slides[0];
    // 添加一个类型为线的自动形状
    slide.Shapes.AddAutoShape(ShapeType.Line, 50, 150, 300, 0);
	// 保存演示文稿文件。
    presentation.Save("NewPresentation_out.pptx", SaveFormat.Pptx);
}
```

以下示例展示如何打开并保存演示文稿。

```csharp
[C#]
// 加载 Presentation 支持的任意文件，例如 ppt、pptx、odp 等。
using (Presentation presentation = new Presentation("Sample.odp"))
{
	// 保存演示文稿文件。
	presentation.Save("OutputPresenation.pptx", SaveFormat.Pptx);
}
```

### 另见

* 接口 [IPresentation](../ipresentation)
* 命名空间 [Aspose.Slides](../../aspose.slides)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->