---
title: max_blobs_bytes_in_memory property
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/blobmanagementoptions/max_blobs_bytes_in_memory/
weight: 30
---
## max_blobs_bytes_in_memory 속성
Defines the maximum total size (in bytes) that all BLOBs may occupy in memory. By default, all BLOBs
            are loaded into memory; only once this limit is reached are alternative mechanisms (such as temporary
            files) employed. Keeping BLOBs in memory maximizes performance but can lead to high memory usage. Use
            this property to tailor behavior to your environment or requirements.

### 비고

This property is ignored if [`BlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/ko/aspose.slides/blobmanagementoptions/is_temporary_files_allowed) is set to false, since memory is then
            the only storage location available and limiting in-memory BLOB usage has no effect.

### 정의:
```python
@property
def max_blobs_bytes_in_memory(self):
    ...

@max_blobs_bytes_in_memory.setter
def max_blobs_bytes_in_memory(self, value):
    ...
```

### 관련 항목
* 클래스 [`BlobManagementOptions`](/slides/python-net/ko/aspose.slides/blobmanagementoptions)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)