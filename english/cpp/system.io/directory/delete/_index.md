---
title: Delete()
second_title: Aspose.Slides for C++ API Reference
description: Removes the specified file or directory. Does not throw.
type: docs
weight: 14
url: /cpp/system.io/directory/delete/
---
## Directory::Delete(const String\&, bool) method


Removes the specified file or directory. Does not throw.

```cpp
static void System::IO::Directory::Delete(const String &path, bool recursive=false)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | The path to the directory or file to be removed |
| recursive | **bool** | If **path** specifies a non-empty directory then **recursive** specifies if if all directory's content should be removed recursively; if the directory specified by **path** is not empty and **recursive** is 'false' then the operation fails |

## See Also

* Class [String](../../../system/string/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)