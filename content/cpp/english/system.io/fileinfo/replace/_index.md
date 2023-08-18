---
title: Replace()
second_title: Aspose.Slides for C++ API Reference
description: Replaces the contents of a specified destination file with the file represented by the current FileInfo object and creates a backup of the replaced file.
type: docs
weight: 131
url: /system.io/fileinfo/replace/
---
## FileInfo::Replace(const String\&, const String\&) method


Replaces the contents of a specified destination file with the file represented by the current [FileInfo](../) object and creates a backup of the replaced file.

```cpp
FileInfoPtr System::IO::FileInfo::Replace(const String &destinationFileName, const String &destinationBackupFileName)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| destinationFileName | const [String](../../../system/string/)\& | A name of the file to replace |
| destinationBackupFileName | const [String](../../../system/string/)\& | A name of the backup file |

### Return Value

A FileInfor object that represents the file pointed to by **destinationFileName**

## FileInfo::Replace(const String\&, const String\&, bool) method


Replaces the contents of a specified destination file with the file represented by the current [FileInfo](../) object and creates a backup of the replaced file.

```cpp
FileInfoPtr System::IO::FileInfo::Replace(const String &destinationFileName, const String &destinationBackupFileName, bool ignoreMetadataErrors)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| destinationFileName | const [String](../../../system/string/)\& | A name of the file to replace |
| destinationBackupFileName | const [String](../../../system/string/)\& | A name of the backup file |
| ignoreMetadataErrors | **bool** | Specifies if the merge errors from the replaced file to the replacement file should be ignored (true) or not (false) |

### Return Value

A FileInfor object that represents the file pointed to by **destinationFileName**

## See Also

* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [String](../../../system/string/)
* Class [FileInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)