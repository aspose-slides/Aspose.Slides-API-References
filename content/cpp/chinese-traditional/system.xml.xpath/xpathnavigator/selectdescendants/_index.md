---
title: SelectDescendants()
second_title: Aspose.Slides for C++ API 參考
description: 選取目前節點的所有子孫節點，且其 XPathNodeType 符合指定的類型。
type: docs
weight: 859
url: /zh-hant/system.xml.xpath/xpathnavigator/selectdescendants/
---
## XPathNavigator::SelectDescendants(XPathNodeType, bool) 方法

選取目前節點的所有子孫節點，且其 XPathNodeType 符合指定的類型。

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectDescendants(XPathNodeType type, bool matchSelf)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | 子孫節點的 XPathNodeType。 |
| matchSelf | **bool** | **true** 以在選取中包含目前節點；否則為 **false**。 |

### 傳回值

一個包含所選節點的 [XPathNodeIterator](../../xpathnodeiterator/)。

## XPathNavigator::SelectDescendants(String, String, bool) 方法

選取目前節點的所有子孫節點，其本地名稱與命名空間 URI 如指定。

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectDescendants(String name, String namespaceURI, bool matchSelf)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 子孫節點的本地名稱。 |
| namespaceURI | [String](../../../system/string/) | 子孫節點的命名空間 URI。 |
| matchSelf | **bool** | **true** 以在選取中包含目前節點；否則為 **false**。 |

### 傳回值

一個包含所選節點的 [XPathNodeIterator](../../xpathnodeiterator/)。

## 另請參閱

* 列舉 [XPathNodeType](../../xpathnodetype/)
* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [XPathNodeIterator](../../xpathnodeiterator/)
* 類別 [XPathNavigator](../)
* 類別 [String](../../../system/string/)
* 命名空間 [System::Xml::XPath](../../)
* 函式庫 [Aspose.Slides](../../../)