---
title: ReadChars()
second_title: Aspose.Slides C++ API 参考
description: 读取元素的文本内容到字符缓冲区。此方法旨在通过连续调用来读取大型嵌入式文本流。
type: docs
weight: 755
url: /zh/system.xml/xmltextreader/readchars/
---
## XmlTextReader::ReadChars(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) 方法

读取元素的文本内容到字符缓冲区。此方法旨在通过连续调用来读取大型嵌入文本流。

```cpp
int32_t System::Xml::XmlTextReader::ReadChars(const ArrayPtr<char16_t> &buffer, int32_t index, int32_t count)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | 用作写入文本内容的缓冲区的字符数组。 |
| index | **int32_t** | 在 **buffer** 中方法可以开始写入文本内容的位置。 |
| count | **int32_t** | 要写入 **buffer** 的字符数。 |

### 返回值

读取的字符数。如果读取器未定位在元素上或在当前上下文中没有更多文本内容可返回，则可能为 0。

## 另请参阅

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)