---
title: IDocumentProperties
second_title: Aspose.Sildes for .NET API 参考
description: 表示演示文稿的属性。
type: docs
weight: 5730
url: /zh/aspose.slides/idocumentproperties/
---
## IDocumentProperties 接口

表示演示文稿的属性。

```csharp
public interface IDocumentProperties
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/idocumentproperties/applicationtemplate) { get; set; } | 返回或设置应用程序的模板。可读写 String。 |
| [AppVersion](../../aspose.slides/idocumentproperties/appversion) { get; } | 返回应用程序版本。只读 String。 |
| [Author](../../aspose.slides/idocumentproperties/author) { get; set; } | 返回或设置演示文稿的作者。可读写 String。 |
| [Category](../../aspose.slides/idocumentproperties/category) { get; set; } | 返回或设置演示文稿的类别。可读写 String。 |
| [Comments](../../aspose.slides/idocumentproperties/comments) { get; set; } | 返回或设置演示文稿的注释。可读写 String。 |
| [Company](../../aspose.slides/idocumentproperties/company) { get; set; } | 返回或设置公司属性。可读写 String。 |
| [ContentStatus](../../aspose.slides/idocumentproperties/contentstatus) { get; set; } | 返回或设置演示文稿的内容状态。可读写 String。 |
| [ContentType](../../aspose.slides/idocumentproperties/contenttype) { get; set; } | 返回或设置演示文稿的内容类型。可读写 String。 |
| [CountOfCustomProperties](../../aspose.slides/idocumentproperties/countofcustomproperties) { get; } | 返回集合中实际包含的自定义属性数量。只读 Int32。 |
| [CreatedTime](../../aspose.slides/idocumentproperties/createdtime) { get; set; } | 返回演示文稿的创建日期。值为 UTC。可读写 DateTime。 |
| [HeadingPairs](../../aspose.slides/idocumentproperties/headingpairs) { get; } | 指示文档部件的分组及每组的部件数量。只读 IHeadingPair[]。 |
| [HiddenSlides](../../aspose.slides/idocumentproperties/hiddenslides) { get; } | 指定演示文稿文档中隐藏的幻灯片数量。只读 Int32。 |
| [HyperlinkBase](../../aspose.slides/idocumentproperties/hyperlinkbase) { get; set; } | 返回或设置 HyperlinkBase 文档属性。可读写 String。 |
| [HyperlinksChanged](../../aspose.slides/idocumentproperties/hyperlinkschanged) { get; set; } | 指定此部件中的一个或多个超链接仅由生成器在此部件中更新。下一个打开此文档的生成器应使用此部件中指定的新超链接更新超链接关系。可读写 Boolean。 |
| [Item](../../aspose.slides/idocumentproperties/item) { get; set; } | 返回或设置与指定名称关联的自定义属性。可读写 Object。 |
| [Keywords](../../aspose.slides/idocumentproperties/keywords) { get; set; } | 返回或设置演示文稿的关键字。可读写 String。 |
| [LastPrinted](../../aspose.slides/idocumentproperties/lastprinted) { get; set; } | 返回演示文稿上次打印的日期。可读写 DateTime。 |
| [LastSavedBy](../../aspose.slides/idocumentproperties/lastsavedby) { get; set; } | 返回最后一次修改演示文稿的人员姓名。可读写 String。 |
| [LastSavedTime](../../aspose.slides/idocumentproperties/lastsavedtime) { get; set; } | 返回演示文稿上次修改的日期。值为 UTC。对于 Presentation.DocumentProperties 为只读（因为在 IPresentation 对象保存过程中会在内部更新）。可以通过 [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties) 方法返回的 DocumentProperties 实例进行更改。请参见 [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties) 方法摘要中的示例。 |
| [LinksUpToDate](../../aspose.slides/idocumentproperties/linksuptodate) { get; set; } | 指示文档中的超链接是否为最新。将此元素设为 **true** 表示超链接已更新。将此元素设为 **false** 表示超链接已过期。可读写 Boolean。 |
| [Manager](../../aspose.slides/idocumentproperties/manager) { get; set; } | 返回或设置管理员属性。可读写 String。 |
| [MultimediaClips](../../aspose.slides/idocumentproperties/multimediaclips) { get; } | 指定文档中存在的声音或视频剪辑的总数量。只读 Int32。 |
| [NameOfApplication](../../aspose.slides/idocumentproperties/nameofapplication) { get; set; } | 返回或设置应用程序的名称。可读写 String。 |
| [Notes](../../aspose.slides/idocumentproperties/notes) { get; } | 指定演示文稿中包含备注的幻灯片数量。只读 Int32。 |
| [Paragraphs](../../aspose.slides/idocumentproperties/paragraphs) { get; } | 指定文档中（如果适用）段落的总数。只读 Int32。 |
| [PresentationFormat](../../aspose.slides/idocumentproperties/presentationformat) { get; set; } | 返回或设置演示文稿的预期格式。可读写 String。 |
| [RevisionNumber](../../aspose.slides/idocumentproperties/revisionnumber) { get; set; } | 返回或设置演示文稿的修订号。可读写 Int32。 |
| [ScaleCrop](../../aspose.slides/idocumentproperties/scalecrop) { get; set; } | 指示文档缩略图的显示模式。将此元素设为 **true** 以启用文档缩略图按显示进行缩放。将此元素设为 **false** 以启用文档缩略图裁剪，仅显示适配显示的部分。可读写 Boolean。 |
| [SharedDoc](../../aspose.slides/idocumentproperties/shareddoc) { get; set; } | 确定演示文稿是否在多人之间共享。可读写 Boolean。 |
| [Slides](../../aspose.slides/idocumentproperties/slides) { get; } | 指定演示文稿文档中幻灯片的总数量。只读 Int32。 |
| [Subject](../../aspose.slides/idocumentproperties/subject) { get; set; } | 返回或设置演示文稿的主题。可读写 String。 |
| [Title](../../aspose.slides/idocumentproperties/title) { get; set; } | 返回或设置演示文稿的标题。可读写 String。 |
| [TitlesOfParts](../../aspose.slides/idocumentproperties/titlesofparts) { get; } | 指定每个文档部件的标题。这些部件不是文档部件，而是文档章节的概念表示。只读 string[]。 |
| [TotalEditingTime](../../aspose.slides/idocumentproperties/totaleditingtime) { get; set; } | 演示文稿的总编辑时间。可读写 TimeSpan。 |
| [Words](../../aspose.slides/idocumentproperties/words) { get; } | 指定文档中包含的单词总数。只读 Int32。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/idocumentproperties/clearbuiltinproperties)() | 清除并设置所有内置属性的默认值。 |
| [ClearCustomProperties](../../aspose.slides/idocumentproperties/clearcustomproperties)() | 删除所有自定义属性。 |
| [ContainsCustomProperty](../../aspose.slides/idocumentproperties/containscustomproperty)(string) | 检查是否存在具有指定名称的自定义属性。 |
| [GetCustomPropertyName](../../aspose.slides/idocumentproperties/getcustompropertyname)(int) | 返回指定索引处的自定义属性名称。 |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | 获取自定义属性中指定名称的 boolean 值。 |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | 获取自定义属性中指定名称的 DateTime 值。 |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | 获取自定义属性中指定名称的 double 值。 |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | 获取自定义属性中指定名称的 float 值。 |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | 获取自定义属性中指定名称的 int 值。 |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | 获取自定义属性中指定名称的 string 值。 |
| [GetSensitivityLabels](../../aspose.slides/idocumentproperties/getsensitivitylabels)() | 从自定义文档属性获取敏感度标签数组（Microsoft Information Protection SDK Metadata）。 |
| [RemoveCustomProperty](../../aspose.slides/idocumentproperties/removecustomproperty)(string) | 删除与指定名称关联的自定义属性。 |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | 设置指定名称的 boolean 自定义属性。 |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | 设置指定名称的 DateTime 自定义属性。 |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | 设置指定名称的 double 自定义属性。 |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | 设置指定名称的 float 自定义属性。 |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | 设置指定名称的 int 自定义属性。 |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | 设置指定名称的 string 自定义属性。 |

### 另请参阅

* 命名空间 [Aspose.Slides](../../aspose.slides)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->