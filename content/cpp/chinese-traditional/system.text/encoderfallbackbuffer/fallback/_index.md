---
title: Fallback()
second_title: Aspose.Slides for C++ API 參考
description: 實作實際的回退程序。
type: docs
weight: 14
url: /zh-hant/system.text/encoderfallbackbuffer/fallback/
---
## EncoderFallbackBuffer::Fallback(char_t, int) 方法

實作實際的回退程序。

```cpp
virtual bool System::Text::EncoderFallbackBuffer::Fallback(char_t charUnknown, int index)=0
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| charUnknown | char_t | 字元編碼器無法編碼此字元。 |
| index | int | 觸發錯誤的字元的[Index](../../../system/index/)。 |

### 返回值

True if buffer processes unknown characters, false if it ignores them.

## EncoderFallbackBuffer::Fallback(char_t, char_t, int) 方法

實作實際的回退程序。

```cpp
virtual bool System::Text::EncoderFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index)=0
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| charUnknownHigh | char_t | 觸發錯誤的代理項對的高位部分。 |
| charUnknownLow | char_t | 觸發錯誤的代理項對的低位部分。 |
| index | int | 觸發錯誤的字元的[Index](../../../system/index/)。 |

### 返回值

True if buffer processes unknown characters, false if it ignores them.

## 另請參閱

* 類別 [EncoderFallbackBuffer](../)
* 命名空間 [System::Text](../../)
* 函式庫 [Aspose.Slides](../../../)