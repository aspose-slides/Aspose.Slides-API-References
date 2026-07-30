---
title: get_OldParent()
second_title: Riferimento API Aspose.Slides per C++
description: "Restituisce il valore di XmlNode::get_ParentNode prima che l'operazione iniziasse."
type: docs
weight: 27
url: /it/system.xml/xmlnodechangedeventargs/get_oldparent/
---
## XmlNodeChangedEventArgs::get_OldParent() Metodo

Restituisce il valore di [XmlNode::get_ParentNode](../../xmlnode/get_parentnode/) prima che l'operazione iniziasse.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNodeChangedEventArgs::get_OldParent()
```


### Valore di ritorno

Il valore di **ParentNode** prima che l'operazione iniziasse. Questo metodo restituisce **nullptr** se il nodo non aveva un genitore. Per i nodi attributo, questo metodo restituisce il valore [XmlAttribute::get_OwnerElement](../../xmlattribute/get_ownerelement/).

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../../xmlnode/)
* Classe [XmlNodeChangedEventArgs](../)
* Namespace [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)