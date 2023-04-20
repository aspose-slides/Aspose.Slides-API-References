---
title: DirectoryInfo
second_title: Aspose.Slides for C++ API Reference
description: "Represents a file system path, a directory referred to by this path and provides instance methods for manipulating directories. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument."
type: docs
weight: 235
url: /cpp/system.io/directoryinfo/
---
## DirectoryInfo class


Represents a file system path, a directory referred to by this path and provides instance methods for manipulating directories. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class DirectoryInfo : public System::IO::FileSystemInfo
```

## Methods

| Method | Description |
| --- | --- |
| void [Create](./create/)() | Creates a directory at the path represented by the current object. |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [CreateSubdirectory](./createsubdirectory/)(const [String](../../system/string/)\&) | Creates subdirectories on the specified path. |
| void [Delete](./delete/)() override | Removes the directory referred to by the path represented by the current object if the directory is empty. |
| void [Delete](./delete/)(**bool**) | Removes the directory referred to by the path represented by the current object. A parameter specifies if the content of the directory should be recursively removed if the directory is not empty. |
|  [DirectoryInfo](./directoryinfo/)(const [String](../../system/string/)\&) | Constructs an instnace of [DirectoryInfo](./) class on the specified path. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\>\> [EnumerateDirectories](./enumeratedirectories/)() | Returns enumerable collection containing all directories located in the directory represented by the current object. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\>\> [EnumerateDirectories](./enumeratedirectories/)(const [String](../../system/string/)\&) | Searches for the directories that satisfy the specified search criteria in the directory represented by the current object. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\>\> [EnumerateDirectories](./enumeratedirectories/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Searches for the directories that satisfy the specified search criteria either in the directory represented by the current object or in the whole directory tree rooted in the directory represented by the current object. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileInfoPtr](../../system/fileinfoptr/)\>\> [EnumerateFiles](./enumeratefiles/)() | Returns enumerable collection containing all files located in the directory represented by the current object. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileInfoPtr](../../system/fileinfoptr/)\>\> [EnumerateFiles](./enumeratefiles/)(const [String](../../system/string/)\&) | Searches for the files that satisfy the specified search criteria in the directory represented by the current object. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileInfoPtr](../../system/fileinfoptr/)\>\> [EnumerateFiles](./enumeratefiles/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Searches for the files that satisfy the specified search criteria either in the directory represented by the current object or in the whole directory tree rooted in the directory represented by the current object. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\>\> [EnumerateFileSystemInfos](./enumeratefilesysteminfos/)() | Returns enumerable collection containing all files and directories located in the directory represented by the current object. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\>\> [EnumerateFileSystemInfos](./enumeratefilesysteminfos/)(const [String](../../system/string/)\&) | Searches for the files and directories that satisfy the specified search criteria in the directory represented by the current object. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\>\> [EnumerateFileSystemInfos](./enumeratefilesysteminfos/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Searches for the files and directories that satisfy the specified search criteria either in the directory represented by the current object or in the whole directory tree rooted in the directory represented by the current object. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares value type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| virtual void [Finalize](../filesysteminfo/finalize/)() | Does nothing. |
| [FileAttributes](../fileattributes/) [get_Attributes](../filesysteminfo/get_attributes/)() | Returns the attributes of the entity represented by the current object. |
| [DateTime](../../system/datetime/) [get_CreationTime](../filesysteminfo/get_creationtime/)() | Returns the creation time of the entity represented by the current object as local time. |
| [DateTime](../../system/datetime/) [get_CreationTimeUtc](../filesysteminfo/get_creationtimeutc/)() | Returns the creation time of the entity represented by the current object as UTC time. |
| **bool** [get_Exists](./get_exists/)() override | Determines if the path represented by the current object refers to existing directory. |
| [String](../../system/string/) [get_Extension](../filesysteminfo/get_extension/)() | Returns the extension of the file represented by the current object. |
| virtual [String](../../system/string/) [get_FullName](../filesysteminfo/get_fullname/)() | Returns the full name (including path) of the entity represented by the current object. |
| [DateTime](../../system/datetime/) [get_LastAccessTime](../filesysteminfo/get_lastaccesstime/)() | Returns the last access time of the entity represented by the current object as local time. |
| [DateTime](../../system/datetime/) [get_LastAccessTimeUtc](../filesysteminfo/get_lastaccesstimeutc/)() | Returns the last access time of the entity represented by the current object as UTC time. |
| [DateTime](../../system/datetime/) [get_LastWriteTime](../filesysteminfo/get_lastwritetime/)() | Returns the last write time of the entity represented by the current object as local time. |
| [DateTime](../../system/datetime/) [get_LastWriteTimeUtc](../filesysteminfo/get_lastwritetimeutc/)() | Returns the last write time of the entity represented by the current object as UTC time. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Returns the name of the entity referred to by the path represented by the current object. |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [get_Parent](./get_parent/)() | Returns a shared pointer to [DirectoryInfo](./) object that represents a path referring the parent directory of the directory represented by the current object. |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [get_Root](./get_root/)() | Returns a shared pointer to [DirectoryInfo](./) object that represents a path referring the root directory of the directory represented by the current object. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| [ArrayPtr](../../system/arrayptr/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\> [GetDirectories](./getdirectories/)() | Returns an array containing shared pointers to [DirectoryInfo](./) objects representing all directories located in the directory represented by the current object. |
| [ArrayPtr](../../system/arrayptr/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\> [GetDirectories](./getdirectories/)(const [String](../../system/string/)\&) | Searches for the directories that satisfy the specified search criteria in the directory represented by the current object. |
| [ArrayPtr](../../system/arrayptr/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\> [GetDirectories](./getdirectories/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Searches for the directories that satisfy the specified search criteria either in the directory represented by the current object or in the whole directory tree rooted in the directory represented by the current object. |
| [ArrayPtr](../../system/arrayptr/)\<[FileInfoPtr](../../system/fileinfoptr/)\> [GetFiles](./getfiles/)() | Returns an array containing shared pointers to [FileInfo](../fileinfo/) objects representing all directories located in the directory represented by the current object. |
| [ArrayPtr](../../system/arrayptr/)\<[FileInfoPtr](../../system/fileinfoptr/)\> [GetFiles](./getfiles/)(const [String](../../system/string/)\&) | Searches for the files that satisfy the specified search criteria in the directory represented by the current object. |
| [ArrayPtr](../../system/arrayptr/)\<[FileInfoPtr](../../system/fileinfoptr/)\> [GetFiles](./getfiles/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Searches for the files that satisfy the specified search criteria either in the directory represented by the current object or in the whole directory tree rooted in the directory represented by the current object. |
| [ArrayPtr](../../system/arrayptr/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\> [GetFileSystemInfos](./getfilesysteminfos/)() | Returns an array containing shared pointers to [FileSystemInfo](../filesysteminfo/) objects representing all files and directories located in the directory represented by the current object. |
| [ArrayPtr](../../system/arrayptr/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\> [GetFileSystemInfos](./getfilesysteminfos/)(const [String](../../system/string/)\&) | Searches for the files and directories that satisfy the specified search criteria in the directory represented by the current object. |
| [ArrayPtr](../../system/arrayptr/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\> [GetFileSystemInfos](./getfilesysteminfos/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Searches for the files and directories that satisfy the specified search criteria either in the directory represented by the current object or in the whole directory tree rooted in the directory represented by the current object. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gets actual type of object. Analog of C# [System.Object.GetType()](../../system/object/gettype/) call. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Check if object represents an instance of type described by targetType. Analog of C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implements C# lock() statement locking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog of C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) method. Enables cloning custom types. |
| void [MoveTo](./moveto/)(const [String](../../system/string/)\&) | Moves the directory represented by the current object and all its contentto the specified location. |
|  [Object](../../system/object/object/)() | Creates object. Initializes all internal data structures. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy constructor. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Assignment operator. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Reference-compares value type object with nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of string and nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of strings. |
| void [Refresh](../filesysteminfo/refresh/)() | Refreshes the state of the current object. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decreases shared reference count by specified value. |
| void [set_Attributes](../filesysteminfo/set_attributes/)([FileAttributes](../fileattributes/)) | Sets the specified attributes on the entity represeted by the current object. |
| void [set_CreationTime](../filesysteminfo/set_creationtime/)([DateTime](../../system/datetime/)) | Sets the creation time of the entity represented by the current object as local time. |
| void [set_CreationTimeUtc](../filesysteminfo/set_creationtimeutc/)([DateTime](../../system/datetime/)) | Sets the creation time of the entity represented by the current object as UTC time. |
| void [set_LastAccessTime](../filesysteminfo/set_lastaccesstime/)([DateTime](../../system/datetime/)) | Sets the last access time of the entity represented by the current object as local time. |
| void [set_LastAccessTimeUtc](../filesysteminfo/set_lastaccesstimeutc/)([DateTime](../../system/datetime/)) | Sets the last access time of the entity represented by the current object as UTC time. |
| void [set_LastWriteTime](../filesysteminfo/set_lastwritetime/)([DateTime](../../system/datetime/)) | Sets the last write time of the entity represented by the current object as local time. |
| void [set_LastWriteTimeUtc](../filesysteminfo/set_lastwritetimeutc/)([DateTime](../../system/datetime/)) | Sets the last write time of the entity represented by the current object as UTC time. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gets current value of shared reference counter. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Increments shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrements and returns shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Returns a string containing the path represented by the current object. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implements C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroys object. Frees all internal data structures. |
## See Also

* Class [FileSystemInfo](../filesysteminfo/)
* Namespace [System::IO](../)
* Library [Aspose.Slides](../../)