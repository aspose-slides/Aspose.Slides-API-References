---
title: XmlTextReader
second_title: Aspose.Slides for C++ API 参考
description: 表示提供快速、非缓存、仅向前访问 XML 数据的阅读器。
type: docs
weight: 508
url: /zh/system.xml/xmltextreader/
---
## XmlTextReader 类


表示提供快速、非缓存、仅向前访问 XML 数据的阅读器。

```cpp
class XmlTextReader : public System::Xml::XmlReader,
                      public System::Xml::IXmlLineInfo,
                      public System::Xml::IXmlNamespaceResolver
```

## 方法

| 方法 | 描述 |
| --- | --- |
| void [Close](./close/)() override | 将 [XmlReader::get_ReadState](../xmlreader/get_readstate/) 更改为 **Closed**。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&) | 创建具有指定 URI 的新 [XmlReader](../xmlreader/) 实例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | 使用指定的 URI 和设置创建新 [XmlReader](../xmlreader/) 实例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | 使用指定的 URI、设置和用于解析的上下文信息创建新 [XmlReader](../xmlreader/) 实例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | 使用指定的流和默认设置创建新 [XmlReader](../xmlreader/) 实例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | 使用指定的流和设置创建新 [XmlReader](../xmlreader/) 实例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | 使用指定的流、基础 URI 和设置创建新 [XmlReader](../xmlreader/) 实例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | 使用指定的流、设置和用于解析的上下文信息创建新 [XmlReader](../xmlreader/) 实例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | 使用指定的文本阅读器创建新 [XmlReader](../xmlreader/) 实例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | 使用指定的文本阅读器和设置创建新 [XmlReader](../xmlreader/) 实例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | 使用指定的文本阅读器、设置和基础 URI 创建新 [XmlReader](../xmlreader/) 实例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | 使用指定的文本阅读器、设置和用于解析的上下文信息创建新 [XmlReader](../xmlreader/) 实例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | 使用指定的 XML 阅读器和设置创建新 [XmlReader](../xmlreader/) 实例。 |
| void [Dispose](../xmlreader/dispose/)() override | 释放当前 [XmlReader](../xmlreader/) 类实例使用的所有资源。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，即使根据 IEC 60559:1989 NaN 与任何值（包括 NaN）都不相等，也将两个 NaN 视为相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，即使根据 IEC 60559:1989 NaN 与任何值（包括 NaN）都不相等，也将两个 NaN 视为相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| **int32_t** [get_AttributeCount](./get_attributecount/)() override | 返回当前节点的属性数量。 |
| [String](../../system/string/) [get_BaseURI](./get_baseuri/)() override | 返回当前节点的基础 URI。 |
| **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() override | 返回指示 [XmlTextReader](./) 是否实现二进制内容读取方法的值。 |
| **bool** [get_CanReadValueChunk](./get_canreadvaluechunk/)() override | 返回指示 [XmlTextReader](./) 是否实现 [XmlReader::ReadValueChunk](../xmlreader/readvaluechunk/) 方法的值。 |
| **bool** [get_CanResolveEntity](./get_canresolveentity/)() override | 返回指示此阅读器是否能够解析并解析实体的值。 |
| **int32_t** [get_Depth](./get_depth/)() override | 返回 XML 文档中当前节点的深度。 |
| [System::Xml::DtdProcessing](../dtdprocessing/) [get_DtdProcessing](./get_dtdprocessing/)() | 返回 DtdProcessing 枚举。 |
| [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | 返回文档的编码。 |
| [System::Xml::EntityHandling](../entityhandling/) [get_EntityHandling](./get_entityhandling/)() | 返回指定阅读器如何处理实体的值。 |
| **bool** [get_EOF](./get_eof/)() override | 返回指示阅读器是否位于流末尾的值。 |
| virtual **bool** [get_HasAttributes](../xmlreader/get_hasattributes/)() | 返回指示当前节点是否具有任何属性的值。 |
| **bool** [get_HasValue](./get_hasvalue/)() override | 返回指示当前节点是否可以拥有除 [String::Empty](../../system/string/empty/) 之外的 [XmlTextReader::get_Value](./get_value/) 的值。 |
| **bool** [get_IsDefault](./get_isdefault/)() override | 返回指示当前节点是否为 DTD 或模式中定义的默认值生成的属性的值。 |
| **bool** [get_IsEmptyElement](./get_isemptyelement/)() override | 返回指示当前节点是否为空元素的值（例如 **<MyElement/>**）。 |
| **int32_t** [get_LineNumber](./get_linenumber/)() override | 返回当前行号。 |
| **int32_t** [get_LinePosition](./get_lineposition/)() override | 返回当前行位置。 |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | 返回当前节点的本地名称。 |
| [String](../../system/string/) [get_Name](./get_name/)() override | 返回当前节点的限定名称。 |
| **bool** [get_Namespaces](./get_namespaces/)() | 返回指示是否进行命名空间支持的值。 |
| [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() override | 返回阅读器所在节点的命名空间 URI（如 W3C 命名空间规范所定义）。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() override | 返回与此实现关联的 [XmlNameTable](../xmlnametable/)。 |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | 返回当前节点的类型。 |
| **bool** [get_Normalization](./get_normalization/)() | 返回指示是否规范化空白和属性值的值。 |
| [String](../../system/string/) [get_Prefix](./get_prefix/)() override | 返回与当前节点关联的命名空间前缀。 |
| **bool** [get_ProhibitDtd](./get_prohibitdtd/)() | 返回指示是否允许 DTD 处理的值。 |
| char16_t [get_QuoteChar](./get_quotechar/)() override | 返回用于包围属性节点值的引号字符。 |
| [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() override | 返回阅读器的状态。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](../xmlreader/get_schemainfo/)() | 返回因模式验证而分配给当前节点的模式信息。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](../xmlreader/get_settings/)() | 返回用于创建此 [XmlReader](../xmlreader/) 实例的 [XmlReaderSettings](../xmlreadersettings/) 对象。 |
| [String](../../system/string/) [get_Value](./get_value/)() override | 返回当前节点的文本值。 |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](../xmlreader/get_valuetype/)() | 返回当前节点的类型。 |
| [System::Xml::WhitespaceHandling](../whitespacehandling/) [get_WhitespaceHandling](./get_whitespacehandling/)() | 返回指定空白处理方式的值。 |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | 返回当前 **xml:lang** 范围。 |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | 返回当前 **xml:space** 范围。 |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) override | 返回具有指定名称的属性的值。 |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) override | 返回具有指定本地名称和命名空间 URI 的属性的值。 |
| [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) override | 返回具有指定索引的属性的值。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的哈希。 |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[String](../../system/string/), [String](../../system/string/)\>\> [GetNamespacesInScope](./getnamespacesinscope/)([XmlNamespaceScope](../xmlnamespacescope/)) override | 返回包含当前作用域内所有命名空间的集合。 |
| [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\> [GetRemainder](./getremainder/)() | 返回缓冲的 XML 剩余部分。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| **bool** [HasLineInfo](./haslineinfo/)() override | 返回指示类是否可以返回行信息的值。 |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)(**int32_t**) | 在派生类中重写时，获取具有指定索引的属性的值。 |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/)) | 在派生类中重写时，获取具有指定 [XmlReader::get_Name](../xmlreader/get_name/) 值的属性的值。 |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/), [String](../../system/string/)) | 在派生类中重写时，获取具有指定 [XmlReader::get_LocalName](../xmlreader/get_localname/) 和 [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) 值的属性的值。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 描述的类型实例。相当于 C# 'is' 运算符。 |
| static **bool** [IsName](../xmlreader/isname/)(const [String](../../system/string/)\&) | 返回指示字符串参数是否为有效 XML 名称的值。 |
| static **bool** [IsNameToken](../xmlreader/isnametoken/)(const [String](../../system/string/)\&) | 返回指示字符串参数是否为有效 XML 名称标记的值。 |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)() | 调用 [XmlReader::MoveToContent](../xmlreader/movetocontent/) 并测试当前内容节点是否为开始标签或空元素标签。 |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/)) | 调用 [XmlReader::MoveToContent](../xmlreader/movetocontent/) 并测试当前内容节点是否为开始标签或空元素标签，以及找到的元素的 [XmlReader::get_Name](../xmlreader/get_name/) 值是否匹配给定参数。 |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/), [String](../../system/string/)) | 调用 [XmlReader::MoveToContent](../xmlreader/movetocontent/) 并测试当前内容节点是否为开始标签或空元素标签，以及找到的元素的 [XmlReader::get_LocalName](../xmlreader/get_localname/) 和 [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) 值是否匹配给定字符串。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | 解析当前元素作用域中的命名空间前缀。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) override | 移动到具有指定名称的属性。 |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) override | 移动到具有指定本地名称和命名空间 URI 的属性。 |
| void [MoveToAttribute](./movetoattribute/)(**int32_t**) override | 移动到具有指定索引的属性。 |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](../xmlreader/movetocontent/)() | 检查当前节点是否为内容节点（非空白文本、**CDATA**、**Element**、**EndElement**、**EntityReference** 或 **EndEntity**）。如果不是内容节点，阅读器将跳过至下一个内容节点或文件结束。它会跳过以下类型的节点：**ProcessingInstruction**、**DocumentType**、**Comment**、**Whitespace** 或 **SignificantWhitespace**。 |
| **bool** [MoveToElement](./movetoelement/)() override | 移动到包含当前属性节点的元素。 |
| **bool** [MoveToFirstAttribute](./movetofirstattribute/)() override | 移动到第一个属性。 |
| **bool** [MoveToNextAttribute](./movetonextattribute/)() override | 移动到下一个属性。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，只是初始化新对象并允许子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，只是初始化新对象并允许子类的拷贝构造。 |
| **bool** [Read](./read/)() override | 从流中读取下一个节点。 |
| **bool** [ReadAttributeValue](./readattributevalue/)() override | 将属性值解析为一个或多个 **[Text](../../system.text/)**、**EntityReference** 或 **EndEntity** 节点。 |
| **int32_t** [ReadBase64](./readbase64/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | 解码 Base64 并返回解码后的二进制字节。 |
| **int32_t** [ReadBinHex](./readbinhex/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | 解码 **BinHex** 并返回解码后的二进制字节。 |
| **int32_t** [ReadChars](./readchars/)(const [ArrayPtr](../../system/arrayptr/)\<char16_t\>\&, **int32_t**, **int32_t**) | 将元素的文本内容读取到字符缓冲区。此方法旨在通过连续调用读取大量嵌入式文本流。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](../xmlreader/readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | 将内容读取为指定类型的对象。 |
| **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | 读取内容并返回 **Base64** 解码后的二进制字节。 |
| **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | 读取内容并返回 **BinHex** 解码后的二进制字节。 |
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
| **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | 读取元素并解码 **BinHex** 内容。 |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)() | 读取当前元素并将内容返回为 [Boolean](../../system/boolean/) 对象。 |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | 检查指定的本地名称和命名空间 URI 是否与当前元素匹配，然后读取当前元素并将内容返回为 [Boolean](../../system/boolean/) 对象。 |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)() | 读取当前元素并将内容返回为 [DateTime](../../system/datetime/) 对象。 |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | 检查指定的本地名称和命名空间 URI 是否与当前元素匹配，然后读取当前元素并将内容返回为 [DateTime](../../system/datetime/) 对象。 |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)() | 读取当前元素并将内容返回为 [Decimal](../../system/decimal/) 对象。 |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | 检查指定的本地名称和命名空间 URI 是否与当前元素匹配，然后读取当前元素并将内容返回为 [Decimal](../../system/decimal/) 对象。 |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)() | 读取当前元素并将内容返回为双精度浮点数。 |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | 检查指定的本地名称和命名空间 URI 是否与当前元素匹配，然后读取当前元素并将内容返回为双精度浮点数。 |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)() | 读取当前元素并将内容返回为单精度浮点数。 |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | 检查指定的本地名称和命名空间 URI 是否与当前元素匹配，然后读取当前元素并将内容返回为单精度浮点数。 |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)() | 读取当前元素并将内容返回为 32 位有符号整数。 |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | 检查指定的本地名称和命名空间 URI 是否与当前元素匹配，然后读取当前元素并将内容返回为 32 位有符号整数。 |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)() | 读取当前元素并将内容返回为 64 位有符号整数。 |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | 检查指定的本地名称和命名空间 URI 是否与当前元素匹配，然后读取当前元素并将内容返回为 64 位有符号整数。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)() | 读取当前元素并将内容返回为 [Object](../../system/object/)。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | 检查指定的本地名称和命名空间 URI 是否与当前元素匹配，然后读取当前元素并将内容返回为 [Object](../../system/object/)。 |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)() | 读取当前元素并将内容返回为 [String](../../system/string/) 对象。 |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | 检查指定的本地名称和命名空间 URI 是否与当前元素匹配，然后读取当前元素并将内容返回为 [String](../../system/string/) 对象。 |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)() | 读取仅文本元素。然而，建议使用 [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) 方法，因为它提供了更直接的处理方式。 |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/)) | 在读取仅文本元素之前，检查找到的元素的 [XmlReader::get_Name](../xmlreader/get_name/) 值是否与给定字符串匹配。然而，建议使用 [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) 方法，因为它提供了更直接的处理方式。 |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/), [String](../../system/string/)) | 在读取仅文本元素之前，检查找到的元素的 [XmlReader::get_LocalName](../xmlreader/get_localname/) 和 [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) 值是否与给定字符串匹配。然而，建议使用 [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) 方法，因为它提供了更直接的处理方式。 |
| virtual void [ReadEndElement](../xmlreader/readendelement/)() | 检查当前内容节点是否为结束标签，并将阅读器前进到下一个节点。 |
| virtual [String](../../system/string/) [ReadInnerXml](../xmlreader/readinnerxml/)() | 在派生类中重写时，将所有内容（包括标记）读取为字符串。 |
| virtual [String](../../system/string/) [ReadOuterXml](../xmlreader/readouterxml/)() | 在派生类中重写时，读取表示此节点及其所有子节点的内容（包括标记）。 |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)() | 检查当前节点是否为元素，并将阅读器前进到下一个节点。 |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/)) | 检查当前内容节点是否为具有给定 [XmlReader::get_Name](../xmlreader/get_name/) 值的元素，并将阅读器前进到下一个节点。 |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/), [String](../../system/string/)) | 检查当前内容节点是否为具有给定 [XmlReader::get_LocalName](../xmlreader/get_localname/) 和 [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) 值的元素，并将阅读器前进到下一个节点。 |
| [String](../../system/string/) [ReadString](./readstring/)() override | 将元素或文本节点的内容读取为字符串。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [ReadSubtree](../xmlreader/readsubtree/)() | 返回可用于读取当前节点及其所有后代的新 [XmlReader](../xmlreader/) 实例。 |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/)) | 将 [XmlReader](../xmlreader/) 前进到具有指定限定名称的下一个后代元素。 |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | 将 [XmlReader](../xmlreader/) 前进到具有指定本地名称和命名空间 URI 的下一个后代元素。 |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/)) | 读取直到找到具有指定限定名称的元素。 |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | 读取直到找到具有指定本地名称和命名空间 URI 的元素。 |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/)) | 将 [XmlReader](../xmlreader/) 前进到具有指定限定名称的下一个兄弟元素。 |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | 将 [XmlReader](../xmlreader/) 前进到具有指定本地名称和命名空间 URI 的下一个兄弟元素。 |
| virtual **int32_t** [ReadValueChunk](../xmlreader/readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | 读取嵌入在 XML 文档中的大型文本流。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 针对字符串和 nullptr 情况的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 针对字符串情况的特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 将共享引用计数减少指定值。 |
| void [ResetState](./resetstate/)() | 将阅读器的状态重置为 [ReadState::Initial](../readstate/)。 |
| void [ResolveEntity](./resolveentity/)() override | 解析 **EntityReference** 节点的实体引用。 |
| void [set_DtdProcessing](./set_dtdprocessing/)([System::Xml::DtdProcessing](../dtdprocessing/)) | 设置 DtdProcessing 枚举。 |
| void [set_EntityHandling](./set_entityhandling/)([System::Xml::EntityHandling](../entityhandling/)) | 设置指定阅读器如何处理实体的值。 |
| void [set_Namespaces](./set_namespaces/)(**bool**) | 设置指示是否进行命名空间支持的值。 |
| void [set_Normalization](./set_normalization/)(**bool**) | 设置指示是否规范化空白和属性值的值。 |
| void [set_ProhibitDtd](./set_prohibitdtd/)(**bool**) | 设置指示是否允许 DTD 处理的值。 |
| void [set_WhitespaceHandling](./set_whitespacehandling/)([System::Xml::WhitespaceHandling](../whitespacehandling/)) | 设置指定空白处理方式的值。 |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../xmlresolver/)\>\&) | 设置用于解析 DTD 引用的 [XmlResolver](../xmlresolver/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享）。允许在容器中将指针切换为弱引用模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [Skip](./skip/)() override | 跳过当前节点的子节点。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | 使用指定的流初始化 [XmlTextReader](./) 类的新实例。 |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | 使用指定的 URL 和流初始化 [XmlTextReader](./) 类的新实例。 |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | 使用指定的流和 [XmlNameTable](../xmlnametable/) 初始化 [XmlTextReader](./) 类的新实例。 |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | 使用指定的 URL、流和 [XmlNameTable](../xmlnametable/) 初始化 [XmlTextReader](./) 类的新实例。 |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | 使用指定的 TextReader 初始化 [XmlTextReader](./) 类的新实例。 |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | 使用指定的 URL 和 TextReader 初始化 [XmlTextReader](./) 类的新实例。 |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | 使用指定的 TextReader 和 [XmlNameTable](../xmlnametable/) 初始化 [XmlTextReader](./) 类的新实例。 |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | 使用指定的 URL、TextReader 和 [XmlNameTable](../xmlnametable/) 初始化 [XmlTextReader](./) 类的新实例。 |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | 使用指定的流、XmlNodeType 和 [XmlParserContext](../xmlparsercontext/) 初始化 [XmlTextReader](./) 类的新实例。 |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | 使用指定的字符串、XmlNodeType 和 [XmlParserContext](../xmlparsercontext/) 初始化 [XmlTextReader](./) 类的新实例。 |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&) | 使用指定的文件初始化 [XmlTextReader](./) 类的新实例。 |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | 使用指定的文件和 [XmlNameTable](../xmlnametable/) 初始化 [XmlTextReader](./) 类的新实例。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 类型别名

| 类型别名 | 描述 |
| --- | --- |
| [Ptr](./ptr/) | 此类实例的共享指针别名。 |

## 备注

建议使用 [XmlReader](../xmlreader/) 类。

此类的对象应仅通过 [System::MakeObject()](../../system/makeobject/) 函数分配。永远不要在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装成 [System::SmartPtr](../../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。

## 另见

* 类 [XmlReader](../xmlreader/)
* 类 [IXmlLineInfo](../ixmllineinfo/)
* 类 [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* 命名空间 [System::Xml](../)
* 库 [Aspose.Slides](../../)