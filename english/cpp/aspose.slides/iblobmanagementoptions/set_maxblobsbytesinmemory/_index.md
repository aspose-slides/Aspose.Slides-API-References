---
title: set_MaxBlobsBytesInMemory()
second_title: Aspose.Slides for C++ API Reference
description: Defines the maximum amount (in bytes) that all BLOBs in total may occupy in memory. First, all BLOBs loading into memory as default behavior and only when it reaches the limit defined by this property, other mechanisms (such as temporary files) can be involved. In terms of performance, the most efficient way is storing BLOBs in memory, but from the other side, it leads to a high memory consumption what may be undesirable. Using this property, you may set the optimal behavior for your environment or other requirements.
type: docs
weight: 92
url: /cpp/aspose.slides/iblobmanagementoptions/set_maxblobsbytesinmemory/
---
## IBlobManagementOptions::set_MaxBlobsBytesInMemory(**uint64_t**) method


Defines the maximum amount (in bytes) that all BLOBs in total may occupy in memory. First, all BLOBs loading into memory as default behavior and only when it reaches the limit defined by this property, other mechanisms (such as temporary files) can be involved. In terms of performance, the most efficient way is storing BLOBs in memory, but from the other side, it leads to a high memory consumption what may be undesirable. Using this property, you may set the optimal behavior for your environment or other requirements.

```cpp
virtual void Aspose::Slides::IBlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t value)=0
```

## Remarks


This value will be ignored if [IBlobManagementOptions::set_IsTemporaryFilesAllowed](../set_istemporaryfilesallowed/) is set to false. It makes no sense to limit the maximum BLOBs in memory, because if [IBlobManagementOptions::set_IsTemporaryFilesAllowed](../set_istemporaryfilesallowed/) is set to false, the memory is the only place where BLOBs can be stored. 

Default value is 629,145,600 bytes (600Mb).
## See Also

* Class [IBlobManagementOptions](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
