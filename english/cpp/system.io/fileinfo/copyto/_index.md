---
title: CopyTo()
second_title: Aspose.Slides for C++ API Reference
description: Copies the file represented by the current object to the specified location. If the destination file already exists, the copying fails.
type: docs
weight: 105
url: /cpp/system.io/fileinfo/copyto/
---
## FileInfo::CopyTo(const [String](../../../system/string/)\&) method


Copies the file represented by the current object to the specified location. If the destination file already exists, the copying fails.

```cpp
FileInfoPtr System::IO::FileInfo::CopyTo(const String &destFileName)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| destFileName | const [String](../../../system/string/)\& | The destination file name |

### Return Value

A [FileInfo](../) object that represents the copy

## See Also

* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [String](../../../system/string/)
* Class [FileInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)
## FileInfo::CopyTo(const [String](../../../system/string/)\&, **bool**) method


Copies the file represented by the current object to the specified location. A parameter specifies if existing destination file should be overwritten.

```cpp
FileInfoPtr System::IO::FileInfo::CopyTo(const String &destFileName, bool overwrite)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| destFileName | const [String](../../../system/string/)\& | The destination file name |
| overwrite | **bool** | True if the existing destination file should be overwritten, false if copying should fail if the destination file already exists |

### Return Value

A [FileInfo](../) object that represents the copy

## See Also

* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [String](../../../system/string/)
* Class [FileInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)
