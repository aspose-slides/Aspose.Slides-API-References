---
title: CreateAttribute()
second_title: Aspose.Slides C++ API 参考
description: 使用指定的命名空间前缀、本地名称和命名空间 URI，以及指定的值，在当前元素节点上创建属性节点。
type: docs
weight: 1041
url: /zh/system.xml.xpath/xpathnavigator/createattribute/
---
## XPathNavigator::CreateAttribute(String, String, String, String) 方法

创建一个属性节点在当前元素节点上，使用指定的命名空间前缀、本地名称、命名空间 URI 和指定的值。

```cpp
virtual void System::Xml::XPath::XPathNavigator::CreateAttribute(String prefix, String localName, String namespaceURI, String value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | 新属性节点的命名空间前缀（如果有）。 |
| localName | [String](../../../system/string/) | 新属性节点的本地名称，不能 [String::Empty](../../../system/string/empty/) 或 **nullptr**。 |
| namespaceURI | [String](../../../system/string/) | 新属性节点的命名空间 URI（如果有）。 |
| value | [String](../../../system/string/) | 新属性节点的值。如果传入 [String::Empty](../../../system/string/empty/) 或 **nullptr**，则创建一个空属性节点。 |

## 另见

* 类 [String](../../../system/string/)
* 类 [XPathNavigator](../)
* 命名空间 [System::Xml::XPath](../../)
* 库 [Aspose.Slides](../../../)