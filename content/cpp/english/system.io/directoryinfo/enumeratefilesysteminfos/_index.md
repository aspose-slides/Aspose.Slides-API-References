---
title: EnumerateFileSystemInfos()
second_title: Aspose.Slides for C++ API Reference
description: Returns enumerable collection containing all files and directories located in the directory represented by the current object.
type: docs
weight: 131
url: /system.io/directoryinfo/enumeratefilesysteminfos/
---
## DirectoryInfo::EnumerateFileSystemInfos() method


Returns enumerable collection containing all files and directories located in the directory represented by the current object.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos()
```

## DirectoryInfo::EnumerateFileSystemInfos(const String\&) method


Searches for the files and directories that satisfy the specified search criteria in the directory represented by the current object.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos(const String &searchPattern)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | The name pattern of the files and directories to search for |

### Return Value

The enumerable collection of shared pointers to [FileSystemInfo](../../filesysteminfo/) objects representing the found files and directories whose names match **searchPattern**

## DirectoryInfo::EnumerateFileSystemInfos(const String\&, SearchOption) method


Searches for the files and directories that satisfy the specified search criteria either in the directory represented by the current object or in the whole directory tree rooted in the directory represented by the current object.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos(const String &searchPattern, SearchOption searchOption)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | The name pattern of the files and directories to search for |
| searchOption | [SearchOption](../../searchoption/) | Specifies whether the search has to be performed in the directory represented by the current object only or in the whole directory tree rooted in the directory represented by the current object |

### Return Value

The enumerable collection of shared pointers to [FileSystemInfo](../../filesysteminfo/) objects representing the found files and directories whose names match **searchPattern**

## See Also

* Enum [SearchOption](../../searchoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)