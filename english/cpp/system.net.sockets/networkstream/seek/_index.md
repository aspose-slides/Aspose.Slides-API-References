---
title: Seek()
second_title: Aspose.Slides for C++ API Reference
description: Sets the position of the stream represented by the current object.
type: docs
weight: 183
url: /cpp/system.net.sockets/networkstream/seek/
---
## NetworkStream::Seek(**int64_t**, [IO::SeekOrigin](../../../system.io/seekorigin/)) method


Sets the position of the stream represented by the current object.

```cpp
int64_t System::Net::Sockets::NetworkStream::Seek(int64_t offset, IO::SeekOrigin origin) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| offset | **int64_t** | The byte offset relative to a position specified by **origin** |
| origin | [IO::SeekOrigin](../../../system.io/seekorigin/) | Specifies the position from which and the direction toward which the offset is calculated |

### Return Value

The new position of the stream

## See Also

* Enum [SeekOrigin](../../../system.io/seekorigin/)
* Class [NetworkStream](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)
