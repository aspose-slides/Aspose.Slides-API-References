---
title: SelectAncestors()
second_title: Aspose.Slides voor C++ API-referentie
description: Selecteert alle voorouderknooppunten van de huidige knoop die een overeenkomend XPathNodeType hebben.
type: docs
weight: 846
url: /nl/system.xml.xpath/xpathnavigator/selectancestors/
---
## XPathNavigator::SelectAncestors(XPathNodeType, bool) methode

Selecteert alle voorouderknooppunten van de huidige knoop die een overeenkomend XPathNodeType hebben.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectAncestors(XPathNodeType type, bool matchSelf)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | Het XPathNodeType van de voorouderknooppunten. |
| matchSelf | **bool** | Om de contextknoop in de selectie op te nemen, **true**; anders **false**. |

### Retourwaarde

Een [XPathNodeIterator](../../xpathnodeiterator/) die de geselecteerde knopen bevat. De geretourneerde knopen staan in omgekeerde documentvolgorde.

## XPathNavigator::SelectAncestors(String, String, bool) methode

Selecteert alle voorouderknooppunten van de huidige knoop die de opgegeven lokale naam en namespace-URI hebben.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectAncestors(String name, String namespaceURI, bool matchSelf)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | [String](../../../system/string/) | De lokale naam van de voorouderknooppunten. |
| namespaceURI | [String](../../../system/string/) | De namespace-URI van de voorouderknooppunten. |
| matchSelf | **bool** | Om de contextknoop in de selectie op te nemen, **true**; anders **false**. |

### Retourwaarde

Een [XPathNodeIterator](../../xpathnodeiterator/) die de geselecteerde knopen bevat. De geretourneerde knopen staan in omgekeerde documentvolgorde.

## Zie ook

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XPathNodeIterator](../../xpathnodeiterator/)
* Klasse [XPathNavigator](../)
* Klasse [String](../../../system/string/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)