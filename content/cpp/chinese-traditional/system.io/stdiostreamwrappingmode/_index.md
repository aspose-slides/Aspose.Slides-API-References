---
title: STDIOStreamWrappingMode
second_title: Aspose.Slides C++ API 參考
description: "指定包裝器在類似 std::iostreams 的串流上執行的 I/O 操作模式。"
type: docs
weight: 573
url: /zh-hant/system.io/stdiostreamwrappingmode/
---
## STDIOStreamWrappingMode enum

指定包裝器在類似 std::iostreams 的串流上執行的 I/O 操作模式。

```cpp
enum class STDIOStreamWrappingMode
```

### 值

| 名稱 | 值 | 說明 |
| --- | --- | --- |
| Binary | 0 | 一種允許輸入操作將 char_type 類型的流資料解碼為位元組，並將位元組編碼為 char_type 資料以供輸出操作的模式。 |
| Conversion | 1 | 一種允許輸入操作將流資料從 char_type 類型轉換為 **uint8_t** 類型，並在輸出操作時反向轉換的模式。 |

## 另請參閱

* 命名空間 [System::IO](../)
* 函式庫 [Aspose.Slides](../../)