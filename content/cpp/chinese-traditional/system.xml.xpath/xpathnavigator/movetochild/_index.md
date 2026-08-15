---
title: MoveToChild()
second_title: Aspose.Slides for C++ API 參考
description: 將 XPathNavigator 移動到具有指定本地名稱和名稱空間 URI 的子節點。
type: docs
weight: 690
url: /zh-hant/system.xml.xpath/xpathnavigator/movetochild/
---
## XPathNavigator::MoveToChild(String, String) 方法

將 [XPathNavigator](../) 移動到具有指定本地名稱和名稱空間 URI 的子節點。

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToChild(String localName, String namespaceURI)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 要移動到的子節點的本地名稱。 |
| namespaceURI | [String](../../../system/string/) | 要移動到的子節點的名稱空間 URI。 |

### 返回值

**true** 如果 [XPathNavigator](../) 成功移動到子節點；否則為 **false**。如果 **false**，[XPathNavigator](../) 的位置保持不變。

## XPathNavigator::MoveToChild(XPathNodeType) 方法

將 [XPathNavigator](../) 移動到指定的 XPathNodeType 的子節點。

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToChild(XPathNodeType type)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | 要移動到的子節點的 XPathNodeType。 |

### 返回值

**true** 如果 [XPathNavigator](../) 成功移動到子節點；否則為 **false**。如果 **false**，[XPathNavigator](../) 的位置保持不變。

## 另見

* 列舉 [XPathNodeType](../../xpathnodetype/)
* 類別 [String](../../../system/string/)
* 類別 [XPathNavigator](../)
* 命名空間 [System::Xml::XPath](../../)
* 函式庫 [Aspose.Slides](../../../)