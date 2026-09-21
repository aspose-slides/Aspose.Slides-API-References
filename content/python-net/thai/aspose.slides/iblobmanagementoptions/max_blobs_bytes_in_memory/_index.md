---
title: max_blobs_bytes_in_memory property
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/iblobmanagementoptions/max_blobs_bytes_in_memory/
weight: 20
---
## max_blobs_bytes_in_memory คุณสมบัติ
Defines the maximum total size (in bytes) that all BLOBs may occupy in memory. By default, all BLOBs
            are loaded into memory; only once this limit is reached are alternative mechanisms (such as temporary
            files) employed. Keeping BLOBs in memory maximizes performance but can lead to high memory usage. Use
            this property to tailor behavior to your environment or requirements.

### หมายเหตุ

This property is ignored if [`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/th/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) is set to false, since memory is then
            the only storage location available and limiting in-memory BLOB usage has no effect.

### คำนิยาม:
```python
@property
def max_blobs_bytes_in_memory(self):
    ...

@max_blobs_bytes_in_memory.setter
def max_blobs_bytes_in_memory(self, value):
    ...
```

### ดูเพิ่มเติม
* คลาส [`IBlobManagementOptions`](/slides/python-net/th/aspose.slides/iblobmanagementoptions)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)