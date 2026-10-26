---
title: TransformFinalBlock()
second_title: Aspose.Slides for C++ API リファレンス
description: データの最後のブロックを処理し、ハッシュを計算します。
type: docs
weight: 79
url: /ja/system.security.cryptography/hashalgorithm/transformfinalblock/
---
## HashAlgorithm::TransformFinalBlock(ArrayPtr\<uint8_t\>, int, int) メソッド

データの最後のブロックを処理し、ハッシュを計算します。

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::TransformFinalBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) からデータを読み取ります。 |
| inputOffset | int | 入力バッファのオフセット。 |
| inputCount | int | 処理するバイト数。 |

### 戻り値

全データシーケンスのハッシュが計算されます。

## 参照

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [HashAlgorithm](../)
* 名前空間 [System::Security::Cryptography](../../)
* ライブラリ [Aspose.Slides](../../../)