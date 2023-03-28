---
title: XmlTextWriter
second_title: Aspose.Slides for C++ API Reference
description: Represents a writer that provides a fast, non-cached, forward-only way of generating streams or files containing XML data that conforms to the W3C Extensible Markup Language (XML) 1.0 and the Namespaces in XML recommendations.
type: docs
weight: 521
url: /cpp/system.xml/xmltextwriter/
---
## XmlTextWriter class


Represents a writer that provides a fast, non-cached, forward-only way of generating streams or files containing XML data that conforms to the W3C Extensible Markup Language (XML) 1.0 and the Namespaces in XML recommendations.

```cpp
class XmlTextWriter : public System::Xml::XmlWriter
```

## Methods

| Method | Description |
| --- | --- |
| void [Close](./close/)() override | Closes this stream and the underlying stream. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [String](../../system/string/)\&) | Creates a new [XmlWriter](../xmlwriter/) instance using the specified filename. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Creates a new [XmlWriter](../xmlwriter/) instance using the filename and [XmlWriterSettings](../xmlwritersettings/) object. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Creates a new [XmlWriter](../xmlwriter/) instance using the specified stream. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Creates a new [XmlWriter](../xmlwriter/) instance using the stream and [XmlWriterSettings](../xmlwritersettings/) object. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | Creates a new [XmlWriter](../xmlwriter/) instance using the specified TextWriter. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Creates a new [XmlWriter](../xmlwriter/) instance using the TextWriter and [XmlWriterSettings](../xmlwritersettings/) objects. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | Creates a new [XmlWriter](../xmlwriter/) instance using the specified [Text::StringBuilder](../../system.text/stringbuilder/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Creates a new [XmlWriter](../xmlwriter/) instance using the [Text::StringBuilder](../../system.text/stringbuilder/) and [XmlWriterSettings](../xmlwritersettings/) objects. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) | Creates a new [XmlWriter](../xmlwriter/) instance using the specified [XmlWriter](../xmlwriter/) object. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Creates a new [XmlWriter](../xmlwriter/) instance using the specified [XmlWriter](../xmlwriter/) and [XmlWriterSettings](../xmlwritersettings/) objects. |
| void [Dispose](../xmlwriter/dispose/)() override | Releases all resources used by the current instance of the [XmlWriter](../xmlwriter/) class. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares value type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| void [Flush](./flush/)() override | Flushes whatever is in the buffer to the underlying streams and also flushes the underlying stream. |
| [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\> [get_BaseStream](./get_basestream/)() | Returns the underlying stream object. |
| [System::Xml::Formatting](../formatting/) [get_Formatting](./get_formatting/)() | Indicates how the output is formatted. |
| **int32_t** [get_Indentation](./get_indentation/)() | Returns how many IndentChars to write for each level in the hierarchy when [XmlTextWriter::set_Formatting](./set_formatting/) is set to [Formatting::Indented](../formatting/). |
| char16_t [get_IndentChar](./get_indentchar/)() | Returns which character to use for indenting when [XmlTextWriter::set_Formatting](./set_formatting/) is set to [Formatting::Indented](../formatting/). |
| **bool** [get_Namespaces](./get_namespaces/)() | Returns a value indicating whether to do namespace support. |
| char16_t [get_QuoteChar](./get_quotechar/)() | Returns which character to use to quote attribute values. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\> [get_Settings](../xmlwriter/get_settings/)() | Returns the [XmlWriterSettings](../xmlwritersettings/) object used to create this [XmlWriter](../xmlwriter/) instance. |
| [System::Xml::WriteState](../writestate/) [get_WriteState](./get_writestate/)() override | Returns the state of the writer. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | Returns the current **xml:lang** scope. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | Returns an XmlSpace representing the current **xml:space** scope. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gets actual type of object. Analog of C# [System.Object.GetType()](../../system/object/gettype/) call. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Check if object represents an instance of type described by targetType. Analog of C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implements C# lock() statement locking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| [String](../../system/string/) [LookupPrefix](./lookupprefix/)([String](../../system/string/)) override | Returns the closest prefix defined in the current namespace scope for the namespace URI. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog of C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) method. Enables cloning custom types. |
|  [Object](../../system/object/object/)() | Creates object. Initializes all internal data structures. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy constructor. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Assignment operator. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Reference-compares value type object with nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of string and nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decreases shared reference count by specified value. |
| void [set_Formatting](./set_formatting/)([System::Xml::Formatting](../formatting/)) | Indicates how the output is formatted. |
| void [set_Indentation](./set_indentation/)(**int32_t**) | Sets how many IndentChars to write for each level in the hierarchy when [XmlTextWriter::set_Formatting](./set_formatting/) is set to [Formatting::Indented](../formatting/). |
| void [set_IndentChar](./set_indentchar/)(char16_t) | Sets which character to use for indenting when [XmlTextWriter::set_Formatting](./set_formatting/) is set to [Formatting::Indented](../formatting/). |
| void [set_Namespaces](./set_namespaces/)(**bool**) | Sets a value indicating whether to do namespace support. |
| void [set_QuoteChar](./set_quotechar/)(char16_t) | Sets which character to use to quote attribute values. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gets current value of shared reference counter. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Increments shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrements and returns shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implements C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual void [WriteAttributes](../xmlwriter/writeattributes/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | When overridden in a derived class, writes out all the attributes found at the current position in the [XmlReader](../xmlreader/). |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | When overridden in a derived class, writes an attribute with the specified local name, namespace URI, and value. |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | When overridden in a derived class, writes out the attribute with the specified local name and value. |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | When overridden in a derived class, writes out the attribute with the specified prefix, local name, namespace URI, and value. |
| void [WriteBase64](./writebase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Encodes the specified binary bytes as base64 and writes out the resulting text. |
| void [WriteBinHex](./writebinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Encodes the specified binary bytes as binhex and writes out the resulting text. |
| void [WriteCData](./writecdata/)([String](../../system/string/)) override | Writes out a **...** block containing the specified text. |
| void [WriteCharEntity](./writecharentity/)(char16_t) override | Forces the generation of a character entity for the specified Unicode character value. |
| void [WriteChars](./writechars/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) override | Writes text one buffer at a time. |
| void [WriteComment](./writecomment/)([String](../../system/string/)) override | Writes out a comment **** containing the specified text. |
| void [WriteDocType](./writedoctype/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | Writes the DOCTYPE declaration with the specified name and optional attributes. |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Writes an element with the specified local name and value. |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Writes an element with the specified local name, namespace URI, and value. |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Writes an element with the specified prefix, local name, namespace URI, and value. |
| void [WriteEndAttribute](./writeendattribute/)() override | Closes the previous [XmlTextWriter::WriteStartAttribute](./writestartattribute/) call. |
| void [WriteEndDocument](./writeenddocument/)() override | Closes any open elements or attributes and puts the writer back in the Start state. |
| void [WriteEndElement](./writeendelement/)() override | Closes one element and pops the corresponding namespace scope. |
| void [WriteEntityRef](./writeentityref/)(const [String](../../system/string/)\&) override | Writes out an entity reference as **&name**;. |
| void [WriteFullEndElement](./writefullendelement/)() override | Closes one element and pops the corresponding namespace scope. |
| void [WriteName](./writename/)(const [String](../../system/string/)\&) override | Writes out the specified name, ensuring it is a valid name according to the [W3C XML 1.0 recommendation](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name). |
| void [WriteNmToken](./writenmtoken/)(const [String](../../system/string/)\&) override | Writes out the specified name, ensuring it is a valid **NmToken** according to the [W3C XML 1.0 recommendation](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name). |
| virtual void [WriteNode](../xmlwriter/writenode/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | When overridden in a derived class, copies everything from the reader to the writer and moves the reader to the start of the next sibling. |
| virtual void [WriteNode](../xmlwriter/writenode/)([SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>, **bool**) | Copies everything from the XPathNavigator object to the writer. The position of the XPathNavigator remains unchanged. |
| void [WriteProcessingInstruction](./writeprocessinginstruction/)([String](../../system/string/), [String](../../system/string/)) override | Writes out a processing instruction with a space between the name and text as follows: **<?name text?>**. |
| void [WriteQualifiedName](./writequalifiedname/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | Writes out the namespace-qualified name. This method looks up the prefix that is in scope for the given namespace. |
| void [WriteRaw](./writeraw/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) override | Writes raw markup manually from a character buffer. |
| void [WriteRaw](./writeraw/)(const [String](../../system/string/)\&) override | Writes raw markup manually from a string. |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | Writes the start of an attribute. |
| void [WriteStartAttribute](../xmlwriter/writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Writes the start of an attribute with the specified local name and namespace URI. |
| void [WriteStartAttribute](../xmlwriter/writestartattribute/)(const [String](../../system/string/)\&) | Writes the start of an attribute with the specified local name. |
| void [WriteStartDocument](./writestartdocument/)() override | Writes the XML declaration with the version \"1.0\". |
| void [WriteStartDocument](./writestartdocument/)(**bool**) override | Writes the XML declaration with the version \"1.0\" and the standalone attribute. |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | Writes the specified start tag and associates it with the given namespace and prefix. |
| void [WriteStartElement](../xmlwriter/writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | When overridden in a derived class, writes the specified start tag and associates it with the given namespace. |
| void [WriteStartElement](../xmlwriter/writestartelement/)(const [String](../../system/string/)\&) | When overridden in a derived class, writes out a start tag with the specified local name. |
| void [WriteString](./writestring/)(const [String](../../system/string/)\&) override | Writes the given text content. |
| void [WriteSurrogateCharEntity](./writesurrogatecharentity/)(char16_t, char16_t) override | Generates and writes the surrogate character entity for the surrogate character pair. |
| virtual void [WriteValue](../xmlwriter/writevalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Writes the object value. |
| virtual void [WriteValue](../xmlwriter/writevalue/)(const [String](../../system/string/)\&) | Writes a [String](../../system/string/) value. |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**bool**) | Writes a [Boolean](../../system/boolean/) value. |
| virtual void [WriteValue](../xmlwriter/writevalue/)([DateTime](../../system/datetime/)) | Writes a [DateTime](../../system/datetime/) value. |
| virtual void [WriteValue](../xmlwriter/writevalue/)([DateTimeOffset](../../system/datetimeoffset/)) | Writes a [DateTimeOffset](../../system/datetimeoffset/) value. |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**double**) | Writes a [Double](../../system/double/) value. |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**float**) | Writes a single-precision floating-point number. |
| virtual void [WriteValue](../xmlwriter/writevalue/)([Decimal](../../system/decimal/)) | Writes a [Decimal](../../system/decimal/) value. |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**int32_t**) | Writes a [Int32](../../system/int32/) value. |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**int64_t**) | Writes a [Int64](../../system/int64/) value. |
| void [WriteWhitespace](./writewhitespace/)([String](../../system/string/)) override | Writes out the given white space. |
|  [XmlTextWriter](./xmltextwriter/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | Creates an instance of the [XmlTextWriter](./) class using the specified stream and encoding. |
|  [XmlTextWriter](./xmltextwriter/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | Creates an instance of the [XmlTextWriter](./) class using the specified file. |
|  [XmlTextWriter](./xmltextwriter/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | Creates an instance of the [XmlTextWriter](./) class using the specified TextWriter. |
| virtual  [~Object](../../system/object/~object/)() | Destroys object. Frees all internal data structures. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## Remarks



It is recommended to use the [XmlWriter](../xmlwriter/) class instead. 

Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## See Also

* Class [XmlWriter](../xmlwriter/)
* Namespace [System::Xml](../)
* Library [Aspose.Slides](../../)
