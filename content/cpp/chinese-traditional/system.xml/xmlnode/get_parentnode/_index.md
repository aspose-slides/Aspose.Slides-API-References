---
title: get_ParentNode()
second_title: Aspose.Slides for C++ API 參考文件
description: 返回此節點的父節點（對於可以有父節點的節點）。
type: docs
weight: 53
url: /zh-hant/system.xml/xmlnode/get_parentnode/
---
## XmlNode::get_ParentNode() 方法


返回此節點的父節點（對於可以有父節點的節點）。

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNode::get_ParentNode() final
```


### 回傳值

[XmlNode](../) 為目前節點的父節點。

## 備註



如果節點剛剛被建立且尚未加入樹中，或已從樹中移除，則其父節點為 **nullptr**。對於其他所有節點，返回的值取決於節點的 [XmlNode::get_NodeType](../get_nodetype/)。以下表格說明了 **get_NodeType** 方法可能的返回值。 

| NodeType | ParentNode 的返回值 |
| --- | --- |
| [Attribute](../../../system/attribute/), Document, DocumentFragment, Entity, Notation | 返回 `nullptr`；這些節點沒有父節點。 |
| CDATA | 返回包含 CDATA 區段的元素或實體參考。 |
| Comment | 返回包含註釋的元素、實體參考、文件類型或文件。 |
| DocumentType | 返回文件節點。 |
| Element | 返回該元素的父節點。如果該元素是樹中的根節點，則父節點是文件節點。 |
| EntityReference | 返回包含該實體參考的元素、屬性或實體參考。 |
| ProcessingInstruction | 返回包含處理指令的文件、元素、文件類型或實體參考。 |
| [Text](../../../system.text/)| 返回包含文字節點的父元素、屬性或實體參考。 |


## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)