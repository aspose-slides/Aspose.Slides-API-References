---
title: PrependChild()
second_title: Riferimento API di Aspose.Slides per C++
description: Aggiunge il nodo specificato all'inizio dell'elenco dei nodi figlio per questo nodo.
type: docs
weight: 261
url: /it/system.xml/xmlattribute/prependchild/
---
## XmlAttribute::PrependChild(SharedPtr\<XmlNode\>) metodo

Aggiunge il nodo specificato all'inizio dell'elenco dei nodi figlio per questo nodo.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::PrependChild(SharedPtr<XmlNode> newChild) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | Il [XmlNode](../../xmlnode/) da aggiungere. Se è un [XmlDocumentFragment](../../xmldocumentfragment/), l'intero contenuto del frammento di documento viene spostato nell'elenco dei figli di questo nodo. |

### Valore di ritorno

Il [XmlNode](../../xmlnode/) aggiunto.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../../xmlnode/)
* Classe [XmlAttribute](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)