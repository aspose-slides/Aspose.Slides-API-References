---
title: max_blobs_bytes_in_memory property
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/blobmanagementoptions/max_blobs_bytes_in_memory/
weight: 30
---
## max_blobs_bytes_in_memory 屬性
定義所有 BLOB 在記憶體中可能佔用的最大總大小（以位元組為單位）。預設情況下，所有 BLOB 會被載入記憶體；僅當達到此限制時，才會使用替代機制（例如暫存檔案）。將 BLOB 保持在記憶體中可以提升效能，但可能導致記憶體使用量過高。使用此屬性可依您的環境或需求調整行為。

### 備註
如果 [`BlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/zh-hant/aspose.slides/blobmanagementoptions/is_temporary_files_allowed) 被設為 false，則此屬性會被忽略，因為此時記憶體是唯一可用的儲存位置，限制記憶體中的 BLOB 使用將不會產生任何效用。

### 定義:
```python
@property
def max_blobs_bytes_in_memory(self):
    ...

@max_blobs_bytes_in_memory.setter
def max_blobs_bytes_in_memory(self, value):
    ...
```

### 另請參閱
* 類別 [`BlobManagementOptions`](/slides/python-net/zh-hant/aspose.slides/blobmanagementoptions)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)