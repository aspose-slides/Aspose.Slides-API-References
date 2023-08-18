---
title: EnumerateDirectories()
second_title: Aspose.Slides for C++ API Reference
description: Returns enumerable collection containing all directories located in the directory represented by the current object.
type: docs
weight: 105
url: /system.io/directoryinfo/enumeratedirectories/
---
## DirectoryInfo::EnumerateDirectories() method


Returns enumerable collection containing all directories located in the directory represented by the current object.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories()
```

## DirectoryInfo::EnumerateDirectories(const String\&) method


Searches for the directories that satisfy the specified search criteria in the directory represented by the current object.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories(const String &searchPattern)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | The name pattern of the directories to search for |

### Return Value

The enumerable collection of shared pointers to [DirectoryInfo](../) objects representing the found directories whose names match **searchPattern**

## DirectoryInfo::EnumerateDirectories(const String\&, SearchOption) method


Searches for the directories that satisfy the specified search criteria either in the directory represented by the current object or in the whole directory tree rooted in the directory represented by the current object.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories(const String &searchPattern, SearchOption searchOption)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | The name pattern of the directories to search for |
| searchOption | [SearchOption](../../searchoption/) | Specifies whether the search has to be performed in the directory represented by the current object only or in the whole directory tree rooted in the directory represented by the current object |

### Return Value

The enumerable collection of shared pointers to [DirectoryInfo](../) objects representing the found directories whose names match **searchPattern**

## See Also

* Enum [SearchOption](../../searchoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)