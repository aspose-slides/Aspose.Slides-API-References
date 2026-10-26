---
title: CloneNode()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een duplicaat van dit knooppunt. Notatienodes kunnen niet worden gekloond. Het aanroepen van deze methode op een XmlNotation-object gooit een uitzondering.
type: docs
weight: 118
url: /nl/system.xml/xmlnotation/clonenode/
---
## XmlNotation::CloneNode(bool) methode

Maakt een duplicaat van dit knooppunt. Notatienodes kunnen niet worden gekloond. Het aanroepen van deze methode op een [XmlNotation](../) object gooit een uitzondering.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNotation::CloneNode(bool deep) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| deep | **bool** | **true** om de subboom onder het opgegeven knooppunt recursief te klonen; **false** om alleen het knooppunt zelf te klonen. |

### Retourwaarde

Een [XmlNode](../../xmlnode/) kopie van het knooppunt waarvan de methode wordt aangeroepen.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlNode](../../xmlnode/)
* Klasse [XmlNotation](../)
* Naamruimte [System::Xml](../../)
* Library [Aspose.Slides](../../../)