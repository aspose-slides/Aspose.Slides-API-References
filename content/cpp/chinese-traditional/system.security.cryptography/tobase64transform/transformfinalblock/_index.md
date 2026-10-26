---
title: TransformFinalBlock()
second_title: Aspose.Slides for C++ API 參考手冊
description: 處理最後一個資料區塊並計算輸出值。
type: docs
weight: 66
url: /zh-hant/system.security.cryptography/tobase64transform/transformfinalblock/
---
## ToBase64Transform::TransformFinalBlock(System::ArrayPtr\<uint8_t\>, int32_t, int32_t) method


處理最後一個資料區塊並計算輸出值。

```cpp
System::ArrayPtr<uint8_t> System::Security::Cryptography::ToBase64Transform::TransformFinalBlock(System::ArrayPtr<uint8_t> inputBuffer, int32_t inputOffset, int32_t inputCount)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| inputBuffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) 讀取資料的來源。 |
| inputOffset | **int32_t** | 輸入緩衝區偏移量。 |
| inputCount | **int32_t** | 要處理的位元組數。 |

### 回傳值

針對整個輸入序列計算的輸出。

## 另請參閱

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ToBase64Transform](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)