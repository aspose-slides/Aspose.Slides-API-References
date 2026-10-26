---
title: LookupNamespace()
second_title: Aspose.Slides voor C++ API-referentie
description: Wanneer overschreven in een afgeleide klasse, lost een namespace-prefix op in de scope van het huidige element.
type: docs
weight: 729
url: /nl/system.xml/xmlreader/lookupnamespace/
---
## XmlReader::LookupNamespace(const String\&) method


Wanneer overschreven in een afgeleide klasse, lost een namespace-prefix op in de scope van het huidige element.

```cpp
virtual String System::Xml::XmlReader::LookupNamespace(const String &prefix)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | De prefix waarvan u de namespace-URI wilt oplossen. Om overeen te komen met de standaard-namespace, geeft u een lege tekenreeks door. |

### Retourwaarde

De namespace-URI waaraan de prefix wordt gekoppeld of **nullptr** als er geen overeenkomende prefix wordt gevonden.

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [XmlReader](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)