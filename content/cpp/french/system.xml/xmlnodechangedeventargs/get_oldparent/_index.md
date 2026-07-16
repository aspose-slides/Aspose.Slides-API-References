---
title: get_OldParent()
second_title: Aspose.Slides for C++ Référence de l'API
description: "Renvoie la valeur de XmlNode::get_ParentNode avant le début de l'opération."
type: docs
weight: 27
url: /fr/system.xml/xmlnodechangedeventargs/get_oldparent/
---
## XmlNodeChangedEventArgs::get_OldParent() méthode

Renvoie la valeur de [XmlNode::get_ParentNode](../../xmlnode/get_parentnode/) avant le début de l'opération.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNodeChangedEventArgs::get_OldParent()
```

### Valeur de retour

La valeur du **ParentNode** avant le début de l'opération. Cette méthode renvoie **nullptr** si le nœud n'avait pas de parent. Pour les nœuds d'attribut, cette méthode renvoie la valeur [XmlAttribute::get_OwnerElement](../../xmlattribute/get_ownerelement/).

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../../xmlnode/)
* Classe [XmlNodeChangedEventArgs](../)
* Espace de noms [System::Xml](../../)
* Library [Aspose.Slides](../../../)