---
title: ReadStartElement()
second_title: Riferimento API di Aspose.Slides per C++
description: Verifica che il nodo corrente sia un elemento e avanza il lettore al nodo successivo.
type: docs
weight: 846
url: /it/system.xml/xmlreader/readstartelement/
---
## XmlReader::ReadStartElement() metodo


Verifica che il nodo corrente sia un elemento e avanza il lettore al nodo successivo.

```cpp
virtual void System::Xml::XmlReader::ReadStartElement()
```


## XmlReader::ReadStartElement(String) metodo


Verifica che il nodo di contenuto corrente sia un elemento con il valore [XmlReader::get_Name](../get_name/) specificato e avanza il lettore al nodo successivo.

```cpp
virtual void System::Xml::XmlReader::ReadStartElement(String name)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | [String](../../../system/string/) | Il nome qualificato dell'elemento. |

## XmlReader::ReadStartElement(String, String) metodo


Verifica che il nodo di contenuto corrente sia un elemento con i valori [XmlReader::get_LocalName](../get_localname/) e [XmlReader::get_NamespaceURI](../get_namespaceuri/) specificati e avanza il lettore al nodo successivo.

```cpp
virtual void System::Xml::XmlReader::ReadStartElement(String localname, String ns)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| localname | [String](../../../system/string/) | Il nome locale dell'elemento. |
| ns | [String](../../../system/string/) | L'URI dello spazio dei nomi dell'elemento. |

## Vedi anche

* Classe [XmlReader](../)
* Classe [String](../../../system/string/)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)