---
title: Open()
second_title: Aspose.Slides for C++ API Reference
description: Opens the file represented by the current object in the specified mode for reading and writing and with no sharing.
type: docs
weight: 183
url: /system.io/fileinfo/open/
---
## FileInfo::Open(FileMode) method


Opens the file represented by the current object in the specified mode for reading and writing and with no sharing.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | Specifies the mode in which to open the flie |

### Return Value

A [FileStream](../../filestream/) object associated with the file represented by the current object

## FileInfo::Open(FileMode, FileAccess) method


Opens the file represented by the current object in the specified mode, with the specified access type and with no sharing.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode, FileAccess access)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | Specifies the mode in which to open the flie |
| access | [FileAccess](../../fileaccess/) | The requested access type |

### Return Value

A [FileStream](../../filestream/) object associated with the file represented by the current object

## FileInfo::Open(FileMode, FileAccess, FileShare) method


Opens the file represented by the current object in the specified mode, with the specified access type and sharing option.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode, FileAccess access, FileShare share)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | Specifies the mode in which to open the flie |
| access | [FileAccess](../../fileaccess/) | The requested access type |
| share | [FileShare](../../fileshare/) | The type of access that other [FileStream](../../filestream/) objects have to the opened file |

### Return Value

A [FileStream](../../filestream/) object associated with the file represented by the current object

## See Also

* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Class [FileInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)