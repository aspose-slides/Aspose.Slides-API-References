---
title: CloneNode()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een duplicaat van dit knooppunt. Entiteitsknooppunten kunnen niet worden gekloond. Het aanroepen van deze methode op een XmlEntity-object veroorzaakt een uitzondering.
type: docs
weight: 170
url: /nl/system.xml/xmlentity/clonenode/
---
## XmlEntity::CloneNode(bool) methode

Maakt een duplicaat van dit knooppunt. Entiteitknooppunten kunnen niet worden gekloond. Het aanroepen van deze methode op een [XmlEntity](../) object veroorzaakt een uitzondering.

```cpp
SharedPtr<XmlNode> System::Xml::XmlEntity::CloneNode(bool deep) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| deep | **bool** | **true** om recursief de subboom onder het opgegeven knooppunt te klonen; **false** om alleen het knooppunt zelf te klonen. |

### Retourwaarde

Een kopie van de [XmlNode](../../xmlnode/) waaruit de methode wordt aangeroepen.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlNode](../../xmlnode/)
* Klasse [XmlEntity](../)
* Naamruimte [System::Xml](../../)
* Library [Aspose.Slides](../../../)