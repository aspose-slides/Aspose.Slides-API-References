---
title: ReadContentAsBinHex()
second_title: Aspose.Slides C++ API 参考
description: 读取内容并返回 BinHex 解码后的二进制字节。
type: docs
weight: 599
url: /zh/system.xml/xmlvalidatingreader/readcontentasbinhex/
---
## XmlValidatingReader::ReadContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) 方法

读取内容并返回 BinHex 解码后的二进制字节。

```cpp
int32_t System::Xml::XmlValidatingReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 用于复制生成文本的缓冲区。此值不能为 **nullptr**。 |
| index | **int32_t** | 在缓冲区中开始复制结果的偏移量。 |
| count | **int32_t** | 要复制到缓冲区的最大字节数。实际复制的字节数由此方法返回。 |

### 返回值

写入缓冲区的字节数。

## 另请参见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [XmlValidatingReader](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)