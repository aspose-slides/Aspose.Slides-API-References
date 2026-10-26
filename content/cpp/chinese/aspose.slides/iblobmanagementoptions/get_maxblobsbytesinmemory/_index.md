---
title: get_MaxBlobsBytesInMemory()
second_title: Aspose.Slides C++ API 参考
description: 定义所有 BLOB 在内存中可能占用的最大总大小（以字节为单位）。默认情况下，所有 BLOB 都会加载到内存中；只有在达到此限制后，才会使用替代机制（例如临时文件）。将 BLOB 保持在内存中可最大化性能，但可能导致内存使用量高。使用此属性可根据您的环境或需求调整行为。
type: docs
weight: 79
url: /zh/aspose.slides/iblobmanagementoptions/get_maxblobsbytesinmemory/
---
## IBlobManagementOptions::get_MaxBlobsBytesInMemory() 方法


定义所有 BLOB 在内存中可能占用的最大总大小（以字节为单位）。默认情况下，所有 BLOB 都会加载到内存中；只有在达到此限制后，才会使用替代机制（例如临时文件）。将 BLOB 保持在内存中可最大化性能，但可能导致内存使用量高。使用此属性可根据您的环境或需求调整行为。

```cpp
virtual uint64_t Aspose::Slides::IBlobManagementOptions::get_MaxBlobsBytesInMemory()=0
```

## 备注


如果 [IBlobManagementOptions::set_IsTemporaryFilesAllowed](../set_istemporaryfilesallowed/) 设置为 false，则此值将被忽略，因为此时内存是唯一可用的存储位置，限制内存中的 BLOB 使用不会产生任何效果。

默认值为 629,145,600 字节（600 MB）。

您可以将此属性设置为零，但仍会保留少量的最小内存。

## 另见

* 类 [IBlobManagementOptions](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)