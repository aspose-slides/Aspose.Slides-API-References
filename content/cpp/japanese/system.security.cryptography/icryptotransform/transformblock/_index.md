---
title: TransformBlock()
second_title: Aspose.Slides for C++ API リファレンス
description: データのブロックを処理し、出力配列にデータをコピーします。
type: docs
weight: 1
url: /ja/system.security.cryptography/icryptotransform/transformblock/
---
## ICryptoTransform::TransformBlock(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<uint8_t\>, int) メソッド

データのブロックを処理し、出力配列にデータをコピーします。

```cpp
virtual int System::Security::Cryptography::ICryptoTransform::TransformBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount, ArrayPtr<uint8_t> outputBuffer, int outputOffset)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/)からデータを読み取るための。 |
| inputOffset | int | 入力バッファのオフセット。 |
| inputCount | int | 処理するバイト数。 |
| outputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | データをコピーする出力バッファ; コピーしない場合は nullptr。 |
| outputOffset | int | 出力バッファのオフセット。 |

### 戻り値

書き込まれたバイト数。

## 関連項目

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [ICryptoTransform](../)
* 名前空間 [System::Security::Cryptography](../../)
* ライブラリ [Aspose.Slides](../../../)