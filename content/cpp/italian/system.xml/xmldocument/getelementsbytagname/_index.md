---
title: GetElementsByTagName()
second_title: Riferimento API Aspose.Slides per C++
description: Restituisce un XmlNodeList contenente un elenco di tutti gli elementi discendenti che corrispondono al nome specificato.
type: docs
weight: 443
url: /it/system.xml/xmldocument/getelementsbytagname/
---
## XmlDocument::GetElementsByTagName(String) metodo

Restituisce un [XmlNodeList](../../xmlnodelist/) contenente un elenco di tutti gli elementi discendenti che corrispondono al nome specificato.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlDocument::GetElementsByTagName(String name)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | [String](../../../system/string/) | Il nome qualificato da confrontare. Viene confrontato con il valore **get_Name** del nodo corrispondente. Il valore speciale **"*"** corrisponde a tutti i tag. |

### Valore restituito

Un [XmlNodeList](../../xmlnodelist/) contenente un elenco di tutti i nodi corrispondenti. Se nessun nodo corrisponde a **name**, la collezione restituita sarà vuota.

## XmlDocument::GetElementsByTagName(String, String) metodo

Restituisce un [XmlNodeList](../../xmlnodelist/) contenente un elenco di tutti gli elementi discendenti che corrispondono al [XmlDocument::get_LocalName](../get_localname/) e al [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) specificati.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlDocument::GetElementsByTagName(String localName, String namespaceURI)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Il LocalName da confrontare. Il valore speciale **"*"** corrisponde a tutti i tag. |
| namespaceURI | [String](../../../system/string/) | NamespaceURI da confrontare. |

### Valore restituito

Un [XmlNodeList](../../xmlnodelist/) contenente un elenco di tutti i nodi corrispondenti. Se nessun nodo corrisponde ai **localName** e **namespaceURI** specificati, la collezione restituita sarà vuota.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNodeList](../../xmlnodelist/)
* Classe [String](../../../system/string/)
* Classe [XmlDocument](../)
* Spazio dei nomi [System::Xml](../../)
* Library [Aspose.Slides](../../../)