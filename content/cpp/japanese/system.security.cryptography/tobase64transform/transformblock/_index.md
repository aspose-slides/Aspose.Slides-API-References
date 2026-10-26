---
title: TransformBlock()
second_title: Aspose.Slides for C++ API リファレンス
description: データのブロックを処理し、出力配列にデータをコピーします。
type: docs
weight: 53
url: /ja/system.security.cryptography/tobase64transform/transformblock/
---
## ToBase64Transform::TransformBlock(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, System::ArrayPtr\<uint8_t\>, int32_t) メソッド

データのブロックを処理し、出力配列にデータをコピーします。

```cpp
int32_t System::Security::Cryptography::ToBase64Transform::TransformBlock(System::ArrayPtr<uint8_t> inputBuffer, int32_t inputOffset, int32_t inputCount, System::ArrayPtr<uint8_t> outputBuffer, int32_t outputOffset)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputBuffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) からデータを読み取ります。 |
| inputOffset | **int32_t** | 入力バッファのオフセット。 |
| inputCount | **int32_t** | 処理するバイト数。 |
| outputBuffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | データをコピーする出力バッファ; nullptr はコピーしません。 |
| outputOffset | **int32_t** | 出力バッファのオフセット。 |

### 戻り値

書き込まれたバイト数。

## 参照

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [ToBase64Transform](../)
* 名前空間 [System::Security::Cryptography](../../)
* ライブラリ [Aspose.Slides](../../../)