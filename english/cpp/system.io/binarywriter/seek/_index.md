---
title: Seek()
second_title: Aspose.Slides for C++ API Reference
description: Sets the position of the stream represented by the current object.
type: docs
weight: 79
url: /cpp/system.io/binarywriter/seek/
---
## BinaryWriter::Seek(int, [System::IO::SeekOrigin](../../seekorigin/)) method


Sets the position of the stream represented by the current object.

```cpp
int64_t System::IO::BinaryWriter::Seek(int offset, System::IO::SeekOrigin origin=System::IO::SeekOrigin::Begin)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| offset | int | The byte offset relative to a position specified by **origin** |
| origin | [System::IO::SeekOrigin](../../seekorigin/) | Specifies the position from which and the direction toward which the offset is calculated |

### Return Value

The new position of the stream

## See Also

* Enum [SeekOrigin](../../seekorigin/)
* Class [BinaryWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)
