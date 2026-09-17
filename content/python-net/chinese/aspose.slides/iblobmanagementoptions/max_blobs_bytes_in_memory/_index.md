---
title: max_blobs_bytes_in_memory property
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/iblobmanagementoptions/max_blobs_bytes_in_memory/
weight: 20
---
## max_blobs_bytes_in_memory 属性
定义所有 BLOB 在内存中可能占用的最大总大小（字节）。默认情况下，所有 BLOB 都会加载到内存中；只有在达到此限制时，才会使用替代机制（例如临时文件）。将 BLOB 保持在内存中可最大化性能，但可能导致高内存使用。使用此属性可根据您的环境或需求定制行为。


### 备注

如果 [`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/zh/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) 设置为 false，则会忽略此属性，因为此时内存是唯一可用的存储位置，对内存中 BLOB 使用的限制没有效果。

### 定义:
```python
@property
def max_blobs_bytes_in_memory(self):
    ...

@max_blobs_bytes_in_memory.setter
def max_blobs_bytes_in_memory(self, value):
    ...
```


### 另请参见
* 类 [`IBlobManagementOptions`](/slides/python-net/zh/aspose.slides/iblobmanagementoptions)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)