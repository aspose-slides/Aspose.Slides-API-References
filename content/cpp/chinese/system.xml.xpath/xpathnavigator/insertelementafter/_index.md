---
title: InsertElementAfter()
second_title: Aspose.Slides for C++ API 参考
description: 使用指定的命名空间前缀、本地名称和命名空间 URI，在当前节点后创建一个新的兄弟元素，并使用指定的值。
type: docs
weight: 1028
url: /zh/system.xml.xpath/xpathnavigator/insertelementafter/
---
## XPathNavigator::InsertElementAfter(String, String, String, String) method


使用指定的命名空间前缀、本地名称和命名空间 URI，在当前节点后创建一个新的兄弟元素，并使用指定的值。

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertElementAfter(String prefix, String localName, String namespaceURI, String value)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | 新子元素的命名空间前缀（如果有）。 |
| localName | [String](../../../system/string/) | 新子元素的本地名称（如果有）。 |
| namespaceURI | [String](../../../system/string/) | 新子元素的命名空间 URI（如果有）。[String::Empty](../../../system/string/empty/) 与 **nullptr** 等价。 |
| value | [String](../../../system/string/) | 新子元素的值。如果传入 [String::Empty](../../../system/string/empty/) 或 **nullptr**，则创建一个空元素。 |

## 另见

* 类 [String](../../../system/string/)
* 类 [XPathNavigator](../)
* 命名空间 [System::Xml::XPath](../../)
* 库 [Aspose.Slides](../../../)