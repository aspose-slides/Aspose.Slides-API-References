---
title: Convert()
second_title: Aspose.Slides for C++ API 参考
description: 在两种编码之间转换字节。
type: docs
weight: 378
url: /zh/system.text/encoding/convert/
---
## Encoding::Convert(const EncodingPtr\&, const EncodingPtr\&, const ArrayPtr\<uint8_t\>\&) 方法

将字节在两种编码之间进行转换。

```cpp
static ArrayPtr<uint8_t> System::Text::Encoding::Convert(const EncodingPtr &src_encoding, const EncodingPtr &dst_encoding, const ArrayPtr<uint8_t> &bytes)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| src_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 源编码。 |
| dst_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 目标编码。 |
| bytes | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 要转换的字节。 |

### 返回值

已转换的字节。

## Encoding::Convert(const EncodingPtr\&, const EncodingPtr\&, const ArrayPtr\<uint8_t\>\&, int, int) 方法

将字节在两种编码之间进行转换。

```cpp
static ArrayPtr<uint8_t> System::Text::Encoding::Convert(const EncodingPtr &src_encoding, const EncodingPtr &dst_encoding, const ArrayPtr<uint8_t> &bytes, int index, int count)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| src_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 源编码。 |
| dst_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 目标编码。 |
| bytes | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 要转换的字节。 |
| index | int | 切片起始位置。 |
| count | int | 切片大小。 |

### 返回值

已转换的字节。

## 参见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类型定义 [EncodingPtr](../../../system/encodingptr/)
* 类 [Encoding](../)
* 命名空间 [System::Text](../../)
* 库 [Aspose.Slides](../../../)