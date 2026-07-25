---
title: Fallback()
second_title: Aspose.Slides for C++ API リファレンス
description: 実際のフォールバック手順を実装します。
type: docs
weight: 14
url: /ja/system.text/decoderfallbackbuffer/fallback/
---
## DecoderFallbackBuffer::Fallback(ArrayPtr\<uint8_t\>, int) メソッド

実際のフォールバック手順を実装します。

```cpp
virtual bool System::Text::DecoderFallbackBuffer::Fallback(ArrayPtr<uint8_t> bytesUnknown, int index)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| bytesUnknown | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Array](../../../system/array/) バイト（デコーダがデコードに失敗したバイトを含む） |
| index | int | [Index](../../../system/index/) バイト（エラーを引き起こしたバイト） |

### 戻り値

バッファが未知のバイトを処理した場合は True、無視した場合は false。

## 参照

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [DecoderFallbackBuffer](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)