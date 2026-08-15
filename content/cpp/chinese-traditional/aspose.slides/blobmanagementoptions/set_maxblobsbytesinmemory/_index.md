---
title: set_MaxBlobsBytesInMemory()
second_title: Aspose.Slides for C++ API 參考
description: 定義所有 BLOB 在記憶體中可能佔用的最大總大小（以位元組為單位）。預設情況下，所有 BLOB 會被載入記憶體；只有在達到此限制時，才會使用其他機制（例如暫存檔案）。將 BLOB 保持在記憶體中可提升效能，但可能導致記憶體使用量過高。使用此屬性可根據您的環境或需求調整行為。
type: docs
weight: 92
url: /zh-hant/aspose.slides/blobmanagementoptions/set_maxblobsbytesinmemory/
---
## BlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t) 方法


定義所有 BLOB 在記憶體中可能佔用的最大總大小（以位元組為單位）。預設情況下，所有 BLOB 會被載入記憶體；只有在達到此限制時，才會使用其他機制（例如暫存檔案）。將 BLOB 保持在記憶體中可提升效能，但可能導致記憶體使用量過高。使用此屬性可依據您的環境或需求調整行為。

```cpp
void Aspose::Slides::BlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t value) override
```

## 備註


如果[BlobManagementOptions::set_IsTemporaryFilesAllowed](../set_istemporaryfilesallowed/) 設為 false，則此值會被忽略，因為此時記憶體是唯一可用的儲存位置，限制記憶體中的 BLOB 使用不會產生任何效果。 

預設值為 629,145,600 位元組 (600 MB)。 

您可以將此屬性設為零，但仍會保留少量的最小記憶體。 
## 參見

* 類別 [BlobManagementOptions](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)