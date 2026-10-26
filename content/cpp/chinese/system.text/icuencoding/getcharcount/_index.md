---
title: GetCharCount()
second_title: Aspose.Slides C++ API 参考
description: 获取解码字节缓冲区所需的字符数。
type: docs
weight: 53
url: /zh/system.text/icuencoding/getcharcount/
---
## ICUEncoding::GetCharCount(const uint8_t *, int) 方法

获取解码字节缓冲区所需的字符数。

```cpp
int System::Text::ICUEncoding::GetCharCount(const uint8_t *bytes, int count) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bytes to decode. |
| count | int | Bytes count. |

### 返回值

字符数。

## ICUEncoding::GetCharCount(ArrayPtr\<uint8_t\>, int, int) 方法

获取解码字节缓冲区所需的字符数。

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes to decode. |
| index | int | Slice beginning. |
| count | int | Slice size. |

### 返回值

字符数。

## ICUEncoding::GetCharCount(ArrayPtr\<uint8_t\>) 方法

获取解码字节缓冲区所需的字符数。

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes to decode. |

### 返回值

字符数。

## ICUEncoding::GetCharCount(const uint8_t *, int) 方法

获取解码字节缓冲区所需的字符数。

```cpp
virtual int System::Text::Encoding::GetCharCount(const uint8_t *bytes, int count)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bytes to decode. |
| count | int | Bytes count. |

### 返回值

字符数。

## 另请参见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [ICUEncoding](../)
* 命名空间 [System::Text](../../)
* 库 [Aspose.Slides](../../../)