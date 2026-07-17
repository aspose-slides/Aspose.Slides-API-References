---
title: set_MaxBlobsBytesInMemory()
second_title: Aspose.Slides C++ API 参考
description: 定义所有 BLOB 在内存中可能占用的最大总大小（字节）。默认情况下，所有 BLOB 都会加载到内存中；仅当达到此限制时，才会使用替代机制（例如临时文件）。将 BLOB 保持在内存中可最大化性能，但可能导致高内存使用。使用此属性可根据您的环境或需求定制行为。
type: docs
weight: 92
url: /zh/aspose.slides/iblobmanagementoptions/set_maxblobsbytesinmemory/
---
## IBlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t) 方法

定义所有 BLOB 在内存中可能占用的最大总大小（字节）。默认情况下，所有 BLOB 都会加载到内存中；仅当达到此限制时，才会使用替代机制（例如临时文件）。将 BLOB 保持在内存中可最大化性能，但可能导致高内存使用。使用此属性可根据您的环境或需求定制行为。

```cpp
virtual void Aspose::Slides::IBlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t value)=0
```

## 备注

如果 [IBlobManagementOptions::set_IsTemporaryFilesAllowed](../set_istemporaryfilesallowed/) 被设置为 false，则此值被忽略，因为此时内存是唯一可用的存储位置，限制内存中 BLOB 的使用没有效果。 

默认值为 629,145,600 字节（600 MB）。 

您可以将此属性设置为零，但仍会保留少量最小内存。 

## 另见

* 类 [IBlobManagementOptions](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)