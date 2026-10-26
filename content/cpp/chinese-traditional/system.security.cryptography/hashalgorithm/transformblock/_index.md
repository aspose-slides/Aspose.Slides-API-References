---
title: TransformBlock()
second_title: Aspose.Slides for C++ API 參考
description: 處理資料區塊並將資料複製到輸出陣列。
type: docs
weight: 66
url: /zh-hant/system.security.cryptography/hashalgorithm/transformblock/
---
## HashAlgorithm::TransformBlock(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<uint8_t\>, int) method

處理一段資料區塊並將資料複製到輸出陣列。

```cpp
int System::Security::Cryptography::HashAlgorithm::TransformBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount, ArrayPtr<uint8_t> outputBuffer, int outputOffset) override
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) 用於讀取資料。 |
| inputOffset | int | 輸入緩衝區偏移量。 |
| inputCount | int | 要處理的位元組數。 |
| outputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 輸出緩衝區，用於複製資料；nullptr 以不執行複製。 |
| outputOffset | int | 輸出緩衝區偏移量。 |

### 返回值

寫入的位元組數。

## 另請參閱

* 型別別名 [ArrayPtr](../../../system/arrayptr/)
* 類別 [HashAlgorithm](../)
* 命名空間 [System::Security::Cryptography](../../)
* 函式庫 [Aspose.Slides](../../../)