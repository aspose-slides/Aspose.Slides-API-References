---
title: TransformFinalBlock()
second_title: Aspose.Slides for C++ API 參考
description: 處理最後一塊資料並計算雜湊值。
type: docs
weight: 79
url: /zh-hant/system.security.cryptography/hashalgorithm/transformfinalblock/
---
## HashAlgorithm::TransformFinalBlock(ArrayPtr\<uint8_t\>, int, int) 方法

處理最後一塊資料並計算雜湊值。

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::TransformFinalBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) 用於讀取資料。 |
| inputOffset | int | 輸入緩衝區的偏移量。 |
| inputCount | int | 要處理的位元組數。 |

### 返回值

整個資料序列的雜湊值。

## 參見

* 型別別名 [ArrayPtr](../../../system/arrayptr/)
* 類別 [HashAlgorithm](../)
* 命名空間 [System::Security::Cryptography](../../)
* 函式庫 [Aspose.Slides](../../../)