---
title: ReadElementContentAsObject()
second_title: Riferimento API di Aspose.Slides per C++
description: Legge l'elemento corrente e restituisce il contenuto come un Object.
type: docs
weight: 469
url: /it/system.xml/xmlreader/readelementcontentasobject/
---
## XmlReader::ReadElementContentAsObject() metodo

Legge l'elemento corrente e restituisce il contenuto come un [Object](../../../system/object/).

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAsObject()
```

### Valore restituito

Un oggetto boxed del tipo più appropriato. Il valore [XmlReader::get_ValueType](../get_valuetype/) determina il tipo appropriato. Se il contenuto è tipizzato come tipo di elenco, questo metodo restituisce un array di oggetti boxed del tipo appropriato.

## XmlReader::ReadElementContentAsObject(String, String) metodo

Verifica che il nome locale e l'URI dello spazio dei nomi specificati corrispondano a quelli dell'elemento corrente, quindi legge l'elemento corrente e restituisce il contenuto come un [Object](../../../system/object/).

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAsObject(String localName, String namespaceURI)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Il nome locale dell'elemento. |
| namespaceURI | [String](../../../system/string/) | L'URI dello spazio dei nomi dell'elemento. |

### Valore restituito

Un oggetto boxed del tipo più appropriato. Il valore [XmlReader::get_ValueType](../get_valuetype/) determina il tipo appropriato. Se il contenuto è tipizzato come tipo di elenco, questo metodo restituisce un array di oggetti boxed del tipo appropriato.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [XmlReader](../)
* Classe [String](../../../system/string/)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)