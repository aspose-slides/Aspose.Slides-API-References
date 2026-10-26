---
title: XmlReaderSettings
second_title: Aspose.Slides C++ API 参考
description: "指定在由 XmlReader::Create 方法创建的 XmlReader 对象上支持的一组功能。"
type: docs
weight: 443
url: /zh/system.xml/xmlreadersettings/
---
## XmlReaderSettings 类

Specifies a set of features to support on the [XmlReader](../xmlreader/) object created by the [XmlReader::Create](../xmlreader/create/) method.

```cpp
class XmlReaderSettings : public System::Object
```

## 方法

| Method | Description |
| --- | --- |
| void [CheckReadOnly](./checkreadonly/)(const [String](../../system/string/)\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](./)\> [Clone](./clone/)() | 创建 [XmlReaderSettings](./) 实例的副本。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 标准，NaN 不等于任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 标准，NaN 不等于任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| **bool** [get_CheckCharacters](./get_checkcharacters/)() | 返回一个指示是否进行字符检查的值。 |
| **bool** [get_CloseInput](./get_closeinput/)() | 返回一个指示在关闭阅读器时是否应关闭底层流或 TextReader 的值。 |
| [System::Xml::ConformanceLevel](../conformancelevel/) [get_ConformanceLevel](./get_conformancelevel/)() | 返回 [XmlReader](../xmlreader/) 将遵循的符合级别。 |
| [System::Xml::DtdProcessing](../dtdprocessing/) [get_DtdProcessing](./get_dtdprocessing/)() | 返回决定 DTD 处理方式的值。 |
| **bool** [get_IgnoreComments](./get_ignorecomments/)() | 返回一个指示是否忽略注释的值。 |
| **bool** [get_IgnoreProcessingInstructions](./get_ignoreprocessinginstructions/)() | 返回一个指示是否忽略处理指令的值。 |
| **bool** [get_IgnoreWhitespace](./get_ignorewhitespace/)() | 返回一个指示是否忽略无意义空白的值。 |
| **int32_t** [get_LineNumberOffset](./get_linenumberoffset/)() | 返回 [XmlReader](../xmlreader/) 对象的行号偏移量。 |
| **int32_t** [get_LinePositionOffset](./get_linepositionoffset/)() | 返回 [XmlReader](../xmlreader/) 对象的行位置偏移量。 |
| **int64_t** [get_MaxCharactersFromEntities](./get_maxcharactersfromentities/)() | 返回一个指示文档中展开实体后允许的最大字符数的值。 |
| **int64_t** [get_MaxCharactersInDocument](./get_maxcharactersindocument/)() | 返回一个指示 XML 文档中允许的最大字符数的值。零 (0) 表示对 XML 文档大小无限制。非零值指定字符数的最大大小。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() | 返回用于原子化字符串比较的 [XmlNameTable](../xmlnametable/)。 |
| **bool** [get_ProhibitDtd](./get_prohibitdtd/)() | 返回一个指示是否禁止文档类型定义 (DTD) 处理的值。 |
| [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\> [get_Schemas](./get_schemas/)() | 返回进行模式验证时使用的 XmlSchemaSet。 |
| [Schema::XmlSchemaValidationFlags](../../system.xml.schema/xmlschemavalidationflags/) [get_ValidationFlags](./get_validationflags/)() | 返回指示模式验证设置的值。此设置适用于验证模式的 [XmlReader](../xmlreader/) 对象（[XmlReaderSettings::get_ValidationType](./get_validationtype/) 值为 [ValidationType::Schema](../validationtype/)）。 |
| [System::Xml::ValidationType](../validationtype/) [get_ValidationType](./get_validationtype/)() | 返回一个指示在读取时 [XmlReader](../xmlreader/) 是否执行验证或类型分配的值。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 所描述的类型实例。相当于 C# 的 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的锁定。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用克隆自定义类型。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 复制构造函数。实际上不复制任何内容，仅初始化新对象并允许子类的复制构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，仅初始化新对象并允许子类的复制构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于字符串和 nullptr 的情况。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于字符串的情况。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值递减共享引用计数。 |
| void [Reset](./reset/)() | 将设置类的成员重置为默认值。 |
| void [set_CheckCharacters](./set_checkcharacters/)(**bool**) | 设置指示是否进行字符检查的值。 |
| void [set_CloseInput](./set_closeinput/)(**bool**) | 设置指示在关闭阅读器时是否应关闭底层流或 TextReader 的值。 |
| void [set_ConformanceLevel](./set_conformancelevel/)([System::Xml::ConformanceLevel](../conformancelevel/)) | 设置 [XmlReader](../xmlreader/) 将遵循的符合级别。 |
| void [set_DtdProcessing](./set_dtdprocessing/)([System::Xml::DtdProcessing](../dtdprocessing/)) | 设置决定 DTD 处理方式的值。 |
| void [set_IgnoreComments](./set_ignorecomments/)(**bool**) | 设置指示是否忽略注释的值。 |
| void [set_IgnoreProcessingInstructions](./set_ignoreprocessinginstructions/)(**bool**) | 设置指示是否忽略处理指令的值。 |
| void [set_IgnoreWhitespace](./set_ignorewhitespace/)(**bool**) | 设置指示是否忽略无意义空白的值。 |
| void [set_LineNumberOffset](./set_linenumberoffset/)(**int32_t**) | 设置 [XmlReader](../xmlreader/) 对象的行号偏移量。 |
| void [set_LinePositionOffset](./set_linepositionoffset/)(**int32_t**) | 设置 [XmlReader](../xmlreader/) 对象的行位置偏移量。 |
| void [set_MaxCharactersFromEntities](./set_maxcharactersfromentities/)(**int64_t**) | 设置指示文档中展开实体后允许的最大字符数的值。 |
| void [set_MaxCharactersInDocument](./set_maxcharactersindocument/)(**int64_t**) | 设置指示 XML 文档中允许的最大字符数的值。零 (0) 表示对 XML 文档大小无限制。非零值指定字符数的最大大小。 |
| void [set_NameTable](./set_nametable/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | 设置用于原子化字符串比较的 [XmlNameTable](../xmlnametable/)。 |
| void [set_ProhibitDtd](./set_prohibitdtd/)(**bool**) | 设置指示是否禁止文档类型定义 (DTD) 处理的值。 |
| void [set_Schemas](./set_schemas/)(const [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\>\&) | 设置进行模式验证时使用的 XmlSchemaSet。 |
| void [set_ValidationFlags](./set_validationflags/)([Schema::XmlSchemaValidationFlags](../../system.xml.schema/xmlschemavalidationflags/)) | 设置指示模式验证设置的值。此设置适用于验证模式的 [XmlReader](../xmlreader/) 对象（[XmlReaderSettings::get_ValidationType](./get_validationtype/) 值为 [ValidationType::Schema](../validationtype/)）。 |
| void [set_ValidationType](./set_validationtype/)([System::Xml::ValidationType](../validationtype/)) | 设置指示在读取时 [XmlReader](../xmlreader/) 是否执行验证或类型分配的值。 |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../xmlresolver/)\>\&) | 设置用于访问外部文档的 [XmlResolver](../xmlresolver/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| void [ValidationEventHandler_add](./validationeventhandler_add/)(Args...) | 添加当读取器遇到验证错误时触发的事件处理程序。 |
| void [ValidationEventHandler_remove](./validationeventhandler_remove/)(Args...) | 移除当读取器遇到验证错误时触发的事件处理程序。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
|  [XmlReaderSettings](./xmlreadersettings/)() | 初始化 [XmlReaderSettings](./) 类的新实例。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 类型定义

| 类型别名 | 描述 |
| --- | --- |
| [Ptr](./ptr/) | 此类实例的共享指针别名。 |

## 备注

此类的对象应仅使用 [System::MakeObject()](../../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装在 [System::SmartPtr](../../system/smartptr/) 指针中，并使用该指针将其作为参数传递给函数。

## 另见

* 类 [Object](../../system/object/)
* 命名空间 [System::Xml](../)
* 库 [Aspose.Slides](../../)