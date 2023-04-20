---
title: XmlReaderSettings
second_title: Aspose.Slides for C++ API Reference
description: "Specifies a set of features to support on the XmlReader object created by the XmlReader::Create method."
type: docs
weight: 443
url: /cpp/system.xml/xmlreadersettings/
---
## XmlReaderSettings class


Specifies a set of features to support on the [XmlReader](../xmlreader/) object created by the [XmlReader::Create](../xmlreader/create/) method.

```cpp
class XmlReaderSettings : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| void [CheckReadOnly](./checkreadonly/)(const [String](../../system/string/)\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](./)\> [Clone](./clone/)() | Creates a copy of the [XmlReaderSettings](./) instance. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares value type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| **bool** [get_CheckCharacters](./get_checkcharacters/)() | Returns a value indicating whether to do character checking. |
| **bool** [get_CloseInput](./get_closeinput/)() | Returns a value indicating whether the underlying stream or TextReader should be closed when the reader is closed. |
| [System::Xml::ConformanceLevel](../conformancelevel/) [get_ConformanceLevel](./get_conformancelevel/)() | Returns the level of conformance which the [XmlReader](../xmlreader/) will comply. |
| [System::Xml::DtdProcessing](../dtdprocessing/) [get_DtdProcessing](./get_dtdprocessing/)() | Returns a value that determines the processing of DTDs. |
| **bool** [get_IgnoreComments](./get_ignorecomments/)() | Returns a value indicating whether to ignore comments. |
| **bool** [get_IgnoreProcessingInstructions](./get_ignoreprocessinginstructions/)() | Returns a value indicating whether to ignore processing instructions. |
| **bool** [get_IgnoreWhitespace](./get_ignorewhitespace/)() | Returns a value indicating whether to ignore insignificant white space. |
| **int32_t** [get_LineNumberOffset](./get_linenumberoffset/)() | Returns line number offset of the [XmlReader](../xmlreader/) object. |
| **int32_t** [get_LinePositionOffset](./get_linepositionoffset/)() | Returns line position offset of the [XmlReader](../xmlreader/) object. |
| **int64_t** [get_MaxCharactersFromEntities](./get_maxcharactersfromentities/)() | Returns a value indicating the maximum allowable number of characters in a document that result from expanding entities. |
| **int64_t** [get_MaxCharactersInDocument](./get_maxcharactersindocument/)() | Returns a value indicating the maximum allowable number of characters in an XML document. A zero (0) value means no limits on the size of the XML document. A non-zero value specifies the maximum size, in characters. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() | Returns the [XmlNameTable](../xmlnametable/) used for atomized string comparisons. |
| **bool** [get_ProhibitDtd](./get_prohibitdtd/)() | Returns a value indicating whether to prohibit document type definition (DTD) processing. |
| [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\> [get_Schemas](./get_schemas/)() | Returns the XmlSchemaSet to use when performing schema validation. |
| [Schema::XmlSchemaValidationFlags](../../system.xml.schema/xmlschemavalidationflags/) [get_ValidationFlags](./get_validationflags/)() | Returns a value indicating the schema validation settings. This setting applies to [XmlReader](../xmlreader/) objects that validate schemas ([XmlReaderSettings::get_ValidationType](./get_validationtype/) value is [ValidationType::Schema](../validationtype/)). |
| [System::Xml::ValidationType](../validationtype/) [get_ValidationType](./get_validationtype/)() | Returns a value indicating whether the [XmlReader](../xmlreader/) will perform validation or type assignment when reading. |
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
| void [set_CheckCharacters](./set_checkcharacters/)(**bool**) | Sets a value indicating whether to do character checking. |
| void [set_CloseInput](./set_closeinput/)(**bool**) | Sets a value indicating whether the underlying stream or TextReader should be closed when the reader is closed. |
| void [set_ConformanceLevel](./set_conformancelevel/)([System::Xml::ConformanceLevel](../conformancelevel/)) | Sets the level of conformance which the [XmlReader](../xmlreader/) will comply. |
| void [set_DtdProcessing](./set_dtdprocessing/)([System::Xml::DtdProcessing](../dtdprocessing/)) | Sets a value that determines the processing of DTDs. |
| void [set_IgnoreComments](./set_ignorecomments/)(**bool**) | Sets a value indicating whether to ignore comments. |
| void [set_IgnoreProcessingInstructions](./set_ignoreprocessinginstructions/)(**bool**) | Sets a value indicating whether to ignore processing instructions. |
| void [set_IgnoreWhitespace](./set_ignorewhitespace/)(**bool**) | Sets a value indicating whether to ignore insignificant white space. |
| void [set_LineNumberOffset](./set_linenumberoffset/)(**int32_t**) | Sets line number offset of the [XmlReader](../xmlreader/) object. |
| void [set_LinePositionOffset](./set_linepositionoffset/)(**int32_t**) | Sets line position offset of the [XmlReader](../xmlreader/) object. |
| void [set_MaxCharactersFromEntities](./set_maxcharactersfromentities/)(**int64_t**) | Sets a value indicating the maximum allowable number of characters in a document that result from expanding entities. |
| void [set_MaxCharactersInDocument](./set_maxcharactersindocument/)(**int64_t**) | Sets a value indicating the maximum allowable number of characters in an XML document. A zero (0) value means no limits on the size of the XML document. A non-zero value specifies the maximum size, in characters. |
| void [set_NameTable](./set_nametable/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Sets the [XmlNameTable](../xmlnametable/) used for atomized string comparisons. |
| void [set_ProhibitDtd](./set_prohibitdtd/)(**bool**) | Sets a value indicating whether to prohibit document type definition (DTD) processing. |
| void [set_Schemas](./set_schemas/)(const [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\>\&) | Sets the XmlSchemaSet to use when performing schema validation. |
| void [set_ValidationFlags](./set_validationflags/)([Schema::XmlSchemaValidationFlags](../../system.xml.schema/xmlschemavalidationflags/)) | Sets a value indicating the schema validation settings. This setting applies to [XmlReader](../xmlreader/) objects that validate schemas ([XmlReaderSettings::get_ValidationType](./get_validationtype/) value is [ValidationType::Schema](../validationtype/)). |
| void [set_ValidationType](./set_validationtype/)([System::Xml::ValidationType](../validationtype/)) | Sets a value indicating whether the [XmlReader](../xmlreader/) will perform validation or type assignment when reading. |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../xmlresolver/)\>\&) | Sets the [XmlResolver](../xmlresolver/) used to access external documents. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gets current value of shared reference counter. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Increments shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrements and returns shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implements C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| void [ValidationEventHandler_add](./validationeventhandler_add/)(Args...) | Adds an event handler that occurs when the reader encounters validation errors. |
| void [ValidationEventHandler_remove](./validationeventhandler_remove/)(Args...) | Removes an event handler that occurs when the reader encounters validation errors. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
|  [XmlReaderSettings](./xmlreadersettings/)() | Initializes a new instance of the [XmlReaderSettings](./) class. |
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