---
title: XslCompiledTransform
second_title: Aspose.Slides for C++ API 参考
description: 使用 XSLT 样式表转换 XML 数据。
type: docs
weight: 53
url: /zh/system.xml.xsl/xslcompiledtransform/
---
## XslCompiledTransform 类

Transforms XML data using an XSLT style sheet.

```cpp
class XslCompiledTransform : public System::Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中即使根据 IEC 60559:1989 标准 NaN 不等于任何值（包括 NaN），两个 NaN 仍被视为相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中即使根据 IEC 60559:1989 标准 NaN 不等于任何值（包括 NaN），两个 NaN 仍被视为相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../../system.xml/xmlwritersettings/)\> [get_OutputSettings](./get_outputsettings/)() | 返回一个 [XmlWriterSettings](../../system.xml/xmlwritersettings/) 对象，其中包含从样式表的 **xsl:output** 元素派生的输出信息。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# 的 [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# 的 [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否是 targetType 描述的类型实例。相当于 C# 的 'is' 运算符。 |
| void [Load](./load/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&) | 编译包含在 [XmlReader](../../system.xml/xmlreader/) 中的样式表。 |
| void [Load](./load/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltSettings](../xsltsettings/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlResolver](../../system.xml/xmlresolver/)\>\&) | 编译包含在 [XmlReader](../../system.xml/xmlreader/) 中的 XSLT 样式表。[XmlResolver](../../system.xml/xmlresolver/) 解析所有 XSLT **import** 或 **include** 元素，XSLT 设置决定样式表的权限。 |
| void [Load](./load/)(const [String](../../system/string/)\&) | 加载并编译位于指定 URI 的样式表。 |
| void [Load](./load/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XsltSettings](../xsltsettings/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlResolver](../../system.xml/xmlresolver/)\>\&) | 加载并编译由 URI 指定的 XSLT 样式表。[XmlResolver](../../system.xml/xmlresolver/) 解析所有 XSLT **import** 或 **include** 元素，XSLT 设置决定样式表的权限。 |
| void [Load](./load/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)\>\&) | 编译包含在 IXPathNavigable 对象中的样式表。 |
| void [Load](./load/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XsltSettings](../xsltsettings/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlResolver](../../system.xml/xmlresolver/)\>) | 编译包含在 IXPathNavigable 中的 XSLT 样式表。[XmlResolver](../../system.xml/xmlresolver/) 解析所有 XSLT **import** 或 **include** 元素，XSLT 设置决定样式表的权限。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的锁定。可直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# 的 [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，只是初始化新对象并允许子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，只是初始化新对象并允许子类的拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化版本，用于 string 与 nullptr 的情况。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化版本，用于字符串的情况。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享指针）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# 的 [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&) | 使用 IXPathNavigable 对象指定的输入文档执行转换，并将结果输出到 [XmlWriter](../../system.xml/xmlwriter/)。 |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&) | 使用 IXPathNavigable 对象指定的输入文档执行转换，并将结果输出到 [XmlWriter](../../system.xml/xmlwriter/)。[XsltArgumentList](../xsltargumentlist/) 提供额外的运行时参数。 |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | 使用 IXPathNavigable 对象指定的输入文档执行转换，并将结果输出到 TextWriter。[XsltArgumentList](../xsltargumentlist/) 提供额外的运行时参数。 |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | 使用 IXPathNavigable 对象指定的输入文档执行转换，并将结果输出到流。[XsltArgumentList](../xsltargumentlist/) 提供额外的运行时参数。 |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&) | 使用 [XmlReader](../../system.xml/xmlreader/) 对象指定的输入文档执行转换，并将结果输出到 [XmlWriter](../../system.xml/xmlwriter/)。 |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&) | 使用 [XmlReader](../../system.xml/xmlreader/) 对象指定的输入文档执行转换，并将结果输出到 [XmlWriter](../../system.xml/xmlwriter/)。[XsltArgumentList](../xsltargumentlist/) 提供额外的运行时参数。 |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | 使用 [XmlReader](../../system.xml/xmlreader/) 对象指定的输入文档执行转换，并将结果输出到 TextWriter。[XsltArgumentList](../xsltargumentlist/) 提供额外的运行时参数。 |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | 使用 [XmlReader](../../system.xml/xmlreader/) 对象指定的输入文档执行转换，并将结果输出到流。[XsltArgumentList](../xsltargumentlist/) 提供额外的运行时参数。 |
| void [Transform](./transform/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&) | 使用 URI 指定的输入文档执行转换，并将结果输出到 [XmlWriter](../../system.xml/xmlwriter/)。 |
| void [Transform](./transform/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&) | 使用 URI 指定的输入文档执行转换，并将结果输出到 [XmlWriter](../../system.xml/xmlwriter/)。[XsltArgumentList](../xsltargumentlist/) 提供额外的运行时参数。 |
| void [Transform](./transform/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | 使用 URI 指定的输入文档执行转换，并将结果输出到 TextWriter。 |
| void [Transform](./transform/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | 使用 URI 指定的输入文档执行转换，并将结果输出到流。[XsltArgumentList](../xsltargumentlist/) 提供额外的运行时参数。 |
| void [Transform](./transform/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 使用 URI 指定的输入文档执行转换，并将结果输出到文件。 |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlResolver](../../system.xml/xmlresolver/)\>\&) | 使用 [XmlReader](../../system.xml/xmlreader/) 对象指定的输入文档执行转换，并将结果输出到 [XmlWriter](../../system.xml/xmlwriter/)。[XsltArgumentList](../xsltargumentlist/) 提供额外的运行时参数，[XmlResolver](../../system.xml/xmlresolver/) 解析 XSLT **document()** 函数。 |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlResolver](../../system.xml/xmlresolver/)\>\&) | 使用 IXPathNavigable 对象指定的输入文档执行转换，并将结果输出到 [XmlWriter](../../system.xml/xmlwriter/)。[XsltArgumentList](../xsltargumentlist/) 提供额外的运行时参数，[XmlResolver](../../system.xml/xmlresolver/) 解析 XSLT **document()** 函数。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 结构。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。可直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
|  [XslCompiledTransform](./xslcompiledtransform/)() | 初始化 [XslCompiledTransform](./) 类的新实例。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 类型别名

| 类型别名 | 描述 |
| --- | --- |
| [Ptr](./ptr/) | 此类实例的共享指针别名。 |

## 备注

Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## 另请参见

* 类 [Object](../../system/object/)
* 命名空间 [System::Xml::Xsl](../)
* 库 [Aspose.Slides](../../)