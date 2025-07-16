---
title: max_blobs_bytes_in_memory property
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/blobmanagementoptions/max_blobs_bytes_in_memory/
weight: 30
---


## max_blobs_bytes_in_memory property
Defines the maximum total size (in bytes) that all BLOBs may occupy in memory. By default, all BLOBs
            are loaded into memory; only once this limit is reached are alternative mechanisms (such as temporary
            files) employed. Keeping BLOBs in memory maximizes performance but can lead to high memory usage. Use
            this property to tailor behavior to your environment or requirements.


### Remarks

This property is ignored if [`BlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/aspose.slides/blobmanagementoptions/is_temporary_files_allowed) is set to false, since memory is then
            the only storage location available and limiting in-memory BLOB usage has no effect.

### Definition:
```python
@property
def max_blobs_bytes_in_memory(self):
    ...

@max_blobs_bytes_in_memory.setter
def max_blobs_bytes_in_memory(self, value):
    ...
```


### See Also
* class [`BlobManagementOptions`](/slides/python-net/aspose.slides/blobmanagementoptions)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

