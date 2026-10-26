---
title: set_MaxBlobsBytesInMemory()
second_title: Aspose.Slides for C++ API 参考
description: 定义所有 BLOB 在内存中可能占用的最大总大小（单位为字节）。默认情况下，所有 BLOB 都会加载到内存中；只有在达到此限制后才会使用其他机制（例如临时文件）。将 BLOB 保持在内存中可最大化性能，但可能导致内存使用量增加。使用此属性可以根据您的环境或需求定制行为。
type: docs
weight: 92
url: /zh/aspose.slides/blobmanagementoptions/set_maxblobsbytesinmemory/
---
## BlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t) 方法

定义所有 BLOB 在内存中可能占用的最大总大小（单位为字节）。默认情况下，所有 BLOB 都会加载到内存中；只有在达到此限制后才会采用其他机制（例如临时文件）。将 BLOB 保持在内存中可以最大化性能，但可能导致内存使用量升高。使用此属性可以根据您的环境或需求调整行为。

```cpp
void Aspose::Slides::BlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t value) override
```

## 备注

如果 [BlobManagementOptions::set_IsTemporaryFilesAllowed](../set_istemporaryfilesallowed/) 被设置为 false，则此值将被忽略，因为此时内存是唯一可用的存储位置，限制内存中 BLOB 的使用没有效果。

默认值为 629,145,600 字节（600 MB）。

您可以将此属性设置为零，但仍会保留一小部分最小内存。

## 另见

* 类 [BlobManagementOptions](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)