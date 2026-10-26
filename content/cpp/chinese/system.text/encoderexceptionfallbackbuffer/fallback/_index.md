---
title: Fallback()
second_title: Aspose.Slides 的 C++ API 参考
description: 处理编码失败。
type: docs
weight: 27
url: /zh/system.text/encoderexceptionfallbackbuffer/fallback/
---
## EncoderExceptionFallbackBuffer::Fallback(char_t, int) 方法

处理编码失败。

```cpp
virtual bool System::Text::EncoderExceptionFallbackBuffer::Fallback(char_t charUnknown, int index) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| charUnknown | char_t | 未知字符；已忽略。 |
| index | int | 未知字符的偏移；已忽略。 |

### 返回值

实际上从不返回，而是抛出异常。

## EncoderExceptionFallbackBuffer::Fallback(char_t, char_t, int) 方法

处理编码失败。

```cpp
virtual bool System::Text::EncoderExceptionFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| charUnknownHigh | char_t | 触发错误的代理对的高位部分。 |
| charUnknownLow | char_t | 触发错误的代理对的低位部分。 |
| index | int | 未知字符的偏移；已忽略。 |

### 返回值

实际上从不返回，而是抛出异常。

## 另见

* 类 [EncoderExceptionFallbackBuffer](../)
* 命名空间 [System::Text](../../)
* 库 [Aspose.Slides](../../../)