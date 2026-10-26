---
title: DocumentProperties
second_title: Aspose.Slides for C++ API 参考
description: 表示演示文稿的属性。
type: docs
weight: 794
url: /zh/aspose.slides/documentproperties/
---
## DocumentProperties 类


表示演示文稿的属性。

```cpp
class DocumentProperties : public Aspose::Slides::IDocumentProperties,
                           public Aspose::Slides::IGenericCloneable<System::SharedPtr<Aspose::Slides::IDocumentProperties>>
```

## 方法

| 方法 | 描述 |
| --- | --- |
| void [ClearBuiltInProperties](./clearbuiltinproperties/)() override | 清除并设置所有内置属性的默认值。 |
| void [ClearCustomProperties](./clearcustomproperties/)() override | 移除所有自定义属性。 |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [Clone](./clone/)() override | 克隆当前对象 |
| [System::SharedPtr](../../system/sharedptr/)\<[IDocumentProperties](../idocumentproperties/)\> [CloneT](./clonet/)() override | 克隆当前对象 |
| **bool** [ContainsCustomProperty](./containscustomproperty/)([System::String](../../system/string/)) override | 检查是否存在具有指定名称的自定义属性。 |
| [DocumentProperties](./documentproperties/)() | 初始化类 [DocumentProperties](./) 的新实例。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，即使根据 IEC 60559:1989 两个 NaN 也被视为相等，尽管 NaN 与任何值（包括 NaN）都不相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，即使根据 IEC 60559:1989 两个 NaN 也被视为相等，尽管 NaN 与任何值（包括 NaN）都不相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| [System::String](../../system/string/) [get_ApplicationTemplate](./get_applicationtemplate/)() override | 返回应用程序的模板。阅读 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_AppVersion](./get_appversion/)() override | 返回应用程序版本。只读 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_Author](./get_author/)() override | 返回演示文稿的作者。阅读 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_Category](./get_category/)() override | 返回演示文稿的类别。阅读 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_Comments](./get_comments/)() override | 返回演示文稿的评论。阅读 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_Company](./get_company/)() override | 返回公司属性。阅读 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_ContentStatus](./get_contentstatus/)() override | 返回演示文稿的内容状态。阅读 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_ContentType](./get_contenttype/)() override | 返回演示文稿的内容类型。阅读 [System::String](../../system/string/)。 |
| **int32_t** [get_CountOfCustomProperties](./get_countofcustomproperties/)() override | 返回集合中实际包含的自定义属性数量。只读 **int32_t**。 |
| [System::DateTime](../../system/datetime/) [get_CreatedTime](./get_createdtime/)() override | 返回演示文稿创建的日期。值为 UTC。阅读 [System::DateTime](../../system/datetime/)。 |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IHeadingPair](../iheadingpair/)\>\> [get_HeadingPairs](./get_headingpairs/)() override | 指示文档部分的分组以及每组的部分数量。只读 [System::ArrayPtr<System::SharedPtr<IHeadingPair>>](../../system/arrayptr/)。 |
| **int32_t** [get_HiddenSlides](./get_hiddenslides/)() override | 返回演示文稿中隐藏幻灯片的数量。只读 **int32_t**。 |
| [System::String](../../system/string/) [get_HyperlinkBase](./get_hyperlinkbase/)() override | 返回 HyperlinkBase 文档属性。阅读 [System::String](../../system/string/)。 |
| **bool** [get_HyperlinksChanged](./get_hyperlinkschanged/)() override | 指定此部分中的一个或多个超链接已由生成器专门在此部分更新。下一个打开此文档的生成器应使用此部分指定的新超链接更新超链接关系。只读 **bool**。 |
| [System::String](../../system/string/) [get_Keywords](./get_keywords/)() override | 返回演示文稿的关键词。阅读 [System::String](../../system/string/)。 |
| [System::DateTime](../../system/datetime/) [get_LastPrinted](./get_lastprinted/)() override | 返回演示文稿上次打印的日期。阅读 [System::DateTime](../../system/datetime/)。 |
| [System::String](../../system/string/) [get_LastSavedBy](./get_lastsavedby/)() override | 返回最后修改演示文稿的人的姓名。阅读 [System::String](../../system/string/)。 |
| [System::DateTime](../../system/datetime/) [get_LastSavedTime](./get_lastsavedtime/)() override | 返回演示文稿最后修改的日期。值为 UTC。在 [Presentation::get_DocumentProperties](../presentation/get_documentproperties/) 情况下为只读（因为在 [IPresentation](../ipresentation/) 对象保存过程中会内部更新）。可通过 [DocumentProperties](./) 实例（由方法 [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/) 返回）进行更改。请参见 [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/) 方法摘要中的示例。 |
| **bool** [get_LinksUpToDate](./get_linksuptodate/)() override | 指示文档中的超链接是否是最新的。将此元素设为 **true** 表示超链接已更新。将此元素设为 **false** 表示超链接已过期。只读 **bool**。 |
| [System::String](../../system/string/) [get_Manager](./get_manager/)() override | 返回 manager 属性。阅读 [System::String](../../system/string/)。 |
| **int32_t** [get_MultimediaClips](./get_multimediaclips/)() override | 返回文档中存在的音频或视频剪辑的总数量。只读 **int32_t**。 |
| [System::String](../../system/string/) [get_NameOfApplication](./get_nameofapplication/)() override | 返回应用程序的名称。阅读 [System::String](../../system/string/)。 |
| **int32_t** [get_Notes](./get_notes/)() override | 返回包含备注的演示文稿幻灯片数量。只读 **int32_t**。 |
| **int32_t** [get_Paragraphs](./get_paragraphs/)() override | 返回文档中找到的段落总数（如适用）。只读 **int32_t**。 |
| [System::String](../../system/string/) [get_PresentationFormat](./get_presentationformat/)() override | 返回演示文稿的预期格式。阅读 [System::String](../../system/string/)。 |
| **int32_t** [get_RevisionNumber](./get_revisionnumber/)() override | 返回演示文稿的修订号。读取 **int32_t**。 |
| **bool** [get_ScaleCrop](./get_scalecrop/)() override | 指示文档缩略图的显示模式。将此元素设为 **true** 以启用将文档缩略图缩放至显示。将此元素设为 **false** 以启用裁剪文档缩略图，仅显示适合显示的部分。只读 **bool**。 |
| **bool** [get_SharedDoc](./get_shareddoc/)() override | 确定演示文稿是否在多个人之间共享。只读 **bool**。 |
| **int32_t** [get_Slides](./get_slides/)() override | 返回演示文稿文档中的幻灯片总数。只读 **int32_t**。 |
| [System::String](../../system/string/) [get_Subject](./get_subject/)() override | 返回演示文稿的主题。阅读 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_Title](./get_title/)() override | 返回演示文稿的标题。阅读 [System::String](../../system/string/)。 |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_TitlesOfParts](./get_titlesofparts/)() override | 指定每个文档部分的标题。这些部分不是文档部分，而是文档章节的概念性表示。只读 [System::ArrayPtr<System::String>](../../system/arrayptr/)。 |
| [System::TimeSpan](../../system/timespan/) [get_TotalEditingTime](./get_totaleditingtime/)() override | 演示文稿的总编辑时间。阅读 [System::TimeSpan](../../system/timespan/)。 |
| **int32_t** [get_Words](./get_words/)() override | 返回文档中包含的单词总数。只读 **int32_t**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| [System::String](../../system/string/) [GetCustomPropertyName](./getcustompropertyname/)(**int32_t**) override | 返回指定索引处的自定义属性名称。 |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **bool**\&) override | 从自定义属性中获取具名布尔值。 |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **int32_t**\&) override | 从自定义属性中获取具名整数值。 |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)\&) override | 从自定义属性中获取具名 DateTime 值。 |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)\&) override | 从自定义属性中获取具名字符串值。 |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **float**\&) override | 从自定义属性中获取具名 float 值。 |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **double**\&) override | 从自定义属性中获取具名 double 值。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的哈希。 |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISensitivityLabel](../isensitivitylabel/)\>\> [GetSensitivityLabels](./getsensitivitylabels/)() override | 获取自定义文档属性中的敏感性标签数组（Microsoft Information Protection SDK 元数据）。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [idx_get](./idx_get/)([System::String](../../system/string/)) override | 返回与指定名称关联的自定义属性。阅读 [System::Object](../../system/object/)。 |
| void [idx_set](./idx_set/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 设置与指定名称关联的自定义属性。写入 [System::Object](../../system/object/)。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 描述的类型实例。相当于 C# 的 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
| [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，仅初始化新对象并启用子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，仅初始化新对象并启用子类的拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 针对 string 与 nullptr 情况的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 针对字符串情况的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [RemoveCustomProperty](./removecustomproperty/)([System::String](../../system/string/)) override | 删除与指定名称关联的自定义属性。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| void [set_ApplicationTemplate](./set_applicationtemplate/)([System::String](../../system/string/)) override | 设置应用程序的模板。写入 [System::String](../../system/string/)。 |
| void [set_Author](./set_author/)([System::String](../../system/string/)) override | 设置演示文稿的作者。写入 [System::String](../../system/string/)。 |
| void [set_Category](./set_category/)([System::String](../../system/string/)) override | 设置演示文稿的类别。写入 [System::String](../../system/string/)。 |
| void [set_Comments](./set_comments/)([System::String](../../system/string/)) override | 设置演示文稿的评论。写入 [System::String](../../system/string/)。 |
| void [set_Company](./set_company/)([System::String](../../system/string/)) override | 设置公司属性。写入 [System::String](../../system/string/)。 |
| void [set_ContentStatus](./set_contentstatus/)([System::String](../../system/string/)) override | 设置演示文稿的内容状态。写入 [System::String](../../system/string/)。 |
| void [set_ContentType](./set_contenttype/)([System::String](../../system/string/)) override | 设置演示文稿的内容类型。写入 [System::String](../../system/string/)。 |
| void [set_CreatedTime](./set_createdtime/)([System::DateTime](../../system/datetime/)) override | 返回演示文稿创建的日期。值为 UTC。写入 [System::DateTime](../../system/datetime/)。 |
| void [set_HyperlinkBase](./set_hyperlinkbase/)([System::String](../../system/string/)) override | 设置 HyperlinkBase 文档属性。写入 [System::String](../../system/string/)。 |
| void [set_HyperlinksChanged](./set_hyperlinkschanged/)(**bool**) override | 指定此部分的一个或多个超链接已由生成器专门在此部分更新。下一个打开此文档的生成器应使用此部分指定的新超链接更新超链接关系。写入 **bool**。 |
| void [set_Keywords](./set_keywords/)([System::String](../../system/string/)) override | 设置演示文稿的关键词。写入 [System::String](../../system/string/)。 |
| void [set_LastPrinted](./set_lastprinted/)([System::DateTime](../../system/datetime/)) override | 返回演示文稿上次打印的日期。写入 [System::DateTime](../../system/datetime/)。 |
| void [set_LastSavedBy](./set_lastsavedby/)([System::String](../../system/string/)) override | 设置最后修改演示文稿的人的姓名。写入 [System::String](../../system/string/)。 |
| void [set_LastSavedTime](./set_lastsavedtime/)([System::DateTime](../../system/datetime/)) override | 返回演示文稿最后修改的日期。值为 UTC。在 [Presentation::get_DocumentProperties](../presentation/get_documentproperties/) 情况下为只读（因为在 [IPresentation](../ipresentation/) 对象保存过程中会内部更新）。可通过 [DocumentProperties](./) 实例（由方法 [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/) 返回）进行更改。请参见 [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/) 方法摘要中的示例。 |
| void [set_LinksUpToDate](./set_linksuptodate/)(**bool**) override | 指示文档中的超链接是否是最新的。将此元素设为 **true** 表示已更新。将此元素设为 **false** 表示已过期。写入 **bool**。 |
| void [set_Manager](./set_manager/)([System::String](../../system/string/)) override | 设置 manager 属性。写入 [System::String](../../system/string/)。 |
| void [set_NameOfApplication](./set_nameofapplication/)([System::String](../../system/string/)) override | 设置应用程序的名称。写入 [System::String](../../system/string/)。 |
| void [set_PresentationFormat](./set_presentationformat/)([System::String](../../system/string/)) override | 设置演示文稿的预期格式。写入 [System::String](../../system/string/)。 |
| void [set_RevisionNumber](./set_revisionnumber/)(**int32_t**) override | 设置演示文稿的修订号。写入 **int32_t**。 |
| void [set_ScaleCrop](./set_scalecrop/)(**bool**) override | 指示文档缩略图的显示模式。将此元素设为 **true** 以启用将文档缩略图缩放至显示。将此元素设为 **false** 以启用裁剪文档缩略图，仅显示适合显示的部分。写入 **bool**。 |
| void [set_SharedDoc](./set_shareddoc/)(**bool**) override | 确定演示文稿是否在多个人之间共享。写入 **bool**。 |
| void [set_Subject](./set_subject/)([System::String](../../system/string/)) override | 设置演示文稿的主题。写入 [System::String](../../system/string/)。 |
| void [set_Title](./set_title/)([System::String](../../system/string/)) override | 设置演示文稿的标题。写入 [System::String](../../system/string/)。 |
| void [set_TotalEditingTime](./set_totaleditingtime/)([System::TimeSpan](../../system/timespan/)) override | 演示文稿的总编辑时间。写入 [System::TimeSpan](../../system/timespan/)。 |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **bool**) override | 设置具名布尔自定义属性。 |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **int32_t**) override | 设置具名整数自定义属性。 |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)) override | 设置具名 DateTime 自定义属性。 |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)) override | 设置具名字符串自定义属性。 |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **float**) override | 设置具名 float 自定义属性。 |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **double**) override | 设置具名 double 自定义属性。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 备注


