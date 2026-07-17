---
title: InsertElementBefore()
second_title: Aspose.Slides C++ API 参考
description: 使用指定的命名空间前缀、本地名称和命名空间 URI，在当前节点之前创建一个新的同级元素，并使用指定的值。
type: docs
weight: 1015
url: /zh/system.xml.xpath/xpathnavigator/insertelementbefore/
---
## XPathNavigator::InsertElementBefore(String, String, String, String) 方法

在当前节点之前使用指定的命名空间前缀、本地名称和命名空间 URI 创建一个新的同级元素，并使用指定的值。

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertElementBefore(String prefix, String localName, String namespaceURI, String value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | 新子元素的命名空间前缀（如果有）。 |
| localName | [String](../../../system/string/) | 新子元素的本地名称（如果有）。 |
| namespaceURI | [String](../../../system/string/) | 新子元素的命名空间 URI（如果有）。[String::Empty](../../../system/string/empty/) 和 **nullptr** 等效。 |
| value | [String](../../../system/string/) | 新子元素的值。如果传入 [String::Empty](../../../system/string/empty/) 或 **nullptr**，则创建空元素。 |

## 另请参阅

* 类 [String](../../../system/string/)
* 类 [XPathNavigator](../)
* 命名空间 [System::Xml::XPath](../../)
* 库 [Aspose.Slides](../../../)