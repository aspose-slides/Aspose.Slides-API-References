---
title: get_OldParent()
second_title: Aspose.Slides voor C++ API-referentie
description: "Retourneert de waarde van de XmlNode::get_ParentNode voordat de bewerking begon."
type: docs
weight: 27
url: /nl/system.xml/xmlnodechangedeventargs/get_oldparent/
---
## XmlNodeChangedEventArgs::get_OldParent() methode


Retourneert de waarde van de [XmlNode::get_ParentNode](../../xmlnode/get_parentnode/) voordat de bewerking begon.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNodeChangedEventArgs::get_OldParent()
```


### Retourwaarde

De waarde van de **ParentNode** voordat de bewerking begon. Deze methode retourneert **nullptr** als het knooppunt geen ouder had. Voor attribuutknooppunten retourneert deze methode de [XmlAttribute::get_OwnerElement](../../xmlattribute/get_ownerelement/) waarde.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlNode](../../xmlnode/)
* Klasse [XmlNodeChangedEventArgs](../)
* Naamruimte [System::Xml](../../)
* Library [Aspose.Slides](../../../)