---
title: SetNamedItem()
second_title: Aspose.Slides per il riferimento API di C++
description: "Aggiunge un XmlNode usando il risultato di XmlNode::get_Name."
type: docs
weight: 14
url: /it/system.xml/xmlattributecollection/setnameditem/
---
## XmlAttributeCollection::SetNamedItem(SharedPtr\<XmlNode\>) metodo


Aggiunge un [XmlNode](../../xmlnode/) usando il risultato del suo [XmlNode::get_Name](../../xmlnode/get_name/).

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttributeCollection::SetNamedItem(SharedPtr<XmlNode> node) override
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | Un nodo attributo da memorizzare in questa raccolta. Il nodo sarà successivamente accessibile utilizzando il nome del nodo. Se un nodo con quel nome è già presente nella raccolta, viene sostituito da quello nuovo; altrimenti, il nodo viene aggiunto alla fine della raccolta. |

### Valore di ritorno

If the **node** replaces an existing node with the same name, the **old node** is returned; otherwise, the **added node** is returned.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlAttributeCollection](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)