---
title: SelectDescendants()
second_title: Aspose.Slides voor C++ API-referentie
description: Selecteert alle afstammingsknooppunten van het huidige knooppunt die een overeenkomend XPathNodeType hebben.
type: docs
weight: 859
url: /nl/system.xml.xpath/xpathnavigator/selectdescendants/
---
## XPathNavigator::SelectDescendants(XPathNodeType, bool) methode

Selecteert alle afstammingsknooppunten van het huidige knooppunt die een overeenkomend XPathNodeType hebben.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectDescendants(XPathNodeType type, bool matchSelf)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | Het XPathNodeType van de afstammingsknooppunten. |
| matchSelf | **bool** | **true** om het contextknooppunt in de selectie op te nemen; anders **false**. |

### Retourwaarde

Een [XPathNodeIterator](../../xpathnodeiterator/) die de geselecteerde knooppunten bevat.

## XPathNavigator::SelectDescendants(String, String, bool) methode

Selecteert alle afstammingsknooppunten van het huidige knooppunt met de opgegeven lokale naam en namespace-URI.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectDescendants(String name, String namespaceURI, bool matchSelf)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | [String](../../../system/string/) | De lokale naam van de afstammingsknooppunten. |
| namespaceURI | [String](../../../system/string/) | De namespace-URI van de afstammingsknooppunten. |
| matchSelf | **bool** | **true** om het contextknooppunt in de selectie op te nemen; anders **false**. |

### Retourwaarde

Een [XPathNodeIterator](../../xpathnodeiterator/) die de geselecteerde knooppunten bevat.

## Zie ook

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Class [XPathNavigator](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)