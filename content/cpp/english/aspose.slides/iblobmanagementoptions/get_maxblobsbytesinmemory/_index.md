---
title: get_MaxBlobsBytesInMemory()
second_title: Aspose.Slides for C++ API Reference
description: Defines the maximum total size (in bytes) that all BLOBs may occupy in memory. By default, all BLOBs are loaded into memory; only once this limit is reached are alternative mechanisms (such as temporary files) employed. Keeping BLOBs in memory maximizes performance but can lead to high memory usage. Use this property to tailor behavior to your environment or requirements.
type: docs
weight: 79
url: /aspose.slides/iblobmanagementoptions/get_maxblobsbytesinmemory/
---
## IBlobManagementOptions::get_MaxBlobsBytesInMemory() method


Defines the maximum total size (in bytes) that all BLOBs may occupy in memory. By default, all BLOBs are loaded into memory; only once this limit is reached are alternative mechanisms (such as temporary files) employed. Keeping BLOBs in memory maximizes performance but can lead to high memory usage. Use this property to tailor behavior to your environment or requirements.

```cpp
virtual uint64_t Aspose::Slides::IBlobManagementOptions::get_MaxBlobsBytesInMemory()=0
```

## Remarks


This value is ignored if [IBlobManagementOptions::set_IsTemporaryFilesAllowed](../set_istemporaryfilesallowed/) is set to false, since memory is then the only storage location available and limiting in-memory BLOB usage has no effect. 

The default value is 629,145,600 bytes (600 MB). 

You may set this property to zero, but a small minimum amount of memory will still be reserved. 
## See Also

* Class [IBlobManagementOptions](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)