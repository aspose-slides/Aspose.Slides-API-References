---
title: ConsoleOutput
second_title: Aspose.Slides for C++ API Reference
description: "Represents the standard output stream. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument."
type: docs
weight: 170
url: /cpp/system/consoleoutput/
---
## ConsoleOutput class


Represents the standard output stream. Objects of this class should only be allocated using [System::MakeObject()](../makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class ConsoleOutput : public System::IO::TextWriter
```

## Methods

| Method | Description |
| --- | --- |
| virtual void [Close](../../system.io/textwriter/close/)() | Closes the stream and releases aquired resources. |
| void [Dispose](../../system.io/textwriter/dispose/)() override | Releases all resources used by the current object and closes the undelying stream. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Compares objects using C# [Object.Equals](../object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Compares value type objects in C# style. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| virtual void [Flush](../../system.io/textwriter/flush/)() | Flushes the content of the buffer to the underlying stream. |
| [SharedPtr](../sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() override | Always returns ASCII encoding. |
| virtual [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\> [get_FormatProvider](../../system.io/textwriter/get_formatprovider/)() const | Returns the currently used [IFormatProvider](../iformatprovider/) object. |
| [IFormatProviderPtr](../iformatproviderptr/) [get_FormatProvider](../../system.io/textwriter/get_formatprovider/)() | Returns the currently used [IFormatProvider](../iformatprovider/) object. |
| virtual [System::String](../string/) [get_NewLine](../../system.io/textwriter/get_newline/)() const | Returns a line terminator string. |
| [String](../string/) [get_NewLine](../../system.io/textwriter/get_newline/)() | Returns a line terminator string. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Gets reference counter data structure associated with the object. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analog of C# [Object.GetHashCode()](../object/gethashcode/) method. Enables hashing of custom objects. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Gets actual type of object. Analog of C# [System.Object.GetType()](../object/gettype/) call. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Check if object represents an instance of type described by targetType. Analog of C# 'is' operator. |
| void [Lock](../object/lock/)() | Implements C# lock() statement locking. Call directly or use [LockContext](../lockcontext/) sentry object. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analog of C# [Object.MemberwiseClone()](../object/memberwiseclone/) method. Enables cloning custom types. |
|  [Object](../object/object/)() | Creates object. Initializes all internal data structures. |
|  [Object](../object/object/)([Object](../object/) const\&) | Copy constructor. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Assignment operator. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Reference-compares value type object with nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specialization of [Object::ReferenceEquals](../object/referenceequals/) for case of string and nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specialization of [Object::ReferenceEquals](../object/referenceequals/) for case of strings. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Decreases shared reference count by specified value. |
| virtual void [set_NewLine](../../system.io/textwriter/set_newline/)(const [System::String](../string/)\&) | Sets a line terminator string. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| int [SharedCount](../object/sharedcount/)() const | Gets current value of shared reference counter. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Increments shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Decrements and returns shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | Analog of C# [Object.ToString()](../object/tostring/) method. Enables converting custom objects to string. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implements C# typeof([System.Object](../object/)) construct. |
| void [Unlock](../object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../lockcontext/) sentry object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [Write](./write/)(**bool**) override | Outputs the string representation of the specified bool value to the output stream represented by the current object. |
| void [Write](./write/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) override | Outputs the string representation of the specified object to the output stream represented by the current object. |
| void [Write](./write/)(char_t) override | Outputs the specified character value to the output stream represented by the current object. |
| void [Write](./write/)([Decimal](../decimal/)) override | Outputs the string representation of [Decimal](../decimal/) value to the output stream represented by the current object. |
| void [Write](./write/)(**double**) override | Outputs the string representation of double-precision floating-point value to the output stream represented by the current object. |
| void [Write](./write/)(**int32_t**) override | Outputs the string representation of 32-bit integer value to the output stream represented by the current object. |
| void [Write](./write/)(**int64_t**) override | Outputs the string representation of 64-bit integer value to the output stream represented by the current object. |
| void [Write](./write/)(**float**) override | Outputs the string representation of single-precision floating-point value to the output stream represented by the current object. |
| void [Write](./write/)(const [String](../string/)\&) override | Outputs the specified string object to the output stream represented by the current object. |
| void [Write](./write/)(**uint32_t**) override | Outputs the string representation of unsigned 32-bit integer value to the output stream represented by the current object. |
| void [Write](./write/)(**uint64_t**) override | Outputs the string representation of unsigned 64-bit integer value to the output stream represented by the current object. |
| void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) override | Outputs the string representation of the specified character array to the output stream represented by the current object. |
| void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Outputs the string representation of a range of values of the specified character array to the output stream represented by the current object. |
| void [Write](./write/)(const char_t *) override | Outputs the specified c-string to the output stream represented by the current object. |
| void [Write](./write/)(const [TypeInfo](../typeinfo/)\&) override | Outputs the string representation of the specified [TypeInfo](../typeinfo/) object to the output stream represented by the current object. |
| void [Write](./write/)(const char *) |  |
| virtual void [Write](../../system.io/textwriter/write/)(int) | Writes the string representation of the specified 32-bit integer value to the stream. |
| void [Write](../../system.io/textwriter/write/)(const [String](../string/)\&, const TArgs\&...) | Writes the specified values formatted according to the specified format to the stream. |
| void [WriteLine](./writeline/)() override | Outputs the current line terminator to the output stream represented by the current object. |
| void [WriteLine](./writeline/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) override | Outputs the string representation of the specified object followed by the current line terminator to the output stream represented by the current object. |
| void [WriteLine](./writeline/)(**bool**) override | Outputs the string representation of the specified bool value followed by the current line terminator to the output stream represented by the current object. |
| void [WriteLine](./writeline/)(char_t) override | Outputs the specified character value followed by the current line terminator to the output stream represented by the current object. |
| void [WriteLine](./writeline/)([Decimal](../decimal/)) override | Outputs the string representation of [Decimal](../decimal/) value followed by the current line terminator to the output stream represented by the current object. |
| void [WriteLine](./writeline/)(**double**) override | Outputs the string representation of double-precision floating-point value followed by the current line terminator to the output stream represented by the current object. |
| void [WriteLine](./writeline/)(int) override | Outputs the string representation of 32-bit integer value followed by the current line terminator to the output stream represented by the current object. |
| void [WriteLine](./writeline/)(**int64_t**) override | Outputs the string representation of 64-bit integer value followed by the current line terminator to the output stream represented by the current object. |
| void [WriteLine](./writeline/)(**float**) override | Outputs the string representation of single-precision floating-point value followed by the current line terminator to the output stream represented by the current object. |
| void [WriteLine](./writeline/)(const [String](../string/)\&) override | Outputs the specified string object followed by the current line terminator to the output stream represented by the current object. |
| void [WriteLine](./writeline/)(**uint32_t**) override | Outputs the string representation of unsigned 32-bit integer value followed by the current line terminator to the output stream represented by the current object. |
| void [WriteLine](./writeline/)(**uint64_t**) override | Outputs the string representation of unsigned 64-bit integer value followed by the current line terminator to the output stream represented by the current object. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) override | Outputs the string representation of the specified character array followed by the current line terminator to the output stream represented by the current object. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Outputs the string representation of a range of values of the specified character array followed by the current line terminator to the output stream represented by the current object. |
| void [WriteLine](./writeline/)(const char_t *) override | Outputs the specified c-string followed by the current line terminator to the output stream represented by the current object. |
| void [WriteLine](./writeline/)(const [TypeInfo](../typeinfo/)\&) override | Outputs the string representation of the specified [TypeInfo](../typeinfo/) object followed by the current line terminator to the output stream represented by the current object. |
| void [WriteLine](./writeline/)(const char *) |  |
| void [WriteLine](../../system.io/textwriter/writeline/)(const [String](../string/)\&, const TArgs\&...) | Writes the specified values formatted according to the specified format followed by the line-terminating characetrs to the stream. |
| virtual  [~Object](../object/~object/)() | Destroys object. Frees all internal data structures. |
| virtual  [~TextWriter](../../system.io/textwriter/~textwriter/)() | Destructor. |
## See Also

* Class [TextWriter](../../system.io/textwriter/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)
