---
title: MoveToAttribute()
second_title: Aspose.Slides for C++ API 参考
description: 将 XPathNavigator 移动到具有匹配本地名称和命名空间 URI 的属性。
type: docs
weight: 495
url: /zh/system.xml.xpath/xpathnavigator/movetoattribute/
---
## XPathNavigator::MoveToAttribute(String, String) 方法

将 [XPathNavigator](../) 移动到具有匹配本地名称和命名空间 URI 的属性。

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToAttribute(String localName, String namespaceURI)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 属性的本地名称。 |
| namespaceURI | [String](../../../system/string/) | 属性的命名空间 URI；空命名空间使用 **nullptr**。 |

### 返回值

**true** 如果 [XPathNavigator](../) 成功移动到属性；否则为 **false**。如果 **false**，[XPathNavigator](../) 的位置保持不变。

## 参见

* 类 [String](../../../system/string/)
* 类 [XPathNavigator](../)
* 命名空间 [System::Xml::XPath](../../)
* 库 [Aspose.Slides](../../../)