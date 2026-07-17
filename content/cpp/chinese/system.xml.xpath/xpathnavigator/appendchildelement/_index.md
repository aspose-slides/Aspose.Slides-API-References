---
title: AppendChildElement()
second_title: Aspose.Slides for C++ API 参考
description: 使用指定的命名空间前缀、本地名称和命名空间 URI，以及指定的值，在当前节点的子节点列表末尾创建一个新的子元素节点。
type: docs
weight: 1002
url: /zh/system.xml.xpath/xpathnavigator/appendchildelement/
---
## XPathNavigator::AppendChildElement(String, String, String, String) 方法

使用指定的命名空间前缀、本地名称和命名空间 URI，以及指定的值，在当前节点的子节点列表末尾创建一个新的子元素节点。

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChildElement(String prefix, String localName, String namespaceURI, String value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | 新子元素节点的命名空间前缀（如果有）。 |
| localName | [String](../../../system/string/) | 新子元素节点的本地名称（如果有）。 |
| namespaceURI | [String](../../../system/string/) | 新子元素节点的命名空间 URI（如果有）。[String::Empty](../../../system/string/empty/) 和 **nullptr** 等价。 |
| value | [String](../../../system/string/) | 新子元素节点的值。如果传入 [String::Empty](../../../system/string/empty/) 或 **nullptr**，将创建一个空元素。 |

## 另请参阅

* 类 [String](../../../system/string/)
* 类 [XPathNavigator](../)
* 命名空间 [System::Xml::XPath](../../)
* 库 [Aspose.Slides](../../../)