---
title: FileMode
second_title: Aspose.Slides for C++ API 參考
description: 指定檔案應如何開啟。
type: docs
weight: 508
url: /zh-hant/system.io/filemode/
---
## FileMode 列舉

指定檔案開啟方式。

```cpp
enum class FileMode
```

### 值

| 名稱 | 值 | 說明 |
| --- | --- | --- |
| CreateNew | 1 | 建立新檔案。如果檔案已存在，會拋出例外。 |
| Create | 2 | 建立新檔案。如果檔案已存在，會覆寫。 |
| Open | 3 | 開啟已存在的檔案。如果檔案不存在，會拋出例外。 |
| OpenOrCreate | 4 | 開啟已存在的檔案，若不存在則建立新檔案。 |
| Truncate | 5 | 開啟已存在的檔案並將其截斷為空。如果檔案不存在，會拋出例外。 |
| Append | 6 | 開啟已存在的檔案並移至檔案尾端，若不存在則建立新檔案。 |

## 另見

* 命名空間 [System::IO](../)
* 程式庫 [Aspose.Slides](../../)