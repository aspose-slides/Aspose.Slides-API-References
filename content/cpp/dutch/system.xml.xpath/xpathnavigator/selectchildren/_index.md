---
title: SelectChildren()
second_title: Aspose.Slides voor C++ API-referentie
description: Selecteert alle kindknooppunten van het huidige knooppunt die het overeenkomende XPathNodeType hebben.
type: docs
weight: 833
url: /nl/system.xml.xpath/xpathnavigator/selectchildren/
---
## XPathNavigator::SelectChildren(XPathNodeType) methode


Selecteert alle kindknooppunten van het huidige knooppunt die het overeenkomende XPathNodeType hebben.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectChildren(XPathNodeType type)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | Het XPathNodeType van de kindknooppunten. |

### Retourwaarde

Een [XPathNodeIterator](../../xpathnodeiterator/) die de geselecteerde knooppunten bevat.

## XPathNavigator::SelectChildren(String, String) methode


Selecteert alle kindknooppunten van het huidige knooppunt die de opgegeven lokale naam en namespace-URI hebben.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectChildren(String name, String namespaceURI)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | [String](../../../system/string/) | De lokale naam van de kindknooppunten. |
| namespaceURI | [String](../../../system/string/) | De namespace-URI van de kindknooppunten. |

### Retourwaarde

Een [XPathNodeIterator](../../xpathnodeiterator/) die de geselecteerde knooppunten bevat.

## Zie ook

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XPathNodeIterator](../../xpathnodeiterator/)
* Klasse [XPathNavigator](../)
* Klasse [String](../../../system/string/)
* Naamruimte [System::Xml::XPath](../../)
* Bibliotheek [Aspose.Slides](../../../)