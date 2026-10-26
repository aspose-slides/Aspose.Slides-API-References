---
title: MoveToFirstNamespace()
second_title: Aspose.Slides for C++ API 參考文件
description: 當在衍生類別中覆寫時，將 XPathNavigator 移動到符合所指定 XPathNamespaceScope 的第一個命名空間節點。
type: docs
weight: 560
url: /zh-hant/system.xml.xpath/xpathnavigator/movetofirstnamespace/
---
## XPathNavigator::MoveToFirstNamespace(XPathNamespaceScope) method

當在衍生類別中覆寫時，將 [XPathNavigator](../) 移動到符合所指定 XPathNamespaceScope 的第一個命名空間節點。

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFirstNamespace(XPathNamespaceScope namespaceScope)=0
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| namespaceScope | [XPathNamespaceScope](../../xpathnamespacescope/) | 描述命名空間範圍的 XPathNamespaceScope 值。 |

### 返回值

**true** if the [XPathNavigator](../) is successful moving to the first namespace node; otherwise, **false**. If **false**, the position of the [XPathNavigator](../) is unchanged.

## XPathNavigator::MoveToFirstNamespace() method

將 [XPathNavigator](../) 移動到目前節點的第一個命名空間節點。

```cpp
bool System::Xml::XPath::XPathNavigator::MoveToFirstNamespace()
```

### 返回值

**true** if the [XPathNavigator](../) is successful moving to the first namespace node; otherwise, **false**. If **false**, the position of the [XPathNavigator](../) is unchanged.

## 另見

* 列舉 [XPathNamespaceScope](../../xpathnamespacescope/)
* 類別 [XPathNavigator](../)
* 命名空間 [System::Xml::XPath](../../)
* 函式庫 [Aspose.Slides](../../../)