---
title: XmlWriter
second_title: Aspose.Slides for C++ API 参考
description: 表示一个写入器，以快速、非缓存、仅前进的方式生成包含 XML 数据的流或文件。
type: docs
weight: 573
url: /zh/system.xml/xmlwriter/
---
## XmlWriter 类


表示一个写入器，以快速、非缓存、仅前进的方式生成包含 XML 数据的流或文件。

```cpp
class XmlWriter : public System::IDisposable
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual void [Close](./close/)() | 在派生类中重写时，关闭此流及其底层流。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [String](../../system/string/)\&) | 使用指定的文件名创建一个新的 [XmlWriter](./) 实例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | 使用文件名和 [XmlWriterSettings](../xmlwritersettings/) 对象创建一个新的 [XmlWriter](./) 实例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | 使用指定的流创建一个新的 [XmlWriter](./) 实例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | 使用流和 [XmlWriterSettings](../xmlwritersettings/) 对象创建一个新的 [XmlWriter](./) 实例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | 使用指定的 TextWriter 创建一个新的 [XmlWriter](./) 实例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | 使用 TextWriter 和 [XmlWriterSettings](../xmlwritersettings/) 对象创建一个新的 [XmlWriter](./) 实例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | 使用指定的 [Text::StringBuilder](../../system.text/stringbuilder/) 创建一个新的 [XmlWriter](./) 实例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | 使用 [Text::StringBuilder](../../system.text/stringbuilder/) 和 [XmlWriterSettings](../xmlwritersettings/) 对象创建一个新的 [XmlWriter](./) 实例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\>\&) | 使用指定的 [XmlWriter](./) 对象创建一个新的 [XmlWriter](./) 实例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | 使用指定的 [XmlWriter](./) 和 [XmlWriterSettings](../xmlwritersettings/) 对象创建一个新的 [XmlWriter](./) 实例。 |
| void [Dispose](./dispose/)() override | 释放当前 [XmlWriter](./) 类实例使用的所有资源。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，即使根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，即使根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| virtual void [Flush](./flush/)() | 在派生类中重写时，将缓冲区中的内容冲刷到底层流，并冲刷底层流本身。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\> [get_Settings](./get_settings/)() | 返回用于创建此 [XmlWriter](./) 实例的 [XmlWriterSettings](../xmlwritersettings/) 对象。 |
| virtual [System::Xml::WriteState](../writestate/) [get_WriteState](./get_writestate/)() | 在派生类中重写时，获取写入器的状态。 |
| virtual [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | 在派生类中重写时，获取当前 **xml:lang** 范围。 |
| virtual [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() | 在派生类中重写时，获取表示当前 **xml:space** 范围的 XmlSpace。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。支持自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否是 targetType 描述的类型实例。相当于 C# 的 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的锁定。直接调用或使用 [LockContext](../../system/lockcontext/) 监视对象。 |
| virtual [String](../../system/string/) [LookupPrefix](./lookupprefix/)([String](../../system/string/)) | 在派生类中重写时，返回当前命名空间作用域中为该命名空间 URI 定义的最近前缀。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。支持克隆自定义类型。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 复制构造函数。实际上不复制任何内容，只是初始化新对象并允许子类复制构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，只是初始化新对象并允许子类复制构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字符串和 nullptr 情形下的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字符串情形下的特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 将共享引用计数减少指定值。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而不是共享指针）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。支持将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 监视对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual void [WriteAttributes](./writeattributes/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | 在派生类中重写时，写出在 [XmlReader](../xmlreader/) 当前位置找到的所有属性。 |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 在派生类中重写时，写出具有指定本地名称、命名空间 URI 和数值的属性。 |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 在派生类中重写时，写出具有指定本地名称和数值的属性。 |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 在派生类中重写时，写出具有指定前缀、本地名称、命名空间 URI 和数值的属性。 |
| virtual void [WriteBase64](./writebase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | 在派生类中重写时，将指定的二进制字节编码为 Base64 并写出生成的文本。 |
| virtual void [WriteBinHex](./writebinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | 在派生类中重写时，将指定的二进制字节编码为 **BinHex** 并写出生成的文本。 |
| virtual void [WriteCData](./writecdata/)([String](../../system/string/)) | 在派生类中重写时，写出包含指定文本的 **...** 块。 |
| virtual void [WriteCharEntity](./writecharentity/)(char16_t) | 在派生类中重写时，为指定的 Unicode 字符值强制生成字符实体。 |
| virtual void [WriteChars](./writechars/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | 在派生类中重写时，一次写入一个缓冲区的文本。 |
| virtual void [WriteComment](./writecomment/)([String](../../system/string/)) | 在派生类中重写时，写出包含指定文本的注释 ****。 |
| virtual void [WriteDocType](./writedoctype/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 在派生类中重写时，使用指定的名称和可选属性写出 DOCTYPE 声明。 |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 写出具有指定本地名称和值的元素。 |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 写出具有指定本地名称、命名空间 URI 和数值的元素。 |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 写出具有指定前缀、本地名称、命名空间 URI 和数值的元素。 |
| virtual void [WriteEndAttribute](./writeendattribute/)() | 在派生类中重写时，关闭先前的 XmlWriter::WriteStartAttribute(String,String) 调用。 |
| virtual void [WriteEndDocument](./writeenddocument/)() | 在派生类中重写时，关闭所有打开的元素或属性，并将写入器恢复到 Start 状态。 |
| virtual void [WriteEndElement](./writeendelement/)() | 在派生类中重写时，关闭一个元素并弹出相应的命名空间作用域。 |
| virtual void [WriteEntityRef](./writeentityref/)(const [String](../../system/string/)\&) | 在派生类中重写时，将实体引用写为 **&name**;。 |
| virtual void [WriteFullEndElement](./writefullendelement/)() | 在派生类中重写时，关闭一个元素并弹出相应的命名空间作用域。 |
| virtual void [WriteName](./writename/)(const [String](../../system/string/)\&) | 在派生类中重写时，写出指定的名称，确保其符合 W3C XML 1.0 推荐（[https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name)）中的有效名称规则。 |
| virtual void [WriteNmToken](./writenmtoken/)(const [String](../../system/string/)\&) | 在派生类中重写时，写出指定的名称，确保其符合 W3C XML 1.0 推荐（[https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name)）中的有效 NmToken 规则。 |
| virtual void [WriteNode](./writenode/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | 在派生类中重写时，将读取器的内容全部复制到写入器，并将读取器移动到下一个同级节点的起始位置。 |
| virtual void [WriteNode](./writenode/)([SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>, **bool**) | 将 XPathNavigator 对象的全部内容复制到写入器。XPathNavigator 的位置保持不变。 |
| virtual void [WriteProcessingInstruction](./writeprocessinginstruction/)([String](../../system/string/), [String](../../system/string/)) | 在派生类中重写时，写出形如 **<?name text?>** 的处理指令，名称和文本之间有空格。 |
| virtual void [WriteQualifiedName](./writequalifiedname/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 在派生类中重写时，写出具备命名空间限定的名称。此方法会查找给定命名空间在作用域中的前缀。 |
| virtual void [WriteRaw](./writeraw/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | 在派生类中重写时，从字符缓冲区手动写出原始标记。 |
| virtual void [WriteRaw](./writeraw/)(const [String](../../system/string/)\&) | 在派生类中重写时，从字符串手动写出原始标记。 |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 写出具有指定本地名称和命名空间 URI 的属性起始标记。 |
| virtual void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 在派生类中重写时，写出具有指定前缀、本地名称和命名空间 URI 的属性起始标记。 |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&) | 写出具有指定本地名称的属性起始标记。 |
| virtual void [WriteStartDocument](./writestartdocument/)() | 在派生类中重写时，写出版本为 "1.0" 的 XML 声明。 |
| virtual void [WriteStartDocument](./writestartdocument/)(**bool**) | 在派生类中重写时，写出版本为 "1.0" 且带有 standalone 属性的 XML 声明。 |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 在派生类中重写时，写出指定的开始标签并将其与给定的命名空间关联。 |
| virtual void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 在派生类中重写时，写出指定的开始标签并将其与给定的命名空间及前缀关联。 |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&) | 在派生类中重写时，写出具有指定本地名称的开始标签。 |
| virtual void [WriteString](./writestring/)(const [String](../../system/string/)\&) | 在派生类中重写时，写出给定的文本内容。 |
| virtual void [WriteSurrogateCharEntity](./writesurrogatecharentity/)(char16_t, char16_t) | 在派生类中重写时，为代理字符对生成并写出代理字符实体。 |
| virtual void [WriteValue](./writevalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | 写出对象的值。 |
| virtual void [WriteValue](./writevalue/)(const [String](../../system/string/)\&) | 写出一个 [String](../../system/string/) 值。 |
| virtual void [WriteValue](./writevalue/)(**bool**) | 写出一个 [Boolean](../../system/boolean/) 值。 |
| virtual void [WriteValue](./writevalue/)([DateTime](../../system/datetime/)) | 写出一个 [DateTime](../../system/datetime/) 值。 |
| virtual void [WriteValue](./writevalue/)([DateTimeOffset](../../system/datetimeoffset/)) | 写出一个 [DateTimeOffset](../../system/datetimeoffset/) 值。 |
| virtual void [WriteValue](./writevalue/)(**double**) | 写出一个 [Double](../../system/double/) 值。 |
| virtual void [WriteValue](./writevalue/)(**float**) | 写出一个单精度浮点数。 |
| virtual void [WriteValue](./writevalue/)([Decimal](../../system/decimal/)) | 写出一个 [Decimal](../../system/decimal/) 值。 |
| virtual void [WriteValue](./writevalue/)(**int32_t**) | 写出一个 [Int32](../../system/int32/) 值。 |
| virtual void [WriteValue](./writevalue/)(**int64_t**) | 写出一个 [Int64](../../system/int64/) 值。 |
| virtual void [WriteWhitespace](./writewhitespace/)([String](../../system/string/)) | 在派生类中重写时，写出给定的空白字符。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |
## 类型定义

| 类型定义 | 描述 |
| --- | --- |
| [Ptr](./ptr/) | 本类实例的共享指针别名。 |
## 另请参见

* 类 [IDisposable](../../system/idisposable/)
* 命名空间 [System::Xml](../)
* 库 [Aspose.Slides](../../)