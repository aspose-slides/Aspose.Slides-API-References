---
title: GetCharCount()
second_title: Aspose.Slides for C++ API 参考
description: 获取解码字节缓冲区所需的字符数。
type: docs
weight: 261
url: /zh/system.text/encoding/getcharcount/
---
## Encoding::GetCharCount(ArrayPtr\<uint8_t\>, int, int) 方法

获取解码字节缓冲区所需的字符数。

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要解码的字节。 |
| index | int | 切片起始位置。 |
| count | int | 切片大小。 |

### 返回值

字符数。

## Encoding::GetCharCount(ArrayPtr\<uint8_t\>) 方法


获取解码字节缓冲区所需的字符数。

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要解码的字节。 |

### 返回值

字符数。

## Encoding::GetCharCount(const uint8_t *, int) 方法


获取解码字节缓冲区所需的字符数。

```cpp
virtual int System::Text::Encoding::GetCharCount(const uint8_t *bytes, int count)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bytes | const **uint8_t** * | 要解码的字节。 |
| count | int | 字节数。 |

### 返回值

字符数。

## 另请参见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [Encoding](../)
* 命名空间 [System::Text](../../)
* 库 [Aspose.Slides](../../../)