---
title: FileInfo
second_title: Aspose.Slides for C++ API Reference
description: "Represents a path to a file and a file referred to by this path and provides methods for manipulating it. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument."
type: docs
weight: 261
url: /cpp/system.io/fileinfo/
---
## FileInfo class


Represents a path to a file and a file referred to by this path and provides methods for manipulating it. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class FileInfo : public System::IO::FileSystemInfo
```

## Methods

| Method | Description |
| --- | --- |
| [StreamWriterPtr](../../system/streamwriterptr/) [AppendText](./appendtext/)() | Opens a file represented by the current object for writing text using UTF-8 encoding, in 'Append' mode with no sharing. |
| [FileInfoPtr](../../system/fileinfoptr/) [CopyTo](./copyto/)(const [String](../../system/string/)\&) | Copies the file represented by the current object to the specified location. If the destination file already exists, the copying fails. |
| [FileInfoPtr](../../system/fileinfoptr/) [CopyTo](./copyto/)(const [String](../../system/string/)\&, **bool**) | Copies the file represented by the current object to the specified location. A parameter specifies if existing destination file should be overwritten. |
| [FileStreamPtr](../../system/filestreamptr/) [Create](./create/)() | Creates a file at the location specified by the path represented by the current object and opens it for reading and writing, in truncate mode and with no sharing. |
| [StreamWriterPtr](../../system/streamwriterptr/) [CreateText](./createtext/)() | Creates a file at the location specified by the path represented by the current object and opens it for writing text using UTF-8 encoding with no sharing. |
| void [Decrypt](./decrypt/)() | NOT IMPLEMENTED. |
| void [Delete](./delete/)() override | Removes the file represented by the current object. |
| void [Encrypt](./encrypt/)() | NOT IMPLEMENTED. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares value type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
|  [FileInfo](./fileinfo/)(const [String](../../system/string/)\&) | Constructs a new instance of [FileInfo](./) class that represents the specified file. |
| virtual void [Finalize](../filesysteminfo/finalize/)() | Does nothing. |
| [FileAttributes](../fileattributes/) [get_Attributes](../filesysteminfo/get_attributes/)() | Returns the attributes of the entity represented by the current object. |
| [DateTime](../../system/datetime/) [get_CreationTime](../filesysteminfo/get_creationtime/)() | Returns the creation time of the entity represented by the current object as local time. |
| [DateTime](../../system/datetime/) [get_CreationTimeUtc](../filesysteminfo/get_creationtimeutc/)() | Returns the creation time of the entity represented by the current object as UTC time. |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [get_Directory](./get_directory/)() | Returns a [DirectoryInfo](../directoryinfo/) object that represents a directory in which the file represented by the current object is located. |
| [String](../../system/string/) [get_DirectoryName](./get_directoryname/)() | Returns the full name of the directory in which the file represented by the current object is loctaed. |
| **bool** [get_Exists](./get_exists/)() override | Returns a value that indicates if the file exists. |
| [String](../../system/string/) [get_Extension](../filesysteminfo/get_extension/)() | Returns the extension of the file represented by the current object. |
| virtual [String](../../system/string/) [get_FullName](../filesysteminfo/get_fullname/)() | Returns the full name (including path) of the entity represented by the current object. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() | Returns a value that indicates if the ReadOnly attribute is set. |
| [DateTime](../../system/datetime/) [get_LastAccessTime](../filesysteminfo/get_lastaccesstime/)() | Returns the last access time of the entity represented by the current object as local time. |
| [DateTime](../../system/datetime/) [get_LastAccessTimeUtc](../filesysteminfo/get_lastaccesstimeutc/)() | Returns the last access time of the entity represented by the current object as UTC time. |
| [DateTime](../../system/datetime/) [get_LastWriteTime](../filesysteminfo/get_lastwritetime/)() | Returns the last write time of the entity represented by the current object as local time. |
| [DateTime](../../system/datetime/) [get_LastWriteTimeUtc](../filesysteminfo/get_lastwritetimeutc/)() | Returns the last write time of the entity represented by the current object as UTC time. |
| **int64_t** [get_Length](./get_length/)() | Returns the size of the file in bytes. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Returns the name of the file. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gets actual type of object. Analog of C# [System.Object.GetType()](../../system/object/gettype/) call. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Check if object represents an instance of type described by targetType. Analog of C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implements C# lock() statement locking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog of C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) method. Enables cloning custom types. |
| void [MoveTo](./moveto/)(const [String](../../system/string/)\&) | Moves the file represented by the current object to the specified location. |
|  [Object](../../system/object/object/)() | Creates object. Initializes all internal data structures. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy constructor. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/)) | Opens the file represented by the current object in the specified mode for reading and writing and with no sharing. |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/), [FileAccess](../fileaccess/)) | Opens the file represented by the current object in the specified mode, with the specified access type and with no sharing. |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/)) | Opens the file represented by the current object in the specified mode, with the specified access type and sharing option. |
| [FileStreamPtr](../../system/filestreamptr/) [OpenRead](./openread/)() | Opens a file represented by the current object for reading only, in 'Open' mode with shared access for reading. |
| [StreamReaderPtr](../../system/streamreaderptr/) [OpenText](./opentext/)() | Opens the existing file at the location specified by the path represented by the current object for reading text using UTF-8 encoding with no sharing. |
| [FileStreamPtr](../../system/filestreamptr/) [OpenWrite](./openwrite/)() | Opens a file represented by the current object for writing only, in 'OpenOrCreate' mode with no sharing. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Assignment operator. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Reference-compares value type object with nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of string and nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of strings. |
| void [Refresh](../filesysteminfo/refresh/)() | Refreshes the state of the current object. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decreases shared reference count by specified value. |
| [FileInfoPtr](../../system/fileinfoptr/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Replaces the contents of a specified destination file with the file represented by the current [FileInfo](./) object and creates a backup of the replaced file. |
| [FileInfoPtr](../../system/fileinfoptr/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | Replaces the contents of a specified destination file with the file represented by the current [FileInfo](./) object and creates a backup of the replaced file. |
| void [set_Attributes](../filesysteminfo/set_attributes/)([FileAttributes](../fileattributes/)) | Sets the specified attributes on the entity represeted by the current object. |
| void [set_CreationTime](../filesysteminfo/set_creationtime/)([DateTime](../../system/datetime/)) | Sets the creation time of the entity represented by the current object as local time. |
| void [set_CreationTimeUtc](../filesysteminfo/set_creationtimeutc/)([DateTime](../../system/datetime/)) | Sets the creation time of the entity represented by the current object as UTC time. |
| void [set_IsReadOnly](./set_isreadonly/)(**bool**) | Sets or unsets the ReadOnly attribute on the file. |
| void [set_LastAccessTime](../filesysteminfo/set_lastaccesstime/)([DateTime](../../system/datetime/)) | Sets the last access time of the entity represented by the current object as local time. |
| void [set_LastAccessTimeUtc](../filesysteminfo/set_lastaccesstimeutc/)([DateTime](../../system/datetime/)) | Sets the last access time of the entity represented by the current object as UTC time. |
| void [set_LastWriteTime](../filesysteminfo/set_lastwritetime/)([DateTime](../../system/datetime/)) | Sets the last write time of the entity represented by the current object as local time. |
| void [set_LastWriteTimeUtc](../filesysteminfo/set_lastwritetimeutc/)([DateTime](../../system/datetime/)) | Sets the last write time of the entity represented by the current object as UTC time. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gets current value of shared reference counter. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Increments shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrements and returns shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Returns a path represented by the current object. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implements C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroys object. Frees all internal data structures. |
## See Also

* Class [FileSystemInfo](../filesysteminfo/)
* Namespace [System::IO](../)
* Library [Aspose.Slides](../../)