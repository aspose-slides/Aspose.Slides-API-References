---
title: TransformBlock()
second_title: Aspose.Slides for C++ API 參考文件
description: 處理資料區塊並將資料複製到輸出陣列。
type: docs
weight: 1
url: /zh-hant/system.security.cryptography/icryptotransform/transformblock/
---
## ICryptoTransform::TransformBlock(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<uint8_t\>, int) 方法

處理資料區塊並將資料複製到輸出陣列。

```cpp
virtual int System::Security::Cryptography::ICryptoTransform::TransformBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount, ArrayPtr<uint8_t> outputBuffer, int outputOffset)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) to read data from. |
| inputOffset | int | Input buffer offset. |
| inputCount | int | Number of bytes to process. |
| outputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Output buffer to copy data into; nullptr to do no copying. |
| outputOffset | int | Output buffer offset. |

### 傳回值

Number of bytes written.

## 另見

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 類別 [ICryptoTransform](../)
* 命名空間 [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)