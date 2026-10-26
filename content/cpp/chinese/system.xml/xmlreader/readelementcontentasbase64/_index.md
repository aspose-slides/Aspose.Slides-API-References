---
title: ReadElementContentAsBase64()
second_title: Aspose.Slides C++ API 参考
description: 读取该元素并解码 Base64 内容。
type: docs
weight: 768
url: /zh/system.xml/xmlreader/readelementcontentasbase64/
---
## XmlReader::ReadElementContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) 方法

读取该元素并解码 **Base64** 内容。

```cpp
virtual int32_t System::Xml::XmlReader::ReadElementContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 用于复制生成文本的缓冲区。此值不能为 **nullptr**。 |
| index | **int32_t** | 在缓冲区中开始复制结果的偏移量。 |
| count | **int32_t** | 复制到缓冲区的最大字节数。实际复制的字节数由此方法返回。 |

## 返回值

写入缓冲区的字节数。

## 参见

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 类 [XmlReader](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)