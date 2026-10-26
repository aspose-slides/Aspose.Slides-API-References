---
title: GetElementsByTagName()
second_title: Riferimento API di Aspose.Slides per C++
description: "Restituisce un XmlNodeList contenente un elenco di tutti gli elementi discendenti che corrispondono al XmlElement::get_Name specificato."
type: docs
weight: 287
url: /it/system.xml/xmlelement/getelementsbytagname/
---
## XmlElement::GetElementsByTagName(String) metodo


Restituisce un [XmlNodeList](../../xmlnodelist/) contenente un elenco di tutti gli elementi discendenti che corrispondono al [XmlElement::get_Name](../get_name/) specificato.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlElement::GetElementsByTagName(String name)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | [String](../../../system/string/) | Il tag di nome da confrontare. Questo è un nome qualificato. Viene confrontato con il valore **get_Name** del nodo corrispondente. L'asterisco (*) è un valore speciale che corrisponde a tutti i tag. |

### Valore di ritorno

Un [XmlNodeList](../../xmlnodelist/) contenente un elenco di tutti i nodi corrispondenti. L'elenco è vuoto se non ci sono nodi corrispondenti.

## XmlElement::GetElementsByTagName(String, String) metodo


Restituisce un [XmlNodeList](../../xmlnodelist/) contenente un elenco di tutti gli elementi discendenti che corrispondono ai valori [XmlElement::get_LocalName](../get_localname/) e [XmlElement::get_NamespaceURI](../get_namespaceuri/) specificati.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlElement::GetElementsByTagName(String localName, String namespaceURI)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Il nome locale da confrontare. L'asterisco (*) è un valore speciale che corrisponde a tutti i tag. |
| namespaceURI | [String](../../../system/string/) | L'URI dello spazio dei nomi da confrontare. |

### Valore di ritorno

Un [XmlNodeList](../../xmlnodelist/) contenente un elenco di tutti i nodi corrispondenti. L'elenco è vuoto se non ci sono nodi corrispondenti.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNodeList](../../xmlnodelist/)
* Classe [String](../../../system/string/)
* Classe [XmlElement](../)
* Namespace [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)