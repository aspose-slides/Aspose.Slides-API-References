---
title: FileOptions
second_title: Aspose.Slides C++ API 參考
description: 表示用於建立 FileStream 物件的進階選項。
type: docs
weight: 521
url: /zh-hant/system.io/fileoptions/
---
## FileOptions enum

表示用於建立 [FileStream](../filestream/) 物件的進階選項。

```cpp
enum class FileOptions
```

### 值

| 名稱 | 值 | 描述 |
| --- | --- | --- |
| None | 0 | 沒有其他選項。 |
| Encrypted | 16384 | 檔案已加密。未實作。 |
| DeleteOnClose | 67108864 | 當檔案不再使用時，應自動刪除。 |
| SequentialScan | 134217728 | 檔案應該以順序方式存取。 |
| RandomAccess | 268435456 | 檔案以隨機方式存取。 |
| Asynchronous | 1073741824 | 檔案可用於非同步 I/O 操作。 |
| WriteThrough | n/a | 所有寫入應直接寫入磁碟，繞過任何中介快取。 |

## 另見

* 命名空間 [System::IO](../)
* 函式庫 [Aspose.Slides](../../)