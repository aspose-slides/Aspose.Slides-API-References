---
title: MoveToContent()
second_title: Aspose.Slides voor C++ API-referentie
description: "Controleert of het huidige knooppunt een content (niet-witte ruimte tekst, CDATA, Element, EndElement, EntityReference, of EndEntity) knooppunt is. Als het knooppunt geen content-knooppunt is, springt de lezer vooruit naar het volgende content-knooppunt of het einde van het bestand. Het slaat knooppunten over van het volgende type: ProcessingInstruction, DocumentType, Comment, Whitespace, of SignificantWhitespace."
type: docs
weight: 833
url: /nl/system.xml/xmlreader/movetocontent/
---
## XmlReader::MoveToContent() methode

Controleert of het huidige knooppunt een content (niet-witte ruimte tekst, **CDATA**, **Element**, **EndElement**, **EntityReference**, of **EndEntity**) knooppunt is. Als het knooppunt geen content-knooppunt is, springt de lezer vooruit naar het volgende content-knooppunt of het einde van het bestand. Het slaat knooppunten over van het volgende type: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace**, of **SignificantWhitespace**.

```cpp
virtual XmlNodeType System::Xml::XmlReader::MoveToContent()
```

### Retourwaarde

De [XmlReader::get_NodeType](../get_nodetype/) waarde van het huidige knooppunt gevonden door de methode of [XmlNodeType::None](../../xmlnodetype/) als de lezer het einde van de invoerstroom heeft bereikt.

## Zie ook

* Enum [XmlNodeType](../../xmlnodetype/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)