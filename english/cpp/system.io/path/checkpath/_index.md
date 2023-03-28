---
title: CheckPath()
second_title: Aspose.Slides for C++ API Reference
description: Determines if the specified path is valid by checking if it contains invalid characters. An exception is thrown if the path contains invalid characters.
type: docs
weight: 209
url: /cpp/system.io/path/checkpath/
---
## Path::CheckPath(const [String](../../../system/string/)\&, const [String](../../../system/string/)\&, **bool**) method


Determines if the specified path is valid by checking if it contains invalid characters. An exception is thrown if the path contains invalid characters.

```cpp
static void System::IO::Path::CheckPath(const String &path, const String &msg=s_msg_path, bool allow_empty=1)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | The path to check |
| msg | const [String](../../../system/string/)\& | The message to pass to the exception object's constructor |
| allow_empty | **bool** | Specifies whether an empty or null string should be considered a correct path (true) or not (false); if this parameter is false and **path** is empty an ArgumentException is thrown; if this parameter is false and **path** is null an ArgumentNullException is thrown |

## See Also

* Class [String](../../../system/string/)
* Class [Path](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)
