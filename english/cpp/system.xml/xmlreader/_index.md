---
title: XmlReader
second_title: Aspose.Slides for C++ API Reference
description: Represents a reader that provides fast, noncached, forward-only access to XML data.
type: docs
weight: 430
url: /cpp/system.xml/xmlreader/
---
## XmlReader class


Represents a reader that provides fast, noncached, forward-only access to XML data.

```cpp
class XmlReader : public System::IDisposable
```

## Methods

| Method | Description |
| --- | --- |
| virtual void [Close](./close/)() | When overridden in a derived class, changes the [XmlReader::get_ReadState](./get_readstate/) to [ReadState::Closed](../readstate/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [String](../../system/string/)\&) | Creates a new [XmlReader](./) instance with specified URI. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Creates a new [XmlReader](./) instance by using the specified URI and settings. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Creates a new [XmlReader](./) instance by using the specified URI, settings, and context information for parsing. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Creates a new [XmlReader](./) instance using the specified stream with default settings. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Creates a new [XmlReader](./) instance with the specified stream and settings. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Creates a new [XmlReader](./) instance using the specified stream, base URI, and settings. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Creates a new [XmlReader](./) instance using the specified stream, settings, and context information for parsing. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | Creates a new [XmlReader](./) instance by using the specified text reader. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Creates a new [XmlReader](./) instance by using the specified text reader and settings. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Creates a new [XmlReader](./) instance by using the specified text reader, settings, and base URI. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Creates a new [XmlReader](./) instance by using the specified text reader, settings, and context information for parsing. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | Creates a new [XmlReader](./) instance by using the specified XML reader and settings. |
| void [Dispose](./dispose/)() override | Releases all resources used by the current instance of the [XmlReader](./) class. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares value type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| virtual **int32_t** [get_AttributeCount](./get_attributecount/)() | When overridden in a derived class, gets the number of attributes on the current node. |
| virtual [String](../../system/string/) [get_BaseURI](./get_baseuri/)() | When overridden in a derived class, gets the base URI of the current node. |
| virtual **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() | Returns a value indicating whether the [XmlReader](./) implements the binary content read methods. |
| virtual **bool** [get_CanReadValueChunk](./get_canreadvaluechunk/)() | Returns a value indicating whether the [XmlReader](./) implements the [XmlReader::ReadValueChunk](./readvaluechunk/) method. |
| virtual **bool** [get_CanResolveEntity](./get_canresolveentity/)() | Returns a value indicating whether this reader can parse and resolve entities. |
| virtual **int32_t** [get_Depth](./get_depth/)() | When overridden in a derived class, gets the depth of the current node in the XML document. |
| virtual **bool** [get_EOF](./get_eof/)() | When overridden in a derived class, gets a value indicating whether the reader is positioned at the end of the stream. |
| virtual **bool** [get_HasAttributes](./get_hasattributes/)() | Returns a value indicating whether the current node has any attributes. |
| virtual **bool** [get_HasValue](./get_hasvalue/)() | When overridden in a derived class, gets a value indicating whether the current node can have a [XmlReader::get_Value](./get_value/) value. |
| virtual **bool** [get_IsDefault](./get_isdefault/)() | When overridden in a derived class, gets a value indicating whether the current node is an attribute that was generated from the default value defined in the DTD or schema. |
| virtual **bool** [get_IsEmptyElement](./get_isemptyelement/)() | When overridden in a derived class, gets a value indicating whether the current node is an empty element (for example, **<MyElement/>**). |
| virtual [String](../../system/string/) [get_LocalName](./get_localname/)() | When overridden in a derived class, gets the local name of the current node. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() | When overridden in a derived class, gets the qualified name of the current node. |
| virtual [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() | When overridden in a derived class, gets the namespace URI (as defined in the W3C Namespace specification) of the node on which the reader is positioned. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() | When overridden in a derived class, gets the [XmlNameTable](../xmlnametable/) associated with this implementation. |
| virtual [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() | When overridden in a derived class, gets the type of the current node. |
| virtual [String](../../system/string/) [get_Prefix](./get_prefix/)() | When overridden in a derived class, gets the namespace prefix associated with the current node. |
| virtual char16_t [get_QuoteChar](./get_quotechar/)() | When overridden in a derived class, gets the quotation mark character used to enclose the value of an attribute node. |
| virtual [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() | When overridden in a derived class, gets the state of the reader. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() | Returns the schema information that has been assigned to the current node as a result of schema validation. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](./get_settings/)() | Returns the [XmlReaderSettings](../xmlreadersettings/) object used to create this [XmlReader](./) instance. |
| virtual [String](../../system/string/) [get_Value](./get_value/)() | When overridden in a derived class, gets the text value of the current node. |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](./get_valuetype/)() | Returns The type for the current node. |
| virtual [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | When overridden in a derived class, gets the current **xml:lang** scope. |
| virtual [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() | When overridden in a derived class, gets the current **xml:space** scope. |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) | When overridden in a derived class, gets the value of the attribute with the specified [XmlReader::get_Name](./get_name/) value. |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) | When overridden in a derived class, gets the value of the attribute with the specified [XmlReader::get_LocalName](./get_localname/) and [XmlReader::get_NamespaceURI](./get_namespaceuri/) values. |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) | When overridden in a derived class, gets the value of the attribute with the specified index. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gets actual type of object. Analog of C# [System.Object.GetType()](../../system/object/gettype/) call. |
| virtual [String](../../system/string/) [idx_get](./idx_get/)(**int32_t**) | When overridden in a derived class, gets the value of the attribute with the specified index. |
| virtual [String](../../system/string/) [idx_get](./idx_get/)([String](../../system/string/)) | When overridden in a derived class, gets the value of the attribute with the specified [XmlReader::get_Name](./get_name/) value. |
| virtual [String](../../system/string/) [idx_get](./idx_get/)([String](../../system/string/), [String](../../system/string/)) | When overridden in a derived class, gets the value of the attribute with the specified [XmlReader::get_LocalName](./get_localname/) and [XmlReader::get_NamespaceURI](./get_namespaceuri/) values. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Check if object represents an instance of type described by targetType. Analog of C# 'is' operator. |
| static **bool** [IsName](./isname/)(const [String](../../system/string/)\&) | Returns a value indicating whether the string argument is a valid XML name. |
| static **bool** [IsNameToken](./isnametoken/)(const [String](../../system/string/)\&) | Returns a value indicating whether or not the string argument is a valid XML name token. |
| virtual **bool** [IsStartElement](./isstartelement/)() | Calls [XmlReader::MoveToContent](./movetocontent/) and tests if the current content node is a start tag or empty element tag. |
| virtual **bool** [IsStartElement](./isstartelement/)([String](../../system/string/)) | Calls [XmlReader::MoveToContent](./movetocontent/) and tests if the current content node is a start tag or empty element tag and if the [XmlReader::get_Name](./get_name/) value of the element found matches the given argument. |
| virtual **bool** [IsStartElement](./isstartelement/)([String](../../system/string/), [String](../../system/string/)) | Calls [XmlReader::MoveToContent](./movetocontent/) and tests if the current content node is a start tag or empty element tag and if the [XmlReader::get_LocalName](./get_localname/) and [XmlReader::get_NamespaceURI](./get_namespaceuri/) values of the element found match the given strings. |
| void [Lock](../../system/object/lock/)() | Implements C# lock() statement locking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| virtual [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) | When overridden in a derived class, resolves a namespace prefix in the current element's scope. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog of C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) method. Enables cloning custom types. |
| virtual **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) | When overridden in a derived class, moves to the attribute with the specified [XmlReader::get_Name](./get_name/) value. |
| virtual **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) | When overridden in a derived class, moves to the attribute with the specified [XmlReader::get_LocalName](./get_localname/) and [XmlReader::get_NamespaceURI](./get_namespaceuri/) values. |
| virtual void [MoveToAttribute](./movetoattribute/)(**int32_t**) | When overridden in a derived class, moves to the attribute with the specified index. |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](./movetocontent/)() | Checks whether the current node is a content (non-white space text, **CDATA**, **Element**, **EndElement**, **EntityReference**, or **EndEntity**) node. If the node is not a content node, the reader skips ahead to the next content node or end of file. It skips over nodes of the following type: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace**, or **SignificantWhitespace**. |
| virtual **bool** [MoveToElement](./movetoelement/)() | When overridden in a derived class, moves to the element that contains the current attribute node. |
| virtual **bool** [MoveToFirstAttribute](./movetofirstattribute/)() | When overridden in a derived class, moves to the first attribute. |
| virtual **bool** [MoveToNextAttribute](./movetonextattribute/)() | When overridden in a derived class, moves to the next attribute. |
|  [Object](../../system/object/object/)() | Creates object. Initializes all internal data structures. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy constructor. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Assignment operator. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| virtual **bool** [Read](./read/)() | When overridden in a derived class, reads the next node from the stream. |
| virtual **bool** [ReadAttributeValue](./readattributevalue/)() | When overridden in a derived class, parses the attribute value into one or more **[Text](../../system.text/)**, **EntityReference**, or **EndEntity** nodes. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](./readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Reads the content as an object of the type specified. |
| virtual **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | Reads the content and returns the Base64 decoded binary bytes. |
| virtual **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | Reads the content and returns the **BinHex** decoded binary bytes. |
| virtual **bool** [ReadContentAsBoolean](./readcontentasboolean/)() | Reads the text content at the current position as a [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadContentAsDateTime](./readcontentasdatetime/)() | Reads the text content at the current position as a [DateTime](../../system/datetime/) object. |
| virtual [DateTimeOffset](../../system/datetimeoffset/) [ReadContentAsDateTimeOffset](./readcontentasdatetimeoffset/)() | Reads the text content at the current position as a [DateTimeOffset](../../system/datetimeoffset/) object. |
| virtual [Decimal](../../system/decimal/) [ReadContentAsDecimal](./readcontentasdecimal/)() | Reads the text content at the current position as a [Decimal](../../system/decimal/) object. |
| virtual **double** [ReadContentAsDouble](./readcontentasdouble/)() | Reads the text content at the current position as a double-precision floating-point number. |
| virtual **float** [ReadContentAsFloat](./readcontentasfloat/)() | Reads the text content at the current position as a single-precision floating point number. |
| virtual **int32_t** [ReadContentAsInt](./readcontentasint/)() | Reads the text content at the current position as a 32-bit signed integer. |
| virtual **int64_t** [ReadContentAsLong](./readcontentaslong/)() | Reads the text content at the current position as a 64-bit signed integer. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAsObject](./readcontentasobject/)() | Reads the text content at the current position as an [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadContentAsString](./readcontentasstring/)() | Reads the text content at the current position as a [String](../../system/string/) object. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](./readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Reads the element content as the requested type. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](./readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | Checks that the specified local name and namespace URI matches that of the current element, then reads the element content as the requested type. |
| virtual **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | Reads the element and decodes the **Base64** content. |
| virtual **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | Reads the element and decodes the **BinHex** content. |
| virtual **bool** [ReadElementContentAsBoolean](./readelementcontentasboolean/)() | Reads the current element and returns the contents as a [Boolean](../../system/boolean/) object. |
| virtual **bool** [ReadElementContentAsBoolean](./readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | Checks that the specified local name and namespace URI matches that of the current element, then reads the current element and returns the contents as a [Boolean](../../system/boolean/) object. |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](./readelementcontentasdatetime/)() | Reads the current element and returns the contents as a [DateTime](../../system/datetime/) object. |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](./readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | Checks that the specified local name and namespace URI matches that of the current element, then reads the current element and returns the contents as a [DateTime](../../system/datetime/) object. |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](./readelementcontentasdecimal/)() | Reads the current element and returns the contents as a [Decimal](../../system/decimal/) object. |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](./readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | Checks that the specified local name and namespace URI matches that of the current element, then reads the current element and returns the contents as a [Decimal](../../system/decimal/) object. |
| virtual **double** [ReadElementContentAsDouble](./readelementcontentasdouble/)() | Reads the current element and returns the contents as a double-precision floating-point number. |
| virtual **double** [ReadElementContentAsDouble](./readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | Checks that the specified local name and namespace URI matches that of the current element, then reads the current element and returns the contents as a double-precision floating-point number. |
| virtual **float** [ReadElementContentAsFloat](./readelementcontentasfloat/)() | Reads the current element and returns the contents as single-precision floating-point number. |
| virtual **float** [ReadElementContentAsFloat](./readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | Checks that the specified local name and namespace URI matches that of the current element, then reads the current element and returns the contents as a single-precision floating-point number. |
| virtual **int32_t** [ReadElementContentAsInt](./readelementcontentasint/)() | Reads the current element and returns the contents as a 32-bit signed integer. |
| virtual **int32_t** [ReadElementContentAsInt](./readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | Checks that the specified local name and namespace URI matches that of the current element, then reads the current element and returns the contents as a 32-bit signed integer. |
| virtual **int64_t** [ReadElementContentAsLong](./readelementcontentaslong/)() | Reads the current element and returns the contents as a 64-bit signed integer. |
| virtual **int64_t** [ReadElementContentAsLong](./readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | Checks that the specified local name and namespace URI matches that of the current element, then reads the current element and returns the contents as a 64-bit signed integer. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](./readelementcontentasobject/)() | Reads the current element and returns the contents as an [Object](../../system/object/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](./readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | Checks that the specified local name and namespace URI matches that of the current element, then reads the current element and returns the contents as an [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](./readelementcontentasstring/)() | Reads the current element and returns the contents as a [String](../../system/string/) object. |
| virtual [String](../../system/string/) [ReadElementContentAsString](./readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | Checks that the specified local name and namespace URI matches that of the current element, then reads the current element and returns the contents as a [String](../../system/string/) object. |
| virtual [String](../../system/string/) [ReadElementString](./readelementstring/)() | Reads a text-only element. However, it is recommended to use the [XmlReader::ReadElementContentAsString](./readelementcontentasstring/) method instead, because it provides a more straightforward way to handle this operation. |
| virtual [String](../../system/string/) [ReadElementString](./readelementstring/)([String](../../system/string/)) | Checks that the [XmlReader::get_Name](./get_name/) value of the element found matches the given string before reading a text-only element. However, it is recommended to use the [XmlReader::ReadElementContentAsString](./readelementcontentasstring/) method instead, because it provides a more straightforward way to handle this operation. |
| virtual [String](../../system/string/) [ReadElementString](./readelementstring/)([String](../../system/string/), [String](../../system/string/)) | Checks that the [XmlReader::get_LocalName](./get_localname/) and [XmlReader::get_NamespaceURI](./get_namespaceuri/) values of the element found matches the given strings before reading a text-only element. However, it is recommended to use the [XmlReader::ReadElementContentAsString](./readelementcontentasstring/) method instead, because it provides a more straightforward way to handle this operation. |
| virtual void [ReadEndElement](./readendelement/)() | Checks that the current content node is an end tag and advances the reader to the next node. |
| virtual [String](../../system/string/) [ReadInnerXml](./readinnerxml/)() | When overridden in a derived class, reads all the content, including markup, as a string. |
| virtual [String](../../system/string/) [ReadOuterXml](./readouterxml/)() | When overridden in a derived class, reads the content, including markup, representing this node and all its children. |
| virtual void [ReadStartElement](./readstartelement/)() | Checks that the current node is an element and advances the reader to the next node. |
| virtual void [ReadStartElement](./readstartelement/)([String](../../system/string/)) | Checks that the current content node is an element with the given [XmlReader::get_Name](./get_name/) value and advances the reader to the next node. |
| virtual void [ReadStartElement](./readstartelement/)([String](../../system/string/), [String](../../system/string/)) | Checks that the current content node is an element with the given [XmlReader::get_LocalName](./get_localname/) and [XmlReader::get_NamespaceURI](./get_namespaceuri/) values and advances the reader to the next node. |
| virtual [String](../../system/string/) [ReadString](./readstring/)() | When overridden in a derived class, reads the contents of an element or text node as a string. However, it is recommended to use the [XmlReader::ReadElementContentAsString](./readelementcontentasstring/) method instead, because it provides a more straightforward way to handle this operation. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [ReadSubtree](./readsubtree/)() | Returns a new [XmlReader](./) instance that can be used to read the current node, and all its descendants. |
| virtual **bool** [ReadToDescendant](./readtodescendant/)([String](../../system/string/)) | Advances the [XmlReader](./) to the next descendant element with the specified qualified name. |
| virtual **bool** [ReadToDescendant](./readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | Advances the [XmlReader](./) to the next descendant element with the specified local name and namespace URI. |
| virtual **bool** [ReadToFollowing](./readtofollowing/)([String](../../system/string/)) | Reads until an element with the specified qualified name is found. |
| virtual **bool** [ReadToFollowing](./readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | Reads until an element with the specified local name and namespace URI is found. |
| virtual **bool** [ReadToNextSibling](./readtonextsibling/)([String](../../system/string/)) | Advances the [XmlReader](./) to the next sibling element with the specified qualified name. |
| virtual **bool** [ReadToNextSibling](./readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | Advances the [XmlReader](./) to the next sibling element with the specified local name and namespace URI. |
| virtual **int32_t** [ReadValueChunk](./readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Reads large streams of text embedded in an XML document. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Reference-compares value type object with nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of string and nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decreases shared reference count by specified value. |
| virtual void [ResolveEntity](./resolveentity/)() | When overridden in a derived class, resolves the entity reference for **EntityReference** nodes. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gets current value of shared reference counter. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Increments shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrements and returns shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual void [Skip](./skip/)() | Skips the children of the current node. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implements C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroys object. Frees all internal data structures. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## See Also

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Xml](../)
* Library [Aspose.Slides](../../)
