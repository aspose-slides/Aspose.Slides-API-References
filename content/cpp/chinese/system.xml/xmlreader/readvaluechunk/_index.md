---
title: ReadValueChunk()
second_title: Aspose.Slides for C++ API 参考
description: 读取嵌入在 XML 文档中的大文本流。
type: docs
weight: 807
url: /zh/system.xml/xmlreader/readvaluechunk/
---
## XmlReader::ReadValueChunk(ArrayPtr\<char16_t\>, int32_t, int32_t) method


读取嵌入在 XML 文档中的大文本流。

```cpp
virtual int32_t System::Xml::XmlReader::ReadValueChunk(ArrayPtr<char16_t> buffer, int32_t index, int32_t count)
```


### Arguments

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char16_t\> | 字符数组，用作写入文本内容的缓冲区。此值不能为空指针 **nullptr**。 |
| index | **int32_t** | 缓冲区中的偏移量，[XmlReader](../) 可以从此处开始复制结果。 |
| count | **int32_t** | 要复制到缓冲区的最大字符数。实际复制的字符数由此方法返回。 |

### Return Value

读取到缓冲区的字符数。当没有更多文本内容时返回零。

## See Also

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [XmlReader](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)