---
title: CloneNode()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een duplicaat van dit knooppunt.
type: docs
weight: 92
url: /nl/system.xml/xmlentityreference/clonenode/
---
## XmlEntityReference::CloneNode(bool) methode

Maakt een duplicaat van dit knooppunt.

```cpp
SharedPtr<XmlNode> System::Xml::XmlEntityReference::CloneNode(bool deep) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| deep | **bool** | **true** om recursief de subboom onder het opgegeven knooppunt te klonen; **false** om alleen het knooppunt zelf te klonen. Voor [XmlEntityReference](../) knooppunten retourneert deze methode altijd een entiteit-referentieknooppunt zonder kinderen. De vervangende tekst wordt ingesteld wanneer het knooppunt in een bovenliggend knooppunt wordt ingevoegd. |

### Returnwaarde

Het gekloonde knooppunt.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlNode](../../xmlnode/)
* Klasse [XmlEntityReference](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)