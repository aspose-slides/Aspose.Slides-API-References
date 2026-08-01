---
title: get_Name()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert de gekwalificeerde naam van het knooppunt, wanneer overschreven in een afgeleide klasse.
type: docs
weight: 1
url: /nl/system.xml/xmlnode/get_name/
---
## XmlNode::get_Name() methode

Retourneert de gekwalificeerde naam van het knooppunt, wanneer overschreven in een afgeleide klasse.

```cpp
virtual String System::Xml::XmlNode::get_Name()=0
```

### Retourwaarde

De gekwalificeerde naam van het knooppunt.

## Opmerkingen

De geretourneerde naam is afhankelijk van de [XmlNode::get_NodeType](../get_nodetype/) van het knooppunt:

| Type | Naam |
| --- | --- |
| [Attribute](../../../system/attribute/)| De gekwalificeerde naam van het attribuut. |
| CDATA | #cdata-section |
| Comment | #comment |
| Document | #document |
| DocumentFragment | #document-fragment |
| DocumentType | De naam van het documenttype. |
| Element | De gekwalificeerde naam van het element. |
| Entity | De naam van de entiteit. |
| EntityReference | De naam van de gerefereerde entiteit. |
| Notation | De naam van de notatie. |
| ProcessingInstruction | Het doel van de verwerkingsinstructie. |
| [Text](../../../system.text/)| #text |
| Whitespace | #whitespace |
| SignificantWhitespace | #significant-whitespace |
| [XmlDeclaration](../../xmldeclaration/)| #xml-declaration |

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [XmlNode](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)