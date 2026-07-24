---
title: get_ParentNode()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt den Elternknoten dieses Knotens zurück (für Knoten, die Eltern haben können).
type: docs
weight: 53
url: /de/system.xml/xmlnode/get_parentnode/
---
## XmlNode::get_ParentNode() Methode

Gibt den Elternknoten dieses Knotens zurück (für Knoten, die Eltern haben können).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNode::get_ParentNode() final
```

### Rückgabewert

Der [XmlNode](../) der das übergeordnete Element des aktuellen Knotens ist.

## Anmerkungen

Wenn ein Knoten gerade erst erstellt wurde und noch nicht zum Baum hinzugefügt wurde oder wenn er aus dem Baum entfernt wurde, ist der Elternknoten **nullptr**. Für alle anderen Knoten hängt der zurückgegebene Wert vom [XmlNode::get_NodeType](../get_nodetype/) des Knotens ab. Die folgende Tabelle beschreibt die möglichen Rückgabewerte für die **get_NodeType** Methode.

| NodeType | Return Value of ParentNode |
| --- | --- |
| [Attribute](../../../system/attribute/), Document, DocumentFragment, Entity, Notation | Gibt `nullptr` zurück; diese Knoten haben keine Eltern. |
| CDATA | Gibt das Element oder die Entity-Referenz zurück, das den CDATA-Abschnitt enthält. |
| Comment | Gibt das Element, die Entity-Referenz, den Dokumenttyp oder das Dokument zurück, das den Kommentar enthält. |
| DocumentType | Gibt den Dokumentknoten zurück. |
| Element | Gibt den übergeordneten Knoten des Elements zurück. Wenn das Element der Wurzelknoten im Baum ist, ist der Elternknoten der Dokumentknoten. |
| EntityReference | Gibt das Element, das Attribut oder die Entity-Referenz zurück, das die Entity-Referenz enthält. |
| ProcessingInstruction | Gibt das Dokument, das Element, den Dokumenttyp oder die Entity-Referenz zurück, das die Verarbeitungsanweisung enthält. |
| [Text](../../../system.text/)| Gibt das übergeordnete Element, Attribut oder die Entity-Referenz zurück, das den Textknoten enthält. |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlNode](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)