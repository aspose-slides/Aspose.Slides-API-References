---
title: XmlValidatingReader
second_title: Aspose.Slides for C++ API Reference
description: Represents a reader that provides document type definition (DTD), XML-Data Reduced (XDR) schema, and XML Schema definition language (XSD) validation.
type: docs
weight: 547
url: /cpp/system.xml/xmlvalidatingreader/
---
## XmlValidatingReader class


Represents a reader that provides document type definition (DTD), XML-Data Reduced (XDR) schema, and XML [Schema](../../system.xml.schema/) definition language (XSD) validation.

```cpp
class XmlValidatingReader : public System::Xml::XmlReader,
                            public System::Xml::IXmlLineInfo,
                            public System::Xml::IXmlNamespaceResolver
```

## Methods

| Method | Description |
| --- | --- |
| void [Close](./close/)() override | Changes the [XmlReader::get_ReadState](../xmlreader/get_readstate/) to Closed. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&) | Creates a new [XmlReader](../xmlreader/) instance with specified URI. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Creates a new [XmlReader](../xmlreader/) instance by using the specified URI and settings. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Creates a new [XmlReader](../xmlreader/) instance by using the specified URI, settings, and context information for parsing. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Creates a new [XmlReader](../xmlreader/) instance using the specified stream with default settings. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Creates a new [XmlReader](../xmlreader/) instance with the specified stream and settings. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Creates a new [XmlReader](../xmlreader/) instance using the specified stream, base URI, and settings. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Creates a new [XmlReader](../xmlreader/) instance using the specified stream, settings, and context information for parsing. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | Creates a new [XmlReader](../xmlreader/) instance by using the specified text reader. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Creates a new [XmlReader](../xmlreader/) instance by using the specified text reader and settings. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Creates a new [XmlReader](../xmlreader/) instance by using the specified text reader, settings, and base URI. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Creates a new [XmlReader](../xmlreader/) instance by using the specified text reader, settings, and context information for parsing. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | Creates a new [XmlReader](../xmlreader/) instance by using the specified XML reader and settings. |
| void [Dispose](../xmlreader/dispose/)() override | Releases all resources used by the current instance of the [XmlReader](../xmlreader/) class. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares value type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| **int32_t** [get_AttributeCount](./get_attributecount/)() override | Returns the number of attributes on the current node. |
| [String](../../system/string/) [get_BaseURI](./get_baseuri/)() override | Returns the base URI of the current node. |
| **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() override | Returns a value indicating whether the [XmlValidatingReader](./) implements the binary content read methods. |
| virtual **bool** [get_CanReadValueChunk](../xmlreader/get_canreadvaluechunk/)() | Returns a value indicating whether the [XmlReader](../xmlreader/) implements the [XmlReader::ReadValueChunk](../xmlreader/readvaluechunk/) method. |
| **bool** [get_CanResolveEntity](./get_canresolveentity/)() override | Returns a value indicating whether this reader can parse and resolve entities. |
| **int32_t** [get_Depth](./get_depth/)() override | Returns the depth of the current node in the XML document. |
| [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | Returns the encoding attribute for the document. |
| [System::Xml::EntityHandling](../entityhandling/) [get_EntityHandling](./get_entityhandling/)() | Returns a value that specifies how the reader handles entities. |
| **bool** [get_EOF](./get_eof/)() override | Returns a value indicating whether the reader is positioned at the end of the stream. |
| virtual **bool** [get_HasAttributes](../xmlreader/get_hasattributes/)() | Returns a value indicating whether the current node has any attributes. |
| **bool** [get_HasValue](./get_hasvalue/)() override | Returns a value indicating whether the current node can have a [XmlValidatingReader::get_Value](./get_value/) other than [String::Empty](../../system/string/empty/). |
| **bool** [get_IsDefault](./get_isdefault/)() override | Returns a value indicating whether the current node is an attribute that was generated from the default value defined in the document type definition (DTD) or schema. |
| **bool** [get_IsEmptyElement](./get_isemptyelement/)() override | Returns a value indicating whether the current node is an empty element (for example, **<MyElement/>**). |
| **int32_t** [get_LineNumber](./get_linenumber/)() override | Returns the current line number. |
| **int32_t** [get_LinePosition](./get_lineposition/)() override | Returns the current line position. |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | Returns the local name of the current node. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Returns the qualified name of the current node. |
| **bool** [get_Namespaces](./get_namespaces/)() | Returns a value indicating whether to do namespace support. |
| [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() override | Returns the namespace Uniform Resource Identifier (URI) (as defined in the World Wide [Web](../../system.web/) Consortium (W3C) Namespace specification) of the node on which the reader is positioned. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() override | Returns the [XmlNameTable](../xmlnametable/) associated with this implementation. |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | Returns the type of the current node. |
| [String](../../system/string/) [get_Prefix](./get_prefix/)() override | Returns the namespace prefix associated with the current node. |
| char16_t [get_QuoteChar](./get_quotechar/)() override | Returns the quotation mark character used to enclose the value of an attribute node. |
| [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [get_Reader](./get_reader/)() | Returns the [XmlReader](../xmlreader/) used to construct this [XmlValidatingReader](./). |
| [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() override | Returns the state of the reader. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](../xmlreader/get_schemainfo/)() | Returns the schema information that has been assigned to the current node as a result of schema validation. |
| [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaCollection](../../system.xml.schema/xmlschemacollection/)\> [get_Schemas](./get_schemas/)() | Returns a XmlSchemaCollection to use for validation. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SchemaType](./get_schematype/)() | Returns a schema type object. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](../xmlreader/get_settings/)() | Returns the [XmlReaderSettings](../xmlreadersettings/) object used to create this [XmlReader](../xmlreader/) instance. |
| [System::Xml::ValidationType](../validationtype/) [get_ValidationType](./get_validationtype/)() | Returns a value indicating the type of validation to perform. |
| [String](../../system/string/) [get_Value](./get_value/)() override | Returns the text value of the current node. |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](../xmlreader/get_valuetype/)() | Returns The type for the current node. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | Returns the current **xml:lang** scope. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | Returns the current **xml:space** scope. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) override | Returns the value of the attribute with the specified name. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) override | Returns the value of the attribute with the specified local name and namespace Uniform Resource Identifier (URI). |
| [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) override | Returns the value of the attribute with the specified index. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gets actual type of object. Analog of C# [System.Object.GetType()](../../system/object/gettype/) call. |
| **bool** [HasLineInfo](./haslineinfo/)() override | Returns a value indicating whether the class can return line information. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)(**int32_t**) | When overridden in a derived class, gets the value of the attribute with the specified index. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/)) | When overridden in a derived class, gets the value of the attribute with the specified [XmlReader::get_Name](../xmlreader/get_name/) value. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/), [String](../../system/string/)) | When overridden in a derived class, gets the value of the attribute with the specified [XmlReader::get_LocalName](../xmlreader/get_localname/) and [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) values. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Check if object represents an instance of type described by targetType. Analog of C# 'is' operator. |
| static **bool** [IsName](../xmlreader/isname/)(const [String](../../system/string/)\&) | Returns a value indicating whether the string argument is a valid XML name. |
| static **bool** [IsNameToken](../xmlreader/isnametoken/)(const [String](../../system/string/)\&) | Returns a value indicating whether or not the string argument is a valid XML name token. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)() | Calls [XmlReader::MoveToContent](../xmlreader/movetocontent/) and tests if the current content node is a start tag or empty element tag. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/)) | Calls [XmlReader::MoveToContent](../xmlreader/movetocontent/) and tests if the current content node is a start tag or empty element tag and if the [XmlReader::get_Name](../xmlreader/get_name/) value of the element found matches the given argument. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/), [String](../../system/string/)) | Calls [XmlReader::MoveToContent](../xmlreader/movetocontent/) and tests if the current content node is a start tag or empty element tag and if the [XmlReader::get_LocalName](../xmlreader/get_localname/) and [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) values of the element found match the given strings. |
| void [Lock](../../system/object/lock/)() | Implements C# lock() statement locking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | Resolves a namespace prefix in the current element's scope. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog of C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) method. Enables cloning custom types. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) override | Moves to the attribute with the specified name. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) override | Moves to the attribute with the specified local name and namespace Uniform Resource Identifier (URI). |
| void [MoveToAttribute](./movetoattribute/)(**int32_t**) override | Moves to the attribute with the specified index. |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](../xmlreader/movetocontent/)() | Checks whether the current node is a content (non-white space text, **CDATA**, **Element**, **EndElement**, **EntityReference**, or **EndEntity**) node. If the node is not a content node, the reader skips ahead to the next content node or end of file. It skips over nodes of the following type: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace**, or **SignificantWhitespace**. |
| **bool** [MoveToElement](./movetoelement/)() override | Moves to the element that contains the current attribute node. |
| **bool** [MoveToFirstAttribute](./movetofirstattribute/)() override | Moves to the first attribute. |
| **bool** [MoveToNextAttribute](./movetonextattribute/)() override | Moves to the next attribute. |
|  [Object](../../system/object/object/)() | Creates object. Initializes all internal data structures. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy constructor. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Assignment operator. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| **bool** [Read](./read/)() override | Reads the next node from the stream. |
| **bool** [ReadAttributeValue](./readattributevalue/)() override | Parses the attribute value into one or more **[Text](../../system.text/)**, **EntityReference**, or **EndEntity** nodes. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](../xmlreader/readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Reads the content as an object of the type specified. |
| **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Reads the content and returns the Base64 decoded binary bytes. |
| **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Reads the content and returns the BinHex decoded binary bytes. |
| virtual **bool** [ReadContentAsBoolean](../xmlreader/readcontentasboolean/)() | Reads the text content at the current position as a [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadContentAsDateTime](../xmlreader/readcontentasdatetime/)() | Reads the text content at the current position as a [DateTime](../../system/datetime/) object. |
| virtual [DateTimeOffset](../../system/datetimeoffset/) [ReadContentAsDateTimeOffset](../xmlreader/readcontentasdatetimeoffset/)() | Reads the text content at the current position as a [DateTimeOffset](../../system/datetimeoffset/) object. |
| virtual [Decimal](../../system/decimal/) [ReadContentAsDecimal](../xmlreader/readcontentasdecimal/)() | Reads the text content at the current position as a [Decimal](../../system/decimal/) object. |
| virtual **double** [ReadContentAsDouble](../xmlreader/readcontentasdouble/)() | Reads the text content at the current position as a double-precision floating-point number. |
| virtual **float** [ReadContentAsFloat](../xmlreader/readcontentasfloat/)() | Reads the text content at the current position as a single-precision floating point number. |
| virtual **int32_t** [ReadContentAsInt](../xmlreader/readcontentasint/)() | Reads the text content at the current position as a 32-bit signed integer. |
| virtual **int64_t** [ReadContentAsLong](../xmlreader/readcontentaslong/)() | Reads the text content at the current position as a 64-bit signed integer. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAsObject](../xmlreader/readcontentasobject/)() | Reads the text content at the current position as an [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadContentAsString](../xmlreader/readcontentasstring/)() | Reads the text content at the current position as a [String](../../system/string/) object. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Reads the element content as the requested type. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | Checks that the specified local name and namespace URI matches that of the current element, then reads the element content as the requested type. |
| **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Reads the element and decodes the Base64 content. |
| **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Reads the element and decodes the BinHex content. |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)() | Reads the current element and returns the contents as a [Boolean](../../system/boolean/) object. |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | Checks that the specified local name and namespace URI matches that of the current element, then reads the current element and returns the contents as a [Boolean](../../system/boolean/) object. |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)() | Reads the current element and returns the contents as a [DateTime](../../system/datetime/) object. |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | Checks that the specified local name and namespace URI matches that of the current element, then reads the current element and returns the contents as a [DateTime](../../system/datetime/) object. |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)() | Reads the current element and returns the contents as a [Decimal](../../system/decimal/) object. |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | Checks that the specified local name and namespace URI matches that of the current element, then reads the current element and returns the contents as a [Decimal](../../system/decimal/) object. |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)() | Reads the current element and returns the contents as a double-precision floating-point number. |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | Checks that the specified local name and namespace URI matches that of the current element, then reads the current element and returns the contents as a double-precision floating-point number. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)() | Reads the current element and returns the contents as single-precision floating-point number. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | Checks that the specified local name and namespace URI matches that of the current element, then reads the current element and returns the contents as a single-precision floating-point number. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)() | Reads the current element and returns the contents as a 32-bit signed integer. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | Checks that the specified local name and namespace URI matches that of the current element, then reads the current element and returns the contents as a 32-bit signed integer. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)() | Reads the current element and returns the contents as a 64-bit signed integer. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | Checks that the specified local name and namespace URI matches that of the current element, then reads the current element and returns the contents as a 64-bit signed integer. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)() | Reads the current element and returns the contents as an [Object](../../system/object/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | Checks that the specified local name and namespace URI matches that of the current element, then reads the current element and returns the contents as an [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)() | Reads the current element and returns the contents as a [String](../../system/string/) object. |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | Checks that the specified local name and namespace URI matches that of the current element, then reads the current element and returns the contents as a [String](../../system/string/) object. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)() | Reads a text-only element. However, it is recommended to use the [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) method instead, because it provides a more straightforward way to handle this operation. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/)) | Checks that the [XmlReader::get_Name](../xmlreader/get_name/) value of the element found matches the given string before reading a text-only element. However, it is recommended to use the [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) method instead, because it provides a more straightforward way to handle this operation. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/), [String](../../system/string/)) | Checks that the [XmlReader::get_LocalName](../xmlreader/get_localname/) and [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) values of the element found matches the given strings before reading a text-only element. However, it is recommended to use the [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) method instead, because it provides a more straightforward way to handle this operation. |
| virtual void [ReadEndElement](../xmlreader/readendelement/)() | Checks that the current content node is an end tag and advances the reader to the next node. |
| virtual [String](../../system/string/) [ReadInnerXml](../xmlreader/readinnerxml/)() | When overridden in a derived class, reads all the content, including markup, as a string. |
| virtual [String](../../system/string/) [ReadOuterXml](../xmlreader/readouterxml/)() | When overridden in a derived class, reads the content, including markup, representing this node and all its children. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)() | Checks that the current node is an element and advances the reader to the next node. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/)) | Checks that the current content node is an element with the given [XmlReader::get_Name](../xmlreader/get_name/) value and advances the reader to the next node. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/), [String](../../system/string/)) | Checks that the current content node is an element with the given [XmlReader::get_LocalName](../xmlreader/get_localname/) and [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) values and advances the reader to the next node. |
| [String](../../system/string/) [ReadString](./readstring/)() override | Reads the contents of an element or text node as a string. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [ReadSubtree](../xmlreader/readsubtree/)() | Returns a new [XmlReader](../xmlreader/) instance that can be used to read the current node, and all its descendants. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/)) | Advances the [XmlReader](../xmlreader/) to the next descendant element with the specified qualified name. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | Advances the [XmlReader](../xmlreader/) to the next descendant element with the specified local name and namespace URI. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/)) | Reads until an element with the specified qualified name is found. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | Reads until an element with the specified local name and namespace URI is found. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/)) | Advances the [XmlReader](../xmlreader/) to the next sibling element with the specified qualified name. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | Advances the [XmlReader](../xmlreader/) to the next sibling element with the specified local name and namespace URI. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadTypedValue](./readtypedvalue/)() | Returns the runt-ime type for the specified XML [Schema](../../system.xml.schema/) definition language (XSD) type. |
| virtual **int32_t** [ReadValueChunk](../xmlreader/readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Reads large streams of text embedded in an XML document. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Reference-compares value type object with nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of string and nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decreases shared reference count by specified value. |
| void [ResolveEntity](./resolveentity/)() override | Resolves the entity reference for **EntityReference** nodes. |
| void [set_EntityHandling](./set_entityhandling/)([System::Xml::EntityHandling](../entityhandling/)) | Sets a value that specifies how the reader handles entities. |
| void [set_Namespaces](./set_namespaces/)(**bool**) | Sets a value indicating whether to do namespace support. |
| void [set_ValidationType](./set_validationtype/)([System::Xml::ValidationType](../validationtype/)) | Sets a value indicating the type of validation to perform. |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../xmlresolver/)\>\&) | Sets the [XmlResolver](../xmlresolver/) used for resolving external document type definition (DTD) and schema location references. The [XmlResolver](../xmlresolver/) is also used to handle any import or include elements found in XML [Schema](../../system.xml.schema/) definition language (XSD) schemas. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gets current value of shared reference counter. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Increments shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrements and returns shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual void [Skip](../xmlreader/skip/)() | Skips the children of the current node. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implements C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| void [ValidationEventHandler_add](./validationeventhandler_add/)(Args...) | Adds an event handler for receiving information about document type definition (DTD), XML-Data Reduced (XDR) schema, and XML [Schema](../../system.xml.schema/) definition language (XSD) schema validation errors. |
| void [ValidationEventHandler_remove](./validationeventhandler_remove/)(Args...) | Removes an event handler for receiving information about document type definition (DTD), XML-Data Reduced (XDR) schema, and XML [Schema](../../system.xml.schema/) definition language (XSD) schema validation errors. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
|  [XmlValidatingReader](./xmlvalidatingreader/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&) | Initializes a new instance of the [XmlValidatingReader](./) class that validates the content returned from the given [XmlReader](../xmlreader/). |
|  [XmlValidatingReader](./xmlvalidatingreader/)(const [String](../../system/string/)\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Initializes a new instance of the [XmlValidatingReader](./) class with the specified values. |
|  [XmlValidatingReader](./xmlvalidatingreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Initializes a new instance of the [XmlValidatingReader](./) class with the specified values. |
| virtual  [~Object](../../system/object/~object/)() | Destroys object. Frees all internal data structures. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## Remarks


Deprecated
:   This class is obsolete. It is recommended to use the [XmlReaderSettings](../xmlreadersettings/) class and the [XmlReader::Create](../xmlreader/create/) method to create a validating XML reader.

Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## See Also

* Class [XmlReader](../xmlreader/)
* Class [IXmlLineInfo](../ixmllineinfo/)
* Class [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* Namespace [System::Xml](../)
* Library [Aspose.Slides](../../)