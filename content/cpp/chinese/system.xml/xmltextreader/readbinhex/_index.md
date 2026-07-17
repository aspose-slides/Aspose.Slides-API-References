---
title: ReadBinHex()
second_title: Aspose.Slides C++ API 参考
description: 解码 BinHex 并返回解码后的二进制字节。
type: docs
weight: 781
url: /zh/system.xml/xmltextreader/readbinhex/
---
## XmlTextReader::ReadBinHex(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 方法

解码 **BinHex** 并返回解码后的二进制字节。

```cpp
int32_t System::Xml::XmlTextReader::ReadBinHex(const ArrayPtr<uint8_t> &array, int32_t offset, int32_t len)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 用作缓冲区的字节数组，解码后的二进制字节将写入其中。 |
| offset | **int32_t** | 数组中的零基索引，指定方法可以开始写入缓冲区的位置。 |
| len | **int32_t** | 写入缓冲区的字节数量。 |

### 返回值

写入缓冲区的字节数。

## 另见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [XmlTextReader](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)