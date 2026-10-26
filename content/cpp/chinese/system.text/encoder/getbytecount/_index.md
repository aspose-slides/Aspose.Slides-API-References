---
title: GetByteCount()
second_title: Aspose.Slides C++ API 参考
description: 获取对缓冲区进行编码所需的字节数。
type: docs
weight: 40
url: /zh/system.text/encoder/getbytecount/
---
## Encoder::GetByteCount(ArrayPtr\<char_t\>, int, int, bool) 方法


获取对缓冲区进行编码所需的字节数。

```cpp
virtual int System::Text::Encoder::GetByteCount(ArrayPtr<char_t> chars, int index, int count, bool flush)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 要编码的字符。 |
| index | int | [Buffer](../../../system/buffer/) 偏移量。 |
| count | int | 要编码的字符数。 |
| flush | **bool** | 如果为 true，则在计算后清除内部编码器状态。 |

### 返回值

对缓冲区进行编码所需的字节数。

## Encoder::GetByteCount(const char_t *, int, bool) 方法


获取对缓冲区进行编码所需的字节数。

```cpp
virtual int System::Text::Encoder::GetByteCount(const char_t *chars, int count, bool flush)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| chars | const char_t * | 要编码的字符。 |
| count | int | 要编码的字符数。 |
| flush | **bool** | 如果为 true，则在计算后清除内部编码器状态。 |

### 返回值

对缓冲区进行编码所需的字节数。

## 另请参见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [Encoder](../)
* 命名空间 [System::Text](../../)
* 库 [Aspose.Slides](../../../)