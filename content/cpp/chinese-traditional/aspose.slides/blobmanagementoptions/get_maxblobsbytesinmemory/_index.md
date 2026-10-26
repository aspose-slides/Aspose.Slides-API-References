---
title: get_MaxBlobsBytesInMemory()
second_title: Aspose.Slides for C++ API 參考文件
description: 定義所有 BLOB 在記憶體中可能佔用的最大總大小（以位元組為單位）。預設情況下，所有 BLOB 都會載入記憶體；僅在達到此限制時，才會使用替代機制（例如暫存檔）。將 BLOB 保持在記憶體中可最大化效能，但可能導致記憶體使用量過高。使用此屬性可依您的環境或需求調整行為。
type: docs
weight: 79
url: /zh-hant/aspose.slides/blobmanagementoptions/get_maxblobsbytesinmemory/
---
## BlobManagementOptions::get_MaxBlobsBytesInMemory() 方法

定義所有 BLOB 在記憶體中可能佔用的最大總大小（以位元組為單位）。預設情況下，所有 BLOB 都會載入記憶體；僅在達到此限制時，才會使用替代機制（例如暫存檔）。將 BLOB 保持在記憶體中可最大化效能，但可能導致記憶體使用量過高。使用此屬性可依您的環境或需求調整行為。

```cpp
uint64_t Aspose::Slides::BlobManagementOptions::get_MaxBlobsBytesInMemory() override
```

## 備註

如果 [BlobManagementOptions::set_IsTemporaryFilesAllowed](../set_istemporaryfilesallowed/) 設為 false，則此值會被忽略，因為記憶體此時是唯一可用的儲存位置，限制記憶體中 BLOB 的使用不會產生任何效果。

預設值為 629,145,600 位元組（600 MB）。

您可以將此屬性設為 0，但仍會保留少量的最低記憶體需求。

## 另請參閱

* 類別 [BlobManagementOptions](../)
* 名稱空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)