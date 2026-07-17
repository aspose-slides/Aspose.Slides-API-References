---
title: Fallback()
second_title: Aspose.Slides for C++ API 参考
description: 处理解码失败。
type: docs
weight: 27
url: /zh/system.text/decoderreplacementfallbackbuffer/fallback/
---
## DecoderReplacementFallbackBuffer::Fallback(ArrayPtr\<uint8_t\>, int) 方法

处理解码失败。

```cpp
virtual bool System::Text::DecoderReplacementFallbackBuffer::Fallback(ArrayPtr<uint8_t> bytesUnknown, int index) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bytesUnknown | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Array](../../../system/array/) 的未知字节；已忽略。 |
| index | int | 未知字节偏移；已忽略。 |

### 返回值

如果提供了替换字符串且非空，则返回 true；否则返回 false。

## 另请参见

* 类型别名 [ArrayPtr](../../../system/arrayptr/)
* 类 [DecoderReplacementFallbackBuffer](../)
* 命名空间 [System::Text](../../)
* 库 [Aspose.Slides](../../../)