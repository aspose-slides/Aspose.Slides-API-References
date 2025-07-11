---
title: MaxBlobsBytesInMemory
second_title: Aspose.Sildes for .NET API Reference
description: 定义了所有 BLOB 在内存中可占用的最大字节数。首先，所有 BLOB 默认行为是加载到内存中，仅当达到此属性定义的限制时，其他机制（如临时文件）才能介入。在性能方面，最有效的方法是将 BLOB 存储在内存中，但另一方面，这会导致高内存消耗，这可能是不可取的。使用此属性，您可以为您的环境或其他要求设置最佳行为。如果 IsTemporaryFilesAllowed../istemporaryfilesallowed 设置为 false，则此属性将被忽略。限制内存中的最大 BLOB 没有意义，因为如果 IsTemporaryFilesAllowed../istemporaryfilesallowed 设置为 false，内存是唯一可以存储 BLOB 的地方。默认值为 629145600 字节（600Mb）。
type: docs
weight: 30
url: /zh/aspose.slides/blobmanagementoptions/maxblobsbytesinmemory/
---

## BlobManagementOptions.MaxBlobsBytesInMemory property

定义了所有 BLOB 在内存中可占用的最大字节数。首先，所有 BLOB 默认行为是加载到内存中，仅当达到此属性定义的限制时，其他机制（如临时文件）才能介入。在性能方面，最有效的方法是将 BLOB 存储在内存中，但另一方面，这会导致高内存消耗，这可能是不可取的。使用此属性，您可以为您的环境或其他要求设置最佳行为。如果 [`IsTemporaryFilesAllowed`](../istemporaryfilesallowed) 设置为 false，则此属性将被忽略。限制内存中的最大 BLOB 没有意义，因为如果 [`IsTemporaryFilesAllowed`](../istemporaryfilesallowed) 设置为 false，内存是唯一可以存储 BLOB 的地方。默认值为 629145600 字节（600Mb）。

```csharp
public ulong MaxBlobsBytesInMemory { get; set; }
```

### See Also

* class [BlobManagementOptions](../../blobmanagementoptions)
* namespace [Aspose.Slides](../../blobmanagementoptions)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->