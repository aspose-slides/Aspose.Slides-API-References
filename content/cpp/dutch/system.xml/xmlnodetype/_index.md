---
title: XmlNodeType
second_title: Aspose.Slides voor C++ API-referentie
description: Specificeert het type van de node.
type: docs
weight: 833
url: /nl/system.xml/xmlnodetype/
---
## XmlNodeType enum

Specificeert het type van de node.

```cpp
enum class XmlNodeType
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| None | 0 | Dit wordt geretourneerd door de [XmlReader](../xmlreader/) als er geen **Read**-methode is aangeroepen. |
| Element | 1 | Een element (bijvoorbeeld, **<item>**). |
| Attribute | 2 | Een attribuut (bijvoorbeeld, **id='123'**). |
| Text | 3 | De tekstinhoud van een node. Een [XmlNodeType::Text](./) node kan geen kindknopen hebben. Het kan verschijnen als een kindnode van de [XmlNodeType::Attribute](./), [XmlNodeType::DocumentFragment](./), [XmlNodeType::Element](./) en [XmlNodeType::EntityReference](./) nodes. |
| CDATA | 4 | Een CDATA-sectie (bijvoorbeeld, **my escaped text**). |
| EntityReference | 5 | Een verwijzing naar een entiteit (bijvoorbeeld, **&num;**). |
| Entity | 6 | Een entiteitsdeclaratie (bijvoorbeeld, **<!ENTITY...>**). |
| ProcessingInstruction | 7 | Een verwerkingsinstructie (bijvoorbeeld, **<?pi test?>**). |
| Comment | 8 | Een opmerking (bijvoorbeeld, ****). |
| Document | 9 | Een documentobject dat, als de wortel van de documentboom, toegang biedt tot het volledige XML-document. |
| DocumentType | 10 | De documenttype-declaratie, aangegeven door de volgende tag (bijvoorbeeld, **<!DOCTYPE...>**). |
| DocumentFragment | 11 | Een documentfragment. |
| Notation | 12 | Een notatie in de documenttype-declaratie (bijvoorbeeld, **<!NOTATION...>**). |
| Whitespace | 13 | Witruimte tussen markup. |
| SignificantWhitespace | 14 | Witruimte tussen markup in een gemengd inhoudsmodel of witruimte binnen de **xml:space="preserve"**-scope. |
| EndElement | 15 | Een eind-element-tag (bijvoorbeeld, ****). |
| EndEntity | 16 | Geretourneerd wanneer [XmlReader](../xmlreader/) het einde van de entiteitsvervanging bereikt als gevolg van een aanroep naar [XmlReader::ResolveEntity](../xmlreader/resolveentity/). |
| XmlDeclaration | 17 | De XML-declaratie (bijvoorbeeld, **<?xml version='1.0'?>**). De [XmlNodeType::XmlDeclaration](./) node moet de eerste node in het document zijn. Het kan geen kinderen hebben. Het is een kind van de [XmlNodeType::Document](./) node. Het kan attributen hebben die versie- en codering-informatie leveren. |

## Zie ook

* Naamruimte [System::Xml](../)
* Bibliotheek [Aspose.Slides](../../)