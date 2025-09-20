---
title: MemoryStream
second_title: Aspose.Slides for C++ API Reference
description: "Represents a stream that reads from and writes to memory. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument."
type: docs
weight: 313
url: /system.io/memorystream/
---
## MemoryStream class


Represents a stream that reads from and writes to memory. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class MemoryStream : public System::IO::Stream
```

## Methods

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Initiates an asynchronous read operation. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Initiates an asynchronous write operation. |
| void [Close](./close/)() override | Closes the stream. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Copies bytes to the specified stream. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **int32_t**) | Copies bytes to the specified stream, using the specified buffer size. |
| void [Dispose](../stream/dispose/)() override | Releases all resources used by the current object and closes the stream. |
| virtual int [EndRead](../stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Waits until the specified asynchronous read operation completes. |
| virtual void [EndWrite](../stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Ends an asynchronous write operation. Waits until the specified asynchronous write operation completes. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares value type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| void [Flush](./flush/)() override | Does nothing. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Asynchronously clears all buffers for this stream, causes any buffered data to be written to the underlying device, and monitors cancellation requests. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)() | Asynchronously clears all buffers for this stream, causes any buffered data to be written to the underlying device, and monitors cancellation requests. |
| **bool** [get_CanRead](./get_canread/)() const override | Determines if the stream is readable. |
| **bool** [get_CanSeek](./get_canseek/)() const override | Determines if the stream supports seeking. |
| virtual **bool** [get_CanTimeout](../stream/get_cantimeout/)() const | Gets a value that determines whether the current stream can time out. |
| **bool** [get_CanWrite](./get_canwrite/)() const override | Determines if the stream is writable. |
| int [get_Capacity](./get_capacity/)() | Returns the current capacity of the underlying memory buffer. |
| **int64_t** [get_Length](./get_length/)() const override | Returns the length of the stream in bytes. |
| **int64_t** [get_Position](./get_position/)() const override | Returns the current position of the stream. |
| virtual int [get_ReadTimeout](../stream/get_readtimeout/)() const | Gets a value, in milliseconds, that determines how long the stream will attempt to read before timing out. |
| virtual int [get_WriteTimeout](../stream/get_writetimeout/)() const | Gets a value, in milliseconds, that determines how long the stream will attempt to write before timing out. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBuffer](./getbuffer/)() | Returns a pointer to the underlying buffer. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gets actual type of object. Analog of C# [System.Object.GetType()](../../system/object/gettype/) call. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Check if object represents an instance of type described by targetType. Analog of C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implements C# lock() statement locking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog of C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) method. Enables cloning custom types. |
|  [MemoryStream](./memorystream/)() | Constructs a new instance of the [MemoryStream](./) class with initial capacity equal to 0. |
|  [MemoryStream](./memorystream/)(int) | Constructs a new instance of the [MemoryStream](./) class that represents a stream based on a memory buffer of the specified size. |
|  [MemoryStream](./memorystream/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **bool**) | Constructs a new instance of the [MemoryStream](./) class that represents a memory stream which is connected to the specified memory buffer. A parameter specifies if the stream is writable. |
|  [MemoryStream](./memorystream/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int, **bool**, **bool**) | Constructs a new instance of the [MemoryStream](./) class that represents a memory stream which is connected to a segment of the specified memory buffer starting at the specified index and including the specified number of elements. Parameters specifies if the stream is writable and if method GetBytes() can be called. |
|  [Object](../../system/object/object/)() | Creates object. Initializes all internal data structures. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy constructor. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Assignment operator. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Reads the specified number of bytes from the stream and writes them to the specified byte array. |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Reads the specified number of bytes from the stream and writes them to the specified byte array. |
| **int32_t** [Read](../stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Reads the specified number of bytes from the stream and writes them to the specified byte array. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Asynchronously reads a sequence of bytes from the current stream, advances the position within the stream by the number of bytes read, and monitors cancellation requests. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Asynchronously reads a sequence of bytes from the current stream, advances the position within the stream by the number of bytes read, and monitors cancellation requests. |
| int [ReadByte](./readbyte/)() override | Reads a single byte from the stream and returns a 32-bit integer value equivalent to the value of the read byte. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Reference-compares value type object with nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of string and nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decreases shared reference count by specified value. |
| **int64_t** [Seek](./seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) override | Sets the position of the stream represented by the current object. |
| void [set_Capacity](./set_capacity/)(int) | Sets the capacity of the underlying memory buffer. |
| void [set_Position](./set_position/)(**int64_t**) override | Sets the stream's position. |
| virtual void [set_ReadTimeout](../stream/set_readtimeout/)(int) | Sets a value that determines whether the current stream can time out. |
| virtual void [set_WriteTimeout](../stream/set_writetimeout/)(int) | Sets a value, in milliseconds, that determines how long the stream will attempt to read before timing out. |
| void [SetLength](./setlength/)(**int64_t**) override | Sets the length of the stream represented by the current object. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gets current value of shared reference counter. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Increments shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrements and returns shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ToArray](./toarray/)() | Returns a copy of underlying memory buffer as an array of bytes. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| **bool** [TryGetBuffer](./trygetbuffer/)([ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\&) | Returns the array of unsigned bytes from which this stream was created. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implements C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Writes the specified subrange of bytes from the specified byte array to the stream. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Writes the specified subrange of bytes from the specified byte array to the stream. |
| void [Write](../stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Writes the specified subrange of bytes from the specified byte array to the stream. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Asynchronously writes a sequence of bytes to the current stream, advances the current position within this stream by the number of bytes written, and monitors cancellation requests. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Asynchronously writes a sequence of bytes to the current stream, advances the current position within this stream by the number of bytes written, and monitors cancellation requests. |
| void [WriteByte](./writebyte/)(**uint8_t**) override | Writes the specified unsigned 8-bit integer value to the stream. |
| virtual void [WriteTo](./writeto/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>) | Writes the content of the underlying buffer to the specified stream. |
| virtual  [~Object](../../system/object/~object/)() | Destroys object. Frees all internal data structures. |
## Fields

| Field | Description |
| --- | --- |
| static [Null](../stream/null/) | A stream with no underlying storage. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for a shared pointer to the self. |
## See Also

* Class [Stream](../stream/)
* Namespace [System::IO](../)
* Library [Aspose.Slides](../../)