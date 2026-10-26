---
title: XmlWriterSettings
second_title: Aspose.Slides for C++ API 参考
description: "指定在由 XmlWriter::Create 方法创建的 XmlWriter 对象上支持的一组功能。"
type: docs
weight: 586
url: /zh/system.xml/xmlwritersettings/
---
## XmlWriterSettings 类

指定在由 [XmlWriter::Create](../xmlwriter/create/) 方法创建的 [XmlWriter](../xmlwriter/) 对象上支持的一组功能。

```cpp
class XmlWriterSettings : public System::Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](./)\> [Clone](./clone/)() | 创建 [XmlWriterSettings](./) 实例的副本。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，即使根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，即使根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅用于内部目的。 |
| **bool** [get_CheckCharacters](./get_checkcharacters/)() | 返回一个值，指示 XML 写入器是否应检查确保文档中的所有字符符合 W3C [XML 1.0 Recommendation](https://www.w3.org/TR/REC-xml/#charsets) 的 "2.2 Characters" 部分。 |
| **bool** [get_CloseOutput](./get_closeoutput/)() | 返回一个值，指示在调用 [XmlWriter::Close](../xmlwriter/close/) 方法时，[XmlWriter](../xmlwriter/) 是否也应关闭底层流或 TextWriter。 |
| [System::Xml::ConformanceLevel](../conformancelevel/) [get_ConformanceLevel](./get_conformancelevel/)() | 返回 XML 写入器检查 XML 输出的符合级别。 |
| **bool** [get_DoNotEscapeUriAttributes](./get_donotescapeuriattributes/)() | 返回一个值，指示 [XmlWriter](../xmlwriter/) 是否不转义 URI 属性。 |
| [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | 返回要使用的文本编码类型。 |
| **bool** [get_Indent](./get_indent/)() | 返回一个值，指示是否缩进元素。 |
| [String](../../system/string/) [get_IndentChars](./get_indentchars/)() | 返回缩进时使用的字符字符串。当 [XmlWriterSettings::set_Indent](./set_indent/) 值设置为 **true** 时使用此设置。 |
| [System::Xml::NamespaceHandling](../namespacehandling/) [get_NamespaceHandling](./get_namespacehandling/)() | 返回一个值，指示在写入 XML 内容时，[XmlWriter](../xmlwriter/) 是否应移除重复的命名空间声明。默认行为是写入器输出其命名空间解析器中存在的所有命名空间声明。 |
| [String](../../system/string/) [get_NewLineChars](./get_newlinechars/)() | 返回用于换行的字符字符串。 |
| [System::Xml::NewLineHandling](../newlinehandling/) [get_NewLineHandling](./get_newlinehandling/)() | 返回一个值，指示是否在输出中标准化换行。 |
| **bool** [get_NewLineOnAttributes](./get_newlineonattributes/)() | 返回一个值，指示是否在新行上写入属性。 |
| **bool** [get_OmitXmlDeclaration](./get_omitxmldeclaration/)() | 返回一个值，指示是否省略 XML 声明。 |
| [XmlOutputMethod](../xmloutputmethod/) [get_OutputMethod](./get_outputmethod/)() | 返回用于序列化 [XmlWriter](../xmlwriter/) 输出的方法。 |
| **bool** [get_WriteEndDocumentOnClose](./get_writeenddocumentonclose/)() | 返回一个值，指示在调用 [XmlWriter::Close](../xmlwriter/close/) 方法时，[XmlWriter](../xmlwriter/) 是否会为所有未闭合的元素标签添加结束标签。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 描述的类型实例。相当于 C# 的 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的锁定。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，只是初始化新对象并支持子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，只是初始化新对象并支持子类的拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字符串与 nullptr 情形下的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字符串情形下的特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 将共享引用计数减少指定的值。 |
| void [Reset](./reset/)() | 将设置类的成员重置为默认值。 |
| void [set_CheckCharacters](./set_checkcharacters/)(**bool**) | 设置一个值，指示 XML 写入器是否应检查确保文档中的所有字符符合 W3C [XML 1.0 Recommendation](https://www.w3.org/TR/REC-xml/#charsets) 的 "2.2 Characters" 部分。 |
| void [set_CloseOutput](./set_closeoutput/)(**bool**) | 设置一个值，指示在调用 [XmlWriter::Close](../xmlwriter/close/) 方法时，[XmlWriter](../xmlwriter/) 是否也应关闭底层流或 TextWriter。 |
| void [set_ConformanceLevel](./set_conformancelevel/)([System::Xml::ConformanceLevel](../conformancelevel/)) | 设置 XML 写入器检查 XML 输出的符合级别。 |
| void [set_DoNotEscapeUriAttributes](./set_donotescapeuriattributes/)(**bool**) | 设置一个值，指示 [XmlWriter](../xmlwriter/) 是否不转义 URI 属性。 |
| void [set_Encoding](./set_encoding/)(const [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\>\&) | 设置要使用的文本编码类型。 |
| void [set_Indent](./set_indent/)(**bool**) | 设置一个值，指示是否缩进元素。 |
| void [set_IndentChars](./set_indentchars/)(const [String](../../system/string/)\&) | 设置缩进时使用的字符字符串。当 [XmlWriterSettings::set_Indent](./set_indent/) 值设置为 **true** 时使用此设置。 |
| void [set_NamespaceHandling](./set_namespacehandling/)([System::Xml::NamespaceHandling](../namespacehandling/)) | 设置一个值，指示在写入 XML 内容时，[XmlWriter](../xmlwriter/) 是否应移除重复的命名空间声明。默认行为是写入器输出其命名空间解析器中存在的所有命名空间声明。 |
| void [set_NewLineChars](./set_newlinechars/)(const [String](../../system/string/)\&) | 设置用于换行的字符字符串。 |
| void [set_NewLineHandling](./set_newlinehandling/)([System::Xml::NewLineHandling](../newlinehandling/)) | 设置一个值，指示是否在输出中标准化换行。 |
| void [set_NewLineOnAttributes](./set_newlineonattributes/)(**bool**) | 设置一个值，指示是否在新行上写入属性。 |
| void [set_OmitXmlDeclaration](./set_omitxmldeclaration/)(**bool**) | 设置一个值，指示是否省略 XML 声明。 |
| void [set_WriteEndDocumentOnClose](./set_writeenddocumentonclose/)(**bool**) | 设置一个值，指示在调用 [XmlWriter::Close](../xmlwriter/close/) 方法时，[XmlWriter](../xmlwriter/) 是否会为所有未闭合的元素标签添加结束标签。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而不是共享指针）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
|  [XmlWriterSettings](./xmlwritersettings/)() | 初始化 [XmlWriterSettings](./) 类的新实例。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 类型定义

| 类型定义 | 描述 |
| --- | --- |
| [Ptr](./ptr/) | 此类实例的共享指针别名。 |

## 备注

此类的对象只能使用 [System::MakeObject()](../../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。

## 另见

* 类 [Object](../../system/object/)
* 命名空间 [System::Xml](../)
* 库 [Aspose.Slides](../../)