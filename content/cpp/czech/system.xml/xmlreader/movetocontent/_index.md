---
title: MoveToContent()
second_title: Aspose.Slides pro C++ API dokumentace
description: "Kontroluje, zda je aktuální uzel obsahovým (ne-bílým textem, CDATA, Element, EndElement, EntityReference nebo EndEntity) uzlem. Pokud uzel není obsahovým uzlem, čtečka přejde na další obsahový uzel nebo na konec souboru. Přeskakuje uzly následujícího typu: ProcessingInstruction, DocumentType, Comment, Whitespace nebo SignificantWhitespace."
type: docs
weight: 833
url: /cs/system.xml/xmlreader/movetocontent/
---
## XmlReader::MoveToContent() metoda


Kontroluje, zda je aktuální uzel obsahový (ne-bílý text, **CDATA**, **Element**, **EndElement**, **EntityReference** nebo **EndEntity**) uzel. Pokud není uzel obsahovým uzlem, čtečka přeskočí na další obsahový uzel nebo na konec souboru. Přeskakuje uzly následujícího typu: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace** nebo **SignificantWhitespace**.

```cpp
virtual XmlNodeType System::Xml::XmlReader::MoveToContent()
```


### Návratová hodnota

Hodnota [XmlReader::get_NodeType](../get_nodetype/) aktuálního uzlu nalezeného metodou nebo [XmlNodeType::None](../../xmlnodetype/), pokud čtečka dosáhla konce vstupního proudu.

## Viz také

* Výčet [XmlNodeType](../../xmlnodetype/)
* Třída [XmlReader](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)