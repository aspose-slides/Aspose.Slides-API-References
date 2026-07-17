---
title: Fallback()
second_title: Aspose.Slides C++ API 参考
description: 处理解码失败。
type: docs
weight: 27
url: /zh/system.text/decoderexceptionfallbackbuffer/fallback/
---
## DecoderExceptionFallbackBuffer::Fallback(ArrayPtr\<uint8_t\>, int) method


处理解码失败。

```cpp
virtual bool System::Text::DecoderExceptionFallbackBuffer::Fallback(ArrayPtr<uint8_t> bytesUnknown, int index) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bytesUnknown | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Array](../../../system/array/) 未知字节；已忽略。 |
| index | int | 未知字节的偏移量；已忽略。 |

### 返回值

实际上从不返回，而是抛出异常。

## 另请参见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [DecoderExceptionFallbackBuffer](../)
* 命名空间 [System::Text](../../)
* 库 [Aspose.Slides](../../../)