---
title: XPathNamespaceScope
second_title: Aspose.Slides C++ API 参考
description: 定义命名空间范围。
type: docs
weight: 144
url: /zh/system.xml.xpath/xpathnamespacescope/
---
## XPathNamespaceScope 枚举

定义命名空间范围。

```cpp
enum class XPathNamespaceScope
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| All | 0 | 返回当前节点作用域中定义的所有命名空间。此列表包括始终隐式声明的 **xmlns:xml** 命名空间。返回的命名空间顺序未定义。 |
| ExcludeXml | 1 | 返回当前节点作用域中定义的所有命名空间，排除 **xmlns:xml** 命名空间。**xmlns:xml** 命名空间始终隐式声明。返回的命名空间顺序未定义。 |
| Local | 2 | 返回在当前节点本地定义的所有命名空间。 |

## 另见

* 命名空间 [System::Xml::XPath](../)
* 库 [Aspose.Slides](../../)