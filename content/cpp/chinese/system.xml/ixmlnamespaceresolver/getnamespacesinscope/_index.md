---
title: GetNamespacesInScope()
second_title: Aspose.Slides for C++ API 参考
description: 返回当前作用域内已定义的前缀-命名空间映射集合。
type: docs
weight: 1
url: /zh/system.xml/ixmlnamespaceresolver/getnamespacesinscope/
---
## IXmlNamespaceResolver::GetNamespacesInScope(XmlNamespaceScope) 方法

返回当前作用域内已定义的前缀-命名空间映射集合。

```cpp
virtual SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::IXmlNamespaceResolver::GetNamespacesInScope(XmlNamespaceScope scope)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| scope | [XmlNamespaceScope](../../xmlnamespacescope/) | 指定要返回的命名空间节点类型的 XmlNamespaceScope 值。 |

### 返回值

包含当前作用域内命名空间的 IDictionary 集合。

## 另见

* Enum [XmlNamespaceScope](../../xmlnamespacescope/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDictionary](../../../system.collections.generic/idictionary/)
* Class [String](../../../system/string/)
* Class [IXmlNamespaceResolver](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)