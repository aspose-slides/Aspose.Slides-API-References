---
title: TransformFinalBlock()
second_title: Aspose.Slides for C++ API 參考
description: 處理最後一個資料區塊並計算輸出值。
type: docs
weight: 14
url: /zh-hant/system.security.cryptography/icryptotransform/transformfinalblock/
---
## ICryptoTransform::TransformFinalBlock(ArrayPtr\<uint8_t\>, int, int) method


處理最後一個資料區塊並計算輸出值。

```cpp
virtual ArrayPtr<uint8_t> System::Security::Cryptography::ICryptoTransform::TransformFinalBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount)=0
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) 用於讀取資料。 |
| inputOffset | int | 輸入緩衝區偏移。 |
| inputCount | int | 要處理的位元組數。 |

### 返回值

為整個輸入序列計算的輸出。

## 另請參閱

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 類別 [ICryptoTransform](../)
* 命名空間 [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)