---
title: GetFileSystemEntries()
second_title: Aspose.Slides for C++ API Reference
description: Searches for the files and directories that satisfy the specified search criteria either in the specified directory or in the whole directory tree rooted in the specified directory.
type: docs
weight: 92
url: /cpp/system.io/directory/getfilesystementries/
---
## Directory::GetFileSystemEntries(const String\&, const String\&, SearchOption) method


Searches for the files and directories that satisfy the specified search criteria either in the specified directory or in the whole directory tree rooted in the specified directory.

```cpp
static ArrayPtr<String> System::IO::Directory::GetFileSystemEntries(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Full or relative path to the directory to search in |
| searchPattern | const [String](../../../system/string/)\& | The name pattern of the files and directories to search for |
| searchOption | [SearchOption](../../searchoption/) | Specifies whether the search has to be performed in the specified directory only or in the whole directory tree rooted in the specified directory |

### Return Value

An array of full paths of the found files and directories whose names match **searchPattern**

## See Also

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)