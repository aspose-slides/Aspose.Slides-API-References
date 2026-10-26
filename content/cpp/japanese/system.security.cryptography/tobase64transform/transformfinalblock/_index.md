---
title: TransformFinalBlock()
second_title: Aspose.Slides for C++ API リファレンス
description: データの最後のブロックを処理し、出力値を計算します。
type: docs
weight: 66
url: /ja/system.security.cryptography/tobase64transform/transformfinalblock/
---
## ToBase64Transform::TransformFinalBlock(System::ArrayPtr\<uint8_t\>, int32_t, int32_t) メソッド

データの最後のブロックを処理し、出力値を計算します。

```cpp
System::ArrayPtr<uint8_t> System::Security::Cryptography::ToBase64Transform::TransformFinalBlock(System::ArrayPtr<uint8_t> inputBuffer, int32_t inputOffset, int32_t inputCount)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputBuffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) からデータを読み取ります。 |
| inputOffset | **int32_t** | 入力バッファのオフセット。 |
| inputCount | **int32_t** | 処理するバイト数。 |

### 戻り値

全入力シーケンスに対して計算された出力。

## 関連項目

* Typedef [ArrayPtr](../../../system/arrayptr/)
* クラス [ToBase64Transform](../)
* 名前空間 [System::Security::Cryptography](../../)
* ライブラリ [Aspose.Slides](../../../)