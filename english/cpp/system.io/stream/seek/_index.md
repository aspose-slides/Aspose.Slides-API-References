---
title: Seek()
second_title: Aspose.Slides for C++ API Reference
description: Sets the position of the stream represented by the current object.
type: docs
weight: 53
url: /cpp/system.io/stream/seek/
---
## Stream::Seek(**int64_t**, [SeekOrigin](../../seekorigin/)) method


Sets the position of the stream represented by the current object.

```cpp
virtual int64_t System::IO::Stream::Seek(int64_t offset, SeekOrigin origin)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| offset | **int64_t** | The byte offset relative to a position specified by **origin** |
| origin | [SeekOrigin](../../seekorigin/) | Specifies the position from which and the direction toward which the offset is calculated |

### Return Value

The new position of the stream

## See Also

* Enum [SeekOrigin](../../seekorigin/)
* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)
