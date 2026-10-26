---
title: get_NewParent()
second_title: Riferimento API di Aspose.Slides per C++
description: "Restituisce il valore di XmlNode::get_ParentNode al termine dell'operazione."
type: docs
weight: 40
url: /it/system.xml/xmlnodechangedeventargs/get_newparent/
---
## XmlNodeChangedEventArgs::get_NewParent() metodo

Restituisce il valore di [XmlNode::get_ParentNode](../../xmlnode/get_parentnode/) al termine dell'operazione.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNodeChangedEventArgs::get_NewParent()
```

### Valore restituito

Il valore di **ParentNode** al termine dell'operazione. Questo metodo restituisce **nullptr** se il nodo è stato rimosso. Per i nodi attributo, questo metodo restituisce il valore [XmlAttribute::get_OwnerElement](../../xmlattribute/get_ownerelement/).

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../../xmlnode/)
* Classe [XmlNodeChangedEventArgs](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)