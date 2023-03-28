---
title: XmlWriterSettings
second_title: Aspose.Slides for C++ API Reference
description: "Specifies a set of features to support on the XmlWriter object created by the XmlWriter::Create method."
type: docs
weight: 586
url: /cpp/system.xml/xmlwritersettings/
---
## XmlWriterSettings class


Specifies a set of features to support on the [XmlWriter](../xmlwriter/) object created by the [XmlWriter::Create](../xmlwriter/create/) method.

```cpp
class XmlWriterSettings : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](./)\> [Clone](./clone/)() | Creates a copy of the [XmlWriterSettings](./) instance. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares value type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| **bool** [get_CheckCharacters](./get_checkcharacters/)() | Returns a value that indicates whether the XML writer should check to ensure that all characters in the document conform to the \"2.2 Characters\" section of the W3C [XML 1.0 Recommendation](https://www.w3.org/TR/REC-xml/#charsets). |
| **bool** [get_CloseOutput](./get_closeoutput/)() | Returns a value indicating whether the [XmlWriter](../xmlwriter/) should also close the underlying stream or TextWriter when the [XmlWriter::Close](../xmlwriter/close/) method is called. |
| [System::Xml::ConformanceLevel](../conformancelevel/) [get_ConformanceLevel](./get_conformancelevel/)() | Returns the level of conformance that the XML writer checks the XML output for. |
| **bool** [get_DoNotEscapeUriAttributes](./get_donotescapeuriattributes/)() | Returns a value that indicates whether the [XmlWriter](../xmlwriter/) does not escape URI attributes. |
| [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | Returns the type of text encoding to use. |
| **bool** [get_Indent](./get_indent/)() | Returns a value indicating whether to indent elements. |
| [String](../../system/string/) [get_IndentChars](./get_indentchars/)() | Returns the character string to use when indenting. This setting is used when the [XmlWriterSettings::set_Indent](./set_indent/) value is set to **true**. |
| [System::Xml::NamespaceHandling](../namespacehandling/) [get_NamespaceHandling](./get_namespacehandling/)() | Returns a value that indicates whether the [XmlWriter](../xmlwriter/) should remove duplicate namespace declarations when writing XML content. The default behavior is for the writer to output all namespace declarations that are present in the writer's namespace resolver. |
| [String](../../system/string/) [get_NewLineChars](./get_newlinechars/)() | Returns the character string to use for line breaks. |
| [System::Xml::NewLineHandling](../newlinehandling/) [get_NewLineHandling](./get_newlinehandling/)() | Returns a value indicating whether to normalize line breaks in the output. |
| **bool** [get_NewLineOnAttributes](./get_newlineonattributes/)() | Returns a value indicating whether to write attributes on a new line. |
| **bool** [get_OmitXmlDeclaration](./get_omitxmldeclaration/)() | Returns a value indicating whether to omit an XML declaration. |
| [XmlOutputMethod](../xmloutputmethod/) [get_OutputMethod](./get_outputmethod/)() | Returns the method used to serialize the [XmlWriter](../xmlwriter/) output. |
| **bool** [get_WriteEndDocumentOnClose](./get_writeenddocumentonclose/)() | Returns a value that indicates whether the [XmlWriter](../xmlwriter/) will add closing tags to all unclosed element tags when the [XmlWriter::Close](../xmlwriter/close/) method is called. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gets actual type of object. Analog of C# [System.Object.GetType()](../../system/object/gettype/) call. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Check if object represents an instance of type described by targetType. Analog of C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implements C# lock() statement locking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
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
| void [Reset](./reset/)() | Resets the members of the settings class to their default values. |
| void [set_CheckCharacters](./set_checkcharacters/)(**bool**) | Sets a value that indicates whether the XML writer should check to ensure that all characters in the document conform to the \"2.2 Characters\" section of the W3C [XML 1.0 Recommendation](https://www.w3.org/TR/REC-xml/#charsets). |
| void [set_CloseOutput](./set_closeoutput/)(**bool**) | Sets a value indicating whether the [XmlWriter](../xmlwriter/) should also close the underlying stream or TextWriter when the [XmlWriter::Close](../xmlwriter/close/) method is called. |
| void [set_ConformanceLevel](./set_conformancelevel/)([System::Xml::ConformanceLevel](../conformancelevel/)) | Sets the level of conformance that the XML writer checks the XML output for. |
| void [set_DoNotEscapeUriAttributes](./set_donotescapeuriattributes/)(**bool**) | Sets a value that indicates whether the [XmlWriter](../xmlwriter/) does not escape URI attributes. |
| void [set_Encoding](./set_encoding/)(const [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\>\&) | Sets the type of text encoding to use. |
| void [set_Indent](./set_indent/)(**bool**) | Sets a value indicating whether to indent elements. |
| void [set_IndentChars](./set_indentchars/)(const [String](../../system/string/)\&) | Sets the character string to use when indenting. This setting is used when the [XmlWriterSettings::set_Indent](./set_indent/) value is set to **true**. |
| void [set_NamespaceHandling](./set_namespacehandling/)([System::Xml::NamespaceHandling](../namespacehandling/)) | Sets a value that indicates whether the [XmlWriter](../xmlwriter/) should remove duplicate namespace declarations when writing XML content. The default behavior is for the writer to output all namespace declarations that are present in the writer's namespace resolver. |
| void [set_NewLineChars](./set_newlinechars/)(const [String](../../system/string/)\&) | Sets the character string to use for line breaks. |
| void [set_NewLineHandling](./set_newlinehandling/)([System::Xml::NewLineHandling](../newlinehandling/)) | Sets a value indicating whether to normalize line breaks in the output. |
| void [set_NewLineOnAttributes](./set_newlineonattributes/)(**bool**) | Sets a value indicating whether to write attributes on a new line. |
| void [set_OmitXmlDeclaration](./set_omitxmldeclaration/)(**bool**) | Sets a value indicating whether to omit an XML declaration. |
| void [set_WriteEndDocumentOnClose](./set_writeenddocumentonclose/)(**bool**) | Sets a value that indicates whether the [XmlWriter](../xmlwriter/) will add closing tags to all unclosed element tags when the [XmlWriter::Close](../xmlwriter/close/) method is called. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gets current value of shared reference counter. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Increments shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrements and returns shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implements C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
|  [XmlWriterSettings](./xmlwritersettings/)() | Initializes a new instance of the [XmlWriterSettings](./) class. |
| virtual  [~Object](../../system/object/~object/)() | Destroys object. Frees all internal data structures. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## Remarks



Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## See Also

* Class [Object](../../system/object/)
* Namespace [System::Xml](../)
* Library [Aspose.Slides](../../)
