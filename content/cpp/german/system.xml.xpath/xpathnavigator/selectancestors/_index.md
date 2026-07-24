---
title: SelectAncestors()
second_title: Aspose.Slides für C++ API-Referenz
description: Wählt alle Vorfahrenknoten des aktuellen Knotens aus, die einen passenden XPathNodeType haben.
type: docs
weight: 846
url: /de/system.xml.xpath/xpathnavigator/selectancestors/
---
## XPathNavigator::SelectAncestors(XPathNodeType, bool) Methode

Wählt alle Vorfahrenknoten des aktuellen Knotens aus, die einen passenden XPathNodeType haben.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectAncestors(XPathNodeType type, bool matchSelf)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | Der XPathNodeType der Vorfahrenknoten. |
| matchSelf | **bool** | Um den Kontextknoten in die Auswahl einzubeziehen, **true**; andernfalls **false**. |

### Rückgabewert

Ein [XPathNodeIterator](../../xpathnodeiterator/), das die ausgewählten Knoten enthält. Die zurückgegebenen Knoten sind in umgekehrter Dokumentreihenfolge.

## XPathNavigator::SelectAncestors(String, String, bool) Methode

Wählt alle Vorfahrenknoten des aktuellen Knotens aus, die den angegebenen lokalen Namen und die angegebene Namespace-URI haben.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectAncestors(String name, String namespaceURI, bool matchSelf)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | [String](../../../system/string/) | Der lokale Name der Vorfahrenknoten. |
| namespaceURI | [String](../../../system/string/) | Die Namespace-URI der Vorfahrenknoten. |
| matchSelf | **bool** | Um den Kontextknoten in die Auswahl einzubeziehen, **true**; andernfalls **false**. |

### Rückgabewert

Ein [XPathNodeIterator](../../xpathnodeiterator/), das die ausgewählten Knoten enthält. Die zurückgegebenen Knoten sind in umgekehrter Dokumentreihenfolge.

## Siehe auch

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XPathNodeIterator](../../xpathnodeiterator/)
* Klasse [XPathNavigator](../)
* Klasse [String](../../../system/string/)
* Namensraum [System::Xml::XPath](../../)
* Bibliothek [Aspose.Slides](../../../)