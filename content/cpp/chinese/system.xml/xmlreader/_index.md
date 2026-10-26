---
title: XmlReader
second_title: Aspose.Slides for C++ API 参考
description: 表示一个读取器，提供快速、无缓存、仅前向访问 XML 数据的功能。
type: docs
weight: 430
url: /zh/system.xml/xmlreader/
---
## XmlReader 类

表示一个读取器，提供快速、无缓存、仅前向访问 XML 数据的功能。

```cpp
class XmlReader : public System::IDisposable
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual void [Close](./close/)() | 在派生类中覆盖时，将 [XmlReader::get_ReadState](./get_readstate/) 更改为 [ReadState::Closed](../readstate/)。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [String](../../system/string/)\&) | 使用指定的 URI 创建一个新的 [XmlReader](./) 实例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | 使用指定的 URI 和设置创建一个新的 [XmlReader](./) 实例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | 使用指定的 URI、设置和解析的上下文信息创建一个新的 [XmlReader](./) 实例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | 使用带有默认设置的指定流创建一个新的 [XmlReader](./) 实例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | 使用指定的流和设置创建一个新的 [XmlReader](./) 实例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | 使用指定的流、基础 URI 和设置创建一个新的 [XmlReader](./) 实例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | 使用指定的流、设置和解析的上下文信息创建一个新的 [XmlReader](./) 实例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | 使用指定的文本阅读器创建一个新的 [XmlReader](./) 实例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | 使用指定的文本阅读器和设置创建一个新的 [XmlReader](./) 实例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | 使用指定的文本阅读器、设置和基础 URI 创建一个新的 [XmlReader](./) 实例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | 使用指定的文本阅读器、设置和解析的上下文信息创建一个新的 [XmlReader](./) 实例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | 使用指定的 XML 阅读器和设置创建一个新的 [XmlReader](./) 实例。 |
| void [Dispose](./dispose/)() override | 释放当前 [XmlReader](./) 类实例使用的所有资源。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 样式比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 样式比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 仿真 C# 风格的浮点比较，两个 NaN 被视为相等，即使根据 IEC 60559:1989 NaN 不等于任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 仿真 C# 风格的浮点比较，两个 NaN 被视为相等，即使根据 IEC 60559:1989 NaN 不等于任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| virtual **int32_t** [get_AttributeCount](./get_attributecount/)() | 在派生类中覆盖时，获取当前节点上的属性数量。 |
| virtual [String](../../system/string/) [get_BaseURI](./get_baseuri/)() | 在派生类中覆盖时，获取当前节点的基础 URI。 |
| virtual **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() | 返回一个值，指示 [XmlReader](./) 是否实现二进制内容读取方法。 |
| virtual **bool** [get_CanReadValueChunk](./get_canreadvaluechunk/)() | 返回一个值，指示 [XmlReader](./) 是否实现 [XmlReader::ReadValueChunk](./readvaluechunk/) 方法。 |
| virtual **bool** [get_CanResolveEntity](./get_canresolveentity/)() | 返回一个值，指示此读取器是否可以解析和解析实体。 |
| virtual **int32_t** [get_Depth](./get_depth/)() | 在派生类中覆盖时，获取 XML 文档中当前节点的深度。 |
| virtual **bool** [get_EOF](./get_eof/)() | 在派生类中覆盖时，获取一个值，指示读取器是否位于流的末尾。 |
| virtual **bool** [get_HasAttributes](./get_hasattributes/)() | 返回一个值，指示当前节点是否有任何属性。 |
| virtual **bool** [get_HasValue](./get_hasvalue/)() | 在派生类中覆盖时，获取一个值，指示当前节点是否可以拥有 [XmlReader::get_Value](./get_value/) 值。 |
| virtual **bool** [get_IsDefault](./get_isdefault/)() | 在派生类中覆盖时，获取一个值，指示当前节点是否是由 DTD 或模式中定义的默认值生成的属性。 |
| virtual **bool** [get_IsEmptyElement](./get_isemptyelement/)() | 在派生类中覆盖时，获取一个值，指示当前节点是否为空元素（例如 **<MyElement/>**）。 |
| virtual [String](../../system/string/) [get_LocalName](./get_localname/)() | 在派生类中覆盖时，获取当前节点的本地名称。 |
| virtual [String](../../system/string/) [get_Name](./get_name/)() | 在派生类中覆盖时，获取当前节点的限定名称。 |
| virtual [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() | 在派生类中覆盖时，获取读取器所在节点的命名空间 URI（如 W3C 命名空间规范所定义）。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() | 在派生类中覆盖时，获取与此实现关联的 [XmlNameTable](../xmlnametable/)。 |
| virtual [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() | 在派生类中覆盖时，获取当前节点的类型。 |
| virtual [String](../../system/string/) [get_Prefix](./get_prefix/)() | 在派生类中覆盖时，获取与当前节点关联的命名空间前缀。 |
| virtual char16_t [get_QuoteChar](./get_quotechar/)() | 在派生类中覆盖时，获取用于包围属性节点值的引号字符。 |
| virtual [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() | 在派生类中覆盖时，获取读取器的状态。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() | 返回在模式验证后分配给当前节点的模式信息。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](./get_settings/)() | 返回用于创建此 [XmlReader](./) 实例的 [XmlReaderSettings](../xmlreadersettings/) 对象。 |
| virtual [String](../../system/string/) [get_Value](./get_value/)() | 在派生类中覆盖时，获取当前节点的文本值。 |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](./get_valuetype/)() | 返回当前节点的类型。 |
| virtual [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | 在派生类中覆盖时，获取当前 **xml:lang** 范围。 |
| virtual [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() | 在派生类中覆盖时，获取当前 **xml:space** 范围。 |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) | 在派生类中覆盖时，获取具有指定 [XmlReader::get_Name](./get_name/) 值的属性的值。 |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) | 在派生类中覆盖时，获取具有指定 [XmlReader::get_LocalName](./get_localname/) 和 [XmlReader::get_NamespaceURI](./get_namespaceuri/) 值的属性的值。 |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) | 在派生类中覆盖时，获取具有指定索引的属性的值。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法的等价实现。启用自定义对象的散列。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual [String](../../system/string/) [idx_get](./idx_get/)(**int32_t**) | 在派生类中覆盖时，获取具有指定索引的属性的值。 |
| virtual [String](../../system/string/) [idx_get](./idx_get/)([String](../../system/string/)) | 在派生类中覆盖时，获取具有指定 [XmlReader::get_Name](./get_name/) 值的属性的值。 |
| virtual [String](../../system/string/) [idx_get](./idx_get/)([String](../../system/string/), [String](../../system/string/)) | 在派生类中覆盖时，获取具有指定 [XmlReader::get_LocalName](./get_localname/) 和 [XmlReader::get_NamespaceURI](./get_namespaceuri/) 值的属性的值。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否是目标类型的实例。相当于 C# 的 'is' 运算符。 |
| static **bool** [IsName](./isname/)(const [String](../../system/string/)\&) | 返回一个值，指示字符串参数是否为有效的 XML 名称。 |
| static **bool** [IsNameToken](./isnametoken/)(const [String](../../system/string/)\&) | 返回一个值，指示字符串参数是否为有效的 XML 名称标记。 |
| virtual **bool** [IsStartElement](./isstartelement/)() | 调用 [XmlReader::MoveToContent](./movetocontent/) 并测试当前内容节点是否为开始标签或空元素标签。 |
| virtual **bool** [IsStartElement](./isstartelement/)([String](../../system/string/)) | 调用 [XmlReader::MoveToContent](./movetocontent/) 并测试当前内容节点是否为开始标签或空元素标签，以及找到的元素的 [XmlReader::get_Name](./get_name/) 值是否匹配给定参数。 |
| virtual **bool** [IsStartElement](./isstartelement/)([String](../../system/string/), [String](../../system/string/)) | 调用 [XmlReader::MoveToContent](./movetocontent/) 并测试当前内容节点是否为开始标签或空元素标签，以及找到的元素的 [XmlReader::get_LocalName](./get_localname/) 和 [XmlReader::get_NamespaceURI](./get_namespaceuri/) 值是否匹配给定字符串。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的锁定。直接调用或使用 [LockContext](../../system/lockcontext/) 监视对象。 |
| virtual [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) | 在派生类中覆盖时，解析当前元素作用域中的命名空间前缀。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法的等价实现。启用自定义类型的克隆。 |
| virtual **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) | 在派生类中覆盖时，移动到具有指定 [XmlReader::get_Name](./get_name/) 值的属性。 |
| virtual **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) | 在派生类中覆盖时，移动到具有指定 [XmlReader::get_LocalName](./get_localname/) 和 [XmlReader::get_NamespaceURI](./get_namespaceuri/) 值的属性。 |
| virtual void [MoveToAttribute](./movetoattribute/)(**int32_t**) | 在派生类中覆盖时，移动到具有指定索引的属性。 |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](./movetocontent/)() | 检查当前节点是否为内容节点（非空白文本、**CDATA**、**Element**、**EndElement**、**EntityReference** 或 **EndEntity**）。如果不是内容节点，读取器会跳过到下一个内容节点或文件结束。它会跳过以下类型的节点：**ProcessingInstruction**、**DocumentType**、**Comment**、**Whitespace** 或 **SignificantWhitespace**。 |
| virtual **bool** [MoveToElement](./movetoelement/)() | 在派生类中覆盖时，移动到包含当前属性节点的元素。 |
| virtual **bool** [MoveToFirstAttribute](./movetofirstattribute/)() | 在派生类中覆盖时，移动到第一个属性。 |
| virtual **bool** [MoveToNextAttribute](./movetonextattribute/)() | 在派生类中覆盖时，移动到下一个属性。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不拷贝任何内容，只是初始化新对象并允许子类拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不拷贝任何内容，只是初始化新对象并允许子类拷贝构造。 |
| virtual **bool** [Read](./read/)() | 在派生类中覆盖时，读取流中的下一个节点。 |
| virtual **bool** [ReadAttributeValue](./readattributevalue/)() | 在派生类中覆盖时，解析属性值为一个或多个 **[Text](../../system.text/)**、**EntityReference** 或 **EndEntity** 节点。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](./readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | 将内容读取为指定类型的对象。 |
| virtual **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | 读取内容并返回 Base64 解码后的二进制字节。 |
| virtual **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | 读取内容并返回 **BinHex** 解码后的二进制字节。 |
| virtual **bool** [ReadContentAsBoolean](./readcontentasboolean/)() | 将当前位置信息的文本内容读取为 [Boolean](../../system/boolean/)。 |
| virtual [DateTime](../../system/datetime/) [ReadContentAsDateTime](./readcontentasdatetime/)() | 将当前位置信息的文本内容读取为 [DateTime](../../system/datetime/) 对象。 |
| virtual [DateTimeOffset](../../system/datetimeoffset/) [ReadContentAsDateTimeOffset](./readcontentasdatetimeoffset/)() | 将当前位置信息的文本内容读取为 [DateTimeOffset](../../system/datetimeoffset/) 对象。 |
| virtual [Decimal](../../system/decimal/) [ReadContentAsDecimal](./readcontentasdecimal/)() | 将当前位置信息的文本内容读取为 [Decimal](../../system/decimal/) 对象。 |
| virtual **double** [ReadContentAsDouble](./readcontentasdouble/)() | 将当前位置信息的文本内容读取为双精度浮点数。 |
| virtual **float** [ReadContentAsFloat](./readcontentasfloat/)() | 将当前位置信息的文本内容读取为单精度浮点数。 |
| virtual **int32_t** [ReadContentAsInt](./readcontentasint/)() | 将当前位置信息的文本内容读取为 32 位有符号整数。 |
| virtual **int64_t** [ReadContentAsLong](./readcontentaslong/)() | 将当前位置信息的文本内容读取为 64 位有符号整数。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAsObject](./readcontentasobject/)() | 将当前位置信息的文本内容读取为 [Object](../../system/object/)。 |
| virtual [String](../../system/string/) [ReadContentAsString](./readcontentasstring/)() | 将当前位置信息的文本内容读取为 [String](../../system/string/) 对象。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](./readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | 将元素内容读取为请求的类型。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](./readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | 检查指定的本地名称和命名空间 URI 是否匹配当前元素，然后将元素内容读取为请求的类型。 |
| virtual **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | 读取元素并解码 **Base64** 内容。 |
| virtual **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | 读取元素并解码 **BinHex** 内容。 |
| virtual **bool** [ReadElementContentAsBoolean](./readelementcontentasboolean/)() | 读取当前元素并将其内容返回为 [Boolean](../../system/boolean/) 对象。 |
| virtual **bool** [ReadElementContentAsBoolean](./readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | 检查指定的本地名称和命名空间 URI 是否匹配当前元素，然后读取当前元素并将其内容返回为 [Boolean](../../system/boolean/) 对象。 |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](./readelementcontentasdatetime/)() | 读取当前元素并将其内容返回为 [DateTime](../../system/datetime/) 对象。 |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](./readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | 检查指定的本地名称和命名空间 URI 是否匹配当前元素，然后读取当前元素并将其内容返回为 [DateTime](../../system/datetime/) 对象。 |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](./readelementcontentasdecimal/)() | 读取当前元素并将其内容返回为 [Decimal](../../system/decimal/) 对象。 |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](./readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | 检查指定的本地名称和命名空间 URI 是否匹配当前元素，然后读取当前元素并将其内容返回为 [Decimal](../../system/decimal/) 对象。 |
| virtual **double** [ReadElementContentAsDouble](./readelementcontentasdouble/)() | 读取当前元素并将其内容返回为双精度浮点数。 |
| virtual **double** [ReadElementContentAsDouble](./readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | 检查指定的本地名称和命名空间 URI 是否匹配当前元素，然后读取当前元素并将其内容返回为双精度浮点数。 |
| virtual **float** [ReadElementContentAsFloat](./readelementcontentasfloat/)() | 读取当前元素并将其内容返回为单精度浮点数。 |
| virtual **float** [ReadElementContentAsFloat](./readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | 检查指定的本地名称和命名空间 URI 是否匹配当前元素，然后读取当前元素并将其内容返回为单精度浮点数。 |
| virtual **int32_t** [ReadElementContentAsInt](./readelementcontentasint/)() | 读取当前元素并将其内容返回为 32 位有符号整数。 |
| virtual **int32_t** [ReadElementContentAsInt](./readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | 检查指定的本地名称和命名空间 URI 是否匹配当前元素，然后读取当前元素并将其内容返回为 32 位有符号整数。 |
| virtual **int64_t** [ReadElementContentAsLong](./readelementcontentaslong/)() | 读取当前元素并将其内容返回为 64 位有符号整数。 |
| virtual **int64_t** [ReadElementContentAsLong](./readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | 检查指定的本地名称和命名空间 URI 是否匹配当前元素，然后读取当前元素并将其内容返回为 64 位有符号整数。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](./readelementcontentasobject/)() | 读取当前元素并将其内容返回为 [Object](../../system/object/)。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](./readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | 检查指定的本地名称和命名空间 URI 是否匹配当前元素，然后读取当前元素并将其内容返回为 [Object](../../system/object/)。 |
| virtual [String](../../system/string/) [ReadElementContentAsString](./readelementcontentasstring/)() | 读取当前元素并将其内容返回为 [String](../../system/string/) 对象。 |
| virtual [String](../../system/string/) [ReadElementContentAsString](./readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | 检查指定的本地名称和命名空间 URI 是否匹配当前元素，然后读取当前元素并将其内容返回为 [String](../../system/string/) 对象。 |
| virtual [String](../../system/string/) [ReadElementString](./readelementstring/)() | 读取仅文本元素。不过，建议使用 [XmlReader::ReadElementContentAsString](./readelementcontentasstring/) 方法，因为它提供更直接的方式来处理此操作。 |
| virtual [String](../../system/string/) [ReadElementString](./readelementstring/)([String](../../system/string/)) | 检查找到的元素的 [XmlReader::get_Name](./get_name/) 值是否匹配给定字符串，然后读取仅文本元素。不过，建议使用 [XmlReader::ReadElementContentAsString](./readelementcontentasstring/) 方法，因为它提供更直接的方式来处理此操作。 |
| virtual [String](../../system/string/) [ReadElementString](./readelementstring/)([String](../../system/string/), [String](../../system/string/)) | 检查找到的元素的 [XmlReader::get_LocalName](./get_localname/) 和 [XmlReader::get_NamespaceURI](./get_namespaceuri/) 值是否匹配给定字符串，然后读取仅文本元素。不过，建议使用 [XmlReader::ReadElementContentAsString](./readelementcontentasstring/) 方法，因为它提供更直接的方式来处理此操作。 |
| virtual void [ReadEndElement](./readendelement/)() | 检查当前内容节点是结束标签并将读取器前进到下一个节点。 |
| virtual [String](../../system/string/) [ReadInnerXml](./readinnerxml/)() | 在派生类中覆盖时，读取所有内容，包括标记，作为字符串。 |
| virtual [String](../../system/string/) [ReadOuterXml](./readouterxml/)() | 在派生类中覆盖时，读取包括标记在内的内容，表示此节点及其所有子节点。 |
| virtual void [ReadStartElement](./readstartelement/)() | 检查当前节点是元素并将读取器前进到下一个节点。 |
| virtual void [ReadStartElement](./readstartelement/)([String](../../system/string/)) | 检查当前内容节点是具有给定 [XmlReader::get_Name](./get_name/) 值的元素并将读取器前进到下一个节点。 |
| virtual void [ReadStartElement](./readstartelement/)([String](../../system/string/), [String](../../system/string/)) | 检查当前内容节点是具有给定 [XmlReader::get_LocalName](./get_localname/) 和 [XmlReader::get_NamespaceURI](./get_namespaceuri/) 值的元素并将读取器前进到下一个节点。 |
| virtual [String](../../system/string/) [ReadString](./readstring/)() | 在派生类中覆盖时，读取元素或文本节点的内容为字符串。不过，建议使用 [XmlReader::ReadElementContentAsString](./readelementcontentasstring/) 方法，因为它提供更直接的方式来处理此操作。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [ReadSubtree](./readsubtree/)() | 返回一个新的 [XmlReader](./) 实例，可用于读取当前节点及其所有后代。 |
| virtual **bool** [ReadToDescendant](./readtodescendant/)([String](../../system/string/)) | 将 [XmlReader](./) 前进到具有指定限定名称的下一个后代元素。 |
| virtual **bool** [ReadToDescendant](./readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | 将 [XmlReader](./) 前进到具有指定本地名称和命名空间 URI 的下一个后代元素。 |
| virtual **bool** [ReadToFollowing](./readtofollowing/)([String](../../system/string/)) | 读取直到找到具有指定限定名称的元素。 |
| virtual **bool** [ReadToFollowing](./readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | 读取直到找到具有指定本地名称和命名空间 URI 的元素。 |
| virtual **bool** [ReadToNextSibling](./readtonextsibling/)([String](../../system/string/)) | 将 [XmlReader](./) 前进到具有指定限定名称的下一个同级元素。 |
| virtual **bool** [ReadToNextSibling](./readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | 将 [XmlReader](./) 前进到具有指定本地名称和命名空间 URI 的下一个同级元素。 |
| virtual **int32_t** [ReadValueChunk](./readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | 读取嵌入在 XML 文档中的大文本流。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 对字符串和 nullptr 情形的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 对字符串情形的特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| virtual void [ResolveEntity](./resolveentity/)() | 在派生类中覆盖时，解析 **EntityReference** 节点的实体引用。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设置为弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 增加共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 减少并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual void [Skip](./skip/)() | 跳过当前节点的子节点。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 方法的等价实现。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 监视对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 增加弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 减少弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |
## 类型定义

| 类型定义 | 描述 |
| --- | --- |
| [Ptr](./ptr/) | 此类实例的共享指针别名。 |
## 另请参见

* 类 [IDisposable](../../system/idisposable/)
* 命名空间 [System::Xml](../)
* 库 [Aspose.Slides](../../)