下面的示例展示了如何访问 PowerPoint [Presentation](../presentation/) 的内置属性。 
```cpp
// 实例化表示演示文稿的 Presentation 类
auto pres = System::MakeObject<Presentation>(dataDir + u"AccessBuiltin Properties.pptx");

// Create a reference to IDocumentProperties object associated with Presentation
System::SharedPtr<IDocumentProperties> documentProperties = pres->get_DocumentProperties();
// Display the builtin properties
System::Console::WriteLine(System::String(u"Category : ") + documentProperties->get_Category());
System::Console::WriteLine(System::String(u"Current Status : ") + documentProperties->get_ContentStatus());
System::Console::WriteLine(System::String(u"Creation Date : ") + documentProperties->get_CreatedTime());
System::Console::WriteLine(System::String(u"Author : ") + documentProperties->get_Author());
System::Console::WriteLine(System::String(u"Description : ") + documentProperties->get_Comments());
```
下面的示例展示了如何修改 PowerPoint [Presentation](../presentation/) 的内置属性。 
```cpp
// 实例化表示演示文稿的 Presentation 类
auto presentation = System::MakeObject<Presentation>(dataDir + u"ModifyBuiltinProperties.pptx");

// 创建与 Presentation 关联的 IDocumentProperties 对象的引用
System::SharedPtr<IDocumentProperties> documentProperties = presentation->get_DocumentProperties();
// 设置内置属性
documentProperties->set_Author(u"Aspose.Slides for .NET");
documentProperties->set_Title(u"Modifying Presentation Properties");
documentProperties->set_Subject(u"Aspose Subject");
// 将演示文稿保存到文件
presentation->Save(u"DocumentProperties_out.pptx", SaveFormat::Pptx);
```

## 另请参见

* 类 [IDocumentProperties](../idocumentproperties/)
* 类 [IGenericCloneable](../igenericcloneable/)
* 命名空间 [Aspose::Slides](../)
* 库 [Aspose.Slides](../../)