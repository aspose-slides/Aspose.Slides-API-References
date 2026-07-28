---
title: MoveToContent()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: "Sprawdza, czy bieżący węzeł jest węzłem zawartości (tekst niebiałej spacji, CDATA, Element, EndElement, EntityReference lub EndEntity). Jeśli węzeł nie jest węzłem zawartości, czytnik przeskakuje do następnego węzła zawartości lub końca pliku. Pomija węzły następującego typu: ProcessingInstruction, DocumentType, Comment, Whitespace lub SignificantWhitespace."
type: docs
weight: 833
url: /pl/system.xml/xmlreader/movetocontent/
---
## XmlReader::MoveToContent() metoda


Sprawdza, czy bieżący węzeł jest węzłem zawartości (tekst niebędący białą spacją, **CDATA**, **Element**, **EndElement**, **EntityReference** lub **EndEntity**) . Jeśli węzeł nie jest węzłem zawartości, czytnik pomija do następnego węzła zawartości lub końca pliku. Pomija węzły następującego typu: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace** lub **SignificantWhitespace**.

```cpp
virtual XmlNodeType System::Xml::XmlReader::MoveToContent()
```


### Wartość zwracana

Wartość [XmlReader::get_NodeType](../get_nodetype/) bieżącego węzła znalezionego przez metodę lub [XmlNodeType::None](../../xmlnodetype/), jeśli czytnik osiągnął koniec strumienia wejściowego.

## Zobacz także

* Enum [XmlNodeType](../../xmlnodetype/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)