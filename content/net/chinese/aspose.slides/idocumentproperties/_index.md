---
title: IDocumentProperties
second_title: Aspose.Sildes for .NET API Reference
description: 表示演示文稿的属性。
type: docs
weight: 5510
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
| [ApplicationTemplate](../../aspose.slides/idocumentproperties/applicationtemplate) { get; set; } | 返回或设置应用程序的模板。可读写字符串。 |
| [AppVersion](../../aspose.slides/idocumentproperties/appversion) { get; } | 返回应用程序版本。只读字符串。 |
| [Author](../../aspose.slides/idocumentproperties/author) { get; set; } | 返回或设置演示文稿的作者。可读写字符串。 |
| [Category](../../aspose.slides/idocumentproperties/category) { get; set; } | 返回或设置演示文稿的类别。可读写字符串。 |
| [Comments](../../aspose.slides/idocumentproperties/comments) { get; set; } | 返回或设置演示文稿的评论。可读写字符串。 |
| [Company](../../aspose.slides/idocumentproperties/company) { get; set; } | 返回或设置公司属性。可读写字符串。 |
| [ContentStatus](../../aspose.slides/idocumentproperties/contentstatus) { get; set; } | 返回或设置演示文稿的内容状态。可读写字符串。 |
| [ContentType](../../aspose.slides/idocumentproperties/contenttype) { get; set; } | 返回或设置演示文稿的内容类型。可读写字符串。 |
| [CountOfCustomProperties](../../aspose.slides/idocumentproperties/countofcustomproperties) { get; } | 返回集合中实际包含的自定义属性的数量。只读Int32。 |
| [CreatedTime](../../aspose.slides/idocumentproperties/createdtime) { get; set; } | 返回演示文稿创建的日期。值为UTC。可读写日期时间。 |
| [HeadingPairs](../../aspose.slides/idocumentproperties/headingpairs) { get; } | 指示文档部分的分组及每组中的部分数量。只读IHeadingPair[]。 |
| [HiddenSlides](../../aspose.slides/idocumentproperties/hiddenslides) { get; } | 指定演示文稿中隐藏幻灯片的数量。只读Int32。 |
| [HyperlinkBase](../../aspose.slides/idocumentproperties/hyperlinkbase) { get; set; } | 返回或设置HyperlinkBase文档属性。可读写字符串。 |
| [HyperlinksChanged](../../aspose.slides/idocumentproperties/hyperlinkschanged) { get; set; } | 指示此部分中的一个或多个超链接已被制作方专门在此部分中更新。下一个打开此文档的制作方应使用此部分中指定的新超链接更新超链接关系。可读写布尔值。 |
| [Item](../../aspose.slides/idocumentproperties/item) { get; set; } | 返回或设置与指定名称关联的自定义属性。可读写对象。 |
| [Keywords](../../aspose.slides/idocumentproperties/keywords) { get; set; } | 返回或设置演示文稿的关键字。可读写字符串。 |
| [LastPrinted](../../aspose.slides/idocumentproperties/lastprinted) { get; set; } | 返回演示文稿最后打印的日期。可读写日期时间。 |
| [LastSavedBy](../../aspose.slides/idocumentproperties/lastsavedby) { get; set; } | 返回或设置最后修改演示文稿的人名。可读写字符串。 |
| [LastSavedTime](../../aspose.slides/idocumentproperties/lastsavedtime) { get; set; } | 返回演示文稿最后修改的日期。值为UTC。专用于Presentation.DocumentProperties的只读（因为在保存IPresentation对象的过程中会内部更新）。可以通过方法[`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties)返回的DocumentProperties实例进行更改。请参阅[`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties)方法摘要中的示例。 |
| [LinksUpToDate](../../aspose.slides/idocumentproperties/linksuptodate) { get; set; } | 指示文档中的超链接是否是最新的。设置此元素为**true**以表示超链接已更新。设置此元素为**false**以表示超链接已过时。可读写布尔值。 |
| [Manager](../../aspose.slides/idocumentproperties/manager) { get; set; } | 返回或设置经理属性。可读写字符串。 |
| [MultimediaClips](../../aspose.slides/idocumentproperties/multimediaclips) { get; } | 指定文档中存在的声音或视频剪辑的总数。只读Int32。 |
| [NameOfApplication](../../aspose.slides/idocumentproperties/nameofapplication) { get; set; } | 返回或设置应用程序的名称。可读写字符串。 |
| [Notes](../../aspose.slides/idocumentproperties/notes) { get; } | 指定包含备注的幻灯片数量。只读Int32。 |
| [Paragraphs](../../aspose.slides/idocumentproperties/paragraphs) { get; } | 指定文档中找到的段落总数（如适用）。只读Int32。 |
| [PresentationFormat](../../aspose.slides/idocumentproperties/presentationformat) { get; set; } | 返回或设置演示文稿的预期格式。可读写字符串。 |
| [RevisionNumber](../../aspose.slides/idocumentproperties/revisionnumber) { get; set; } | 返回或设置演示文稿的修订号。可读写Int32。 |
| [ScaleCrop](../../aspose.slides/idocumentproperties/scalecrop) { get; set; } | 指示文档缩略图的显示模式。设置此元素为**true**以启用文档缩略图的比例缩放显示。设置此元素为**false**以启用文档缩略图的剪裁，仅显示适合显示的部分。可读写布尔值。 |
| [SharedDoc](../../aspose.slides/idocumentproperties/shareddoc) { get; set; } | 确定演示文稿是否在多个人之间共享。可读写布尔值。 |
| [Slides](../../aspose.slides/idocumentproperties/slides) { get; } | 指定演示文稿文档中的幻灯片总数。只读Int32。 |
| [Subject](../../aspose.slides/idocumentproperties/subject) { get; set; } | 返回或设置演示文稿的主题。可读写字符串。 |
| [Title](../../aspose.slides/idocumentproperties/title) { get; set; } | 返回或设置演示文稿的标题。可读写字符串。 |
| [TitlesOfParts](../../aspose.slides/idocumentproperties/titlesofparts) { get; } | 指定每个文档部分的标题。这些部分不是文档部分，而是文档部分的概念表示。只读字符串[]。 |
| [TotalEditingTime](../../aspose.slides/idocumentproperties/totaleditingtime) { get; set; } | 演示文稿的总编辑时间。可读写TimeSpan。 |
| [Words](../../aspose.slides/idocumentproperties/words) { get; } | 指定文档中包含的单词总数。只读Int32。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/idocumentproperties/clearbuiltinproperties)() | 清除并设置所有内置属性的默认值。 |
| [ClearCustomProperties](../../aspose.slides/idocumentproperties/clearcustomproperties)() | 删除所有自定义属性。 |
| [ContainsCustomProperty](../../aspose.slides/idocumentproperties/containscustomproperty)(string) | 检查指定名称的自定义属性是否存在。 |
| [GetCustomPropertyName](../../aspose.slides/idocumentproperties/getcustompropertyname)(int) | 返回指定索引处的自定义属性名称。 |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | 从自定义属性中获取命名的布尔值。 |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | 从自定义属性中获取命名的DateTime值。 |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | 从自定义属性中获取命名的双精度值。 |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | 从自定义属性中获取命名的浮点值。 |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | 从自定义属性中获取命名的整数值。 |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | 从自定义属性中获取命名的字符串值。 |
| [RemoveCustomProperty](../../aspose.slides/idocumentproperties/removecustomproperty)(string) | 删除与指定名称关联的自定义属性。 |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | 设置命名的布尔自定义属性。 |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | 设置命名的DateTime自定义属性。 |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | 设置命名的双精度自定义属性。 |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | 设置命名的浮点自定义属性。 |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | 设置命名的整数自定义属性。 |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | 设置命名的字符串自定义属性。 |

### 另请参见

* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->