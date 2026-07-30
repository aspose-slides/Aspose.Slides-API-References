---
title: Item()
second_title: Riferimento API Aspose.Slides per C++
description: Recupera il nodo all'indice specificato nel XmlNamedNodeMap.
type: docs
weight: 53
url: /it/system.xml/xmlnamednodemap/item/
---
## XmlNamedNodeMap::Item(int32_t) method

Recupera il nodo all'indice specificato nel [XmlNamedNodeMap](../).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::Item(int32_t index)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | La posizione dell'indice del nodo da recuperare da [XmlNamedNodeMap](../). L'indice parte da zero; quindi, l'indice del primo nodo è 0 e l'indice dell'ultimo nodo è [XmlNamedNodeMap::get_Count](../get_count/) - 1. |

### Valore di ritorno

Il [XmlNode](../../xmlnode/) all'indice specificato. Se **index** è minore di 0 o maggiore o uguale al valore [XmlNamedNodeMap::get_Count](../get_count/), viene restituito **nullptr**.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../../xmlnode/)
* Classe [XmlNamedNodeMap](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)