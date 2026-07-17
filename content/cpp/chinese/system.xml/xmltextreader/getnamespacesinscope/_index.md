---
title: GetNamespacesInScope()
second_title: Aspose.Slides for C++ API 参考
description: 返回一个包含当前作用域内所有命名空间的集合。
type: docs
weight: 716
url: /zh/system.xml/xmltextreader/getnamespacesinscope/
---
## XmlTextReader::GetNamespacesInScope(XmlNamespaceScope) 方法


返回一个集合，其中包含当前作用域内的所有命名空间。

```cpp
SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::XmlTextReader::GetNamespacesInScope(XmlNamespaceScope scope) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| scope | [XmlNamespaceScope](../../xmlnamespacescope/) | 一个 XmlNamespaceScope 值，指定要返回的命名空间节点类型。 |

### 返回值

一个包含所有当前作用域命名空间的 IDictionary 对象。如果读取器未定位在元素上，则返回一个空字典（无命名空间）。

## 另请参见

* 枚举 [XmlNamespaceScope](../../xmlnamespacescope/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IDictionary](../../../system.collections.generic/idictionary/)
* 类 [String](../../../system/string/)
* 类 [XmlTextReader](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)