---
title: get_LocalName()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce il nome locale del nodo corrente.
type: docs
weight: 27
url: /it/system.xml/xmltextreader/get_localname/
---
## XmlTextReader::get_LocalName() metodo


Restituisce il nome locale del nodo corrente.

```cpp
String System::Xml::XmlTextReader::get_LocalName() override
```


### Valore di ritorno

Il nome del nodo corrente senza il prefisso. Per esempio, **LocalName** è **book** per l'elemento **<bk:book>**. Per i tipi di nodo che non hanno un nome (come **[Text](../../../system.text/)**, **Comment**, e così via), questo metodo restituisce [String::Empty](../../../system/string/empty/).

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [XmlTextReader](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)