---
title: ReadString()
second_title: Aspose.Slides C++ API 参考
description: 将元素或文本节点的内容读取为字符串。
type: docs
weight: 690
url: /zh/system.xml/xmltextreader/readstring/
---
## XmlTextReader::ReadString() 方法

读取元素或文本节点的内容为字符串。

```cpp
String System::Xml::XmlTextReader::ReadString() override
```

### 返回值

元素或文本节点的内容。如果读取器定位在非元素或文本节点的其他位置，或者在当前上下文中没有更多的文本内容可返回，则可能为空字符串。**注意：**文本节点可以是元素文本节点或属性文本节点。

## 参见

* 类 [String](../../../system/string/)
* 类 [XmlTextReader](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)