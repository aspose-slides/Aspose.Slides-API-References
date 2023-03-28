---
title: XmlConvert
second_title: Aspose.Slides for C++ API Reference
description: Encodes and decodes XML names, and provides methods for converting between runtime types and XML Schema definition language (XSD) types. When converting data types, the values returned are locale-independent.
type: docs
weight: 157
url: /cpp/system.xml/xmlconvert/
---
## XmlConvert class


Encodes and decodes XML names, and provides methods for converting between runtime types and XML [Schema](../../system.xml.schema/) definition language (XSD) types. When converting data types, the values returned are locale-independent.

```cpp
class XmlConvert : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| static [String](../../system/string/) [DecodeName](./decodename/)(const [String](../../system/string/)\&) | Decodes a name. This method does the reverse of the XmlConvert::EncodeName(String) and XmlConvert::EncodeLocalName(String) methods. |
| static [String](../../system/string/) [EncodeLocalName](./encodelocalname/)(const [String](../../system/string/)\&) | Converts the name to a valid XML local name. |
| static [String](../../system/string/) [EncodeName](./encodename/)(const [String](../../system/string/)\&) | Converts the name to a valid XML name. |
| static [String](../../system/string/) [EncodeNmToken](./encodenmtoken/)(const [String](../../system/string/)\&) | Verifies the name is valid according to the XML specification. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares value type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gets actual type of object. Analog of C# [System.Object.GetType()](../../system/object/gettype/) call. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Check if object represents an instance of type described by targetType. Analog of C# 'is' operator. |
| static **bool** [IsNCNameChar](./isncnamechar/)(char16_t) | Checks whether the passed-in character is a valid non-colon character type. |
| static **bool** [IsPublicIdChar](./ispublicidchar/)(char16_t) | Returns the passed-in character instance if the character in the argument is a valid public id character, otherwise **nullptr**. |
| static **bool** [IsStartNCNameChar](./isstartncnamechar/)(char16_t) | Checks if the passed-in character is a valid Start Name Character type. |
| static **bool** [IsWhitespaceChar](./iswhitespacechar/)(char16_t) | Checks if the passed-in character is a valid XML whitespace character. |
| static **bool** [IsXmlChar](./isxmlchar/)(char16_t) | Checks if the passed-in character is a valid XML character. |
| static **bool** [IsXmlSurrogatePair](./isxmlsurrogatepair/)(char16_t, char16_t) | Checks if the passed-in surrogate pair of characters is a valid XML character. |
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
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gets current value of shared reference counter. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Increments shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrements and returns shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| static **bool** [ToBoolean](./toboolean/)([String](../../system/string/)) | Converts the [String](../../system/string/) to a [Boolean](../../system/boolean/) equivalent. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../../system/string/)\&) | Converts the [String](../../system/string/) to a [Byte](../../system/byte/) equivalent. |
| static char16_t [ToChar](./tochar/)(const [String](../../system/string/)\&) | Converts the [String](../../system/string/) to a [Char](../../system/char/) equivalent. |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&) | Converts the [String](../../system/string/) to a [DateTime](../../system/datetime/) equivalent. |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Converts the [String](../../system/string/) to a [DateTime](../../system/datetime/) equivalent. |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Converts the [String](../../system/string/) to a [DateTime](../../system/datetime/) equivalent. |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&, [XmlDateTimeSerializationMode](../xmldatetimeserializationmode/)) | Converts the [String](../../system/string/) to a [DateTime](../../system/datetime/) using the XmlDateTimeSerializationMode specified. |
| static [DateTimeOffset](../../system/datetimeoffset/) [ToDateTimeOffset](./todatetimeoffset/)(const [String](../../system/string/)\&) | Converts the supplied [String](../../system/string/) to a [DateTimeOffset](../../system/datetimeoffset/) equivalent. |
| static [DateTimeOffset](../../system/datetimeoffset/) [ToDateTimeOffset](./todatetimeoffset/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Converts the supplied [String](../../system/string/) to a [DateTimeOffset](../../system/datetimeoffset/) equivalent. |
| static [DateTimeOffset](../../system/datetimeoffset/) [ToDateTimeOffset](./todatetimeoffset/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Converts the supplied [String](../../system/string/) to a [DateTimeOffset](../../system/datetimeoffset/) equivalent. |
| static [Decimal](../../system/decimal/) [ToDecimal](./todecimal/)(const [String](../../system/string/)\&) | Converts the [String](../../system/string/) to a [Decimal](../../system/decimal/) equivalent. |
| static **double** [ToDouble](./todouble/)([String](../../system/string/)) | Converts the [String](../../system/string/) to a [Double](../../system/double/) equivalent. |
| static [Guid](../../system/guid/) [ToGuid](./toguid/)(const [String](../../system/string/)\&) | Converts the [String](../../system/string/) to a [Guid](../../system/guid/) equivalent. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../../system/string/)\&) | Converts the [String](../../system/string/) to a [Int16](../../system/int16/) equivalent. |
| static **int32_t** [ToInt32](./toint32/)(const [String](../../system/string/)\&) | Converts the [String](../../system/string/) to a [Int32](../../system/int32/) equivalent. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../../system/string/)\&) | Converts the [String](../../system/string/) to a [Int64](../../system/int64/) equivalent. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../../system/string/)\&) | Converts the [String](../../system/string/) to a [SByte](../../system/sbyte/) equivalent. |
| static **float** [ToSingle](./tosingle/)([String](../../system/string/)) | Converts the [String](../../system/string/) to a [Single](../../system/single/) equivalent. |
| static [String](../../system/string/) [ToString](./tostring/)(**bool**) | Converts the [Boolean](../../system/boolean/) to a [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(char16_t) | Converts the [Char](../../system/char/) to a [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([Decimal](../../system/decimal/)) | Converts the [Decimal](../../system/decimal/) to a [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**int8_t**) | Converts the [SByte](../../system/sbyte/) to a [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**int16_t**) | Converts the [Int16](../../system/int16/) to a [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**int32_t**) | Converts the [Int32](../../system/int32/) to a [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**int64_t**) | Converts the [Int64](../../system/int64/) to a [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**uint8_t**) | Converts the [Byte](../../system/byte/) to a [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**uint16_t**) | Converts the [UInt16](../../system/uint16/) to a [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**uint32_t**) | Converts the [UInt32](../../system/uint32/) to a [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**uint64_t**) | Converts the [UInt64](../../system/uint64/) to a [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**float**) | Converts the [Single](../../system/single/) to a [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**double**) | Converts the [Double](../../system/double/) to a [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([TimeSpan](../../system/timespan/)) | Converts the [TimeSpan](../../system/timespan/) to a [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([DateTime](../../system/datetime/)) | Converts the [DateTime](../../system/datetime/) to a [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([DateTime](../../system/datetime/), const [String](../../system/string/)\&) | Converts the [DateTime](../../system/datetime/) to a [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([DateTime](../../system/datetime/), [XmlDateTimeSerializationMode](../xmldatetimeserializationmode/)) | Converts the [DateTime](../../system/datetime/) to a [String](../../system/string/) using the XmlDateTimeSerializationMode specified. |
| static [String](../../system/string/) [ToString](./tostring/)([DateTimeOffset](../../system/datetimeoffset/)) | Converts the supplied [DateTimeOffset](../../system/datetimeoffset/) to a [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([DateTimeOffset](../../system/datetimeoffset/), const [String](../../system/string/)\&) | Converts the supplied [DateTimeOffset](../../system/datetimeoffset/) to a [String](../../system/string/) in the specified format. |
| static [String](../../system/string/) [ToString](./tostring/)([Guid](../../system/guid/)) | Converts the [Guid](../../system/guid/) to a [String](../../system/string/). |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| static [TimeSpan](../../system/timespan/) [ToTimeSpan](./totimespan/)(const [String](../../system/string/)\&) | Converts the [String](../../system/string/) to a [TimeSpan](../../system/timespan/) equivalent. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../../system/string/)\&) | Converts the [String](../../system/string/) to a [UInt16](../../system/uint16/) equivalent. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../../system/string/)\&) | Converts the [String](../../system/string/) to a [UInt32](../../system/uint32/) equivalent. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../../system/string/)\&) | Converts the [String](../../system/string/) to a [UInt64](../../system/uint64/) equivalent. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implements C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| static [String](../../system/string/) [VerifyName](./verifyname/)(const [String](../../system/string/)\&) | Verifies that the name is a valid name according to the W3C Extended Markup Language recommendation. |
| static [String](../../system/string/) [VerifyNCName](./verifyncname/)(const [String](../../system/string/)\&) | Verifies that the name is a valid **NCName** according to the W3C Extended Markup Language recommendation. An **NCName** is a name that cannot contain a colon. |
| static [String](../../system/string/) [VerifyNMTOKEN](./verifynmtoken/)(const [String](../../system/string/)\&) | Verifies that the string is a valid NMTOKEN according to the W3C XML [Schema](../../system.xml.schema/) Part2: Datatypes recommendation. |
| static [String](../../system/string/) [VerifyPublicId](./verifypublicid/)(const [String](../../system/string/)\&) | Returns the passed in string instance if all the characters in the string argument are valid public id characters. |
| static [String](../../system/string/) [VerifyTOKEN](./verifytoken/)(const [String](../../system/string/)\&) | Verifies that the string is a valid token according to the W3C XML [Schema](../../system.xml.schema/) Part2: Datatypes recommendation. |
| static [String](../../system/string/) [VerifyWhitespace](./verifywhitespace/)(const [String](../../system/string/)\&) | Returns the passed-in string instance if all the characters in the string argument are valid whitespace characters. |
| static [String](../../system/string/) [VerifyXmlChars](./verifyxmlchars/)(const [String](../../system/string/)\&) | Returns the passed-in string if all the characters and surrogate pair characters in the string argument are valid XML characters, otherwise an XmlException is thrown with information on the first invalid character encountered. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroys object. Frees all internal data structures. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Xml](../)
* Library [Aspose.Slides](../../)
