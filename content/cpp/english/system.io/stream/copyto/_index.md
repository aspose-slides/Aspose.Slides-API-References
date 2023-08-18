---
title: CopyTo()
second_title: Aspose.Slides for C++ API Reference
description: Copies bytes to the specified stream.
type: docs
weight: 170
url: /system.io/stream/copyto/
---
## Stream::CopyTo(const SharedPtr\<Stream\>\&) method


Copies bytes to the specified stream.

```cpp
void System::IO::Stream::CopyTo(const SharedPtr<Stream> &destination)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| destination | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../)\>\& | [Stream](../) to which data will be copied. |

## Stream::CopyTo(const SharedPtr\<Stream\>\&, int32_t) method


Copies bytes to the specified stream, using the specified buffer size.

```cpp
void System::IO::Stream::CopyTo(const SharedPtr<Stream> &destination, int32_t buffer_size)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| destination | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../)\>\& | [Stream](../) to which data will be copied. |
| buffer_size | **int32_t** | Size of the buffer. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)