---
title: CloneNode()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een duplicaat van dit knooppunt.
type: docs
weight: 40
url: /nl/system.xml/xmlcomment/clonenode/
---
## XmlComment::CloneNode(bool) methode

Maakt een duplicaat van dit knooppunt.

```cpp
SharedPtr<XmlNode> System::Xml::XmlComment::CloneNode(bool deep) override
```

### Arguments

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| deep | **bool** | **true** om de subtree onder het opgegeven knooppunt recursief te klonen; **false** om alleen het knooppunt zelf te klonen. Omdat commentaarknooppunten geen kinderen hebben, bevat het gekloonde knooppunt altijd de tekstinhoud, ongeacht de parameterinstelling. |

### Retourwaarde

Het gekloonde knooppunt.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlNode](../../xmlnode/)
* Klasse [XmlComment](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)