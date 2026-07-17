---
title: XmlTextWriter
second_title: Aspose.Slides for C++ API 参考
description: 表示一种写入器，提供快速、非缓存、仅向前的方式来生成符合 W3C 可扩展标记语言 (XML) 1.0 和 XML 命名空间推荐的包含 XML 数据的流或文件。
type: docs
weight: 521
url: /zh/system.xml/xmltextwriter/
---
## XmlTextWriter 类

表示一种写入器，提供一种快速、非缓存、只向前的方式来生成符合 W3C 可扩展标记语言 (XML) 1.0 和 XML 命名空间推荐的包含 XML 数据的流或文件。

```cpp
class XmlTextWriter : public System::Xml::XmlWriter
```

## 方法

| 方法 | 描述 |
| --- | --- |
| void [Close](./close/)() override | 关闭此流以及底层流。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [String](../../system/string/)\&) | 使用指定的文件名创建一个新的 [XmlWriter](../xmlwriter/) 实例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | 使用文件名和 [XmlWriterSettings](../xmlwritersettings/) 对象创建一个新的 [XmlWriter](../xmlwriter/) 实例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | 使用指定的流创建一个新的 [XmlWriter](../xmlwriter/) 实例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | 使用流和 [XmlWriterSettings](../xmlwritersettings/) 对象创建一个新的 [XmlWriter](../xmlwriter/) 实例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | 使用指定的 TextWriter 创建一个新的 [XmlWriter](../xmlwriter/) 实例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | 使用 TextWriter 和 [XmlWriterSettings](../xmlwritersettings/) 对象创建一个新的 [XmlWriter](../xmlwriter/) 实例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | 使用指定的 [Text::StringBuilder](../../system.text/stringbuilder/) 创建一个新的 [XmlWriter](../xmlwriter/) 实例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | 使用 [Text::StringBuilder](../../system.text/stringbuilder/) 和 [XmlWriterSettings](../xmlwritersettings/) 对象创建一个新的 [XmlWriter](../xmlwriter/) 实例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) | 使用指定的 [XmlWriter](../xmlwriter/) 对象创建一个新的 [XmlWriter](../xmlwriter/) 实例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | 使用指定的 [XmlWriter](../xmlwriter/) 和 [XmlWriterSettings](../xmlwritersettings/) 对象创建一个新的 [XmlWriter](../xmlwriter/) 实例。 |
| void [Dispose](../xmlwriter/dispose/)() override | 释放当前 [XmlWriter](../xmlwriter/) 类实例使用的所有资源。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，即使根据 IEC 60559:1989，NaN 与任何值（包括 NaN）都不相等，两个 NaN 仍被视为相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，即使根据 IEC 60559:1989，NaN 与任何值（包括 NaN）都不相等，两个 NaN 仍被视为相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| void [Flush](./flush/)() override | 将缓冲区中的内容刷新到底层流，并同时刷新底层流。 |
| [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\> [get_BaseStream](./get_basestream/)() | 返回底层流对象。 |
| [System::Xml::Formatting](../formatting/) [get_Formatting](./get_formatting/)() | 指示输出的格式方式。 |
| **int32_t** [get_Indentation](./get_indentation/)() | 当 [XmlTextWriter::set_Formatting](./set_formatting/) 设置为 [Formatting::Indented](../formatting/) 时，返回每层层次结构应写入的 IndentChars 数量。 |
| char16_t [get_IndentChar](./get_indentchar/)() | 当 [XmlTextWriter::set_Formatting](./set_formatting/) 设置为 [Formatting::Indented](../formatting/) 时，返回用于缩进的字符。 |
| **bool** [get_Namespaces](./get_namespaces/)() | 返回指示是否进行命名空间支持的值。 |
| char16_t [get_QuoteChar](./get_quotechar/)() | 返回用于引用属性值的字符。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\> [get_Settings](../xmlwriter/get_settings/)() | 返回用于创建此 [XmlWriter](../xmlwriter/) 实例的 [XmlWriterSettings](../xmlwritersettings/) 对象。 |
| [System::Xml::WriteState](../writestate/) [get_WriteState](./get_writestate/)() override | 返回写入器的状态。 |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | 返回当前 **xml:lang** 范围。 |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | 返回表示当前 **xml:space** 范围的 XmlSpace。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否为 targetType 描述的类型实例。相当于 C# 的 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的锁定。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| [String](../../system/string/) [LookupPrefix](./lookupprefix/)([String](../../system/string/)) override | 返回当前命名空间范围内为该命名空间 URI 定义的最近前缀。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
| [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，仅初始化新对象并允许子类拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，仅初始化新对象并允许子类拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 针对字符串和 nullptr 情况的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 针对字符串情况的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 将共享引用计数减少指定的值。 |
| void [set_Formatting](./set_formatting/)([System::Xml::Formatting](../formatting/)) | 指示输出的格式方式。 |
| void [set_Indentation](./set_indentation/)(**int32_t**) | 当 [XmlTextWriter::set_Formatting](./set_formatting/) 设置为 [Formatting::Indented](../formatting/) 时，设置每层层次结构应写入的 IndentChars 数量。 |
| void [set_IndentChar](./set_indentchar/)(char16_t) | 当 [XmlTextWriter::set_Formatting](./set_formatting/) 设置为 [Formatting::Indented](../formatting/) 时，设置用于缩进的字符。 |
| void [set_Namespaces](./set_namespaces/)(**bool**) | 设置指示是否进行命名空间支持的值。 |
| void [set_QuoteChar](./set_quotechar/)(char16_t) | 设置用于引用属性值的字符。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设置为弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取当前共享引用计数的值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual void [WriteAttributes](../xmlwriter/writeattributes/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | 在派生类中重写时，写出 [XmlReader](../xmlreader/) 当前位置信息中找到的所有属性。 |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 在派生类中重写时，写出具有指定本地名称、命名空间 URI 和数值的属性。 |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 在派生类中重写时，写出具有指定本地名称和数值的属性。 |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 在派生类中重写时，写出具有指定前缀、本地名称、命名空间 URI 和数值的属性。 |
| void [WriteBase64](./writebase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | 将指定的二进制字节编码为 base64 并写出生成的文本。 |
| void [WriteBinHex](./writebinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | 将指定的二进制字节编码为 binhex 并写出生成的文本。 |
| void [WriteCData](./writecdata/)([String](../../system/string/)) override | 写出包含指定文本的 **...** 块。 |
| void [WriteCharEntity](./writecharentity/)(char16_t) override | 强制为指定的 Unicode 字符值生成字符实体。 |
| void [WriteChars](./writechars/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) override | 一次写入一个缓冲区的文本。 |
| void [WriteComment](./writecomment/)([String](../../system/string/)) override | 写出包含指定文本的注释 ****。 |
| void [WriteDocType](./writedoctype/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | 写出具有指定名称和可选属性的 DOCTYPE 声明。 |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 写出具有指定本地名称和数值的元素。 |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 写出具有指定本地名称、命名空间 URI 和数值的元素。 |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 写出具有指定前缀、本地名称、命名空间 URI 和数值的元素。 |
| void [WriteEndAttribute](./writeendattribute/)() override | 关闭先前的 [XmlTextWriter::WriteStartAttribute](./writestartattribute/) 调用。 |
| void [WriteEndDocument](./writeenddocument/)() override | 关闭所有打开的元素或属性，并将写入器恢复到 Start 状态。 |
| void [WriteEndElement](./writeendelement/)() override | 关闭一个元素并弹出相应的命名空间范围。 |
| void [WriteEntityRef](./writeentityref/)(const [String](../../system/string/)\&) override | 将实体引用写为 **&name**;。 |
| void [WriteFullEndElement](./writefullendelement/)() override | 关闭一个元素并弹出相应的命名空间范围。 |
| void [WriteName](./writename/)(const [String](../../system/string/)\&) override | 写出指定名称，确保它符合 [W3C XML 1.0 recommendation](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name) 的有效名称要求。 |
| void [WriteNmToken](./writenmtoken/)(const [String](../../system/string/)\&) override | 写出指定名称，确保它符合 [W3C XML 1.0 recommendation](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name) 的有效 **NmToken** 要求。 |
| virtual void [WriteNode](../xmlwriter/writenode/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | 在派生类中重写时，将读取器的所有内容复制到写入器，并将读取器移动到下一个兄弟节点的起始位置。 |
| virtual void [WriteNode](../xmlwriter/writenode/)([SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>, **bool**) | 将 XPathNavigator 对象的所有内容复制到写入器。XPathNavigator 的位置保持不变。 |
| void [WriteProcessingInstruction](./writeprocessinginstruction/)([String](../../system/string/), [String](../../system/string/)) override | 写出处理指令，名称和文本之间有空格，例如：**<?name text?>**。 |
| void [WriteQualifiedName](./writequalifiedname/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | 写出具有命名空间限定的名称。此方法查找给定命名空间范围内的前缀。 |
| void [WriteRaw](./writeraw/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) override | 从字符缓冲区手动写出原始标记。 |
| void [WriteRaw](./writeraw/)(const [String](../../system/string/)\&) override | 从字符串手动写出原始标记。 |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | 写出属性的起始部分。 |
| void [WriteStartAttribute](../xmlwriter/writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 写出具有指定本地名称和命名空间 URI 的属性起始部分。 |
| void [WriteStartAttribute](../xmlwriter/writestartattribute/)(const [String](../../system/string/)\&) | 写出具有指定本地名称的属性起始部分。 |
| void [WriteStartDocument](./writestartdocument/)() override | 写出版本为 "1.0" 的 XML 声明。 |
| void [WriteStartDocument](./writestartdocument/)(**bool**) override | 写出版本为 "1.0" 且包含 standalone 属性的 XML 声明。 |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | 写出指定的起始标签并将其关联到给定的命名空间和前缀。 |
| void [WriteStartElement](../xmlwriter/writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 在派生类中重写时，写出指定的起始标签并将其关联到给定的命名空间。 |
| void [WriteStartElement](../xmlwriter/writestartelement/)(const [String](../../system/string/)\&) | 在派生类中重写时，写出具有指定本地名称的起始标签。 |
| void [WriteString](./writestring/)(const [String](../../system/string/)\&) override | 写出给定的文本内容。 |
| void [WriteSurrogateCharEntity](./writesurrogatecharentity/)(char16_t, char16_t) override | 为代理字符对生成并写出代理字符实体。 |
| virtual void [WriteValue](../xmlwriter/writevalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | 写出对象的值。 |
| virtual void [WriteValue](../xmlwriter/writevalue/)(const [String](../../system/string/)\&) | 写出一个 [String](../../system/string/) 值。 |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**bool**) | 写出一个 [Boolean](../../system/boolean/) 值。 |
| virtual void [WriteValue](../xmlwriter/writevalue/)([DateTime](../../system/datetime/)) | 写出一个 [DateTime](../../system/datetime/) 值。 |
| virtual void [WriteValue](../xmlwriter/writevalue/)([DateTimeOffset](../../system/datetimeoffset/)) | 写出一个 [DateTimeOffset](../../system/datetimeoffset/) 值。 |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**double**) | 写出一个 [Double](../../system/double/) 值。 |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**float**) | 写出单精度浮点数。 |
| virtual void [WriteValue](../xmlwriter/writevalue/)([Decimal](../../system/decimal/)) | 写出一个 [Decimal](../../system/decimal/) 值。 |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**int32_t**) | 写出一个 [Int32](../../system/int32/) 值。 |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**int64_t**) | 写出一个 [Int64](../../system/int64/) 值。 |
| void [WriteWhitespace](./writewhitespace/)([String](../../system/string/)) override | 写出给定的空白字符。 |
| [XmlTextWriter](./xmltextwriter/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | 使用指定的流和编码创建 [XmlTextWriter](./) 类的实例。 |
| [XmlTextWriter](./xmltextwriter/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | 使用指定的文件创建 [XmlTextWriter](./) 类的实例。 |
| [XmlTextWriter](./xmltextwriter/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | 使用指定的 TextWriter 创建 [XmlTextWriter](./) 类的实例。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 类型别名

| 类型别名 | 描述 |
| --- | --- |
| [Ptr](./ptr/) | 此类实例的共享指针别名。 |

## 备注

建议使用 [XmlWriter](../xmlwriter/) 类。

此类的对象应仅使用 [System::MakeObject()](../../system/makeobject/) 函数分配。切勿在栈上或使用 new 运算符创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装在 [System::SmartPtr](../../system/smartptr/) 指针中，并使用该指针作为参数传递给函数。

## 另见

* 类 [XmlWriter](../xmlwriter/)
* 命名空间 [System::Xml](../)
* 库 [Aspose.Slides](../../)