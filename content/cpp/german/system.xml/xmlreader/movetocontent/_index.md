---
title: MoveToContent()
second_title: Aspose.Slides für C++ API-Referenz
description: "Überprüft, ob der aktuelle Knoten ein Inhaltsknoten (nicht-Leerzeichen-Text, CDATA, Element, EndElement, EntityReference oder EndEntity) ist. Wenn der Knoten kein Inhaltsknoten ist, springt der Reader zum nächsten Inhaltsknoten oder zum Dateiende. Er überspringt Knoten des folgenden Typs: ProcessingInstruction, DocumentType, Comment, Whitespace oder SignificantWhitespace."
type: docs
weight: 833
url: /de/system.xml/xmlreader/movetocontent/
---
## XmlReader::MoveToContent() Methode

Prüft, ob der aktuelle Knoten ein Inhaltsknoten (nicht-Leerzeichen-Text, **CDATA**, **Element**, **EndElement**, **EntityReference** oder **EndEntity**) ist. Wenn der Knoten kein Inhaltsknoten ist, springt der Leser zum nächsten Inhaltsknoten oder zum Dateiende. Er überspringt Knoten des folgenden Typs: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace** oder **SignificantWhitespace**.

```cpp
virtual XmlNodeType System::Xml::XmlReader::MoveToContent()
```

### Rückgabewert

Der [XmlReader::get_NodeType](../get_nodetype/) Wert des aktuellen Knotens, der von der Methode gefunden wurde, oder [XmlNodeType::None](../../xmlnodetype/), wenn der Leser das Ende des Eingabestreams erreicht hat.

## Siehe auch

* Enum [XmlNodeType](../../xmlnodetype/)
* Klasse [XmlReader](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)