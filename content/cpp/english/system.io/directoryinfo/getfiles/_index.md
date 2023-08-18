---
title: GetFiles()
second_title: Aspose.Slides for C++ API Reference
description: Returns an array containing shared pointers to FileInfo objects representing all directories located in the directory represented by the current object.
type: docs
weight: 157
url: /system.io/directoryinfo/getfiles/
---
## DirectoryInfo::GetFiles() method


Returns an array containing shared pointers to [FileInfo](../../fileinfo/) objects representing all directories located in the directory represented by the current object.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles()
```

## DirectoryInfo::GetFiles(const String\&) method


Searches for the files that satisfy the specified search criteria in the directory represented by the current object.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles(const String &searchPattern)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | The name pattern of the files to search for |

### Return Value

An array of shared pointers to [FileInfo](../../fileinfo/) objects representing the found files whose names match **searchPattern**

## DirectoryInfo::GetFiles(const String\&, SearchOption) method


Searches for the files that satisfy the specified search criteria either in the directory represented by the current object or in the whole directory tree rooted in the directory represented by the current object.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles(const String &searchPattern, SearchOption searchOption)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | The name pattern of the files to search for |
| searchOption | [SearchOption](../../searchoption/) | Specifies whether the search has to be performed in the directory represented by the current object only or in the whole directory tree rooted in the directory represented by the current object |

### Return Value

An array of shared pointers to [FileInfo](../../fileinfo/) objects representing the found files whose names match **searchPattern**

## See Also

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)