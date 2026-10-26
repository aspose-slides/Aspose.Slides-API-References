---
title: ReadString()
second_title: Aspose.Slides for C++ API 参考
description: 将元素或文本节点的内容读取为字符串。
type: docs
weight: 391
url: /zh/system.xml/xmlnodereader/readstring/
---
## XmlNodeReader::ReadString() 方法

读取元素或文本节点的内容为字符串。

```cpp
String System::Xml::XmlNodeReader::ReadString() override
```

### 返回值

元素或类似文本节点的内容（这可以包括 CDATA、[Text](../../../system.text/) 节点等）。如果读取器定位在除元素或文本节点以外的内容，或当前上下文中没有更多可返回的文本内容，则可能为空字符串。注意：文本节点可以是元素节点或属性文本节点。

## 另请参阅

* 类 [String](../../../system/string/)
* 类 [XmlNodeReader](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)