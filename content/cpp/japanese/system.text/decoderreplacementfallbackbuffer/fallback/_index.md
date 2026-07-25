---
title: Fallback()
second_title: Aspose.Slides for C++ API リファレンス
description: デコード失敗を処理します。
type: docs
weight: 27
url: /ja/system.text/decoderreplacementfallbackbuffer/fallback/
---
## DecoderReplacementFallbackBuffer::Fallback(ArrayPtr\<uint8_t\>, int) メソッド

デコード失敗を処理します。

```cpp
virtual bool System::Text::DecoderReplacementFallbackBuffer::Fallback(ArrayPtr<uint8_t> bytesUnknown, int index) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| bytesUnknown | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Array](../../../system/array/) 不明なバイトの; 無視されます。 |
| index | int | 不明なバイトのオフセット; 無視されます。 |

### 戻り値

置換文字列が提供され、空でない場合は True、そうでない場合は false。

## 参照

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [DecoderReplacementFallbackBuffer](../)
* 名前空間 [System::Text](../../)
* ライブラリ [Aspose.Slides](../../../)