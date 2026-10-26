---
title: Fallback()
second_title: Aspose.Slides for C++ API リファレンス
description: 実際のフォールバック手順を実装します。
type: docs
weight: 14
url: /ja/system.text/encoderfallbackbuffer/fallback/
---
## EncoderFallbackBuffer::Fallback(char_t, int) メソッド


実際のフォールバック手順を実装します。

```cpp
virtual bool System::Text::EncoderFallbackBuffer::Fallback(char_t charUnknown, int index)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| charUnknown | char_t | 文字エンコーダがエンコードに失敗した文字。 |
| index | int | [Index](../../../system/index/) エラーを引き起こした文字の。 |

### 戻り値

バッファが不明な文字を処理する場合は true、無視する場合は false。

## EncoderFallbackBuffer::Fallback(char_t, char_t, int) メソッド


実際のフォールバック手順を実装します。

```cpp
virtual bool System::Text::EncoderFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| charUnknownHigh | char_t | エラーを引き起こしたサロゲートペアの上位部。 |
| charUnknownLow | char_t | エラーを引き起こしたサロゲートペアの下位部。 |
| index | int | [Index](../../../system/index/) エラーを引き起こした文字の。 |

### 戻り値

バッファが不明な文字を処理する場合は true、無視する場合は false。

## 参照

* クラス [EncoderFallbackBuffer](../)
* 名前空間 [System::Text](../../)
* ライブラリ [Aspose.Slides](../../../)