---
title: SystemIOStreamWrappingMode
second_title: Aspose.Slides for C++ API 參考
description: "指定封裝器在類似 System::IO::Stream 的串流上執行 I/O 操作的模式。"
type: docs
weight: 599
url: /zh-hant/system.io/systemiostreamwrappingmode/
---
## SystemIOStreamWrappingMode 列舉

指定封裝器在 [System::IO::Stream](../stream/) 類似的串流上執行 I/O 操作的模式。

```cpp
enum class SystemIOStreamWrappingMode
```

### 值

| 名稱 | 值 | 說明 |
| --- | --- | --- |
| Binary | 0 | 允許輸入操作將串流位元組編碼為 char_type 資料，並在輸出操作時將 char_type 資料解碼回串流位元組的模式。 |
| Conversion | 1 | 允許輸入操作將串流位元組從 **uint8_t** 類型轉換為 char_type 類型，並在輸出操作時反向轉換的模式。 |

## 另請參閱

* 命名空間 [System::IO](../)
* 函式庫 [Aspose.Slides](../../)