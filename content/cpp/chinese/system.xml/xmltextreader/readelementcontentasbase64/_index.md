---
title: ReadElementContentAsBase64()
second_title: Aspose.Slides for C++ API 参考
description: 读取元素并解码 Base64 内容。
type: docs
weight: 651
url: /zh/system.xml/xmltextreader/readelementcontentasbase64/
---
## XmlTextReader::ReadElementContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) 方法

读取元素并解码 Base64 内容。

```cpp
int32_t System::Xml::XmlTextReader::ReadElementContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要将结果文本复制到的缓冲区。此值不能为 **nullptr**。 |
| index | **int32_t** | 在缓冲区中的偏移量，表示从何处开始复制结果。 |
| count | **int32_t** | 要复制到缓冲区的最大字节数。实际复制的字节数由此方法返回。 |

### 返回值

写入缓冲区的字节数。

## 另见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [XmlTextReader](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)