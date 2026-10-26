---
title: MoveToNamespace()
second_title: Aspose.Slides for C++ API 参考
description: 将 XPathNavigator 移动到具有指定命名空间前缀的命名空间节点。
type: docs
weight: 547
url: /zh/system.xml.xpath/xpathnavigator/movetonamespace/
---
## XPathNavigator::MoveToNamespace(String) 方法

移动 [XPathNavigator](../) 到具有指定命名空间前缀的命名空间节点。

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNamespace(String name)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 命名空间节点的命名空间前缀。 |

### 返回值

**true** 如果 [XPathNavigator](../) 成功移动到指定的命名空间；**false** 如果未找到匹配的命名空间节点，或者 [XPathNavigator](../) 未定位在元素节点上。若 **false**，[XPathNavigator](../) 的位置保持不变。

## 另请参见

* 类 [String](../../../system/string/)
* 类 [XPathNavigator](../)
* 命名空间 [System::Xml::XPath](../../)
* 库 [Aspose.Slides](../../../)