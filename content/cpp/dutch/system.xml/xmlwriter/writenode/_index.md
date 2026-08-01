---
title: WriteNode()
second_title: Aspose.Slides voor C++ API-referentie
description: Wanneer overschreven in een afgeleide klasse, kopieert het alles van de lezer naar de schrijver en verplaatst de lezer naar het begin van de volgende sibling.
type: docs
weight: 430
url: /nl/system.xml/xmlwriter/writenode/
---
## XmlWriter::WriteNode(SharedPtr\<XmlReader\>, bool) methode


Wanneer in een afgeleide klasse wordt overschreven, kopieert het alles van de lezer naar de schrijver en verplaatst de lezer naar het begin van de volgende sibling.

```cpp
virtual void System::Xml::XmlWriter::WriteNode(SharedPtr<XmlReader> reader, bool defattr)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | De [XmlReader](../../xmlreader/) om van te lezen. |
| defattr | **bool** | **true** om de standaardattributen van de [XmlReader](../../xmlreader/) te kopiëren; anders **false**. |

## XmlWriter::WriteNode(SharedPtr\<XPath::XPathNavigator\>, bool) methode


Kopieert alles van het XPathNavigator-object naar de schrijver. De positie van de XPathNavigator blijft ongewijzigd.

```cpp
virtual void System::Xml::XmlWriter::WriteNode(SharedPtr<XPath::XPathNavigator> navigator, bool defattr)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| navigator | [SharedPtr](../../../system/sharedptr/)\<[XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | De XPathNavigator om van te kopiëren. |
| defattr | **bool** | **true** om de standaardattributen te kopiëren; anders **false**. |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlReader](../../xmlreader/)
* Klasse [XmlWriter](../)
* Klasse [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Naamruimte [System::Xml](../../)
* Library [Aspose.Slides](../../../)