---
title: Copy()
second_title: Aspose.Slides for C++ API Reference
description: Copies the specified file to the specified location. If the destination file already exists, a parameter specifies if it should be overwritten.
type: docs
weight: 40
url: /cpp/system.io/file/copy/
---
## File::Copy(const String\&, const String\&, bool) method


Copies the specified file to the specified location. If the destination file already exists, a parameter specifies if it should be overwritten.

```cpp
static void System::IO::File::Copy(const String &sourceFileName, const String &destFileName, bool overwrite=false)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| sourceFileName | const [String](../../../system/string/)\& | A path of the file to copy |
| destFileName | const [String](../../../system/string/)\& | A path of the new location of the file to copy |
| overwrite | **bool** | True if the existing destination file should be overwritten, false if copying should fail if the destination file already exists |

## See Also

* Class [String](../../../system/string/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)