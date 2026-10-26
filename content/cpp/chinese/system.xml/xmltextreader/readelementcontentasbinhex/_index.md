---
title: ReadElementContentAsBinHex()
second_title: Aspose.Slides for C++ API 参考
description: 读取该元素并解码 BinHex 内容。
type: docs
weight: 677
url: /zh/system.xml/xmltextreader/readelementcontentasbinhex/
---
## XmlTextReader::ReadElementContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) 方法

读取该元素并解码 **BinHex** 内容。

```cpp
int32_t System::Xml::XmlTextReader::ReadElementContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 用于复制生成文本的 buffer。此值不能为 **nullptr**。 |
| index | **int32_t** | 在 buffer 中开始复制结果的偏移量。 |
| count | **int32_t** | 要复制到 buffer 的最大字节数。实际复制的字节数由此方法返回。 |

### 返回值

写入 buffer 的字节数。

## 另见

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 类 [XmlTextReader](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)