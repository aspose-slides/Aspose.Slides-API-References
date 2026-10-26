---
title: ReadString()
second_title: Riferimento API di Aspose.Slides per C++
description: Legge il contenuto di un elemento o di un nodo di testo come stringa.
type: docs
weight: 391
url: /it/system.xml/xmlnodereader/readstring/
---
## XmlNodeReader::ReadString() metodo

Legge il contenuto di un elemento o di un nodo di testo come stringa.

```cpp
String System::Xml::XmlNodeReader::ReadString() override
```

### Valore restituito

Il contenuto dell'elemento o del nodo di tipo testo (Può includere CDATA, [Text](../../../system.text/) nodi e così via). Può essere una stringa vuota se il lettore è posizionato su qualcosa di diverso da un elemento o nodo di testo, o se non c'è più contenuto testuale da restituire nel contesto corrente. Nota: Il nodo di testo può essere sia un elemento sia un nodo di testo attributo.

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [XmlNodeReader](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)