---
title: max_blobs_bytes_in_memory property
second_title: Aspose.Slides for Python 透過 .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/iblobmanagementoptions/max_blobs_bytes_in_memory/
weight: 20
---
## max_blobs_bytes_in_memory 屬性
定義所有 BLOB 在記憶體中可能佔用的最大總大小（以位元組為單位）。預設情況下，所有 BLOB 都會載入記憶體；只有當達到此限制時，才會採用替代機制（例如暫存檔案）。將 BLOB 保留在記憶體中可最大化效能，但可能導致記憶體使用量過高。請使用此屬性根據您的環境或需求調整行為。

### 備註
若 [`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/zh-hant/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) 被設為 false，則此屬性會被忽略，因為此時記憶體是唯一可用的儲存位置，限制記憶體中的 BLOB 使用不會產生任何效果。

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
* 類別 [`IBlobManagementOptions`](/slides/python-net/zh-hant/aspose.slides/iblobmanagementoptions)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)