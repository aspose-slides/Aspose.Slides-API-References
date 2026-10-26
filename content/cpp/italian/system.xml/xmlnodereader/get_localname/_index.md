---
title: get_LocalName()
second_title: Aspose.Slides per C++ Riferimento API
description: Restituisce il nome locale del nodo corrente.
type: docs
weight: 27
url: /it/system.xml/xmlnodereader/get_localname/
---
## XmlNodeReader::get_LocalName() metodo


Restituisce il nome locale del nodo corrente.

```cpp
String System::Xml::XmlNodeReader::get_LocalName() override
```

### Valore di ritorno

Il nome del nodo corrente con il prefisso rimosso. Ad esempio, **LocalName** è **book** per l'elemento **<bk:book>**. Per i tipi di nodo che non hanno un nome (come **[Text](../../../system.text/)**, **Comment**, e così via), questo metodo restituisce [String::Empty](../../../system/string/empty/).

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [XmlNodeReader](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)