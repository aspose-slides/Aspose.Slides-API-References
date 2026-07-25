---
title: Fallback()
second_title: Aspose.Slides C++ API リファレンス
description: エンコーディング失敗を処理します。
type: docs
weight: 27
url: /ja/system.text/encoderreplacementfallbackbuffer/fallback/
---
## EncoderReplacementFallbackBuffer::Fallback(char_t, int) メソッド


エンコーディング失敗を処理します。

```cpp
virtual bool System::Text::EncoderReplacementFallbackBuffer::Fallback(char_t charUnknown, int index) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| charUnknown | char_t | 不明な文字です。無視されます。 |
| index | int | 不明な文字位置です。無視されます。 |

### 戻り値

置換文字列が提供されていて空でない場合は true、そうでない場合は false。

## EncoderReplacementFallbackBuffer::Fallback(char_t, char_t, int) メソッド


エンコーディング失敗を処理します。

```cpp
virtual bool System::Text::EncoderReplacementFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| charUnknownHigh | char_t | エラーを引き起こしたサロゲートペアの上位部。 |
| charUnknownLow | char_t | エラーを引き起こしたサロゲートペアの下位部。 |
| index | int | 不明な文字位置です。無視されます。 |

### 戻り値

置換文字列が提供されていて空でない場合は true、そうでない場合は false。

## 参照

* クラス [EncoderReplacementFallbackBuffer](../)
* 名前空間 [System::Text](../../)
* ライブラリ [Aspose.Slides](../../../)