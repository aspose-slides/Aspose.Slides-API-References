---
title: SelectDescendants()
second_title: Aspose.Slides für C++ API-Referenz
description: Wählt alle Nachkommenknoten des aktuellen Knotens aus, die einen passenden XPathNodeType besitzen.
type: docs
weight: 859
url: /de/system.xml.xpath/xpathnavigator/selectdescendants/
---
## XPathNavigator::SelectDescendants(XPathNodeType, bool) Methode

Wählt alle Nachkommenknoten des aktuellen Knotens aus, die einen passenden XPathNodeType besitzen.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectDescendants(XPathNodeType type, bool matchSelf)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | Der XPathNodeType der Nachkommenknoten. |
| matchSelf | **bool** | **true**, um den Kontextknoten in die Auswahl einzubeziehen; andernfalls **false**. |

### Rückgabewert

Ein [XPathNodeIterator](../../xpathnodeiterator/) der die ausgewählten Knoten enthält.

## XPathNavigator::SelectDescendants(String, String, bool) Methode

Wählt alle Nachkommenknoten des aktuellen Knotens aus, die den angegebenen lokalen Namen und den Namespace-URI besitzen.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectDescendants(String name, String namespaceURI, bool matchSelf)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | [String](../../../system/string/) | Der lokale Name der Nachkommenknoten. |
| namespaceURI | [String](../../../system/string/) | Der Namespace-URI der Nachkommenknoten. |
| matchSelf | **bool** | **true**, um den Kontextknoten in die Auswahl einzubeziehen; andernfalls **false**. |

### Rückgabewert

Ein [XPathNodeIterator](../../xpathnodeiterator/) der die ausgewählten Knoten enthält.

## Siehe Auch

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XPathNodeIterator](../../xpathnodeiterator/)
* Klasse [XPathNavigator](../)
* Klasse [String](../../../system/string/)
* Namensraum [System::Xml::XPath](../../)
* Bibliothek [Aspose.Slides](../../../)