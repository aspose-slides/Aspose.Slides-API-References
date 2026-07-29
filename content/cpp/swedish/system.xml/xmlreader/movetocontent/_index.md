---
title: MoveToContent()
second_title: Aspose.Slides för C++ API-referens
description: "Kontrollerar om den aktuella noden är ett innehåll (icke-blankstegstext, CDATA, Element, EndElement, EntityReference eller EndEntity) nod. Om noden inte är en innehållsnod hoppar läsaren fram till nästa innehållsnod eller slutet på filen. Den hoppar över noder av följande typ: ProcessingInstruction, DocumentType, Comment, Whitespace eller SignificantWhitespace."
type: docs
weight: 833
url: /sv/system.xml/xmlreader/movetocontent/
---
## XmlReader::MoveToContent() metod


Kontrollerar om den aktuella noden är ett innehåll (icke-blankstegstext, **CDATA**, **Element**, **EndElement**, **EntityReference** eller **EndEntity**) nod. Om noden inte är en innehållsnod hoppar läsaren fram till nästa innehållsnod eller slutet på filen. Den hoppar över noder av följande typ: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace** eller **SignificantWhitespace**.

```cpp
virtual XmlNodeType System::Xml::XmlReader::MoveToContent()
```


### Returvärde

The [XmlReader::get_NodeType](../get_nodetype/) value of the current node found by the method or [XmlNodeType::None](../../xmlnodetype/) if the reader has reached the end of the input stream.

## Se även

* Enum [XmlNodeType](../../xmlnodetype/)
* Klass [XmlReader](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)