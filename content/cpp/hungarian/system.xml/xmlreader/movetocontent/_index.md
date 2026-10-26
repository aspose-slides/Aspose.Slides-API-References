---
title: MoveToContent()
second_title: Aspose.Slides C++ API referencia
description: "Ellenőrzi, hogy a jelenlegi csomópont tartalom (nem üres hely karakterekkel rendelkező szöveg, CDATA, Element, EndElement, EntityReference vagy EndEntity) csomópont-e. Ha a csomópont nem tartalomcsomópont, az olvasó átugrik a következő tartalomcsomópontra vagy a fájl végére. Kihagyja a következő típusú csomópontokat: ProcessingInstruction, DocumentType, Comment, Whitespace vagy SignificantWhitespace."
type: docs
weight: 833
url: /hu/system.xml/xmlreader/movetocontent/
---
## XmlReader::MoveToContent() metódus

Ellenőrzi, hogy a jelenlegi csomópont tartalom (nem üres hely karakterekkel rendelkező szöveg, **CDATA**, **Element**, **EndElement**, **EntityReference**, vagy **EndEntity**) csomópont-e. Ha a csomópont nem tartalom csomópont, az olvasó átugrik a következő tartalom csomópontra vagy a fájl végére. Kihagyja a következő típusú csomópontokat: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace**, vagy **SignificantWhitespace**.

```cpp
virtual XmlNodeType System::Xml::XmlReader::MoveToContent()
```

### Visszatérési érték

A [XmlReader::get_NodeType](../get_nodetype/) érték a metódus által megtalált jelenlegi csomópont értéke vagy [XmlNodeType::None](../../xmlnodetype/), ha az olvasó elérte a bemeneti adatfolyam végét.

## Lásd még

* Enum [XmlNodeType](../../xmlnodetype/)
* Osztály [XmlReader](../)
* Névtér [System::Xml](../../)
* Library [Aspose.Slides](../../../)