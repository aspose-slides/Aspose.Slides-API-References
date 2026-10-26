---
title: LoadOptions
second_title: Aspose.Slides C++ API 参考
description: 在加载演示文稿时，允许指定附加选项（例如格式或默认字体）。
type: docs
weight: 4395
url: /zh/aspose.slides/loadoptions/
---
## LoadOptions 类

在加载演示文稿时，允许指定附加选项（例如格式或默认字体）。

```cpp
class LoadOptions : public Aspose::Slides::ILoadOptions
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 在 C# 风格中比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 在 C# 风格中比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C#-style 浮点比较，即使根据 IEC 60559:1989，NaN 不等于任何值（包括 NaN），两个 NaN 也被视为相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C#-style 浮点比较，即使根据 IEC 60559:1989，NaN 不等于任何值（包括 NaN），两个 NaN 也被视为相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅用于内部目的。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IBlobManagementOptions](../iblobmanagementoptions/)\> [get_BlobManagementOptions](./get_blobmanagementoptions/)() override | 表示可用于管理大二进制对象（BLOB）处理行为的选项，例如使用临时文件或内存中最大 BLOB 字节数。这些选项旨在为特定环境或需求设置最佳的性能/内存消耗比率。 |
| [System::String](../../system/string/) [get_DefaultAsianFont](./get_defaultasianfont/)() override | 返回在未找到源字体时使用的亚洲字体。阅读 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_DefaultRegularFont](./get_defaultregularfont/)() override | 返回在未找到源字体时使用的常规字体。阅读 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_DefaultSymbolFont](./get_defaultsymbolfont/)() override | 返回在未找到源字体时使用的符号字体。阅读 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_DefaultTextLanguage](./get_defaulttextlanguage/)() override | 返回演示文稿文本的默认语言。阅读 [System::String](../../system/string/)。 |
| **bool** [get_DeleteEmbeddedBinaryObjects](./get_deleteembeddedbinaryobjects/)() override | 确定在加载演示文稿时 [Aspose.Slides](../) 是否会删除所有嵌入的二进制对象。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontSources](../ifontsources/)\> [get_DocumentLevelFontSources](./get_documentlevelfontsources/)() override | 指定演示文稿使用的外部字体来源。这些字体在演示文稿的整个生命周期内可用，并且不与其他演示文稿共享。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IInterruptionToken](../iinterruptiontoken/)\> [get_InterruptionToken](./get_interruptiontoken/)() override | 用于监视中断请求的令牌。 |
| [Aspose::Slides::LoadFormat](../loadformat/) [get_LoadFormat](./get_loadformat/)() override | 返回要加载的演示文稿格式。阅读 [Slides::LoadFormat](../loadformat/)。 |
| **bool** [get_OnlyLoadDocumentProperties](./get_onlyloaddocumentproperties/)() override | 如果演示文稿文件受密码保护，此属性才有意义。值为 true 表示仅从加密的演示文稿文件加载文档属性，并且应忽略密码。值为 false 表示必须使用正确的密码加载整个加密的演示文稿。如果演示文稿未加密，则始终忽略此属性值。如果加密文件的文档属性不是公开的且属性值为 true，则无法加载文档属性并会抛出异常。读取 **bool**。 |
| [System::String](../../system/string/) [get_Password](./get_password/)() override | 获取密码。阅读 [System::String](../../system/string/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IResourceLoadingCallback](../iresourceloadingcallback/)\> [get_ResourceLoadingCallback](./get_resourceloadingcallback/)() override | 返回管理外部资源加载的回调接口。阅读 [IResourceLoadingCallback](../iresourceloadingcallback/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ISpreadsheetOptions](../ispreadsheetoptions/)\> [get_SpreadsheetOptions](./get_spreadsheetoptions/)() override | 获取电子表格的选项。例如，这些选项会影响图表公式的计算。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](./get_warningcallback/)() override | 返回接收警告并决定加载过程是否继续或中止的对象。阅读 [Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 描述的类型实例。相当于 C# 的 'is' 运算符。 |
|  [LoadOptions](./loadoptions/)() | 创建新的默认加载选项。 |
|  [LoadOptions](./loadoptions/)([Aspose::Slides::LoadFormat](../loadformat/)) | 创建新的加载选项。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的锁定。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，只是初始化新对象并允许子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，只是初始化新对象并允许子类的拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 使用引用将值类型对象与 nullptr 进行比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 针对字符串和 nullptr 情形的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 针对字符串情形的特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 将共享引用计数减少指定的值。 |
| void [set_BlobManagementOptions](./set_blobmanagementoptions/)([System::SharedPtr](../../system/sharedptr/)\<[IBlobManagementOptions](../iblobmanagementoptions/)\>) override | 表示可用于管理大二进制对象（BLOB）处理行为的选项，例如使用临时文件或内存中最大 BLOB 字节数。这些选项旨在为特定环境或需求设置最佳的性能/内存消耗比率。 |
| void [set_DefaultAsianFont](./set_defaultasianfont/)([System::String](../../system/string/)) override | 设置在未找到源字体时使用的亚洲字体。写入 [System::String](../../system/string/)。 |
| void [set_DefaultRegularFont](./set_defaultregularfont/)([System::String](../../system/string/)) override | 设置在未找到源字体时使用的常规字体。写入 [System::String](../../system/string/)。 |
| void [set_DefaultSymbolFont](./set_defaultsymbolfont/)([System::String](../../system/string/)) override | 设置在未找到源字体时使用的符号字体。写入 [System::String](../../system/string/)。 |
| void [set_DefaultTextLanguage](./set_defaulttextlanguage/)([System::String](../../system/string/)) override | 设置演示文稿文本的默认语言。写入 [System::String](../../system/string/)。 |
| void [set_DeleteEmbeddedBinaryObjects](./set_deleteembeddedbinaryobjects/)(**bool**) override | 确定在加载演示文稿时 [Aspose.Slides](../) 是否会删除所有嵌入的二进制对象。 |
| void [set_DocumentLevelFontSources](./set_documentlevelfontsources/)([System::SharedPtr](../../system/sharedptr/)\<[IFontSources](../ifontsources/)\>) override | 指定演示文稿使用的外部字体来源。这些字体在演示文稿的整个生命周期内可用，并且不与其他演示文稿共享。 |
| void [set_InterruptionToken](./set_interruptiontoken/)([System::SharedPtr](../../system/sharedptr/)\<[IInterruptionToken](../iinterruptiontoken/)\>) override | 用于监视中断请求的令牌。 |
| void [set_LoadFormat](./set_loadformat/)([Aspose::Slides::LoadFormat](../loadformat/)) override | 设置要加载的演示文稿格式。写入 [Slides::LoadFormat](../loadformat/)。 |
| void [set_OnlyLoadDocumentProperties](./set_onlyloaddocumentproperties/)(**bool**) override | 如果演示文稿文件受密码保护，此属性才有意义。值为 true 表示仅从加密的演示文稿文件加载文档属性，并且应忽略密码。值为 false 表示必须使用正确的密码加载整个加密的演示文稿。如果演示文稿未加密，则始终忽略此属性值。如果加密文件的文档属性不是公开的且属性值为 true，则无法加载文档属性并会抛出异常。写入 **bool**。 |
| void [set_Password](./set_password/)([System::String](../../system/string/)) override | 设置密码。写入 [System::String](../../system/string/)。 |
| void [set_ResourceLoadingCallback](./set_resourceloadingcallback/)([System::SharedPtr](../../system/sharedptr/)\<[IResourceLoadingCallback](../iresourceloadingcallback/)\>) override | 设置管理外部资源加载的回调接口。写入 [IResourceLoadingCallback](../iresourceloadingcallback/)。 |
| void [set_SpreadsheetOptions](./set_spreadsheetoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISpreadsheetOptions](../ispreadsheetoptions/)\>) override | 获取电子表格的选项。例如，这些选项会影响图表公式的计算。 |
| void [set_WarningCallback](./set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | 设置接收警告并决定加载过程是否继续或中止的对象。写入 [Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享指针）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 参见

* 类 [ILoadOptions](../iloadoptions/)
* 命名空间 [Aspose::Slides](../)
* 库 [Aspose.Slides](../../)