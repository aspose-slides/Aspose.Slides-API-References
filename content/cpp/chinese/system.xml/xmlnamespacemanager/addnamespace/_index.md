---
title: AddNamespace()
second_title: Aspose.Slides C++ API 参考
description: 将给定的命名空间添加到集合中。
type: docs
weight: 66
url: /zh/system.xml/xmlnamespacemanager/addnamespace/
---
## XmlNamespaceManager::AddNamespace(String, String) 方法


将给定的命名空间添加到集合中。

```cpp
virtual void System::Xml::XmlNamespaceManager::AddNamespace(String prefix, String uri)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | 要与所添加的命名空间关联的前缀。使用 [String::Empty](../../../system/string/empty/) 添加默认命名空间。如果 [XmlNamespaceManager](../) 将用于在 XML 路径语言 ([XPath](../../../system.xml.xpath/)) 表达式中解析命名空间，则必须指定前缀。如果 [XPath](../../../system.xml.xpath/) 表达式不包含前缀，则假定命名空间统一资源标识符 (URI) 为空命名空间。有关 [XPath](../../../system.xml.xpath/) 表达式和 [XmlNamespaceManager](../) 的更多信息，请参阅 XmlNode::SelectNodes(String) 和 XPathExpression::SetContext(SharedPtr<XmlNamespaceManager>) 方法。 |
| uri | [String](../../../system/string/) | 要添加的命名空间。 |

## 另请参见

* 类 [String](../../../system/string/)
* 类 [XmlNamespaceManager](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)