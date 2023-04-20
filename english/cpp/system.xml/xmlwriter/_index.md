---
title: XmlWriter
second_title: Aspose.Slides for C++ API Reference
description: Represents a writer that provides a fast, non-cached, forward-only way to generate streams or files that contain XML data.
type: docs
weight: 573
url: /cpp/system.xml/xmlwriter/
---
## XmlWriter class


Represents a writer that provides a fast, non-cached, forward-only way to generate streams or files that contain XML data.

```cpp
class XmlWriter : public System::IDisposable
```

## Methods

| Method | Description |
| --- | --- |
| virtual void [Close](./close/)() | When overridden in a derived class, closes this stream and the underlying stream. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [String](../../system/string/)\&) | Creates a new [XmlWriter](./) instance using the specified filename. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Creates a new [XmlWriter](./) instance using the filename and [XmlWriterSettings](../xmlwritersettings/) object. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Creates a new [XmlWriter](./) instance using the specified stream. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Creates a new [XmlWriter](./) instance using the stream and [XmlWriterSettings](../xmlwritersettings/) object. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | Creates a new [XmlWriter](./) instance using the specified TextWriter. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Creates a new [XmlWriter](./) instance using the TextWriter and [XmlWriterSettings](../xmlwritersettings/) objects. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | Creates a new [XmlWriter](./) instance using the specified [Text::StringBuilder](../../system.text/stringbuilder/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Creates a new [XmlWriter](./) instance using the [Text::StringBuilder](../../system.text/stringbuilder/) and [XmlWriterSettings](../xmlwritersettings/) objects. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\>\&) | Creates a new [XmlWriter](./) instance using the specified [XmlWriter](./) object. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Creates a new [XmlWriter](./) instance using the specified [XmlWriter](./) and [XmlWriterSettings](../xmlwritersettings/) objects. |
| void [Dispose](./dispose/)() override | Releases all resources used by the current instance of the [XmlWriter](./) class. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares value type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| virtual void [Flush](./flush/)() | When overridden in a derived class, flushes whatever is in the buffer to the underlying streams and also flushes the underlying stream. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\> [get_Settings](./get_settings/)() | Returns the [XmlWriterSettings](../xmlwritersettings/) object used to create this [XmlWriter](./) instance. |
| virtual [System::Xml::WriteState](../writestate/) [get_WriteState](./get_writestate/)() | When overridden in a derived class, gets the state of the writer. |
| virtual [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | When overridden in a derived class, gets the current **xml:lang** scope. |
| virtual [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() | When overridden in a derived class, gets an XmlSpace representing the current **xml:space** scope. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gets actual type of object. Analog of C# [System.Object.GetType()](../../system/object/gettype/) call. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Check if object represents an instance of type described by targetType. Analog of C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implements C# lock() statement locking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| virtual [String](../../system/string/) [LookupPrefix](./lookupprefix/)([String](../../system/string/)) | When overridden in a derived class, returns the closest prefix defined in the current namespace scope for the namespace URI. |
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
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gets current value of shared reference counter. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Increments shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrements and returns shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implements C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual void [WriteAttributes](./writeattributes/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | When overridden in a derived class, writes out all the attributes found at the current position in the [XmlReader](../xmlreader/). |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | When overridden in a derived class, writes an attribute with the specified local name, namespace URI, and value. |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | When overridden in a derived class, writes out the attribute with the specified local name and value. |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | When overridden in a derived class, writes out the attribute with the specified prefix, local name, namespace URI, and value. |
| virtual void [WriteBase64](./writebase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | When overridden in a derived class, encodes the specified binary bytes as Base64 and writes out the resulting text. |
| virtual void [WriteBinHex](./writebinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | When overridden in a derived class, encodes the specified binary bytes as **BinHex** and writes out the resulting text. |
| virtual void [WriteCData](./writecdata/)([String](../../system/string/)) | When overridden in a derived class, writes out a **...** block containing the specified text. |
| virtual void [WriteCharEntity](./writecharentity/)(char16_t) | When overridden in a derived class, forces the generation of a character entity for the specified Unicode character value. |
| virtual void [WriteChars](./writechars/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | When overridden in a derived class, writes text one buffer at a time. |
| virtual void [WriteComment](./writecomment/)([String](../../system/string/)) | When overridden in a derived class, writes out a comment **** containing the specified text. |
| virtual void [WriteDocType](./writedoctype/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | When overridden in a derived class, writes the DOCTYPE declaration with the specified name and optional attributes. |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Writes an element with the specified local name and value. |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Writes an element with the specified local name, namespace URI, and value. |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Writes an element with the specified prefix, local name, namespace URI, and value. |
| virtual void [WriteEndAttribute](./writeendattribute/)() | When overridden in a derived class, closes the previous XmlWriter::WriteStartAttribute(String,String) call. |
| virtual void [WriteEndDocument](./writeenddocument/)() | When overridden in a derived class, closes any open elements or attributes and puts the writer back in the Start state. |
| virtual void [WriteEndElement](./writeendelement/)() | When overridden in a derived class, closes one element and pops the corresponding namespace scope. |
| virtual void [WriteEntityRef](./writeentityref/)(const [String](../../system/string/)\&) | When overridden in a derived class, writes out an entity reference as **&name**;. |
| virtual void [WriteFullEndElement](./writefullendelement/)() | When overridden in a derived class, closes one element and pops the corresponding namespace scope. |
| virtual void [WriteName](./writename/)(const [String](../../system/string/)\&) | When overridden in a derived class, writes out the specified name, ensuring it is a valid name according to the W3C XML 1.0 recommendation ([https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name)). |
| virtual void [WriteNmToken](./writenmtoken/)(const [String](../../system/string/)\&) | When overridden in a derived class, writes out the specified name, ensuring it is a valid NmToken according to the W3C XML 1.0 recommendation ([https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name)). |
| virtual void [WriteNode](./writenode/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | When overridden in a derived class, copies everything from the reader to the writer and moves the reader to the start of the next sibling. |
| virtual void [WriteNode](./writenode/)([SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>, **bool**) | Copies everything from the XPathNavigator object to the writer. The position of the XPathNavigator remains unchanged. |
| virtual void [WriteProcessingInstruction](./writeprocessinginstruction/)([String](../../system/string/), [String](../../system/string/)) | When overridden in a derived class, writes out a processing instruction with a space between the name and text as follows: **<?name text?>**. |
| virtual void [WriteQualifiedName](./writequalifiedname/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | When overridden in a derived class, writes out the namespace-qualified name. This method looks up the prefix that is in scope for the given namespace. |
| virtual void [WriteRaw](./writeraw/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | When overridden in a derived class, writes raw markup manually from a character buffer. |
| virtual void [WriteRaw](./writeraw/)(const [String](../../system/string/)\&) | When overridden in a derived class, writes raw markup manually from a string. |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Writes the start of an attribute with the specified local name and namespace URI. |
| virtual void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | When overridden in a derived class, writes the start of an attribute with the specified prefix, local name, and namespace URI. |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&) | Writes the start of an attribute with the specified local name. |
| virtual void [WriteStartDocument](./writestartdocument/)() | When overridden in a derived class, writes the XML declaration with the version \"1.0\". |
| virtual void [WriteStartDocument](./writestartdocument/)(**bool**) | When overridden in a derived class, writes the XML declaration with the version \"1.0\" and the standalone attribute. |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | When overridden in a derived class, writes the specified start tag and associates it with the given namespace. |
| virtual void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | When overridden in a derived class, writes the specified start tag and associates it with the given namespace and prefix. |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&) | When overridden in a derived class, writes out a start tag with the specified local name. |
| virtual void [WriteString](./writestring/)(const [String](../../system/string/)\&) | When overridden in a derived class, writes the given text content. |
| virtual void [WriteSurrogateCharEntity](./writesurrogatecharentity/)(char16_t, char16_t) | When overridden in a derived class, generates and writes the surrogate character entity for the surrogate character pair. |
| virtual void [WriteValue](./writevalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Writes the object value. |
| virtual void [WriteValue](./writevalue/)(const [String](../../system/string/)\&) | Writes a [String](../../system/string/) value. |
| virtual void [WriteValue](./writevalue/)(**bool**) | Writes a [Boolean](../../system/boolean/) value. |
| virtual void [WriteValue](./writevalue/)([DateTime](../../system/datetime/)) | Writes a [DateTime](../../system/datetime/) value. |
| virtual void [WriteValue](./writevalue/)([DateTimeOffset](../../system/datetimeoffset/)) | Writes a [DateTimeOffset](../../system/datetimeoffset/) value. |
| virtual void [WriteValue](./writevalue/)(**double**) | Writes a [Double](../../system/double/) value. |
| virtual void [WriteValue](./writevalue/)(**float**) | Writes a single-precision floating-point number. |
| virtual void [WriteValue](./writevalue/)([Decimal](../../system/decimal/)) | Writes a [Decimal](../../system/decimal/) value. |
| virtual void [WriteValue](./writevalue/)(**int32_t**) | Writes a [Int32](../../system/int32/) value. |
| virtual void [WriteValue](./writevalue/)(**int64_t**) | Writes a [Int64](../../system/int64/) value. |
| virtual void [WriteWhitespace](./writewhitespace/)([String](../../system/string/)) | When overridden in a derived class, writes out the given white space. |
| virtual  [~Object](../../system/object/~object/)() | Destroys object. Frees all internal data structures. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## See Also

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Xml](../)
* Library [Aspose.Slides](../../)