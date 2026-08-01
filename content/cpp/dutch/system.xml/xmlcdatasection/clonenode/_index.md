---
title: CloneNode()
second_title: Aspose.Slides voor C++ API Referentie
description: Maakt een duplicaat van deze knoop.
type: docs
weight: 53
url: /nl/system.xml/xmlcdatasection/clonenode/
---
## XmlCDataSection::CloneNode(bool) methode

Maakt een duplicaat van deze knoop.

```cpp
SharedPtr<XmlNode> System::Xml::XmlCDataSection::CloneNode(bool deep) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| deep | **bool** | **true** om recursief de subboom onder de opgegeven knoop te klonen; **false** om alleen de knoop zelf te klonen. Omdat CDATA-knopen geen kinderen hebben, zal de gekloonde knoop, ongeacht de parameterinstelling, altijd de gegevensinhoud bevatten. |

### Retourwaarde

De gekloonde knoop.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlNode](../../xmlnode/)
* Klasse [XmlCDataSection](../)
* Namespace [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)