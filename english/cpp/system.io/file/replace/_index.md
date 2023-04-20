---
title: Replace()
second_title: Aspose.Slides for C++ API Reference
description: Replaces the contents of a one file with another and creates a backup of the replaced file.
type: docs
weight: 339
url: /cpp/system.io/file/replace/
---
## File::Replace(const String\&, const String\&, const String\&, bool) method


Replaces the contents of a one file with another and creates a backup of the replaced file.

```cpp
static void System::IO::File::Replace(const String &sourceFileName, const String &destinationFileName, const String &destinationBackupFileName, bool ignoreMetadataErrors=1)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| sourceFileName | const [String](../../../system/string/)\& | A name of the file to replace with |
| destinationFileName | const [String](../../../system/string/)\& | A name of the file to replace |
| destinationBackupFileName | const [String](../../../system/string/)\& | A name of the backup file |
| ignoreMetadataErrors | **bool** | Specifies if the merge errors from the replaced file to the replacement file should be ignored (true) or not (false) |

## See Also

* Class [String](../../../system/string/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)