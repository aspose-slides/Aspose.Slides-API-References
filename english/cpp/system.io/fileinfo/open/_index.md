---
title: Open()
second_title: Aspose.Slides for C++ API Reference
description: Opens the file represented by the current object in the specified mode for reading and writing and with no sharing.
type: docs
weight: 183
url: /cpp/system.io/fileinfo/open/
---
## FileInfo::Open([FileMode](../../filemode/)) method


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

## See Also

* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Enum [FileMode](../../filemode/)
* Class [FileInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)
## FileInfo::Open([FileMode](../../filemode/), [FileAccess](../../fileaccess/)) method


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

## See Also

* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Class [FileInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)
## FileInfo::Open([FileMode](../../filemode/), [FileAccess](../../fileaccess/), [FileShare](../../fileshare/)) method


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

* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Class [FileInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)
