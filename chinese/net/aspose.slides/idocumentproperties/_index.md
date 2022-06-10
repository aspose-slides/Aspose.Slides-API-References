---
title: IDocumentProperties
second_title: Aspose.Slides for .NET API 参考
description: 表示演示文稿的属性
type: docs
weight: 5210
url: /zh/net/aspose.slides/idocumentproperties/
---
## IDocumentProperties interface

表示演示文稿的属性。

```csharp
public interface IDocumentProperties
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/idocumentproperties/applicationtemplate) { get; set; } | 返回或设置应用程序的模板。 读/写String。 |
| [AppVersion](../../aspose.slides/idocumentproperties/appversion) { get; } | 返回应用程序版本。 只读String。 |
| [Author](../../aspose.slides/idocumentproperties/author) { get; set; } | 返回或设置演示文稿的作者。 读/写String。 |
| [Category](../../aspose.slides/idocumentproperties/category) { get; set; } | 返回或设置演示文稿的类别。 读/写String。 |
| [Comments](../../aspose.slides/idocumentproperties/comments) { get; set; } | 返回或设置演示文稿的注释。 读/写String。 |
| [Company](../../aspose.slides/idocumentproperties/company) { get; set; } | 返回或设置公司属性。 读/写String。 |
| [ContentStatus](../../aspose.slides/idocumentproperties/contentstatus) { get; set; } | 返回或设置演示文稿的内容状态。 读/写String。 |
| [ContentType](../../aspose.slides/idocumentproperties/contenttype) { get; set; } | 返回或设置演示文稿的内容类型。 读/写String。 |
| [CountOfCustomProperties](../../aspose.slides/idocumentproperties/countofcustomproperties) { get; } | 返回集合中实际包含的自定义属性的数量。 只读Int32。 |
| [CreatedTime](../../aspose.slides/idocumentproperties/createdtime) { get; set; } | 返回创建演示文稿的日期。 读/写DateTime。 |
| [HyperlinkBase](../../aspose.slides/idocumentproperties/hyperlinkbase) { get; set; } | 返回或设置 HyperlinkBase 文档属性。 读/写String。 |
| [Item](../../aspose.slides/idocumentproperties/item) { get; set; } | 返回或设置与指定名称关联的自定义属性。 读/写Object。 |
| [Keywords](../../aspose.slides/idocumentproperties/keywords) { get; set; } | 返回或设置演示文稿的关键字。 读/写String。 |
| [LastPrinted](../../aspose.slides/idocumentproperties/lastprinted) { get; set; } | 返回上次打印演示文稿的日期。 读/写DateTime。 |
| [LastSavedBy](../../aspose.slides/idocumentproperties/lastsavedby) { get; set; } | 返回或设置最后修改演示文稿的人的姓名。 读/写String。 |
| [LastSavedTime](../../aspose.slides/idocumentproperties/lastsavedtime) { get; set; } | 返回上次修改演示文稿的日期。 在 Presentation.DocumentProperties 的情况下为只读（因为它将在 IPresentation 对象保存过程中在内部更新）。 可以通过方法返回的 DocumentProperties 实例进行更改[`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties) 请参见:::R5 中的示例:M:Aspose.Slides.IPresentationInfo.UpdateDocumentProperties(Aspose.Slides.IDocumentProperties):::方法总结。 |
| [Manager](../../aspose.slides/idocumentproperties/manager) { get; set; } | 返回或设置管理器属性。 读/写String。 |
| [NameOfApplication](../../aspose.slides/idocumentproperties/nameofapplication) { get; set; } | 返回或设置应用程序的名称。 读/写String。 |
| [PresentationFormat](../../aspose.slides/idocumentproperties/presentationformat) { get; set; } | 返回或设置演示文稿的预期格式。 读/写String。 |
| [RevisionNumber](../../aspose.slides/idocumentproperties/revisionnumber) { get; set; } | 返回或设置演示版本号。 读/写Int32。 |
| [SharedDoc](../../aspose.slides/idocumentproperties/shareddoc) { get; set; } | 确定演示文稿是否在多人之间共享。 读/写Boolean。 |
| [Subject](../../aspose.slides/idocumentproperties/subject) { get; set; } | 返回或设置演示的主题。 读/写String。 |
| [Title](../../aspose.slides/idocumentproperties/title) { get; set; } | 返回或设置演示文稿的标题。 读/写String。 |
| [TotalEditingTime](../../aspose.slides/idocumentproperties/totaleditingtime) { get; set; } | 演示文稿的总编辑时间。 读/写TimeSpan。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/idocumentproperties/clearbuiltinproperties)() | 清除并设置所有内置属性的默认值。 |
| [ClearCustomProperties](../../aspose.slides/idocumentproperties/clearcustomproperties)() | 删除所有自定义属性。 |
| [ContainsCustomProperty](../../aspose.slides/idocumentproperties/containscustomproperty)(string) | 检查具有指定名称的自定义属性的存在。 |
| [GetCustomPropertyName](../../aspose.slides/idocumentproperties/getcustompropertyname)(int) | 返回指定索引处的自定义属性名称。 |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | 从自定义属性中获取命名布尔值。 |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | 从自定义属性中获取命名的 DateTime 值。 |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | 从自定义属性中获取命名的双精度值。 |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | 从自定义属性中获取命名的浮点值。 |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | 从自定义属性中获取命名整数值。 |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | 从自定义属性中获取命名字符串值。 |
| [RemoveCustomProperty](../../aspose.slides/idocumentproperties/removecustomproperty)(string) | 删除与指定名称关联的自定义属性。 |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | 设置命名布尔自定义属性。 |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | 设置命名的 DateTime 自定义属性。 |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | 设置命名双自定义属性。 |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | 设置命名浮点自定义属性。 |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | 设置命名整数自定义属性。 |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | 设置命名字符串自定义属性。 |

### 也可以看看

* 命名空间 [Aspose.Slides](../../aspose.slides)
* 部件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
