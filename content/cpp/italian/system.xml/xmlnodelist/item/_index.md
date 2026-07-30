---
title: Item()
second_title: Riferimento API di Aspose.Slides per C++
description: Recupera un nodo all'indice specificato.
type: docs
weight: 14
url: /it/system.xml/xmlnodelist/item/
---
## XmlNodeList::Item(int32_t) metodo


Recupera un nodo all'indice specificato.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNodeList::Item(int32_t index)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | L'indice basato su zero nella lista dei nodi. |

### Valore di ritorno

Il [XmlNode](../../xmlnode/) con l'indice specificato nella collezione. Se **index** è maggiore o uguale al numero di nodi nella lista, questo restituisce **nullptr**.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../../xmlnode/)
* Classe [XmlNodeList](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)