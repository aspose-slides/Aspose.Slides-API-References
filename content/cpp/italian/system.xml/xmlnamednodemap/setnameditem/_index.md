---
title: SetNamedItem()
second_title: Riferimento API di Aspose.Slides per C++
description: "Aggiunge un XmlNode usando il valore di XmlNode::get_Name."
type: docs
weight: 27
url: /it/system.xml/xmlnamednodemap/setnameditem/
---
## XmlNamedNodeMap::SetNamedItem(SharedPtr\<XmlNode\>) metodo

Aggiunge un [XmlNode](../../xmlnode/) usando il suo valore [XmlNode::get_Name](../../xmlnode/get_name/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::SetNamedItem(SharedPtr<XmlNode> node)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | Un [XmlNode](../../xmlnode/) da memorizzare nel [XmlNamedNodeMap](../). Se un nodo con quel nome è già presente nella mappa, viene sostituito da quello nuovo. |

### Return Value

Se il **node** sostituisce un nodo esistente con lo stesso nome, viene restituito il nodo vecchio; altrimenti, viene restituito **nullptr**.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../../xmlnode/)
* Classe [XmlNamedNodeMap](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)