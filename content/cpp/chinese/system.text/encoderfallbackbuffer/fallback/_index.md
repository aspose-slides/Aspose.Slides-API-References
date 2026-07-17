---
title: Fallback()
second_title: Aspose.Slides for C++ API 参考
description: 实现实际的回退过程。
type: docs
weight: 14
url: /zh/system.text/encoderfallbackbuffer/fallback/
---
## EncoderFallbackBuffer::Fallback(char_t, int) 方法

实现实际的回退过程。

```cpp
virtual bool System::Text::EncoderFallbackBuffer::Fallback(char_t charUnknown, int index)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| charUnknown | char_t | 编码器无法编码的字符。 |
| index | int | 触发错误的字符索引。 |

### 返回值

如果缓冲区处理未知字符则返回 true，否则返回 false。

## EncoderFallbackBuffer::Fallback(char_t, char_t, int) 方法

实现实际的回退过程。

```cpp
virtual bool System::Text::EncoderFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| charUnknownHigh | char_t | 触发错误的代理对的高位字符。 |
| charUnknownLow | char_t | 触发错误的代理对的低位字符。 |
| index | int | 触发错误的字符索引。 |

### 返回值

如果缓冲区处理未知字符则返回 true，否则返回 false。

## 另请参见

* 类 [EncoderFallbackBuffer](../)
* 命名空间 [System::Text](../../)
* 库 [Aspose.Slides](../../../)