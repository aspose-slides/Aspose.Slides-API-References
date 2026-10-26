---
title: get_LocalName()
second_title: Aspose.Slides per C++ – Riferimento API
description: Quando viene sovrascritto in una classe derivata, ottiene il nome locale del nodo corrente.
type: docs
weight: 40
url: /it/system.xml/xmlreader/get_localname/
---
## XmlReader::get_LocalName() metodo

Quando sovrascritto in una classe derivata, restituisce il nome locale del nodo corrente.

```cpp
virtual String System::Xml::XmlReader::get_LocalName()=0
```

### Valore di ritorno

Il nome del nodo corrente con il prefisso rimosso. Per esempio, **LocalName** è **book** per l'elemento **<bk:book>**. Per i tipi di nodo che non hanno un nome (come **[Text](../../../system.text/)**, **Comment**, e così via), questo metodo restituisce [String::Empty](../../../system/string/empty/).

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [XmlReader](../)
* Namespace [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)