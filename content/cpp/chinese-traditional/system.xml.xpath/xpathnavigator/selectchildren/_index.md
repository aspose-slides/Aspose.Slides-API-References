---
title: SelectChildren()
second_title: Aspose.Slides for C++ API 參考
description: 選取目前節點的所有子節點，這些子節點的 XPathNodeType 相符。
type: docs
weight: 833
url: /zh-hant/system.xml.xpath/xpathnavigator/selectchildren/
---
## XPathNavigator::SelectChildren(XPathNodeType) 方法

選取目前節點的所有子節點，這些子節點的 XPathNodeType 與之匹配。

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectChildren(XPathNodeType type)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | 子節點的 XPathNodeType。 |

### 返回值

包含所選節點的 [XPathNodeIterator](../../xpathnodeiterator/)。

## XPathNavigator::SelectChildren(String, String) 方法

選取目前節點的所有子節點，這些子節點具有指定的本地名稱和命名空間 URI。

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectChildren(String name, String namespaceURI)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 子節點的本地名稱。 |
| namespaceURI | [String](../../../system/string/) | 子節點的命名空間 URI。 |

### 返回值

包含所選節點的 [XPathNodeIterator](../../xpathnodeiterator/)。

## 參見

* 列舉 [XPathNodeType](../../xpathnodetype/)
* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [XPathNodeIterator](../../xpathnodeiterator/)
* 類別 [XPathNavigator](../)
* 類別 [String](../../../system/string/)
* 命名空間 [System::Xml::XPath](../../)
* 函式庫 [Aspose.Slides](../../../)