---
title: DocumentProperties
second_title: Aspose.Slides for .NET API 参考
description: 表示演示文稿的属性
type: docs
weight: 2640
url: /zh/aspose.slides/documentproperties/
---
## DocumentProperties class

表示演示文稿的属性。

```csharp
public class DocumentProperties : IDocumentProperties, IGenericCloneable<IDocumentProperties>
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [DocumentProperties](documentproperties)() | 初始化类[`DocumentProperties`](../documentproperties)的新实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/documentproperties/applicationtemplate) { get; set; } | 返回或设置应用程序的模板。 读/写String。 |
| [AppVersion](../../aspose.slides/documentproperties/appversion) { get; } | 返回应用程序版本。 只读String。 |
| [Author](../../aspose.slides/documentproperties/author) { get; set; } | 返回或设置演示文稿的作者。 读/写String。 |
| [Category](../../aspose.slides/documentproperties/category) { get; set; } | 返回或设置演示文稿的类别。 读/写String。 |
| [Comments](../../aspose.slides/documentproperties/comments) { get; set; } | 返回或设置演示文稿的注释。 读/写String。 |
| [Company](../../aspose.slides/documentproperties/company) { get; set; } | 返回或设置公司属性。 读/写String。 |
| [ContentStatus](../../aspose.slides/documentproperties/contentstatus) { get; set; } | 返回或设置演示文稿的内容状态。 读/写String。 |
| [ContentType](../../aspose.slides/documentproperties/contenttype) { get; set; } | 返回或设置演示文稿的内容类型。 读/写String。 |
| [CountOfCustomProperties](../../aspose.slides/documentproperties/countofcustomproperties) { get; } | 返回集合中实际包含的自定义属性的数量。 只读Int32。 |
| [CreatedTime](../../aspose.slides/documentproperties/createdtime) { get; set; } | 返回创建演示文稿的日期。 读/写DateTime。 |
| [HyperlinkBase](../../aspose.slides/documentproperties/hyperlinkbase) { get; set; } | 返回或设置 HyperlinkBase 文档属性。 读/写String。 |
| [Item](../../aspose.slides/documentproperties/item) { get; set; } | 返回或设置与指定名称关联的自定义属性。 读/写Object。 |
| [Keywords](../../aspose.slides/documentproperties/keywords) { get; set; } | 返回或设置演示文稿的关键字。 读/写String。 |
| [LastPrinted](../../aspose.slides/documentproperties/lastprinted) { get; set; } | 返回上次打印演示文稿的日期。 读/写DateTime。 |
| [LastSavedBy](../../aspose.slides/documentproperties/lastsavedby) { get; set; } | 返回或设置最后修改演示文稿的人的姓名。 读/写String。 |
| [LastSavedTime](../../aspose.slides/documentproperties/lastsavedtime) { get; set; } | 返回上次修改演示文稿的日期。 在 Presentation.DocumentProperties 的情况下为只读（因为它将在 IPresentation 对象保存过程中在内部更新）。 可以通过方法返回的 DocumentProperties 实例进行更改[`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties) 请参见:::R5 中的示例:M:Aspose.Slides.IPresentationInfo.UpdateDocumentProperties(Aspose.Slides.IDocumentProperties):::方法总结。 |
| [Manager](../../aspose.slides/documentproperties/manager) { get; set; } | 返回或设置管理器属性。 读/写String。 |
| [NameOfApplication](../../aspose.slides/documentproperties/nameofapplication) { get; set; } | 返回或设置应用程序的名称。 读/写String。 |
| [PresentationFormat](../../aspose.slides/documentproperties/presentationformat) { get; set; } | 返回或设置演示文稿的预期格式。 读/写String。 |
| [RevisionNumber](../../aspose.slides/documentproperties/revisionnumber) { get; set; } | 返回或设置演示版本号。 读/写Int32。 |
| [SharedDoc](../../aspose.slides/documentproperties/shareddoc) { get; set; } | 确定演示文稿是否在多人之间共享。 读/写Boolean。 |
| [Subject](../../aspose.slides/documentproperties/subject) { get; set; } | 返回或设置演示的主题。 读/写String。 |
| [Title](../../aspose.slides/documentproperties/title) { get; set; } | 返回或设置演示文稿的标题。 读/写String。 |
| [TotalEditingTime](../../aspose.slides/documentproperties/totaleditingtime) { get; set; } | 演示文稿的总编辑时间。 读/写TimeSpan。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/documentproperties/clearbuiltinproperties)() | 清除并设置所有内置属性的默认值。 |
| [ClearCustomProperties](../../aspose.slides/documentproperties/clearcustomproperties)() | 删除所有自定义属性。 |
| [Clone](../../aspose.slides/documentproperties/clone)() | 克隆当前对象 |
| [CloneT](../../aspose.slides/documentproperties/clonet)() | 克隆当前对象 |
| [ContainsCustomProperty](../../aspose.slides/documentproperties/containscustomproperty)(string) | 检查具有指定名称的自定义属性的存在。 |
| [GetCustomPropertyName](../../aspose.slides/documentproperties/getcustompropertyname)(int) | 返回指定索引处的自定义属性名称。 |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | 从自定义属性中获取命名布尔值。 |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | 从自定义属性中获取命名的 DateTime 值。 |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | 从自定义属性中获取命名的双精度值。 |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | 从自定义属性中获取命名的浮点值。 |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | 从自定义属性中获取命名整数值。 |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | 从自定义属性中获取命名字符串值。 |
| [RemoveCustomProperty](../../aspose.slides/documentproperties/removecustomproperty)(string) | 删除与指定名称关联的自定义属性。 |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | 设置命名布尔自定义属性。 |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | 设置命名的 DateTime 自定义属性。 |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | 设置命名双自定义属性。 |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | 设置命名浮点自定义属性。 |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | 设置命名整数自定义属性。 |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | 设置命名字符串自定义属性。 |

### 也可以看看

* interface [IDocumentProperties](../idocumentproperties)
* interface [IGenericCloneable&lt;T&gt;](../igenericcloneable-1)
* 命名空间 [Aspose.Slides](../../aspose.slides)
* 部件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
