---
title: IPresentation
second_title: Aspose.Sildes for .NET API 参考
description: 演示文稿
type: docs
weight: 6770
url: /zh/aspose.slides/ipresentation/
---
## IPresentation 接口

演示文稿

```csharp
public interface IPresentation : IDisposable, IPresentationComponent
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/ipresentation/allcustomxmlparts) { get; } | 返回演示文稿中所有自定义数据部件。只读 [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [AsIDisposable](../../aspose.slides/ipresentation/asidisposable) { get; } | 返回 IDisposable 接口。只读 IDisposable. |
| [AsIPresentationComponent](../../aspose.slides/ipresentation/asipresentationcomponent) { get; } | 允许获取基础 IPresentationComponent 接口。只读 [`IPresentationComponent`](../ipresentationcomponent). |
| [Audios](../../aspose.slides/ipresentation/audios) { get; } | 返回演示文稿中所有嵌入音频文件的集合。只读 [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/ipresentation/commentauthors) { get; } | 返回评论作者的集合。只读 [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/ipresentation/currentdatetime) { get; set; } | 返回或设置日期时间，用于替换 datetime 字段的内容。默认值为此 Presentation 对象创建的时间。读/写 DateTime. |
| [CustomData](../../aspose.slides/ipresentation/customdata) { get; } | 返回演示文稿的自定义数据。只读 [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/ipresentation/defaulttextstyle) { get; } | 返回形状的默认文本样式。只读 [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/ipresentation/digitalsignatures) { get; } | 返回用于签署演示文稿的签名集合。只读 [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/ipresentation/documentproperties) { get; } | 返回包含标准和自定义文档属性的 DocumentProperties 对象。只读 [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/ipresentation/firstslidenumber) { get; set; } | 表示演示文稿中的第一张幻灯片编号。读/写 Int32. |
| [FontsManager](../../aspose.slides/ipresentation/fontsmanager) { get; } | 返回字体管理器。只读 [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/ipresentation/headerfootermanager) { get; } | 返回演示文稿的 HeaderFooter 管理器。只读 [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/ipresentation/hyperlinkqueries) { get; } | 提供对所有演示文稿幻灯片中包含的超链接的便捷访问（不包括母版、布局、备注幻灯片）。只读 [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/ipresentation/images) { get; } | 返回演示文稿中所有图像的集合。只读 [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/ipresentation/layoutslides) { get; } | 返回演示文稿中定义的所有布局幻灯片的列表。只读 [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/ipresentation/masterhandoutslidemanager) { get; } | 返回讲义母版管理器。只读 [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/ipresentation/masternotesslidemanager) { get; } | 返回备注母版管理器。只读 [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/ipresentation/masters) { get; } | 返回演示文稿中定义的所有母版幻灯片的列表。只读 [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/ipresentation/mastertheme) { get; } | 返回演示文稿的母版主题。只读 [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/ipresentation/notessize) { get; } | 返回备注幻灯片尺寸对象。只读 [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/ipresentation/protectionmanager) { get; } | 获取此演示文稿权限的管理器。只读 [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/ipresentation/sections) { get; } | 返回演示文稿中定义的所有幻灯片分节的列表。只读 [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/ipresentation/sensitivitylabels) { get; } | 返回应用于演示文稿的敏感度标签集合。只读 [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/ipresentation/slides) { get; } | 返回演示文稿中定义的所有幻灯片的列表。只读 [`ISlideCollection`](../islidecollection). |
| [SlideSize](../../aspose.slides/ipresentation/slidesize) { get; } | 返回幻灯片尺寸对象。只读 [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/ipresentation/sourceformat) { get; } | 返回关于演示文稿加载自哪种格式的信息。只读 [`SourceFormat`](./sourceformat). |
| [VbaProject](../../aspose.slides/ipresentation/vbaproject) { get; set; } | 获取包含演示文稿宏的 VBA 项目。读/写 [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/ipresentation/videos) { get; } | 返回演示文稿中所有嵌入视频文件的集合。只读 [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/ipresentation/viewproperties) { get; } | 获取演示文稿范围的视图属性。只读 [`IViewProperties`](../iviewproperties). |

## 方法

| 名称 | 描述 |
| --- | --- |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages)(IRenderingOptions) | 返回演示文稿中所有幻灯片的缩略图 Image 对象。 |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_1)(IRenderingOptions, int[]) | 返回演示文稿中指定幻灯片的缩略图 Bitmap 对象。 |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_5)(IRenderingOptions, Size) | 返回演示文稿中所有幻灯片的缩略图 Image 对象，使用指定的大小。 |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_4)(IRenderingOptions, float, float) | 返回演示文稿中所有幻灯片的缩略图 Image 对象，使用自定义缩放。 |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | 返回演示文稿中指定幻灯片的缩略图 Image 对象，使用指定的大小。 |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | 返回演示文稿中指定幻灯片的缩略图 Image 对象，使用自定义缩放。 |
| [GetSlideById](../../aspose.slides/ipresentation/getslidebyid)(uint) | 根据 Id 返回 Slide、MasterSlide 或 LayoutSlide。 |
| [HighlightRegex](../../aspose.slides/ipresentation/highlightregex)(Regex, Color, IFindResultCallback) | 使用指定颜色高亮正则表达式的所有匹配项。 |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext)(string, Color) | 使用指定颜色高亮示例文本的所有匹配项。 |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | 使用指定颜色高亮示例文本的所有匹配项。 |
| [JoinPortionsWithSameFormatting](../../aspose.slides/ipresentation/joinportionswithsameformatting)() | 在所有幻灯片的所有可接受形状中的所有段落中合并具有相同格式的运行。 |
| [RefreshChartsData](../../aspose.slides/ipresentation/refreshchartsdata)(bool) | 从源工作簿重新加载演示文稿中所有图表的数据。 |
| [ReplaceRegex](../../aspose.slides/ipresentation/replaceregex)(Regex, string, IFindResultCallback) | 使用指定字符串替换正则表达式的所有匹配项。 |
| [ReplaceText](../../aspose.slides/ipresentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | 将指定文本的所有出现替换为另一个指定文本。 |
| [Save](../../aspose.slides/ipresentation/save#save)(IXamlOptions) | 将演示文稿的所有幻灯片保存为一组表示 XAML 标记的文件。 |
| [Save](../../aspose.slides/ipresentation/save#save_1)(Stream, SaveFormat) | 以指定格式将演示文稿的所有幻灯片保存到流中。 |
| [Save](../../aspose.slides/ipresentation/save#save_5)(string, SaveFormat) | 以指定格式将演示文稿的所有幻灯片保存到文件。 |
| [Save](../../aspose.slides/ipresentation/save#save_3)(Stream, int[], SaveFormat) | 以指定格式将演示文稿的指定幻灯片保存到流中。 |
| [Save](../../aspose.slides/ipresentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | 以指定格式并使用附加选项将演示文稿的所有幻灯片保存到流中。 |
| [Save](../../aspose.slides/ipresentation/save#save_7)(string, int[], SaveFormat) | 以指定格式将演示文稿的指定幻灯片保存到文件。 |
| [Save](../../aspose.slides/ipresentation/save#save_6)(string, SaveFormat, ISaveOptions) | 以指定格式并使用附加选项将演示文稿的所有幻灯片保存到文件。 |
| [Save](../../aspose.slides/ipresentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | 以指定格式将演示文稿的指定幻灯片保存到流中。 |
| [Save](../../aspose.slides/ipresentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | 以指定格式将演示文稿的指定幻灯片保存到文件。 |

### 另见

* 接口 [IPresentationComponent](../ipresentationcomponent)
* 命名空间 [Aspose.Slides](../../aspose.slides)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->