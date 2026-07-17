---
title: ILoadOptions
second_title: Aspose.Slides for C++ API 参考
description: 在加载演示文稿时允许指定附加选项（例如格式或默认字体）。
type: docs
weight: 2796
url: /zh/aspose.slides/iloadoptions/
---
## ILoadOptions 类

允许在加载演示文稿时指定其他选项（例如格式或默认字体）。

```cpp
class ILoadOptions : public virtual System::Object
```

## 方法

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点数比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点数比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBlobManagementOptions](../iblobmanagementoptions/)\> [get_BlobManagementOptions](./get_blobmanagementoptions/)() | 表示可用于管理大二进制对象 (BLOB) 处理行为的选项，例如使用临时文件或在内存中限制 BLOB 的最大字节数。这些选项旨在为特定环境或需求设定最佳的性能/内存消耗比率。 |
| virtual [System::String](../../system/string/) [get_DefaultAsianFont](./get_defaultasianfont/)() | 返回在未找到源字体时使用的亚洲字体。读取 [System::String](../../system/string/)。 |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](./get_defaultregularfont/)() | 返回在未找到源字体时使用的常规字体。读取 [System::String](../../system/string/)。 |
| virtual [System::String](../../system/string/) [get_DefaultSymbolFont](./get_defaultsymbolfont/)() | 返回在未找到源字体时使用的符号字体。读取 [System::String](../../system/string/)。 |
| virtual [System::String](../../system/string/) [get_DefaultTextLanguage](./get_defaulttextlanguage/)() | 返回演示文稿文本的默认语言。读取 [System::String](../../system/string/)。 |
| virtual **bool** [get_DeleteEmbeddedBinaryObjects](./get_deleteembeddedbinaryobjects/)() | 确定在加载演示文稿时 [Aspose.Slides](../) 是否会删除所有嵌入的二进制对象。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontSources](../ifontsources/)\> [get_DocumentLevelFontSources](./get_documentlevelfontsources/)() | 指定演示文稿使用的外部字体来源。这些字体在整个演示文稿生命周期内可用且不与其他演示文稿共享。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IInterruptionToken](../iinterruptiontoken/)\> [get_InterruptionToken](./get_interruptiontoken/)() | 用于监视中断请求的令牌。 |
| virtual [Aspose::Slides::LoadFormat](../loadformat/) [get_LoadFormat](./get_loadformat/)() | 返回要加载的演示文稿的格式。读取 [Slides::LoadFormat](../loadformat/)。 |
| virtual **bool** [get_OnlyLoadDocumentProperties](./get_onlyloaddocumentproperties/)() | 此属性在演示文稿文件受密码保护时有意义。值为 true 表示只需从加密的演示文稿文件中加载文档属性并忽略密码。值为 false 表示必须使用正确密码加载整个加密的演示文稿。如果演示文稿未加密，则始终忽略属性值。如果加密文件的文档属性不是公开的且属性值为 true，则无法加载文档属性并将抛出异常。读取 **bool**。 |
| virtual [System::String](../../system/string/) [get_Password](./get_password/)() | 获取密码。读取 [System::String](../../system/string/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IResourceLoadingCallback](../iresourceloadingcallback/)\> [get_ResourceLoadingCallback](./get_resourceloadingcallback/)() | 返回管理外部资源加载的回调接口。读取 [IResourceLoadingCallback](../iresourceloadingcallback/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISpreadsheetOptions](../ispreadsheetoptions/)\> [get_SpreadsheetOptions](./get_spreadsheetoptions/)() | 表示可用于指定附加电子表格行为的选项。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](./get_warningcallback/)() | 返回一个接收警告并决定加载过程是继续还是中止的对象。读取 [Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用对自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 描述的类型实例。相当于 C# 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。实现自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，仅初始化新对象并允许子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，仅初始化新对象并允许子类的拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 针对字符串和 nullptr 情形的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 针对字符串情形的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| virtual void [set_BlobManagementOptions](./set_blobmanagementoptions/)([System::SharedPtr](../../system/sharedptr/)\<[IBlobManagementOptions](../iblobmanagementoptions/)\>) | 表示可用于管理大二进制对象 (BLOB) 处理行为的选项，例如使用临时文件或在内存中限制 BLOB 的最大字节数。这些选项旨在为特定环境或需求设定最佳的性能/内存消耗比率。 |
| virtual void [set_DefaultAsianFont](./set_defaultasianfont/)([System::String](../../system/string/)) | 设置在未找到源字体时使用的亚洲字体。写入 [System::String](../../system/string/)。 |
| virtual void [set_DefaultRegularFont](./set_defaultregularfont/)([System::String](../../system/string/)) | 设置在未找到源字体时使用的常规字体。写入 [System::String](../../system/string/)。 |
| virtual void [set_DefaultSymbolFont](./set_defaultsymbolfont/)([System::String](../../system/string/)) | 设置在未找到源字体时使用的符号字体。写入 [System::String](../../system/string/)。 |
| virtual void [set_DefaultTextLanguage](./set_defaulttextlanguage/)([System::String](../../system/string/)) | 设置演示文稿文本的默认语言。写入 [System::String](../../system/string/)。 |
| virtual void [set_DeleteEmbeddedBinaryObjects](./set_deleteembeddedbinaryobjects/)(**bool**) | 确定在加载演示文稿时 [Aspose.Slides](../) 是否会删除所有嵌入的二进制对象。 |
| virtual void [set_DocumentLevelFontSources](./set_documentlevelfontsources/)([System::SharedPtr](../../system/sharedptr/)\<[IFontSources](../ifontsources/)\>) | 指定演示文稿使用的外部字体来源。这些字体在整个演示文稿生命周期内可用且不与其他演示文稿共享。 |
| virtual void [set_InterruptionToken](./set_interruptiontoken/)([System::SharedPtr](../../system/sharedptr/)\<[IInterruptionToken](../iinterruptiontoken/)\>) | 用于监视中断请求的令牌。 |
| virtual void [set_LoadFormat](./set_loadformat/)([Aspose::Slides::LoadFormat](../loadformat/)) | 设置要加载的演示文稿的格式。写入 [Slides::LoadFormat](../loadformat/)。 |
| virtual void [set_OnlyLoadDocumentProperties](./set_onlyloaddocumentproperties/)(**bool**) | 此属性在演示文稿文件受密码保护时有意义。值为 true 表示只需从加密的演示文稿文件中加载文档属性并忽略密码。值为 false 表示必须使用正确密码加载整个加密的演示文稿。如果演示文稿未加密，则始终忽略属性值。如果加密文件的文档属性不是公开的且属性值为 true，则无法加载文档属性并将抛出异常。写入 **bool**。 |
| virtual void [set_Password](./set_password/)([System::String](../../system/string/)) | 设置密码。写入 [System::String](../../system/string/)。 |
| virtual void [set_ResourceLoadingCallback](./set_resourceloadingcallback/)([System::SharedPtr](../../system/sharedptr/)\<[IResourceLoadingCallback](../iresourceloadingcallback/)\>) | 设置管理外部资源加载的回调接口。写入 [IResourceLoadingCallback](../iresourceloadingcallback/)。 |
| virtual void [set_SpreadsheetOptions](./set_spreadsheetoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISpreadsheetOptions](../ispreadsheetoptions/)\>) | 表示可用于指定附加电子表格行为的选项。 |
| virtual void [set_WarningCallback](./set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | 设置接收警告并决定加载过程是继续还是中止的对象。写入 [Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享指针）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 增加共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。实现自定义对象到字符串的转换。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 结构。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 增加弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另请参见

* 类 [Object](../../system/object/)
* 命名空间 [Aspose::Slides](../)
* 库 [Aspose.Slides](../../)