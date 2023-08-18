---
title: StringWriter
second_title: Aspose.Slides for C++ API Reference
description: "Implements a TextWriter that writes information to a string. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument."
type: docs
weight: 404
url: /system.io/stringwriter/
---
## StringWriter class


Implements a [TextWriter](../textwriter/) that writes information to a string. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class StringWriter : public System::IO::TextWriter
```

## Methods

| Method | Description |
| --- | --- |
| virtual void [Close](../textwriter/close/)() | Closes the stream and releases aquired resources. |
| void [Dispose](../textwriter/dispose/)() override | Releases all resources used by the current object and closes the undelying stream. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares value type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| virtual void [Flush](../textwriter/flush/)() | Flushes the content of the buffer to the underlying stream. |
| [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() override | Returns the currently used encoding. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](../textwriter/get_formatprovider/)() const | Returns the currently used [IFormatProvider](../../system/iformatprovider/) object. |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](../textwriter/get_formatprovider/)() | Returns the currently used [IFormatProvider](../../system/iformatprovider/) object. |
| virtual [System::String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() const | Returns a line terminator string. |
| [String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() | Returns a line terminator string. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\> [GetStringBuilder](./getstringbuilder/)() | Returns the currently used StringBuilder. |
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
| virtual void [set_NewLine](../textwriter/set_newline/)(const [System::String](../../system/string/)\&) | Sets a line terminator string. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gets current value of shared reference counter. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Increments shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrements and returns shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
|  [StringWriter](./stringwriter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | Constructs a new instance of [StringWriter](./) using the specified StringBuilder and [IFormatProvider](../../system/iformatprovider/). |
|  [StringWriter](./stringwriter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | Constructs a new instance of [StringWriter](./) using the specified StringBuilder and [IFormatProvider](../../system/iformatprovider/) from the current culture. |
|  [StringWriter](./stringwriter/)(const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | Constructs a new instance of [StringWriter](./) using the specified [IFormatProvider](../../system/iformatprovider/). |
|  [StringWriter](./stringwriter/)() | Constructs a new instance of [StringWriter](./) using [IFormatProvider](../../system/iformatprovider/) from the current culture. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Returns the underlying string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implements C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [Write](./write/)(char_t) override | Writes the specified character to the stream. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Writes the specified subrange of characters from the specified character array to the stream. |
| void [Write](./write/)(const [String](../../system/string/)\&) override | Writes the specified string to the stream. |
| virtual void [Write](../textwriter/write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Writes the string representation of the specified object to the stream. |
| virtual void [Write](../textwriter/write/)(**bool**) | Writes the string representation of the specified boolean value to the stream. |
| virtual void [Write](../textwriter/write/)([Decimal](../../system/decimal/)) | Writes the string representation of the specified [Decimal](../../system/decimal/) object to the stream. |
| virtual void [Write](../textwriter/write/)(**double**) | Writes the string representation of the specified double-precision floating point value to the stream. |
| virtual void [Write](../textwriter/write/)(int) | Writes the string representation of the specified 32-bit integer value to the stream. |
| virtual void [Write](../textwriter/write/)(**int64_t**) | Writes the string representation of the specified 64-bit integer value to the stream. |
| virtual void [Write](../textwriter/write/)(**float**) | Writes the string representation of the specified single-precision floating point value to the stream. |
| virtual void [Write](../textwriter/write/)(**uint32_t**) | Writes the string representation of the specified unsigned 32-bit integer value to the stream. |
| virtual void [Write](../textwriter/write/)(**uint64_t**) | Writes the string representation of the specified unsigned 64-bit integer value to the stream. |
| virtual void [Write](../textwriter/write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Writes all characetrs from the specified array to the stream. |
| virtual void [Write](../textwriter/write/)(const char_t *) | Writes the specified c-string to the stream. |
| virtual void [Write](../textwriter/write/)(const [TypeInfo](../../system/typeinfo/)\&) | Writes the string representation of the specified [TypeInfo](../../system/typeinfo/) object to the stream. |
| void [Write](../textwriter/write/)(const [String](../../system/string/)\&, const TArgs\&...) | Writes the specified values formatted according to the specified format to the stream. |
| virtual void [WriteLine](../textwriter/writeline/)() | Writes line terminator characters to the stream. |
| virtual void [WriteLine](../textwriter/writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Writes the string representation of the specified object followed by the line-terminating characters to the stream. |
| virtual void [WriteLine](../textwriter/writeline/)(**bool**) | Writes the string representation of the specified boolean value followed by the line-terminating characters to the stream. |
| virtual void [WriteLine](../textwriter/writeline/)(char_t) | Writes the specified character followed by the line-terminating characters to the stream. |
| virtual void [WriteLine](../textwriter/writeline/)([Decimal](../../system/decimal/)) | Writes the string representation of the specified [Decimal](../../system/decimal/) object followed by the line-terminating characters to the stream. |
| virtual void [WriteLine](../textwriter/writeline/)(**double**) | Writes the string representation of the specified double-precision floating point value followed by the line-terminating characters to the stream. |
| virtual void [WriteLine](../textwriter/writeline/)(int) | Writes the string representation of the specified 32-bit integer value followed by the line-terminating characters to the stream. |
| virtual void [WriteLine](../textwriter/writeline/)(**int64_t**) | Writes the string representation of the specified 64-bit integer value followed by the line-terminating characters to the stream. |
| virtual void [WriteLine](../textwriter/writeline/)(**float**) | Writes the string representation of the specified single-precision floating point value followed by the line-terminating characters to the stream. |
| virtual void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&) | Writes the specified string followed by the line-terminating characters to the stream. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint32_t**) | Writes the string representation of the specified unsigned 32-bit integer value followed by the line-terminating characters to the stream. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint64_t**) | Writes the string representation of the specified unsigned 64-bit integer value followed by the line-terminating characters to the stream. |
| virtual void [WriteLine](../textwriter/writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Writes all characetrs from the specified array followed by the line-terminating characters to the stream. |
| virtual void [WriteLine](../textwriter/writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | Writes the specified subrange of UTF-16 characters from the specified character array followed by the line-terminating characters to the stream. |
| virtual void [WriteLine](../textwriter/writeline/)(const char_t *) | Writes the specified c-string followed by the line-terminating characters to the stream. |
| virtual void [WriteLine](../textwriter/writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | Writes the string representation of the specified [TypeInfo](../../system/typeinfo/) object followed by the line-terminating characters to the stream. |
| void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | Writes the specified values formatted according to the specified format followed by the line-terminating characetrs to the stream. |
| virtual  [~Object](../../system/object/~object/)() | Destroys object. Frees all internal data structures. |
| virtual  [~TextWriter](../textwriter/~textwriter/)() | Destructor. |
## See Also

* Class [TextWriter](../textwriter/)
* Namespace [System::IO](../)
* Library [Aspose.Slides](../../)