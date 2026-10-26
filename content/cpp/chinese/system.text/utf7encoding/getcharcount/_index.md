---
title: GetCharCount()
second_title: Aspose.Slides for C++ API 参考
description: 获取解码字节缓冲区所需的字符数。
type: docs
weight: 79
url: /zh/system.text/utf7encoding/getcharcount/
---
## UTF7Encoding::GetCharCount(ArrayPtr\<uint8_t\>, int, int) method

获取解码字节缓冲区所需的字符数。

```cpp
int System::Text::UTF7Encoding::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 待解码的字节。 |
| index | int | 切片起始位置。 |
| count | int | 切片大小。 |

### 返回值

字符数。

## UTF7Encoding::GetCharCount(const uint8_t *, int) method

获取解码字节缓冲区所需的字符数。

```cpp
int System::Text::UTF7Encoding::GetCharCount(const uint8_t *bytes, int count) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bytes | const **uint8_t** * | 待解码的字节。 |
| count | int | 字节计数。 |

### 返回值

字符数。

## UTF7Encoding::GetCharCount(ArrayPtr\<uint8_t\>, int, int) method

获取解码字节缓冲区所需的字符数。

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 待解码的字节。 |
| index | int | 切片起始位置。 |
| count | int | 切片大小。 |

### 返回值

字符数。

## UTF7Encoding::GetCharCount(ArrayPtr\<uint8_t\>) method

获取解码字节缓冲区所需的字符数。

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 待解码的字节。 |

### 返回值

字符数。

## UTF7Encoding::GetCharCount(const uint8_t *, int) method

获取解码字节缓冲区所需的字符数。

```cpp
virtual int System::Text::Encoding::GetCharCount(const uint8_t *bytes, int count)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bytes | const **uint8_t** * | 待解码的字节。 |
| count | int | 字节计数。 |

### 返回值

字符数。

## 另请参阅

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [UTF7Encoding](../)
* 命名空间 [System::Text](../../)
* 库 [Aspose.Slides](../../../)