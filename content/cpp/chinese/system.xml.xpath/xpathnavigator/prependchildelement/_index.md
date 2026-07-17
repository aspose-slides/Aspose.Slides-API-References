---
title: PrependChildElement()
second_title: Aspose.Slides for C++ API 参考
description: 使用指定的命名空间前缀、本地名称和命名空间 URI，以及指定的值，在当前节点的子节点列表开头创建一个新的子元素。
type: docs
weight: 989
url: /zh/system.xml.xpath/xpathnavigator/prependchildelement/
---
## XPathNavigator::PrependChildElement(String, String, String, String) 方法

创建一个新的子元素，并将其放置在当前节点的子节点列表开头，使用指定的命名空间前缀、本地名称和命名空间 URI，以及指定的值。

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChildElement(String prefix, String localName, String namespaceURI, String value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | 新子元素的命名空间前缀（如果有）。 |
| localName | [String](../../../system/string/) | 新子元素的本地名称（如果有）。 |
| namespaceURI | [String](../../../system/string/) | 新子元素的命名空间 URI（如果有）。 [String::Empty](../../../system/string/empty/) 和 **nullptr** 等价。 |
| value | [String](../../../system/string/) | 新子元素的值。如果传入 [String::Empty](../../../system/string/empty/) 或 **nullptr**，将创建空元素。 |

## 另请参见

* 类 [String](../../../system/string/)
* 类 [XPathNavigator](../)
* 命名空间 [System::Xml::XPath](../../)
* 库 [Aspose.Slides](../../../)