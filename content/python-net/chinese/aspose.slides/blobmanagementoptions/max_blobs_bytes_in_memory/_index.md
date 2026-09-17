---
title: max_blobs_bytes_in_memory property
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/blobmanagementoptions/max_blobs_bytes_in_memory/
weight: 30
---
## max_blobs_bytes_in_memory 属性
定义所有 BLOB 在内存中可能占用的最大总体大小（以字节为单位）。默认情况下，所有 BLOB
            已加载到内存中；只有当达到此限制时，才会采用替代机制（例如临时
            文件）。将 BLOB 保持在内存中可最大化性能，但可能导致高内存使用。使用
            此属性可根据您的环境或需求定制行为。

### 备注

如果 [`BlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/zh/aspose.slides/blobmanagementoptions/is_temporary_files_allowed) 被设置为 false，则此属性将被忽略，因为内存此时
            是唯一可用的存储位置，限制内存中 BLOB 的使用无效。

### 定义:
```python
@property
def max_blobs_bytes_in_memory(self):
    ...

@max_blobs_bytes_in_memory.setter
def max_blobs_bytes_in_memory(self, value):
    ...
```

### 另请参阅
* 类 [`BlobManagementOptions`](/slides/python-net/zh/aspose.slides/blobmanagementoptions)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)