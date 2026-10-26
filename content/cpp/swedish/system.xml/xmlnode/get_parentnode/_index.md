---
title: get_ParentNode()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar föräldern till den här noden (för noder som kan ha föräldrar).
type: docs
weight: 53
url: /sv/system.xml/xmlnode/get_parentnode/
---
## XmlNode::get_ParentNode() metod

Returns the parent of this node (for nodes that can have parents).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNode::get_ParentNode() final
```

### Returvärde

The [XmlNode](../) som är föräldern till den aktuella noden.

## Anmärkningar

If a node has just been created and not yet added to the tree, or if it has been removed from the tree, the parent is **nullptr**. For all other nodes, the value returned depends on the [XmlNode::get_NodeType](../get_nodetype/) of the node. The following table describes the possible return values for the **get_NodeType** method. 

| NodeType | Returvärde för ParentNode |
| --- | --- |
| [Attribute](../../../system/attribute/), Document, DocumentFragment, Entity, Notation | Returnerar `nullptr`; dessa noder har inga föräldrar. |
| CDATA | Returnerar elementet eller entitetsreferensen som innehåller CDATA-sektionen. |
| Comment | Returnerar elementet, entitetsreferensen, dokumenttypen eller dokumentet som innehåller kommentaren. |
| DocumentType | Returnerar dokumentnoden. |
| Element | Returnerar föräldranoden för elementet. Om elementet är rot noden i trädet är föräldern dokumentnoden. |
| EntityReference | Returnerar elementet, attributet eller entitetsreferensen som innehåller entitetsreferensen. |
| ProcessingInstruction | Returnerar dokumentet, elementet, dokumenttypen eller entitetsreferensen som innehåller processinstruktionen. |
| [Text](../../../system.text/)| Returnerar föräldraelementet, attributet eller entitetsreferensen som innehåller textnoden. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [XmlNode](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)