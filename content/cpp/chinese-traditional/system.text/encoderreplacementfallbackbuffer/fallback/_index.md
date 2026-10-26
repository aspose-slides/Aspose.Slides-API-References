---
title: Fallback()
second_title: Aspose.Slides for C++ API 參考文件
description: 處理編碼失敗。
type: docs
weight: 27
url: /zh-hant/system.text/encoderreplacementfallbackbuffer/fallback/
---
## EncoderReplacementFallbackBuffer::Fallback(char_t, int) 方法

處理編碼失敗。

```cpp
virtual bool System::Text::EncoderReplacementFallbackBuffer::Fallback(char_t charUnknown, int index) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| charUnknown | char_t | 未知字元；已忽略。 |
| index | int | 未知字元位置；已忽略。 |

### 回傳值

如果提供了取代字串且不為空則回傳 true，否則回傳 false。

## EncoderReplacementFallbackBuffer::Fallback(char_t, char_t, int) 方法

處理編碼失敗。

```cpp
virtual bool System::Text::EncoderReplacementFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| charUnknownHigh | char_t | 觸發錯誤的代理對的高位元組。 |
| charUnknownLow | char_t | 觸發錯誤的代理對的低位元組。 |
| index | int | 未知字元位置；已忽略。 |

### 回傳值

如果提供了取代字串且不為空則回傳 true，否則回傳 false。

## 參閱

* 類別 [EncoderReplacementFallbackBuffer](../)
* 命名空間 [System::Text](../../)
* 函式庫 [Aspose.Slides](../../../)