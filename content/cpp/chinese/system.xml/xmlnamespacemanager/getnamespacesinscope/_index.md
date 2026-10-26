---
title: GetNamespacesInScope()
second_title: Aspose.Slides for C++ API 参考
description: 返回一个按前缀键入的命名空间名称集合，可用于枚举当前作用域中的命名空间。
type: docs
weight: 105
url: /zh/system.xml/xmlnamespacemanager/getnamespacesinscope/
---
## XmlNamespaceManager::GetNamespacesInScope(XmlNamespaceScope) 方法

返回一个按前缀键入的命名空间名称集合，可用于枚举当前作用域中的命名空间。

```cpp
SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::XmlNamespaceManager::GetNamespacesInScope(XmlNamespaceScope scope) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| scope | [XmlNamespaceScope](../../xmlnamespacescope/) | 一个枚举值，指定要返回的命名空间节点的类型。 |

### 返回值

当前作用域中命名空间和前缀对的集合。

## 另见

* 枚举 [XmlNamespaceScope](../../xmlnamespacescope/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IDictionary](../../../system.collections.generic/idictionary/)
* 类 [String](../../../system/string/)
* 类 [XmlNamespaceManager](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)