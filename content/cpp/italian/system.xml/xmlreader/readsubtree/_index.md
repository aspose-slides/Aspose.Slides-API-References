---
title: ReadSubtree()
second_title: Riferimento API Aspose.Slides per C++
description: Restituisce una nuova istanza di XmlReader che può essere usata per leggere il nodo corrente e tutti i suoi discendenti.
type: docs
weight: 963
url: /it/system.xml/xmlreader/readsubtree/
---
## XmlReader::ReadSubtree() metodo


Restituisce una nuova istanza di [XmlReader](../) che può essere utilizzata per leggere il nodo corrente e tutti i suoi discendenti.

```cpp
virtual SharedPtr<XmlReader> System::Xml::XmlReader::ReadSubtree()
```


### Valore di ritorno

Una nuova istanza di lettore XML impostata su [ReadState::Initial](../../readstate/). Chiamare il metodo [XmlReader::Read](../read/) posiziona il nuovo lettore sul nodo che era corrente prima della chiamata al metodo [XmlReader::ReadSubtree](./).

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlReader](../)
* Spazio dei nomi [System::Xml](../../)
* Library [Aspose.Slides](../../../)