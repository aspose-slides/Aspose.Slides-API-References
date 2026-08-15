---
title: TransformBlock()
second_title: Aspose.Slides for C++ API 參考
description: 處理資料區塊並將資料複製到輸出陣列。
type: docs
weight: 53
url: /zh-hant/system.security.cryptography/tobase64transform/transformblock/
---
## ToBase64Transform::TransformBlock(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, System::ArrayPtr\<uint8_t\>, int32_t) 方法

處理資料區塊並將資料複製到輸出陣列。

```cpp
int32_t System::Security::Cryptography::ToBase64Transform::TransformBlock(System::ArrayPtr<uint8_t> inputBuffer, int32_t inputOffset, int32_t inputCount, System::ArrayPtr<uint8_t> outputBuffer, int32_t outputOffset)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| inputBuffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) 用於讀取資料。 |
| inputOffset | **int32_t** | 輸入緩衝區的位移。 |
| inputCount | **int32_t** | 要處理的位元組數。 |
| outputBuffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 輸出緩衝區，用於複製資料；若為 nullptr，則不執行複製。 |
| outputOffset | **int32_t** | 輸出緩衝區的位移。 |

### 返回值

寫入的位元組數。

## 另見

* 型別定義 [ArrayPtr](../../../system/arrayptr/)
* 類別 [ToBase64Transform](../)
* 命名空間 [System::Security::Cryptography](../../)
* 函式庫 [Aspose.Slides](../../../)