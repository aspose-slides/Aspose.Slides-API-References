---
title: GetDirectories()
second_title: Aspose.Slides for C++ API Reference
description: Returns an array containing shared pointers to DirectoryInfo objects representing all directories located in the directory represented by the current object.
type: docs
weight: 144
url: /system.io/directoryinfo/getdirectories/
---
## DirectoryInfo::GetDirectories() method


Returns an array containing shared pointers to [DirectoryInfo](../) objects representing all directories located in the directory represented by the current object.

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories()
```

## DirectoryInfo::GetDirectories(const String\&) method


Searches for the directories that satisfy the specified search criteria in the directory represented by the current object.

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories(const String &searchPattern)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | The name pattern of the directories to search for |

### Return Value

An array of shared pointers to [DirectoryInfo](../) objects representing the found directories whose names match **searchPattern**

## DirectoryInfo::GetDirectories(const String\&, SearchOption) method


Searches for the directories that satisfy the specified search criteria either in the directory represented by the current object or in the whole directory tree rooted in the directory represented by the current object.

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories(const String &searchPattern, SearchOption searchOption)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | The name pattern of the directories to search for |
| searchOption | [SearchOption](../../searchoption/) | Specifies whether the search has to be performed in the directory represented by the current object only or in the whole directory tree rooted in the directory represented by the current object |

### Return Value

An array of shared pointers to [DirectoryInfo](../) objects representing the found directories whose names match **searchPattern**

## See Also

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)