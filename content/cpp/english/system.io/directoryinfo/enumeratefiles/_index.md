---
title: EnumerateFiles()
second_title: Aspose.Slides for C++ API Reference
description: Returns enumerable collection containing all files located in the directory represented by the current object.
type: docs
weight: 118
url: /system.io/directoryinfo/enumeratefiles/
---
## DirectoryInfo::EnumerateFiles() method


Returns enumerable collection containing all files located in the directory represented by the current object.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles()
```

## DirectoryInfo::EnumerateFiles(const String\&) method


Searches for the files that satisfy the specified search criteria in the directory represented by the current object.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles(const String &searchPattern)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | The name pattern of the files to search for |

### Return Value

The enumerable collection of shared pointers to [FileInfo](../../fileinfo/) objects representing the found files whose names match **searchPattern**

## DirectoryInfo::EnumerateFiles(const String\&, SearchOption) method


Searches for the files that satisfy the specified search criteria either in the directory represented by the current object or in the whole directory tree rooted in the directory represented by the current object.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles(const String &searchPattern, SearchOption searchOption)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | The name pattern of the files to search for |
| searchOption | [SearchOption](../../searchoption/) | Specifies whether the search has to be performed in the directory represented by the current object only or in the whole directory tree rooted in the directory represented by the current object |

### Return Value

The enumerable collection of shared pointers to [FileInfo](../../fileinfo/) objects representing the found files whose names match **searchPattern**

## See Also

* Enum [SearchOption](../../searchoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)