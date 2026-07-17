---
title: IDocumentProperties
second_title: Aspose.Slides for C++ API 参考
description: 表示演示文稿的属性。
type: docs
weight: 1977
url: /zh/aspose.slides/idocumentproperties/
---
## IDocumentProperties 类

表示演示文稿的属性。

```cpp
class IDocumentProperties : public virtual System::Object
```

## 方法

| Method | Description |
| --- | --- |
| virtual void [ClearBuiltInProperties](./clearbuiltinproperties/)() | 清除并为所有内置属性设置默认值。 |
| virtual void [ClearCustomProperties](./clearcustomproperties/)() | 删除所有自定义属性。 |
| virtual **bool** [ContainsCustomProperty](./containscustomproperty/)([System::String](../../system/string/)) | 检查是否存在具有指定名称的自定义属性。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 标准，NaN 与任何值（包括 NaN）都不相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 标准，NaN 与任何值（包括 NaN）都不相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| virtual [System::String](../../system/string/) [get_ApplicationTemplate](./get_applicationtemplate/)() | 返回应用程序的模板。读取 [System::String](../../system/string/)。 |
| virtual [System::String](../../system/string/) [get_AppVersion](./get_appversion/)() | 返回应用程序版本。只读 [System::String](../../system/string/)。 |
| virtual [System::String](../../system/string/) [get_Author](./get_author/)() | 返回演示文稿的作者。读取 [System::String](../../system/string/)。 |
| virtual [System::String](../../system/string/) [get_Category](./get_category/)() | 返回演示文稿的类别。读取 [System::String](../../system/string/)。 |
| virtual [System::String](../../system/string/) [get_Comments](./get_comments/)() | 返回演示文稿的注释。读取 [System::String](../../system/string/)。 |
| virtual [System::String](../../system/string/) [get_Company](./get_company/)() | 返回公司属性。读取 [System::String](../../system/string/)。 |
| virtual [System::String](../../system/string/) [get_ContentStatus](./get_contentstatus/)() | 返回演示文稿的内容状态。读取 [System::String](../../system/string/)。 |
| virtual [System::String](../../system/string/) [get_ContentType](./get_contenttype/)() | 返回演示文稿的内容类型。读取 [System::String](../../system/string/)。 |
| virtual **int32_t** [get_CountOfCustomProperties](./get_countofcustomproperties/)() | 返回集合中实际包含的自定义属性数量。只读 **int32_t**。 |
| virtual [System::DateTime](../../system/datetime/) [get_CreatedTime](./get_createdtime/)() | 返回演示文稿的创建日期。值为 UTC。读取 [System::DateTime](../../system/datetime/)。 |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IHeadingPair](../iheadingpair/)\>\> [get_HeadingPairs](./get_headingpairs/)() | 指示文档部分的分组以及每组的部分数量。只读 [System::ArrayPtr<System::SharedPtr<IHeadingPair>>](../../system/arrayptr/)。 |
| virtual **int32_t** [get_HiddenSlides](./get_hiddenslides/)() | 指定演示文稿文档中隐藏幻灯片的数量。只读 **int32_t**。 |
| virtual [System::String](../../system/string/) [get_HyperlinkBase](./get_hyperlinkbase/)() | 返回 HyperlinkBase 文档属性。读取 [System::String](../../system/string/)。 |
| virtual **bool** [get_HyperlinksChanged](./get_hyperlinkschanged/)() | 指定此部分中的一个或多个超链接已由生成者在此部分独占性更新。下一个打开此文档的生成者应使用此部分中指定的新超链接更新超链接关系。读取 **bool**。 |
| virtual [System::String](../../system/string/) [get_Keywords](./get_keywords/)() | 返回演示文稿的关键字。读取 [System::String](../../system/string/)。 |
| virtual [System::DateTime](../../system/datetime/) [get_LastPrinted](./get_lastprinted/)() | 返回演示文稿上次打印的日期。读取 [System::DateTime](../../system/datetime/)。 |
| virtual [System::String](../../system/string/) [get_LastSavedBy](./get_lastsavedby/)() | 返回最后修改演示文稿的人的姓名。读取 [System::String](../../system/string/)。 |
| virtual [System::DateTime](../../system/datetime/) [get_LastSavedTime](./get_lastsavedtime/)() | 返回演示文稿的最后修改日期。值为 UTC。对于 Presentation.DocumentProperties 为只读（因为在 [IPresentation](../ipresentation/) 对象保存过程中会内部更新）。可以通过 [DocumentProperties](../documentproperties/) 实例（由方法 [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/) 返回）进行更改。请参见 [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/) 方法摘要中的示例。 |
| virtual **bool** [get_LinksUpToDate](./get_linksuptodate/)() | 指示文档中的超链接是否是最新的。将此元素设置为 **true** 以表明超链接已更新。将此元素设置为 **false** 以表明超链接已过时。读取 **bool**。 |
| virtual [System::String](../../system/string/) [get_Manager](./get_manager/)() | 返回管理员属性。读取 [System::String](../../system/string/)。 |
| virtual **int32_t** [get_MultimediaClips](./get_multimediaclips/)() | 指定文档中存在的声音或视频剪辑的总数。只读 **int32_t**。 |
| virtual [System::String](../../system/string/) [get_NameOfApplication](./get_nameofapplication/)() | 返回应用程序的名称。读取 [System::String](../../system/string/)。 |
| virtual **int32_t** [get_Notes](./get_notes/)() | 指定包含备注的演示文稿幻灯片数量。只读 **int32_t**。 |
| virtual **int32_t** [get_Paragraphs](./get_paragraphs/)() | 指定文档中（如适用）找到的段落总数。只读 **int32_t**。 |
| virtual [System::String](../../system/string/) [get_PresentationFormat](./get_presentationformat/)() | 返回演示文稿的预期格式。读取 [System::String](../../system/string/)。 |
| virtual **int32_t** [get_RevisionNumber](./get_revisionnumber/)() | 返回演示文稿的修订号。读取 **int32_t**。 |
| virtual **bool** [get_ScaleCrop](./get_scalecrop/)() | 指示文档缩略图的显示模式。将此元素设置为 **true** 以启用将文档缩略图缩放至显示。将此元素设置为 **false** 以启用裁剪文档缩略图，仅显示适合显示的部分。读取 **bool**。 |
| virtual **bool** [get_SharedDoc](./get_shareddoc/)() | 确定演示文稿是否在多个人之间共享。读取 **bool**。 |
| virtual **int32_t** [get_Slides](./get_slides/)() | 指定演示文稿文档中的幻灯片总数。只读 **int32_t**。 |
| virtual [System::String](../../system/string/) [get_Subject](./get_subject/)() | 返回演示文稿的主题。读取 [System::String](../../system/string/)。 |
| virtual [System::String](../../system/string/) [get_Title](./get_title/)() | 返回演示文稿的标题。读取 [System::String](../../system/string/)。 |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_TitlesOfParts](./get_titlesofparts/)() | 指定每个文档部分的标题。这些部分不是文档部分，而是文档章节的概念表示。只读 [System::ArrayPtr<System::String>](../../system/arrayptr/)。 |
| virtual [System::TimeSpan](../../system/timespan/) [get_TotalEditingTime](./get_totaleditingtime/)() | 演示文稿的总编辑时间。读取 [System::TimeSpan](../../system/timespan/)。 |
| virtual **int32_t** [get_Words](./get_words/)() | 指定文档中包含的总单词数。只读 **int32_t**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual [System::String](../../system/string/) [GetCustomPropertyName](./getcustompropertyname/)(**int32_t**) | 返回指定索引处的自定义属性名称。 |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **bool**\&) | 从自定义属性获取具名布尔值。 |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **int32_t**\&) | 从自定义属性获取具名整数值。 |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)\&) | 从自定义属性获取具名 DateTime 值。 |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)\&) | 从自定义属性获取具名字符串值。 |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **float**\&) | 从自定义属性获取具名 float 值。 |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **double**\&) | 从自定义属性获取具名 double 值。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的哈希。 |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISensitivityLabel](../isensitivitylabel/)\>\> [GetSensitivityLabels](./getsensitivitylabels/)() | 从自定义文档属性获取敏感度标签数组（Microsoft Information Protection SDK 元数据）。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [idx_get](./idx_get/)([System::String](../../system/string/)) | 返回与指定名称关联的自定义属性。读取 [System::Object](../../system/object/)。 |
| virtual void [idx_set](./idx_set/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | 设置与指定名称关联的自定义属性。写入 [System::Object](../../system/object/)。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示由 targetType 描述的类型实例。相当于 C# 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 复制构造函数。实际上不复制任何内容，只是初始化新对象并启用子类的复制构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，只是初始化新对象并启用子类的复制构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 按引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 针对字符串和 nullptr 的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 针对字符串的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| virtual **bool** [RemoveCustomProperty](./removecustomproperty/)([System::String](../../system/string/)) | 移除与指定名称关联的自定义属性。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| virtual void [set_ApplicationTemplate](./set_applicationtemplate/)([System::String](../../system/string/)) | 设置应用程序的模板。写入 [System::String](../../system/string/)。 |
| virtual void [set_Author](./set_author/)([System::String](../../system/string/)) | 设置演示文稿的作者。写入 [System::String](../../system/string/)。 |
| virtual void [set_Category](./set_category/)([System::String](../../system/string/)) | 设置演示文稿的类别。写入 [System::String](../../system/string/)。 |
| virtual void [set_Comments](./set_comments/)([System::String](../../system/string/)) | 设置演示文稿的注释。写入 [System::String](../../system/string/)。 |
| virtual void [set_Company](./set_company/)([System::String](../../system/string/)) | 设置公司属性。写入 [System::String](../../system/string/)。 |
| virtual void [set_ContentStatus](./set_contentstatus/)([System::String](../../system/string/)) | 设置演示文稿的内容状态。写入 [System::String](../../system/string/)。 |
| virtual void [set_ContentType](./set_contenttype/)([System::String](../../system/string/)) | 设置演示文稿的内容类型。写入 [System::String](../../system/string/)。 |
| virtual void [set_CreatedTime](./set_createdtime/)([System::DateTime](../../system/datetime/)) | 返回演示文稿的创建日期。值为 UTC。写入 [System::DateTime](../../system/datetime/)。 |
| virtual void [set_HyperlinkBase](./set_hyperlinkbase/)([System::String](../../system/string/)) | 设置 HyperlinkBase 文档属性。写入 [System::String](../../system/string/)。 |
| virtual void [set_HyperlinksChanged](./set_hyperlinkschanged/)(**bool**) | 指定此部分中的一个或多个超链接已由生成者在此部分独占性更新。下一个打开此文档的生成者应使用此部分中指定的新超链接更新超链接关系。写入 **bool**。 |
| virtual void [set_Keywords](./set_keywords/)([System::String](../../system/string/)) | 设置演示文稿的关键字。写入 [System::String](../../system/string/)。 |
| virtual void [set_LastPrinted](./set_lastprinted/)([System::DateTime](../../system/datetime/)) | 返回演示文稿上次打印的日期。写入 [System::DateTime](../../system/datetime/)。 |
| virtual void [set_LastSavedBy](./set_lastsavedby/)([System::String](../../system/string/)) | 设置最后修改演示文稿的人的姓名。写入 [System::String](../../system/string/)。 |
| virtual void [set_LastSavedTime](./set_lastsavedtime/)([System::DateTime](../../system/datetime/)) | 返回演示文稿的最后修改日期。值为 UTC。对于 Presentation.DocumentProperties 为只读（因为在 [IPresentation](../ipresentation/) 对象保存过程中会内部更新），可以通过 [DocumentProperties](../documentproperties/) 实例（由方法 [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/) 返回）进行更改。请参见 [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/) 方法摘要中的示例。 |
| virtual void [set_LinksUpToDate](./set_linksuptodate/)(**bool**) | 指示文档中的超链接是否是最新的。将此元素设置为 **true** 以表明超链接已更新。将此元素设置为 **false** 以表明超链接已过时。写入 **bool**。 |
| virtual void [set_Manager](./set_manager/)([System::String](../../system/string/)) | 设置管理员属性。写入 [System::String](../../system/string/)。 |
| virtual void [set_NameOfApplication](./set_nameofapplication/)([System::String](../../system/string/)) | 设置应用程序的名称。写入 [System::String](../../system/string/)。 |
| virtual void [set_PresentationFormat](./set_presentationformat/)([System::String](../../system/string/)) | 设置演示文稿的预期格式。写入 [System::String](../../system/string/)。 |
| virtual void [set_RevisionNumber](./set_revisionnumber/)(**int32_t**) | 设置演示文稿的修订号。写入 **int32_t**。 |
| virtual void [set_ScaleCrop](./set_scalecrop/)(**bool**) | 指示文档缩略图的显示模式。将此元素设置为 **true** 以启用将文档缩略图缩放至显示。将此元素设置为 **false** 以启用裁剪文档缩略图，仅显示适合显示的部分。写入 **bool**。 |
| virtual void [set_SharedDoc](./set_shareddoc/)(**bool**) | 确定演示文稿是否在多个人之间共享。写入 **bool**。 |
| virtual void [set_Subject](./set_subject/)([System::String](../../system/string/)) | 设置演示文稿的主题。写入 [System::String](../../system/string/)。 |
| virtual void [set_Title](./set_title/)([System::String](../../system/string/)) | 设置演示文稿的标题。写入 [System::String](../../system/string/)。 |
| virtual void [set_TotalEditingTime](./set_totaleditingtime/)([System::TimeSpan](../../system/timespan/)) | 演示文稿的总编辑时间。写入 [System::TimeSpan](../../system/timespan/)。 |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **bool**) | 设置具名布尔自定义属性。 |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **int32_t**) | 设置具名整数自定义属性。 |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)) | 设置具名 DateTime 自定义属性。 |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)) | 设置具名字符串自定义属性。 |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **float**) | 设置具名 float 自定义属性。 |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **double**) | 设置具名 double 自定义属性。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享指针）。允许在容器中切换指针为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另请参阅

* 类 [Object](../../system/object/)
* 命名空间 [Aspose::Slides](../)
* 库 [Aspose.Slides](../../)