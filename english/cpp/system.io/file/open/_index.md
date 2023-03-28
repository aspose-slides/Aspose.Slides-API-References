---
title: Open()
second_title: Aspose.Slides for C++ API Reference
description: Opens the specified file in the specified mode for reading and writing and with no sharing.
type: docs
weight: 235
url: /cpp/system.io/file/open/
---
## File::Open(const [String](../../../system/string/)\&, [FileMode](../../filemode/)) method


Opens the specified file in the specified mode for reading and writing and with no sharing.

```cpp
static FileStreamPtr System::IO::File::Open(const String &path, FileMode mode)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | The path of the file to open |
| mode | [FileMode](../../filemode/) | Specifies the mode in which to open the file |

### Return Value

A [FileStream](../../filestream/) object associated with the opened file

## See Also

* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Class [String](../../../system/string/)
* Enum [FileMode](../../filemode/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)
## File::Open(const [String](../../../system/string/)\&, [FileMode](../../filemode/), [FileAccess](../../fileaccess/), [FileShare](../../fileshare/)) method


Opens the specified file in the specified mode, with the specified access type and sharing option.

```cpp
static FileStreamPtr System::IO::File::Open(const String &path, FileMode mode, FileAccess access, FileShare share=FileShare::None)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | The path of the file to open |
| mode | [FileMode](../../filemode/) | Specifies the mode in which to open the file |
| access | [FileAccess](../../fileaccess/) | The requested access type |
| share | [FileShare](../../fileshare/) | The type of access that other [FileStream](../../filestream/) objects have to the opened file |

### Return Value

A [FileStream](../../filestream/) object associated with the opened file

## See Also

* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Class [String](../../../system/string/)
* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)
