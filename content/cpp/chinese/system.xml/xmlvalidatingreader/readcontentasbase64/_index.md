---
title: ReadContentAsBase64()
second_title: Aspose.Slides for C++ API 参考
description: 读取内容并返回 Base64 解码后的二进制字节。
type: docs
weight: 573
url: /zh/system.xml/xmlvalidatingreader/readcontentasbase64/
---
## XmlValidatingReader::ReadContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) 方法

读取内容并返回 Base64 解码后的二进制字节。

```cpp
int32_t System::Xml::XmlValidatingReader::ReadContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 用于复制生成文本的缓冲区。此值不能为 **nullptr**。 |
| index | **int32_t** | 缓冲区中开始复制结果的偏移量。 |
| count | **int32_t** | 要复制到缓冲区的最大字节数。实际复制的字节数由此方法返回。 |

### 返回值

写入缓冲区的字节数。

## 另见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [XmlValidatingReader](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)