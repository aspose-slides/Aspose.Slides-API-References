---
title: TransformBlock()
second_title: Aspose.Slides for C++ API リファレンス
description: データブロックを処理し、出力配列にデータをコピーします。
type: docs
weight: 66
url: /ja/system.security.cryptography/hashalgorithm/transformblock/
---
## HashAlgorithm::TransformBlock(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<uint8_t\>, int) メソッド

データブロックを処理し、出力配列にデータをコピーします。

```cpp
int System::Security::Cryptography::HashAlgorithm::TransformBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount, ArrayPtr<uint8_t> outputBuffer, int outputOffset) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) データを読み取るバッファ。 |
| inputOffset | int | 入力バッファのオフセット。 |
| inputCount | int | 処理するバイト数。 |
| outputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | データをコピーする出力バッファ。コピーしない場合は nullptr を指定。 |
| outputOffset | int | 出力バッファのオフセット。 |

### 戻り値

書き込まれたバイト数。

## 参照

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [HashAlgorithm](../)
* 名前空間 [System::Security::Cryptography](../../)
* ライブラリ [Aspose.Slides](../../../)