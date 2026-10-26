---
title: IDocumentProperties
second_title: Aspose.Sildes for .NET API 参考
description: 表示演示文稿的属性。
type: docs
weight: 5710
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
| [ApplicationTemplate](../../aspose.slides/idocumentproperties/applicationtemplate) { get; set; } | 返回或设置应用程序的模板。读取/写入 String。 |
| [AppVersion](../../aspose.slides/idocumentproperties/appversion) { get; } | 返回应用程序版本。只读 String。 |
| [Author](../../aspose.slides/idocumentproperties/author) { get; set; } | 返回或设置演示文稿的作者。读取/写入 String。 |
| [Category](../../aspose.slides/idocumentproperties/category) { get; set; } | 返回或设置演示文稿的类别。读取/写入 String。 |
| [Comments](../../aspose.slides/idocumentproperties/comments) { get; set; } | 返回或设置演示文稿的注释。读取/写入 String。 |
| [Company](../../aspose.slides/idocumentproperties/company) { get; set; } | 返回或设置公司属性。读取/写入 String。 |
| [ContentStatus](../../aspose.slides/idocumentproperties/contentstatus) { get; set; } | 返回或设置演示文稿的内容状态。读取/写入 String。 |
| [ContentType](../../aspose.slides/idocumentproperties/contenttype) { get; set; } | 返回或设置演示文稿的内容类型。读取/写入 String。 |
| [CountOfCustomProperties](../../aspose.slides/idocumentproperties/countofcustomproperties) { get; } | 返回集合中实际包含的自定义属性数量。只读 Int32。 |
| [CreatedTime](../../aspose.slides/idocumentproperties/createdtime) { get; set; } | 返回演示文稿的创建日期。值为 UTC。读取/写入 DateTime。 |
| [HeadingPairs](../../aspose.slides/idocumentproperties/headingpairs) { get; } | 指示文档部件的分组以及每组中的部件数量。只读 IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/idocumentproperties/hiddenslides) { get; } | 指定演示文稿文档中隐藏幻灯片的数量。只读 Int32。 |
| [HyperlinkBase](../../aspose.slides/idocumentproperties/hyperlinkbase) { get; set; } | 返回或设置 HyperlinkBase 文档属性。读取/写入 String。 |
| [HyperlinksChanged](../../aspose.slides/idocumentproperties/hyperlinkschanged) { get; set; } | 指定该部件中的一个或多个超链接已由生成器仅在此部件中更新。下一个打开此文档的生成器应使用此部件中指定的新超链接更新超链接关系。读取/写入 Boolean。 |
| [Item](../../aspose.slides/idocumentproperties/item) { get; set; } | 返回或设置与指定名称关联的自定义属性。读取/写入 Object。 |
| [Keywords](../../aspose.slides/idocumentproperties/keywords) { get; set; } | 返回或设置演示文稿的关键字。读取/写入 String。 |
| [LastPrinted](../../aspose.slides/idocumentproperties/lastprinted) { get; set; } | 返回演示文稿上次打印的日期。读取/写入 DateTime。 |
| [LastSavedBy](../../aspose.slides/idocumentproperties/lastsavedby) { get; set; } | 返回或设置最后修改演示文稿的人的姓名。读取/写入 String。 |
| [LastSavedTime](../../aspose.slides/idocumentproperties/lastsavedtime) { get; set; } | 返回演示文稿最后修改的日期。值为 UTC。对于 Presentation.DocumentProperties 为只读（因为在 IPresentation 对象保存过程内部会更新）。可以通过 [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties) 方法返回的 DocumentProperties 实例进行更改。请参见 [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties) 方法摘要中的示例。 |
| [LinksUpToDate](../../aspose.slides/idocumentproperties/linksuptodate) { get; set; } | 指示文档中的超链接是否为最新。将此元素设置为 **true** 表示超链接已更新。将此元素设置为 **false** 表示超链接已过时。读取/写入 Boolean。 |
| [Manager](../../aspose.slides/idocumentproperties/manager) { get; set; } | 返回或设置 manager 属性。读取/写入 String。 |
| [MultimediaClips](../../aspose.slides/idocumentproperties/multimediaclips) { get; } | 指定文档中存在的声音或视频剪辑的总数。只读 Int32。 |
| [NameOfApplication](../../aspose.slides/idocumentproperties/nameofapplication) { get; set; } | 返回或设置应用程序的名称。读取/写入 String。 |
| [Notes](../../aspose.slides/idocumentproperties/notes) { get; } | 指定包含备注的演示文稿幻灯片数量。只读 Int32。 |
| [Paragraphs](../../aspose.slides/idocumentproperties/paragraphs) { get; } | 指定文档中（如果适用）找到的段落总数。只读 Int32。 |
| [PresentationFormat](../../aspose.slides/idocumentproperties/presentationformat) { get; set; } | 返回或设置演示文稿的预期格式。读取/写入 String。 |
| [RevisionNumber](../../aspose.slides/idocumentproperties/revisionnumber) { get; set; } | 返回或设置演示文稿的修订号。读取/写入 Int32。 |
| [ScaleCrop](../../aspose.slides/idocumentproperties/scalecrop) { get; set; } | 指示文档缩略图的显示模式。将此元素设置为 **true** 可将文档缩略图缩放至显示区域。将此元素设置为 **false** 可裁剪文档缩略图，仅显示适合显示区域的部分。读取/写入 Boolean。 |
| [SharedDoc](../../aspose.slides/idocumentproperties/shareddoc) { get; set; } | 确定演示文稿是否在多个人之间共享。读取/写入 Boolean。 |
| [Slides](../../aspose.slides/idocumentproperties/slides) { get; } | 指定演示文稿文档中幻灯片的总数。只读 Int32。 |
| [Subject](../../aspose.slides/idocumentproperties/subject) { get; set; } | 返回或设置演示文稿的主题。读取/写入 String。 |
| [Title](../../aspose.slides/idocumentproperties/title) { get; set; } | 返回或设置演示文稿的标题。读取/写入 String。 |
| [TitlesOfParts](../../aspose.slides/idocumentproperties/titlesofparts) { get; } | 指定每个文档部件的标题。这些部件不是文档部件，而是文档章节的概念性表示。只读 string[]. |
| [TotalEditingTime](../../aspose.slides/idocumentproperties/totaleditingtime) { get; set; } | 演示文稿的总编辑时间。读取/写入 TimeSpan。 |
| [Words](../../aspose.slides/idocumentproperties/words) { get; } | 指定文档中包含的单词总数。只读 Int32。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/idocumentproperties/clearbuiltinproperties)() | 清除并为所有内置属性设置默认值。 |
| [ClearCustomProperties](../../aspose.slides/idocumentproperties/clearcustomproperties)() | 移除所有自定义属性。 |
| [ContainsCustomProperty](../../aspose.slides/idocumentproperties/containscustomproperty)(string) | 检查是否存在具有指定名称的自定义属性。 |
| [GetCustomPropertyName](../../aspose.slides/idocumentproperties/getcustompropertyname)(int) | 返回指定索引处的自定义属性名称。 |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | 从自定义属性获取指定名称的布尔值。 |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | 从自定义属性获取指定名称的 DateTime 值。 |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | 从自定义属性获取指定名称的 double 值。 |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | 从自定义属性获取指定名称的 float 值。 |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | 从自定义属性获取指定名称的整数值。 |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | 从自定义属性获取指定名称的字符串值。 |
| [GetSensitivityLabels](../../aspose.slides/idocumentproperties/getsensitivitylabels)() | 从自定义文档属性获取敏感度标签数组（Microsoft Information Protection SDK 元数据）。 |
| [RemoveCustomProperty](../../aspose.slides/idocumentproperties/removecustomproperty)(string) | 移除与指定名称关联的自定义属性。 |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | 设置指定名称的布尔自定义属性。 |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | 设置指定名称的 DateTime 自定义属性。 |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | 设置指定名称的 double 自定义属性。 |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | 设置指定名称的 float 自定义属性。 |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | 设置指定名称的整数自定义属性。 |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | 设置指定名称的字符串自定义属性。 |

### 另请参见

* 命名空间 [Aspose.Slides](../../aspose.slides)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->