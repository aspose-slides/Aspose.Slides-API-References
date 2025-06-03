---
title: DocumentProperties
second_title: Aspose.Slides for .NET API 参考
description: 表示演示文稿的属性。
type: docs
weight: 2700
url: /zh/aspose.slides/documentproperties/
---

## DocumentProperties 类

表示演示文稿的属性。

```csharp
public class DocumentProperties : IDocumentProperties, IGenericCloneable<IDocumentProperties>
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [DocumentProperties](documentproperties)() | 初始化类 [`DocumentProperties`](../documentproperties) 的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/documentproperties/applicationtemplate) { get; set; } | 返回或设置应用程序的模板。可读写字符串。 |
| [AppVersion](../../aspose.slides/documentproperties/appversion) { get; } | 返回应用程序版本。只读字符串。 |
| [Author](../../aspose.slides/documentproperties/author) { get; set; } | 返回或设置演示文稿的作者。可读写字符串。 |
| [Category](../../aspose.slides/documentproperties/category) { get; set; } | 返回或设置演示文稿的类别。可读写字符串。 |
| [Comments](../../aspose.slides/documentproperties/comments) { get; set; } | 返回或设置演示文稿的评论。可读写字符串。 |
| [Company](../../aspose.slides/documentproperties/company) { get; set; } | 返回或设置公司属性。可读写字符串。 |
| [ContentStatus](../../aspose.slides/documentproperties/contentstatus) { get; set; } | 返回或设置演示文稿的内容状态。可读写字符串。 |
| [ContentType](../../aspose.slides/documentproperties/contenttype) { get; set; } | 返回或设置演示文稿的内容类型。可读写字符串。 |
| [CountOfCustomProperties](../../aspose.slides/documentproperties/countofcustomproperties) { get; } | 返回集合中实际包含的自定义属性的数量。只读 Int32。 |
| [CreatedTime](../../aspose.slides/documentproperties/createdtime) { get; set; } | 返回演示文稿创建的日期。值为 UTC 时间。可读写 DateTime。 |
| [HeadingPairs](../../aspose.slides/documentproperties/headingpairs) { get; } | 指示文档部分的分组及每组中的部分数量。只读 IHeadingPair[]。 |
| [HiddenSlides](../../aspose.slides/documentproperties/hiddenslides) { get; } | 返回演示文稿文档中隐藏幻灯片的数量。只读 Int32。 |
| [HyperlinkBase](../../aspose.slides/documentproperties/hyperlinkbase) { get; set; } | 返回或设置 HyperlinkBase 文档属性。可读写字符串。 |
| [HyperlinksChanged](../../aspose.slides/documentproperties/hyperlinkschanged) { get; set; } | 指定此部分中的一个或多个超链接仅在此部分由制作方更新。下一个打开该文档的制作方应使用此部分中指定的新超链接更新超链接关系。可读写布尔值。 |
| [Item](../../aspose.slides/documentproperties/item) { get; set; } | 返回或设置与指定名称关联的自定义属性。可读写对象。 |
| [Keywords](../../aspose.slides/documentproperties/keywords) { get; set; } | 返回或设置演示文稿的关键词。可读写字符串。 |
| [LastPrinted](../../aspose.slides/documentproperties/lastprinted) { get; set; } | 返回演示文稿最后一次打印的日期。可读写 DateTime。 |
| [LastSavedBy](../../aspose.slides/documentproperties/lastsavedby) { get; set; } | 返回或设置最后修改演示文稿的人员名称。可读写字符串。 |
| [LastSavedTime](../../aspose.slides/documentproperties/lastsavedtime) { get; set; } | 返回演示文稿最后修改的日期。值为 UTC 时间。对于 Presentation.DocumentProperties 是只读的（因为在保存 IPresentation 对象的过程中会内部更新）。可以通过 [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties) 方法返回的 DocumentProperties 实例更改。请参见 [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties) 方法摘要中的示例。 |
| [LinksUpToDate](../../aspose.slides/documentproperties/linksuptodate) { get; set; } | 指示文档中的超链接是否为最新。将此元素设置为 **true** 表示超链接已更新。将此元素设置为 **false** 表示超链接已过期。可读写布尔值。 |
| [Manager](../../aspose.slides/documentproperties/manager) { get; set; } | 返回或设置经理属性。可读写字符串。 |
| [MultimediaClips](../../aspose.slides/documentproperties/multimediaclips) { get; } | 返回文档中存在的音频或视频剪辑的总数量。只读 Int32。 |
| [NameOfApplication](../../aspose.slides/documentproperties/nameofapplication) { get; set; } | 返回或设置应用程序的名称。可读写字符串。 |
| [Notes](../../aspose.slides/documentproperties/notes) { get; } | 返回包含备注的演示文稿幻灯片的数量。只读 Int32。 |
| [Paragraphs](../../aspose.slides/documentproperties/paragraphs) { get; } | 如果适用，返回文档中找到的段落的总数量。只读 Int32。 |
| [PresentationFormat](../../aspose.slides/documentproperties/presentationformat) { get; set; } | 返回或设置演示文稿的预期格式。可读写字符串。 |
| [RevisionNumber](../../aspose.slides/documentproperties/revisionnumber) { get; set; } | 返回或设置演示文稿的修订号。可读写 Int32。 |
| [ScaleCrop](../../aspose.slides/documentproperties/scalecrop) { get; set; } | 指示文档缩略图的显示模式。将此元素设置为 **true** 以启用文档缩略图的缩放。将此元素设置为 **false** 以启用文档缩略图的裁剪，仅显示适合显示的部分。可读写布尔值。 |
| [SharedDoc](../../aspose.slides/documentproperties/shareddoc) { get; set; } | 确定演示文稿是否在多个人员之间共享。可读写布尔值。 |
| [Slides](../../aspose.slides/documentproperties/slides) { get; } | 返回演示文稿文档中的幻灯片总数量。只读 Int32。 |
| [Subject](../../aspose.slides/documentproperties/subject) { get; set; } | 返回或设置演示文稿的主题。可读写字符串。 |
| [Title](../../aspose.slides/documentproperties/title) { get; set; } | 返回或设置演示文稿的标题。可读写字符串。 |
| [TitlesOfParts](../../aspose.slides/documentproperties/titlesofparts) { get; } | 指定每个文档部分的标题。这些部分不是文档部分，而是文档部分的概念表示。只读字符串[]。 |
| [TotalEditingTime](../../aspose.slides/documentproperties/totaleditingtime) { get; set; } | 演示文稿的总编辑时间。可读写 TimeSpan。 |
| [Words](../../aspose.slides/documentproperties/words) { get; } | 返回文档中包含的单词总数。只读 Int32。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/documentproperties/clearbuiltinproperties)() | 清除并为所有内置属性设置默认值。 |
| [ClearCustomProperties](../../aspose.slides/documentproperties/clearcustomproperties)() | 移除所有自定义属性。 |
| [Clone](../../aspose.slides/documentproperties/clone)() | 克隆当前对象 |
| [CloneT](../../aspose.slides/documentproperties/clonet)() | 克隆当前对象 |
| [ContainsCustomProperty](../../aspose.slides/documentproperties/containscustomproperty)(string) | 检查指定名称的自定义属性是否存在。 |
| [GetCustomPropertyName](../../aspose.slides/documentproperties/getcustompropertyname)(int) | 返回指定索引的自定义属性名称。 |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | 从自定义属性中获取命名的布尔值。 |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | 从自定义属性中获取命名的 DateTime 值。 |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | 从自定义属性中获取命名的 double 值。 |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | 从自定义属性中获取命名的 float 值。 |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | 从自定义属性中获取命名的整数值。 |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | 从自定义属性中获取命名的字符串值。 |
| [RemoveCustomProperty](../../aspose.slides/documentproperties/removecustomproperty)(string) | 移除与指定名称关联的自定义属性。 |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | 设置命名的布尔自定义属性。 |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | 设置命名的 DateTime 自定义属性。 |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | 设置命名的 double 自定义属性。 |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | 设置命名的 float 自定义属性。 |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | 设置命名的整数自定义属性。 |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | 设置命名的字符串自定义属性。 |

### 示例

以下示例演示如何访问 PowerPoint 演示文稿的内置属性。

```csharp
[C#]
// 实例化表示演示文稿的 Presentation 类
using (Presentation pres = new Presentation(dataDir + "AccessBuiltin Properties.pptx"))
{
	// 创建与演示文稿关联的 IDocumentProperties 对象的引用
	IDocumentProperties documentProperties = pres.DocumentProperties;
	// 显示内置属性
	Console.WriteLine("类别 : " + documentProperties.Category);
	Console.WriteLine("当前状态 : " + documentProperties.ContentStatus);
	Console.WriteLine("创建日期 : " + documentProperties.CreatedTime);
	Console.WriteLine("作者 : " + documentProperties.Author);
	Console.WriteLine("描述 : " + documentProperties.Comments);
}
```

以下示例演示如何修改 PowerPoint 演示文稿的内置属性。

```csharp
[C#]
// 实例化表示演示文稿的 Presentation 类
using (Presentation presentation = new Presentation(dataDir + "ModifyBuiltinProperties.pptx"))
{
	// 创建与演示文稿关联的 IDocumentProperties 对象的引用
	IDocumentProperties documentProperties = presentation.DocumentProperties;
	// 设置内置属性
	documentProperties.Author = "Aspose.Slides for .NET";
	documentProperties.Title = "修改演示文稿属性";
	documentProperties.Subject = "Aspose 主题";
	// 将演示文稿保存到文件
	presentation.Save(dataDir + "DocumentProperties_out.pptx", SaveFormat.Pptx);
}
```

### 另见

* 接口 [IDocumentProperties](../idocumentproperties)
* 接口 [IGenericCloneable&lt;T&gt;](../igenericcloneable-1)
* 命名空间 [Aspose.Slides](../../aspose.slides)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->