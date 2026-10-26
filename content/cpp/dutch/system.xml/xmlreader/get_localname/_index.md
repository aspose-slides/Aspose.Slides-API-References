---
title: get_LocalName()
second_title: Aspose.Slides voor C++ API-referentie
description: Wanneer het in een afgeleide klasse wordt overschreven, wordt de lokale naam van het huidige knooppunt opgehaald.
type: docs
weight: 40
url: /nl/system.xml/xmlreader/get_localname/
---
## XmlReader::get_LocalName() methode


Wanneer het in een afgeleide klasse wordt overschreven, wordt de lokale naam van het huidige knooppunt opgehaald.

```cpp
virtual String System::Xml::XmlReader::get_LocalName()=0
```


### Retourwaarde

De naam van het huidige knooppunt zonder het voorvoegsel. Bijvoorbeeld, **LocalName** is **book** voor het element **<bk:book>**. Voor knooptypen die geen naam hebben (zoals **[Text](../../../system.text/)**, **Comment**, enzovoort), retourneert deze methode [String::Empty](../../../system/string/empty/).

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [XmlReader](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)