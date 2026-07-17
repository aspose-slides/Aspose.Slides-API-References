---
title: GetAttribute()
second_title: Aspose.Slides for C++ API 参考
description: 返回具有指定本地名称和命名空间 URI 的属性值。
type: docs
weight: 482
url: /zh/system.xml.xpath/xpathnavigator/getattribute/
---
## XPathNavigator::GetAttribute(String, String) 方法


返回具有指定本地名称和命名空间 URI 的属性值。

```cpp
virtual String System::Xml::XPath::XPathNavigator::GetAttribute(String localName, String namespaceURI)
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 属性的本地名称。**localName** 区分大小写。 |
| namespaceURI | [String](../../../system/string/) | 属性的命名空间 URI。 |

### 返回值

一个 [String](../../../system/string/)，其中包含指定属性的值；如果未找到匹配的属性，或者 [XPathNavigator](../) 未定位在元素节点上，则返回 [String::Empty](../../../system/string/empty/)。

## 另请参阅

* 类 [String](../../../system/string/)
* 类 [XPathNavigator](../)
* 命名空间 [System::Xml::XPath](../../)
* 库 [Aspose.Slides](../../../)