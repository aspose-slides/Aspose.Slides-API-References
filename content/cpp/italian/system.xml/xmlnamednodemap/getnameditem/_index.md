---
title: GetNamedItem()
second_title: Riferimento API di Aspose.Slides per C++
description: Recupera un XmlNode specificato per nome.
type: docs
weight: 14
url: /it/system.xml/xmlnamednodemap/getnameditem/
---
## XmlNamedNodeMap::GetNamedItem(String) metodo


Recupera un [XmlNode](../../xmlnode/) specificato per nome.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::GetNamedItem(String name)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | [String](../../../system/string/) | Il nome qualificato del nodo da recuperare. Viene confrontato con il valore [XmlNode::get_Name](../../xmlnode/get_name/) del nodo corrispondente. |

### Valore di ritorno

Un [XmlNode](../../xmlnode/) con il nome specificato o **nullptr** se non viene trovato un nodo corrispondente.

## XmlNamedNodeMap::GetNamedItem(String, String) metodo


Recupera un nodo con i valori corrispondenti [XmlNode::get_LocalName](../../xmlnode/get_localname/) e [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::GetNamedItem(String localName, String namespaceURI)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Il nome locale del nodo da recuperare. |
| namespaceURI | [String](../../../system/string/) | L'Uniform Resource Identifier (URI) dello spazio dei nomi del nodo da recuperare. |

### Valore di ritorno

Un [XmlNode](../../xmlnode/) con il nome locale e l'URI dello spazio dei nomi corrispondenti o **nullptr** se non viene trovato un nodo corrispondente.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../../xmlnode/)
* Classe [String](../../../system/string/)
* Classe [XmlNamedNodeMap](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)