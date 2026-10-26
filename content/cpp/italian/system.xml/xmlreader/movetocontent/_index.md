---
title: MoveToContent()
second_title: Riferimento API Aspose.Slides per C++
description: "Verifica se il nodo corrente è un nodo di contenuto (testo non bianco, CDATA, Element, EndElement, EntityReference o EndEntity). Se il nodo non è un nodo di contenuto, il lettore avanza al nodo di contenuto successivo o alla fine del file. Salta i nodi del seguente tipo: ProcessingInstruction, DocumentType, Comment, Whitespace o SignificantWhitespace."
type: docs
weight: 833
url: /it/system.xml/xmlreader/movetocontent/
---
## XmlReader::MoveToContent() metodo

Verifica se il nodo corrente è un nodo di contenuto (testo non bianco, **CDATA**, **Element**, **EndElement**, **EntityReference** o **EndEntity**). Se il nodo non è un nodo di contenuto, il lettore avanza al nodo di contenuto successivo o alla fine del file. Salta i nodi dei seguenti tipi: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace** o **SignificantWhitespace**.

```cpp
virtual XmlNodeType System::Xml::XmlReader::MoveToContent()
```

### Valore di ritorno

Il valore [XmlReader::get_NodeType](../get_nodetype/) del nodo corrente trovato dal metodo o [XmlNodeType::None](../../xmlnodetype/) se il lettore ha raggiunto la fine del flusso di input.

## Vedi anche

* Enum [XmlNodeType](../../xmlnodetype/)
* Classe [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)