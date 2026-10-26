---
title: ReadElementContentAsBinHex()
second_title: Aspose.Slides for C++ API 参考
description: 读取元素并解码 BinHex 内容。
type: docs
weight: 482
url: /zh/system.xml/xmlnodereader/readelementcontentasbinhex/
---
## XmlNodeReader::ReadElementContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) 方法

读取元素并解码 BinHex 内容。

```cpp
int32_t System::Xml::XmlNodeReader::ReadElementContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 用于复制结果文本的缓冲区。此值不能为 **nullptr**。 |
| index | **int32_t** | 在缓冲区中开始复制结果的偏移量。 |
| count | **int32_t** | 要复制到缓冲区的最大字节数。实际复制的字节数由此方法返回。 |

### 返回值

写入缓冲区的字节数。

## 另请参见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [XmlNodeReader](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)