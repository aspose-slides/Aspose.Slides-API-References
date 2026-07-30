---
title: RemoveNamedItem()
second_title: Riferimento API Aspose.Slides per C++
description: Rimuove il nodo da XmlNamedNodeMap.
type: docs
weight: 40
url: /it/system.xml/xmlnamednodemap/removenameditem/
---
## XmlNamedNodeMap::RemoveNamedItem(String) metodo

Rimuove il nodo da [XmlNamedNodeMap](../).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::RemoveNamedItem(String name)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | [String](../../../system/string/) | Il nome qualificato del nodo da rimuovere. Il nome viene confrontato con il valore [XmlNode::get_Name](../../xmlnode/get_name/) del nodo corrispondente. |

### Valore di ritorno

Il [XmlNode](../../xmlnode/) rimosso da questo [XmlNamedNodeMap](../) o **nullptr** se non è stato trovato un nodo corrispondente.

## XmlNamedNodeMap::RemoveNamedItem(String, String) metodo

Rimuove un nodo con i valori [XmlNode::get_LocalName](../../xmlnode/get_localname/) e [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) corrispondenti.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::RemoveNamedItem(String localName, String namespaceURI)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Il nome locale del nodo da rimuovere. |
| namespaceURI | [String](../../../system/string/) | L'URI del namespace del nodo da rimuovere. |

### Valore di ritorno

Il [XmlNode](../../xmlnode/) rimosso o **nullptr** se non è stato trovato un nodo corrispondente.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../../xmlnode/)
* Classe [String](../../../system/string/)
* Classe [XmlNamedNodeMap](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)