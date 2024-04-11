---
title: max_blobs_bytes_in_memory property
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/blobmanagementoptions/max_blobs_bytes_in_memory/
weight: 30
---


## max_blobs_bytes_in_memory property
Defines the maximum amount (in bytes) that all BLOBs in total may occupy in memory. First, all BLOBs 
            loading into memory as default behavior and only when it reaches the limit defined by this property, 
            other mechanisms (such as temporary files) can be involved. In terms of performance, the most efficient 
            way is storing BLOBs in memory, but from the other side, it leads to a high memory consumption what 
            may be undesirable. Using this property, you may set the optimal behavior for your environment or 
            other requirements.
            
            This property will be ignored if [`BlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/aspose.slides/blobmanagementoptions#is_temporary_files_allowed) is
            set to false. It makes no sense to limit the maximum BLOBs in memory, because if 
            [`BlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/aspose.slides/blobmanagementoptions#is_temporary_files_allowed) is set to false, the memory is the only place 
            where BLOBs can be stored.
            Default value is 629,145,600 bytes (600Mb).

### Definition:
```python
@property
def max_blobs_bytes_in_memory(self):
    ...
@max_blobs_bytes_in_memory.setter
def max_blobs_bytes_in_memory(self, value):
    ...
```
