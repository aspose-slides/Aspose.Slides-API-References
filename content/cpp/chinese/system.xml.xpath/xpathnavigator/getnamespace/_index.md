---
title: GetNamespace()
second_title: Aspose.Slides for C++ API 参考
description: 返回与指定本地名称对应的命名空间节点的值。
type: docs
weight: 534
url: /zh/system.xml.xpath/xpathnavigator/getnamespace/
---
## XPathNavigator::GetNamespace(String) 方法

返回与指定本地名称对应的命名空间节点的值。

```cpp
virtual String System::Xml::XPath::XPathNavigator::GetNamespace(String name)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 命名空间节点的本地名称。 |

### 返回值

一个 [String](../../../system/string/)，其中包含命名空间节点的值；如果未找到匹配的命名空间节点，或如果 [XPathNavigator](../) 未定位在元素节点上，则为 [String::Empty](../../../system/string/empty/)。

## 另请参见

* 类 [String](../../../system/string/)
* 类 [XPathNavigator](../)
* 命名空间 [System::Xml::XPath](../../)
* 库 [Aspose.Slides](../../../)