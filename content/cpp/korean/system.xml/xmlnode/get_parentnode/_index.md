---
title: get_ParentNode()
second_title: Aspose.Slides C++ API 레퍼런스
description: 이 노드의 부모를 반환합니다 (부모를 가질 수 있는 노드의 경우).
type: docs
weight: 53
url: /ko/system.xml/xmlnode/get_parentnode/
---
## XmlNode::get_ParentNode() 메서드

Returns the parent of this node (for nodes that can have parents).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNode::get_ParentNode() final
```

### 반환 값

The [XmlNode](../) that is the parent of the current node.

## 비고

If a node has just been created and not yet added to the tree, or if it has been removed from the tree, the parent is **nullptr**. For all other nodes, the value returned depends on the [XmlNode::get_NodeType](../get_nodetype/) of the node. The following table describes the possible return values for the **get_NodeType** 메서드. 

| NodeType | ParentNode 반환 값 |
| --- | --- |
| [Attribute](../../../system/attribute/), Document, DocumentFragment, Entity, Notation | `nullptr`을 반환합니다; 이러한 노드는 부모가 없습니다. |
| CDATA | CDATA 섹션을 포함하는 요소 또는 엔터티 참조를 반환합니다. |
| Comment | 주석을 포함하는 요소, 엔터티 참조, 문서 타입 또는 문서를 반환합니다. |
| DocumentType | 문서 노드를 반환합니다. |
| Element | 요소의 부모 노드를 반환합니다. 요소가 트리의 루트 노드인 경우, 부모는 문서 노드입니다. |
| EntityReference | 엔터티 참조를 포함하는 요소, 속성 또는 엔터티 참조를 반환합니다. |
| ProcessingInstruction | 처리 지시어를 포함하는 문서, 요소, 문서 타입 또는 엔터티 참조를 반환합니다. |
| [Text](../../../system.text/) | 텍스트 노드를 포함하는 부모 요소, 속성 또는 엔터티 참조를 반환합니다. |

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlNode](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)