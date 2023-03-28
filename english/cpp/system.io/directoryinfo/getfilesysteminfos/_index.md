---
title: GetFileSystemInfos()
second_title: Aspose.Slides for C++ API Reference
description: Returns an array containing shared pointers to FileSystemInfo objects representing all files and directories located in the directory represented by the current object.
type: docs
weight: 170
url: /cpp/system.io/directoryinfo/getfilesysteminfos/
---
## DirectoryInfo::GetFileSystemInfos() method


Returns an array containing shared pointers to [FileSystemInfo](../../filesysteminfo/) objects representing all files and directories located in the directory represented by the current object.

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos()
```

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)
## DirectoryInfo::GetFileSystemInfos(const [String](../../../system/string/)\&) method


Searches for the files and directories that satisfy the specified search criteria in the directory represented by the current object.

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos(const String &searchPattern)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | The name pattern of the files and directories to search for |

### Return Value

An array of shared pointers to [FileSystemInfo](../../filesysteminfo/) objects representing the found files and directories whose names match **searchPattern**

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Class [String](../../../system/string/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)
## DirectoryInfo::GetFileSystemInfos(const [String](../../../system/string/)\&, [SearchOption](../../searchoption/)) method


Searches for the files and directories that satisfy the specified search criteria either in the directory represented by the current object or in the whole directory tree rooted in the directory represented by the current object.

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos(const String &searchPattern, SearchOption searchOption)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | The name pattern of the files and directories to search for |
| searchOption | [SearchOption](../../searchoption/) | Specifies whether the search has to be performed in the directory represented by the current object only or in the whole directory tree rooted in the directory represented by the current object |

### Return Value

An array of shared pointers to [FileSystemInfo](../../filesysteminfo/) objects representing the found files and directories whose names match **searchPattern**

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Class [String](../../../system/string/)
* Enum [SearchOption](../../searchoption/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)
