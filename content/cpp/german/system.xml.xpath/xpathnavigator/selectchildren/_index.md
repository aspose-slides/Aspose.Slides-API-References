---
title: SelectChildren()
second_title: Aspose.Slides für C++ API-Referenz
description: Wählt alle Kindknoten des aktuellen Knotens aus, die den passenden XPathNodeType haben.
type: docs
weight: 833
url: /de/system.xml.xpath/xpathnavigator/selectchildren/
---
## XPathNavigator::SelectChildren(XPathNodeType) Methode

Wählt alle Kindknoten des aktuellen Knotens aus, die den passenden XPathNodeType haben.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectChildren(XPathNodeType type)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | Der XPathNodeType der Kindknoten. |

### Rückgabewert

Ein [XPathNodeIterator](../../xpathnodeiterator/), das die ausgewählten Knoten enthält.

## XPathNavigator::SelectChildren(String, String) Methode

Wählt alle Kindknoten des aktuellen Knotens aus, die den angegebenen lokalen Namen und den Namespace-URI besitzen.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectChildren(String name, String namespaceURI)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | [String](../../../system/string/) | Der lokale Name der Kindknoten. |
| namespaceURI | [String](../../../system/string/) | Der Namespace-URI der Kindknoten. |

### Rückgabewert

Ein [XPathNodeIterator](../../xpathnodeiterator/), das die ausgewählten Knoten enthält.

## Siehe auch

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XPathNodeIterator](../../xpathnodeiterator/)
* Klasse [XPathNavigator](../)
* Klasse [String](../../../system/string/)
* Namensraum [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)