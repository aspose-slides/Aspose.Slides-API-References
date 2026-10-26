---
title: XmlNodeReader
second_title: Aspose.Slides for C++ API 参考
description: 表示提供快速、非缓存、仅向前访问 XML 数据的 XmlNode 阅读器。
type: docs
weight: 365
url: /zh/system.xml/xmlnodereader/
---
## XmlNodeReader 类


表示提供快速、非缓存、仅向前访问 [XmlNode](../xmlnode/) 中 XML 数据的读取器。

```cpp
class XmlNodeReader : public System::Xml::XmlReader,
                      public System::Xml::IXmlNamespaceResolver
```

## 方法

| 方法 | 描述 |
| --- | --- |
| void [Close](./close/)() override | 将 [XmlNodeReader::get_ReadState](./get_readstate/) 更改为 [ReadState::Closed](../readstate/)。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&) | 使用指定的 URI 创建一个新的 [XmlReader](../xmlreader/) 实例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | 使用指定的 URI 和设置创建一个新的 [XmlReader](../xmlreader/) 实例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | 使用指定的 URI、设置和用于解析的上下文信息创建一个新的 [XmlReader](../xmlreader/) 实例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | 使用指定的流和默认设置创建一个新的 [XmlReader](../xmlreader/) 实例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | 使用指定的流和设置创建一个新的 [XmlReader](../xmlreader/) 实例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | 使用指定的流、基础 URI 和设置创建一个新的 [XmlReader](../xmlreader/) 实例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | 使用指定的流、设置和用于解析的上下文信息创建一个新的 [XmlReader](../xmlreader/) 实例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | 使用指定的文本读取器创建一个新的 [XmlReader](../xmlreader/) 实例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | 使用指定的文本读取器和设置创建一个新的 [XmlReader](../xmlreader/) 实例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | 使用指定的文本读取器、设置和基础 URI 创建一个新的 [XmlReader](../xmlreader/) 实例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | 使用指定的文本读取器、设置和用于解析的上下文信息创建一个新的 [XmlReader](../xmlreader/) 实例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | 使用指定的 XML 读取器和设置创建一个新的 [XmlReader](../xmlreader/) 实例。 |
| void [Dispose](../xmlreader/dispose/)() override | 释放当前 [XmlReader](../xmlreader/) 类实例使用的所有资源。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，即两个 NaN 被视为相等，尽管根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，即两个 NaN 被视为相等，尽管根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| **int32_t** [get_AttributeCount](./get_attributecount/)() override | 返回当前节点上的属性数量。 |
| [String](../../system/string/) [get_BaseURI](./get_baseuri/)() override | 返回当前节点的基础 URI。 |
| **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() override | 返回一个值，指示 [XmlNodeReader](./) 是否实现二进制内容读取方法。 |
| virtual **bool** [get_CanReadValueChunk](../xmlreader/get_canreadvaluechunk/)() | 返回一个值，指示 [XmlReader](../xmlreader/) 是否实现 [XmlReader::ReadValueChunk](../xmlreader/readvaluechunk/) 方法。 |
| **bool** [get_CanResolveEntity](./get_canresolveentity/)() override | 返回一个值，指示此读取器是否可以解析和解析实体。 |
| **int32_t** [get_Depth](./get_depth/)() override | 返回 XML 文档中当前节点的深度。 |
| **bool** [get_EOF](./get_eof/)() override | 返回一个值，指示读取器是否位于流的末尾。 |
| **bool** [get_HasAttributes](./get_hasattributes/)() override | 返回一个值，指示当前节点是否有任何属性。 |
| **bool** [get_HasValue](./get_hasvalue/)() override | 返回一个值，指示当前节点是否可以具有 [XmlNodeReader::get_Value](./get_value/) 值。 |
| **bool** [get_IsDefault](./get_isdefault/)() override | 返回一个值，指示当前节点是否为从文档类型定义 (DTD) 或模式中定义的默认值生成的属性。 |
| **bool** [get_IsEmptyElement](./get_isemptyelement/)() override | 返回一个值，指示当前节点是否为空元素（例如 **<MyElement/>**）。 |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | 返回当前节点的本地名称。 |
| [String](../../system/string/) [get_Name](./get_name/)() override | 返回当前节点的限定名称。 |
| [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() override | 返回读取器所在节点的命名空间 URI（如 W3C 命名空间规范所定义）。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() override | 返回与此实现关联的 [XmlNameTable](../xmlnametable/)。 |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | 返回当前节点的类型。 |
| [String](../../system/string/) [get_Prefix](./get_prefix/)() override | 返回与当前节点关联的命名空间前缀。 |
| virtual char16_t [get_QuoteChar](../xmlreader/get_quotechar/)() | 在派生类中被重写时，获取用于包围属性节点值的引号字符。 |
| [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() override | 返回读取器的状态。 |
| [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() override | 返回已分配给当前节点的模式信息。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](../xmlreader/get_settings/)() | 返回用于创建此 [XmlReader](../xmlreader/) 实例的 [XmlReaderSettings](../xmlreadersettings/) 对象。 |
| [String](../../system/string/) [get_Value](./get_value/)() override | 返回当前节点的文本值。 |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](../xmlreader/get_valuetype/)() | 返回当前节点的类型。 |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | 返回当前 **xml:lang** 范围。 |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | 返回当前 **xml:space** 范围。 |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) override | 返回具有指定名称的属性值。 |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) override | 返回具有指定本地名称和命名空间 URI 的属性值。 |
| [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) override | 返回具有指定索引的属性值。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法的类似实现。启用自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# 的 [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)(**int32_t**) | 在派生类中被重写时，获取具有指定索引的属性值。 |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/)) | 在派生类中被重写时，获取具有指定 [XmlReader::get_Name](../xmlreader/get_name/) 值的属性值。 |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/), [String](../../system/string/)) | 在派生类中被重写时，获取具有指定 [XmlReader::get_LocalName](../xmlreader/get_localname/) 和 [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) 值的属性值。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 描述的类型实例。相当于 C# 的 'is' 运算符。 |
| static **bool** [IsName](../xmlreader/isname/)(const [String](../../system/string/)\&) | 返回一个值，指示字符串参数是否为有效的 XML 名称。 |
| static **bool** [IsNameToken](../xmlreader/isnametoken/)(const [String](../../system/string/)\&) | 返回一个值，指示字符串参数是否为有效的 XML 名称标记。 |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)() | 调用 [XmlReader::MoveToContent](../xmlreader/movetocontent/) 并测试当前内容节点是否为开始标签或空元素标签。 |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/)) | 调用 [XmlReader::MoveToContent](../xmlreader/movetocontent/) 并测试当前内容节点是否为开始标签或空元素标签，以及找到的元素的 [XmlReader::get_Name](../xmlreader/get_name/) 值是否匹配给定参数。 |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/), [String](../../system/string/)) | 调用 [XmlReader::MoveToContent](../xmlreader/movetocontent/) 并测试当前内容节点是否为开始标签或空元素标签，以及找到的元素的 [XmlReader::get_LocalName](../xmlreader/get_localname/) 和 [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) 值是否匹配给定字符串。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的锁定。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | 解析当前元素作用域中的命名空间前缀。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法的类似实现。启用自定义类型的克隆。 |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) override | 移动到具有指定名称的属性。 |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) override | 移动到具有指定本地名称和命名空间 URI 的属性。 |
| void [MoveToAttribute](./movetoattribute/)(**int32_t**) override | 移动到具有指定索引的属性。 |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](../xmlreader/movetocontent/)() | 检查当前节点是否为内容节点（非空白文本、**CDATA**、**Element**、**EndElement**、**EntityReference** 或 **EndEntity**）。如果节点不是内容节点，读取器将跳到下一个内容节点或文件结束。它会跳过以下类型的节点：**ProcessingInstruction**、**DocumentType**、**Comment**、**Whitespace** 或 **SignificantWhitespace**。 |
| **bool** [MoveToElement](./movetoelement/)() override | 移动到包含当前属性节点的元素。 |
| **bool** [MoveToFirstAttribute](./movetofirstattribute/)() override | 移动到第一个属性。 |
| **bool** [MoveToNextAttribute](./movetonextattribute/)() override | 移动到下一个属性。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，只是初始化新对象并允许子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，只是初始化新对象并允许子类的拷贝构造。 |
| **bool** [Read](./read/)() override | 从流中读取下一个节点。 |
| **bool** [ReadAttributeValue](./readattributevalue/)() override | 将属性值解析为一个或多个 **[Text](../../system.text/)**、**EntityReference** 或 **EndEntity** 节点。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](../xmlreader/readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | 将内容读取为指定类型的对象。 |
| **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | 读取内容并返回 Base64 解码后的二进制字节。 |
| **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | 读取内容并返回 BinHex 解码后的二进制字节。 |
| virtual **bool** [ReadContentAsBoolean](../xmlreader/readcontentasboolean/)() | 将当前位置的文本内容读取为 [Boolean](../../system/boolean/)。 |
| virtual [DateTime](../../system/datetime/) [ReadContentAsDateTime](../xmlreader/readcontentasdatetime/)() | 将当前位置的文本内容读取为 [DateTime](../../system/datetime/) 对象。 |
| virtual [DateTimeOffset](../../system/datetimeoffset/) [ReadContentAsDateTimeOffset](../xmlreader/readcontentasdatetimeoffset/)() | 将当前位置的文本内容读取为 [DateTimeOffset](../../system/datetimeoffset/) 对象。 |
| virtual [Decimal](../../system/decimal/) [ReadContentAsDecimal](../xmlreader/readcontentasdecimal/)() | 将当前位置的文本内容读取为 [Decimal](../../system/decimal/) 对象。 |
| virtual **double** [ReadContentAsDouble](../xmlreader/readcontentasdouble/)() | 将当前位置的文本内容读取为双精度浮点数。 |
| virtual **float** [ReadContentAsFloat](../xmlreader/readcontentasfloat/)() | 将当前位置的文本内容读取为单精度浮点数。 |
| virtual **int32_t** [ReadContentAsInt](../xmlreader/readcontentasint/)() | 将当前位置的文本内容读取为 32 位有符号整数。 |
| virtual **int64_t** [ReadContentAsLong](../xmlreader/readcontentaslong/)() | 将当前位置的文本内容读取为 64 位有符号整数。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAsObject](../xmlreader/readcontentasobject/)() | 将当前位置的文本内容读取为 [Object](../../system/object/)。 |
| virtual [String](../../system/string/) [ReadContentAsString](../xmlreader/readcontentasstring/)() | 将当前位置的文本内容读取为 [String](../../system/string/) 对象。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | 将元素内容读取为请求的类型。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | 检查指定的本地名称和命名空间 URI 是否与当前元素匹配，然后将元素内容读取为请求的类型。 |
| **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | 读取元素并解码 Base64 内容。 |
| **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | 读取元素并解码 BinHex 内容。 |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)() | 读取当前元素并将内容作为 [Boolean](../../system/boolean/) 对象返回。 |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | 检查指定的本地名称和命名空间 URI 是否与当前元素匹配，然后读取当前元素并将内容作为 [Boolean](../../system/boolean/) 对象返回。 |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)() | 读取当前元素并将内容作为 [DateTime](../../system/datetime/) 对象返回。 |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | 检查指定的本地名称和命名空间 URI 是否与当前元素匹配，然后读取当前元素并将内容作为 [DateTime](../../system/datetime/) 对象返回。 |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)() | 读取当前元素并将内容作为 [Decimal](../../system/decimal/) 对象返回。 |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | 检查指定的本地名称和命名空间 URI 是否与当前元素匹配，然后读取当前元素并将内容作为 [Decimal](../../system/decimal/) 对象返回。 |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)() | 读取当前元素并将内容作为双精度浮点数返回。 |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | 检查指定的本地名称和命名空间 URI 是否与当前元素匹配，然后读取当前元素并将内容作为双精度浮点数返回。 |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)() | 读取当前元素并将内容作为单精度浮点数返回。 |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | 检查指定的本地名称和命名空间 URI 是否与当前元素匹配，然后读取当前元素并将内容作为单精度浮点数返回。 |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)() | 读取当前元素并将内容作为 32 位有符号整数返回。 |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | 检查指定的本地名称和命名空间 URI 是否与当前元素匹配，然后读取当前元素并将内容作为 32 位有符号整数返回。 |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)() | 读取当前元素并将内容作为 64 位有符号整数返回。 |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | 检查指定的本地名称和命名空间 URI 是否与当前元素匹配，然后读取当前元素并将内容作为 64 位有符号整数返回。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)() | 读取当前元素并将内容作为 [Object](../../system/object/) 返回。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | 检查指定的本地名称和命名空间 URI 是否与当前元素匹配，然后读取当前元素并将内容作为 [Object](../../system/object/) 返回。 |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)() | 读取当前元素并将内容作为 [String](../../system/string/) 对象返回。 |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | 检查指定的本地名称和命名空间 URI 是否与当前元素匹配，然后读取当前元素并将内容作为 [String](../../system/string/) 对象返回。 |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)() | 读取仅包含文本的元素。但建议使用 [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) 方法，因为它提供了更直接的处理方式。 |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/)) | 在读取仅包含文本的元素之前，检查找到的元素的 [XmlReader::get_Name](../xmlreader/get_name/) 值是否匹配给定字符串。但建议使用 [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) 方法，因为它提供了更直接的处理方式。 |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/), [String](../../system/string/)) | 在读取仅包含文本的元素之前，检查找到的元素的 [XmlReader::get_LocalName](../xmlreader/get_localname/) 和 [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) 值是否匹配给定字符串。但建议使用 [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) 方法，因为它提供了更直接的处理方式。 |
| virtual void [ReadEndElement](../xmlreader/readendelement/)() | 检查当前内容节点是否为结束标签，并将读取器推进到下一个节点。 |
| virtual [String](../../system/string/) [ReadInnerXml](../xmlreader/readinnerxml/)() | 在派生类中被重写时，将所有内容（包括标记）读取为字符串。 |
| virtual [String](../../system/string/) [ReadOuterXml](../xmlreader/readouterxml/)() | 在派生类中被重写时，读取表示此节点及其所有子节点的内容（包括标记）。 |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)() | 检查当前节点是否为元素，并将读取器推进到下一个节点。 |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/)) | 检查当前内容节点是否为具有给定 [XmlReader::get_Name](../xmlreader/get_name/) 值的元素，并将读取器推进到下一个节点。 |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/), [String](../../system/string/)) | 检查当前内容节点是否为具有给定 [XmlReader::get_LocalName](../xmlreader/get_localname/) 和 [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) 值的元素，并将读取器推进到下一个节点。 |
| [String](../../system/string/) [ReadString](./readstring/)() override | 将元素或文本节点的内容读取为字符串。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [ReadSubtree](../xmlreader/readsubtree/)() | 返回一个新的 [XmlReader](../xmlreader/) 实例，可用于读取当前节点及其所有后代。 |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/)) | 将 [XmlReader](../xmlreader/) 前进到具有指定限定名称的下一个后代元素。 |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | 将 [XmlReader](../xmlreader/) 前进到具有指定本地名称和命名空间 URI 的下一个后代元素。 |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/)) | 读取直到找到具有指定限定名称的元素。 |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | 读取直到找到具有指定本地名称和命名空间 URI 的元素。 |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/)) | 将 [XmlReader](../xmlreader/) 前进到具有指定限定名称的下一个兄弟元素。 |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | 将 [XmlReader](../xmlreader/) 前进到具有指定本地名称和命名空间 URI 的下一个兄弟元素。 |
| virtual **int32_t** [ReadValueChunk](../xmlreader/readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | 读取嵌入在 XML 文档中的大文本流。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于字符串和 nullptr 的情况。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于字符串的情况。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| void [ResolveEntity](./resolveentity/)() override | 解析 **EntityReference** 节点的实体引用。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设置为弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用，请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用，请使用智能指针或 ThisProtector。 |
| void [Skip](./skip/)() override | 跳过当前节点的子节点。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 方法的类似实现。启用自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用，请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用，请使用智能指针或 ThisProtector。 |
|  [XmlNodeReader](./xmlnodereader/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>\&) | 使用指定的 [XmlNode](../xmlnode/) 创建 [XmlNodeReader](./) 类的实例。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 类型别名

| 类型别名 | 描述 |
| --- | --- |
| [Ptr](./ptr/) | 此类实例的共享指针别名。 |

## 备注



此类的对象应仅使用 [System::MakeObject()](../../system/makeobject/) 函数进行分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言失败。始终将此类包装成 [System::SmartPtr](../../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 

## 另见

* 类 [XmlReader](../xmlreader/)
* 类 [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* 命名空间 [System::Xml](../)
* 库 [Aspose.Slides](../../)