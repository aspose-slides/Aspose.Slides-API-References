---
title: SetNamedItem()
second_title: Aspose.Slides voor C++ API-referentie
description: "Voegt een XmlNode toe met behulp van het resultaat van XmlNode::get_Name."
type: docs
weight: 14
url: /nl/system.xml/xmlattributecollection/setnameditem/
---
## XmlAttributeCollection::SetNamedItem(SharedPtr\<XmlNode\>) methode


Voegt een [XmlNode](../../xmlnode/) toe met behulp van het [XmlNode::get_Name](../../xmlnode/get_name/) resultaat.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttributeCollection::SetNamedItem(SharedPtr<XmlNode> node) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | Een attribuut-node om op te slaan in deze collectie. De node is later toegankelijk via de naam van de node. Als er al een node met die naam aanwezig is in de collectie, wordt deze vervangen door de nieuwe; anders wordt de node aan het einde van de collectie toegevoegd. |

### Retourwaarde

Als de **node** een bestaande node met dezelfde naam vervangt, wordt de oude node geretourneerd; anders wordt de toegevoegde node geretourneerd.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlAttributeCollection](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)