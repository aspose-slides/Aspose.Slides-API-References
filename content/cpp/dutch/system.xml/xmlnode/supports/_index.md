---
title: Supports()
second_title: Aspose.Slides voor C++ API-referentie
description: Test of de DOM-implementatie een specifieke functie implementeert.
type: docs
weight: 482
url: /nl/system.xml/xmlnode/supports/
---
## XmlNode::Supports(String, String) methode


Test of de DOM-implementatie een specifieke functie ondersteunt.

```cpp
virtual bool System::Xml::XmlNode::Supports(String feature, String version)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| feature | [String](../../../system/string/) | De pakketnaam van de functie die moet worden getest. Deze naam is niet hoofdlettergevoelig. |
| version | [String](../../../system/string/) | Het versienummer van de pakketnaam die moet worden getest. Als de versie niet is opgegeven (null), zorgt het ondersteunen van elke versie van de functie ervoor dat de methode **true** retourneert. |

### Retourwaarde

**true** als de functie is geïmplementeerd in de opgegeven versie; anders **false**.
## Opmerkingen



De onderstaande tabel beschrijft de combinaties die **true** retourneren. 

| Feature | [Version](../../../system/version/)|
| --- | --- |
| XML | 1.0 |
| XML | 2.0 |


## Zie ook

* Class [String](../../../system/string/)
* Class [XmlNode](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)