---
title: StreamReader
second_title: Aspose.Slides for C++ API Reference
description: "Represents a reader that reads characters from a byte stream. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument."
type: docs
weight: 365
url: /cpp/system.io/streamreader/
---
## StreamReader class


Represents a reader that reads characters from a byte stream. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class StreamReader : public System::IO::TextReader
```

## Methods

| Method | Description |
| --- | --- |
| void [Close](./close/)() override | Closes the current and underlying streams. |
| virtual void [Dispose](./dispose/)(**bool**) | Releases all resources used by the current object and closes the undelying stream. |
| void [Dispose](./dispose/)() override | Releases all resources used by the current object and closes the undelying stream. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares value type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\> [get_BaseStream](./get_basestream/)() const | Returns a shared pointer to an object that represents the underlying stream. |
| [EncodingPtr](../../system/encodingptr/) [get_CurrentEncoding](./get_currentencoding/)() | Returns the currently used encoding. |
| **bool** [get_EndOfStream](./get_endofstream/)() | Returns a value that indicates if the end of of stream has been reached. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gets actual type of object. Analog of C# [System.Object.GetType()](../../system/object/gettype/) call. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Check if object represents an instance of type described by targetType. Analog of C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implements C# lock() statement locking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog of C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) method. Enables cloning custom types. |
|  [Object](../../system/object/object/)() | Creates object. Initializes all internal data structures. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy constructor. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Assignment operator. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| int [Peek](./peek/)() override | Reads a single character from the stream without changing the stream's read cursor. |
| int [Read](./read/)() override | Reads a single character from the stream. |
| int [Read](./read/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) override | Reads the specified number of characters from the stream, converts them to UTF-16 encoding and writes the resulting UTF-16 characters to the specified character array starting at the specified position. |
| virtual int [ReadBlock](../textreader/readblock/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Reads the specified maximum number of characters from the current text reader and writes the data to a buffer, starting at the specified index. |
| [String](../../system/string/) [ReadLine](./readline/)() override | Reads characters from the stream until the end of the current line. |
| [String](../../system/string/) [ReadToEnd](./readtoend/)() override | Reads characters from the stream until the end of the stream. |
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
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Constructs an instance of [StreamReader](./) object that reads characters from the specified underlying stream using UTF-8 encoding and a buffer with default size of 1024 bytes. |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **bool**) | Constructs an instance of [StreamReader](./) object that reads characters from the specified underlying stream using UTF-8 encoding and a buffer with default size of 1024 bytes. A parameter specifies if byte order mark detection should be enabled. |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Constructs an instance of [StreamReader](./) object that reads characters from the specified underlying stream using the specified encoding and a buffer with default size of 1024 bytes. |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**) | Constructs an instance of [StreamReader](./) object that reads characters from the specified underlying stream using the specified encoding and a buffer with default size of 1024 bytes. A parameter specifies if byte order mark detection should be enabled. |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**, int) | Constructs an instance of [StreamReader](./) object that reads characters from the specified underlying stream using the specified encoding and a buffer of the specified size. A parameter specifies if byte order mark detection should be enabled. |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&) | Constructs an instance of [StreamReader](./) object that reads characters from the specified file using UTF-8 encoding and a buffer with default size of 4096 bytes. |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, **bool**) | Constructs an instance of [StreamReader](./) object that reads characters from the specified file using UTF-8 encoding and a buffer with default size of 4096 bytes. A parameter specifies if byte order mark detection should be enabled. |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Constructs an instance of [StreamReader](./) object that reads characters from the specified file using the specified encoding and a buffer with default size of 4096 bytes. |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**) | Constructs an instance of [StreamReader](./) object that reads characters from the specified underlying stream using the specified encoding and a buffer with default size of 4096 bytes. A parameter specifies if byte order mark detection should be enabled. |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**, int) | Constructs an instance of [StreamReader](./) object that reads characters from the specified file using the specified encoding and a buffer of the specified size. A parameter specifies if byte order mark detection should be enabled. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implements C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroys object. Frees all internal data structures. |
|  [~StreamReader](./~streamreader/)() | Destructor. |
## See Also

* Class [TextReader](../textreader/)
* Namespace [System::IO](../)
* Library [Aspose.Slides](../../)