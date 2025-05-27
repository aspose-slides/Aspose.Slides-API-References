---
title: IPresentation
second_title: Aspose.Sildes for .NET API 参考
description: 演示文档
type: docs
weight: 6550
url: /zh/aspose.slides/ipresentation/
---

## IPresentation 接口

演示文档

```csharp
public interface IPresentation : IDisposable, IPresentationComponent
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/ipresentation/allcustomxmlparts) { get; } | 返回演示文档中的所有自定义数据部分。只读 [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [AsIDisposable](../../aspose.slides/ipresentation/asidisposable) { get; } | 返回 IDisposable 接口。只读 IDisposable。 |
| [AsIPresentationComponent](../../aspose.slides/ipresentation/asipresentationcomponent) { get; } | 允许获取基 IPresentationComponent 接口。只读 [`IPresentationComponent`](../ipresentationcomponent)。 |
| [Audios](../../aspose.slides/ipresentation/audios) { get; } | 返回演示文档中所有嵌入音频文件的集合。只读 [`IAudioCollection`](../iaudiocollection)。 |
| [CommentAuthors](../../aspose.slides/ipresentation/commentauthors) { get; } | 返回评论作者的集合。只读 [`ICommentAuthorCollection`](../icommentauthorcollection)。 |
| [CurrentDateTime](../../aspose.slides/ipresentation/currentdatetime) { get; set; } | 返回或设置将替代日期时间字段内容的日期和时间。默认情况下为此演示文档对象创建的时间。读写 DateTime。 |
| [CustomData](../../aspose.slides/ipresentation/customdata) { get; } | 返回演示文档的自定义数据。只读 [`ICustomData`](../icustomdata)。 |
| [DefaultTextStyle](../../aspose.slides/ipresentation/defaulttextstyle) { get; } | 返回形状的默认文本样式。只读 [`ITextStyle`](../itextstyle)。 |
| [DigitalSignatures](../../aspose.slides/ipresentation/digitalsignatures) { get; } | 返回用于签署演示文档的签名集合。只读 [`IDigitalSignatureCollection`](../idigitalsignaturecollection)。 |
| [DocumentProperties](../../aspose.slides/ipresentation/documentproperties) { get; } | 返回包含标准和自定义文档属性的 DocumentProperties 对象。只读 [`IDocumentProperties`](../idocumentproperties)。 |
| [FirstSlideNumber](../../aspose.slides/ipresentation/firstslidenumber) { get; set; } | 表示演示文档中的第一张幻灯片编号。读写 Int32。 |
| [FontsManager](../../aspose.slides/ipresentation/fontsmanager) { get; } | 返回字体管理器。只读 [`IFontsManager`](../ifontsmanager)。 |
| [HeaderFooterManager](../../aspose.slides/ipresentation/headerfootermanager) { get; } | 返回演示文档的页眉页脚管理器。只读 [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager)。 |
| [HyperlinkQueries](../../aspose.slides/ipresentation/hyperlinkqueries) { get; } | 便捷访问演示文档所有幻灯片中包含的所有超链接（不包括母版、布局、备注幻灯片）。只读 [`IHyperlinkQueries`](../ihyperlinkqueries)。 |
| [Images](../../aspose.slides/ipresentation/images) { get; } | 返回演示文档中所有图像的集合。只读 [`IImageCollection`](../iimagecollection)。 |
| [LayoutSlides](../../aspose.slides/ipresentation/layoutslides) { get; } | 返回演示文档中定义的所有布局幻灯片的列表。只读 [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection)。 |
| [MasterHandoutSlideManager](../../aspose.slides/ipresentation/masterhandoutslidemanager) { get; } | 返回讲义母版管理器。只读 [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager)。 |
| [MasterNotesSlideManager](../../aspose.slides/ipresentation/masternotesslidemanager) { get; } | 返回备注母版管理器。只读 [`IMasterNotesSlideManager`](../imasternotesslidemanager)。 |
| [Masters](../../aspose.slides/ipresentation/masters) { get; } | 返回演示文档中定义的所有母版幻灯片的列表。只读 [`IMasterSlideCollection`](../imasterslidecollection)。 |
| [MasterTheme](../../aspose.slides/ipresentation/mastertheme) { get; } | 返回演示文档的母版主题。只读 [`IMasterTheme`](../../aspose.slides.theme/imastertheme)。 |
| [NotesSize](../../aspose.slides/ipresentation/notessize) { get; } | 返回备注幻灯片大小对象。只读 [`INotesSize`](../inotessize)。 |
| [ProtectionManager](../../aspose.slides/ipresentation/protectionmanager) { get; } | 获取此演示文档权限的管理器。只读 [`IProtectionManager`](../iprotectionmanager)。 |
| [Sections](../../aspose.slides/ipresentation/sections) { get; } | 返回演示文档中定义的所有幻灯片节的列表。只读 [`ISectionCollection`](../isectioncollection)。 |
| [Slides](../../aspose.slides/ipresentation/slides) { get; } | 返回演示文档中定义的所有幻灯片的列表。只读 [`ISlideCollection`](../islidecollection)。 |
| [SlideSize](../../aspose.slides/ipresentation/slidesize) { get; } | 返回幻灯片大小对象。只读 [`ISlideSize`](../islidesize)。 |
| [SourceFormat](../../aspose.slides/ipresentation/sourceformat) { get; } | 返回有关演示文档加载自哪个格式的信息。只读 [`SourceFormat`](./sourceformat)。 |
| [VbaProject](../../aspose.slides/ipresentation/vbaproject) { get; set; } | 获取包含演示文档宏的 VBA 项目。读写 [`IVbaProject`](../../aspose.slides.vba/ivbaproject)。 |
| [Videos](../../aspose.slides/ipresentation/videos) { get; } | 返回演示文档中所有嵌入视频文件的集合。只读 [`IVideoCollection`](../ivideocollection)。 |
| [ViewProperties](../../aspose.slides/ipresentation/viewproperties) { get; } | 获取演示文档范围的视图属性。只读 [`IViewProperties`](../iviewproperties)。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages)(IRenderingOptions) | 返回演示文档所有幻灯片的缩略图图像对象。 |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_1)(IRenderingOptions, int[]) | 返回指定幻灯片的缩略图位图对象。 |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_5)(IRenderingOptions, Size) | 返回具有指定大小的演示文档所有幻灯片的缩略图图像对象。 |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_4)(IRenderingOptions, float, float) | 返回具有自定义缩放的演示文档所有幻灯片的缩略图图像对象。 |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | 返回具有指定大小的指定幻灯片的缩略图图像对象。 |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | 返回具有自定义缩放的指定幻灯片的缩略图图像对象。 |
| [GetSlideById](../../aspose.slides/ipresentation/getslidebyid)(uint) | 通过 Id 返回幻灯片、母版幻灯片或布局幻灯片。 |
| [HighlightRegex](../../aspose.slides/ipresentation/highlightregex)(Regex, Color, IFindResultCallback) | 用指定颜色高亮显示正则表达式的所有匹配项。 |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext)(string, Color) | 用指定颜色高亮显示样本文本的所有匹配项。 |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | 用指定颜色高亮显示样本文本的所有匹配项。 |
| [JoinPortionsWithSameFormatting](../../aspose.slides/ipresentation/joinportionswithsameformatting)() | 在所有幻灯片的所有可接受形状中的所有段落中连接具有相同格式的文本块。 |
| [ReplaceRegex](../../aspose.slides/ipresentation/replaceregex)(Regex, string, IFindResultCallback) | 用指定字符串替换正则表达式的所有匹配项。 |
| [ReplaceText](../../aspose.slides/ipresentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | 用另一个指定文本替换所有指定文本的出现。 |
| [Save](../../aspose.slides/ipresentation/save#save)(IXamlOptions) | 将演示文档的所有幻灯片保存为一组表示 XAML 标记的文件。 |
| [Save](../../aspose.slides/ipresentation/save#save_1)(Stream, SaveFormat) | 将演示文档的所有幻灯片保存到指定格式的流中。 |
| [Save](../../aspose.slides/ipresentation/save#save_5)(string, SaveFormat) | 将演示文档的所有幻灯片保存为指定格式的文件。 |
| [Save](../../aspose.slides/ipresentation/save#save_3)(Stream, int[], SaveFormat) | 将指定幻灯片的演示文档保存到指定格式的流中。 |
| [Save](../../aspose.slides/ipresentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | 将演示文档的所有幻灯片以指定格式和附加选项保存到流中。 |
| [Save](../../aspose.slides/ipresentation/save#save_7)(string, int[], SaveFormat) | 将指定幻灯片的演示文档保存为指定格式的文件。 |
| [Save](../../aspose.slides/ipresentation/save#save_6)(string, SaveFormat, ISaveOptions) | 将演示文档的所有幻灯片保存为指定格式的文件，并附加选项。 |
| [Save](../../aspose.slides/ipresentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | 将指定幻灯片的演示文档保存到指定格式的流中。 |
| [Save](../../aspose.slides/ipresentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | 将指定幻灯片的演示文档保存为指定格式的文件。 |

### 另请参阅

* 接口 [IPresentationComponent](../ipresentationcomponent)
* 命名空间 [Aspose.Slides](../../aspose.slides)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->