---
title: get_NewParent()
second_title: Aspose.Slides voor C++ API-referentie
description: "Retourneert de waarde van XmlNode::get_ParentNode nadat de bewerking is voltooid."
type: docs
weight: 40
url: /nl/system.xml/xmlnodechangedeventargs/get_newparent/
---
## XmlNodeChangedEventArgs::get_NewParent() methode

Retourneert de waarde van de [XmlNode::get_ParentNode](../../xmlnode/get_parentnode/) nadat de bewerking is voltooid.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNodeChangedEventArgs::get_NewParent()
```

### Retourwaarde

De waarde van de **ParentNode** nadat de bewerking is voltooid. Deze methode retourneert **nullptr** als het knooppunt wordt verwijderd. Voor attribuutknopen retourneert deze methode de [XmlAttribute::get_OwnerElement](../../xmlattribute/get_ownerelement/) waarde.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlNode](../../xmlnode/)
* Klasse [XmlNodeChangedEventArgs](../)
* Naamruimte [System::Xml](../../)
* Library [Aspose.Slides](../../../)