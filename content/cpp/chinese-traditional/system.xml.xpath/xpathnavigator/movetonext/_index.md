---
title: MoveToNext()
second_title: Aspose.Slides for C++ API 參考文件
description: 當在衍生類別中被覆寫時，將 XPathNavigator 移動到目前節點的下一個同級節點。
type: docs
weight: 586
url: /zh-hant/system.xml.xpath/xpathnavigator/movetonext/
---
## XPathNavigator::MoveToNext() method


當在衍生類別中被覆寫時，將 [XPathNavigator](../) 移動到目前節點的下一個同級節點。

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext()=0
```


### Return Value

**true** if the [XPathNavigator](../) is successful moving to the next sibling node; otherwise **false** if there are no more siblings or if the [XPathNavigator](../) is currently positioned on an attribute node. If **false**, the position of the [XPathNavigator](../) is unchanged.

## XPathNavigator::MoveToNext(String, String) method


將 [XPathNavigator](../) 移動到具備指定本地名稱和命名空間 URI 的下一個同級節點。

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext(String localName, String namespaceURI)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 要移動到的下一個同級節點的本地名稱。 |
| namespaceURI | [String](../../../system/string/) | 要移動到的下一個同級節點的命名空間 URI。 |

### Return Value

**true** if the [XPathNavigator](../) is successful moving to the next sibling node; **false** if there are no more siblings, or if the [XPathNavigator](../) is currently positioned on an attribute node. If **false**, the position of the [XPathNavigator](../) is unchanged.

## XPathNavigator::MoveToNext(XPathNodeType) method


將 [XPathNavigator](../) 移動到符合指定 XPathNodeType 的目前節點之下一個同級節點。

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext(XPathNodeType type)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | 要移動到的同級節點之 XPathNodeType。 |

### Return Value

**true** if the [XPathNavigator](../) is successful moving to the next sibling node; otherwise, **false** if there are no more siblings or if the [XPathNavigator](../) is currently positioned on an attribute node. If **false**, the position of the [XPathNavigator](../) is unchanged.

## See Also

* Enum [XPathNodeType](../../xpathnodetype/)
* Class [XPathNavigator](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)