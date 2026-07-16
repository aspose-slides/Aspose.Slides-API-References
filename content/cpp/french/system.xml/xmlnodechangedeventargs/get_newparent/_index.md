---
title: get_NewParent()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Renvoie la valeur de XmlNode::get_ParentNode après la fin de l'opération."
type: docs
weight: 40
url: /fr/system.xml/xmlnodechangedeventargs/get_newparent/
---
## XmlNodeChangedEventArgs::get_NewParent() méthode


Renvoie la valeur de [XmlNode::get_ParentNode](../../xmlnode/get_parentnode/) après la fin de l'opération.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNodeChangedEventArgs::get_NewParent()
```


### Valeur de retour

La valeur de **ParentNode** après la fin de l'opération. Cette méthode renvoie **nullptr** si le nœud est supprimé. Pour les nœuds d'attribut, cette méthode renvoie la valeur [XmlAttribute::get_OwnerElement](../../xmlattribute/get_ownerelement/).

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../../xmlnode/)
* Classe [XmlNodeChangedEventArgs](../)
* Espace de noms [System::Xml](../../)
* Library [Aspose.Slides](../../../)