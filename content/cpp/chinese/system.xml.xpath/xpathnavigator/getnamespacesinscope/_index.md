---
title: GetNamespacesInScope()
second_title: Aspose.Slides for C++ API 参考
description: 返回当前节点的作用域内命名空间。
type: docs
weight: 430
url: /zh/system.xml.xpath/xpathnavigator/getnamespacesinscope/
---
## XPathNavigator::GetNamespacesInScope(XmlNamespaceScope) 方法


返回当前节点的作用域内命名空间。

```cpp
SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::XPath::XPathNavigator::GetNamespacesInScope(XmlNamespaceScope scope) override
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| scope | [XmlNamespaceScope](../../../system.xml/xmlnamespacescope/) | 指定要返回的命名空间的 XmlNamespaceScope 值。 |

### 返回值

一个 IDictionary 集合，键为前缀的命名空间名称。

## 参见

* Enum [XmlNamespaceScope](../../../system.xml/xmlnamespacescope/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IDictionary](../../../system.collections.generic/idictionary/)
* 类 [String](../../../system/string/)
* 类 [XPathNavigator](../)
* 命名空间 [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)