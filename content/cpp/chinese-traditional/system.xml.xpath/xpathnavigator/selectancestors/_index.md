---
title: SelectAncestors()
second_title: Aspose.Slides for C++ API 參考文件
description: 選取目前節點的所有祖先節點，這些節點的 XPathNodeType 符合指定的類型。
type: docs
weight: 846
url: /zh-hant/system.xml.xpath/xpathnavigator/selectancestors/
---
## XPathNavigator::SelectAncestors(XPathNodeType, bool) 方法

選取目前節點的所有祖先節點，這些節點的 XPathNodeType 符合指定的類型。

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectAncestors(XPathNodeType type, bool matchSelf)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | 祖先節點的 XPathNodeType。 |
| matchSelf | **bool** | 若要在選取中包含當前節點，**true**；否則 **false**。 |

### 回傳值

一個 [XPathNodeIterator](../../xpathnodeiterator/)，包含所選取的節點。返回的節點以相反的文件順序排列。

## XPathNavigator::SelectAncestors(String, String, bool) 方法

選取目前節點的所有祖先節點，這些節點具有指定的本機名稱和命名空間 URI。

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectAncestors(String name, String namespaceURI, bool matchSelf)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 祖先節點的本機名稱。 |
| namespaceURI | [String](../../../system/string/) | 祖先節點的命名空間 URI。 |
| matchSelf | **bool** | 若要在選取中包含當前節點，**true**；否則 **false**。 |

### 回傳值

一個 [XPathNodeIterator](../../xpathnodeiterator/)，包含所選取的節點。返回的節點以相反的文件順序排列。

## 另見

* 列舉 [XPathNodeType](../../xpathnodetype/)
* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [XPathNodeIterator](../../xpathnodeiterator/)
* 類別 [XPathNavigator](../)
* 類別 [String](../../../system/string/)
* 命名空間 [System::Xml::XPath](../../)
* 函式庫 [Aspose.Slides](../../../)