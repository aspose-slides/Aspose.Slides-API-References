---
title: CloneNode()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een duplicaat van dit knooppunt.
type: docs
weight: 157
url: /nl/system.xml/xmldeclaration/clonenode/
---
## XmlDeclaration::CloneNode(bool) method


Maakt een duplicaat van dit knooppunt.

```cpp
SharedPtr<XmlNode> System::Xml::XmlDeclaration::CloneNode(bool deep) override
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| deep | **bool** | **true** om de onderliggende subboom van de opgegeven node recursief te klonen; **false** om alleen de node zelf te klonen. Omdat [XmlDeclaration](../) nodes geen kinderen hebben, bevat de gekloonde node altijd de gegevenswaarde, ongeacht de instellingen van de parameter. |

### Retourwaarde

De gekloonde node.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlNode](../../xmlnode/)
* Klasse [XmlDeclaration](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)