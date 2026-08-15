---
title: MoveToNextNamespace()
second_title: Aspose.Slides for C++ API 參考
description: 當在衍生類別中被覆寫時，將 XPathNavigator 移動到符合指定 XPathNamespaceScope 的下一個命名空間節點。
type: docs
weight: 573
url: /zh-hant/system.xml.xpath/xpathnavigator/movetonextnamespace/
---
## XPathNavigator::MoveToNextNamespace(XPathNamespaceScope) 方法


當在衍生類別中被覆寫時，將 [XPathNavigator](../) 移動到符合指定的 XPathNamespaceScope 的下一個命名空間節點。

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNextNamespace(XPathNamespaceScope namespaceScope)=0
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| namespaceScope | [XPathNamespaceScope](../../xpathnamespacescope/) | 一個描述命名空間範圍的 XPathNamespaceScope 值。 |

### 返回值

**true** 若 [XPathNavigator](../) 成功移動到下一個命名空間節點，則返回 **true**；否則返回 **false**。如果 **false**，[XPathNavigator](../) 的位置保持不變。

## XPathNavigator::MoveToNextNamespace() 方法


將 [XPathNavigator](../) 移動到下一個命名空間節點。

```cpp
bool System::Xml::XPath::XPathNavigator::MoveToNextNamespace()
```


### 返回值

**true** 若 [XPathNavigator](../) 成功移動到下一個命名空間節點，則返回 **true**；否則返回 **false**。如果 **false**，[XPathNavigator](../) 的位置保持不變。

## 參見

* Enum [XPathNamespaceScope](../../xpathnamespacescope/)
* 類別 [XPathNavigator](../)
* 命名空間 [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)