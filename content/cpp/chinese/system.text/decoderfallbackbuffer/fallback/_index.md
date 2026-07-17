---
title: Fallback()
second_title: Aspose.Slides for C++ API 参考
description: 实现实际的回退过程。
type: docs
weight: 14
url: /zh/system.text/decoderfallbackbuffer/fallback/
---
## DecoderFallbackBuffer::Fallback(ArrayPtr\<uint8_t\>, int) 方法

实现实际的回退过程。

```cpp
virtual bool System::Text::DecoderFallbackBuffer::Fallback(ArrayPtr<uint8_t> bytesUnknown, int index)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bytesUnknown | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Array](../../../system/array/) 的字节，包括解码器无法解码的字节。 |
| index | int | 触发错误的字节的索引。 |

### 返回值

如果缓冲区处理未知字节则返回 true，否则返回 false。

## 参见

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 类 [DecoderFallbackBuffer](../)
* 命名空间 [System::Text](../../)
* Library [Aspose.Slides](../../../)