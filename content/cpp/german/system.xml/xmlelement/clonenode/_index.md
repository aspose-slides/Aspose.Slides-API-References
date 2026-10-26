---
title: CloneNode()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt ein Duplikat dieses Knotens.
type: docs
weight: 196
url: /de/system.xml/xmlelement/clonenode/
---
## XmlElement::CloneNode(bool) Methode


Erstellt ein Duplikat dieses Knotens.

```cpp
SharedPtr<XmlNode> System::Xml::XmlElement::CloneNode(bool deep) override
```


### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| deep | **bool** | **true** zum rekursiven Klonen des Teilbaums unter dem angegebenen Knoten; **false** zum Klonen nur des Knotens selbst (und seiner Attribute, falls der Knoten ein [XmlElement](../) ist). |

### Rückgabewert

Der geklonte Knoten.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlElement](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)