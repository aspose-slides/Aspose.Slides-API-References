---
title: IsStartElement()
second_title: Riferimento API di Aspose.Slides per C++
description: "Chiama XmlReader::MoveToContent e verifica se il nodo di contenuto corrente è un tag di inizio o un tag di elemento vuoto."
type: docs
weight: 885
url: /it/system.xml/xmlreader/isstartelement/
---
## XmlReader::IsStartElement() method

Chiama [XmlReader::MoveToContent](../movetocontent/) e verifica se il nodo di contenuto corrente è un tag di inizio o un tag di elemento vuoto.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement()
```

### Valore di ritorno

**true** se [XmlReader::MoveToContent](../movetocontent/) trova un tag di inizio o un tag di elemento vuoto; **false** se è stato trovato un tipo di nodo diverso da [XmlNodeType::Element](../../xmlnodetype/).

## XmlReader::IsStartElement(String) method

Chiama [XmlReader::MoveToContent](../movetocontent/) e verifica se il nodo di contenuto corrente è un tag di inizio o un tag di elemento vuoto e se il valore [XmlReader::get_Name](../get_name/) dell'elemento trovato corrisponde all'argomento fornito.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement(String name)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | [String](../../../system/string/) | La stringa confrontata con il valore **Name** dell'elemento trovato. |

### Valore di ritorno

**true** se il nodo risultante è un elemento e il valore **Name** corrisponde alla stringa specificata. **false** se è stato trovato un tipo di nodo diverso da [XmlNodeType::Element](../../xmlnodetype/) o se il valore **Name** dell'elemento non corrisponde alla stringa specificata.

## XmlReader::IsStartElement(String, String) method

Chiama [XmlReader::MoveToContent](../movetocontent/) e verifica se il nodo di contenuto corrente è un tag di inizio o un tag di elemento vuoto e se i valori [XmlReader::get_LocalName](../get_localname/) e [XmlReader::get_NamespaceURI](../get_namespaceuri/) dell'elemento trovato corrispondono alle stringhe fornite.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement(String localname, String ns)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| localname | [String](../../../system/string/) | La stringa da confrontare con il valore **LocalName** dell'elemento trovato. |
| ns | [String](../../../system/string/) | La stringa da confrontare con il valore **NamespaceURI** dell'elemento trovato. |

### Valore di ritorno

**true** se il nodo risultante è un elemento. **false** se è stato trovato un tipo di nodo diverso da [XmlNodeType::Element](../../xmlnodetype/) o se i valori **LocalName** e **NamespaceURI** dell'elemento non corrispondono alle stringhe specificate.

## Vedi anche

* Classe [XmlReader](../)
* Classe [String](../../../system/string/)
* Namespace [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)