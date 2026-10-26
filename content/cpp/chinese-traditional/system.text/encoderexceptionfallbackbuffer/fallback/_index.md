---
title: Fallback()
second_title: Aspose.Slides for C++ API 參考
description: 處理編碼失敗。
type: docs
weight: 27
url: /zh-hant/system.text/encoderexceptionfallbackbuffer/fallback/
---
## EncoderExceptionFallbackBuffer::Fallback(char_t, int) 方法

處理編碼失敗。

```cpp
virtual bool System::Text::EncoderExceptionFallbackBuffer::Fallback(char_t charUnknown, int index) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| charUnknown | char_t | 未知字元；已忽略。 |
| index | int | 未知字元偏移量；已忽略。 |

### 返回值

永遠不會返回，而是拋出例外。

## EncoderExceptionFallbackBuffer::Fallback(char_t, char_t, int) 方法

處理編碼失敗。

```cpp
virtual bool System::Text::EncoderExceptionFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| charUnknownHigh | char_t | 觸發錯誤的代理對的高位部分。 |
| charUnknownLow | char_t | 觸發錯誤的代理對的低位部分。 |
| index | int | 未知字元偏移量；已忽略。 |

### 返回值

永遠不會返回，而是拋出例外。

## 另見

* 類別 [EncoderExceptionFallbackBuffer](../)
* 命名空間 [System::Text](../../)
* 程式庫 [Aspose.Slides](../../../)