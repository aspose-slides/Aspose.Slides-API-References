---
title: UnmanagedMemoryStream()
second_title: Aspose.Slides for C++ API Reference
description: Constructs a new instance of UnmanagedMemoryStream.
type: docs
weight: 118
url: /system.io/unmanagedmemorystream/unmanagedmemorystream/
---
## UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *, int64_t) constructor


Constructs a new instance of [UnmanagedMemoryStream](../).

```cpp
System::IO::UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *pointer, int64_t length)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| pointer | **uint8_t** * | A pointer to unmanaged buffer |
| length | **int64_t** | The size of unmanaged buffer in bytes |

## UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *, int64_t, int64_t, FileAccess) constructor


Constructs a new instance of [UnmanagedMemoryStream](../).

```cpp
System::IO::UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *pointer, int64_t length, int64_t capacity, FileAccess access)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| pointer | **uint8_t** * | A pointer to unmanaged buffer |
| length | **int64_t** | The size of unmanaged buffer in bytes |
| capacity | **int64_t** | The total amount of memory assigned to the stream |
| access | [FileAccess](../../fileaccess/) | Specifies if the stream should be read-only, write-onle or both |

## See Also

* Enum [FileAccess](../../fileaccess/)
* Class [UnmanagedMemoryStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)