---
title: Fallback()
second_title: Aspose.Slides for C++ APIリファレンス
description: デコード失敗を処理します。
type: docs
weight: 27
url: /ja/system.text/decoderexceptionfallbackbuffer/fallback/
---
## DecoderExceptionFallbackBuffer::Fallback(ArrayPtr\<uint8_t\>, int) メソッド

デコード失敗を処理します。

```cpp
virtual bool System::Text::DecoderExceptionFallbackBuffer::Fallback(ArrayPtr<uint8_t> bytesUnknown, int index) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| bytesUnknown | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Array](../../../system/array/) の不明なバイト; 無視されます。 |
| index | int | 不明なバイトのオフセット; 無視されます。 |

### 戻り値

実際には決して戻りません。代わりに例外をスローします。

## 参照

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [DecoderExceptionFallbackBuffer](../)
* 名前空間 [System::Text](../../)
* ライブラリ [Aspose.Slides](../../../)