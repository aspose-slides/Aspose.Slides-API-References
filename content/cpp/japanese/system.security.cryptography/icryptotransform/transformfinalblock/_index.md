---
title: TransformFinalBlock()
second_title: Aspose.Slides for C++ API リファレンス
description: データの最後のブロックを処理し、出力値を計算します。
type: docs
weight: 14
url: /ja/system.security.cryptography/icryptotransform/transformfinalblock/
---
## ICryptoTransform::TransformFinalBlock(ArrayPtr\<uint8_t\>, int, int) メソッド

入力データの最後のブロックを処理し、出力値を計算します。

```cpp
virtual ArrayPtr<uint8_t> System::Security::Cryptography::ICryptoTransform::TransformFinalBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) からデータを読み取るための |
| inputOffset | int | 入力バッファのオフセット。 |
| inputCount | int | 処理するバイト数。 |

### 戻り値

入力シーケンス全体に対して計算された出力。

## 参照

* Typedef [ArrayPtr](../../../system/arrayptr/)
* クラス [ICryptoTransform](../)
* 名前空間 [System::Security::Cryptography](../../)
* ライブラリ [Aspose.Slides](../../../)