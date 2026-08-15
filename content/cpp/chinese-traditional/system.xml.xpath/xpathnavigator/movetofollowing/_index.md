---
title: MoveToFollowing()
second_title: Aspose.Slides for C++ API 參考
description: 將 XPathNavigator 移動到文檔順序中指定本地名稱和名稱空間 URI 的元素。
type: docs
weight: 703
url: /zh-hant/system.xml.xpath/xpathnavigator/movetofollowing/
---
## XPathNavigator::MoveToFollowing(String, String) 方法

將 [XPathNavigator](../) 移至文檔順序中指定的本地名稱和名稱空間 URI 的元素。

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(String localName, String namespaceURI)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 元素的本地名稱。 |
| namespaceURI | [String](../../../system/string/) | 元素的名稱空間 URI。 |

### 返回值

**true** 若 [XPathNavigator](../) 移動成功，否則為 **false**。

## XPathNavigator::MoveToFollowing(String, String, SharedPtr\<XPathNavigator\>) 方法

將 [XPathNavigator](../) 移至文檔順序中指定的本地名稱和名稱空間 URI 的元素，並移動到指定的邊界。

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(String localName, String namespaceURI, SharedPtr<XPathNavigator> end)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 元素的本地名稱。 |
| namespaceURI | [String](../../../system/string/) | 元素的名稱空間 URI。 |
| end | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | 位於元素邊界的 [XPathNavigator](../) 物件，當前的 [XPathNavigator](../) 在搜尋下一個元素時不會越過此邊界。 |

### 返回值

**true** 若 [XPathNavigator](../) 移動成功，否則為 **false**。

## XPathNavigator::MoveToFollowing(XPathNodeType) 方法


將 [XPathNavigator](../) 移至文檔順序中指定的 XPathNodeType 的下一個元素。

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(XPathNodeType type)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | 元素的 XPathNodeType。XPathNodeType 不能是 [XPathNodeType::Attribute](../../xpathnodetype/) 或 [XPathNodeType::Namespace](../../xpathnodetype/)。 |

### 返回值

**true** 若 [XPathNavigator](../) 移動成功，否則為 **false**。

## XPathNavigator::MoveToFollowing(XPathNodeType, SharedPtr\<XPathNavigator\>) 方法


將 [XPathNavigator](../) 移至文檔順序中指定的 XPathNodeType 的下一個元素，並移動到指定的邊界。

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(XPathNodeType type, SharedPtr<XPathNavigator> end)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | 元素的 XPathNodeType。XPathNodeType 不能是 [XPathNodeType::Attribute](../../xpathnodetype/) 或 [XPathNodeType::Namespace](../../xpathnodetype/)。 |
| end | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | 位於元素邊界的 [XPathNavigator](../) 物件，當前的 [XPathNavigator](../) 在搜尋下一個元素時不會越過此邊界。 |

### 返回值

**true** 若 [XPathNavigator](../) 移動成功，否則為 **false**。

## 另請參閱

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [String](../../../system/string/)
* 類別 [XPathNavigator](../)
* 命名空間 [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)