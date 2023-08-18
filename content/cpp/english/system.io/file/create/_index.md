---
title: Create()
second_title: Aspose.Slides for C++ API Reference
description: Creates a new file (or overwrites existing) and opens it for reading and writing access using the specified buffer size and options.
type: docs
weight: 53
url: /system.io/file/create/
---
## File::Create(const String\&, int32_t, FileOptions) method


Creates a new file (or overwrites existing) and opens it for reading and writing access using the specified buffer size and options.

```cpp
static FileStreamPtr System::IO::File::Create(const String &path, int32_t bufferSize=DefaultBufferSize, FileOptions options=FileOptions::None)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | The path of the file to create or overwrite |
| bufferSize | **int32_t** | The number of bytes buffered when reading from and writing to the file |
| options | [FileOptions](../../fileoptions/) | Specifies how to create or overwrite the file |

### Return Value

A shared pointer to the [FileStream](../../filestream/) object associated with the specified file

## See Also

* Enum [FileOptions](../../fileoptions/)
* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Class [String](../../../system/string/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)