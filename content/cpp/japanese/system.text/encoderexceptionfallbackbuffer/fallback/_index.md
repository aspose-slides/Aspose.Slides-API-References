---
title: Fallback()
second_title: Aspose.Slides for C++ API リファレンス
description: エンコーディング失敗を処理します。
type: docs
weight: 27
url: /ja/system.text/encoderexceptionfallbackbuffer/fallback/
---
## EncoderExceptionFallbackBuffer::Fallback(char_t, int) メソッド

エンコーディング失敗を処理します。

```cpp
virtual bool System::Text::EncoderExceptionFallbackBuffer::Fallback(char_t charUnknown, int index) override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| charUnknown | char_t | 不明な文字; 無視されます。 |
| index | int | 不明な文字のオフセット; 無視されます。 |

### 戻り値

実際には決して返らず、代わりに例外をスローします。

## EncoderExceptionFallbackBuffer::Fallback(char_t, char_t, int) メソッド

エンコーディング失敗を処理します。

```cpp
virtual bool System::Text::EncoderExceptionFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index) override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| charUnknownHigh | char_t | エラーを引き起こしたサロゲートペアの上位部。 |
| charUnknownLow | char_t | エラーを引き起こしたサロゲートペアの下位部。 |
| index | int | 不明な文字のオフセット; 無視されます。 |

### 戻り値

実際には決して返らず、代わりに例外をスローします。

## 参照

* クラス [EncoderExceptionFallbackBuffer](../)
* 名前空間 [System::Text](../../)
* ライブラリ [Aspose.Slides](../../../)